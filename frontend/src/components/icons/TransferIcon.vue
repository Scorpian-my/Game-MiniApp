<template>
    <svg :width="props.width" :height="props.height" :fill="props.fill" viewBox="0 0 16 16">
        <path d="M14.082 2.182a.5.5 0 0 1 .103.557L8.528 15.467a.5.5 0 0 1-.917-.007L5.57 10.694.803 8.652a.5.5 0 0 1-.006-.916l12.728-5.657a.5.5 0 0 1 .556.103z"/>
    </svg>
</template>


<script setup lang="ts">
interface Props {
    width?: string,
    height?: string,
    fill?: string,
}
const props = withDefaults(defineProps<Props>(), {
    width: "20px",
    height: "20px",
    fill: "currentColor"
});
</script>