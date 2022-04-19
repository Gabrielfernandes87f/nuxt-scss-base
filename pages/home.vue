<template>
<div>

  <h1>
      Discord
      <a href="#" class="buttom linkscss" @click="dark=true"> tema dark</a>

  </h1>
      <button @click="toglleDarck=false">
        false
      </button>
            <button @click="toglleDarck=true">
        true
      </button>
</div>
</template>

<script>
export default {
  name: 'home'
}
</script>
