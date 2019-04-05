### Files to change when keystore/make all is run

Update password and ports here
- spring-security-x509-client-auth/src/main/resources/application.properties

Copy the keystore/keystore.jks to this directory after make
- spring-security-x509-client-auth/src/main/resources/keystore.jks



### Useful Key Management Commands

- keytool -list -v -keystore keystore.jks

- keytool -list -v -keystore truststore.jks


Relevant Articles:

- [X.509 Authentication in Spring Security](http://www.baeldung.com/x-509-authentication-in-spring-security)

- [Windows make file](http://gnuwin32.sourceforge.net/packages/make.htm)


