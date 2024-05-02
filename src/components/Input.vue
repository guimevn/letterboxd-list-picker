<template>
    <div class="container">
        <div class="logo">
            <img src="../assets/letterboxd-icon.png" />
        </div>
        <h1>put the link</h1>
        <div class="submit">
            <input type="text" placeholder="Enter a link" />
            <button>Submit</button>
        </div>
    </div>
</template>

<style>
.container {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
}

.logo img {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 200px;
}

.submit {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.submit input {
    width: 300px;
    height: 40px;
    padding-left: 20px;
    margin-bottom: 30px;
    border: 1px solid black;
}

.submit button {
    width: 320px;
    height: 40px;
    border: 1px solid black;
    background: black;
    color: white;
    cursor: pointer;
}
</style>

<script>
export default {
    name: 'Input'
}
</script>
