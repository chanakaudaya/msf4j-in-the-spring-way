# How to build and run the sample

## About this sample

This sample demonstrates how to inject environment properties into MSF4J runtime.


## How to build the sample

From this directory, run

```
mvn clean install
```

## How to run the sample

From the target directory, run
```
java -jar target/sample12-1.0.0.jar
```

## How to test the sample

We will use the cURL command line tool for testing. You can use your preferred HTTP or REST client too.

```
curl -v -k https://localhost:7070/hello/wso2
```

You should get a response similar to the following:

```
Hi wso2
```