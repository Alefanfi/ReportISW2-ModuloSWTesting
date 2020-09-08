# ReportISW2-ModuloSWTesting

AVRO

Esecuzione test:

mvn verify
Esecuzione PIT, dal modulo java/lang/avro:

mvn verify org.pitest:pitest-maven:mutationCoverage 

Bookkeeper

Esecuzione test:

mvn verify
Esecuzione PIT, dal modulo bookkeeper-server:

mvn verify org.pitest:pitest-maven:mutationCoverage
