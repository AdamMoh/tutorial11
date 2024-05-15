# Tutorial 11 Advpog

## Reflection on Hello Minikube
1. Compare the application logs before and after you exposed it as a Service. Try to open the app several times while the proxy into the Service is running. What do you see in the logs? Does the number of logs increase each time you open the app?
Yes, because every time i do a request to the service it logs the request.

<img src="/static/ss1.png">

2. What is the purpose of the `-n` option and why did the output not list the pods/services that you explicitly created?

the `-n` option is used to specify the namespace to list the pods/services. The output did not list the pods/services that i explicitly created because the namespace was not specified.

