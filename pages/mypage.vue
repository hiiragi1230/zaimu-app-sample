<template>
    <div class="text-center my-5alert alert-primary" role="alert">
        <h1 class="p-4">マイページ</h1>
        <ul>
            <li>ユーザーネーム：{{ user.name }}</li>
            <li>会社名：{{ user.company }}</li>
        </ul>

    </div>
</template>
<script setup>
import { ref } from 'vue'

const user =userInformation();

function increment() {
  user.value++
}
</script>