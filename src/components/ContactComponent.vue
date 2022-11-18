<template>
<p>
    contact
</p>
<div>
    <form>
        <Label>comment</Label><input type="text" placeholder="talk to your mentor" class="inputy"><br>
        <input type="button" class="ttt" value="SUBMIT">
    </form>
</div>
</template>

<script>
export default {
    name: 'ContactContent',
}
</script>

<style>
label {
    text-transform: capitalize;
    color: rgb(95, 19, 165);
}

.inputy {
    width: 65vh;
    height: 20vw;
    border: 2px;
    border-radius: 15%;
    background-color: rgb(245, 243, 240);
    position: center;
    text-align: center;
}

.ttt {
    background-image:url('/public/pictures/mikeBill2.png');
    font-size: 1rem;
    padding: 0.5em 2em;
}


</style>
