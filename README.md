# iocdemo
Demo for understanding Dependency Injection in Spring
Who said "Hello Word!" is such a primitive coding experience? Try to apply invertion of control principle.
In this example we have 2 interfaces: 
- MessageProvider who offers a message 
- MessageRenderer who does something with the message
We can create as many implementations as we wish.
To change the implementation class, we are not going to recompile the code
Just configure beans in config.xml or in JavaConfig class (both ways are ok) and enjoy!
To start:
- run MainAnnotationDriven ==> loads JavaConfig.java
or: 
- run MainXmlDriven ==> loads config.xml

