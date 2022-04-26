<script lang="ts" setup>
interface PropState {
  title: string;
  subTitle: string;
  haha: boolean;
}
const props = defineProps<PropState>();
onUpdated(() => {
  console.log("haha");
});
</script>

<template>
  <div class="h-[50px] bg-red-400 text-center">HAHA</div>
</template>
