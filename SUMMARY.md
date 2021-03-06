# Summary

* [concepts](concepts/concepts.md)
  * [Assets](concepts/Assets/Assets.md)
    * [默认任务](concepts/Assets/DefaultTasks.md)
    * [禁用Grunt](concepts/Assets/DefaultTasks.md)
    * [任务自动化](concepts/Assets/TaskAutomation.md)
  * [Blueprints](concepts/Blueprints/Blueprints.md)
    * [Blueprint Actions](concepts/Blueprints/Blueprint Actions.md)
    * [Blueprint Routes](concepts/Blueprints/Blueprint Routes.md)
  * [Configuration](concepts/Configuration/Configuration.md)
    * [`config/local.js`文件](concepts/Configurationk/localjsfile.md)
    * [使用`.sailsrc`文件](concepts/Configurationk/usingsailsrcfiles.md)
  * [控制器](concepts/Controllers/Controllers.md)
    * [生成控制器](concepts/Controllers/GeneratingControllers.md)
    * [路由到控制器](concepts/Controllers/RoutingToControllers.md)
  * [Custom Responses](concepts/Custom Responses/Custom Responses.md)
    * [添加自定义的响应](concepts/Custom Responses/AddingCustomResponse.md)
    * [默认响应](concepts/Custom Responses/DefaultResponses.md)
  * [Deployment](concepts/Deployment/generics.md)
    * [FAQ](concepts/Deployment/FAQ.md)
    * [Hosting](concepts/Deployment/Hosting.md)
    * [可伸缩的](concepts/Deployment/Scaling.md)
  * [Extending Sails](concepts/extending-sails/extending-sails.md)
    * [适配器](concepts/extending-sails/Adapters/Adapters.md)
      * [罗列可用的适配器](concepts/extending-sails/Adapters/adapterList.md)
      * [自定义的适配器](concepts/extending-sails/Adapters/customAdapters.md)
    * [生成器](concepts/extending-sails/Generators/Generators.md)
      * [可用的生成器](concepts/extending-sails/Generators/generatorList)
      * [自定义的生成器](concepts/extending-sails/Generators/customGenerators.md)
    * [钩子](concepts/extending-sails/Hooks/Hooks.md)
      * [创建一个可安装的钩子](concepts/extending-sails/Hooks/installablehooks.md)
      * [创建一个工程钩子](concepts/extending-sails/Hooks/projecthooks.md)
      * [在一个Sails App中使用钩子](concepts/extending-sails/Hooks/usinghooks.md)
      * [钩子技术规范](concepts/extending-sails/Hooks/hookspec/hookspec.md)
        * [`configure()`](concepts/extending-sails/Hooks/hookspec/configure.md)
        * [`defaults`](concepts/extending-sails/Hooks/hookspec/defaults.md)
        * [`initialize(cb)`](concepts/extending-sails/Hooks/hookspec/initialize.md)
        * [`routes`](concepts/extending-sails/Hooks/hookspec/routes.md)
  * [File Uploads](concepts/File Uploads/declaration_merging.md)
    * [上传到Amazon S3](concepts/File Uploads/uploading-to-amazon-s3.md)
    * [上传到Mongo GridFS](concepts/File Uploads/uploading-to-mongo-gridfs.mds)
  * [Globals](concepts/Globals/Globals.md)
    * [禁用全局变量](concepts/Globals/DisablingGlobals.mds)
  * [Internationalization](concepts/Internationalization/Internationalization.md)
    * [区域设置](concepts/Internationalization/Locales.md)
    * [动态翻译内容](concepts/Internationalization/TranslatingDynamicContent.md)
  * [Logging](concepts/Logging/Logging.md)
    * [自定义日志消息](concepts/Logging/Custom log messages.md)
  * [中间件](concepts/Middleware/Middleware.md)
    * [常见的默认值](concepts/Middleware/ConventionalDefaults.md)
  * [ORM](concepts/ORM/ORM.md)
    * [适配器](concepts/ORM/Associations/Associations.md)
      * [一对一](concepts/ORM/Associations/OnetoOne.md)
      * [一对多](concepts/ORM/Associations/OnetoMany.md)
      * [多对多](concepts/ORM/Associations/ManytoMany.md)
      * [单向连接](concepts/ORM/Associations/OneWayAssociation.md)
      * [直达的关联](concepts/ORM/Associations/ThroughAssociations.md)
      * [支配](concepts/ORM/Associations/Dominance.md)
    * [属性值](concepts/ORM/Attributes.md)
    * [生命周期回调](concepts/ORM/Lifecyclecallbacks.md)
    * [模型的设置](concepts/ORM/model-settings.md)
    * [模型](concepts/ORM//Models.md)
    * [Waterline查询语言](concepts/ORMs/Querylanguage.md)
    * [校验](concepts/ORM/Validations.md)
  * [Policies](concepts/Policies/Policies.md)
    * [Sails + Passport的认证与权限](concepts/Policies/SailsAndPassport.md)
  * [可编程地使用Sails](concepts/Programmatic Usage/Programmatic Usage.md)
    * [可编程方法的提示和技巧](concepts/Programmatic Usage/Tips and Tricks.md)
  * [实时通信(aka Sockets)](concepts/Realtime/Realtime.md)
    * [从一个服务器中发送实时消息到多个客户端](concepts/Realtime/On the client.md)
    * [客户端和服务器之间的实时通信](concepts/Realtime/On the server.md)
    * [在多服务器(也就是"集群")环境下的实时通信](concepts/Realtime/Multi-server environments.md)
  * [Routes](concepts/Routes/Routes.md)
    * [自定义路由](concepts/Routes/RouteTargetSyntax.md)
    * [URL Slugs](concepts/Routes/URLSlugs.md)
  * [Security](concepts/Security/Security.md)
    * [点击劫持](concepts/Security/Clickjacking.md)
    * [内容安全策略(CSP)](concepts/Security/ContentSecurityPolicy.md)
    * [CORS(Cross-Origin Resource Sharing)](concepts/Security/CORS.md)
    * [CSRF](concepts/Security/CSRF.md)
    * [DDOS](concepts/Security/DDOS.md)
    * [P3P](concepts/Security/P3P.md)
    * [XSS](concepts/Security/XSS.md)
    * [套接字劫持](concepts/Security/SocketHijacking.md)
    * [HTTP严格传输安全](concepts/Security/StrictTransportSecurity.md)
  * [Services](concepts/Services/Services.md)
    * [创建一个service](concepts/Services/CreatingAService.md)
  * [Sessions](concepts/Sessions/sessions.md)
  * [Testing](concepts/Testing/Testing.md)
  * [Views](concepts/Views/Views.md)
    * [布局](concepts/Views/Layouts.md)
    * [本地变量](concepts/Views/Locals.md)
    * [Partials(局部模板)](concepts/Views/Partials.md)
    * [模板引擎](concepts/Views/ViewEngines.md)
* [upgrading](upgrading/upgrading.md)
  * [升级到v.0.10](upgrading/To0.10.md)
  * [升级到v.0.11](upgrading/To0.11.md)
  * [升级到v.0.12](upgrading/To0.12.md)