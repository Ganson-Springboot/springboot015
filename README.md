# 全目录

3000套系统，根据编号搜索演示视频，复制至流浪器：www.yuque.com/wisebit/blog


<p>抠: 206157502(sql文件)</p>
<p>抠群: 983063232(sql文件)</p>

# springboot015在线视频教育平台的设计与实现



# 第五章 系统实现

## 5.1用户功能模块
用户点击进入到系统操作界面，可以对首页、个人中心、课程信息管理、我的收藏管理、订单管理等功能模块，个人信息：通过列表可以获取账号、密码、姓名、性别、手机、邮箱、照片、备注并进行修改操作，如图5-1所示。

![](/md/blog.013.png)

图5-1个人信息界面图

课程信息管理：通过列表可以获取课程编号、课程名称、课程类型、关键字、课时、课程详情、封面、教师工号、教师姓名、价格、审核回复、审核状态等信息进行详情或查看评论操作，如图5-2所示。

![](/md/blog.014.png)

图5-2课程信息管理界面图



我的收藏管理：通过列表可以获取收藏名称、收藏图片等信息，进行详情、修改及删除操作，如图5-3所示。

![](/md/blog.015.png)

图5-3我的收藏管理界面图



订单管理：通过列表可以获取订单管理；订单编号、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、支付类型、状态、地址等信息，进行详情、修改、删除等操作，如图5-4所示。

![](/md/blog.016.png)

图5-4订单管理界面图


#########
## 5.2管理员功能模块
##
管理员通过用户名和密码、角色填写完成后进行登录，如图5-5所示。管理员登录成功后进入到系统操作界面，可以对首页、个人中心、用户管理、教师管理、课程信息管理、课程类型管理、我的收藏管理、系统管理、订单管理等功能模块进行相对应操作。

用户管理：通过列表可以获账号、密码、姓名、性别、手机、邮箱、照片、备注等内容，可以进行详情、修改或删除操作，如图5-6所示。

![](/md/blog.017.png)

图5-5管理员登录界面图

![](/md/blog.018.png)

图5-6用户管理界面图

教师管理：通过列表可以获取教师工号、密码、教师姓名、性别、照片、职称、联系电话、教师邮箱等信息，进行详情、删除或修改操作，如图5-7所示。


![](/md/blog.019.png)

图5-7教师管理界面图

课程信息管理：通过列表可以获取课程编号、课程名称、课程类型、关键字、课时、课程详情、封面、教师工号、教师姓名、价格、审核回复、审核状态等信息，进行详情、查看评论、修改或删除操作，如图5-8所示。

![](/md/blog.020.png)

图5-8课程信息管理界面图 

课程类型管理：通过列表可以获取课程类型等信息，进行修改或删除操作，如图5-9所示。

![](/md/blog.021.png)

图5-9课程类型管理界面图

我的收藏管理：管理员通过列表可以获取收藏名称、收藏图片等信息，进行详情、修改或删除等操作，如图5-10所示。

![](/md/blog.022.png)

图5-10我的收藏管理界面图








轮播图；该页面为轮播图管理界面。管理员可以在此页面进行首页轮播图的管理，通过新建操作可在轮播图中加入新的图片，还可以对以上传的图片进行修改操作，以及图片的删除操作，如图5-11所示。

![](/md/blog.023.png)

图5-11轮播图管理界面图



订单管理管理：管理员通过列表可以获取订单管理；订单编号、商品名称、商品图片、购买数量、价格/积分、折扣价格、总价格/总积分、折扣总价格、支付类型、状态、地址等信息，进行修改或删除操作，如图5-12所示。

![](/md/blog.024.png)

图5-12订单管理管理界面图
##
## 5.3教师功能模块
教师点击进入到系统操作界面，可以对首页、个人中心、课程信息管理、我的收藏管理等功能模块，课程信息管理页面通过列表可以获取课程编号、课程名称、课程类型、关键字、课时、课程详情、封面、教师工号、教师姓名、价格、审核回复、审核状态并进行详情、修改、查看评论或删除等操作，如图5-13所示。

![](/md/blog.025.png)

图5-13课程信息管理界面图

我的收藏管理：通过列表可以获取删除名称、收藏图片等信息，进行详情、修改、删除操作，如图5-14所示。

![](/md/blog.026.png)

图5-14我的收藏管理界面图


## 5.4前台首页功能模块
在前台首页，在首页可以查看首页、课程信息、个人中心、后台管理、购物车等内容，如图5-15所示。

![](/md/blog.027.png)

图5-15前台首页功能界面图



`    `用户登录，在登录页面通过填写账号、密码、角色等信息完成登录，如图5-16所示。

![](/md/blog.028.png)

图5-16用户登录界面图
#########
在课程信息页面通过填写课程编号、课程名称、课程类型、关键字、课时、课程详情、教师工号、教师姓名、点击次数等信息进行添加到购物车、立即购买或点我收藏等操作，如图5-17所示。在购物车页面通过填写购买商品、价格、数量、总价等信息进行点击购买或删除等操作，如图5-18所示。

![](/md/blog.029.png)

图5-17课程信息界面图
#########
![](/md/blog.030.png)

图5-18购物车界面图




第六章  系统测试
##
##











