<template>
  <div class="wrapper">
    <h1>新建分类</h1>
    <el-form label-width="120px" @submit.native.prevent="save">
      <el-form-item label="名称">
        <el-input v-model="model.name"></el-input>
      </el-form-item>
      <el-form-item>
        <el-button type="primary" native-type="submit">
          保存
        </el-button>
      </el-form-item>
    </el-form>
  </div>
</template>

<script>
export default {
  components: {},
  props: {},
  data () {
    return {
      model: {
        name: ""
      }
    }
  },
  watch: {},
  computed: {},
  methods: {
    save() {
      // this.$http.post()
    }
  },
  created () {},
  mounted () {}
}
</script>
<style lang="stylus" scoped>
</style>
