  Application Context 是 spring 中较高级的容器。和 BeanFactory 类似，它可以加载配置文件中定义的 bean，将所有的 bean 集中在一起，当有请求的时候分配 bean。 另外，它增加了企业所需要的功能，
比如，从属性文件从解析文本信息和将事件传递给所指定的监听器。这个容器在 org.springframework.context.ApplicationContext interface接口中定义。ApplicationContext 包含 BeanFactory 所有的功能，
一般情况下，相对于 BeanFactory，ApplicationContext 会被推荐使用。BeanFactory 仍然可以在轻量级应用中使用，比如移动设备或者基于 applet 的应用程序。<br>
  [ApplicationContext介绍](http://book.51cto.com/art/201203/321008.htm)<br>
