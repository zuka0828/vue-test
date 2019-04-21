<template>
  <div>
    <p v-if="msg.length > 0">
      {{msg}}
    </p>
    <p v-else>
      (null)
    </p>
    <p>
      msg.length = {{msg.length}}
    </p>
    <input type="text" v-model="msg">
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: "Hello!"
    }
  }
}
</script>
