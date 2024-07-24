<script>
    export let type = 'primary'
    export let bigify = false
    export let flat = false
</script>

<button class="{type}" class:bigify={bigify} class:flat={flat}>
   <slot></slot>
</button>

<style>
    button{
        border: 0;
        margin: 5px;
        border-radius: 5px;
        width: 100px;
        padding: 7px;
        font-weight: bold;
        box-shadow: 1px 2px 3px rgba(0,0,0,0.2);
    }
    .primary{
        background: #000;
        color: #eee;
    }
    .secondary{
        background: #673ab1;
        color: #eee;
    }
    .bigify{
        width: 400px;
    }
</style>