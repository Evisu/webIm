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


 1  /*定义滚动条轨道*/
 2     #style-2::-webkit-scrollbar-track
 3     {
 4         background-color: #F5F5F5;
 5         -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.22);
 6     }
 7     /*定义滚动条高宽及背景*/
 8     #style-2::-webkit-scrollbar
 9     {
10         width: 10px;
11         background-color: rgba(0, 0, 0, 0.34);
12     }
13     /*定义滚动条*/
14     #style-2::-webkit-scrollbar-thumb
15     {
16         background-color: #8b8b8b;
17         border-radius: 10px;
18     }:0 auto; border-radius: 10px; background:red;/*内层轨道*/}


/* 设置滚动条的样式 */
::-webkit-scrollbar {
width:12px;
}
/* 滚动槽 */
::-webkit-scrollbar-track {
-webkit-box-shadow:inset006pxrgba(0,0,0,0.3);
border-radius:10px;
}
/* 滚动条滑块 */
::-webkit-scrollbar-thumb {
border-radius:10px;
background:rgba(0,0,0,0.1);
-webkit-box-shadow:inset006pxrgba(0,0,0,0.5);
}
::-webkit-scrollbar-thumb:window-inactive {
background:rgba(255,0,0,0.4);
