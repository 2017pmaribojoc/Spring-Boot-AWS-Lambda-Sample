# Spring-Boot-AWS-Lambda-Sample
Sample Spring Boot project for AWS Lambda

## AWS Lambda Setup
1. Create function. 
2. Upload .jar file generated from `mvn clean install`
3. Edit Runtime settings. Select Java 8 runtime and enter `org.springframework.cloud.function.adapter.aws.FunctionInvoker::handleRequest` as Handler
4. Optional: Configure test events
