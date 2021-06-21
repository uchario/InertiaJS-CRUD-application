<template>
    <layout>
        <h1>Welcome</h1>
        <p>This is the about page: {{ foo }}</p>
    </layout>
</template>

<script>
import Layout from '../Shared/Layout'
export default {
    props: ['foo'],

    components: {
        Layout,
    }
}
</script>