# solution one

<div class="block" :class="{animate: animatedBlock}"></div>
<button @click="animateBlock">Animate</button>

data() {
    return {
     animatedBlock: false
    }
}

methods: {
    animateBlock() {
    this.animatedBlock = true
}
}


<style>
    .block {
        /* transition:  transform 0.3s ease-out */

    }

    .animated {
        /* transform: translateX(180deg) */
        animation: slide-fade 0.3s ease-out

    }

    @keyframes slide-fade {
        0% - 50% - 100%

    }
</style>

# final solution
use vue animations fro the vue doc
