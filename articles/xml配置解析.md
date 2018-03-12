# xml配置解析

## spring加载上下文的5种方式

* AnnotationConfigApplicationContext：从一个或多个基于Java的配置类中加载Spring应用上下文。
* AnnotationConfigWebApplicationContext：从一个或多个基于Java的配置类中加载Spring Web应用上下文。
* ClassPathXmlApplicationContext：从类路径下的一个或多个XML配置文件中加载上下文定义，把应用上下文的定义文件作为类资源。
* FileSystemXmlapplicationcontext：从文件系统下的一个或多个XML配置文件中加载上下文定义。
* XmlWebApplicationContext：从Web应用下的一个或多个XML配置文件中加载上下文定义。

xml依赖注入：

```javascript
  <bean id="hdpos4-sys-core.dQueryUtil" class="com.hd123.latin.sys.service.dquery.DQueryUtil">
    <property name="constClassNames">
      <map>
        <entry key="jobDataProcess"
          value="com.hd123.latin.sys.service.jobdataprocess.JobDataProcesses" />
        <entry key="client"
          value="com.hd123.hdpos4.mdata.service.client.client.Clients" />
      </map>
    </property>
  </bean>
```
