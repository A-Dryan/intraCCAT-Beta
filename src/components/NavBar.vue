<template>
    <div>
        <div class="container-bar">
        <div class="container-bar__titulo">C C A T</div>
        <a class="logout" href="index.html"><img src="IMG/icologout.png"></a>
        </div>
    </div>
</template>

<style scoped>
.container-bar{
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    background-color: rgb(7, 156, 243);
    height: 8%;
    width: 100%;
    justify-content: space-between;
    align-items: center;
    color: #fff;
}
.container-bar__titulo{
width: 13.55%;
height: 100%;
display: flex;
justify-content: center;
align-items: center;
background:rgb(16, 139, 211);
cursor: default;
}
.container-bar a{
    padding: 0% 1.5%;
    height: 100%;
display: flex;
justify-content: center;
align-items: center;
background-color: rgb(211, 29, 29);
}

</style>
