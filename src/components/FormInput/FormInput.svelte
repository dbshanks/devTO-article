<script>
    import './FormInput.scss';

    export let placeholderMsg;
    export let name;
    export let classProp;
    export let inputType;
</script>

<style src="./FormInput.scss"></style>

<input type="{ inputType }" class="{ classProp }" name="{ name }" placeholder="{ placeholderMsg }" />
