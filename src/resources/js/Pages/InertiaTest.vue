<script setup>
import { Head, Link } from '@inertiajs/inertia-vue3';

</script>

<template>

    InertiaTest <br>
    <a href="/">aタグ経由</a><br>
    <Link href="/">Linkコンポーネント経由</Link><br>
    <Link v-bind:href="route('inertia.index')">名前付きルートの確認</Link><br>
    <Link v-bind:href="route('inertia.show',{ id : 1 })">ルートパラメータ確認</Link>

</template>