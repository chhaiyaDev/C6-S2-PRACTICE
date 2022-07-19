<template>
    <div class="form">
        <div class="firstName">
            <input type="text" placeholder="First Name">
        </div>
        <div class="lastName">
            <input type="text" placeholder="Last Name">
        </div>
        <div class="comment">
            <input type="text" placeholder="Comment">
        </div>
        <button>ADD</button>
    </div>
</template>

<style>
    .form{
        width: 50%;
        padding: 15px;
        margin: auto;
        box-shadow: rgba(0, 0, 0, 0.16) 0px 3px 6px, rgba(0, 0, 0, 0.23) 0px 3px 6px;
    }

    input{
        width: 98%;
        height: 5vh;
        margin-top: 15px;  
    }

    button{
        margin-top: 15px;
        height: 5vh;
        width: 100%
    }
</style>