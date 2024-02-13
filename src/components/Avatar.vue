<template>
    <div>
        <img class="avatar" :src="imageSrc" />
    </div>
</template>

<script lang="ts">
export default {
    name: "Avatar",
    props: {
        imageSrc: {
        type: String,
        required: true,
        },
    },
};
</script>

<style>
.avatar {
    width: 6rem;
    height: 6rem;

    border-radius: 50%;
}
</style>
  