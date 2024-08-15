<script setup lang="ts">
</script>

<template>
    <section class="gifts">
        <div class="header" />
        <div class="box">
            <p>Wir freuen uns sehr, dass ihr mit uns feiert, und erwarten keine Geschenke.</p>
            <p>Solltet ihr uns dennoch eine Freude machen wollen, würden wir uns über einen Beitrag zu unserer Flitterwochenkasse freuen.</p>
        </div>
    </section>
</template>

<style scoped>
.gifts {
    box-sizing: border-box;
    max-width: 100vw;
    width: 75rem;
    display: flex;
    flex-direction: column;
    padding: 5rem;
    align-items: flex-start;
    padding-left: 0rem;
}
.header {
    height: 10rem;
    width: 100%;
    background:url('../assets/gift.svg') left center no-repeat;
    background-size: contain;
    max-width: calc(100vw - 6rem);
    margin-bottom: 5rem;
}

.box {
    text-align: left;
    font-size: 1.8rem;
    line-height: 2.4rem;
    margin-bottom: 5rem;
    max-width: 30rem;
}
p, h2 {
    margin-bottom: 2rem;
}

h2 {
    font-family: "mrs-eaves-roman-small-caps", serif;
    font-weight: 400;
    font-style: normal;
    font-size: 1.8rem;
}

.button {
    font-size: 1.8rem;
    display: block;
    padding: 1.5rem 3rem;
    border: 1px solid black;
    text-decoration: none;
}

a.button:hover, a.button:active {
    color: white;
    background: black;
}


@media (max-width: 999px) {
    .gifts {
        align-items: flex-start;
        padding: 5rem;
    }
    .header {
        background-position: left center;
    }

    .box {
        margin-left: 20vw;
        max-width: 50vw;
        margin-bottom: 2rem;
    }

    .button {
        margin-left: 20vw;
        
    }
}

</style>
  