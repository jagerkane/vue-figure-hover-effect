<template>
    <div class="show-container">
        <div class="container">
            <figure-item v-bind:content="test1"></figure-item>
            <figure-item v-bind:content="test2"></figure-item>
        </div>
        <div class="container">
            <figure-item v-bind:content="test3"></figure-item>
            <figure-item v-bind:content="test4"></figure-item>
        </div>
        <div class="container">
            <figure-item v-bind:content="test5"></figure-item>
            <figure-item v-bind:content="test6"></figure-item>
        </div>
        <div class="container">
            <figure-item v-bind:content="test7"></figure-item>
            <figure-item v-bind:content="test8"></figure-item>
        </div>
        <div class="container">
            <figure-item v-bind:content="test9"></figure-item>
            <figure-item v-bind:content="test10"></figure-item>
        </div>
    </div>
</template>
<script>
    import FigureItem from 'vue-figure-hover-effect'
    import image8 from '../assets/images/hero_8.jpg'
    import image1 from '../assets/images/hero_1.jpg'
    import image2 from '../assets/images/hero_2.jpg'
    import image3 from '../assets/images/hero_3.jpg'
    import image4 from '../assets/images/hero_4.jpg'
    import image5 from '../assets/images/hero_5.jpg'
    import image6 from '../assets/images/hero_6.jpg'
    import image7 from '../assets/images/hero_7.jpg'
    import image9 from '../assets/images/hero_9.jpg'
    import image10 from '../assets/images/hero_10.jpg'
    export default {
        components:{
            'figure-item':FigureItem,
        },
        data(){
            return{
                test1:{
                    image:image1,
                    css:"effect-up-slide",
                    pLst:['从此刻开始，战场由我一人主宰'],
                    title:"呂布",
                    subTitle:'三分之地',
                },
                test2:{
                    image:image2,
                    css:"effect-left-slide",
                    pLst:['天机难测，却尽在我掌中','在我面前耍花样?哼~太嫩了'],
                    title:"司馬懿",
                    subTitle:'三分之地',
                },
               
                test3:{
                    image:image3,
                    css:"effect-milo",
                    pLst:['离家太远会忘掉故乡，杀人太多会忘掉自己'],
                    title:"花木兰",
                    subTitle:'星计划',
                },
                test4:{
                    image:image4,
                    css:"effect-chico",
                    pLst:['是狐不是祸，最近就流行我这样高冷的主角。'],
                    title:"李白",
                    subTitle:'上陽臺',
                },
                test5:{
                    image:image5,
                    css:"effect-sarah",
                    pLst:[],
                    title:"浪一夏",
                    subTitle:'',
                },
                test6:{
                    image:image6,
                    css:"effect-dexter",
                    pLst:['打个赌，阴险的敌人，永远不敢来场堂堂正正的对决'],
                    title:"梅西",
                    subTitle:'裴擒虎',
                },
                test7:{
                    image:image7,
                    css:"effect-remeo",
                    pLst:['随心所欲，这就是俺的人生信条'],
                    title:"夏侯惇",
                    subTitle:'不羁之风',
                },
                test8:{
                    image:image8,
                    css:"effect-sadie",
                    pLst:['盾山的设定是修复的长城的机器人，所以他的台词也是机器人的预言，咱们人类是听不懂的!'],
                    title:"盾山",
                    subTitle:'极冰防御线',
                },
                test9:{
                    image:image9,
                    css:"effect-dexter",
                    pLst:['这是最好的时代，这是最坏的时代，我们一无所有，我们巍然矗立.'],
                    title:"李信",
                    subTitle:'谋世之战',
                },
                test10:{
                    image:image10,
                    css:"effect-zoe",
                    pLst:['身躯已然冰封，灵魂仍旧火热。美貌是种罪孽，暴雪也无法掩埋。白梅落下之日，归去故里之时。'],
                    title:"王昭君",
                    subTitle:'凤凰于飞',
                }
            }
        }
    }
</script>

<style>
    @import '../assets/css/index.css';
    @import '../assets/css/figure.css';
</style>

