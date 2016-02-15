# javaee7tutorial
Use: 
- IntelliJ IDEA 15.0; 
- Wildfly 10 application server; 
- Oracle Java JDK 8
(language level is 7); 
- Eclipselink persistence provider 
(.../wildfly-10.0.0.Final/modules/system/layers/base/org/eclipse/persistence/main/eclipselink-2.6.2.jar 
and "<resources>
        <resource-root path="jipijapa-eclipselink-10.0.0.Final.jar"/>
	<resource-root path="eclipselink-2.6.2.jar">
		<filter>
                	<exclude path="javax/**" />
        	</filter>
        </resource-root>
    </resources>" 
in .../wildfly-10.0.0.Final/modules/system/layers/base/org/eclipse/persistence/main/module.xml).

