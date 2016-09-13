# Developing a first application with IBM MQ Light

This repository contains a set of material used at conferences to demonstrate
the MQ Light API and how it can be used to write cloud apps which perform
worker offload.

Check out the
[IBM MQ Light Homepage](https://developer.ibm.com/messaging/mq-light/) or the 
[Bluemix documentation](https://console.ng.bluemix.net/docs/services/MessageHub/index.html#messagehub) for
more info on these and other samples.

## What you will learn

This lab will teach you how you can improve the responsiveness and scalability of your
web appli-cations, both on premise and in the cloud by using messaging with the
MQ Light API. 

It will explain how to off-load heavy workloads to separate worker threads while your
web handlers deal quickly and efficiently with the requests from your online users. 
As software developers we want our applications to be responsive and scalable to really
engage users, but it's not always easy to write code that behaves like this. The MQ Light
API, available in IBM MQ and the Message Hub Service in IBM Bluemix, is a great tool that
helps applications off-load work to be dealt with asynchronously thus ensuring your
applications responds quickly. Addi-tionally, as workload increases, applications
that use MQ Light become very easy to scale up. 

In this Lab you will learn how to use the MQ Light API, develop an application which runs
locally using the MQ Light Developer Tools before deploying it to the Cloud using IBM
Bluemix and the Message Hub Service. You will also learn how to use the MQ Light user
interface to understand and debug the messages that your application has sent and received. 


Read the [Lab Instructions](Lab Instructions.pdf) to get started.

