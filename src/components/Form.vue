<template>
    <form action="">
        <div class="form-group">
            <label for="title">Title</label>
            <input class="form-control" type="text" name="title" id="title" placeholder="Title name">
        </div>
        <div class="form-group">
            <label for="content">Content</label>
            <textarea class="form-control" rows="5" type="text" name="content" id="content" placeholder="Post content . . ."></textarea>
        </div>
        <div class="form-group">
            <input class="btn btn-action" type="submit" value="Create">
            <button class="btn btn-back">Back</button>
        </div>
    </form>
</template>

<script>
export default {

}
</script>

<style>
    .form-group {
        margin: 10px 0;
    }
    .form-control {
        display: block;
        width: 100%;
        font-size: 1rem;
        padding: 5px;
        margin-top: 5px;
        border: 1px solid blueviolet;
        outline: none;
    }
    .btn-action {
        margin-right: 10px;
    }
</style>