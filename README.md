# 中文简介 #

CCppCMS(custom CppCMS)是基于CppCMS的Web开发框架，旨意为使用C++高效率的构建高性能的Web程序。
CppCMS是免费的高性能的Web开发框架（而不是一个CMS），旨在为快速Web应用开发:
1. 高负载的应对
2. 它采用modern C + +作为主要开发语言，以达到第一的目标。
3. 它的目的是对网站的发展，而不是“喜欢GUI”Web应用程序


但是CppCMS在日常Web开发并不完美：
1. CppCMS只提供了MVC的基础工具及基础库，并没有提供一个通用的基础Web框架。
2. 没有提供完整的URI Router的配置
3. CppDB只适用于关系数据库（MySQL和PostgreSQL，sqlite3）的Api
4. CppDB没有支持Nosql（MongoDB，Tokyo Cabinet, Redis等）Api
5. CppDB没有支持分布式缓冲（Memcache， Ehcache）的Api

根据的CppCMS的劣势和优势，CCppCMS应该以以下基本原则：
1. CCppCMS主要有几个组件。
> a. CppCMS
> b. CppDB独立的C ++连接库，支持MySQL，PostgreSQL中，sqlite3的数据库和通用的ODBC驱动程序）。
2. CCppCMS自定义。
a. 自定义Layout，例如Control、Service、Dao和Dal。
b. 自定义Dal的API。
3. CCppCMS应具备的强大配置项。
4. 完整的路由器配置。
5. 自动构建新的Web项目
6. 自动部署