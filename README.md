# springboot-camel

A demo project for cefalo knowledge sharing session on "Riding The Apache Camel"
All the diagrams used in the ppt are taken from "Camel In Action" book.

This is a very simple demonstration to show how apache camel can help making the integration simple
and fun. This demonstration shows two simple rss feeds. It fetches rss feeds for bbc and nyt times using
apache camel's rss components and then it sends it to message topic. Finally, those feeds are delivered
to the client through websocket.

#Requirements
1. java 8
2. maven
3. apache-activemq