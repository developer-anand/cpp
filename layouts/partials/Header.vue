<template>
        <header>
          <span>
            <a href="./" >
        <img src="~/assets/logo.png" class="logo" />
            </a>
          </span>
        <ul>
          <li>
            <nuxt-link to="/about">About</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/carrers">Carrers</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/projects">Projects</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/contact">Contact Us</nuxt-link>
          </li>
        </ul>
      </header>
</template>
<style lang="scss" scoped>
    header{
        background: #fff;
        margin-bottom: 0;
        height: 150px;
        color: red;
        width: (100 - 14em);
        padding: 0 7em;
        height:8em;
        display:flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;

        .logo {
            padding: 0;
            margin-bottom: 0;
            float: right;
            width: 350px;
            height: 100px;
            margin-left: 5px;
            top: 50%;
           
        }
        a{
           cursor: pointer;
        }

        ul {
            padding: 0;
            margin-bottom: 0;
            margin: 0;
            list-style: none;
            display: flex;
            flex-direction: row;

            li{ 
                font-size: 1.5em;
                margin-bottom: 0;

                &,a {
                    padding: 1em .5em;

                }
               a {
                   color:black;
                   text-decoration: none;
                }
            }
        }
    }

</style>