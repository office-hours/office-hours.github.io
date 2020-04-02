# Back end

### Ubuntu Linux OS [Ubuntu Server Docs](https://ubuntu.com/server/docs?_ga=2.208630098.1134918235.1585844330-683245728.1585844330)

### Apache HTTP server configured as reverse proxy [Apache HTTP Server Project](https://httpd.apache.org/docs/2.4/developer/API.html)

### JRE 8 [Java 8th Edition](https://docs.oracle.com/javase/8/docs/api/)

### Apache Tomcat Java application server [Apache Tomcat API](https://tomcat.apache.org/tomcat-7.0-doc/api/index.html)

### Web service application, incorporating:

	#### Data
		* Embedded Apache Derby database [Apache Derby API Docs](https://db.apache.org/derby/docs/10.14/publishedapi/index.html)
		* Hibernate ORM [Hibernate Javadocs](https://docs.jboss.org/hibernate/orm/5.2/javadocs/)
		* Custom entity classes
		* Spring Boot Data [Spring Boot Docs](https://docs.spring.io/spring-boot/docs/current/reference/)
		* Custom data repository interfaces
		  
	#### Service controllers
	  
         * Spring MVC [Spring MVC Docs](https://docs.spring.io/spring/docs/current/spring-framework-reference/web.html)          
		 * Custom controller classes
         * Custom Service classes
		  
    #### View composition & serialization
	  
         * Jackson JSON [Jackson Project Docs](https://github.com/FasterXML/jackson)
         * Custom view classes & interfaces
		  
    #### Authentication
	  
        * Google Sign In (external service; see https://developers.google.com/identity)

# Front end

### Android OS [Android API reference](https://developer.android.com/reference)

### Data model

* SQLite [SQLiteDatabase](https://developer.android.com/reference/android/database/sqlite/SQLiteDatabase)
* Room ORM [Room Persistance Library](https://developer.android.com/topic/libraries/architecture/room)
* Custom entity and other model classes
* Custom type converters
* Data access object (DAO) interfaces
	  
### Remote service interfaces

* Retrofit [Retrofit Javadocs](https://javadoc.io/doc/com.squareup.retrofit2/retrofit/2.6.2/index.html)
* ReactiveX [ReactiveX Android Javadocs](https://javadoc.io/doc/io.reactivex.rxjava2/rxandroid/latest/index.html),[ReactiveX Java Javadocs](https://javadoc.io/doc/io.reactivex.rxjava2/rxjava/2.2.17/index.html)
* Gson [Gson Javadocs](https://www.javadoc.io/doc/com.google.code.gson/gson/2.8.5/overview-summary.html)
* Custom serializer/deserializers
	  
### View Model components

* Android Lifecycle framework (ViewModel & LiveData)
* Custom view model classes

### View

* Custom RecyclerView.Adapter and RecyclerView.Holder classes
* Custom layouts
	  
### Controller

* Custom activity and fragment classes
	  
### Authentication

* Google Sign In (external service; see https://developers.google.com/identity)
* Custom sign in service class
