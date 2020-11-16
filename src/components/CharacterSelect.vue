<template>
<section>
    <img alt="Vue logo" src="../assets/pf2e-logo.png">
    <div class="buttons">
        <b-button type="is-dark" size="is-large" @click="startNewCharacter" expanded> New Character </b-button>
        <b-button type="is-dark" size="is-large" expanded> Load Character </b-button>
    </div>
</section>
</template>

<script>
export default {
    name: 'CharacterSelect',
    data() {
        return {
            sectionComplete: false,
            newCharacter: false
        }
    },
    methods: {
        startNewCharacter() {
            this.sectionComplete = true;
            this.newCharacter = true;
            alert("new character");
        },

        startLoadCharacter() {
            this.sectionComplete = true;
        }
    }
}
</script>

<style scoped>
.buttons {
    margin: 0;
    width: 600px;
    position: absolute;
    top: 35%;
    left: 50%;
    -ms-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
}
</style>