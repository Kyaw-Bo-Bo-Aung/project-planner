<template>
    <div class="card">
        <div class="card-header">
            <h3 class="card-header-title" @click="toggleBody">card header</h3>
            <div class="card-action">
                <span>edit</span>
                <span>delete</span>
            </div>
        </div>
        <p v-if="showBody" class="card-body">
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eligendi tempore porro impedit, quidem temporibus beatae ea soluta est pariatur officiis minus, earum magnam. Ab numquam assumenda aspernatur eaque consequatur?
        </p>
    </div>
</template>

<script>
export default {
    data() {
        return {
            showBody: false
        }
    },
    methods: {
        toggleBody() {
            this.showBody = !this.showBody
        }
    }
}
</script>

<style scoped>
.card {
    padding: 15px;
    margin: 10px 0;
    box-shadow: 0 0 3px 1px rgba(0, 0, 0, 0.2);
    border-left: 5px solid green;
    border-radius: 5px;
}
.card-header {
    display: flex;
    justify-content: space-between;
    margin-bottom: 10px;
    cursor: pointer;
}
.card-header-title {
    text-transform: capitalize;
}
.card-action span {
    margin-left: 5px;
    cursor: pointer;
    padding: 5px;
}
.card-action span:hover {
    background-color: silver;
}
</style>