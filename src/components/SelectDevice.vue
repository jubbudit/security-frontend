<template>
    <div id="device-selector">
        <div class="selector-content">
            <table>
                <tr>
                    <th><div class="option">Windows</div></th>
                    <th><div class="option">Mac</div></th>
                    <th><div class="option">iPhone</div></th>
                    <th><div class="option">Android</div></th>
                    <th><div class="option">Game Console</div></th>
                </tr>
            </table>
        </div>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import ItemBox from './ItemBox.vue'

export default {
    data() {
        return {
        }
    },
    methods: {
    },
    components: {
        ItemBox
    }
}
</script>

<style scoped>
#device-selector {
    width: 65%;
    height: 200px;
    background-color: orange;
    margin-left: auto;
    margin-right: auto;
    border-radius: 8px;
    vertical-align: middle;
    padding-top: 25px;
}

.selector-content {
    display: inline-block;
    text-align: center;
}

.option {
    width: 150px;
    height: 150px;
    background-color: white;
    padding: 20px 20px 20px 20px;
    border-radius: 20px;
    vertical-align: middle;
}

.option:hover {
    background-color: #cccccc;
}

.selector-content th {
    vertical-align: middle;
    position: relative;
}
</style>