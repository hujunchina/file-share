<template>
  <el-upload
    class="upload-demo"
    drag
    action="http://www.so-paper.com:8081/posts/"
    multiple>
    <i class="el-icon-upload"></i>
    <div class="el-upload__text">将文件拖到此处，或<em>点击上传</em></div>
    <div class="el-upload__tip" slot="tip">上传文件会生成二维码或易记的URL</div>
  </el-upload>
</template>

<script>
export default {
  name: 'FileShare',
  props: {
    msg: String
  }
}
</script>
