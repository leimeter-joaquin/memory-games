<script lang="ts" setup>

//llenar arreglo, duplicarlo y meterlo dentro de IconsShuffled
interface Icon {
    id: string //check how to limit number of characters
    img: string
    isShowing: boolean
}

const initialIcons: Icon[] = []
const IconsShuffled = []

</script>
<template>
    <JoaquinGrid >
        <JoaquinTile />
    </JoaquinGrid>
</template>