
# Project Title
A Simple SignIn -Sign Up -Forgot Password-JSP-Servlet-JDBC project using Eclipse2021-12

## Tools used
1.IDE - Eclipse 2021-12
2.JDK - 1.8 or later
3.Apache Tomcat - 9.0.56
4.mysql-connector-java-8.0.27.jar
5.JSTL(provided by Glassfish) *javax.servlet.jsp.jstl-api-1.2.2.jar and *javax.servlet.jsp.jstl-1.2.5.jar
6.Servlet API 
7.mysql workbench 8.0 CE

## Steps to follow
1. Create an Eclipse Dynamic Web Project[This project is actually named **registration-jsp-servlet-jdbc-example** ]

![1 creating dynamic web project](https://user-images.githubusercontent.com/98513320/151336660-9df39d39-97b9-42fb-9f8b-b36acef920e2.gif)
![2 Dynamic web project](https://user-images.githubusercontent.com/98513320/151336925-5f962956-e88f-43b1-beb8-d5cb65d2531b.gif)
![3 Dynamic web project](https://user-images.githubusercontent.com/98513320/151336952-f4dceb79-f8b6-4004-98f5-a6a3fe524a92.gif)
![4 Dynamic web project](https://user-images.githubusercontent.com/98513320/151336982-e758165b-932f-4696-a340-45e8179228a8.gif)
![5 Dynamic web project-created](https://user-images.githubusercontent.com/98513320/151336854-7e494fce-ddd5-4052-b55d-2b80dab041d4.gif)

2. Configure the runtime environment
![6 1 Runtime configuration](https://user-images.githubusercontent.com/98513320/151365440-149201e3-4c86-4978-8ab9-3469967f2218.gif)
![6 2 Runtime configuration](https://user-images.githubusercontent.com/98513320/151365499-17e28b40-1af7-49f6-9161-7dadd5a37891.gif)
![6 3 Runtime configuration](https://user-images.githubusercontent.com/98513320/151365526-c3c6fe72-543a-45ef-8db7-10920aece494.gif)
![6 4 Runtime configuration](https://user-images.githubusercontent.com/98513320/151365560-251d2083-59b3-41e8-98d9-3962e6ab5c26.gif)

4. Create a MySQL Database named users with table name useraccount.
5. Download JDBC library to drive the connection with the Database.Here I have used **mysql-connector-java-8.0.27.jar**.
6. You need to download 2 JSTL libraries:
    **javax.servlet.jsp.jstl-*.jar  and 
    javax.servlet.jsp.jslt-api-*.jar**
    http://mvnrepository.com/artifact/org.glassfish.web/javax.servlet.jsp.jstl
7. **Servlet api.jar** should be copied from the lib folder of the Apache Tomcat folder that is installed on your system.
   ![7 servlet api](https://user-images.githubusercontent.com/98513320/151368190-9ce0cb66-8b6e-49ca-be16-595acb78d3a5.gif)
   
8. Copy all the four jar files that you just downloaded into the /WEB-INF/lib:

![Required jar files](https://user-images.githubusercontent.com/98513320/151368688-871f57fe-22ea-47a6-ad02-da61a260c005.jpg)

9. Create all necessary **.java, .jsp, and servlet files** by right-clicking on the project name and place them in the appropriate folders as per the MVC pattern.

![project structure](https://user-images.githubusercontent.com/98513320/151371006-e188eb8c-a004-4a58-9b4e-dbd6ac2c0085.jpg)

![views](https://user-images.githubusercontent.com/98513320/151371143-f5090fce-08f7-4dcb-ab43-07be1396e88e.jpg)

10. **Xml mapping** is

![xml](https://user-images.githubusercontent.com/98513320/151374106-20c3a195-a2dd-4ad3-848f-2688880908e0.gif)

11.**Demo**

It's time to see a demo of the above development. Deploy this web application in tomcat server.

Right-click on registration-jsp-servlet-jdbc-example, select:

![runonserver,gif](https://user-images.githubusercontent.com/98513320/151384734-e850d335-c004-47c3-ace1-cbfe7543c62c.gif)

**Home Page**:

![home-jsp](https://user-images.githubusercontent.com/98513320/151380638-61115991-8fde-4391-8ba7-b65dace4c141.gif)

**Register Here**

![useraccountregister-jsp](https://user-images.githubusercontent.com/98513320/151380888-9f553f18-f954-4b23-9ae6-0cf4f4e921ff.gif)

**Successful Registration**

![registerdetails-jsp](https://user-images.githubusercontent.com/98513320/151382705-a17b4200-3ba6-4616-a910-4614434c069f.gif)

**Verfication with Database Record**

![database](https://user-images.githubusercontent.com/98513320/151381147-5e4bcf2d-a6f2-4d81-ae6b-ec9ca3436521.gif)

**Improper SignUp**

![improperregistration](https://user-images.githubusercontent.com/98513320/151381186-089e5ca9-e538-4647-ac2c-264b8ebbd3c3.gif)

![useraccountnotregistered](https://user-images.githubusercontent.com/98513320/151381289-c42ef8f4-6781-4e88-adc7-0ad6b85a5b32.gif)

**SignIn**

![signin](https://user-images.githubusercontent.com/98513320/151381384-572fbcfa-c619-4f07-9878-0ec961833683.gif)

![signinsuccess](https://user-images.githubusercontent.com/98513320/151381455-9cae8881-e071-4551-9d9c-63d800f46cf4.gif)

**Improper SignIn**

![signinwithmissingdata](https://user-images.githubusercontent.com/98513320/151381501-51f9b792-431d-4c0f-8339-475b52b16a67.gif)

![signinerror](https://user-images.githubusercontent.com/98513320/151381542-e8491c4a-8c62-4041-84d6-eba2b8c44afb.gif)

**Forgot Password**

![recoverpassword](https://user-images.githubusercontent.com/98513320/151381615-e1e64124-dba3-4243-9df4-26b552e40c66.gif)

![gettingpassword](https://user-images.githubusercontent.com/98513320/151381697-ec4ff9c4-51d1-4df4-abb3-473ccc31c939.gif)

**If Forgot Password form is filled improperly
**

![improperpassword](https://user-images.githubusercontent.com/98513320/151381727-34a4d450-cd57-4d07-bb39-353bb37e6074.gif)

![passworderror](https://user-images.githubusercontent.com/98513320/151381774-5b35d044-7ef1-4a59-b620-30fd97c99729.gif)

