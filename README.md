#Toolchain for Simple Weather Application with DRA

This cloud-native toolchain will build a simple NodeJs weather application.  The toolchain is configured to build from a github repository, perform unit tests with MochaJS, check code coverage with Istanbul, request DRA decisions, and then deploy to Bluemix.  DRA has been added to the toolchain to analyze the unit test and code coverage results before deploying to Bluemix.

###To get started, click this button:
[![Deploy To Bluemix](./.bluemix/create_toolchain_button.png)](https://new-console.ng.bluemix.net/devops/setup/deploy/?repository=https%3A//github.com/jparra5/weather-dra-demo.git)

---
###Prerequisites

* User must have a Bluemix account. [Sign up here](https://new-console.ng.bluemix.net/registration/)
* User will need access to Toolchains.  [Request access here](https://new-console.ng.bluemix.net/devops/)
* A github.com account will be needed.


---
###Learn more

* [Cloud-native toolchain for microservices](https://www.ibm.com/devops/method/toolchains/microservices_toolchain) on the IBM Bluemix Garage Method site
