https://exiao.yuque.com/docs/share/e954465c-72c1-4184-b825-0f72cdc40723?# 《安装轻流平台》
# qingflow-deploy
轻流一键部署包-具体请联系商务获取，然后通过授权码进行兑换
更新内容：
轻流无代码系统搭建平台	           
2021/11/22
# 「功能优化」NUM函数修复
优化了NUM函数后端运算，运算逻辑与前端运算一致

# 「功能优化」提醒推送新增插入字段
当待办/通过数据/超时/催办等事件发生时，可以触发webhook，将事件详细信息推送到任意url地址

2021/11/15
# 「体验优化」表单/报表/门户中数据表支持记录列宽
表单、报表、门户支持保留上次调整后的字段列宽。

# 「体验优化」部门字段支持显示部门层级
在多层级部门的状况下，选择子部门后，部门字段显示层级部门。

2021/11/08
# 「新功能」管理后台新增全部应用
可在工作区「管理后台」-「全部应用」中进行全部应用的管理，支持修改应用基本信息、快速搜索等操作，点击了解更多

# 「体验优化」移动端仅拍照上传优化
对移动端（手机、平板）在使用浏览器进行附件仅拍照上传进行了兼容性优化，点击了解更多

2021/11/01
# 「新功能」引用字段支持Q-Robot

# 「功能优化」优化了流程图中自动化流程的冗余显示
为避免使用误解，涉及Q-Robot、Webhook相关的流程日志，将不再显示“重新执行”按钮

# 「体验优化」邀请成员加入工作区无需创建新工作区
优化后，邀请成员加入工作区不会再单独创建新工作区，将直接进入邀请人的工作区中

2021/10/25
# 「功能优化」表格字段中支持链接字段
现支持表格字段中添加链接字段啦，支持数据关联、筛选等操作。

# 「功能优化」查看流程图新增查看Q-Robot日志
可在表单「流程节点」-「基础设置」及数据表中开启配置开关，开放Q-Robot类型节点的流程日志查看权限。

# 「钉钉」三方自建应用免登优化
优化了钉钉自建应用的免登录状态

2021/10/18
# Q-Linker支持提交重计算
在数据提交的时候，可以自动拉取最新的qlinker结果进行数据填充。

2021/10/11
#「体验优化」自定义打印保留其原有格式进行打印
多行文本字段在进行打印时，会保持原有格式进行打印，如换行、回车字符等

#「体验优化」门户轮播组件中优化
解除了轮播组件和链接字段的强绑定，链接字段不作为内容来源的必填项

#「体验优化」轻流界面设计及弹窗样式更新
更新了轻流的界面设计元素

2021/09/27
# 优化了数据并发时页面刷新的问题
当点击用户详情的刷新按钮时，则仅刷新该弹窗页面。

# 表单图标组件设计优化

2021/09/18
# 批量修改数据显示优化
优化了批量修改的历史记录显示。

2021/09/06
# 帮助界面新增「最佳实践」
为多种行业场景提供解决方案和实践讲解，快速解决你的搭建难题。点击查看详情

#「微信增强」更名为微信服务号增强
为清晰传达插件内涵，轻流将原“绑定微信服务号”插件更名为“微信服务号增强”。点击查看详情

2021/08/23
# 【打印模版】流程日志支持拆分节点进行打印

字段对照表拆分为系统字段和表单字段，可选择具体流程节点的字段信息进行打印；
流程日志现支持复制节点字段进行打印。

2021/08/17
# 【高级字段】引用

新增引用字段，可以获取其他应用数据中最新的字段值，实时更新字段信息，实现跨连接数据引用，点击了解更多

# 【系统字段】数据ID

新增数据ID字段，方便数据的查询和调取，配合引用字段在筛选条件、Q-Robot中等内容中进行设置，点击了解更多

# 【开放平台】Unicdoe编码解码

高级公式新增UNICODEENCODE、UNICODEDECODE公式，将文本字符串或表单字段内容使用Unicode编码/解码。

# 【开放平台】Q-Source优化

优化了英文界面显示，以及部分异常提醒；
优化了入口操作，以及生成解析的效果；
支持偏移量拉取数据，点击了解更多

2021/08/09
#【视觉优化】全站基础元素设计优化

对全站基础元素进行设计优化，包括字体、按钮等样式

2021/08/02
#【轻析】内测版本发布

轻析内测版本已上线，拥有数据源、数据集、可视化三大能力，协同轻流办公，打通业务系统和BI平台之间的双向连接。产品详情与内测报名方式，点击了解更多

2021/07/26
#【门户】链接组件新增刷新按钮
门户的链接组件中增加刷新按钮，可刷新链接页面，点击了解更多

2021/07/05
#【个人中心】补充安全信息优化
对个人中心的安全信息进行了设置和显示的优化

2021/06/28
#【绑定微信服务号】支持PC端微信使用
支持PC端微信正常使用，与移动端一致的微信增强功能，点击了解更多

#【开放平台】temporarytoken支持拼接字符串
单点登录oauth2.0、鉴权oauth2.0支持temporary token，先访问另一URL获取临时Token，需要您自定义此请求的地址及返回参数解析方式，然后将解析完成的参数插入到header/query/body中，点击了解更多

#【开放平台】qsource支持鉴权
Qsource主动模式里增加了鉴权配置项，一些接口可以通过配置鉴权模版，直接使用，
点击了解更多

2021/06/21
#批量修改可以修改多个字段
批量修改功能现支持一次修改多个字段，同时你也可以在批量拒绝、批量提交/通过、批量转交的操作中修改数据中的字段，来减少对同一批数据进行多次批量操作的情况，点击了解更多

#查看流程图
对于开放流程日志查看权限的节点，在未完结的流程日志，点击“查看流程图”按钮，将显示流程图和节点状态，满足你对预览流程图的需求，点击了解更多

#门户链接组件·允许授权登录信息
Alpha版本的门户-链接组件增加“允许授权登陆信息”配置项，允许授权后，嵌入链接会携带门户查看者的部分登录信息参数，点击了解更多

#专有云&私有化版本支持导出附件
专有云和本地化工作区中，数据表支持附件导出功能

2021/06/15
#【流程】被回退的数据重新提交
审批节点流程回退时，默认按流程顺序审批，节点负责人可选择是否“直达当前节点”，点击了解更多

2021/06/07
#【专有云&私有化企微】通讯录支持手动添加成员&部门
企业微信专有云&私有化版本，在组织架构同步的基础上，新增手动添加成员和部门的功能，点击了解更多

#【数据量】放开专有云&私有化工作区数据量限制
放开了专有云与私有化用户的数据库导入导出等数据量限制

#【连接】openapi新增用户登录接口
如果有userid和权限组accesstoken，用返回的登陆code拼接好对应路由，可直接登录

#【连接】accesstoken权限组
对openapi设置超级管理员和权限组，超级管理员accesstoken有最高权限，权限组accesstoken通过关联子管理员/成员限制其权限，维护平台安全，点击了解更多

2021/05/31
#【筛选条件】支持判断多位小数0
当筛选条件两个数字字段的小数位数不统一时，系统会自动以0补齐位数，以避免筛选结果与预期不一致的情况。

#【连接】LDAP新增域账号模式
现在你可以在sso单点登录-LDAP方式下配置域账号，可以让配置过程更加便捷，点击了解更多

2021/05/25
#任务委托支持移动端消息提醒
可以选择多个消息接收平台，除轻流外，增加了企业微信、钉钉和飞书，帮助消息成功送达，点击了解更多

2021/05/06
#【选项】支持选项颜色
单选、多选和下拉选择字段现支持配置选项颜色。你可以根据选项内容和填写需要为不同种类的选项配置合适的填充色，让视觉更美观、数据更直观，点击了解更多

2021/04/26
#【word模版】支持批量打印
word打印模版现已支持批量打印，你可以选择将多条数据拼接成一个文件进行打印，也可以选择把每条数据分开逐条打印，点击了解更多

 

2021/04/19
#【自定义按钮】移动端交互优化
现在您在移动端通过自定义按钮执行操作时，跳转界面将会以弹窗形式出现，以便您保留原表单界面的编辑内容

2021/04/12
#【通讯录】企业微信通讯录同步优化
企业微信版本工作区现在可以直接将企业微信的通讯录同步为轻流通讯录，无需通过自建应用进行通讯录同步授权，点击了解更多

#【通讯录】同步企业微信管理员为轻流管理员
在企业微信版本工作区中，您现在可以将企业微信管理员同步为轻流管理员，同时也可以手动添加轻流工作区管理员，点击了解更多

#【文件预览】支持私有化配置文件预览服务器
私有化用户可以通过配置文件预览服务器地址，来进行文件预览

2021/04/06
#【个人中心】任务委托
任务委托适用于请假、临时转岗等多种场景，您可以将特定的应用和应用包中所涉及的任务、审批在某段时间内转交给工作区的其他成员进行处理。系统将会在你所设定的时间区间内自动将工单转交至受托人，点击了解更多

#【连接】提醒推送支持鉴权
推送提醒支持鉴权功能，您现在可以在提醒推送界面设置鉴权方式，点击了解更多

2021/03/29
#【自定义打印】支持上传Word模版
您可以在Word文件中灵活自定义模板样式和内容，并将其作为打印模板进行打印。Word打印模版提供了更多定制空间，创建更多的模版样式，从而满足您更多的打印需求，点击了解更多

#【门户】筛选组件优化
筛选组件现在可通过拖拽调整布局与大小，且您可以在筛选组件中添加筛选组和筛选条件，将门户的多个报表汇总在一个查询入口进行查询，进行多报表查询。点击了解更多

#【多行文字】多行文字支持公式计算
您现在可以在多行文字字段的配置栏中启用公式计算，点击了解更多

#【通讯录】支持搜索部门、角色
您现在可以在通讯录中搜索部门和角色，点击了解更多

 

2021/03/15
#【连接】Q-source被动模式支持更新数据标识支持其他字段
在Q-source被动模式中，您现在可以通过匹配应用字段来更新数据，点击了解更多

 

2021/03/08
#【登录】自定义登录有效期
您现在可以自定义账号的登录状态有效期，且支持移动端和桌面端设置不同的有效期。该功能目前仅支持专有云和私有化版本，请联系您的售后人员了解更多。

#【sso】工作区支持关闭sso自动登录创建用户
启用该功能后，首次单点登录的用户将不会自动在工作区通讯录中自动创建账号。

2021/03/01
#【应用创建】继承应用包权限
当您在应用包中创建应用时，新建应用的权限默认值会自动继承应用包的权限设置。

#【筛选条件】支持复制
您现在可以在同一个应用中复制、黏贴筛选条件，让您的搭建过程更加高效，点击了解更多

#【手写签名】支持申请节点
您现在可以在申请节点开启手写签名功能，点击了解更多

#【段落字段】数据表权限设置
您现在可以在数据表中进行对段落子字段进行权限设置，也可以通过段落批量设置字段的权限、段落的默认开启和关闭状态，点击了解更多

#轻流上架飞书
轻流和飞书结合产品优势和使用场景进行了深度打通，你现在可以在飞书上安装轻流，实现账号体系同步、消息及时传递、支持多端登录等多种功能，点击了解更多

2021/02/08
#【进程中心】支持批量导入
您现在可以通过随时进程中心查看数据导入的进程和状态，无需在弹窗界面等待，点击了解更多

#【门户】专有云&私有化链接跳转
我们优化了专有云和私有化版本在小程序点击链接跳转时的跳转逻辑，以保证用户拥有更好的使用体验。

#【表格】表格字段支持行号
表格现支持行号功能，您可以表格填写中，通过序号勾选批量删除表格数据、也可以在某行数据后直接插入新行，点击了解更多

 

2021/02/01
#手机字段升级为电话字段
全新的电话字段支持录入手机号码和固定电话，点击了解更多

#表格支持单项选择
您现在可以将单项选择添加作为表格子字段，点击了解更多

#表单编辑优化
我们对表单编辑界面的视觉进行了优化，让您能有更好的编辑体验

#柱状图、折线图日期维度不同单位显示
我们对柱状图、折线图日期维度不同单位的显示进行了优化

#Q-source支持表格字段
您现在可以通过Q-source将外部数据连接到表格子字段中，点击了解更多

#数据筛选新增“属于”、“不属于”筛选条件
当您选择属于、不属于条件来筛选数据时，您就可以筛选出【某字段】属于/不属于【某数值范围】时的所有数据，点击了解更多

#筛选条件属于/不属于支持日期与起止时间
您现在可以使用属于/不属于条件来对日期和起止时间字段进行筛选，点击了解更多

#【筛选条件】数据关联字段匹配其他字段
您现在可以在门户的筛选组件中让已经实现关联的两个字段参与同一个筛选条件

#逐级审批设置优化
您现在可以将表格中的成员字段设置为逐级审批的起点，且当您将成员字段（表格内外）作为审批起点时，您可以针对该字段进行审批去重，点击了解更多

 

2021/01/21
#【通讯录】部门信息显示优化
您现在可以通过【通讯录-成员信息】卡片了解到成员所在部门、担任职务以及部门所属关系。

#【数据列表】记录用户对于单页表格显示条数设置
当您在数据列表设置完单页表格的显示条数之后，系统将自动保存您的设置，以免每次查看需要重复设置。

#【轻商城】付费解决方案上架轻商城
您可以在【轻商城-应用中心】中，购买安装由经验丰富的垂直专业专家们，将多年深耕垂直场景的最佳实践，设计出的解决方，点击了解更多

#【轻商城】服务中心正式上线
备受瞩目的服务中心正式上线啦，服务中心致力于为企业数字化升级提供专业的一站式服务，您可以根据自身需求选择不同的服务类型，让专业的服务助力您实现更快的数字化转型，点击这里了解更多

#轻流plus版本正式上线
全新上线的plus版本正式上线啦，作为轻流全新的互联共生型管理平台定位版本，您可以在plus版本中无门槛使用：高级版Q-robot、段落字段、门户引擎，以及数据来源标记、ocr文字识别等多款插件

点击这里了解更多plus版本相关的功能和服务

 

2021/01/11
#表单新增段落字段
段落字段是一个表单布局工具类型的字段。设计表单时，可将多个字段放置于一个段落中，令表单布局更清晰；并支持在不同节点，配置段落的收起/展开、批量设置段落内字段权限等属性，点击了解更多

段落字段是ALPHA版本可用功能，当工作区升级成功后，可点击前往插件中心查看并安装

 

2021/01/06
#【在线支付】支付信息支持打印与导出
通过在线支付插件而产生的支付信息，现支持打印和导出，点击了解更多

#表格中数字字段支持enter换行
您如今在表格的数字字段中录入数据时，可通过enter按键添加新行，点击了解更多

#【数据列表】录入数据后自动刷新
现在录入数据后，应用相关的界面和数据将及时自动刷新

#门户新增宫格组件
您现在可以通过宫格组件，创建工作区内的门户、应用、应用包和外部链接的快捷入口，实现与其他产品、页面的打通，实现更加多样的页面访问需求，点击了解更多

#门户新增文本组件
您现在可以通过文本组件编辑公告、说明等等，让访问者更好地理解仪表盘中的内容，点击了解更多

#门户新增轮播组件
您现在可以通过轮播组件，以更突出、有效、快捷地方式传递核心价值观、推广信息、宣传广告等内容，点击了解更多

#门户新增链接组件
您现在可以借助链接组件、将工作区外的网页、视频、宣传信息以及工作区内的应用等直接放置仪表盘中，让您想要传达的信息更快地触达用户，点击了解更多

 

2020/12/28
#「OCR文字识别插件」现支持PDF格式文件
您现可通过OCR文字插件上传单页PDF文件进行文字识别，点击了解更多

2020/12/21
#鉴权插件现支持oauth2协议
鉴权插件增加了被广泛使用的，Oauth2.0协议，点击了解更多

#OpenApi插件新增获取应用表单信息方式
您现在可在OpenApi插件中通过逻辑表单和数据关联参数获取应用表单信息，点击了解更多

#门户新增对移动端显示界面编辑功能
您现在可通过pc端编辑门户在移动端的显示界面，点击了解更多

#门户分栏优化
门户的分栏布局由原先的8列增加至24列，支持了更多布局与展现方式。

 

2020/12/15
#轻流付费版功能范围调整
对轻流不同版本的价格页进行了更新，涉及多个功能定位调整，点击这里了解更多

#【自定义编号】、【公式】、【自定义提交成功页面】、【会签】、【提交校验】五项功能调整为pro版及以上可用功能
当前付费版本用户（包括air版）仍可继续使用以上功能，针对当前版本的续费也不会收到本次调整影响。若该功能与您当前的版本不匹配，可点击这里进行版本升级

#【钉钉M2智能前台】、【微信增强】、【轻流logo隐藏】三项功能调整为pro及以上版本付费插件
当前付费版本用户（包括air版）仍可继续使用以上功能，针对当前版本的续费也不会收到本次调整影响。若该功能与您当前的版本不匹配，可点击这里进行版本升级

#【权限组】更名为【子管理员】
插件【权限组】现更名为【子管理员】，本次更名不会影响您的正常使用和配置，点击这里了解更多

2020/12/07
#仅拍照上传功能优化
优化在企业微信端使用【仅拍照上传】功能会出现报错的情况，点击了解更多

2020/11/30
#打印模板支持自定义打印文件标题
您现在可以在自定义打印模板中，自定义打印文件的文件标题，点击了解更多

#提交重计算成员字段优化
支持以【部门】和【角色】为单位对成员字段提交重计算

 

2020/11/23
#仪表盘支持所有人可见
新增仪表盘【公开分享】功能，支持将仪表盘分享至工作区外部人员查看，点击抢先体验

#新增MD5、Join函数
MD5函数支持文本MD5加密，可自定义加密位数（16/32位）；Join函数允许自定义多值字段的连接符，点击了解更多

#webhook全局配置
您可以在插件中心自定义webhook配置，生成全局可用的webhook模板，点击了解更多

#安卓手机上传多张图片
优化安卓手机上传附件的功能设置，支持用户同时上传多张照片，点击了解具体设置

#通讯录成员分页优化
优化通讯录部门/角色的成员列表的分页显示

#免费版成员上限下调至10人
免费版工作区可使用人数调整至10人，试用版和付费版工作区人数不变，为您带来的不便请谅解~

2020/11/16
#移动端支持留言提醒
开启留言提醒后，若成员在留言中被@，将可收到微信/钉钉/邮件留言提醒。点击了解更多

#通讯录信息导出
导出通讯录成员信息，并支持在进程中心和操作记录中查看任务状态和记录。点击了解更多

#微信支持扫码自动登录
微信/企业微信中扫码查看数据，支持自动跳转授权登录

2020/11/09
#数据关联支持添加自定义按钮
在字段后添加按钮操作，例如添加数据、跳转链接等。点击了解更多

#webhook支持回调
支持Json、XML两种数据结构，根据您自定义的解析方式对webhook收到的回调内容进行解析。点击了解更多

#私有云&本地化支持引入外部js文件
支持从外部引入js文件，为更多拓展功能（加载第三方插件、自定义插件）提供支持

#自定义编号优化
优化表单使用自定义编号小概率提交出错的情况

 

2020/11/02
#逐条打印
批量打印在原有拼接打印的基础上，新增逐条打印的方式；逐条打印时，打印的每条数据会生成一个打印文件，并保存在一个压缩包内。点击了解更多

#鉴权方式
连接功能调用外部接口时，验证调用者是否有调用权限，支持Basic Auth、Api Key 、Temporary Token三种鉴权方式。点击了解更多

#插件中心优化
插件中心视觉优化，界面更清爽；每个插件新增插件详情，可帮助你更好理解插件的使用场景；新增5个插件（权限组、标记数据来源、甘特视图、日历视图、漏斗视图）。点击了解更多

#邮件登录验证优化
节点负责人为工作区成员时，打开邮件提醒中的链接，须先登录后，才能查看数据内容。

#扫码查看数据跳转优化
在未登录状态下，扫描非所有人可见数据的二维码后，优先跳转登录页面。

2020/10/26
#进程中心
在进程中心，可随时查看进行中任务的进程相关信息；目前支持查看批量打印操作的相关任务进程及记录。点击了解更多

#批量打印支持查看操作记录
批量打印支持查看操作记录。点击了解更多

#Webhook支持XML和插入表格
webhook支持传输XML格式的数据和插入表格。点击了解更多

#Q-Source主动轮询支持XML
Q-Source主动轮询支持传输XML格式的数据。点击了解更多

 

2020/10/19
#表单视觉优化
表单编辑页面的视觉升级，界面更清爽简洁~

2020/10/12
#逐级审批
审批节点中，节点负责人可设置为逐级审批，待办到达该节点后，会从直接主管开始，逐级向上审批到指定层级。点击了解更多

#表格字段体验优化
针对手机端的表格录入体验进行优化，且支持切换行。

#导入优化
导入时，附件字段可支持同时导入多个附件。

2020/09/27
#移动端支持查看留言
留言可在移动端进行查看。点击了解详情

#新增TEXTUSER和TEXTDEPT公式
TEXTUSER可获取所选成员在通讯录中的名称、邮箱或手机号；TEXTDEPT可获取所选部门的名称或ID。点击了解详情

#批量打印多条数据
数据列表中，可以选择多条数据，进行批量打印。点击了解详情

#webhook优化
webhook使用POST形式时，Header 可匹配当前的表单字段。点击了解详情

2020/09/21
#仅拍照上传
附件字段可以设置仅拍照上传，该功能只能在微信、微信小程序和企业微信移动客户端上可以用。点击了解更多

#Q-Linker全局配置支持插入系统参数
表单编辑中，使用Q-Linker模板的时候，绑定变量值可选择系统参数，如数据唯一标识(applyId),编号，申请人，更新时间，创建时间。点击了解更多

#选择类字段和数据关联字段优化
选择类字段的系统其他选项，在关联时的表现统一；数据关联设置的交互优化

 

2020/09/14
#提交校验支持校验应用
当被选择的应用正在被添加或更新数据时，无法通过校验。点击了解更多

#新手引导优化
新手引导全新体验升级，帮助新用户更快上手系统使用，欢迎体验~

2020/09/07
#数据关联支持表格子字段
数据关联可直接关联到目标表单的表格某一行。点击了解更多

#Q-Source被动模式支持更新数据和添加白名单
Q-Source被动模式下，支持更新数据和添加白名单。

#Q-Linker支持插入到表格
当Q-Linker中的Result Format选择JSON或XML的时候，别名可以选择配置为表格别名，表格别名用于将QLinker请求到的数组(表格)类型数据关联到表格中。点击了解更多

 

2020/08/31
#流程节点支持剪切
流程节点剪切后，当前处于该节点的数据也会一起剪切过去。点击了解更多

 

2020/08/24
#公式新增NETWORKDAYS
可计算两个日期之前的工作日，并支持指定假期。

#成员可解绑微信增强的服务号
在个人中心-账户信息中，成员可解绑微信增强的服务号
2020/08/17
#Q-Linker支持全局配置
在插件中心配置Q-Linker模板，在表单编辑中使用Q-Linker字段的时候可以使用模板，实现一次配置随处使用；点击了解更多

#导入数据体验优化
当导入数据出现失败时，导入失败的数据可生成一个错误报告，下载后可见详细报错信息；点击了解更多

#API接口更新
支持通过API获取流程日志中修改的内容和获取所有用户列表的接口

2020/08/10
#成员可导入数据
当成员需要录入的数据较多时，可进行批量导入数据。点击了解更多

#富文本支持调整图片大小
富文本中可调整图片大小。点击了解更多

#对外报表可支持设置需要先登录
当报表的可见范围为所有人可见时，可设置“需要先登录”。点击了解更多

#公式支持日期时间戳转换
新增2个公式，DATETOTIMESTAMP（date）可支持日期转时间戳，即将日期转化为13位毫秒级时间戳；TIMESTAMPTODATE（时间戳）可将时间戳转换为日期格式，即「年-月-日 时:分:秒」。

 

2020/08/03
#节点可关闭撤回功能
审批/填写节点中，支持关闭撤回功能，了解更多

2020/07/20
#在线支付
流程中可以直接发起微信收款，且所有款项将直接进入企业的交易账户中。了解更多

2020/07/13
#超时提醒优化
超时后支持提醒给部门主管，或提醒给邮件字段，以提醒工作区外部人员。了解更多

#Webhook参数新增applyId
Webhook的配置，如URL中，可插入数据唯一标识(applyId)。了解更多

 

2020/07/06
#公式MAX MIN 支持判断日期时间
max、min支持判断日期时间大小。了解详情

#邮件处理页面优化
通过邮件打开待办时，在手机端和电脑端的显示优化

 

2020/06/29
#提醒推送
应用数据有新的提醒的时候，将提醒事件推送到第三方系统，如待办，抄送，催办，超时提醒等

#自定义按钮
自定义数据详情的操作按钮，点击后可添加数据、跳转链接等；添加数据时，还支持带上当前数据相关的信息到目标表单 。了解更多

 

2020/06/15
#SSO支持LDAP
SSO单点登录新增LDAP协议。点击了解更多

2020/05/25
#Q-Linker优化
当参数发生变化时，会自动触发一次Q-Linker，不必再手动触发一次。点击了解更多

#地址字段优化
地址字段内容更新优化和手机端上的样式优化。

#数据表支持全局搜索
在数据表中，直接搜索关键词快速找到数据。

2020/05/18
#手写签名
审批流程的时候，可以进行签名审批，还能打印出来。点击了解更多



#表格限制最大行数
每个表格可录入的最大行数为200条。了解更多：https://hc.qingflow.com/help-center/specialtable/#i-9

#应用数据列表优化
无流程不显示待办、已办和抄送；且可以记录上次访问的列表。了解更多：https://hc.qingflow.com/help-center/createapp/#i-6

#SSO获取AccessToken配置新增queryParam
SSO获取AccessToken配置新增queryParam。

2020/05/06
#手机号支持短信验证
填写表单时，所填写的手机号码必须短信验证通过才可提交，保证手机号真实性，点击了解更多

#导入数据时，支持导入部门字段
部门字段支持携带上下级部门的路径进行直接导入，点击了解更多

#表单组件优化
附件等字段的样式和交互优化，PC和mobile体验更统一；表单字段校验时，还能直接定位字段位置。

#webhook自定义json中支持插入系统字段
webhook自定义json中可以插入系统字段，如编号、申请人、申请时间等

#单个应用数据量限制
免费版的单个应用数据量上限为3万条；PRO&ALPHA版的单个应用数据量上限为50万条

#单点登录（SSO）登录优化
用户退出登录时，进入单点登录（SSO）登录页，点击了解更多

#应用可见权限优化
若某应用的节点负责人，无此应用的可见权限时，则在应用列表中将无法看到该应用，如需查看，管理员可修改一下应用的可见权限；但本次更新对之前的通知和待办无任何影响

 

 

 

 

2020/04/26
#应用包上线
“分组”升级为“应用包”了，不仅支持进一步分组，还可以批量删除应用，助力应用场景化管理



#首页新增已办事项
「首页」新增已办事项，可查看自己的所有已办，且支持搜索，查找已办更迅速~



#Q-Linker参数支持插入表格子字段
Q-Linker配置相关的url、form body、json body中支持插入表格子字段，点击了解更多

 

 

 

2020/04/20
#Q-linker支持自定义文案
Q-linker字段支持自定义文案，了解更多：https://hc.qingflow.com/help-center/q-linker/



2020/04/13
#多个字段优化
地址字段的省市区更新至最新；轻流钉钉版的定位精确度优化；「附件字段」的图片类型新增jfif，且支持在线预览，了解更多：https://hc.qingflow.com/help-center/attachment/

2020/04/07
#Q-Robot更新优化
「Q-Robot更新」在现有功能的基础上，新增支持用当前表单字段更新目标表格的已有行、当前表格子字段更新目标表单字段、当前表格覆盖目标表格。查看更多：https://hc.qingflow.com/article-categories/q-robot-update

#数据表支持留言
数据表中可以进行留言，查看更多：https://hc.qingflow.com/help-center/data-sheet/#i



#字段管理可设置表格子字段显隐
数据列表中，当切换到详细视图后，可在「字段管理」中设置表格子字段的显隐。



#成员&部门字段优化
成员和部门字段的可选范围，默认为工作区所有成员/部门。

 

2020/03/30
#表格默认值优化
当表格同时设置了「整表的默认内容」和「子字段的默认内容」时，将优先展示「整表的默认内容」

2020/03/23
#流程节点设置优化
流程节点的配置项被拆分成「基础设置」和「高级设置」，视觉和交互上进行了统一的优化升级，使用起来更清晰更高效~

2020/03/02
#数据列表显示表格内容
在操作栏中，点击切换到详细试图，就可以看到表格里的详细内容了~

#Q-source支持轮询
通过外部数据源开放的接口，定期将外部数据源与轻流数据进行同步。比如：1. 将当前正在使用的软件的订单/客户等数据同步到轻流； 2.定期将其他系统数据的新增，修改或删除操作同步更新到轻流中的对应数据

#汇总表支持列固定
汇总表的数据量大到超过一屏，但需要查看右侧的数据时，难以定位数据信息？试一下固定某一列吧！

#数据删除优化
管理员删除全部数据中数据时，需要进行多次确认

 

2020/02/24
#报表支持添加备注信息
可在报表中添加备注，说明报表内容/用途等。了解更多：https://hc.qingflow.com/help-center/custom-report/#i-19

#报表的维度、指标支持选择表格内子字段
柱状表、折线图、饼状图、漏斗图的「维度」和「指标」，支持选择表格内子字段，了解更多：https://hc.qingflow.com/help-center/custom-report/

#工作区可以设置外链语言类型
在【管理-基本信息】中，可对外链语言进行设置，如设置为英文时，工作区外部人员点开表单/报表分享链接、邮件通知后，看到的就是英文内容

2020/02/17
#手机端全部数据
含有应用数据管理权限的成员，可以在手机端查看全部数据

#报表优化
所有报表统一支持通过计算获得指标、指标显示格式设置、流程处理时长和流程超时时长的单位设置

2020/02/07
#流程回退支持范围限制
「流程回退」限制范围后，审批人进行回退操作时，仅可回退到之前的所有节点/上一节点/指定节点. 了解更多：https://hc.qingflow.com/help-center/opertoroperation/



#qrobot更新数据的筛选条件支持系统字段
设置Q-robot更新数据的筛选条件时，可将当前应用和目标应用的系统字段进行筛选匹配. 了解更多：https://hc.qingflow.com/help-center/qrobot/

2020/01/20
#报表打印可关闭系统默认模版
数据表中设置打印模板时，可以关闭“系统默认模板”

#汇总表的列汇总和小计，支持多种汇总方式
在汇总表中，列汇总和小计的汇总方式可以选择无、求和、平均值、最大值、最小值。了解更多：https://hc.qingflow.com/help-center/summary-table/#i-2

 

2020/01/10
#待办详情查看优化
可将流程日志和留言展开/收起

#流程日志优化
查看节点编辑详情体验优化，且手机端的流程日志中支持查看当前处理人

 

2019/12/26
#Q-robot更新数据优化
Q-robot添加/更新数据严格按照流程设定的顺序执行，Q-robot更新最多可更新3万条/次。了解更多：https://hc.qingflow.com/help-center/qrobot/

#新增「钉钉M2智能前台」插件
当钉钉M2智能前台上有新增数据时，直接往目标应用添加数据，在轻流中处理M2的数据。了解更多：https://hc.qingflow.com/help-center/data_sources/



#待办转交支持限制范围
待办转交可设置为可转交给指定成员/所有成员。了解更多：https://hc.qingflow.com/help-center/opertoroperation/



 

2019/12/20
#自定义打印模板支持插入字段二维码/条形码和数据查看二维码
自定义打印模板中，支持插入字段的二维码或条形码；数据查看二维码可根据每个人的查看权限，查看对应的数据。了解更多：https://hc.qingflow.com/help-center/print-template-setting/



#数据表的单条数据支持分享
在数据表打开某条数据弹窗后，点击更多即可获得单条数据分享二维码/链接。了解更多：https://hc.qingflow.com/help-center/data-sheet



#系统默认打印模版支持关闭
根据节点设置打印模板时，可选择关闭系统默认模板。

2019/12/16
#留言支持发送文件
留言中可以发送文件和图片，同时支持图片预览。了解更多：https://hc.qingflow.com/help-center/comment/



#自定义打印模板支持设置打印尺寸和方向
设置自定义打印模板时，可自定义打印尺寸，并支持设置打印方向。了解更多：https://hc.qingflow.com/help-center/customed-sheet-for-print/

2019/12/09
#漏斗图
自定义报表新增「漏斗图」，可直观地展现出数据各个阶段的转化趋势。了解更多：https://hc.qingflow.com/help-center/custom-report/#i-14



#支持导出2,000条以上数据
数据大量导出超过2,000条后，每2000条数据将保存为一个Excel文件。

#流程时效统计支持单位设置（时、分、天）
在报表中进行流程处理时长和超时处理时长时，可设置时、分、天为统计单位。了解更多：https://hc.qingflow.com/help-center/process_effectiveness_statistics/

#数据关联的值支持排序
数据关联字段可以按照目标应用中某个字段的升降序，对关联过来的值进行排序。了解更多：https://hc.qingflow.com/help-center/data-association-2/



 

 

 

2019/12/02
#筛选条件支持选择表格内字段
所有筛选条件的左侧字段选择可支持表格内字段，只要表格中含有一行满足所设条件，该数据就会被筛选出来。



#报表支持仅展示排名内的数据
自定义报表中，可选择只展示排名靠前/排名靠后n位的数据。了解更多：https://hc.qingflow.com/help-center/custom-report/#i-5



#报表指标支持显示格式设置
在设置指标时，可将指标的显示格式设置为千分位、百分比、金额等。了解更多：https://hc.qingflow.com/help-center/custom-report/#i-5



 

2019/11/26
#日历视图
以日历的形式展现应用数据，并以时间维度进行管理数据的一种方式，工作区成员可以通过日历查看每天的日程安排。了解更多：https://hc.qingflow.com/help-center/calendar_view/



#连接扫码枪
用扫码枪扫码后，自动填入对应字段中，在表格内时还会自动添加一行

#新留言和自定义提醒优化
更直观地看到有新的留言信息；点击自定义提醒的通知，可直接链接跳转到相关数据详情

2019/11/18
#流程时效统计
自定义报表中，支持统计流程节点、节点负责人的节点处理时长、超时时长等，处理效率清晰可见~

#单点登录
使用第三方帐号体系登录轻流。了解更多：https://hc.qingflow.com/help-center/sso/

#ocr 识别后，自动往表格中增加一行
OCR识别内容匹配到表格子字段时，每识别一次，会自动往表格里增加一行，使用更方便~

2019/11/11
#表格子字段支持部门字段
表格中支持添加部门字段了~了解更多

#起止时间/日期字段支持不精确到秒
起止时间和日期字段的「精确到时分秒」，可选择具体精确度（时/分、时/分/秒）~了解更多

2019/11/04
#OCR自定义识别模板
文字识别（OCR）的识别模板支持自定义~了解更多



#【数据关联-筛选条件】的高级模式支持选择当前应用的字段
设置数据关联的筛选条件时，若选择高级模式，也能选择当前应用的字段了~



#轻流钉钉版支持同步角色
支持将钉钉上设置的角色同步到轻流~

2019/10/28
#成员字段的可选范围可动态匹配部门字段值
可将表单中部门字段的值，作为成员字段的动态可选范围~了解更多



#数据表可设置默认排序
数据表打开后就有一个默认排序。了解更多


#自定义提醒的提醒人可以选择表单内的邮箱、手机字段
自定义提醒的被提醒人，可以是表单内的邮箱、手机字段的动态值。了解更多



#图片选择支持逻辑表单
图片选择字段可以支持设置逻辑表单了~

2019/10/21
#一级界面重大更新
全新导航菜单，为场景化分类提供了更多便利，如将同一场景的应用和仪表盘添加到统一“分组”内；应用查看与操作更集中，使用效率更高~



#手机端支持查看关联报表
手机端支持查看关联报表~



#审批节点支持关闭“拒绝”操作
审批节点-高级设置中，可将拒绝操作关闭了~点击了解更多



#整表关联支持多行、邮箱、手机、数据关联
表格默认内容的关联已有数据，支持选择多行、邮箱、手机、数据关联字段。点击了解更多

#OpenAPI-微信增强 可返回客户公众号下的用户Open ID
开启微信增强时，返回关注客户公众号的用户Open ID。

 

 

2019/10/16
#文字识别（OCR）
对图像中文字内容的提取，并自动填入表单中的对应的字段中，方便用户进行文本的提取或录入。了解更多：https://hc.qingflow.com/help-center/character_recognition/



2019/09/30
#公式新增SQRT函数
可以计算指定数字的平方根～立即体验：https://qingflow.com/f/6ab59c06



 

2019/09/23
#甘特图
通过条状图来显示某些时间相关的活动（任务、阶段、项目等）随着时间进展的情况，以便管理者直观地查看活动进度，把控全局。了解更多：https://hc.qingflow.com/help-center/gantt/

 

2019/09/17
#关联报表 支持根据节点配置关联报表的可见范围
在某个节点可以设置节点负责人能查看哪个关联报表～了解更多：https://hc.qingflow.com/help-center/relate-reports/



#数据列表优化
图片可预览缩略图、附件字段支持预览等，列表交互更友好～

2019/09/09
#OpenApi支持催办数据
通过调用轻流的OpenApi接口，实现催办某条数据的功能～

 

2019/09/02
#电子签章
在轻流的审批节点中，开启签章审批的功能，所有签署的文件与线下盖章方式一样具有法律效应～了解更多：https://hc.qingflow.com/help-center/electronic-signature/



#Q-robot自动更新数据 支持往目标表格新增行
「Q-robot自动更新数据」支持在目标应用的表格中，以新增一行的方式，将当前应用表单字段更新至对应表格子字段，了解更多：https://hc.qingflow.com/help-center/qrobot/



#新增IFS函数
能判断是否满足判断条件，从而返回对应的TRUE值，相当于IF函数简易版～了解更多： https://hc.qingflow.com/help-center/function2/



 

2019/08/26
#自定义打印模板、报表支持复制
可以直接基于已有的自定义打印模版、报表进行复制～





#新增Ln函数
数字函数中新增Ln函数，可以计算指定数字的自然对数～了解更多：https://hc.qingflow.com/help-center/function2/#LN



#Open api的申请人可以自定义
通过OpenApi申请的数据，可以指定数据的申请人为通讯录中的任意成员。当后续数据遇到回退、撤回申请等场景时，可以通知到申请人，方便对数据进行及时跟进～

 

2019/08/19
#表格内支持禁止重复子字段值
表格内支持禁止重复子字段值，比如填写表格单据时数量过多时，不用再担心录入重复数据了～了解更多：https://hc.qingflow.com/help-center/specialtable/#i-5



#动态负责人支持表格内成员、邮箱、手机字段
动态负责人支持选择表格内的成员、邮箱、手机字段～了解更多：https://hc.qingflow.com/help-center/representative/

#关联已有数据 可选择Q-Linker
原本仅「数据关联」可关联Q-Linker的值，现在所有字段的「关联已有数据」也都支持啦～了解更多：https://hc.qingflow.com/help-center/q-linker-help-documentation/

#仪表盘优化
仪表盘中打开报表的交互优化，打开报表更快，使用体验更好了～

 

2019/08/12
#Q-robot更新数据 可对不符合筛选条件的数据进行处理
Q-robot更新数据可将不符合筛选条件的数据，作为一条新数据在目标应用中添加～了解更多：https://hc.qingflow.com/help-center/qrobot/



2019/08/06
#整表关联支持公式和且、或条件
整表关联的筛选条件新增“简易模式”和“高级模式”，更多的场景、更复杂的筛选条件都能支持！～了解更多：https://hc.qingflow.com/help-center/table-association/

#公式识别部门字段
公式支持识别部门字段了，如可以筛选出“部门字段=某部门”的数据！了解更多：https://hc.qingflow.com/help-center/function/

#自定义提醒支持短信发送
自定义提醒的提醒方式可选择「短信提醒」了，触发该自定义提醒时，会自动发送短信～了解更多：https://hc.qingflow.com/help-center/time-reminder/



#应用创建体验优化
应用创建的交互和视觉优化，为你带来更好的使用体验～了解更多：https://hc.qingflow.com/help-center/manager/



#复制节点
在节点设置中，可复制节点后，粘贴在任意的节点位置上，节点原本的设置都能完整地复制过来～了解更多：https://hc.qingflow.com/help-center/nodecopy/



#仪表盘-添加报表时，可支持报表搜索
编辑仪表盘，在进行添加报表时，可直接搜索报表进行添加～了解更多：https://hc.qingflow.com/help-center/dashboard/



 

2019/07/29
#批量处理
将待办进行批量提交/通过、拒绝、转交，管理员还能直接在全部数据中进行重新指派负责人，再也不害怕待办出现积压了，待办处理效率迅速提高！了解更多：https://hc.qingflow.com/help-center/batch-process/



#数据关联的筛选条件支持公式
数据关联的筛选条件新增高级模式，支持进行公式筛选，了解更多：https://hc.qingflow.com/help-center/data-association-2/

#Q-Robot发送邮件支持添加附件
Q-Robot发送邮件支持添加多个表单内上传附件和自定义打印模板。了解更多：https://hc.qingflow.com/help-center/q-robotsendemail/

·

2019/07/22
#重新申请
在「我的申请」和「全部数据」中，打开数据详情后，可在该数据的基础上进行重新申请。了解更多： https://hc.qingflow.com/help-center/re-apply/ ‎

#上传附件限制个数
「上传附件字段」支持限制个数。了解更多： https://hc.qingflow.com/help-center/attachment/



2019/07/15
#表格填写优化
点开表格某一行并填写完毕后，可以直接点击下一行，进行填写～了解更多：https://hc.qingflow.com/help-center/specialtable/



 

2019/07/02
#留言
在流程中留言，如果留言中使用@功能，还能实时通知到被@成员，针对某条数据的沟通可直接在轻流上完成，还方便追溯～了解更多：https://hc.qingflow.com/help-center/comment/



#模版中心全新升级
更多场景、行业模版供你选择～了解更多：https://qingflow.com/template



#openAPI支持筛选和删除数据
OpenAPI可以根据字段值来筛选数据了，还能支持删除应用的数据～了解更多：https://hc.qingflow.com/help-center/open-api/

#自定义节点按钮文案
申请人、审批节点、填写节点的按钮都可以进行自定义文案，可以针对具体场景了解更多：https://hc.qingflow.com/help-center/custom-button-text/

#提交/通过时重新触发数据关联或公式 支持整表选择
“提交/通过时重新触发数据关联或公式”可以支持整表选择，选择整表后可重新触发整表关联～了解更多：https://hc.qingflow.com/help-center/recalculation/
 

2019/06/26
#仪表盘筛选组件
在一个仪表盘中，合并不同报表的同类型字段为一个筛选条件，一次筛选多个报表，再也不用建多个报表和仪表盘了！✌️了解更多：https://hc.qingflow.com/help-center/dashboard-filter-component/

#单行文字直接切换成多行文字
单行文字支持直接切换成多行文字，了解更多：https://hc.qingflow.com/help-center/singletext/



#地址字段 增加 “海外” 选项
填写地址时，可选择“海外”选项～



2019/06/19
#个人动态增加草稿箱
在首页就可以快速查看所有历史草稿～



#自定义报表支持进行「部门字段」筛选 
自定义报表中，可通过选择「部门字段」进行筛选数据，并支持「当前部门」的动态筛选～了解更多：https://hc.qingflow.com/help-center/department-field/

#公有云-付费版本调整
公有云付费版本调整成「免费版」、「PRO版」和「ALPHA版」，了解更多：https://hc.qingflow.com/help-center/release/#i-2

2019/06/10
#数字字段可添加显示格式和限制范围
数字可以以千位分隔符和百分比显示，还能限制输入的数字范围，了解更多：https://hc.qingflow.com/help-center/numberoftext/

#流程分支中的节点筛选条件
流程分支中，筛选条件新增申请人、申请时间、编号和数据来源选项，了解更多：https://hc.qingflow.com/help-center/permission_group/

2019/06/03
#管理员权限细分
权限设置中新增的权限组，支持仅开通个别应用的部分管理权限，如个别应用的编辑、数据管理权限，以及通讯录管理权限，助力企业实现精细化管理！了解更多：https://hc.qingflow.com/help-center/permission_group/

#自定义报表的筛选条件支持公式
自定义报表的数据筛选条件新增了高级模式——公式筛选，支持进行更复杂的数据筛选，支持更强大的报表分析～了解更多：https://hc.qingflow.com/help-center/custom-report/#i-12

#表格子字段新增“多行文字”、“手机”、“邮箱”字段
表格子字段类型新增多行文字、邮箱和手机字段。了解更多：https://hc.qingflow.com/help-center/specialtable/

2019/05/27
#轻流PC 2.0
全新一级界面，让你的工作内容一目了然，全新导航是页面更直观用得更称心，还有常用应用为更高效的工作助力！

#提交/通过时重新触发数据关联或公式
在流程中进行提交/通过时会重新对表单中的某些字段重新进行关联或者计算，保证入库的数据为最新的后台数据。了解更多：https://hc.qingflow.com/help-center/recalculation/

 

2019/05/13
#自定义打印支持打印附件、流程日志、待办二维码和分页符
自定义打印模版，支持附件照片、流程日志和待办二维码的打印了，还增加了分页符显示。了解更多：https://hc.qingflow.com/help-center/print-template-setting/

 

2019/05/06
#新增部门字段
提供部门的选择，设置几乎跟成员字段一样，轻轻松松上手~由于部门字段时跟通讯录的部门设置同步的，还无需多次维护~

查看详情：https://hc.qingflow.com/help-center/department-field/



#动态负责人新增”部门字段”和“部门主管”
表单中添加了部门字段后，在流程中，可直接设置该部门所有成员/部门主管为节点负责人~



#新增Q-source插件
ALPHA版本中，当第三方系统（如金数据）添加数据后，也能直接在当前应用中自动添加数据~



#Q-linker的body支持json
ALPHA版本中，Q-linker的postBody现在可以直接写json了

2019/04/16
#报表维度支持选择地址字段
报表支持对不同地址精度的选择，进行相应的维度分析~

#多项选择可设置下拉模式
多项选择在原先的平铺基础上，新增下拉模式，下拉模式可在选项过多时，进行搜索，达到快速选择的目的~


 

2019/04/08
#上传附件可设置默认条件
“上传附件”字段不仅可以上传多个/不同类型的文件作为默认值，还可以“关联已有数据”了~点击了解详情



#关联已有数据支持多个筛选条件
在“关联已有数据”中添加多个筛选条件，精准关联不在话下~点击了解详情



#Q-robot邮件主题支持插入字段
可以在“Q-robot·发送邮件”的邮件主题中”插入字段“了~



 

2019/04/01
#单条待办数据分享
管理员可将某条待办数据以二维码或链接的形式，发给待办处理人；点击了解详情。



2019/03/18
#超时自动提交
超过流程节点的处理时间后，该节点会忽略任何提交限制，自动提交到下一个节点，再也不用担心节点停滞的情况了；点击了解详情。



2019/03/11
#数据来源标记
给表单链接添加“特殊标记”后发布，通过标记对不同发布渠道的数据进行统计与分析；点击了解详情。

#成员字段支持大小写模糊搜索
成员字段支持大小写模糊搜索了，搜索更方便~

2019/03/05
#批量导入数据支持导入申请人
轻流将通过申请人的邮箱，匹配相应的工作区成员为申请人，若未非工作区成员将显示为：匿名用户



2019/02/25
#提交后页面的自定义显示
不再仅限于文案的修改，现采用富文本编辑后，可进行图文排版和插入表单字段，可更自由地进行页面内容定制了~

#查询条件可查询表格子字段
数据表的查询条件已可进行表格子字段的查询。

#汇总表、指标卡的公式计算，支持非数字字段
自定义报表中，汇总表和指标卡的通过计算获得指标，现在可选择非数字字段了。

 

2019/02/18
#申请节点查看关联报表
在流程中设置允许申请人查看申请报表后，申请人在申请时就能查看到与相关的报表数据了。

#单选、多选、下拉选择字段，支持关联已有数据
单选、多选、下拉选择字段也支持关联已有数据了，助你轻松实现已有相关数据的调取。

2019/01/21
#新增地址字段
表单设置中可以添加一个地址字段，方便地址信息录入。

 

2019/01/14
#Q-Linker升级
支持将获取到的数据填入多个字段中。

#数字字段/新增小数点的位数限制
数字字段允许小数的时候，可以设置小数位数，你可以收集到自己想要的小数数值范围了。

#表格字段/新增默认内容
表格字段新增默认值设置，可进行行数设置与内容设置。

2019/01/02
#表格权限细分（新增行、删除已有行、编辑已有行）
节点负责人对于表格的操作权限有了进一步的细分，可以对删除、添加、编辑三种权限进行分配了。

#附件上传支持自动压缩图片
再也不用担心附件的上传量消耗过快了。现在你可以对图片类型的附件进行压缩上传了。

2018/12/24
#自定义打印模板优化
我们对模板的行编辑和列编辑进行了操作优化，操作更加人性化了。

#Q-Robot邮件模板支持插入基础字段
Q-Robot邮件中支持插入申请人、编号、申请时间、更新时间等表单基础字段了。

2018/12/17
#Webhook 重磅上线
Webhook可用于连接第三方系统，如果您有相关的需求，可以点击右下角的小弹窗联系我们进行演示和使用。

#在线附件预览
Office相关的附件，例如：PowerPoint、Word、Excel等无需下载可以直接进行预览了。如下图所示：



#审批、填写、抄送节点隐藏流程日志
不光是申请人，您也可以对其他类型的流程节点隐藏流程日志了。

 

2018/12/10
#Q-Linker 重磅上线
通过Q-Linker可以从第三方系统中获取数据，例如其他系统中的客户数据、订单数据等，也可获取天气信息、股市行情、物流信息等。您可以通过网站右下角的聊天窗口联系我们，我们将安排顾问为您演示强大的Q-Linker。


#新增函数：REGTEST
新增函数：REGTEST（正则公式），点击右侧链接学习该函数。了解详情

#表格内支持添加：成员字段、上传附件
 

 

2018/12/04
#关联报表
查看某一条数据的详情时，可以根据一定的关联查看其他应用中对应数据的报表。  了解详情

#定位字段
填写应用表单或者修改表单数据的时候，可以获取到操作人员当前所在的位置，支持手动标注。了解详情

2018/11/25
 

#Q-Robot发送短信
支持在流程中，通过Q-Robot触发短信推送通知，发送给成员/外部人员/手机号  了解详情



#汇总表增加行小计
汇总表增加默认“行小计”，汇总表中每一行会针对指标做计数。

#Q-Robot新增/更新支持自定义匹配条件
Q-Robot新增/更新，新增通过自定义内容（固定值）的方式进行条件匹配。

#Q-Robot新增/更新支持上传文件字段
Q-Robot新增/更新可以选择“上传文件”字段。

#Q-Robot邮件支持上传文件字段
Q-Robot邮件，支持嵌入文件，会以链接形式在邮件中显示。

#个人中心支持更改绑定手机号
#全站添加loading
2018/11/19
#微信增强
通过微信认证的服务号向申请人发送提醒推送  了解详情👉

#获取申请人微信信息
获取通过微信填写的申请人的微信信息，包括昵称和头像  了解详情👉

#插件中心
插件中心正式推出，根据不同的需求配置一个专属自动化小助手

#超时支持根据子表格内时间字段进行设置
对表格内的每一项进行超时时间的设置判定

#表格子字段的宽度可调整
现在表格内的子字段支持四种尺寸的宽度设置了

#数据关联及关联已有数据支持关联编号
数据关联可以关联另一个应用的编号字段了

#数据表查询条件可设置模糊查询
2018/11/13
#超时支持根据表单内日期字段设置
在表单中设置日期字段，以这个字段为准设置超时时间据预警。

#流程日志优化
流程日志更加清晰美观，新增抄送及Q-Robot相关日志

#表格内容展开填写
PC端和移动端的表格都支持展开录入了~  填写更方便，更易用

2018/11/05
#自定义编号格式
转为流水号推出的强悍功能，根据不同场景需要定制编号格式！

查看详情

#会签/或签
审批类型新增会签/或签，支持多人审批规则设置

查看详情

2018/10/29
#批量修改数据
选中指定数据，一键批量修改，前所未有的便捷

查看详情

#自定打印支持插入图片
终于可以在打印单据中插入公司logo了！

#仪表盘可移动位置
仪表盘的顺序可以自由调整了，操作方法与字段排序一样简单！

#支持部分字段类型转换
数字字段和单行文字字段支持互相转换，单项选择与下拉选择支持互相转换。

2018/10/22
#自定义按钮文案
数据弹窗内的操作按钮的文案可根据使用场景进行自定义

查看详情

#汇总表支持对表格子字段的汇总
汇总表的行维度、列维度、指标均支持选择表格内的子字段

#数据弹窗的样式及操作按钮的优化
更好看~ 更好用~

2018/10/15
#数据列表的字段支持自由排序
数据列表的字段顺序可以自由调整，配合字段隐藏可以设置一个内容精简、符合自己需求的列表

#数据筛选的日期类型字段支持动态范围
现在可以非常方便的筛选出今日、昨日、本周、上周、本月、上月、今年、去年的数据了

#新增【ROUND UP】和【ROUND DOWN】函数
#优化了手机端和PC端的图片类型的附件预览
2018/10/08
#强大的【自定义提醒】重磅上线！
自定义内容、自定义时间、自定义被提醒人、自定义频率、自定义提醒方式……

可用于合同到期提醒、库存预警、项目状态更新提醒 等多种场景

点击链接了解具体的设置方法：https://hc.qingflow.com/help-center/custom-reminder/

#优化了日常提醒推送，移除了【定时提醒】
更友好的设置界面，更简单的设置方式。不过从今天起，轻流将不再提供定时提醒功能

#优化了【数据筛选】：筛选条件同时支持匹配筛选和精确筛选
匹配筛选和精确筛选可以同时支持，更加灵活、更加强大，目前仅支持【数据关联】字段的数据筛选

 

2018/09/25
#汇总表操作权限支持【导出】了！
不但设置简单！居然还支持一键导出Excel文件！

#【柱状图】【饼状图】【折线图】支持选择不同的颜色主题
随心所欲选择报表色彩主题，让仪表盘更加生动美观

2018/09/17
#【工程项目管理】、【售后管理】行业最佳实践方案正式上线！
点击链接查看详情：

【工程项目管理】：https://s.qingflow.com/landing-pages/project-manage/page.html

【售后管理】：https://s.qingflow.com/landing-pages/after-sale/page.html

#汇总表支持【列维度】
列维度可以使汇总表具有更多的灵活性，统计汇总效果更加清晰明了

#数据表支持【导出】权限设置
在自定义报表创建【数据表】时，可以选择是否允许查看人导出该表的数据。

#【日期】维度支持设置【日期单位】
报表设置日期类型字段为维度时，可以设置日期显示的单位，现在已经支持“年、月、日”三种单位了！

#数据筛选支持关键字搜索
数据筛选可以更精确地筛选到目标数据了

 

2018/09/08
 

#企业微信增强
可以支持已有账号绑定企业微信，具体绑定方式请咨询客服。

#字段删除优化
字段删除时提示与其他应用和功能相关联字段。减少误删除后带来的损失哦～

#手机预览图片优化
H5/小程序/企业微信/钉钉中的图片预览优化

2018/09/01
 

#权限优化：角色上线，部门更新
本次上线后，流程设置、应用权限、报表权限、仪表盘权限可以通过设置部门、角色控制权限。在通讯录中可将任意成员加入到部门、角色当中。当部门、角色中增加成员后，自动获得相应权限。



2018/08/26
 

#单行文本支持扫码输入
单行文本开启允许扫码输入后，在微信/企业微信/钉钉/小程序中打开，即可录入二维码/条形码的包含数据内容。可以便捷进行物品条码的快速录入。

#筛选条件支持空值匹配
在数据关联筛选条件/分支筛选条件/报表限制数据范围中，新增空值匹配。可以通过此功能快捷筛选某个字段是否填写，或根据是否填写来控制是否显示在报表中。

#分支筛选条件支持成员字段
可以利用分支筛选条件，根据成员匹配，进入不同的流程。

#新的报表配色，新的心情
优化报表显示，更换基础报表配色。希望轻流能够给您的工作带来好心情！

2018/08/20
 

#表格字段支持关联已有表格
本次更新后，可以调取其他数据中的“表格”，无需重新录入。调取的表格及其中的数据也能参与计算哦~更多详细内容请查看：关联已有表格设置文档。


#数据表格中的列宽可以拖拽记录啦！
数据表中，可以通过“拖拽表格列”来改变表格宽度。本次更新后，会记录拖拽的宽度。同时使用“拖拽列宽”+“隐藏列”，快去设置便捷的操作吧！

#汇总表/饼图/折线图/柱状图的指标，可以设置排序
本次更新后，支持按照指标默认排序。可以按照相应指标的顺序、倒序等进行排序。

#可以设置申请通道开启/关闭时间
在某些特定场景下，需要控制开启、关闭时间。当流程正式使用前，或者流程作废后，不允许填写。

#自定义打印优化
优化了自定义打印的“表格”显示方式。

2018/08/13
 

#超时功能上线
您可以通过设置超时提醒，为每一项任务设置“时效性”，区别轻重缓急。同时通过数据统计的概览，了解超时预警统计情况。点击此处了解更多使用介绍内容。



 

2018/08/06
#申请人/分享报表可设置查看流程日志
在申请人节点中可针对申请人进行“是否可见流程日志”设置，在数据报表中可设置分享的报表“是否可见流程日志。

#限时推出新的付费方式
很多童鞋希望使用轻流的pro版本功能，但企业人数只有十几个人。为了给出更大的优惠，轻流限时推出按照人数付费的版本，200/人/年，10人起购，轻松享受pro版本功能，快来订购/升级吧！

详细请见：https://qingflow.com/price

#企业微信支持二维码一键部署
用微信扫描下方二维码，即可立即使用轻流x企业微信版本，详细请资讯右下角客服人员。



2018/07/30
#自定义打印模版
支持根据需求自定义打印模版，可以打印指定格式的数据，实现合同、工资单、采购单等自定义打印，点击查看详细内容



#支持更换账号绑定邮箱
员工离职之后，修改绑定邮箱更安全！绑定方式请前往账户设置中，激活新邮箱后完成更换绑定

 

2018/07/16
#通讯录允许批量删除/移除部门
通讯录批量操作上线！更便捷的管理企业员工～



 

2018/07/09
#Q-Robot实现自动化触发邮件
Q-Robot发送邮件功能上线，流程一键触发自定义邮件，点击查看详细内容；



#OpenApi上线
提供了数据获取接口，点击查看详细内容；



#数据叠加包上线
现在可以直接在线购买数据量、附件量以及邮件配额了，点击查看详细内容。



 

2018/06/24
#节点校验功能上线
增加节点校验条件，可以限制满足条件的数据提交了



#模板中心解决方案包更新
模板中心更新应用解决方案包，欢迎尝试使用：https://qingflow.com/template



#数据表结构优化，分页展示
数据表显示重构，长得更清新啦！同时更改数据加载方式改为分页加载方式，增加流畅度。

2018/06/19
 

#流程支持子表单内权限配置
表格内权限进一步细化，可以将表格中的不同列根据节点配置不同的“权限”。



#企业微信版来啦～
轻流支持在企业微信中使用啦！详情请见：https://news.qingflow.com/workwechat/



#满意度调查上线啦！
工作区概览页面加上用户满意度调研，如果有建议请毫不犹豫地告诉我们：https://qingflow.com/f/cf8a609b

2018/06/11
 

#新的用户引导上线！
为了帮助您更好的体验轻流，轻流上线了“四大引导”，分别是激活邮箱、如何创建应用、如何创建报表、如何邀请成员，快来达成轻流成就吧！



#多个文件允许同时上传
选多张图片/文件一起上传，极大的便捷了操作！

#设置负责人时可以立即邀请成员
人不够用直接邀请来凑！每邀请3位成员，可以额外获得3天高级版本哦～以此类推365人365天哦😯！！！

2018/06/03
 

#流程日志增加查看当前处理人
流程谁在处理，一键允许查看！

#应用列表支持位置移动
pc端应用列表洁面，支持应用支持移动位置（手机、数据列表会同步哦~）

#支持流程日志打印
表单打印支持勾选流程日志打印，了解单据的历史处理流程并进行存档备份。

#手机图片预览优化
手机端预览图片，可以放大缩小、长按下载等。

#Excel导入允许进入流程
导入Excel的数据支持可选择进入流程，单次导入不要超过100条哦～

#允许“解绑”微信
解除绑定后，可以更换新微信号或用原有号码再次绑定。

2018/05/28
#手机上支持仪表盘查看啦！
手机支持查看数据仪表盘，数据可视化不再局限于pc端！

#手机支持多种格式的在线预览
手机中支持doc\word\excel\pdf等格式的在线预览

#移动端ui再次优化


 

2018/05/21
 

#指标卡来啦！
一种新的报表类型，让“数字”说话！



#数据关联支持“精确筛选”
数据关联字段支持“精确筛选”，可以通过“固定文字”进行数据关联筛选条件设置



#子表单拓展：支持表格内外字段相互调用、公式计算
一直以来子表单都是轻流很重要的组成部分，应用场景非常大。本次更新后子表单可以调取子表单外的字段内容，也可以将子表单外的字段与表单内进行公式计算，完全畅通无阻！

#数据报表支持筛选“仅当前用户可见”
数据关联精确筛选条件可以设置当前用户，，则可以实现数据报表，每一个用户查看自己所对应的数据内容。

#应用设置可见范围
本功能为应用列表中的可见范围，如需外部人员填写，请前往【添加流程】中【申请人】节点，选择【所有人可填】。



#数据报表权限拓展
创建数据报表时，增加设置报表的可见权限。数据报表可以开启修改数据权限，可以配置允许可见数据报表的成员修改数据。



 

2018/05/14
#仪表盘隆重推出！
新增仪表盘功能，可以将常用的报表加载到首页仪表中使用，还可以根据不同成员设定不同的仪表盘权限、报表权限，实现不同人员可视化不同数据内容！点击查看详情



#新帮助中心上线
上线了新的帮助中心，助力更好的理解轻流的产品相关功能介绍和使用用法，点击查看详情

 

2018/05/06
 

#汇总表中增加“计数”指标
汇总表指标中增加计数，可以通过“数据条数”进行指标的汇总分析

#手机端待办事项显示二级分类
手机端增加查看数据详情的目录增加了二级tab，更加人性化，和PC端统一

#年度主题首页上线，推陈出新！
美美哒！



 

2018/04/23
#抄送显示更新
个人动态增加抄送的数据，数据列表增加抄送的数据





 

2018/04/13
 

#数据报表重大更新！
数据报表更新重构，支持多种数据报表、图表可动态分享、查看，权限设置、数据范围控制等功能。



#新增公式
增加RMBUPPER()方法，可将数字转换为大写金额

#字段相互关联调取范围扩增
1.关联已有数据时，单行文字可以关联显示单项选择/下拉选择的值

2.Q-robot设置中，单行文字可以填入单选/下拉选择

3.Q-robot新增/更新数据时，数据关联字段原关联类型为数字等类型时，可以填入相同类型的值中

 

2018/03/30
 

#数据报表增加搜索功能
数据报表增加搜索，可以快速定位到所需查看应用。

#Q-Robot设置，支持数据关联字段匹配
支持qrobot新增、修改同类型的数据关联字段。例如：qrobot可以将关联后的数字字段填入数字字段。

#数据分享查询条件，支持数据关联字段匹配
分享查询条件支持调取同类型的数据关联字段。

#成员字段拓展
1.数据关联支持成员字段作为筛选条件

2.成员字段可以设置关联已有数据

 

2018/03/25
 

#Q-Robot自动化更新数据上线！
通过Q-Robot可以实现在一个应用的流程中更新另外一个应用中的某些数据，实现“数据回写“功能，点击查看详细设置方式介绍，也可以查看视频介绍哦。



#选择类型问题支持默认值设置
选择题可以设置默认值选项，如果填写成员不进行更改，【提交后】则会按照默认值进行数据的录入。

#数据关联筛选条件拓展
数据关联作为筛选条件时，如果原问题类型为数字，可以选择大于大于等于，小于小于等于等数字筛选方式。

2018/03/16
#数据流程日志支持详细内容展现
数据流程日志记录数据更新详细情况，任意数据的更新历史都会在数据历史记录中进行展示，以便随时查阅。



#手机端增加显示流程日志
手机端也增加流程日志显示，便于在手机中随时查阅。

#应用列表增加搜索功能
更便捷的应用定位，应用数目增加不用愁。标签+搜索，两大功能助力应用管理！

#数据关联支持聚合操作
数据关联支持聚合操作(可以对关联出来的数据进行求和/平均值/最大值/最小值/第一个值/最后一个值/计数)，实现关联数据对历史数据的调取和计算，结合“数据关联筛选条件”，即可对满足筛选条件的数据内容进行关联计算，点击查看详情。

 

2018/02/28
#表单校验提示优化
表单填写时，不满足校验条件的时候，告诉用户具体哪个字段有问题

#数据关联字段拓展，增加设置筛选条件
数据关联字段增加筛选条件设置功能，可以根据筛选条件匹配所需的数据关联内容，过滤无需显示的数据！点击查看详情。



2018/02/05
 

#数据报表增加汇总
增加汇总表，一种新的统计图表。可以将表格式的数据汇总为透视统计表。类似Excel中的数据透视表哦～点击查看已有报表类型。



#流程日志显示实际处理人信息
流程日志中可以看到历史处理人的信息，实际处理人一目了然！

#新增公式
公式计算增加了十余种新的公式函数，请点击查看目前支持函数的详细介绍。

 

2018/01/22
 

#Q-Robot节点上线
qrobot是轻流推出的业务流程自动化的重要节点。通过qrobot，我们可以在a应用的进程中，主动触发b应用，并传递a应用的数据。实现了【主流程】-【子流程】的数据交互，便于跨部门数据管理，点击查看详情。



#支持流程图导出
设置好流程可以导出图片，发送给同事、共享流程设置。

2018/01/12
#手机处理数据支持回退&转交
手机逐也是处理数据的主战场，本次更新支持手机处理“回退”、“转交”功能，更方便的使用！

#文本类型模块增加链接识别
单行文字、多行文字等，出现形如“http://”或“https://”将会被识别为【链接】，可以点击直接访问。

#子表格功能拓展，表格内增加数字、日期、数据关联字段
子表格支持使用“数字”、“日期”、“数据关联”字段，子表格功能更加强大啦！

#子表格中的字段可以更换位置
子表格设置完成后，需要修改表格中子字段顺序，一键拖拽无压力！

#节点设置优化退回、转交功能
1. 审批节点默认开启退回指定节点功能和转交数据功能
2. 填写节点默认开启转交数据功能

 

2018/01/01
 

#轻流学院上线！
通过“轻流学院”，我们为您对接专业的咨询顾问，为您提供最适合的业务解决方案。也就是说您也可以通过轻流学院对接专家顾问，进行业务流程优化。有了“轻流学院”，您的业务流程有了云端的专家顾问，随叫随到，为您提供最优化的解决方案。为效率工作赋能。

成为顾问：https://hc.qingflow.com/help-center/collegeconsultant/

我要顾问：https://hc.qingflow.com/help-center/collegecustomer/



 

 

2017/12/22
 

#数据关联/公式优化
仅可见字段可以触发数据关联/公式。但注意如果字段设置【隐藏】，则不会触发数据关联及公式！

#退回数据增加处理反馈
退回数据的时候，可以填写处理反馈

#工作区管理后台
更新工作区管理后台，更好地概览数据当前状况

2017/12/11
 

#个人动态优化
个人动态中，【我的申请】只推送已通过/已拒绝/退回补充。

#选择选项支持拖拽更改位置
选项位置可以自由拖拽变换，便于修改维护。

#增加解决方案模版
增加解决方案模版，可供更好的参考使用。

2017/12/01
 

#增加数据转交功能
增加数据转交给工作区其他用户的功能，出差、临时有事儿，都可以把单据转交给其他同事！

#增加退回到指定节点功能
数据支持回退到指定节点。凡事数据流转过的节点，都可以被退回到相应指定节点！

#节点配置优化
1. 增加流程图中显示每个节点设置的可编辑/隐藏/仅可见字段
2. 增加设置节点是否可以退回数据到任意节点
3. 增加设置节点是否可以把数据转交给任意通讯录成员

2017/11/24
 

#申请成功后提示优化
1. 手机弹窗重新申请功能优化
2. 优化申请成功后，查看我的数据

#关联已有数据支持成员字段
成员字段增加支持关联已有数据，可以调取其他表单中的“成员字段”，并且进行关联匹配。

#流程设计优化
流程设计样式调整，流程设计权限设置采用最新基础组件



#工作区增加通讯录备注
管理员可以为工作区人员增加备注，在所有调用部分，都显示备注名称。以便于识别工作区内成员。

2017/11/12
#数据报表功能上线
增加数据图表功能，用户可以自定义报表啦！详细请查看数据报表设置相关介绍。



#支持单条数据打印
增加单条数据打印的功能，通过管理员设置后，成员可以在流程中或被分享的报表中打印单条数据！



 

2017/10/18
 

#Excel数据导出优化
1.增加显示当前选中数目和已有数据条数等优化数据的删除／导出



2017/10/06
 

#数据重新分配负责人
管理员可将数据重新分配负责人，如果负责人离职、负责人出差等，可以交由其他成员处理。

#流程设置-申请人权限限制
申请人类型限制变更，在流程中申请人节点，可以设置“哪些人可填写”，可以设置全部人员可填写，实现“工作区”外部成员，也就是客户、供应商的等合作方对于表单的填写权限。



#新增数据分享查询功能
增加查询功能，可以根据表单内的某个或某几个字段，进行数据查询。将查询报表分享给外部成员，即可实现外部成员查询搜索的功能！



2017/09/26
 

#增加动态负责人功能
在流程中，可以设置“动态负责人”，如部门主管、表单中的邮箱和成员字段、申请人等，都能作为动态负责人的调用数据，点击查看功能详细介绍。



2017/09/16
 

#个人动态样式更新
个人动态更新样式，更便于快速定位到【待处理数据】和【通过/拒绝数据】



#通讯录增加批量邀请用户
可以通过扫描二维码、复制链接，批量填入成员信息来进行邀请。



2017/09/10
#增加工作区
轻流账号体系变更，以【工作区】为单位标注使用区域。每一个账号可以拥有一个【创建的工作区】，可以加入任意个工作区，并且可以成为任意数量工作区的【管理员】。



2017/08/26
#创建人可修改数据
创建人/管理员可以在数据列表中修改/删除数据。

#增加导出excel
可以在数据列表中，选中数条数据导出为excel格式。



#列表中增加显示数据状态
列表中显示当前所处节点（待处理节点），并且可以根据数据所处节点进行筛选。

#发起申请登录后改为站内申请，不再跳转链接


#上传附件，如果是图片，增加图片预览
附件上传字段增加图片的缩略预览，点击后可以放大显示。

#填写/审批节点增加是否开启审批反馈的设置
可以手动开启/关闭审批反馈。无需审批反馈的数据，点击通过/拒绝/提交/退回，直接提交。

#应用发布增加最近发布时间


 

2017/08/18
#应用列表优化
1.增加应用状态／申请通道状态／发布状态的显示

2.增加应用收藏／取消收藏快捷方式



#增加数据使用量的限制
增加数据使用量的限制，可在管理后台中查看，增加对于用户使用量超出限制等情况的错误提示。



#付费用户表单样式自定义
付费用户可以自定义表头颜色／图片，背景颜色／图片



2017/08/07
#添加催办功能
若数据停留在某个流程节点24小时以上，申请人可以选择“催办”提醒节点负责人处理数据。



#自定义填写完成之后的提示内容/跳转链接
填写完成之后，可以跳转链接，或者设置提示内容。



#支持在微信中使用轻流
1.手机端－微信自动登录

2.PC端增加微信扫码登录／注册并绑定／登录并绑定

话不多说，先扫码关注轻流微信服务号再说：



 




























































































































































































































































































































































































































































































































































































































































































































































返回轻流
© Copyright 轻流. | 沪ICP备 16014957号-7
