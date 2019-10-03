<script>
    export let placeholderMsg;
    export let name;
    export let classProp;
    export let inputType;
</script>

<style src="./FormInput.styles.scss"></style>

<input type="{ inputType }" class="{ classProp }" name="{ name }" placeholder="{ placeholderMsg }" />
