<template>
<nav>
    <ul>
        <li>
            <router-link to="/App">Home</router-link>
        </li>
        <li>
            <router-link to="/BloggComponent">Blog</router-link>
        </li>
        <li>
            <router-link to="/MediaComponent">Media</router-link>
        </li>
        <li>
            <router-link to="/ContactComponent">Contact</router-link>
        </li>
        <li>
            <router-link to="/AboutComponent">About</router-link>
        </li>
        <li>
            <router-link to="/ScheduleComponent">schedule</router-link>
        </li>
        <RouterView />
    </ul>
</nav>
</template>

<script>
export default {
    name: 'HeaderComponent',

}
</script>

<style>
nav {

    width: 100%;
    line-height: 1.4em;
}

ul {
    list-style: none;
    background-color: transparent;
    display: block;
    width: 100%;
    margin: 0;
    padding: 0;
    text-align: justify;
    margin-bottom: -1.4em;
}

ul:after {
    content: "";

    color: rgb(20, 182, 33);
    display: inline-block;
    width: 100%;
}

li {
    display: inline-block;
    display: flexbox;
    flex-direction: row;
    flex-wrap: wrap;
    text-decoration: none;
    font-size: larger;
    margin: 4%;
    padding: auto;
    font: size 25px;
    font-style: normal;
    color: rgb(20, 182, 33);
    text-decoration: none;

}

nav>a {
    font-weight: bold;
    color: #2c3e50;
    /* &.router-link-exact-active {
    color: #42b983;
  } */
}

html {
    position: relative;
    min-height: 100%;
}

body {
    color: rgb(228, 147, 41);
    margin-bottom: 60px;
    background-image: url('/public/pictures/mikeBill5.png');
    background-size: cover;
    background-repeat: no-repeat;
    /* Margin bottom by footer height */
}
</style>
