- 测试使用OkHttp3与Retrifit发送Http请求
- 注意AM文件 添加以下配置
  - `android:networkSecurityConfig="@xml/network_security_config"`
  - 在res/xml/network_security_config.xml中
  - ```xml
    <?xml version="1.0" encoding="utf-8"?>
    <network-security-config>
        <!-- 禁用明文流量请求的检查-->
        <base-config cleartextTrafficPermitted="true"/>
    </network-security-config>
    ```
- 
