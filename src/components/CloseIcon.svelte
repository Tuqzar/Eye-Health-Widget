<script>
    import {createEventDispatcher} from "svelte";
    const dispatcher = createEventDispatcher();

    function onClick() {
        dispatcher('click')
    }
</script>

<style lang="scss">
    button {
        width: 36.92px;
        height: 36.92px;
        background-color: var(--gray);
        border-radius: 50%;
        overflow: hidden;
    }
</style>

<button on:click={onClick}>
    <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
         viewBox="0 0 174.239 174.239">
        <g>
            <path d="M120.83,53.414c-2.917-2.917-7.647-2.917-10.559,0L87.12,76.568L63.969,53.414c-2.917-2.917-7.642-2.917-10.559,0   s-2.917,7.642,0,10.559l23.151,23.153L53.409,110.28c-2.917,2.917-2.917,7.642,0,10.559c1.458,1.458,3.369,2.188,5.28,2.188   c1.911,0,3.824-0.729,5.28-2.188L87.12,97.686l23.151,23.153c1.458,1.458,3.369,2.188,5.28,2.188c1.911,0,3.821-0.729,5.28-2.188   c2.917-2.917,2.917-7.642,0-10.559L97.679,87.127l23.151-23.153C123.747,61.057,123.747,56.331,120.83,53.414z"
                  fill="#000000"/>
        </g>
    </svg>
</button>
