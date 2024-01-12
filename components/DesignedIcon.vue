<template>
    <div class="rounded-full border w-max h-max m-3">
        <div :class="[text ? 'iconWithText' : 'iconWithoutText']">
            <Icon :name="name"/>
            <span v-if="text" class="ml-2">{{ text }}</span>
        </div>
    </div>  
</template>

<script setup>
const props = defineProps(['name', 'text']);

</script>

<style  lang="scss" scoped>

.iconWithoutText {
    width: 4em;
    height: 4em;

    svg{
        vertical-align: unset;
        margin-bottom: 0;
        transform: translate(50%, 50%);
        width: 2em;
        height: 2em;
    }
}

.iconWithText {
    padding: 1em;
    svg {
        margin-bottom: 0.2em;
        width: 1em;
        height: 1em;
    }
}
</style>