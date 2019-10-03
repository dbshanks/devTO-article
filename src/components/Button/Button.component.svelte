<script>
    export let btnType;
    export let classType;
    export let buttonMsg;
</script>

<style src="./Button.styles.scss"></style>

<button 
    btnType="{ btnType }" 
    class="{classType}">
    { buttonMsg }
    <i class="fas fa-chevron-right"></i>
</button>