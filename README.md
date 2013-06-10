flume-cep
=========

원격지 서버(web1, web2, web3)에 flume agent 각각 설치
콜렉터(Collector) 서버는 원격지 정보 수집

실행 방법

Collector 서버의 Flume 시작
https://github.com/lotshin/flume-cep/blob/master/dist/apache-flume-1.3.1-bin/start.collector.sh

Agent 서버의 Flume 시작
https://github.com/lotshin/flume-cep/blob/master/dist/apache-flume-1.3.1-bin/start.agent.sh


Apache Flume + Esper CEP

라이브러리 추출하기
mvn dependency:copy-dependencies
