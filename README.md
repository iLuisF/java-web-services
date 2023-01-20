Orden de ejecución para servicios SOAP:
1. hellowebservice
2. wsdlfirstws
3. javasoapclient (se mantiene el servicio anterior en ejecución)
4. javafirstws
5. utclient (username token profile client)
6. mtom
7. wsdlfirstws (ahora con handlers)
8. javafirstws (ahora con Fault Exception)
9. productcrud

Referencia:

https://www.udemy.com/course/java-web-services/