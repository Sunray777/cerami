<template>
    <div class="v-main-wrapper">
<p>{{title}}</p>
    </div>
</template>

<script>
export default {
name: 'v-main-wrapper',
components: {}, // дочернии компоненты нашего компонента
props: {},
data(){
    return{
        title: "Main wrapper"
    }
},
computed: {}, // вычисления
methods: {}, // анимации, показы модальных окон, нажатия кнопок итд
watch: {}, // следят за изменениями компонента и что-то делают в случае этого изменения
mounted() {
    console.log('Hello, I am alive') // маунтед это то что выполняется когда компонент полностью загрузился
}


}

</script>

<style>

.v-main-wrapper
{
display: flex;
justify-content: center;
align-items: center;
max-width: 900px;
margin: auto;
}

</style>