## 上传与下载

#### md的重点技巧

* 当在一个内容块里面出不来时可用，小键盘上下箭头来移出，当然如果还是不出来就回车试试

### 连接github与上传

1. **确保本地SSH与github的一致**

2. **关联远程库**

   > ```shell
   > git remote add origin XXX（:qaqtime/qaqtime.github.io.git）仓库链接
   > ```

3. **本地与git更新同步(建议是不是第一次建库一般都需要用下面的命令更新)**

   > ```shell
   > git pull --rebase origin master
   > ```
   >
   >

4. **真正上传本地文件**

   > ```shell
   > git push -u origin master
   > ```

### 下载

> ```shell
> git clone XXX(仓库download下载链接)
> ```

