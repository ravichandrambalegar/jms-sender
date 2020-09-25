# jms-sender

springboot-app

Requirements
For building and running the application  need:

JDK 1.8
Maven 
apache-artemis-2.15.0

Before Running the application Download and install apache-artemis-2.15.0 with Credentials (User name and password)
link to dowload apache-artemis

http://activemq.apache.org/components/artemis/download/

commandline to install apache-artemis:

. unzip the downloaded apache-artemis-2.15.0
. cd apache-artemis-2.15.0
. cd bin
. ./artemis
create the artremis broker
. ./artemis create /tmp/mybroker
  set user name and password
. cd /tmp/mybroker
. cd bin
. ./artemis-service start

run the project after installation of pache-artemis.

. This application used to send Message :
   1. point to point (P2P)
   2. Publish/Subscribe (Pub/Sub)
   3. P2P with Acknowledgement Response.
