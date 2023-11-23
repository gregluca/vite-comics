<script>
export default {
    data () {
        return {
            bonusItem: [
                {
                    title:"DIGITAL COMICS"
                },
                {
                    title:"DC MERCHANDISE"
                },
                {
                    title:"SUBSCRIPTION"
                },
                {
                    title:"COMIC SHOP LOCATOR"
                },
                {
                    title:"DC POWER SHOP VISA"
                }
            ]
        }
    }
}
</script>
<template>
    <div class="container">
        <div class="small-container">
            <ul>
                <li v-for="item in bonusItem" :key="item.title"><a href=""></a>{{ item.title }}</li>
            </ul>
        </div>
    </div>
</template>

<style scoped lang="scss">
    .container {
        background-color:hsl(208.67deg 100% 48.82%);
        padding: 30px;
    }
    .small-container {
        width: 80%;
        margin: 0 auto;
    }
    ul {
        display: flex;
        justify-content: space-between;
    }
    li {
        color: white;
        list-style-type: none;
    }

</style>