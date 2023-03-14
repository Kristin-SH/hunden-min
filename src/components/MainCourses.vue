<template>
    <section id="Courses">
        <div class="container">
            <div class="text">
                <h2>Våre Kurs</h2>
                <p>Hos oss står hund og eiers behov i første rekke. Våre instruktører er opptatte av at hund og eier skal bli sett og veiledet, slik at dere lykkes med treningen.</p><br>
            </div>

            <!-- Valpekurs-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/valpekurs.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                        <h3>Valpekurs</h3>
                        <p>Er du fersk hundeeier eller blir du eier av en valp i nær framtid? I vår kursoversikt finner du valpekurs som kan lære deg å unngå de typiske nybegynnerfeilene som hundeeier, samt sikre valpen din mange positive førstegangsopplevelser.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingValp ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingValp" class="course-moreinfo">
                    <p>Hva lærer du og valpen gjennom et valpekurs? Gjennom et valpekurs kan du få en  hverdagslydig hund. På valpekurset vil du blant annet kunne lære hvordan du skal  få valpen til å slutte å tisse og bæsje inne, hvordan unngå at valpen biter i alt og alle, hvordan du får hunden til å gå pent i bånd, hvordan aktivisere valpen oghvordan du får valpen til å komme på innkalling. I tillegg er valpekurset en finarena for valpen din å bli sosialisert med andre hunder og mennesker. På kurset jobber man systematisk og metodisk med ulike, enkle øvelser. Ofte bruker man positive belønningsmetoder og godbiter i innlæringen.</p>
                    <p>Det er vanlig at valpekurs holdes utendørs. Noen valpekurs tilbyr også  miljøtrening der man lærer opp valpen til å håndtere ulike omgivelser (foreksempel kjøpesenter). Normalt har hundeskoler aldersgrense for et valpekurs10-12 uker. Ofte strekker kurset seg over flere uker med en treningskveld per   uke. Som regel er det relativt få deltakere på valpekursene, slik at alle hunder   og hundeeiere får individuell oppfølging og valpene slipper å ha for mange å   forholde seg til samtidig.</p>
                    <p>Et valpekurs vil gjøre deg sikker i hvilken retning du ønsker å dresserehunden. Du slipper dermed at din usikkerhet smitter over på hunden slik at det  blir vanskelig å lære hunden de gode vanene du ønsker at den skal ha. Ved at du   er tydelig, rolig og oppmundtrende, legger du de beste forutsetningene for å   lykkes med treningen av valpen din.</p>
                    <h3>Kursavgift: 1.595,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        <li>Valpekurs er 2 dager i uken</li>
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Barn og Hund-kurs-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/barn_hund_kurs.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                        <h3>Barn Og Hund-Kurs</h3>
                        <p>Samspillet mellom de minste i familien og hunden er svært viktig! Barn og hund kursene våre fokuserer på mestring, lek og samarbeidet mellom barn og hund. Anbefalt aldersgruppe: 8 - 12 år </p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingBarn ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingBarn" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Massasje- og stretchingkurs-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/massasje.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                        <h3>Massasje- og stretchingkurs</h3>
                        <p>Å lære massasje og stretching er godt for både hund og eier da du knytter enda nærmere bånd mellom deg og hunden, og ikke minst er det forebyggende i en aktiv hverdag. Teknikkene du lærer på kurset kan brukes både som avslapping eller etter en god treningsøkt og konkurranse.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingStretch ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingStretch" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Rallylydighet-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/rally.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                            <h3>Rallylydighet</h3>
                            <p>Rallylydighet er en hundesport som kombinerer øvelser fra lydighet, agility og freestyle og passer for alle hunder, uavhengig av rase og alder.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingRally ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingRally" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Agilitykurs-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/agility.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                            <h3>Agility</h3>
                        <p>Agility er en spennende og fartsfylt hundesport, der både hund og hundefører(handler) må være på høyden for å lykkes. Agility er dessuten en av de raskestvoksende sportsgrenene for hunder, også i Norge.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingAgility ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingAgility" class="course-moreinfo">
                    <p>Hva lærer du og valpen gjennom et valpekurs? Gjennom et valpekurs kan du få en  hverdagslydig hund. På valpekurset vil du blant annet kunne lære hvordan du skal  få valpen til å slutte å tisse og bæsje inne, hvordan unngå at valpen biter i alt og alle, hvordan du får hunden til å gå pent i bånd, hvordan aktivisere valpen oghvordan du får valpen til å komme på innkalling. I tillegg er valpekurset en finarena for valpen din å bli sosialisert med andre hunder og mennesker. På kurset jobber man systematisk og metodisk med ulike, enkle øvelser. Ofte bruker man positive belønningsmetoder og godbiter i innlæringen.</p>
                    
                    <h3>Kursavgift: 1.595,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        <li>Valpekurs er 2 dager i uken</li>
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Unghundkurs-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/unghundkurs.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                            <h3>Unghundkurs </h3>
                            <p>Unghundkurs passer for deg som vil ha en hyggelig og veltilpasset familiehund,for deg som har noen utfordringer med din hund eller for deg som ønsker å drive meden form for hundesport.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingBarn ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingBarn" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Hverdagslydighet-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/lydighet.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                        <h3>Hverdagslydighet</h3>
                        <p>Hverdagslydighet passer for deg som vil ha en hyggelig og veltilpassetfamiliehund, for deg som har noen utfordringer med din hund eller for deg som ønskerå drive med en form for hundesport.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingLydighet ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingLydighet" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

            <!-- Treningsgruppe-->

            <div class="course-container">
                <div class="course">
                    <div class="course-image" style="background-image: url('/src/assets/images/treningsgruppe.jpeg');">
                    </div>
                    <div class="course-info">
                        <div class="course-info-text">
                            <h3>Treningsgruppe</h3>
                        <p>Treningsgruppen er et tilbud der dere kommer når dere har lyst og anledning til å trene på oppsatte dager. Det vil alltid være instruktør tilstede for veiledning og hjelp.</p>
                        </div>
                        <div class="course-info-button">
                            <button @click="isShowingGruppe ^= true" class="btn">Mer informasjon</button>
                        </div>
                    </div>
                </div>
                <div v-show="isShowingGruppe" class="course-moreinfo">
                    
                    <p>Det vil legges opp til enkle øvelser og lek slik at barna synes treningen er gøy og full av mestring. Instruktøren vil tilrettelegge for at dette skal være en positiv og lærerik trening for familiens yngste medlemmer. </p>
                    <h3>Kursavgift: 1.495,-</h3>
                    <ul>
                        <li>Antall hunder på kurset: maks 6 stk</li>
                        <li>Antall kurskvelder: 1 teori og 6 praksis</li>
                        
                    </ul>
                    <h3>Neste kurs er 23.06.23</h3>
                    <h3>Velkommen på kurs!</h3>

                    <button class="btn">Meld deg på her</button>
                </div>
            </div>

        </div>
    </section>
</template>

<script>

export default {
    name: 'MainCourses',

    data() {
        return {
            isShowingValp:false,
            isShowingBarn:false,
            isShowingStretch:false,
            isShowingRally:false,
            isShowingAgility:false,
            isShowingUng:false,
            isShowingLydighet:false,
            isShowingGruppe:false
        }
    }
}

</script>

<style  scoped>
section {
    background-color: var(--main-lblue);
}
.course-container {
    margin-bottom: 50px;
    box-shadow: var(--shadow);
}
.course {
    display: flex;
    flex-direction: row;
    background-color: white;
}

.course-image {
    width: 550px;
    min-Height: 100%;
    
    background-size: cover;
    background-position: center;
}

.course-info {
    display: flex;
    flex-direction: column;
    width: 100%;
}

.course-info-text {
    text-align: left;
    padding: 10px;
}

.course-info-button {
    padding: 10px;
    text-align: right;
}

.course-moreinfo {
    background-color: rgb(235, 234, 234);
    padding: 10px 10px 10px 20px;
    text-align: left;
    width: 100%;
    border-top: dashed 1px black;
    box-shadow: var(--shadow);
}

.course-moreinfo p {
    margin-left: 20px;
    font-size: 0.9rem;
    margin-bottom: 10px;
    
}

@media screen and (max-width: 800px) {
    .course {
    flex-direction: column;
    }

    .course-image {
    width: 100%;
    Height: 350px;
    background-image: url('/src/assets/images/agility.jpeg');
    background-size: cover;
    background-position: center center;
    }

    .course-info-button .btn{
        width: 100%;
    }
}
</style>