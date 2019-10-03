<script>
    export let placeholderMsg;
    export let name;
    export let classProp;
    export let inputType;
</script>

<style lang="scss">
@import './FormInput.scss';
</style>

<input type="{ inputType }" class="{ classProp }" name="{ name }" placeholder="{ placeholderMsg }" />
