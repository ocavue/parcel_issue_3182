<template>
  <div> Hello {{bundler}} </div>
</template>

<script>
import Vue from "vue";

export default Vue.extend({
  data() {
    return {
      bundler: "Parcel!" // <--- Edit this string and you well see error in browser console
    };
  }
});
</script>