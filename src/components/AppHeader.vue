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
    <header>
        <div class="container">
            <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="Logo DC Comics" />
            </div>
            <nav>
              <ul>
                  <li v-for="item in navItems" :key="item.title">
                  <a href="">{{ item.title }}</a>
                  </li>
              </ul>
            </nav>
        </div>
      </header>
    </template>

<style scoped lang="scss">
@use "../style/partials/mixin" as *;
@use "../style/partials/variables" as *;

    header {
        padding: 1rem;
        background-color: $white;
        z-index: 999;


        .container {
            @include flex();
        }
        .logo{
            text-align: center;

            img {
                max-width: 80px;
            }
        }
        ul {
            @include flex();
            list-style-type: none;
            gap: 1rem;
        }
        a{
            text-decoration: none;
            color: $header-color;
        }
        a:hover {
            color: $banner-bg-color;
        }
    }

</style>