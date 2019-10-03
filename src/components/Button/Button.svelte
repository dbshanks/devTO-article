<script>
    import './Button.scss';

    export let btnType;
    export let classType;
    export let buttonMsg;
</script>

<style src="./Button.scss"></style>

<button 
    btnType="{ btnType }" 
    class="{classType}">
    { buttonMsg }
    <i class="fas fa-chevron-right"></i>
</button>