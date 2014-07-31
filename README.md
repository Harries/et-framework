<h1><strong>写在前面</strong></h1>
&nbsp;

工作6年有余，一直从事java方面的工作，用过大大小小各种框架，尝试过各种复杂的配置以及不同学习曲线，感觉java的世界是如此杂而乱。借此希望造一个轮子，已简化java web开发，开发者不需要学习更多的知识，只要一个框架就能解决绝大多数日常应用开发中的问题。由于诞生了这个框架，暂且取名为：

<span style="font-size: 13px;">ET-Framework (来自外星人的框架)</span>

&nbsp;
<h1><strong>目标与计划</strong></h1>
&nbsp;

(1)简洁---去掉不必要依赖，尽量减少对外部环境的依赖，使用jdk源码实现的尽量用jdk源码实现

(2)高效---开发效率要高，集成server，支持热部署，动态替换

(3)简单---学习曲线低，几天就可以上手

&nbsp;
<h1>Roadmap</h1>
&nbsp;
<table>
<thead>
<tr>
<th data-column="0">
<div>
<div>序号</div>
</div></th>
<th data-column="1">
<div>
<div>模块名称</div>
</div></th>
<th data-column="2">
<div>
<div>模块说明</div>
</div></th>
</tr>
</thead>
<tbody>
<tr>
<td>1</td>
<td>et-framework</td>
<td>(maven父工程,管理所有的子模块或者是子项目，以及负责整体发布，整体打包，等等)</td>
</tr>
<tr>
<td colspan="1">2</td>
<td colspan="1">et-service</td>
<td colspan="1"> 这个jar 文件是所有应用都要用到的，它包含访问配置文件、创建和管理bean 以及进行Inversion of Control / Dependency Injection（IoC/DI）操作相关的所有类。如果应用只需基本的IoC/DI 支持，引入et-service.jar和et-common.jar 文件就可以了。</td>
</tr>
<tr>
<td colspan="1">3</td>
<td colspan="1">et-web</td>
<td colspan="1"> 这个jar 文件包含ET MVC 框架相关的所有类。包括框架的Servlets，Web MVC框架，控制器和视图支持。当然，如果你的应用使用了独立的MVC 框架，则无需这个JAR 文件里的任何类。</td>
</tr>
<tr>
<td colspan="1">4</td>
<td colspan="1">et-dao</td>
<td colspan="1"> 这个jar 文件包含对ET对JDBC 数据访问进行封装的所有类。和事务访问数据库</td>
</tr>
<tr>
<td colspan="1">5</td>
<td colspan="1">et-common</td>
<td colspan="1"> 这个jar 文件包含ET 框架基本的核心工具类。et 其它组件要都要使用到这个包里的类，是通用的核心的工具类，当然你也可以在自己的应用系统中使用这些工具类</td>
</tr>
</tbody>
</table>
<h1></h1>
<h1><strong>备注</strong></h1>
&nbsp;

采用maven搭建项目，管理依赖以及版本的控制，代码托管在github ，希望大家为中国的开源事业贡献自己的一份力量

基础知识准备：
<ol>
	<li><a style="font-size: 13px;" href="http://www.liuhaihua.cn/?p=826">git和eclipse集成</a></li>
	<li><a href="http://www.liuhaihua.cn/?p=632">maven和eclipse集成</a></li>
</ol>
有疑问请联系liuhaihua@59et.com QQ群号：223082909