# Android证书管理

用于管理发布android应用时进行签名的证书，可进行新建秘钥、上传证书文件、导入证书文件、同步证书文件、删除、查找、下载证书文件等操作。页面中的列表记录为当前数据库中的key列表和上传的crt文件列表。

![](/articles/build/3-/images/image16.png)

图：Andorid证书管理界面截图

◆ **功能操作说明**

**新建密钥**：点击表格左下方的New Key按钮，即可进入新建密钥界面。

![](/articles/build/3-/images/image17.png)

图：Andorid证书管理界面截图

在新增密钥界面中，设置相关密钥信息并输入密码后，即可完成密钥的新增。

![](/articles/build/3-/images/image18.png)

图：编写新建密钥

**修改**：双击行进入条目编辑页面，导航栏上显示为Edit。由于Android证书的特殊性，仅提供keypass和storepass的编辑功能。

![](/articles/build/3-/images/image19.png)

图：修改

修改已有的信息后点击Save，即可保存修改，点击Return或者是对应的菜单项，可返回表格页面。

**删除**：表格中的多选框为删除选择框，点击表格标题栏中的选择框，可选择当前页面内的所有行。选中要删除的记录后，点击表格左下方的Delete按钮，即可删除所有选中的记录。

![](/articles/build/3-/images/image20.png)

图：Andorid证书管理删除

**上传.crt证书文件**

点击数据列表下方的\[Upload .crt\]，可上传.crt证书文件。如下图所示：

![](/articles/build/3-/images/image21.png)

图：上传.crt证书文件

上传的.crt文件后会有Import按钮，点击按钮则可导入该.crt文件中的所有key，导入成功后，Import按钮取消，显示“SUCCESS”，表示导入成功。

**同步**：点击表格下方的SYNC按钮，则可进行同步功能。如果数据库中有记录没有keypass，则会弹出提示框，提示添加keypass后再进行同步。

![](/articles/build/3-/images/image22.png)

图：Andorid证书管理同步

