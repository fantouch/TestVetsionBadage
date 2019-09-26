# 获取安装
安装 Java SDK 前，先获取安全凭证。在第一次使用云API之前，用户首先需要在腾讯云控制台上申请安全凭证，安全凭证包括 SecretID 和 SecretKey， SecretID 是用于标识 API 调用者的身份，SecretKey是用于加密签名字符串和服务器端验证签名字符串的密钥。SecretKey 必须严格保管，避免泄露。
## 通过 Maven 安装(推荐)
通过 Maven 获取安装是使用 JAVA SDK 的推荐方法，Maven 是 JAVA 的依赖管理工具，支持您项目所需的依赖项，并将其安装到项目中。关于 Maven 详细可参考 Maven 官网 。
1. 请访问[Maven官网](https://maven.apache.org/)下载对应系统Maven安装包进行安装。
2. 为您的项目添加 Maven 依赖项，只需在 Maven pom.xml 添加以下依赖项即可。**注意这里的版本号只是举例,您可以在[Maven仓库](https://search.maven.org/search?q=tencentcloud-sdk-java)上找到最新的版本。**：

    <dependency>
      <groupId>com.tencentcloudapi</groupId>
      <artifactId>tencentcloud-sdk-java</artifactId>
      <!-- go to https://search.maven.org/search?q=tencentcloud-sdk-java and get the latest version. -->
      <!-- 请到https://search.maven.org/search?q=tencentcloud-sdk-java查询最新版本 -->
      <version>3.0.93</version> 
    </dependency>
    ![image](https://img.shields.io/maven-central/v/com.tencentcloudapi/tencentcloud-sdk-java?label=maven最新版本) 

asdfasdf