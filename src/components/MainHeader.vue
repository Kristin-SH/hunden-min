<template>
    <section>
        <div class="container">
            <div class="contact">
               <p><span class="material-symbols-outlined">phone_android</span> +47 465 41 107</p>
               <p><span class="material-symbols-outlined">mail</span><a href="mailto:post@hundenmin.no?subject=Forespørsel%20fra%20nettsiden">post@hundenmin.no</a></p>
            </div>
            <nav>
                <div class="logo">
                    <img src="/src/assets/images/hundenmin-weblogo.png" alt="Hunden min">
                </div>
                <div class="link">
                    <ul>
                        <li><a href="#Courses">våre kurs</a></li>
                        <li><a href="#Instructors">instruktører</a></li>
                        <li><a href="#Contact">kontakt oss</a></li>
                        <li><a href="#">pålogging</a></li>
                    </ul>
                </div>
            </nav>
        </div>
    </section>
</template>

<script>
    export default {
    name: 'MainHeader'
        
    }
</script>

<style scoped>

section {
    background-color: white;
    padding: 0;
}

.container {
    display: flex;
    flex-direction: column;
    margin-bottom: 0;
}

.material-symbols-outlined {
    vertical-align: bottom;
    font-size: 2rem;
  font-variation-settings:
  'FILL' 0,
  'wght' 400,
  'GRAD' 0,
  'opsz' 48
}

.logo img {
    padding: 10px 10px 0 10px;
    width: 100%;
    min-width: 150px;
    height: auto;
}

.contact {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    border-bottom: 1px solid grey;
}

.contact p {
    font-family: "Oswald";
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
    font-family: "Oswald";
    display: block;
    text-align: center;
    padding: 6px;
    color: black;
    border-bottom: 2px white solid;
    text-transform: uppercase;
}

.link a:hover {
    color: var(--main-orange);
    border-bottom: 2px var(--main-orange) solid;
}

@media screen and (max-width: 800px) {
    nav {
    flex-direction: column;
    }

    ul {
    flex-direction: column;
    }

    .link a {
        font-size: 1.4rem;
        padding: 12px;
    }

}


</style>