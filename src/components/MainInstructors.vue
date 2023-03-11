<template>
    <section>
        <div class="container">          
                <div class="text">
                    <h2>Våre instruktører</h2>
                    <p>Våre instruktører er opptatte av at hund og eier skal bli sett og veiledet, slik at dere lykkes med treningen.</p>
                    <br><br>
                </div>
                <div class="instructor-container">
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Bernt.jpeg" alt="">
                        <h3>Bernt</h3>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ipsam, sapiente optio temporibus nam quibusdam labore vitae officia quae nihil magnam! Excepturi omnis quaerat sunt, vel modi consectetur pariatur sed. Quidem!</p>
                    </div>
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Camilla.jpeg" alt="">
                        <h3>Camilla</h3>
                        <p>Camilla er opptatt av å se den enkelte og tilrettelegge treningen, slik at detblir både morsomt og lærerikt for både hund og eier.Camilla eier Jack Russell tispaMolly. Sammen er de glad i å trene lydighet og deltar gjerne på en og annenutstilling. Hun holder i hovedsak valpekurs hos oss og er opptatt av hvordan du ogdin nye valp skal få en god start.</p>
                    </div>
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Isabell.jpeg" alt="">
                        <h3>Isabell</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Doloremque hic atdistinctio incidunt nulla aliquid excepturi inventore eveniet omnis? Iste sapienteoptio consequuntur maiores reprehenderit et labore sint earum nam.</p>
                    </div>
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Martin.jpeg" alt="">
                        <h3>Martin</h3>
                        <p>Martin har jobbet som instruktør i flere år. Han er opptatt av at hund og førerskal lykkes og ha det gøy med treningen. Personlig har han ei rottweiler tispe på 2år som heter CAP og sammen trener de lydighet, rally, agility  og rundering. Dutreffer Martin i Ulvika når vi har kurs.</p>
                    </div>
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Stine.jpeg" alt="">
                        <h3>Stine</h3>
                        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quas quae nobis nullain nisi corporis, esse dicta ipsam. Sint, necessitatibus.</p>
                    </div>
                    <div class="instructor">
                        <img src="/src/assets/images/Instructors/Staale.jpeg" alt="">
                        <h3>Ståle</h3>
                        <p>Ståle jobber med at hunden skal bli godt sosialisert, jobbe positivt med eier ogha det gøy på trening. Ståle eier Rottweiler tispa ADA. Hu er en tidlig 2017 modell,godt sosialisert og elsker rundering i skogen. Sammen trener agility, rally,lydighet og smeller. Vi er også aktive med Norsk Redningshunder. Han holder kurs forvalper, unghunder og i lydighet.
                    </p>
                    </div>
                </div>
        </div>
    </section>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
.text {
    text-align: center;
}

.instructor-container {
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: center;
    gap: 2rem;
}

.instructor {
    flex-basis: 25%;
    flex-grow: 1;
}

.instructor img {
    height: 500px;
    width: auto;
}

.instructor p {
    font-size: 0.8rem;
    text-align: left;
    padding: 0px 30px;
}
</style>