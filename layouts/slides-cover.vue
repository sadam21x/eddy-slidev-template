<template>
    <div class="slidev-layout default sc-container">
        <div class="sc-content">
            <slot />
        </div>
    </div>
</template>

<style scoped>
.sc-container {
    width: 100%;
    height: 100%;
    position: relative;
    background-color: white;
    background-image: url('/img/slides-bg-1.jpg');
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    color: black;
}

.sc-content {
    position: absolute;
    top: 10%;
    left: 25%;
    padding-right: 5rem;
}
</style>
