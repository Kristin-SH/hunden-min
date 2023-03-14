<template>
    <section>
        <div class="hero-container">
            <div class="hero-info">
                <div class="hero-text">
                    <h1>Den naturlige veien til veltilpasset hund</h1>
                </div>
                <div class="hero-buttons">
                    <div class="hero-button">
                        <button class="btn">Click me!</button>
                    </div>
                    <div class="hero-button">
                        <button class="btn">Click me!</button>
                    </div>
                </div>
            </div>

        </div>
    </section>
</template>

<script>
    export default {
        name: 'MainHero'
    }
</script>

<style scoped>
section {
    background-color: var(--main-green);
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url('..\assets\images\dogs.jpg');
    height: 600px;
    background-position: 0px 30%;
    background-repeat: no-repeat;
    background-size: cover;
}

.hero-container {
    width: 80%;
    margin: auto;
}

.hero-info {
    padding-top: 200px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 2rem;
    
}

.hero-text {
    color: white;
}

.hero-text h1 {
    line-height: 7rem;
}
.hero-buttons {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 2rem;
}

.hero-button {

}

@media screen and (max-width: 800px) {
    section {
    background-position: 45% 30%;
    /* position: relative; */
    }

    .hero-text h1 {
    font-size: 3rem;
    line-height: 4rem;
    }

}

@media screen and (max-width: 500px) {
    .hero-text h1 {
    font-size: 2.5rem;
    line-height: 3rem;
    }

}

</style>