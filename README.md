Spring Security, Hibernate, SQLServer
============

This is the Fruzenshtein/security-spr fork. I had some problems to run Fruzenshtein project, so I decided to do some changes:

1. Spring Security version changed to 2.3.2.RELEASE
2. Database changed to SQLServer2008 (jtds driver artifact in pom.xml)
3. Custom, simple and single user authority table

You may encounter some troubles:
1. "javax.servlet.jsp.JspException cannot be resolved" error after import to Eclipse: menu Project -> Properties -> Target Runtimes -> choose appropriate runtime target (tomcat 7.0?)
2. 
2. 
