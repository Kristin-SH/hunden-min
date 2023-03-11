<template>
    <section>
        <div class="container">
            <div class="text">
                <h2>Våre Kurs</h2>
                <p>Hos oss står hund og eiers behov i første rekke. Våre instruktører er opptatte av at hund og eier skal bli sett og veiledet, slik at dere lykkes med treningen.</p><br>
            </div>
            <div class="course-container">
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\valpekurs.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Valpekurs</h3>
                        <p>Er du fersk hundeeier eller blir du eier av en valp i nær framtid? Da er du kommet riktig. I vår kursoversikt finner du valpekurs som kan lære deg å unngå de typiske nybegynnerfeilene som hundeeier, samt sikre valpen din mange positive førstegangsopplevelser.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\barn_hund_kurs.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Barn Og Hund-Kurs</h3>
                        <p>Samspillet mellom de minste i familien og hunden er svært viktig! Barn og hund kursene våre fokuserer på mestring, lek og samarbeidet mellom barn og hund. Anbefalt aldersgruppe: 8 - 12 år </p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="reveal">
                    <h3>Eksempel på "mer info"</h3>
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring.</p>
                    <p>Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer.</p>
                    <p>Kursavgift: 1.495,-</p>
                    <p>Antall hunder på kurset: maks 6 stk</p>
                    <p>Antall kurskvelder: 6 praksis</p>
                    <p>Neste ledig kurs: (<i>Her kommer kurs dato</i>)</p>
                    <p>Velkommen på kurs!</p>
                    <button class="btn">Meld deg på her</button>
                </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\massasje.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Massasje- og stretchingkurs</h3>
                        <p>SKunne du tenke deg å lære hvordan du kan forebygge skader og slitasje på hunden din?</p>
                        <p>Å lære massasje og stretching er godt for både hund og eier da du knytter enda nærmere bånd mellom deg og hunden, og ikke minst er det forebyggende i en aktiv hverdag. Teknikkene du lærer på kurset kan brukes både som avslapping eller etter en god treningsøkt og konkurranse.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="course">
                        <div class="course-img">
                            <img src="src\assets\images\rally.jpeg" alt="">
                        </div>
                        <div class="course-text">
                            <h3>Rallylydighet</h3>
                            <p>Rallylydighet er en hundesport som kombinerer øvelser fra lydighet, agility og freestyle og passer for alle hunder, uavhengig av rase og alder.</p>
                            <br>
                            <button class="btn">Les mer</button>
                        </div>
                    </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\agility.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Agility</h3>
                        <p>Agility er en spennende og fartsfylt hundesport, der både hund og hundefører(handler) må være på høyden for å lykkes.Agility er dessuten en av de raskestvoksende sportsgrenene for hunder, også i Norge. I all enkelhet er agility et kort,men svært fartsfylt hinderløp for hunder, der hundefører bidrar aktivt medstyringskommandoer hunden må utføre for å lykkes.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\unghundkurs.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Unghundkurs </h3>
                        <p>Unghundkurs passer for deg som vil ha en hyggelig og veltilpasset familiehund,for deg som har noen utfordringer med din hund eller for deg som ønsker å drive meden form for hundesport.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\lydighet.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Hverdagslydighet</h3>
                        <p>Hverdagslydighet passer for deg som vil ha en hyggelig og veltilpassetfamiliehund, for deg som har noen utfordringer med din hund eller for deg som ønskerå drive med en form for hundesport.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
                <div class="course">
                    <div class="course-img">
                        <img src="src\assets\images\treningsgruppe.jpeg" alt="">
                    </div>
                    <div class="course-text">
                        <h3>Treningsgruppe</h3>
                        <p>Treningsgruppen er et tilbud der dere kommer når dere har lyst og anledning til å trene på oppsatte dager. Det vil alltid være instruktør tilstede for veiledning og hjelp.</p><br>
                        <button class="btn">Les mer</button>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>

export default {
    name: 'MainCourses'
}

</script>

<style scoped>

section {
    background-color: var(--main-lblue);
}
.text {
    text-align: center;
}

.course-container {
    display: flex;
    flex-direction: column;
    
}

.course {
    display: flex;
    flex-direction: row;
    box-shadow: var(--shadow);
    margin-top: 2rem;
    padding: 5px;
    background-color: white;
}

.course-img {
    width: 30%;
}

.course-img img {
    width: 100%;
    min-height: 100%;
}

.course-text {
    width: 70%;
    text-align: left;
    padding: 0px 10px 0px 20px;
    background-color: white;
}

.btn {
    float: right;
}

/* CSS */


.reveal {
    /* display: none; */
    background-color: rgb(216, 212, 212);
    padding: 10px 10px 10px 20px;
    text-align: left;
    /* box-shadow: var(--shadow); */
}

.reveal p {
    margin-left: 20px;
}
</style>