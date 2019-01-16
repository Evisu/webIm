<el-dropdown>
  <span class="el-dropdown-link">
    下拉菜单<i class="el-icon-arrow-down el-icon--right"></i>
  </span>
  <el-dropdown-menu slot="dropdown">
    <el-dropdown-item>黄金糕</el-dropdown-item>
    <el-dropdown-item>狮子头</el-dropdown-item>
    <el-dropdown-item>螺蛳粉</el-dropdown-item>
    <el-dropdown-item disabled>双皮奶</el-dropdown-item>
    <el-dropdown-item divided>蚵仔煎</el-dropdown-item>
  </el-dropdown-menu>
</el-dropdown>


body::-webkit-scrollbar { width:20px; height:2px; background:#ccc; border-radius:10px;/*外层轨道*/} 

body::-webkit-scrollbar-thumb{ display:block; width:6px; margin:0 auto; border-radius: 10px; background:red;/*内层轨道*/}