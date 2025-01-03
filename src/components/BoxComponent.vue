<template>
 <div class="box has-text-weigth-bold">
<slot></slot>
 </div>
</template>

<script lang="ts">
import { defineComponent} from 'vue';

export default defineComponent({
    name:"BoxComponent"
})
</script>

<style scoped>
.box{
    background:#6c6c6c ;
}
</style>