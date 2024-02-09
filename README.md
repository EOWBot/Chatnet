本网站使用[Chatnetv1.10](https://support.oncodes.com/help-center/articles/1/2/25/changelog)搭建！

1. **环境**：PHP7.4+  能复写规则的Apache 2.4+（NGINX某些功能可能出现问题） MySQL5.6+

2. **PHP扩展**：cURL扩展  MBString扩展  GD扩展  Json扩展  Zip扩展  *IMAP扩展  FileInfo扩展  Exif扩展*（这些没有内置）

3. **配置**：Nginx 服务器配置文件中添加

   ```nginx
       location / {
           try_files $uri $uri/ /index.php?$args;
       }
   ```

4. **数据库**：创建排序规则为 ***utf8mb4_unicode_ci***的数据库

5. **安装**：确保所有文件权限都为 **644**，所有目录权限都为 **775**，浏览器访问 `您的域名/install` 以运行安装程序，激活码随意填

6. **SSL**：如果要用SSL请在安装前配置（如安装成功后个别功能无法使用，请确保您已为站点配置 SSL）

**原版文档：<a href="https://support.oncodes.com/help-center/articles/1/2/1/system-requirements">Chatnet文档🐱</a>**  **汉化文档：<a href="https://futa.gitbook.io/chatnet/install/geng-xin-ri-zhi">第三方文档👓</a>(更新中)**

**支持正版，从你我做起！！！[购买地址](https://codecanyon.net/item/chatnet-php-ajax-chat-room-private-chat-script/28419241)**



> **开源与你我同在**

---

为防止侵权网站建设设置并未放出，请谅解（有些人真的伤透我们的心了）   ————EndofWorld团队开发组至上