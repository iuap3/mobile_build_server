# IOS证书管理

主要用与管理IOS证书文件，可上传mobileprovision文件、p12文件，校验文件uid是否一致，删除文件记录，导入证书文件和同步证书文件。

![](/articles/build/3-/images/image23.png)

图：IOS证书管理

◆ **功能操作说明**

**新建**：点击表格左下方的New按钮，即可进入新建界面。

![](/articles/build/3-/images/image24.png)

图：IOS证书管理

选择.mobileprovision文件后，自动上传到服务器，服务器分析文件内容，包括appidentifier、profileuuid、profiletype等，并将结果返回显示在界面上。

![](/articles/build/3-/images/image25.png)

图：上传证书成功

**修改**：双击行进入条目编辑页面，面包线上显示为Edit。

![](/articles/build/3-/images/image26.png)

图：IOS证书管理

选择.mobileprovision文件后，自动上传到服务器，服务器分析文件内容，包括appidentifier、profileuuid、profiletype等，并将结果返回显示在界面上。

![](/articles/build/3-/images/image52.png)

图：修改证书

修改已有的信息后点击Save，即可保存修改，点击Return或者是对应的菜单项，可返回表格页面。

**删除**：表格中的多选框为删除选择框，点击表格标题栏中的选择框，可选择当前页面内的所有行。选中要删除的记录后，点击表格左下方的Delete按钮，即可删除所有选中的记录。

![](/articles/build/3-/images/image27.png)

**同步**：点击表格下方的SYNC按钮，可将所有的.mobileprovision证书的数据内容同步到数据库管理。

![](/articles/build/3-/images/image26.png)

图：IOS证书管理
