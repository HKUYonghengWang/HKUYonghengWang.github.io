# README

## How to compile this project

1. 打开 github desktop (小紫色软件)
2. 看有不有还没有push的更新，push上去
3. 点击 Fetch origin
4. 点击 open in Subline Text
5. 点击 open in Folder
6. 在 文件页面中 ，选中 www 文件夹，右键唤出菜单，选择打开 终端
7. 运行下面的代码
  ```
  conda activate py2
  python ../jemdoc.py -c jemdoc.conf -o ../html/  *.jemdoc
  ```
8. 打开 html 文件夹，点击 index.html，看更新后的效果，如果已经打开了，则直接刷新对应页面即可
9. 更新完成后打开 github desktop，输入 summary （随便输入）
10. 点击 push，完成上传
