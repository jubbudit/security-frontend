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

export default {
    data() {
        return {
        }
    },
    methods: {
    },
    components: {
    }
}
</script>

<style scoped>
#device-selector {
    width: 65%;
    height: 300px;
    background-color: orange;
    margin-left: auto;
    margin-right: auto;
    border: 2px DarkOrange solid;
    border-radius: 8px;
    padding-top:75px;
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
}

.option:hover {
    background-color: #cccccc;
}

</style>