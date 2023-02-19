# TestAPI

This contains what you need to run sample JMeter scripts.

Setup Scenarios
The components necessary for performance/capacity testing are:

A. The application under test. I've used TMS API for API Load Test. 

B. JMeter to run scripts that emulate 1 or a lot of client instances. Blazemeter cloud provides that. A Docker image of the free/open-source Jenkins can be used locally or in a public cloud.

C. Environment to host the app. 

D. If required, please ensure to have CI/CD workflow engine (such as Jenkins, Harness.io, CircleCI, GitHub Actions, etc.) which builds the app under test and test for security, functionality, capacity capability, etc

E. Monitoring (Metrics, Diagnostics, Logging) in the same environment running the app to identify trends, pin-point bottlenecks, and identify root causes.

Below are step-by-step instructions for using the Repo: 

1. I have used plugins manager for the script and you may already be able to see the plugins once you have imported the jmx into the JMeter solution. 
2. I have made the following assumptions : 
  a. The category id field will remain static. It is in the range of the 10 values provided. 
  b. No other field will be required to be paraameterized or correlated based on the FR & NFR given
  
  
