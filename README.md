Bopepo
======

[![Build Status](https://ci-jrimum.rhcloud.com/buildStatus/icon?job=Bopepo)](https://ci-jrimum.rhcloud.com)

Biblioteca Java para geração de boletos bancários.

 * http://jrimum.org/bopepo 




ATENÇÃO!

Para compilar este projeto e dependecias com java 7:

Setar o JAVA HOME:

export JAVA_HOME=/usr/lib/jvm/jdk1.7.0_80
export PATH=$JAVA_HOME/bin:$PATH
echo $JAVA_HOME

Executar instalação forçando o TLS:

MAVEN_OPTS="-Dhttps.protocols=TLSv1.2" mvn clean install -U

Para executar o mesmo comando eem executar os testes unitários:

MAVEN_OPTS="-Dhttps.protocols=TLSv1.2" mvn clean install -U -DskipTests -Dmaven.test.skip=true