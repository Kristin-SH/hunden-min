<template>
    <section id="Contact">
        <div class="container">
            <h2>Kontakt oss</h2>
            <div class="info">
                <div class="info-container">
                    <div class="info-card">
                        <div class="info-icon">
                            <span class="material-symbols-outlined">
                            phone_android
                            </span>
                        </div>
                        <div class="info-details">
                            <p>+ (47) 465 41 107</p>
                            <p>+ (47) 920 15 088</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="info-icon">
                            <span class="material-symbols-outlined">
                            pin_drop
                            </span>
                        </div>
                        <div class="info-details">
                            <p>Ulvikveien 23</p>
                            <p>Den røde låven</p>
                            <p>3150 Tolvsrød</p>
                        </div>
                    </div>
                    <div class="info-card">
                        <div class="info-icon">
                            <span class="material-symbols-outlined">
                            mail
                            </span>
                        </div>
                        <div class="info-details">
                            <p>post@hundenmin.no</p>
                            
                        </div>
                    </div>
                </div>
            </div>

            <p>Hvis du ikke finner det du leter etter så fyll ut skjemaet nedenfor, så svarer vi deg så snart vi kan!</p><br>
        </div>
        <div class="contact">
            <form action="http://localhost:5173">
                <input type="text" name="navn" id="navn" aria-label="Navn" placeholder="Ditt navn"><br>
                <input type="text" name="tlf" id="tlf" placeholder="Ditt telefonnummer"><br>
                <input type="text" name="epost" id="epost" placeholder="Din e-postadresse"><br>
                <textarea name="melding" id="melding" cols="20" rows="10" placeholder="Din melding"></textarea>
                <br>
                <button type="submit" name="submit" id="submit" value="SEND OSS NÅ!">Send inn nå</button>
            </form>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'MainContact'
    }
</script>

<style scoped>
section {
    background-color: var(--main-lblue);
}

.material-symbols-outlined {
    vertical-align: bottom;
    font-size: 4rem;
  font-variation-settings:
  'FILL' 0,
  'wght' 300,
  'GRAD' 0,
  'opsz' 40
}

.info-container {
    display: flex;
    align-items: center;
    justify-content:space-evenly;
    flex-wrap: wrap;
    margin: 30px 0;
}

.info-card {
    display:flex;
    align-items: center;
    justify-content: center;
    min-width: 2rem;
}

.info-card p {
    font-family: "Oswald";
}

.info-icon {
    padding: 10px;
}

.info-details {
    padding: 10px;
    text-align: left;
}

.contact input, textarea {
    font-family: "Roboto";
    font-size: 18px;
    padding: 10px;
    margin: 0.8rem;
    min-width: 30%;
    /* min-width: 350px; */
    border: 1px solid var(--main-grey);
    background-color: rgb(240, 240, 240);    
}

button {
    font-family: "Roboto";
    font-size: 1rem;
    padding: 10px;
    width:auto;
}

.contact input:focus,
.contact textarea:focus  {
    background-color: white;
    box-shadow: var(--shadow);
    outline: none;
}

</style>