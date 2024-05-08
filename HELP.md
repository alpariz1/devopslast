2024-04-14 14:49:29
2024-04-14 14:49:29   .   ____          _            __ _ _
2024-04-14 14:49:29  /\\ / ___'_ __ _ _(_)_ __  __ _ \ \ \ \
2024-04-14 14:49:29 ( ( )\___ | '_ | '_| | '_ \/ _` | \ \ \ \
2024-04-14 14:49:29  \\/  ___)| |_)| | | | | || (_| |  ) ) ) )
2024-04-14 14:49:29   '  |____| .__|_| |_|_| |_\__, | / / / /
2024-04-14 14:49:29  =========|_|==============|___/=/_/_/_/
2024-04-14 14:49:29  :: Spring Boot ::                (v3.2.4)
2024-04-14 14:49:29
2024-04-14 14:49:29 2024-04-14T11:49:29.315Z  INFO 1 --- [demo] [           main] com.example.demo.DemoApplication         : Starting DemoApplication v0.0.1-SNAPSHOT using Java 17-ea with PID 1 (/app/app.jar started by root in /app)
2024-04-14 14:49:29 2024-04-14T11:49:29.318Z  INFO 1 --- [demo] [           main] com.example.demo.DemoApplication         : No active profile set, falling back to 1 default profile: "default"
2024-04-14 14:49:30 2024-04-14T11:49:30.047Z  INFO 1 --- [demo] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Bootstrapping Spring Data JPA repositories in DEFAULT mode.
2024-04-14 14:49:30 2024-04-14T11:49:30.111Z  INFO 1 --- [demo] [           main] .s.d.r.c.RepositoryConfigurationDelegate : Finished Spring Data repository scanning in 55 ms. Found 1 JPA repository interface.
2024-04-14 14:49:30 2024-04-14T11:49:30.612Z  INFO 1 --- [demo] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat initialized with port 8080 (http)
2024-04-14 14:49:30 2024-04-14T11:49:30.624Z  INFO 1 --- [demo] [           main] o.apache.catalina.core.StandardService   : Starting service [Tomcat]
2024-04-14 14:49:30 2024-04-14T11:49:30.624Z  INFO 1 --- [demo] [           main] o.apache.catalina.core.StandardEngine    : Starting Servlet engine: [Apache Tomcat/10.1.19]
2024-04-14 14:49:30 2024-04-14T11:49:30.666Z  INFO 1 --- [demo] [           main] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring embedded WebApplicationContext
2024-04-14 14:49:30 2024-04-14T11:49:30.667Z  INFO 1 --- [demo] [           main] w.s.c.ServletWebServerApplicationContext : Root WebApplicationContext: initialization completed in 1263 ms
2024-04-14 14:49:30 2024-04-14T11:49:30.824Z  INFO 1 --- [demo] [           main] o.hibernate.jpa.internal.util.LogHelper  : HHH000204: Processing PersistenceUnitInfo [name: default]
2024-04-14 14:49:30 2024-04-14T11:49:30.881Z  INFO 1 --- [demo] [           main] org.hibernate.Version                    : HHH000412: Hibernate ORM core version 6.4.4.Final
2024-04-14 14:49:30 2024-04-14T11:49:30.913Z  INFO 1 --- [demo] [           main] o.h.c.internal.RegionFactoryInitiator    : HHH000026: Second-level cache disabled
2024-04-14 14:49:31 2024-04-14T11:49:31.136Z  INFO 1 --- [demo] [           main] o.s.o.j.p.SpringPersistenceUnitInfo      : No LoadTimeWeaver setup: ignoring JPA class transformer
2024-04-14 14:49:31 2024-04-14T11:49:31.160Z  INFO 1 --- [demo] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Starting...
2024-04-14 14:49:31 2024-04-14T11:49:31.259Z  INFO 1 --- [demo] [           main] com.zaxxer.hikari.pool.HikariPool        : HikariPool-1 - Added connection org.postgresql.jdbc.PgConnection@36478bce
2024-04-14 14:49:31 2024-04-14T11:49:31.261Z  INFO 1 --- [demo] [           main] com.zaxxer.hikari.HikariDataSource       : HikariPool-1 - Start completed.
2024-04-14 14:49:31 2024-04-14T11:49:31.288Z  WARN 1 --- [demo] [           main] org.hibernate.orm.deprecation            : HHH90000025: PostgreSQLDialect does not need to be specified explicitly using 'hibernate.dialect' (remove the property setting and it will be selected by default)
2024-04-14 14:49:31 2024-04-14T11:49:31.960Z  INFO 1 --- [demo] [           main] o.h.e.t.j.p.i.JtaPlatformInitiator       : HHH000489: No JTA platform available (set 'hibernate.transaction.jta.platform' to enable JTA platform integration)
2024-04-14 14:49:31 2024-04-14T11:49:31.994Z  INFO 1 --- [demo] [           main] j.LocalContainerEntityManagerFactoryBean : Initialized JPA EntityManagerFactory for persistence unit 'default'
2024-04-14 14:49:32 2024-04-14T11:49:32.237Z  WARN 1 --- [demo] [           main] JpaBaseConfiguration$JpaWebConfiguration : spring.jpa.open-in-view is enabled by default. Therefore, database queries may be performed during view rendering. Explicitly configure spring.jpa.open-in-view to disable this warning
2024-04-14 14:49:32 2024-04-14T11:49:32.557Z  INFO 1 --- [demo] [           main] o.s.b.w.embedded.tomcat.TomcatWebServer  : Tomcat started on port 8080 (http) with context path ''
2024-04-14 14:49:32 2024-04-14T11:49:32.566Z  INFO 1 --- [demo] [           main] com.example.demo.DemoApplication         : Started DemoApplication in 3.702 seconds (process running for 4.181)
2024-04-14 14:49:42 2024-04-14T11:49:42.537Z  INFO 1 --- [demo] [nio-8080-exec-1] o.a.c.c.C.[Tomcat].[localhost].[/]       : Initializing Spring DispatcherServlet 'dispatcherServlet'
2024-04-14 14:49:42 2024-04-14T11:49:42.537Z  INFO 1 --- [demo] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Initializing Servlet 'dispatcherServlet'
2024-04-14 14:49:42 2024-04-14T11:49:42.538Z  INFO 1 --- [demo] [nio-8080-exec-1] o.s.web.servlet.DispatcherServlet        : Completed initialization in 1 ms
2024-04-14 14:49:42 Hibernate: select p1_0.id,p1_0.address,p1_0.img_url,p1_0.name from person p1_0
2024-04-14 14:49:59 java.nio.file.NoSuchFileException: src/main/resources/static/images/image.png
2024-04-14 14:49:59 at java.base/sun.nio.fs.UnixException.translateToIOException(UnixException.java:92)
2024-04-14 14:49:59 at java.base/sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:106)
2024-04-14 14:49:59 at java.base/sun.nio.fs.UnixException.rethrowAsIOException(UnixException.java:111)
2024-04-14 14:49:59 at java.base/sun.nio.fs.UnixFileSystemProvider.newByteChannel(UnixFileSystemProvider.java:219)
2024-04-14 14:49:59 at java.base/java.nio.file.spi.FileSystemProvider.newOutputStream(FileSystemProvider.java:478)
2024-04-14 14:49:59 at java.base/java.nio.file.Files.newOutputStream(Files.java:224)
2024-04-14 14:49:59 at java.base/java.nio.file.Files.write(Files.java:3495)
2024-04-14 14:49:59 at com.example.demo.controller.PersonController.addPerson(PersonController.java:42)
2024-04-14 14:49:59 at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
2024-04-14 14:49:59 at java.base/jdk.internal.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:78)
2024-04-14 14:49:59 at java.base/jdk.internal.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
2024-04-14 14:49:59 at java.base/java.lang.reflect.Method.invoke(Method.java:568)
2024-04-14 14:49:59 at org.springframework.web.method.support.InvocableHandlerMethod.doInvoke(InvocableHandlerMethod.java:255)
2024-04-14 14:49:59 at org.springframework.web.method.support.InvocableHandlerMethod.invokeForRequest(InvocableHandlerMethod.java:188)
2024-04-14 14:49:59 at org.springframework.web.servlet.mvc.method.annotation.ServletInvocableHandlerMethod.invokeAndHandle(ServletInvocableHandlerMethod.java:118)
2024-04-14 14:49:59 at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.invokeHandlerMethod(RequestMappingHandlerAdapter.java:925)
2024-04-14 14:49:59 at org.springframework.web.servlet.mvc.method.annotation.RequestMappingHandlerAdapter.handleInternal(RequestMappingHandlerAdapter.java:830)
2024-04-14 14:49:59 at org.springframework.web.servlet.mvc.method.AbstractHandlerMethodAdapter.handle(AbstractHandlerMethodAdapter.java:87)
2024-04-14 14:49:59 at org.springframework.web.servlet.DispatcherServlet.doDispatch(DispatcherServlet.java:1089)
2024-04-14 14:49:59 at org.springframework.web.servlet.DispatcherServlet.doService(DispatcherServlet.java:979)
2024-04-14 14:49:59 at org.springframework.web.servlet.FrameworkServlet.processRequest(FrameworkServlet.java:1014)
2024-04-14 14:49:59 at org.springframework.web.servlet.FrameworkServlet.doPost(FrameworkServlet.java:914)
2024-04-14 14:49:59 at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:590)
2024-04-14 14:49:59 at org.springframework.web.servlet.FrameworkServlet.service(FrameworkServlet.java:885)
2024-04-14 14:49:59 at jakarta.servlet.http.HttpServlet.service(HttpServlet.java:658)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:205)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:149)
2024-04-14 14:49:59 at org.apache.tomcat.websocket.server.WsFilter.doFilter(WsFilter.java:51)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:174)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:149)
2024-04-14 14:49:59 at org.springframework.web.filter.RequestContextFilter.doFilterInternal(RequestContextFilter.java:100)
2024-04-14 14:49:59 at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:174)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:149)
2024-04-14 14:49:59 at org.springframework.web.filter.FormContentFilter.doFilterInternal(FormContentFilter.java:93)
2024-04-14 14:49:59 at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:174)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:149)
2024-04-14 14:49:59 at org.springframework.web.filter.CharacterEncodingFilter.doFilterInternal(CharacterEncodingFilter.java:201)
2024-04-14 14:49:59 at org.springframework.web.filter.OncePerRequestFilter.doFilter(OncePerRequestFilter.java:116)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.internalDoFilter(ApplicationFilterChain.java:174)
2024-04-14 14:49:59 at org.apache.catalina.core.ApplicationFilterChain.doFilter(ApplicationFilterChain.java:149)
2024-04-14 14:49:59 at org.apache.catalina.core.StandardWrapperValve.invoke(StandardWrapperValve.java:167)
2024-04-14 14:49:59 at org.apache.catalina.core.StandardContextValve.invoke(StandardContextValve.java:90)
2024-04-14 14:49:59 at org.apache.catalina.authenticator.AuthenticatorBase.invoke(AuthenticatorBase.java:482)
2024-04-14 14:49:59 at org.apache.catalina.core.StandardHostValve.invoke(StandardHostValve.java:115)
2024-04-14 14:49:59 at org.apache.catalina.valves.ErrorReportValve.invoke(ErrorReportValve.java:93)
2024-04-14 14:49:59 at org.apache.catalina.core.StandardEngineValve.invoke(StandardEngineValve.java:74)
2024-04-14 14:49:59 at org.apache.catalina.connector.CoyoteAdapter.service(CoyoteAdapter.java:344)
2024-04-14 14:49:59 at org.apache.coyote.http11.Http11Processor.service(Http11Processor.java:391)
2024-04-14 14:49:59 at org.apache.coyote.AbstractProcessorLight.process(AbstractProcessorLight.java:63)
2024-04-14 14:49:59 at org.apache.coyote.AbstractProtocol$ConnectionHandler.process(AbstractProtocol.java:896)
2024-04-14 14:49:59 at org.apache.tomcat.util.net.NioEndpoint$SocketProcessor.doRun(NioEndpoint.java:1744)
2024-04-14 14:49:59 at org.apache.tomcat.util.net.SocketProcessorBase.run(SocketProcessorBase.java:52)
2024-04-14 14:49:59 at org.apache.tomcat.util.threads.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1191)
2024-04-14 14:49:59 at org.apache.tomcat.util.threads.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:659)
2024-04-14 14:49:59 at org.apache.tomcat.util.threads.TaskThread$WrappingRunnable.run(TaskThread.java:63)
2024-04-14 14:49:59 at java.base/java.lang.Thread.run(Thread.java:831)
2024-04-14 14:49:59 Hibernate: insert into person (address,img_url,name) values (?,?,?)
2024-04-14 14:49:59 Hibernate: select p1_0.id,p1_0.address,p1_0.img_url,p1_0.name from person p1_0
