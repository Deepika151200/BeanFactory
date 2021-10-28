# BeanFactory

As a part of my learnings in bean factory, I have integrated the bean with springframework to create objects of objects. This helped me in achieving loose coupling. 

Beans are java objects that are configured at run-time by Spring IoC Container. BeanFactory represents a basic IoC container which is a parent interface of ApplicationContext. BeanFactory uses Beans and their dependencies metadata to create and configure them at run-time. BeanFactory loads the bean definitions and dependency amongst the beans based on a configuration file(XML) or the beans can be directly returned when required using Java Configuration. There are other types of configuration files like LDAP, RDMS, properties file, etc. BeanFactory does not support Annotation-based configuration whereas ApplicationContext does.

This project was built using Maven dependencies and added springframework in pom.xml. I have a small application, which clearly tells the use of simple annotations that are present in bean factory, which helps the developer to maintain loose coupling for the project. 
