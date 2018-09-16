

## virtuoso

mvn install:install-file -DgroupId=virtuoso -DartifactId=virtuoso-jdbc4 -Dversion=0.1 -Dfile=lib/virtjdbc4_2.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=../mvn-repo-awave/repository  -DcreateChecksum=true

mvn install:install-file -DgroupId=virtuoso -DartifactId=virtuoso-rdf4j -Dversion=0.1 -Dfile=lib/virt_rdf4j.jar -Dpackaging=jar -DgeneratePom=true -DlocalRepositoryPath=../mvn-repo-awave/repository  -DcreateChecksum=true


