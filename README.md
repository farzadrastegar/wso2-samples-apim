> [!NOTE]
> This repo creates a basic infrastructure for trying out [WSO2 scenarios](https://apim.docs.wso2.com/en/latest/tutorials/scenarios/scenario-overview/). To run the setup, follow the steps below.

1. Clone https://github.com/farzadrastegar/wso2-samples-apim.
2. Go to wso2-samples-apim/apim-tutorial.
3. Start the setup using the command `docker-compose up -d`.
4. You can view the logs using the command `docker-compose logs -d`.
5. It might take 5-10 minutes for the setup to complete (if it is the first time, based on your download speed it might take longer).
6. When you see the below log you can start working on the scenarios.
```
“==Data population completed==”
```

---
## WSO2 API Manager Samples

This repo contains WSO2 API Manager related samples.

### XACML Handler 
Contains the source code of the entitlement handler that is used as a sample in the following WSO2 library article and documentation.

https://docs.wso2.com/display/AM210/Enabling+Role-Based+Access+Control+Using+XACML
https://wso2.com/library/tutorials/2016/02/tutorial-how-to-enable-role-based-access-control-for-wso2-api-manager-using-xacml/


---
### Kubernetes Demo
*This 'Kubernetes Demo' repository contains scource code of*

1.Deploying API Manager pattern-1 and automating a sample backend service in gcloud Kubernetes Engine

2.Rolling updates on WSO2 API Manager

3.Autoscaling WSO2 API Manager based on the production load

---
### CustomJWTGenerator
This repo contains the source code of the Custom JWT Token Generator that is used as sample in the following article:

https://docs.wso2.com/display/AM260/Passing+Enduser+Attributes+to+the+Backend+Using+JWT

