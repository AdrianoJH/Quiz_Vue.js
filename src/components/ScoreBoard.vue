<template>
   
    <section class="score">
        <h1>Quiz</h1>
        <div class="pontos">
            Player <span>{{ this.winCount }}</span> X <span>{{ this.loseCount }}</span> Computer
        </div>
    </section>
</template>

<script>
export default {
    props: ['winCount', 'loseCount']
}
</script>

<style lang="scss">

    section.score {
        border-bottom: 1px solid black;
        padding: 25px;
        font-size: 18px;
       

        h1 {
            margin-top: -30px;
            margin-bottom: 70px;
            font-size: 35px;
        }

        div.pontos {
            margin-left: 30px;
        }

        span {
            padding: 10px;
            font-weight: bold;
            border: 1px solid black;
        }

    }
</style>