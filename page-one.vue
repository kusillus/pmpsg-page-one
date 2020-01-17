<template>
    <div class="mf-wrapper-page">
        hola soy la página 1
        <span class="message">
            {{saludo}}
        </span>
    </div>
</template>

<script>
export default {
    // name: 'DemoExternalComponent',
    data(){
        return {
            saludo: 'Hola amiguitos bienvenidos a mi componente.'
        }
    }

}
</script>

<style lang="scss">
.mf-wrapper-page{
    background: orange;
    width: 100%;
    .message{
        animation: changeColor 1s infinite alternate;
    }
}
@keyframes changeColor {
    to {
        background-color: yellow;
    }
    from {
        background-color: yellowgreen;
    }
}
</style>