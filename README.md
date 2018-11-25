# Awesome Ruby China

以下内容来源 [Ruby China](https://ruby-china.org) 社区的精华帖。当然也不局限于社区，有觉得好的内容也欢迎提 Pull Request。

### 目录
<details>
<summary><b>展开目录</b></summary>

- [Ruby China](#awesome-ruby-china)
  - [精彩回帖](#精彩回帖)
  - [Ruby Conf](#ruby-conf)
  - [Rails](#rails)
    - [Rails 版本新特性 / 升级](#rails-版本新特性--升级)
    - [Rails 源码分析 / 简单实现 Rails](#rails-源码分析--简单实现-rails)
    - [Gem 源码阅读](#gem-源码阅读)
    - [ActiveRecord](#activerecord)
    - [ActiveJob / 异步队列 / 定时任务](#activejob--异步队列--定时任务)
    - [Action Cable / WebSocket](#action-cable--websocket)
    - [Action View](#action-view)
    - [Action Mailer / Mail](#action-mailer--mail)
    - [ActiveSupport](#activesupport)
    - [i18n](#i18n)
    - [Rails 技巧](#rails-技巧)
    - [Rails 配置](#rails-配置)
    - [日志文件](#日志文件)
    - [缓存](#缓存)
    - [优化 / 性能统计 / 性能分析](#优化--性能统计--性能分析)
    - [Rails API 服务](#rails-api-服务)
    - [安全](#安全)
    - [全文搜索](#全文搜索)
    - [业务](#业务)
    - [数据库 DB](#数据库-db)
    - [数据仓库](#数据仓库)
    - [异常处理](#异常处理)
    - [GraphQL](#graphql)
    - [部署](#部署)
    - [服务器](#服务器)
    - [Puma](#puma)
    - [Unicorn](#unicorn)
    - [Nginx](#nginx)
    - [Windows Environment](#windows-environment)
    - [重构](#重构)
    - [Gitlab](#gitlab)
    - [测试](#测试)
    - [Rack](#rack)
    - [微信开发](#微信开发)
    - [包管理 / bundler](#包管理--bundler)
    - [Gems 分享 / 创建](#gems-分享--创建)
  - [Ruby](#ruby)
    - [元编程](#元编程)
    - [Ruby 深入 / 高级技巧](#ruby-深入--高级技巧)
    - [并发、多线程、多进程 / 异步](#并发多线程多进程--异步)
    - [Ruby 扩展](#ruby-扩展)
    - [爬虫](#爬虫)
    - [Ruby GC / 内存](#ruby-gc--内存)
    - [Sinatra](#sinatra)
    - [机器学习](#机器学习)
    - [游戏](#游戏)
    - [算法 / 数据结构 / 逻辑](#算法--数据结构--逻辑)
  - [技术总结 / 展望 / 趋势](#技术总结--展望--趋势)
  - [职业经历](#职业经历)
  - [前端](#前端)
    - [Ember](#ember)
  - [计算机知识](#计算机知识)
  - [代码设计](#代码设计)
  - [其他](#其他)

- [《提问的智慧》](https://ruby-china.org/topics/24325)

</details>


## 精彩回帖

* [有考虑使用 Sinatra + ActiveRecord 替换你的 Rails 项目吗](https://ruby-china.org/topics/34951)
* [Ruby 2.6.0-preview1 已发布](https://ruby-china.org/topics/35072)
* [JIT for MRI 开始开发了](https://ruby-china.org/topics/35015)
* [量产型炮灰工程师](https://ruby-china.org/topics/33036)
* [北京面试所感](https://ruby-china.org/topics/32781)
* [又一篇讲为什么从 Python (文中的观点也可以适用于 Ruby) 迁移到 Erlang 的文章](https://ruby-china.org/topics/30467)
* [Happy 2016! AMA * Ask Me Anything :)](https://ruby-china.org/topics/28583)
* [通过「刻意练习」，你才能成为顶尖的程序员](https://ruby-china.org/topics/28553)
* [应届生求个实习职位，怎么就这么难啊？求支招！](https://ruby-china.org/topics/28487)
* [大家觉得 AngularJS 好吗？](https://ruby-china.org/topics/27590)
* [评论 Why I wouldn’ t use rails for a new company](https://ruby-china.org/topics/27500)
* [2015 最新调查：现在的前端工程师都用什么？](https://ruby-china.org/topics/27265)
* [Rails－ 让我欢喜让我忧！](https://ruby-china.org/topics/29336)
* [想问个问题，你们为何选择 Rails？](https://ruby-china.org/topics/21633)
* [我对待技术学习的态度](https://ruby-china.org/topics/19356)
* [GO 的性能真的是很惊人啊](https://ruby-china.org/topics/14364)
* [真的没必要浪费心思在 Go 语言上](https://ruby-china.org/topics/14407)
* [Ruby 性能真的比 Node 差这么多么？](https://ruby-china.org/topics/13442)

## Rails

* [The Rails Doctrine - 中文翻译](https://ruby-china.org/topics/30703)
* [另一篇 The Rails Doctrine - 中文翻译](https://ruby-china.org/topics/31249)
* [DHH: 2017 年 Rails 框架还值得学习吗?](https://ruby-china.org/topics/34762)
* [为什么国外的创业公司更喜欢 Rails?](https://ruby-china.org/topics/25547)
* [為你自己學 Ruby on Rails](https://ruby-china.org/topics/33043)
* [集成论坛包括 Discuz 和 Discourse](https://ruby-china.org/topics/32569)
* [《Rails 指南》发布](https://ruby-china.org/topics/32272)
* [Rails 开发：那些年，我们一起踩过的坑 (剧终)](https://ruby-china.org/topics/24742)
* [Rails Console Tips](https://ruby-china.org/topics/19806)
* [来自 37signals 的 3 个 Rails console 技巧](https://ruby-china.org/topics/3506)
* [Is Rails Slow? by Akira Matsuda](https://ruby-china.org/topics/22558)
* [Ruby on Rails 线程安全代码](https://ruby-china.org/topics/10932)

### Rails 版本新特性 / 升级

* [Rails 3 与 Rails 4 中 try 方法的不同](https://ruby-china.org/topics/22759)
* [Ruby on Rails 升级指南 (3.2 => 4.0)](https://ruby-china.org/topics/15579)
* [Rails 3.2 升级到 Rails 4 中遇到的问题](https://ruby-china.org/topics/21748)
* [Upgrade 到 Rails4 的一些感想](https://ruby-china.org/topics/10672)
* [Rails 4 升级第一弹](https://ruby-china.org/topics/22280)
* [Rails 4.1 的新特性 (译)](https://ruby-china.org/topics/18504)
* [Rails 4-2-stable 参考手册 (Beta)](https://ruby-china.org/topics/26954)
* [Rails 5 正式发布了 - Action Cable, API mode 以及其他新特性介绍](https://ruby-china.org/topics/30422)
* [RAILS API TO BE PART OF RAILS 5](https://ruby-china.org/topics/26212)
* [Rails 5 - 将会有更快的 render collection 以及优化小细节](https://ruby-china.org/topics/25741)
* [Rails 5.1 add delegate_missing_to](https://ruby-china.org/topics/33119)
* [在一个简单项目中探索 Rails 5.1 新功能：yarn 集成和集成测试](https://ruby-china.org/topics/32792)
* [Rails 5.2 新功能详解](https://ruby-china.org/topics/36666)
* [Rails 5.2 中的 Credentials 和 Active Storage](https://ruby-china.org/topics/36081)

### Rails 源码分析 / 简单实现 Rails

* [Rails 中 mattr_accessor 一处文档错误](https://ruby-china.org/topics/23675)
* [Rails 中的 MIME 类型解析规则](https://ruby-china.org/topics/35274)
* [Rails 路由系统源码探索](https://ruby-china.org/topics/22726)
* [源码探索 Rails 路由的处理](https://ruby-china.org/topics/34110)
* [Rails 基础实现学习笔记](https://ruby-china.org/topics/32696)
* [rails s 启动过程分析](https://ruby-china.org/topics/32567)
* [详解 Rails Controller 中的 Callback](https://ruby-china.org/topics/32357)
* [尝试理解 ActionController::Base#render](https://ruby-china.org/topics/31162)
* [Rails 从 Request 到 Response (1)](https://ruby-china.org/topics/31156)
* [Rails 从 Request 到 Response (2)](https://ruby-china.org/topics/31529)
* [尝试理解 ActionDispatch::Routing::RouteSet](https://ruby-china.org/topics/30916)
* [在 Swift 下实现了 Rails 风格的路由库](https://ruby-china.org/topics/29133)
* [Rails 源码分析之 eager_load! 篇](https://ruby-china.org/topics/26866)
* [从头开始写一个 Rails-like web 框架](https://ruby-china.org/topics/21508)

### Gem 源码阅读
* [在 console 中直接开启编辑器查看源码](https://ruby-china.org/topics/8690)
* [阅读 God 源码心得](https://ruby-china.org/topics/27736)
* [Warden 的代码学习](https://ruby-china.org/topics/32842)
* [源码阅读系列 - connection_pool](https://ruby-china.org/topics/27002)
* [Spree 源码导读](https://ruby-china.org/topics/24472)
* [Puma 源代码分析 － 概述](https://ruby-china.org/topics/24378)
* [Puma 源代码分析 － 启动流程](https://ruby-china.org/topics/24393)
* [Puma 源代码分析 － 单进程模式](https://ruby-china.org/topics/24426)
* [Puma 源代码分析 － 集群模式](https://ruby-china.org/topics/24529)
* [Puma 源代码分析 － IO 处理](https://ruby-china.org/topics/24599)
* [Puma 源代码分析 － HTTP 协议解析](https://ruby-china.org/topics/24654)
* [Puma 源代码分析 － 完结篇](https://ruby-china.org/topics/24837)
* [PostgreSQL 的异步操作接口，以及 Ruby 中对应实现](https://ruby-china.org/topics/21370)
* [Sprockets 源码初体验](https://ruby-china.org/topics/16841)
* [Webrick 源码阅读笔记](https://ruby-china.org/topics/15102)
* [五问 Sidekiq](https://ruby-china.org/topics/36825)
* [RabbitMQ Ruby 客户端 Bunny 部分源码解读](https://ruby-china.org/topics/37277)

### ActiveRecord

* [Rails 4.1.5 开始 where 查询也有类似 Mass Assignment 保护了](https://ruby-china.org/topics/21540)
* [Exploring ActiveRecord](https://ruby-china.org/topics/34242)
* [ActiveRecord Store 使用介绍](https://ruby-china.org/topics/32471)
* [!! 注意 delete_all 的坑](https://ruby-china.org/topics/33421)
* [ActiveRecord Enum 实战总结](https://ruby-china.org/topics/32470)
* [详解 has_many 方法在 Active Record 中的运行过程](https://ruby-china.org/topics/32419)
* [浅谈 ActiveRecord 的 N + 1 查询问题](https://ruby-china.org/topics/32364)
* [ActiveRecord 和 Ecto 的联系与对立](https://ruby-china.org/topics/30608)
* [Rails inverse_of 研究](https://ruby-china.org/topics/35374)
* [Mongoid inverse_of not work as well as active_records](https://ruby-china.org/topics/30271)
* [关于在 Rails Model 中使用 Enum (枚举) 的若干总结](https://ruby-china.org/topics/28654)
* [Rails Scopes 预加载](https://ruby-china.org/topics/26323)
* [ActiveRecord Object Instantiate](https://ruby-china.org/topics/23523)
* [ActiveRecord 中的 Callback 浅析](https://ruby-china.org/topics/22809)
* [ActiveRecord 用 bulk_insert 来批量插入数据，提高效率](https://ruby-china.org/topics/29562)
* [Rails 5 新功能 - 实现适用于不同场景的 ActiveRecord 验证](https://ruby-china.org/topics/30470)
* [ActiveRecord 的三种数据预加载形式 - includes, preload, eager_load](https://ruby-china.org/topics/22192)
* [Preload、 Eagerload、 Includes 和 Joins](https://ruby-china.org/topics/17866)

### ActiveJob / 异步队列 / 定时任务

* [RabbitMQ / Sneakers 消息重试机制及源码简析](https://ruby-china.org/topics/34022)
* [Rails 最佳实践 - 定时任务](https://ruby-china.org/topics/32162)
* [Sidekiq 系统信号处理源码分析](https://ruby-china.org/topics/31642)
* [Sidekiq 任务调度流程分析](https://ruby-china.org/topics/31470)
* [使用 Upstart + Inspeqtor 管理你的 Sidekiq (监控、崩溃自动重启、邮件通知)](https://ruby-china.org/topics/29752)
* [[12 台减至 3 台] 用 Golang 重写 Sidekiq 的 worker](https://ruby-china.org/topics/26785)
* [Rails 4.2 中 ActiveJob 的使用](https://ruby-china.org/topics/25209)
* [如何使用 Sidekiq 进行异步处理](https://ruby-china.org/topics/36771)
* [Rails 中用 RabbitMQ 做消息队列 [译]](https://ruby-china.org/topics/22332)
* [Rails 4.2 新增后端任务框架 - Active Job](https://ruby-china.org/topics/21092)
* [Sidekiq 精通 36 分钟](https://ruby-china.org/topics/19891)
* [基于 Sidekiq 的异步任务管理引擎设计](https://ruby-china.org/topics/36850)
* [RabbitMQ / Sneaker 工作方式简析](https://ruby-china.org/topics/37587)

### Action Cable / WebSocket

* [Ruby Web 实时通讯方案剖析 (资料和参会感受)](https://ruby-china.org/topics/34188)
* [支撑ActionCable的底层库](https://www.jianshu.com/p/b462c222862d)
* [聊一聊 ActionCable 背后的技术](https://ruby-china.org/topics/30494)
* [我写了 WebSocket 和 ActionCable 相关的序列文章](https://ruby-china.org/topics/29927)
* [Ruby 的 Websocket Server 发送压缩后的 Binary Frame 格式的数据](https://ruby-china.org/topics/36767)
* [基于 WebSocket 写了一个简单实时的 pusher 工具：SimplePusher](https://ruby-china.org/topics/19357)

### Action View

* [使用 Rails 自带的 Form Builder 来重构你的 Form](https://ruby-china.org/topics/31898)
* [如何理解 form_for 和 form_tag](https://ruby-china.org/topics/21523)
* [看我如何解决 ActionView::MissingTemplate 的问题](https://ruby-china.org/topics/19454)

### Action Mailer / Mail

* [解析邮件碰到的那些坑](https://ruby-china.org/topics/33882)

### ActiveSupport

* [理解 ActiveSupport::Concern](https://ruby-china.org/topics/26208)
* [Active Support 的 Concern 模块来由探究](https://ruby-china.org/topics/32585)
* [谨防 ActiveSupport::Cache::Store 缓存 nil 值](https://ruby-china.org/topics/27900)
* [Rails 中的类加载机制](https://ruby-china.org/topics/26034)
* [ActiveSupport::Autoload 学习](https://ruby-china.org/topics/25021)
* [利用 ActiveSupport::Notifications 在 Rails 中实现 PUB/SUB 模式](https://ruby-china.org/topics/24914)

### i18n

* [注意 I18n.locale 是 thread-local](https://ruby-china.org/topics/31799)

### Rails 技巧

* [如何教会小明实现 Rails 的 Validation](https://ruby-china.org/topics/35273)
* [使用 Subscriber 来管理 Model Callbacks](https://ruby-china.org/topics/32649)
* [容错和速错](https://ruby-china.org/topics/23924)

### Rails 配置

* [Rails 最佳实践之配置管理](https://ruby-china.org/topics/32126)
* [Rails 5 允许对静态资源文件设置 HTTP 头](https://ruby-china.org/topics/30709)
* [Heroku-style config management with capistrano and dotenv](https://ruby-china.org/topics/28356)
* [怎样管理 Linux / Mac 的配置文件](https://ruby-china.org/topics/27834)
* [提高 Ruby 程序员效率的 rc 文件](https://ruby-china.org/topics/26781)
* [Rails Routes 中的两件事](https://ruby-china.org/topics/15270)

### 日志文件

* [简记 Rails 中的 logger 实用技巧](https://ruby-china.org/topics/34663)
* [Rails Log Process](https://ruby-china.org/topics/27523)
* [Rails log 自动分割该怎么配置才正确](https://ruby-china.org/topics/3704)
* [Ruby 原生日志分割已经解决多进程问题？](https://ruby-china.org/topics/36880)

### 缓存

* [Redis 作为缓存服务器的配置](https://ruby-china.org/topics/22761)
* [Web 开发后端缓存思路](https://ruby-china.org/topics/25009)
* [Redis 实战之薄荷 timeline 的优化](https://ruby-china.org/topics/25908)
* [Redis 实现 Cache 系统实践](https://ruby-china.org/topics/27939)
* [Rails 缓存，你应该知道的几件事](https://ruby-china.org/topics/32511)
* [说说 Rails 的套娃缓存机制](https://ruby-china.org/topics/21488)
* [Cache 在 Ruby China 里面的应用](https://ruby-china.org/topics/19436)
* [总结 Web 应用中常用的各种 Cache](https://ruby-china.org/topics/19389)
* [Web 应用的缓存设计模式](https://ruby-china.org/topics/9243)
* [second_level_cache 简介](https://ruby-china.org/topics/5535)
* [在 rails 中使用 HTTP 缓存](https://ruby-china.org/topics/36889)

### 优化 / 性能统计 / 性能分析

* [性能优化案例分析之一：软删除是慢查询的罪魁祸首？](https://ruby-china.org/topics/34540)
* [性能优化案例分析之二：时间区域查询的性能优化](https://ruby-china.org/topics/34571)
* [ancestry 和 closure_tree 的批量读对比](https://ruby-china.org/topics/32802)
* [Rails 3 和 Rails 4 中 ETags 工作原理](https://ruby-china.org/topics/24996)
* [使用 Ruby 处理大型 CSV 文件](https://ruby-china.org/topics/31444)
* [Ruby on Rails 网站大型化之静态资源 CDN 架构](https://ruby-china.org/topics/28666)
* [Ruby Profiler 详解之 StackProf-CPU 和对象分配的采样剖析](https://ruby-china.org/topics/26324)
* [Ruby Profiler 详解之 ruby-prof (I)](https://ruby-china.org/topics/25959)
* [Ruby 中的 Profiling 工具](https://ruby-china.org/topics/25856)
* [InfluxDB + Grafana 快速搭建自己的 NewRelic，分析应用运行情况](https://ruby-china.org/topics/23470)
* [使用 Slack & exception_notification 监控 Rails 异常](https://ruby-china.org/topics/23442)
* [使用 Monit＋Mina 监控服务器](https://ruby-china.org/topics/23176)
* [单机数据抓取性能提升总结篇](https://ruby-china.org/topics/23116)
* [也谈如何构建高性能服务端程序](https://ruby-china.org/topics/22742)
* [性能监控的好工具 - NewRelic 简介](https://ruby-china.org/topics/22379)
* [How Did Tenderlove and Others Speed Up Rails?](https://ruby-china.org/topics/21922)
* [如何降低页面 render 时的耗时以及 CPU 资源](https://ruby-china.org/topics/12008)
* [有人告诉我如果数据量大了就不能做分页了？是这样么？](https://ruby-china.org/topics/10843)

### Rails API 服务

* [使用 Rails 构建 API 实践](https://ruby-china.org/topics/25822)
* [用 Rails 写 API 服务，性能感觉不足，怎么办？](https://ruby-china.org/topics/33620)

### 安全

* [深入 Rails 中的 CSRF Protection](https://ruby-china.org/topics/35199)
* [Rails Cookie 如何解密](https://ruby-china.org/topics/34235)
* [ActionView 的組件有安全問題，請趕快更新 rails-html-sanitizer，並確定是否已經是 1.0.4 或以上](https://ruby-china.org/topics/35303)
* [Web 安全和 Rails](https://ruby-china.org/topics/31114)
* [Paperclip中的服务器端请求伪造（SSRF）漏洞分析](http://www.freebuf.com/news/161453.html)
* [Rails & rails-html-sanitizer 安全性更新](https://ruby-china.org/topics/28853)
* [Rails 与安全](https://ruby-china.org/topics/24635)
* [高手对决 -- 博客服务器被黑的故事](https://ruby-china.org/topics/23848)
* [分享两个博客，其中有提到两个重要的安全漏洞](https://ruby-china.org/topics/23103)
* [SSLv3 的 POODLE 漏洞](https://ruby-china.org/topics/22064)
* [ShellShock 漏洞及 OS X 紧急修复方法](https://ruby-china.org/topics/21720)
* [计时攻击原理以及 Rails 对应的防范](https://ruby-china.org/topics/21380)
* [在 OpenSSL 心脏攻击中 Rubyist 该怎么办](https://ruby-china.org/topics/18511)
* [别用 raw 和 html_safe](https://ruby-china.org/topics/16633)
* [黑客可否修改本地的 cookies 或者 session？](https://ruby-china.org/topics/15814)
* [Rails secret key 泄漏了，是不是逆向计算任意用户 Cookie](https://ruby-china.org/topics/13649)
* [调用外部程序要小心](https://ruby-china.org/topics/12435)
* [HTTPS Best Practices](https://ruby-china.org/topics/11931)
* [Rails 安全性小探](https://ruby-china.org/topics/10603)
* [Rails 这次漏洞有点严重啊](https://ruby-china.org/topics/7941)

### 全文搜索

* [为 Rails 项目升级使用 ElasticSearch 5.x 版本](https://ruby-china.org/topics/34486)
* [在 Rails 项目中管理、自定义配置你的 ElasticSearch indexes](https://ruby-china.org/topics/32428)
* [Elasticsearch analysis & 自定义 analyzers](https://xguox.me/elasticsearch-custom-analyzer.html)
* [ElasticSearch 的分数 (_score) 是怎么计算得出 (2.X & 5.X)](https://ruby-china.org/topics/31934)
* [整合 ElasticSearch 到现有 Rails 项目](https://ruby-china.org/topics/27530)
* [How search and index works (Ruby 语言描述)](https://ruby-china.org/topics/23447)
* [Sunspot 学习笔记](https://ruby-china.org/topics/21473)
* [ElasticSearch 初次使用小结，一起学习进步哈~](https://ruby-china.org/topics/15337)

### 业务

* [[RubyConfChina2017 话题分享] 金数据是如何鉴黄的](https://ruby-china.org/topics/34176)
* [只要六步，轻松添加 Google 两步认证](https://ruby-china.org/topics/34148)
* [FormCore —— 动态表单系统的一种参考实现 (带一点私货技巧)](https://ruby-china.org/topics/33098)
* [权限设计 - Role-based Authorization with Pundit](https://ruby-china.org/topics/26642)
* [Not All Migrations are Equal: Schema vs. Data](https://ruby-china.org/topics/29939)
* [Redis 实现自动输入完成](https://ruby-china.org/topics/28015)
* [重新思考找回忘记密码解决方法](https://ruby-china.org/topics/25080)
* [一个简单的评论过滤系统的实现](https://ruby-china.org/topics/23718)
* [基于地址位置，查询附近的人 ，解决方案及性能分析](https://ruby-china.org/topics/22059)
* [Ruby 实现的简易推荐系统 (译)](https://ruby-china.org/topics/18165)
* [请教如何让 ActiveRecord 的查询按照某个虚拟字段排序](https://ruby-china.org/topics/17612)
* [Third-Party Cookies Is Dead, Long Live First-Party Cookies(跨站 session)](https://ruby-china.org/topics/13589)

### 数据库 DB

* [counter_cache + foreign_key + MySQL = DEADLOCK??](https://ruby-china.org/topics/33235)
* [如何从 MongoDB 迁移到 MySQL](https://ruby-china.org/topics/34421)
* [用 PostgreSQL 的 COPY 导入导出 CSV](https://ruby-china.org/topics/32293)
* [Rails 中乐观锁与悲观锁的使用](https://ruby-china.org/topics/28963)
* [Ruby China on PostgreSQL](https://ruby-china.org/topics/28754)
* [Use MySQL stream for large datasets](https://ruby-china.org/topics/27829)
* [Schema 与数据类型优化小技巧](https://ruby-china.org/topics/26873)
* [MySQL 为什么需要一个主键](https://ruby-china.org/topics/26352)
* [Rails 中的事务处理](https://ruby-china.org/topics/25427)
* [阿里云 Rails 项目调整 RDS MySQL 编码为 utf8mb4 的详细步骤](https://ruby-china.org/topics/24693)
* [MySQL 用 UUID 作为主键，实际使用中有什么问题](https://ruby-china.org/topics/24509)
* [MongoDB 那些坑](https://ruby-china.org/topics/20128)
* [[你还不用 pg?] 坑爹的 MySQL 事务](https://ruby-china.org/topics/19499)
* [Bulk Upsert for MySQL & PostgreSQL](https://ruby-china.org/topics/32424)
* [[译] Rails 数据库最佳实践](https://ruby-china.org/topics/31640)
* [MySQL 慢查询优化实战一例](https://ruby-china.org/topics/26668)
* [MySQL 联合索引 (a,b) 的一些困惑](https://ruby-china.org/topics/27022)
* [Rails Database Migrations 译文](https://ruby-china.org/topics/14277)
* [SQL 通配符真的很糟糕么](https://ruby-china.org/topics/5695)
* [基于 Postgres 实现一个推荐系统](https://ruby-china.org/topics/37522)
* [基于 Postgres 实现一个热度算法](https://ruby-china.org/topics/37629)
* [一招秒杀 N+1 agg 问题](https://ruby-china.org/topics/37712)
* [It's never too late to learn Postgres](https://ruby-china.org/topics/37815)

### 数据仓库

* [ETL with Ruby](https://ruby-china.org/topics/25145)
* [Ruby ETL 工具漫谈](https://ruby-china.org/topics/30023)
* [Data Warehouse Concepts and Overview](https://ruby-china.org/topics/25115)
* [Data Warehouse Schema Design](https://ruby-china.org/topics/25116)

### 异常处理

* [ExceptionTrack - 捕捉 Rails 应用运行期的异常，并存储到数据库](https://ruby-china.org/topics/32325)
* [记一次 Rails 项目异常排查](https://ruby-china.org/topics/32181)
* [简单处理掉所有 Rails ActionController::RoutingError 的错误](https://ruby-china.org/topics/21460)

### GraphQL

* [Ruby on Rails 使用 GraphQL 例子](https://ruby-china.org/topics/33109)
* [在 Rails 项目里使用 Graphql](https://ruby-china.org/topics/32239)

### 部署

* [使用 dokku 部署你的 Rails 应用](https://ruby-china.org/topics/32525)
* [长文慎入：将 Rails 程序部署到 Docker 容器中](https://ruby-china.org/topics/32459)
* [在 Ubuntu 14.04 上使用 Puma 和 Nginx 部署 Rails App](https://ruby-china.org/topics/32451)
* [使用 acme.sh 给 Nginx 安装 Let’ s Encrypt 提供的免费 SSL 证书](https://ruby-china.org/topics/31983)
* [CentOS 7 下 Nginx 安装使用 Let’ s Encrypt 证书的完整过程](https://ruby-china.org/topics/31942)
* [使用 Jenkins 在 Ubuntu 下构建 Rails 持续集成环境](https://ruby-china.org/topics/31857)
* [运维环境简单化 - 容器封装](https://ruby-china.org/topics/31639)
* [为什么 Ruby 程序员应该了解和掌握 Docker](https://ruby-china.org/topics/28209)
* [Rails 到底该选择什么 server](https://ruby-china.org/topics/26854)
* [利用 Mina 自动部署 Rails + Sidekiq + Unicorn](https://ruby-china.org/topics/26661)
* [Rails 中自动布署工具 mina 的经验谈](https://ruby-china.org/topics/25529)
* [Docker 介绍以及其相关术语、底层原理和技术](https://ruby-china.org/topics/22004)
* [Install Ruby The "Postmodern" Way](https://ruby-china.org/topics/20385)
* [多台机器上 Unicorn 共享 Session](https://ruby-china.org/topics/19520)
* [Deploy Rails App With Docker](https://ruby-china.org/topics/18157)
* [淘宝威客站点的部署](https://ruby-china.org/topics/12222)
* [蝉游记网站的部署 Nginx,Unicorn,Capistrano,OOB,Graceful Restart](https://ruby-china.org/topics/12033)
* [赞美 Mina，实在太好用了，写点心得给还在纠结的同学](https://ruby-china.org/topics/9606)
* [Deploy Rails app with JRuby and Dokku](https://ruby-china.org/topics/36865)
* [Capistrano + Rails 5.2 自动化部署](https://ruby-china.org/topics/36899)
* [GitLab, Docker, Ruby on Rails CI/CD 实践](https://ruby-china.org/topics/37638)

### 服务器

* [Ruby 服务器对比](https://ruby-china.org/topics/25276)
* [[译] 为什么我们开发的 Raptor 比 Unicorn 快 4 倍，比 Puma，Torquebox 快 2 倍](https://ruby-china.org/topics/22636)
* [服务器性能讨论...](https://ruby-china.org/topics/11270)
* [Ruby 的多线程应用服务器介绍](https://ruby-china.org/topics/10832)

### Puma

* [记录一次排查 Puma 内存占用过高的问题](https://ruby-china.org/topics/35236)
* [Puma 的线程数量与数据库连接池的关系](https://ruby-china.org/topics/35191)
* [Ruby China 已经正式换成 Puma 来跑了！](https://ruby-china.org/topics/15140)

### Unicorn

* [如何持续监控 Unicorn 的性能指标](https://ruby-china.org/topics/29792)
* [Unicorn 进程如何保证平滑更替?](https://ruby-china.org/topics/36935)

### Nginx

* [利用 Nginx 的 ngx_http_image_filter_module 做实时的图片缩略图](https://ruby-china.org/topics/31498)
* [Nginx + Rails 下如何进行文件的安全下载？](https://ruby-china.org/topics/28951)
* [Unicorn 是如何与 Nginx 通讯的——介绍 Ruby 中的 Unix Socket](https://ruby-china.org/topics/26758)
* [Nginx location 配置踩坑过程分享](https://ruby-china.org/topics/24090)
* [Rails / Nginx 与 Weak Etag](https://ruby-china.org/topics/23193)
* [使用 Rails Asset Pipeline 配合 Nginx 的 gzip_static 优化 tips](https://ruby-china.org/topics/19437)

### Windows Environment

* [Windows 环境添加 Ruby China Gems 源的 SSL 异常问题解决记录](https://ruby-china.org/topics/33843)
* [Window 10 下的开发 Rails](https://ruby-china.org/topics/31872)
* [Rails 在 Windows 下的完整开发环境压缩包 (Ruby 2.1.7 和 2.2.4)](https://ruby-china.org/topics/26191)
* [Windows 下一键安装 Redmine](https://ruby-china.org/topics/37185)

### 重构

* [常见重构手法 (上)](https://ruby-china.org/topics/31956)
* [[译] 重构 Rails MVC 组件的 7 个设计模式](https://ruby-china.org/topics/31742)
* [干掉你代码中的坏味道](https://ruby-china.org/topics/30746)
* [Breaking Up a Monolithic Rails App Without MicroService](https://ruby-china.org/topics/28538)
* [发布 / 订阅模式](https://ruby-china.org/topics/24908)
* [Service Object: What? Why? and How?](https://ruby-china.org/topics/24780)
* [Service Object 整理和小结](https://ruby-china.org/topics/23892)
* [Rails 重构: 利用 Service 优化 Fat Model](https://ruby-china.org/topics/22179)
* [Ruby Code Smells](https://ruby-china.org/topics/16805)

### Gitlab

* [我们如何改造 Gitlab](https://ruby-china.org/topics/34219)
* [我们如何为三万人的公司横向伸缩 GitLab](https://ruby-china.org/topics/30146)

### 测试

* [写测试的基础入门](https://ruby-china.org/topics/33614)
* [理解 Rails 5 中 Controller 和 Integration 测试](https://ruby-china.org/topics/30758)
* [测试的主要作用和必要体现在哪？](https://ruby-china.org/topics/28355)
* [How Minitest works](https://ruby-china.org/topics/27912)
* [“小众”之美——Ruby在QA自动化中的应用](https://tech.meituan.com/ruby_autotest.html)
* [FactoryGirl 的两个技巧: trait 和 association](https://ruby-china.org/topics/22003)
* [DHH: TDD is dead. Long live testing.](https://ruby-china.org/topics/18809)
* [Sidekiq 的测试怎么写](https://ruby-china.org/topics/16702)
* [FactoryGirl 粗浅介绍](https://ruby-china.org/topics/3777)
* [功能测试 vs 整合测试 vs 单元测试](https://ruby-china.org/topics/36835)
* [Goreplay - 使用真实流量测试你的应用](https://ruby-china.org/topics/37756)

### Rack

* [Rack/Rails 服务器获取用户 IP 问题分享](https://ruby-china.org/topics/34778)
* [动态 CDN+ 负载均衡网络条件下，Rails 获取用户真实 IP 的问题](https://ruby-china.org/topics/31608)
* [Ruby Rack及其应用（上）](https://ruby-china.org/topics/31592)
* [Ruby Rack 及其应用 (下)](https://ruby-china.org/topics/33055)
* [Rack Middleware 新的理解](https://ruby-china.org/topics/31737)
* [构建 Rack-based 框架 (Rails/Grape/Sinatra) 的几个 Tricks](https://ruby-china.org/topics/27644)
* [初步深入 Rack (一)](https://ruby-china.org/topics/24166)
* [为什么我们需要 Rack ?](https://ruby-china.org/topics/21517)
* [Rack, 我忽视你了 [已更新]](https://ruby-china.org/topics/15017)
* [Rails on Rack 译文](https://ruby-china.org/topics/14279)
* [Ruby 服务器、Rack、Rack App 三者是如何协同工作的](https://ruby-china.org/topics/13601)

### 微信开发

* [wechat-starter - 5 分钟部署你的微信公众号](https://ruby-china.org/topics/30957)
* [[微信开发] 开发环境搭建](https://ruby-china.org/topics/26443)
* [[微信开发系列] 使用 JS API 实现微信支付功能](https://ruby-china.org/topics/26138)
* [微信开放平台 Omniauth 探索](https://ruby-china.org/topics/25410)

### 包管理 / bundler

* [Ruby 包管理分析](https://ruby-china.org/topics/29475)
* [Gemfile 详解](https://ruby-china.org/topics/26655)
* [Bundler 到底是怎么工作的 (暨 Ruby 依赖管理历史回顾)](https://ruby-china.org/topics/28453)
* [Bundler 的作用及原理](https://ruby-china.org/topics/25530)
* [RVM 与 Bundler 的爱恨情仇](https://ruby-china.org/topics/20836)

### Gems 分享 / 创建

* [WorkflowCore —— SaaS 快速开发套件之工作流引擎](https://ruby-china.org/topics/37555)
* [ActionStore - 一步到位的 Like, Follow, Star, Block ... 等动作的解决方案](https://ruby-china.org/topics/32262)
* [自制开源 Web 框架的 40 天 - em-midori](https://ruby-china.org/topics/31358)
* [midori 百日记](https://ruby-china.org/topics/31921)
* [[译] Awesome Rails Gem 中文版](https://ruby-china.org/topics/31645)
* [完美的 Ruby 图形验证码 Gem - RuCaptcha](https://ruby-china.org/topics/27832)
* [关于 rucaptcha 库验证码显示空白的问题探究及解决](https://ruby-china.org/topics/31015)
* [推荐 rails-template 给大家, 极速构建一个全新又老道的 Rails 5 项目](https://ruby-china.org/topics/30406)
* [weapon，为已有项目，配置 mina 部署，i18n 定制，rails_settings_ui](https://ruby-china.org/topics/26327)
* [Rails 项目 Gem 依赖的社交关系网络关系图及其生成](https://ruby-china.org/topics/26502)
* [Rails 利用 cancan 实现一个优雅可扩展的角色管理系统](https://ruby-china.org/topics/25512)
* [eager_group 修复 n+1 聚合函数问题](https://ruby-china.org/topics/26245)
* [存在内存泄露的 Gem 列表](https://ruby-china.org/topics/27761)
* [记录使用 typhoeus 调用 360 HTTPS API 时碰到的坑](https://ruby-china.org/topics/27491)
* [God 使用手册](https://ruby-china.org/topics/21354)
* [OAuth 2.0 教程: Grape API 整合 Doorkeeper](https://ruby-china.org/topics/14656)
* [刚发了个 gem: triez (加了个全文搜索服务器的例子)](https://ruby-china.org/topics/8587)
* [merit - 用更优雅的方式构建的网站的积分，等级，徽章系统](https://ruby-china.org/topics/3571)
* [分享如何创建一个新 Ruby Gem](https://ruby-china.org/topics/31692)
* [写一个 Gem 需要哪些知识？](https://ruby-china.org/topics/11060)

## Ruby

* [推荐 Ruby ＆ Rails 内部实现文集](https://ruby-china.org/topics/20275)
* [Ruby 中 require,load,autoload,extend,include,prepend 的区别](https://ruby-china.org/topics/35350)
* [基础 Ruby 中 Include, Extend, Load, Require 的使用区别](https://ruby-china.org/topics/25706)
* [1.9.3 的速度](https://ruby-china.org/topics/990)
* [Ruby 1.9+ 的字符编码](https://ruby-china.org/topics/16856)
* [Ruby 2.0 in Detail](https://ruby-china.org/topics/9372)
* [Ruby 2.1 Features PDF](https://ruby-china.org/topics/14361)
* [Ruby 2.2 中实验性的采用 Vfork](https://ruby-china.org/topics/23604)
* [Ruby 2.3 中的魔法注释 # frozen_string_literal: true](https://ruby-china.org/topics/35215)
* [Ruby 安全调用运算符 (&.)](https://ruby-china.org/topics/35195)
* [Cool things in Ruby in 2018](https://ruby-china.org/topics/34964)
* [Ruby 2.5.0 已发布](https://ruby-china.org/topics/34771)
* [Ruby 用户指南 (简体中文)-初版发布](https://ruby-china.org/topics/34066)
* [Getting started with JRuby](https://ruby-china.org/topics/28960)
* [在 Ruby 中使用 DATA 和 __END__ 将代码和数据混合](https://ruby-china.org/topics/27040)
* [这是我读过关于 constant lookup 讲的最好的文章，不要问我为什么](https://ruby-china.org/topics/26890)
* [如何在源码阶段写出更快的 Ruby](https://ruby-china.org/topics/25728)
* [分享给同是新手的 Rubyists，简单说明了些 Ruby 基础知识](https://ruby-china.org/topics/25565)
* [Ruby 中的函数式编程](https://ruby-china.org/topics/25389)
* [总结一下 Ruby 中的对象和类模型](https://ruby-china.org/topics/25325)
* [10 个 Ruby 技巧提升你的代码](https://ruby-china.org/topics/24903)
* [透彻理解 Ruby 中的 return](https://ruby-china.org/topics/24783)
* [[译] Five Ruby Methods You Should Be Using](https://ruby-china.org/topics/23784)
* [用 Ruby 开发命令行工具的一些 tips](https://ruby-china.org/topics/22714)
* [用 Block 重构代码的几种方法](https://ruby-china.org/topics/22016)
* [Ruby 中的 OpenStruct 详解](https://ruby-china.org/topics/21617)
* [Performance Differences in Ruby](https://ruby-china.org/topics/19207)
* [Ruby 里的 %Q, %q, %W, %w, %x, %r, %s, %i (译)](https://ruby-china.org/topics/18512)
* [反面模式：用迭代循环来构建集合 (译自 thoughtbot)](https://ruby-china.org/topics/18164)
* [Ruby 中那些你绕不过的「坑」(译)](https://ruby-china.org/topics/17742)
* [Ruby socket 库中的 BasicSocket#recv 方法的一个疑问](https://ruby-china.org/topics/13852)
* [聊聊 Ruby 中的 block, proc 和 lambda](https://ruby-china.org/topics/10414)
* [Ruby Web 框架简单介绍](https://ruby-china.org/topics/9851)
* [Ruby 社区应该去 Rails 化了](https://ruby-china.org/topics/9765)
* [Ruby 内联私有方法与原理](https://ruby-china.org/topics/37080)
* [修改 Ruby 核心类和模块的方法](https://ruby-china.org/topics/37598)

### 元编程

* [元编程 进一步理解 metaclass](https://ruby-china.org/topics/25707)
* [元编程 基础方法整理](https://ruby-china.org/topics/25691)
* [从 Rails 中学习元编程的使用场景](https://ruby-china.org/topics/32645)
* [Ruby 和元编程的故事 - 第 2 回: 类与模块，Ruby 的绝代双骄](https://ruby-china.org/topics/1581)

### Ruby 深入 / 高级技巧

* [Ruby 位运算符详解](https://ruby-china.org/topics/35247)
* [Ruby 2.4 哈希表 (Hash) 的变化](https://ruby-china.org/topics/32549)
* [Ruby + OMR JIT 简介](https://ruby-china.org/topics/31764)
* [探秘模块混入 (include Module) 背后的故事](https://ruby-china.org/topics/30378)
* [非动态，也非静态，Ruby 3 Typing 的第三条路](https://ruby-china.org/topics/31763)
* [千万别构建超过 23 个字符的 Ruby 字符串](https://ruby-china.org/topics/28104)
* [将您的 Ruby 应用编译成单个可执行文件](https://ruby-china.org/topics/34684)
* [用 Ruby 简单模拟 Lambda 演算](https://ruby-china.org/topics/33961)
* [[译] (上) 高级元编程指南：创建一个 Ruby DSL](https://ruby-china.org/topics/33712)
* [关于 eval 是否 evil 的一些想法](https://ruby-china.org/topics/31465)
* [Ruby 是如何解释运行程序的](https://ruby-china.org/topics/28040)
* [DIY Ruby CPU 分析 [更新到 Part IV]](https://ruby-china.org/topics/27855)
* [Ruby 中一些重要的钩子方法](https://ruby-china.org/topics/25397)
* [试译 Ruby 源码解读](https://ruby-china.org/topics/22386)
* [Ruby | Rails - 浅拷贝 | 深拷贝](https://ruby-china.org/topics/22164)
* [Ruby 的方法查找与 method_missing](https://ruby-china.org/topics/21304)
* [发个很好的 Ruby VM 的学习资料](https://ruby-china.org/topics/13721)
* [Teahour 20 期：跟 @luikore 和 @skandhas 一起讨论底层开发和 Ruby VM](https://ruby-china.org/topics/11956)
* [浅谈尾递归](https://ruby-china.org/topics/36896)
* [在 Ruby 中实现一个 WebSocket 掩码](https://ruby-china.org/topics/37133)

### 并发、多线程、多进程 / 异步

* [Good news everyone! Ruby 又要添加绿色线程了, Thread::Green (可以理解为 go 的 goroutine)](https://ruby-china.org/topics/34992)
* [Ruby 异步编程奥德赛](https://ruby-china.org/topics/34187)
* [Ruby 的并发, 进程, 线程, GIL, EventMachine, Celluloid](https://ruby-china.org/topics/33987)
* [浅谈 Ruby 中的并发， 并行和全局锁](https://ruby-china.org/topics/32902)
* [Ruby 3 Guilds 并发模型](https://ruby-china.org/topics/31348)
* [Fiber and EventMachine 一些心得](https://ruby-china.org/topics/29041)
* [无人知晓的 GIL](https://ruby-china.org/topics/28415)
* [实例说明 Ruby 多线程的潜力和弱点](https://ruby-china.org/topics/11248)
* [ruby 线程使用举例](https://ruby-china.org/topics/8625)
* [关于ruby多线程编程中的join](http://www.letiantian.me/2014-08-30-ruby-thread-join/)
* [Grape on Rails + Puma 线程安全性的讨论?](https://ruby-china.org/topics/30188)

### Ruby 扩展

* [使用 Ruby FFI 调用 Go 函数：十倍效率提升](https://ruby-china.org/topics/34921)

### 爬虫

* [Ruby 的爬虫世界](https://ruby-china.org/topics/31784)
* [斗鱼弹幕助手 (Ruby 版本)](https://ruby-china.org/topics/28968)
* [爬虫获取 ruby-china 职位地区分布数量统计](https://ruby-china.org/topics/22449)
* [the_scrap - 提取了个网页抓取的 Gem](https://ruby-china.org/topics/21104)

### Ruby GC / 内存

* [画说 Ruby 与 Python 垃圾回收](https://ruby-china.org/topics/28127)
* [Ruby 的内存陷阱](https://ruby-china.org/topics/25584)
* [How Ruby Uses Memory](https://ruby-china.org/topics/25790)
* [关于 RoR 内存问题的讨论](https://ruby-china.org/topics/35238)
* [升级 Ruby 2.1 以及 GC 调整](https://ruby-china.org/topics/17575)
* [Ruby 2.2 中的增量式垃圾回收](https://ruby-china.org/topics/24242)
* [Ruby 2.2 的 可回收 symbol](https://ruby-china.org/topics/21498)
* [Ruby memory leak detection](https://ruby-china.org/topics/9737)
* [Ruby GC 自述](https://ruby-china.org/topics/37118)
* [Ruby 的好朋友 -- jemalloc](https://ruby-china.org/topics/37699)

### Sinatra

* [Sinatra 扩展机制原理分析](https://ruby-china.org/topics/33512)
* [用 Ruby 快速开发一个静态服务全过程](https://ruby-china.org/topics/27956)
* [How Ruby Uses Memory](https://ruby-china.org/topics/25790)
* [Ruby Web API Server 小评测](https://ruby-china.org/topics/11249)
* [How Sinatra Works](https://ruby-china.org/topics/7921)

### 机器学习

* [Ruby 机器学习尝试 — 训练 Atari (雅达利) 打弹球游戏 AI](https://ruby-china.org/topics/35478)
* [商科背景， 5 周完成 deeplearning.ai 课程的过程、心得与总结](https://ruby-china.org/topics/35031)
* [Ruby 的机器学习项目](https://ruby-china.org/topics/13361)

### 游戏

* [Ruby + GTK 3 实现经典小游戏，坦克大战](https://ruby-china.org/topics/33227)
* [一套 Ruby 网游服务器框架](https://ruby-china.org/topics/20865)

### 算法 / 数据结构 / 逻辑

* [关于算法, 我们该学什么?](https://ruby-china.org/topics/16750)
* [challenge #1 - #6 update 06/03](https://ruby-china.org/topics/33040)
* [Byakuren：一个 C 实现的主题色提取库](https://ruby-china.org/topics/32437)
* [动态密码生成算法介绍与实现](https://ruby-china.org/topics/32333)
* [Dijkstra 最短路径算法的理解与实现](https://ruby-china.org/topics/32226)
* [扑克牌的练习题](https://ruby-china.org/topics/30918)
* [我为什么要使用哈希](https://ruby-china.org/topics/27700)
* [理解红黑树](https://ruby-china.org/topics/22499)
* [经典排序算法资料及 ruby 实现](https://ruby-china.org/topics/20569)
* [领略一下快排的魅力](https://ruby-china.org/topics/18052)
* [面试时候如何用 Ruby 写一个最短二分查找代码](https://ruby-china.org/topics/16601)
* [昨天有面试的算法题目,当抛砖引玉了](https://ruby-china.org/topics/12837)

## 技术总结 / 展望 / 趋势

* [友好速搭的技术栈 for Ruby off Rails](https://ruby-china.org/topics/21970)
* [2014 年 Web 高手都在做什么 -- 一个 Rails 开发者的视角](https://ruby-china.org/topics/23365)
* [Beansmile 2016年 技术管理总结](https://ruby-china.org/topics/32033)
* [Strikingly 团队 2017 技术展望](https://ruby-china.org/topics/32307)
* [2016 年后 Web 开发趋势是什么](https://ruby-china.org/topics/29901)
* [Elixir 会成为明日之星么？似乎是](https://ruby-china.org/topics/31736)
* [[译] 再见微服务，从 100 多个问题儿童到一个超级明星](https://ruby-china.org/topics/37189)

## 职业经历

* [十年磨一剑，从菜鸟到 CTO —— 我的故事](https://ruby-china.org/topics/31703)
* [译文：一个 Perl 程序员职业生涯的中年危机](https://ruby-china.org/topics/34079)
* [[经验之谈] 转行做程序员的 8 个月](https://ruby-china.org/topics/19961)
* [学习编程没有捷径，需要的是热情与毅力](https://ruby-china.org/topics/19396)
* [从士兵到程序员再到 SOHO 程序员](https://ruby-china.org/topics/14189)
* [从士兵到程序员再到 SOHO 程序员 (二) - 求职](https://ruby-china.org/topics/16192)
* [从士兵到程序员再到 SOHO 程序员 (三) - 游击战与阻力](https://ruby-china.org/topics/17597)
* [工作也旅行 - 工作机会](https://ruby-china.org/topics/17008)
* [工作也旅行 - 跨洋远程面试](https://ruby-china.org/topics/17092)
* [工作也旅行 - 工作日常](https://ruby-china.org/topics/27162)
* [介绍我的项目 ＋ 找一份工作](https://ruby-china.org/topics/15217)
* [[译] 炒与被炒](https://ruby-china.org/topics/14633)

## 前端

* [使用 Chrome Timeline 来优化页面性能](https://ruby-china.org/topics/30788)
* [在 Rails 中实现拖拽排序功能](https://ruby-china.org/topics/35481)
* [看完离编写高性能的 JavaScript 又近了一步](https://ruby-china.org/topics/34668)
* [知人的前端开发之 “道”](https://ruby-china.org/topics/34230)
* [Rails 5.1 使用 yarn 和 webpack 实战 (vue, 构建等)](https://ruby-china.org/topics/32904)
* [心痒痒之二用 Vue.js 写的 Ruby China 山寨版](https://ruby-china.org/topics/32268)
* [在 Rails 中使用 Yarn 管理三方 assets](https://ruby-china.org/topics/31625)
* [基于 React.js + Redux + Bootstrap 的 Ruby China 示例](https://ruby-china.org/topics/31287)
* [Turbolinks 5 概述及实现原理](https://ruby-china.org/topics/30760)
* [[翻译] React.js 的 Rails 开发者指南](https://ruby-china.org/topics/30037)
* [同构化的 React + Redux 服务端渲染](https://ruby-china.org/topics/29352)
* [(番外篇) 同构化的 React + Redux 服务端渲染](https://ruby-china.org/topics/29835)
* [npm 没有 Gemfile.lock 这样的机制，怎么想的？](https://ruby-china.org/topics/29777)
* [Rails 用 RJS 简单有效的实现页面局部刷新](https://ruby-china.org/topics/29046)
* [Cjsx 还是挺好使的...](https://ruby-china.org/topics/27985)
* [还在纠结 Flux 或 Relay，或许 Redux 更适合你](https://ruby-china.org/topics/26944)
* [前端架构分享](https://ruby-china.org/topics/25802)
* [Gulp 基础任务配置](https://ruby-china.org/topics/25477)
* [浅谈 Underscore.js 中 _.throttle 和 _.debounce 的差异](https://ruby-china.org/topics/22494)
* [从剪切版里粘贴图片: HTML5 Clipboard API hacking](https://ruby-china.org/topics/17266)
* [Javascript 跨子域通讯](https://ruby-china.org/topics/7598)
* [用现代 Rails 逃离单页面应用 “兔子洞”](https://ruby-china.org/topics/37531)

### Ember

* [推荐一个学 Ember 的资源，专门针对有 Rails 基础的同学](https://ruby-china.org/topics/32554)
* [Ember Data 概述](https://ruby-china.org/topics/28295)
* [React vs Ember by Alex Matchneer at EmberNYC meetup](https://ruby-china.org/topics/27907)
* [为什么我偏爱 Ember.js 胜过 Angular 和 React.js](https://ruby-china.org/topics/32634)
* [从恨到爱——如何使用 Ember 开发应用程序](https://ruby-china.org/topics/31451)
* [[Thinking in Ember 2] 组件化的探索——路漫漫其修远兮，还得 Up & Down 啊～](https://ruby-china.org/topics/28230)
* [[Tips on Ember 2] UI 布局与应用状态的关系处理](https://ruby-china.org/topics/27258)
* [[Tips on Ember 2] 如何尝试 angle-bracket component](https://ruby-china.org/topics/27155)
* [求 Ember.js 开发经验的分享](https://ruby-china.org/topics/24646)

## 计算机知识

* [IO 模式和 IO 多路复用](https://ruby-china.org/topics/35472)
* [网络协议——写给每个懂点编程的同学](https://ruby-china.org/topics/33160)
* [如何通过 HSB 颜色模式构建夜间模式](https://ruby-china.org/topics/32711)
* [《GPU Animation: Doing It Right》| GPU 动画的正确打开方式](https://ruby-china.org/topics/32052)
* [Docker 在 Coding WebIDE 项目中的运用](https://ruby-china.org/topics/26157)

## 代码设计

* [Feed 流设计 (一)：如何对多态内容进行抽象？](https://ruby-china.org/topics/37548)
* [Feed 流设计 (二)：拉模式 Vs 推模式](https://ruby-china.org/topics/37549)

## 其他

* [SQL Style Guide](https://ruby-china.org/topics/37464)
* [写出好的 commit message](https://ruby-china.org/topics/15737)
* [围绕 MacBook Pro 打造的工作站设计日志](https://ruby-china.org/topics/30343)
* [如何读文档？](https://ruby-china.org/topics/33517)
* [產品的系統性成長 ( Growth ) 方法](https://ruby-china.org/topics/28922)
* [理解本质的 REST](https://ruby-china.org/topics/34341)
* [如何用 GitBook 结合 markdown 写一本开源书籍](https://ruby-china.org/topics/34627)
* [普通码农的思维总结](https://ruby-china.org/topics/32679)
* [程序员如何写简历和面试](https://ruby-china.org/topics/31041)
* [关于创业与产品的老文整理](https://ruby-china.org/topics/13209)
* [如何在中国的一座小城市注册公司](https://ruby-china.org/topics/32556)
* [咨询小公司网络配置方案](https://ruby-china.org/topics/26055)
* [macOS 日常使用技巧小记](https://ruby-china.org/topics/31870)
* [周末到了，来段代码压压惊](https://ruby-china.org/topics/31706)
* [手把手将 Vim 打造成开发 Ruby 和 Rails 的强大 IDE](https://ruby-china.org/topics/25295)
* [《Linux 命令行》中文版 PDF 上线了，epub 也上了](https://ruby-china.org/topics/21831)
* [minimagick 使用 strip 后图片变大](https://ruby-china.org/topics/21724)
* [一张图理解 Git 对象模型](https://ruby-china.org/topics/20723)
* [怎样快速学习一门新技术](https://ruby-china.org/topics/19578)
* [怎样成为一个优秀的初级开发者](https://ruby-china.org/topics/19375)
* [Web 中文字体应用指南](https://ruby-china.org/topics/14005)
* [远程工作经验谈 - 如何适应以及如何管理团队](https://ruby-china.org/topics/12738)
* [六一在家折腾个 WALL·E 给闺女玩 (已更新：Audio & Text to Speech)](https://ruby-china.org/topics/11436)
* ["Elixir Things" - 今天在公司内部做的演讲，对 Elixir 感兴趣的可以来看看](https://ruby-china.org/topics/37718)
* [使用 Ruby 实现 Erlang Process -- 8s spawn 一百万 “process”](https://ruby-china.org/topics/37750)
* [浅谈 Markdown 编译器](https://ruby-china.org/topics/37790)
