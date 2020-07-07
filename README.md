# OAA(Oracle Advanced Analytics)

오라클 DB에서 제공하는 Data Mining 툴에 대해 알아보도록 하겠습니다.
기본적으로 Data Mining을 사용하기 위해서는 DB의 AA Option을 enable하여야 합니다.

DB서버에 접속하여 다음과 같이 AA 옵션을 활성화하십시오.

cd $ORACLE_HOME/bin
srvctl stop database -d Sales(DB고유이름)
chopt enable oaa
srvctl start database -d Sales
