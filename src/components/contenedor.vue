<template>
    <div class="mi_primer_diseño">
        <p>este es mi primer parrafo aj oi asid joias diojas iod iaos duisaduisahjdui sau uisa duisa ioud uoj asd saudn asn</p>
    </div>
    <div id="from" class="container">

        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Nombre y apellido</label>
            <input type="text" class="form-control" id="text1" placeholder="coloque sus nombres">
        </div>

        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Cedula</label>
            <input type="number" class="form-control" id="text2" placeholder="numero de identificacion">
        </div>
        <div class="mb-3">
            <label for="exampleFormControlInput1" class="form-label">Email</label>
            <input type="email" class="form-control" id="text3" placeholder="name@example.com">
        </div>

        <div class="mb-3">
            <label for="exampleFormControlTextarea1" class="form-label" placeholder="escriba su informacion aqui">Example textarea</label>
            <textarea class="form-control" id="text4" rows="3"></textarea>
        </div>

        <button type="submit">enviar registro</button>

    </div>
</template>

<script setup>

</script>

<style scoped>
    .mi_primer_diseño{
        background-color: rgb(236, 180, 180);
        width: 400px;
        height: 200px;
        position: relative;
        padding: 14px;
        margin: 4px;
        top: 50%;
        left: 50%;
    }
</style>