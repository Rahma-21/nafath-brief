Version: NAFATH-V3
Track: Data

## Overview

A government is trying to launch an AI chat to help citizens. Structuring the AI chat requires several areas to work together. Software (Semantic Versioning) it is needed to help teams manage updates without breaking existing features. RAG helps to retrieve information more correctly. Mobile (ATS) is used to make the data that moves between the application and the server more secure. Networking: knowing that the number of devices is increasing.  Cybersecurity helps us defend against malicious attacks. Data: knowing which way to protect users' information. My chosen track focuses on the difference between anonymization and pseudonymization in citizens’ chat logs.

## Software
MAJOR should be changed when we change our current API to a new API. If we change the API without updating the version numbers, it will be unable to communicate with the service.
MINOR can be changed if we are adding a new feature to the current update.
PATCH can be changed when we are fixing a bug.

As the scenario above we will update MINOR to incrment to a new number because we are adding only new feature and it is AI chat. 

 MAJOR is the first number: 1.5.4 --> 1
MINOR is the second: --> 5
PATCH is the third: --> 4

Resource: Semantic Versioning 2.0.0 - https://semver.org/


## AI
RAG is used to enhance the answer of AI because AI is usually trained with large data that is only available on the internet and the information can be incorrect sometimes. by using RAG, the AI can acces external information like government data so it can give us correct answer.
Example: a citizen is asking how he can renew his driving licens by using an AI chat (chatbot) that the government added in their app.  AI can now answer him correctly because we used RAG that has access to government data.

Resource: What is retrieval-augmented generation (RAG)? - https://www.ibm.com/think/topics/retrieval-augmented-generation




## Mobile
ATS is used to make the data that moves between the application and the server more secure. Example: ATS enforces apps in IOS to use the HTTPS protocol to encrypt the data.
There are more requirements that Apple forces, like the server certificate must be signed, and connection must use Transport Layer Security (TLS), and other requirements.

If an app tries to call a plain HTTP, ATS will stop these kinds of connections because HTTP carries data and it is not encrypted, and anyone can modify the data.

Resource: Preventing Insecure Network Connections - https://developer.apple.com/documentation/security/preventing-insecure-network-connections


## Networking




## Cybersecurity






## Data




## Misconception in My Track




## Open Question


