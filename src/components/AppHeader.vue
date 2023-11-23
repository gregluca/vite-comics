<script>
export default {
    data() {
        return {
            navItems: [
                {
                    title: "CHARACTERS"
                },
                {
                    title:"COMICS"
                },
                {
                    title:"MOVIES"
                },
                {
                    title:"TV"
                },
                {
                    title:"GAMES"
                },
                {
                    title:"COLLECTIBLES"
                },
                {
                    title:"VIDEOS"
                },
                {
                    title:"FANS"
                },
                {
                    title:"NEWS"
                },
                {
                    title:"SHOP"
                },
            ]
        }
    }
}
</script>

<template>
<div class="container">
    <div class="small-container">
        <header>
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <nav>
                <li v-for="item in navItems" :key="item.title"><a href="">{{ item.title }}</a></li>
            </nav>
        </header>
    </div>
</div>

</template>

<style scoped lang="scss">
.container {
    margin-top: 60px;
    background-color: white;
}
.small-container {
    width: 80%;
    margin: 0 auto;
}
    header {
        padding: 20px;
        display: flex;
        justify-content: space-between;

        .logo{
            text-align: center;

            img {
                max-width: 80px;
            }
        }
        nav {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 1rem;
        }
        li {
            list-style-type: none;
        }
        a {
            text-decoration: none;
            color: black;

            &:hover {
                color: #0082f9;
            }
        }
    }

</style>