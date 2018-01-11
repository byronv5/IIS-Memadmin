安装web平台安装工具;
安装适用于IIS的PHP Manager;
新建网站，物理路径指向memadmin项目;
php_memcache.dll放入C:\Program Files (x86)\PHP\v5.3\ext下面;
IIS网站-功能视图-PHP Manager-PHP Extentions,将php_memcache.dll设置为Enable;
浏览index.php即可出现登录页面。
（本文件夹里的php版本和memcache扩展相一致，无需担心不一致导致的页面报错）