<template>
    <ul>
        <li><a href="#">home</a></li>
        <li><a href="#">about us</a></li>
        <li><a href="#">services</a></li>
        <li><a href="#">help?</a></li>
    </ul>
</template>

<style>
    ul{
        display: flex;
        align-items: center;
        background: rgb(22, 162, 255);
        width: 90%;
        height: 10vh;
        margin: auto;
        margin-bottom: 15px;
    }

    ul li{
        list-style: none;
    }

    ul li a{
        text-decoration: none;
        text-transform: uppercase;
        color: #ffff;
        margin-left: 30px;
    }
</style>