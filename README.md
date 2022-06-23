# w_1319
wetech-cms内容管理系统源码
<br/></br>
[下载地址](https://www.uuid2.com/1319.html "下载地址")
<br/></br>
<h3>源码简介：</h3>
<p>wetech cms是本人自己整合开发的一套内容管理系统。旨在开发一个通用的、可持续开发集成的、方便扩展的cms系统。<p>
<p>首页使用freemarker完全静态化处理，减轻服务器和数据库的压力<p>
<p>后台相关js只在第一次登录时加载，各功能网页通过AJAX load到content div中，包括异步前后台表单验证，所有的请求都是通过ajax来完成。<p>
<p>批量删除功能，查询、新增、修改全部在一个网页当中，减少与服务器交互<p>
<p>对datatables进行封装，增删改查基本的操作封装成插件，降低开发难度<p>
<p>严格的代码规范，对于每个类都有对应的单元测试覆盖<p>
<p>wetech-parent：是所有子模块的父类，同时也是项目聚合器，以及版本申明管理，无实质代码<p>
<p>wetech-basic-common：主要是放一些通用工具类<p>
<p>wetech-basic-hibernate：对hibernate进行封装，目前就放了IBaseDao和BaseDao<p>
<p>wetech-core：项目核心模块，用来放POJO、DAO对象，以及ORM映射<p>
<p>wetech-topic：服务层文章相关<p>
<p>wetech-user：服务层用户相关<p>
<p>wetech-web：用来放前台页面，以及控制层相关代码<p>
<p>后端技术<p>
<p>Spring Framework    容器    4.3.5.RELEASE<p>
<p>SpringMVC    MVC框架    4.3.5.RELEASE<p>
<p>Hibernate    ORM框架    4.2.0.Final<p>
<p>Maven    项目构建管理    4.0.0<p>
<p>Freemarker    模板引擎    2.3.23<p>
<p>Logback    日志组件    1.1.3<p>
<p>Dbcp2    数据库连接池    2.1.1<p>
<p>Hibernate Validator    后端校验框架    5.4.2.Final<p>
<p>DWR    WEB远程调用框架    3.0.1-RELEASE<p>
<p>Thumbnailator    生成高质量缩略图的Java类库    0.4.3<p>
<p>jQuery    优秀的Javascript库    3.1.1<p>
<p>Amaze UI    前端框架    2.7.2 <p>
<p>DataTables    数据表格    1.10.16 <p>
<p>Layer    jQuery弹出层插件    3.0.1<p>
<p>ZTree    jQuery树插件    3.5.12 <p>
<p>WangEditor    轻量级web富文本编辑器    2.1.22<p>
<p>JDK1.8+<p>
<p>MySQL5.6+<p>
<p>Tomcat7.0+/jetty9.0+<p>
<p>Maven3.0+<p>
<p>通过git下载源码<p>
<p>创建数据库wetech_cms，数据库编码为UTF-8<p>
<p>执行docs/sql/init.sql文件，初始化数据<p>
<p>修改wetech-core模块下jdbc.properties文件，更改MySQL账号和密码<p>
<p>在项目根模块执行【mvn clean package】<p>
<p>在wetech-core模块执行【mvn jetty:run】命令，即可运行项目<p>
<p>项目访问路径：http://localhost:8888/wetech-cms<p>
<p>账号密码：admin/123456<p>
<h3>截图：</h3>
<img src="https://www.uuid2.com/wp-content/uploads/img/202111/e0135e5566.gif" alt="wetech-cms内容管理系统源码">
