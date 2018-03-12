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
