# Ghi chú của Sơn
__Thư viện .NET__
* Phát triển hệ thống báo cáo nhanh và bình dân hóa: [FastReport](https://github.com/FastReports/FastReport)
* [FoundatioFx/Foundatio](https://github.com/FoundatioFx/Foundatio): Pluggable foundation blocks for building loosely coupled distributed apps.
* [SergiySeletsky/Unified](https://github.com/SergiySeletsky/Unified): Sinh chuỗi ID 64 bit
* [sharding-core](https://xuejmnet.github.io/sharding-core-doc/en/guide/params-confg/): Phân mảnh dữ liệu
* [Fody/MethodTimer](https://github.com/Fody/MethodTimer): Đo thời gian thực thi của Method
* [dotnetchina](https://gitee.com/dotnetchina): Một số thư viện dotNET của China
  - [ThingsGateway](https://gitee.com/dotnetchina/ThingsGateway) - Nền tảng IoT dựa trên .NET8, hỗ trợ thu thập dữ liệu từ PLC và các giao thức khác.
  - [weaving-socket](https://gitee.com/dotnetchina/weaving-socket) - Thư viện socket hỗ trợ .NET và Unity, dùng trong IoT và web.
  - [NanUI](https://gitee.com/dotnetchina/NanUI) - Xây dựng giao diện Windows Forms bằng HTML5/CSS3 cho .NET.
  - [MiniExcel](https://gitee.com/dotnetchina/MiniExcel) - Công cụ xử lý Excel đơn giản và hiệu quả trong .NET.
  - [SqlSugar ORM](https://gitee.com/dotnetchina/SqlSugar) - ORM hỗ trợ nhiều loại cơ sở dữ liệu và cú pháp mạnh mẽ.
  - [OpenAuth.Net](https://gitee.com/dotnetchina/OpenAuth.Net) - Khung phát triển nhanh với quản lý quyền và quy trình công việc cho .NET.
* [justinstenning/SharedMemory](https://github.com/justinstenning/SharedMemory) or [ZeroPlusCoders/SharedMemory](https://github.com/ZeroPlusCoders/SharedMemory) : Bộ nhớ
* [Polly](https://github.com/App-vNext/Polly) - Thư viện mạnh mẽ cho phép triển khai các chiến lược xử lý lỗi, như retry, circuit-breaker, timeout và bulkhead isolation cho ứng dụng .NET.
* [MediatR](https://github.com/jbogard/MediatR) - Thư viện triển khai mẫu Mediator Pattern cho .NET, giúp xử lý các yêu cầu và thông báo một cách rõ ràng và tách biệt.
* [NServiceBus](https://particular.net/nservicebus) - Thư viện hỗ trợ xử lý message và sự kiện cho các hệ thống phân tán, giúp xây dựng các dịch vụ kết nối với nhau một cách bền vững và linh hoạt.
* Distributed - Phân tán
  * [madelson/DistributedLock](https://github.com/madelson/DistributedLock): Lock tránh xung đột
  * [MassTransit](https://github.com/MassTransit/MassTransit): Message Queue
  * [RobThree/IdGen](https://github.com/RobThree/IdGen): Sinh Id 64 bit
  * [Nito.AsyncEx](https://github.com/StephenCleary/AsyncEx) - Thư viện hỗ trợ các công cụ đồng bộ hóa trong lập trình bất đồng bộ như `AsyncLock` và `AsyncSemaphore`.
  * [Medallion.Threading](https://github.com/madelson/MedallionThreading) - Thư viện cung cấp các cơ chế đồng bộ hóa và khóa phân tán với hỗ trợ backend như SQL Server, Redis.
  * [SemaphoreSlim (Microsoft Documentation)](https://learn.microsoft.com/en-us/dotnet/api/system.threading.semaphoreslim) - Lớp hỗ trợ đồng bộ hóa tích hợp trong .NET 
  * Framework để hạn chế số lượng tiến trình đồng thời.
  * [RedLock.net](https://github.com/samcook/RedLock.net) - Thư viện triển khai thuật toán Redlock của Redis, cung cấp giải pháp khóa phân tán mạnh mẽ giữa các tiến trình và máy chủ.
  * [Hangfire](https://www.hangfire.io/) - Thư viện giúp quản lý công việc nền và cung cấp cơ chế kiểm soát số lượng công việc đồng thời để tránh chạy trùng lặp.

* Database - DB:
   * DB Engine
      - [LiteDB](https://github.com/mbdavid/LiteDB) - Cơ sở dữ liệu NoSQL nhúng viết thuần bằng C# hỗ trợ giao diện truy vấn tương tự SQL, phù hợp cho ứng dụng nhỏ và desktop.
      - [ManagedEsent](https://github.com/microsoft/ManagedEsent) - Thư viện .NET wrapper cho ESENT, cơ sở dữ liệu nhúng từ Microsoft, cung cấp API truy vấn nâng cao.
      - [FileDb](https://github.com/ahuja4/FileDb) - Cơ sở dữ liệu đơn giản viết bằng C#, không cần máy chủ, phù hợp cho các ứng dụng nhỏ và nhúng.
      - [RaptorDB](https://github.com/mujtaba1/RaptorDB) - Cơ sở dữ liệu dạng document, hỗ trợ giao diện truy vấn tương tự SQL, viết thuần bằng C#, dễ tích hợp cho các dự án .NET nhỏ.
    - **SharpDB** - Cơ sở dữ liệu nhẹ viết bằng C#, không cần máy chủ, phù hợp với ứng dụng nhỏ yêu cầu lưu trữ đơn giản (không có link chính thức). 
  * [victor-wiki/DatabaseManager](https://github.com/victor-wiki/DatabaseManager): Phần mềm quản lý DB
  * [JoshClose/FluentDatabase](https://github.com/JoshClose/FluentDatabase): Viết 1 code tạo các bảng cho nhiều loại CSDL
  * [Mimetis/Dotmim.Sync](https://github.com/Mimetis/Dotmim.Sync): Đồng bộ dữ liệu giữa các loại DB với nhau
  * MessagePack: Giống Json nhưng siêu nhanh và siêu nhẹ
chia sẻ
* Tập hợp các thư viện hay cho dotNET
  * [thangchung/awesome-dotnet-core](https://github.com/thangchung/awesome-dotnet-core)
  * [quozd/awesome-dotnet](https://github.com/quozd/awesome-dotnet)
  * [uhub/awesome-c-sharp](https://github.com/uhub/awesome-c-sharp)
  * [iaspnetcore/SeoInNet](https://github.com/iaspnetcore/SeoInNet)
  * [sindresorhus/awesome](https://github.com/sindresorhus/awesome)
  * [top-asp-dotnet-core-open-source-apps](https://www.syncfusion.com/blogs/post/top-asp-dotnet-core-open-source-apps)
  * [Orchard Core](https://docs.orchardcore.net/en/main/)
  * [oqtane/oqtane.framework](https://github.com/oqtane/oqtane.framework)
* Lập lịch
  * [usausa/hosted-service-extension](https://github.com/usausa/hosted-service-extension  )
  * QuartzNet
    * [jlucansky/Quartzmin](https://github.com/jlucansky/Quartzmin)
      * [maikebing/SilkierQuartz](https://github.com/maikebing/SilkierQuartz) fork từ Quartzmin
      * [mandlar/Quartzmon](https://github.com/mandlar/Quartzmon) fork từ Quartzmin
    * [adometry/QuartzNetManager](https://github.com/adometry/QuartzNetManager)
    * [mausch/QuartzNetWebConsole](https://github.com/mausch/QuartzNetWebConsole)
  * Backtest
    * [jonblankenship/stratysis](https://github.com/jonblankenship/stratysis/): Backtest chiến lược
* Optimize
    * SEO:
      * [mjebrahimi/SeoTags](https://github.com/mjebrahimi/SeoTags)
      * [sebnilsson/AspNetSeo](https://github.com/sebnilsson/AspNetSeo)
      * [nazuke/SEOMacroscope](https://github.com/nazuke/SEOMacroscope): Scan & Audit tool
      * [serpapi/awesome-seo-tools](https://github.com/serpapi/awesome-seo-tools): Awesome Seo Tools
* API Gateway:
    * YARP: [https://microsoft.github.io/reverse-proxy/articles/getting-started.html](https://microsoft.github.io/reverse-proxy/articles/getting-started.html)
    * Ocelot: [ThreeMammals/Ocelot](https://github.com/ThreeMammals/Ocelot)
* Authenticate
  * [mihirdilip/aspnetcore-authentication-basic](https://github.com/mihirdilip/aspnetcore-authentication-basic/)
  * OpenID
    * [simpleidserver/SimpleIdServer](https://github.com/simpleidserver/SimpleIdServer): SimpleIdServer is an open source framework enabling the support of OPENID, OAUTH2.0, SCIM2.0, UMA2.0, FAPI and CIBA
    * Openiddct
* Modular:
  * [thiennn/trymodular](https://github.com/thiennn/trymodular): Modular Web Application with ASP.NET Core 
  * [ExtCore/ExtCore](https://github.com/ExtCore/ExtCore):ExtCore is free, open source and cross-platform framework for creating modular and extendable web applications based on ASP.NET Core
* Build Script
  * [CSScript](https://github.com/oleg-shilo/cs-script/): Công cụ build CS file
  * [json-2-sql-query-dotnet](https://github.com/ali33/json-2-sql-query-dotnet): Convert từ Json sang chuỗi Query SQL
  * [json2sql](https://github.com/mohdnazir/json2sql): Convert từ Json sang script tạo bảng và chèn dữ liệu
  * [ExpressionBuilder](https://github.com/dbelmont/ExpressionBuilder)
  * [code-flu/online-json-to-sql-converter](https://github.com/code-flu/online-json-to-sql-converter): Upload JSON and select as SQL Query
  * [JsonToSQL](https://github.com/ali33/JsonToSQL): Convert from Json to Tables and Insert Scripts
  * [guifier](https://github.com/maliknajjar/guifier): Json, Yaml, ToML Editor
* Shipping & Delivery
  * [Spoleto.Delivery](https://github.com/spoleto-software/Spoleto.Delivery): Giao diện mẫu lập trình cho dịch vụ vận chuyển
* Config:
  * [TOML](https://toml.io/en/): A config file format for humans.
* File System:
  * [xoofx/zio](https://github.com/xoofx/zio): Thiết kế giao diện lập trình cho nhiều hệ thống FS
  * [SharpGrip/FileSystem](https://github.com/SharpGrip/FileSystem): FS hỗ trợ nhiều loại Network Storage: FTP, SFTP, Google Storage
* Price & Competitor
  * [changedetection.io](https://github.com/ali33/changedetection.io): Phần mềm soi giá
* [Roaring.Net](https://github.com/k-wojcik/Roaring.Net): Thư viện xử lý BitSets
__Quy trình__
* [danielgerlag/workflow-core](https://github.com/danielgerlag/workflow-core): Workflow Core is a light weight embeddable workflow engine targeting .NET Standard
* [besley/Slickflow](https://github.com/besley/Slickflow): Quản lý & Edit quy trình BPMN
* [Camunda.com](https://camunda.com/): DMN Platform
* [bpmn.io/toolkit/dmn-js/](https://bpmn.io/toolkit/dmn-js/): DMN Editor
* [X-Flowchart-Vue](https://github.com/OXOYO/X-Flowchart-Vue): Bộ Editor lược đồ online
* Phân tích yêu cầu dự án [Tuyển tập các bài về BA](https://thinhnotes.com/tuyen-tap-cac-notes-ve-business-analyst/)
* Lấy yêu cầu và thống nhất yêu cầu [FS - __F__unctional __S__pecification - Đặc tả chức năng](https://thinhnotes.com/chuyen-nghe-ba/tan-man-ve-fs/)
* Dùng cho đặc tả luồng xử lý: [BPMN (Business Process Modeling Notation) và sự lợi hại của nó](https://thinhnotes.com/chuyen-nghe-ba/bpmn-va-su-loi-hai-cua-no/)
* [pditommaso/awesome-pipeline](https://github.com/pditommaso/awesome-pipeline): Tập hợp Frameworks và Thư viện về Workflow
* [elsa-workflows/elsa-core](https://github.com/elsa-workflows/elsa-core): Elsa is a powerful workflow library that enables workflow execution within any .NET application 

__Tự động hóa theo Rule__
* [drools](https://www.drools.org/): một công cụ quản lý quy tắc kinh doanh rất mạnh mẽ và linh hoạt
* [NRules](https://github.com/NRules): Business Rules Engine (BRE) mã nguồn mở dành cho .NET, cung cấp khả năng quản lý và thực thi các quy tắc kinh doanh giống như Drools
* [RulesEngine](https://github.com/microsoft/RulesEngine): Nguồn mở do Microsoft phát triển
* [Drools.NET](https://www.codeproject.com/Articles/29165/Getting-Started-with-Drools-NET): Phiên bản chuyển thể từ Drools (Java) sang nền tảng .NET
  
__Viết tài liệu hướng dẫn__
* [mkdocs](https://squidfunk.github.io/mkdocs-material/creating-your-site/): Python Markdow to HTML
* [mkdocs-material](https://squidfunk.github.io/mkdocs-material/getting-started/)
  
__Ảo hóa và Cloud__

__Javascript__
* Json Editor để cấu hình nhah [json-editor/json-editor](https://github.com/json-editor/json-editor)
* Thử viện Validate [imask.js](https://imask.js.org/)
* Xây dựng biểu thức Logic
  * [exp.js](https://exp.js.org/)
  * [chrisjpowers/business-rules](https://github.com/chrisjpowers/business-rules)
  * [Ahnfelt/rulebuilder/](https://github.com/Ahnfelt/rulebuilder/)
  * [emerbrito/ng-expression-builder](https://github.com/emerbrito/ng-expression-builder)
* Gantt Chart:
  * [https://www.angular-gantt.com/demo/](https://www.angular-gantt.com/demo/): Thư viện Gantt chart cho AngularJS
  * [https://github.com/robicch/jQueryGantt](https://github.com/robicch/jQueryGantt): Thư viện Gantt chart cho Jquery
__Bản đồ__
* [osrm-backend-docker](https://github.com/peter-evans/osrm-backend-docker): Triển khai bản đồ số bằng docker | [Ví dụ trên openstreetmap](https://www.openstreetmap.org/directions?engine=fossgis_osrm_car&route=21.03174%2C105.78387%3B21.05582%2C105.61154#map=13/21.0590/105.6979) | Hoặc [Monogramm/docker-osrm-backend](https://github.com/Monogramm/docker-osrm-backend)

__UI/UX__
* [AdminLTE](https://adminlte.io/)
* [Semantic-UI](https://semantic-ui.com/)
* [Bootstrap](https://getbootstrap.com/)
* Tailwind CSS
* Foundation
* Bulma
* Skeleton
* [FixedHeader for DataTables](https://www.ihbc.org.uk/consultationsdb_new/extensions/FixedHeader/examples/top_left_right.html)
* [Amphiluke/handy-scroll](https://github.com/Amphiluke/handy-scroll)

__Ecommerce__
* [smartstore/Smartstore](https://github.com/smartstore/Smartstore): Shop
* [DallasBuyer/awesome-dynamic-pricing](https://github.com/DallasBuyer/awesome-dynamic-pricing): Các bài học thuật về quản lý giá
* [dynamic repricing](https://azure.github.io/Cloud-Native/60DaysOfIA/dynamic-repricing-of-products-using-intelligent-apps-part-1): Điều chỉnh giá bằng AI
* __Các ví dụ về E-commerce bằng asp.net core__
  * [EPiServer](https://github.com/episerver/Foundation)
  * [GoogleProductFeed](D:\Data\META\META.V6\FeedBuilder\GoogleProductFeed)

__Metrics/KPI/OKR__: Tổng hợp các chỉ số cần đo trong các lĩnh vực khác nhau
* [sales-metrics](https://www.yesware.com/blog/sales-metrics/): Thước đo bán hàng
* [abolotnov/MetricsKeeper](https://github.com/abolotnov/MetricsKeeper/): Lưu giữ các số đo
* [shopyourway/metrics](https://github.com/shopyourway/metrics): Lưu giữ các số đo
* [OKR](https://github.com/joelparkerhenderson/objectives-and-key-results): Quản trị mục tiêu
* [goal-examples](https://hypercontext.com/goal-examples): Các ví dụ về OKR 
* [RACI Matrix](https://github.com/joelparkerhenderson/responsibility-assignment-matrix): Ma trận trách nhiệm

__Phân tích biểu đồ__
* Xử lý dữ liệu
  * [Microsoft.Data.Analysis](https://www.nuget.org/packages/Microsoft.Data.Analysis/)
  * [fslaborg/Deedle](https://github.com/fslaborg/Deedle): Dữ liệu Frame
  * [SciSharp/Pandas.NET](https://github.com/SciSharp/Pandas.NET)
* [AlexWan/OsEngine](https://github.com/AlexWan/OsEngine)
* [StockSharp/StockSharp](https://github.com/StockSharp/StockSharp)
* [karlwancl/Trady](https://github.com/karlwancl/Trady)
* [worldexplorer/SquareOne](https://github.com/worldexplorer/SquareOne)
* [sthewissen/Mynt](https://github.com/sthewissen/Mynt)

__Big Data/Cloud__
* [orleans](https://github.com/dotnet/orleans)
* [Dorisoy.Pan](https://github.com/dorisoy/Dorisoy.Pan): Quản lý tài liệu bằng .NET
* [zarusz/SlimCluster](https://github.com/zarusz/SlimCluster): Phát triển cụm máy chủ
* [cluster/raft](https://dotnet.github.io/dotNext/features/cluster/raft.html)
__Notebooks__
* [Polyglot Notebooks](https://marketplace.visualstudio.com/items?itemName=ms-dotnettools.dotnet-interactive-vscode)
* [Jupyter Notebooks](https://jupyter.org/)

__Marketing__
* [google-marketing-solutions/feedx](https://github.com/google-marketing-solutions/feedx): Thử nghiệm google feed 
* [google-marketing-solutions/feedgen](https://github.com/google-marketing-solutions/feedgen): Tạo feed
* Email marketing
  * [ActiveCampaign](https://www.activecampaign.com/pricing) & [gandhiashishp/ActiveCampaign.Net](https://github.com/gandhiashishp/ActiveCampaign.Net)
    
__ML: Machine Learning/Máy học__
* [Kiến thức ML.NET](https://github.com/dotnet/machinelearning-samples/tree/main)
* [Forecasting-Sales](https://github.com/dotnet/machinelearning-samples/tree/main/samples/csharp/end-to-end-apps/Forecasting-Sales): Dự đoán doanh số
  
__Linh tinh__
* [html-preview.github.io](https://html-preview.github.io/): View HTML trực tiếp trên Github
* Proxy:
  * [Lozy/danted](https://github.com/Lozy/danted/tree/master)
  * [saaiful/socks5](https://github.com/saaiful/socks5)
 
__Data Mining & Reporting__
* [ariacom/Seal-Report](https://github.com/ariacom/Seal-Report): Thiết kế report và ETL
* [Etl.Net](https://paillave.github.io/Etl.Net/)
* [Apache Superset](https://medium.com/free-or-open-source-software/how-to-install-apache-superset-in-windows-subsystem-for-linux-ubuntu-20-04-os-f198eafd11fa) 
* [Cách cài đặt superset từ source code](https://hackernoon.com/a-better-guide-to-build-apache-superset-from-source-6f2ki32n0)
* ETL
  * [Cài đặt Airbyte bằng Docker](https://docs.airbyte.com/deploying-airbyte/docker-compose) 
__Themes__
* [amir-ko/alibaba-template](https://github.com/amir-ko/alibaba-template)

__Nguyên tắc quản lý phiên bản__
* [https://semver.org/lang/vi/](https://semver.org/lang/vi/)

__Git__
* [github/gitignore](https://github.com/github/gitignore/tree/main): Tổng hợp các mẫu ignore cho Github

# Thống kê các CMS cho ASP.NET
There are plenty of such equivalents, and more are emerging every day:

here are list of cms systems from [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") (legacy aspx wenforms engine):
*   [Statiq.Web](https://github.com/statiqdev/Statiq.Web): Tạo Website tĩnh
*   [Composite C1](https://github.com/Orckestra/C1-CMS-Foundation "github.com") - A web CMS that focus on UX and adaptability
*   [mojoPortal](https://github.com/i7media/mojoportal "github.com") \- MojoPortal is an extensible, cross database, mobile friendly, web content management system (CMS) and web application framework written in C# [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net")
*   [N2CMS](https://github.com/n2cms/n2cms "github.com") - Open source, lightweight, code-first CMS able to seamlessly integrate into any MVC project.
*   [Orchard](https://github.com/OrchardCMS/Orchard "github.com") \- Free, open source, community-focused project aimed at delivering applications and reusable components on the [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") platform
*   [Piranha CMS](https://github.com/PiranhaCMS/Piranha "github.com") - Piranha is the fun, fast and lightweight .NET framework for developing cms-based web applications with an extra bite. It's built on [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") MVC and Web Pages and is fully compatible with both Visual Studio and WebMatrix. [https://piranhacms.org](https://piranhacms.org/ "piranhacms.org")
*   [Umbraco](https://github.com/umbraco/Umbraco-CMS "github.com") - Umbraco is a free open source Content Management System built on the [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") platform
*   [BetterCMS](http://www.bettercms.com/ "www.bettercms.com") - Open Source .NET Intuitive User Interface for Developer and Publisher
*   [DotNetNuke](https://www.dnnsoftware.com/community/download "www.dnnsoftware.com") - DNN Platform is our free, open source web CMS and the foundation of every professional DNN solution. Over 750,000 organizations worldwide have built websites powered by the DNN Platform.
*   [BlogEngine.NET](https://github.com/rxtur/BlogEngine.NET "github.com") - Simple but full featured [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") blog

The same are upgraded to newer net core version, but again here is a list for those who have continued with time:

*   [Awesome-CMS-Core](https://github.com/SaiGonSoftware/Awesome-CMS-Core "github.com") - Awesome CMS Core is an open source CMS built using [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core & ReactJS with module separation concern in mind and provide lastest trend of technology like .Net Core, React, Webpack, SASS, Background Job, Message Queue.
*   [Blogifier.Core](https://github.com/blogifierdotnet/Blogifier.Core "github.com") - [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") applications to provide common blogging functionality.
*   [Cofoundry](https://github.com/cofoundry-cms/cofoundry "github.com") - Open source .NET Core CMS and modular application framework. Code-first, unobtrusive and extensible.
*   [CoreWiki](https://github.com/csharpfritz/CoreWiki "github.com") - Simple [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core wiki that we are working on during live coding streams.
*   [dasblog-core](https://github.com/poppastring/dasblog-core "github.com") - The original DasBlog reimagined with [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core
*   [Lynicon](https://github.com/jamesej/lyniconanc "github.com") - O/S [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core/.Net Core CMS with paid for modules: JSON content, works with variety of data stores, c# content types
*   [Miniblog](https://github.com/madskristensen/Miniblog.Core "github.com") - An [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core blogging engine.
*   [Mixcore CMS](https://github.com/mixcore/mix.core "github.com") - Open Source CMS powered by DotNet Core. Mixcore CMS is a scalable, open platform for web content management and digital experiences. Mixcore CMS provides deep capabilities and endless flexibility on the web.
*   [NetCoreCMS](https://github.com/OnnoRokomSoftware/NetCoreCMS "github.com") - An Open source [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core 2.0 CMS. It currently supports MySQL and planned to implement MSSQL, SQLite and PostgreSQL. Also it is a modular CMS supports theme, skin, custom layout, widgets, multiple language (En, BN).
*   [Orchard Core CMS](https://github.com/OrchardCMS/OrchardCore "github.com") - Open Source Content Management System built with [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core on top of a Modular and Extensible Application Framework.
*   [Piranha CMS](https://github.com/piranhacms/piranha.core "github.com") - A Lightweight & Unobtrusive Open Source CMS for [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core and Entity Framework Core.
*   [Platformus](https://github.com/Platformus "github.com") - Free, open source and cross-platform CMS based on [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core 1.0 and ExtCore framework.
*   [SimpleContent](https://github.com/joeaudette/cloudscribe.SimpleContent "github.com") - Simple, yet flexible content and blog engine for [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core that can work with or without a database.
*   [Squidex](https://github.com/Squidex/squidex "github.com") - Headless CMS, based on MongoDB, CQRS and Event Sourcing.
*   [Swastika I/O Core CMS](https://github.com/Swastika-IO/Swastika-IO-Core "github.com") - Open source [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core 2.x CMS. It currently supports MS SQL and planned to implement MSSQL, SQLite in the near future. It has many built-in features out of the box like multilanguage support, theme, template...
*   [Weapsy](https://github.com/Weapsy/Weapsy "github.com") - Open source [ASP.NET | Open-source web framework for .NET](http://asp.net/ "asp.net") Core CMS based on DDD and CQRS. It supports MSSQL, MySQL, SQLite and PostgreSQL out of the box.
*   [Wyam](https://github.com/Wyamio/Wyam "github.com") - Modular static content and static site generator.
*   [ZKEACMS](https://github.com/SeriaWei/ZKEACMS.Core "github.com") - Visual design, build site onlie by drag and drop.

Hope you find this info useful. as an experienced .net developer i can assure you that these products based on c#/net core provides much better security and performance then wordpress any time.

Thanks for A2A
