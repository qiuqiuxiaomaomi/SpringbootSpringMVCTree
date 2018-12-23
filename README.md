# SpringbootSpringMVCTree
SpringBoot,SpringMVC对比技术研究


<pre>
      spring 家族发展到今天，已经很庞大了，作为一个开发者，如果想要使用 spring 家族一系列的技
      术，需要一个一个的搞配置，然后还有个版本兼容性问题，其实挺麻烦的，偶尔也会有小坑出现，其实
      蛮影响开发进度， spring boot 就是来解决这个问题，提供了一个解决方案吧，可以先不关心如何
      配置，可以快速的启动开发，进行业务逻辑编写，各种需要的技术，加入 starter 就配置好了，直接
      使用，可以说追求开箱即用的效果吧.

      spring 框架有超多的延伸产品例如 boot security jpa etc... 但它的基础就是 spring 的 
      ioc 和 aop ioc 提供了依赖注入的容器 aop 解决了面向横切面的编程 然后在此两者的基础上实
      现了其他延伸产品的高级功能 Spring MVC 呢是基于 Servlet 的一个 MVC 框架 主要解决 WEB 
      开发的问题 因为 Spring 的配置太复杂了 各种 XML JavaConfig hin 麻烦 于是懒人改变世界
      推出了 Spring boot 约定优于配置 简化了 spring 的配置流程

Spring MVC的功能

      Spring MVC提供了一种轻度耦合的方式来开发web应用。

      Spring MVC是Spring的一个模块，式一个web框架。通过Dispatcher Servlet, ModelAndView 
      和 View Resolver，开发web应用变得很容易。解决的问题领域是网站应用程序或者服务开发——URL
      路由、Session、模板引擎、静态Web资源等等。

Spring Boot的功能

      Spring Boot实现了自动配置，降低了项目搭建的复杂度。

      众所周知Spring框架需要进行大量的配置，Spring Boot引入自动配置的概念，让项目设置变得很容
      易。Spring Boot本身并不提供Spring框架的核心特性以及扩展功能，只是用于快速、敏捷地开发新一
      代基于Spring框架的应用程序。也就是说，它并不是用来替代Spring的解决方案，而是和Spring框架
      紧密结合用于提升Spring开发者体验的工具。同时它集成了大量常用的第三方库配置(例如
      Jackson, JDBC, Mongo, Redis, Mail等等)，Spring Boot应用中这些第三方库几乎可以零配置的
      开箱即用(out-of-the-box)，大部分的Spring Boot应用都只需要非常少量的配置代码，开发者能
      够更加专注于业务逻辑。

      Spring Boot只是承载者，辅助你简化项目搭建过程的。如果承载的是WEB项目，使用Spring MVC
      作为MVC框架，那么工作流程和你上面描述的是完全一样的，因为这部分工作是Spring MVC做的而
      不是Spring Boot。

      对使用者来说，换用Spring Boot以后，项目初始化方法变了，配置文件变了，另外就是不需要单独
      安装Tomcat这类容器服务器了，maven打出jar包直接跑起来就是个网站，但你最核心的业务逻辑实现
      与业务流程实现没有任何变化。

      所以，用最简练的语言概括就是：

           Spring 是一个“引擎”；

           Spring MVC 是基于Spring的一个 MVC 框架 ；

           Spring Boot 是基于Spring4的条件注册的一套快速开发整合包
</pre>