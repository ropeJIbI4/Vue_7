<template>
    <div class="header center">
        <div class="header__nav">
            <div>
                <img class="header__logo" src="/public/assets/Logo_header.png" alt="">
            </div>
            <div class="header__link">
                <a href="#">Home</a>
                <a href="#">Project</a>
                <a href="#">Blog</a>
            </div>
        </div>
    </div>
</template>

<style>
a {
    text-decoration: none;
    color: black;
}

.center {
    padding-left: calc(50% - 560px);
    padding-right: calc(50% - 560px);
}

.header__nav {
    padding-right: 10px;
    padding-left: 10px;
    display: flex;
    justify-content: space-between;
}

.header__link {
    display: flex;
    padding-top: 15px;
    gap: 15px;
}

.header__logo {
    width: 176px;
}
</style>