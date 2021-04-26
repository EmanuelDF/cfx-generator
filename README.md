
1. Put wsdl file on path
`src/main/resources/wsdl/!!putwsldhere!!`
2. Update pom with wsdlreferences
> <wsdl>${basedir}/src/main/resources/wsdl/<!!putwsdlhere!!>.wsdl</wsdl>

> <wsdlLocation>classpath:wsdl/<!!putwsdlhere!!>.wsdl</wsdlLocation>

3. `mvn clean -u install` (using java 8 and maven 3.6.3)