<template>
<div class="media">
    <div class="item">
        image1
        <img alt="Vue logo" src="/pictures/mikeBill3.png" class="firstimage7">
    </div>
    <div class="item">
        image2
        <img alt="Vue logo" src="/pictures/mikeBill2.png" class="firstimage2">
    </div>
    <div class="item">
        image3
        <img alt="Vue logo" src="/pictures/mikeBill3.png" class="firstimage3">
    </div>
    <div class="item">
        image4
        <img alt="Vue logo" src="/pictures/mikeBill7.png" class="firstimage2">
    </div>
    <div class="item">
        image4
        <img alt="Vue logo" src="/pictures/mikeBill4.png" class="firstimage3">
    </div>
    <div class="item">
        image5
        <img alt="Vue logo" src="/pictures/mikeBill5.png" class="firstimage4">
    </div>
    <div class="item">
        image6
        <img alt="Vue logo" src="/pictures/mikeBill6.png" class="firstimage5">
    </div>
    <div class="item">
        image6
        <img alt="Vue logo" src="/pictures/mikeBill6.png" class="firstimage6">
    </div>
    <div class="item">
        image6
        <img alt="Vue logo" src="/pictures/mikeBill6.png" class="firstimage7">
    </div>
</div>
</template>

<style scoped>
.media {
    display: flex;

    flex-direction: row;
    flex-wrap: wrap;
    justify-content: flex-start;
    align-content: stretch;
    align-items: stretch;
}

.firstimage7 {
    border: 2px;
    border-radius: 15%;
    flex: 1 1 70%;
    height: 70vh;
    width: 60vw;
}

.firstimage2 {
    border: 2px;
    border-radius: 15%;
    height: 40vh;
    width: 30vw;
}

.firstimage3 {
    border: 2px;
    border-radius: 15%;
    height: 40vh;
    width: 30vw;
}

.firstimage6 {
    border: 2px;
    border-radius: 15%;
    align-items: center;
    height: 40vh;
    width: 30vw;
}

.firstimage4 {
    border: 2px;
    border-radius: 15%;
    height: 40vh;
    width: 35vw;
}

.firstimage5 {
    border: 2px;
    border-radius: 15%;
    height: 40vh;
    width: 30vw;
}

.item {

    object-fit: contain;

}
</style>
