<template>
    <section>
        <div class="container">
            <div class="foot-container">
                <div class="info">
                    <h3>Hundenmin</h3>
                    <p> Vi er en hundeskole som gjør alt for hund og fører! <a href="#Les mer"></a></p>
                    <p><span class="material-symbols-outlined">home</span>
                     Ulvikveien 23, 3150 Tolvsrød</p>
                    <p><span class="material-symbols-outlined">mail</span> post@hundenmin.no</p>
                    <p><span class="material-symbols-outlined">phone_android</span> + (47) 465 41 107</p>
                </div>
                <div class="nyhetsbrev">
                    <h3>Nyhetsbrev</h3>
                    <p>Meld deg på vårt nyhetsbrev!</p>
                    <form action="">
                        <input type="text" name="navn" id="navn" placeholder="Ditt navn"><br>
                        <input type="text" name="epost" id="epost" placeholder="Din epost"><br>
                        <button class="btn" type="submit">Send in</button>
                    </form>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
    export default {
        name: 'MainFooter'
    }
</script>

<style scoped>
section {
    background-color: #252525;
}

.material-symbols-outlined {
    vertical-align: bottom;
    padding-bottom: 5px;
  font-variation-settings:
  'FILL' 0,
  'wght' 400,
  'GRAD' 0,
  'opsz' 48
}

.foot-container {
    display: flex;
    flex-direction: row;
    align-content: center;
    justify-content: center;
    flex-wrap: wrap;
    color: white;
}

.foot-container p {
    font-family: "Roboto";
    font-weight: 400;
}

.info, .nyhetsbrev {
    margin: 10px;
    min-width: 40%;
}
.info {
    text-align: left;
}

.nyhetsbrev {
    text-align: left;
}

.nyhetsbrev input {
    padding: 5px;
    width: 100%;
    font-size: 1rem;
    margin-bottom: 5px;
}

@media (max-width: 800px) {
  .foot-container {
    flex-direction: column;
  }
}

</style>