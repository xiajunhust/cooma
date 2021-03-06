Cooma is a simple and flexible microcontainer implementation of Java.

Documentation page: <https://github.com/alibaba/cooma/wiki>  
Report problems or suggestions: <https://github.com/alibaba/cooma/issues>  
Code Project page: <https://github.com/alibaba/cooma>  
MailList: <mailto:java-cooma@googlegroups.com>

Code compile and browse tutorial
==================================

Checkout
--------------

```bash
git clone https://github.com/alibaba/cooma.git
```

Compile
---------------

```bash
mvn install -Dmaven.test.skip
```

Browse
---------------

Eclipse:

```bash
mvn eclipse:eclipse -DdownloadSources

Eclipse -> File -> Import -> Existing Projects into Workspace -> Browse -> Finished
```

Idea:

```bash
mvn idea:idea -DdownloadSources

Idea -> File -> Open -> Browse project directory -> OK
```

Related Product
=========================

- [Spring](http://www.springsource.org/)
- [Google Guice](http://code.google.com/p/google-guice/)
- [microcontainer of JBoss](http://www.jboss.org/jbossmc/) 
- [Excalibur](http://excalibur.apache.org/)
- [Loom](http://loom.codehaus.org/)
- [nanocontainer](http://nanocontainer.codehaus.org/)

Design Principle
=========================

- Tiny and simple. Less than 1000 lines of code(not including code comments).
- Concept independence.
- Integration friendly.