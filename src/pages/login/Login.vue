<template>
  <div :style="bgImg">111</div>
</template>

<script>
export default {
  data () {
    return {
      bgImg: {
        backgroundImage: 'url(' + require('@/assets/login.jpg') + ')',
        backgroundRepeat: 'no-repeat',
				backgroundSize: '100% 100%',
      }
    }
  }
}
</script>
