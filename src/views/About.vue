<template>
  <div>
    <field v-if="zj!='me'"></field>
  
    <components :is="zj"></components>

    <bottom  @show="jieshou"></bottom>
  </div>
</template>

<script>
import field from "@/components/field.vue";
import home from "@/views/Home.vue";
import jian from "@/views/jian.vue";
import me from "@/components/me.vue"
import zhong from "@/views/zhong.vue";
import bottom from "@/components/bottom.vue";
export default {
  components: { field, bottom, zhong,home, jian, me},
  data() {
    return {
      zj:"zhong"
    }
  },methods: {
    jieshou(val){
     
      this.zj=val
       console.log("val"+this.zj);
    }
  },
};
</script>

<style>
</style>