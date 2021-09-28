<template>
    <div class="question">
        <div class="question-content">
            <strong><h2>{{ question }}</h2></strong>
            <p><em>{{ description }}</em></p><br/>
            <table>
                <tr>
                    <th><BaseButton title="YES"></BaseButton></th>
                    <th><BaseButton title="NO"></BaseButton></th>
                </tr>
            </table>
        </div>
    </div>
    <br/>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import BaseButton from './BaseButton.vue'

export default {
    props: {
        question: String,
        description: String
    },
    data() {
        return {
        }
    },
    methods: {
    },
    components: {
        BaseButton
    }
}
</script>

<style scoped>
table {
    width: 100%;
}

th {
    display: inline-block;
}

.question {
    background-color: orange;
    border-radius: 8px;
    width: 65%;
    margin-left: auto;
    margin-right: auto;
}

.question-content {
    padding: 8px 8px 8px 8px;
}
</style>