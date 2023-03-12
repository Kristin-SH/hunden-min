<template>
    <section>
        <div class="container">
            <div class="card-container">
                <div class="card">
                    <h2>Den naturlige veien til en veltilpasset hund</h2>
                    <div class="buttons-container">
                        <div class="buttoni"><button class="btn">finn ut mer</button></div>
                        <div class="buttoni"><button class="btn">bestill kurs nå</button></div>
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
    height: 800px;
    background-position: 0px 30%;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}

h1, h2 {
    text-shadow: 2px 2px 5px #1d1d1d;
    font-family: "Roboto";
}

h1 {
    color: var(--main-green);
    padding: 0;
    margin: 0;
}

h2 {
    color: white;
    padding: 0;
    margin-bottom: 20px;
}


.card-container {
    height: 700px;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    justify-content: center;
}

.card {
    display: flex;
    flex-direction: column;
    align-items: center;
    color: white;
    min-width: 50%;
}

.card p {
    width: 30%;    
}

.buttons-container {
    display: flex;
    gap: 1rem;
}

.buttoni {
    display: block;
    width: 200px;
}

.buttoni .btn {
    width: 100%;
}

</style>