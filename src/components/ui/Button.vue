<template>
    <button :style="{ background: color }" class="btn">
        {{ text }}
    </button>
</template>

<script>

export default {
  name: 'Button',
  props: {
    text: {
        type: String,
        default: 'View'
    },
    color: {
        type: String,
        default: '#0090DA',
    },
  },
}
</script>