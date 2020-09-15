<template>
  <div>
    <el-button>Hello,原型+Element UI</el-button>
  </div>
</template>
<script>
  import { Button } from 'element-ui';
  import './node_modules/element-ui/lib/theme-chalk/index.css'
  export default {
    components: {
      ElButton: Button,
    }
  }
</script>