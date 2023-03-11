<template>
    <section>
        <div class="container">
            <div class="contact">
               <p>+47 465 41 107</p>
               <p>post@hundenmin.no</p>
            </div>
            <nav>
                <div class="logo">
                    <img src="/src/assets/images/hundenmin-weblogo.png" alt="Hunden min">
                </div>
                <div class="link">
                    <ul>
                        <li><a href="#">våre kurs</a></li>
                        <li><a href="#">instruktører</a></li>
                        <li><a href="#">kontakt oss</a></li>
                        <li><a href="#">pålogging</a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </section>
</template>

<script>
    export default {
    name: 'MainHeader',
        
    }
</script>

<style scoped>

section {
    background-color: white;
    padding: 0;
}

.container {
    font-family: "Oswald";
    display: flex;
    flex-direction: column;
    margin-bottom: 0;
}

.logo img {
    padding: 10px 0;
    width: 100%;
    min-width: 150px;
    height: auto;
}

.contact {
    display: flex;
    justify-content: space-between;
    border-bottom: 1px solid grey;
}

nav {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
    justify-items: space-between;
    align-items: center;
}

.link a {
    display: block;
    text-align: center;
    padding: 6px;
    color: black;
    border-bottom: 2px white solid;
}

.link a:hover {
    color: var(--main-orange);
    border-bottom: 2px var(--main-orange) solid;
}

</style>