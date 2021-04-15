# Data-Mining-For-Networks
Different types of attacks exist in a network, e.g. port scan, denial of services,
botnets. There are two main ways to prevent them. The first one is to try to
detect explicitely a virus in the payload of packets. The second one is to detect
anomalous patterns of communication

The goal of the project is to develop a method to carry out anomaly detection
in IP traffic. In few words, the principle of the method is to build a profile of
each IP address under the form of a small graph, called graphlet. We then build
a model using Support Vector Machine to distinguish normal from malicious
end hosts from an annotated trace. The last step will be to try to detect attack
in a not annotated trace.

![image](https://user-images.githubusercontent.com/80511292/114938628-a0a18400-9e3f-11eb-8820-38523b2eabbe.png)
