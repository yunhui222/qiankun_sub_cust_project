<template>
  <div>
    <el-container> 
        <el-main>
          <el-table :data="tableData">
            <el-table-column prop="date" label="日期" width="140">
            </el-table-column>
            <el-table-column prop="name" label="姓名" width="120">
            </el-table-column>
            <el-table-column prop="address" label="地址">
            </el-table-column>
          </el-table>
        </el-main>
      </el-container>
  </div>
</template>

<script>
export default {
  components: {

  },
  props: {

  },
  data() {
    const item = {
      date: '2022-01-09',
      name: '王小宝',
      address: '北京市西城区中国邮政集团邮票印制局'
    }

    return {
      tableData: Array(8).fill(item),
    }
  },
  computed: {

  },
  watch: {

  },
  created() {

  },
  mounted() {

  },
  methods: {

  }
}
</script>

<style scoped lang="less">

</style>
