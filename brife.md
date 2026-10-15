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

IPv4 has 4.3 billion addresses, and most of them are assigned, while IPv6 has 340 trillion unique addresses. Why do we need IPv6? Because the number of devices that are connected to the internet is increasing, and every device needs an IP address, and because of the limitation of the number of IPv4 addresses, IPv6 has more addresses.

Resource: Policy Brief: Adoption of IPv6 - https://www.internetsociety.org/policybriefs/ipv6/


## Cybersecurity


Prompt Injection is letting an LLM or AI ignore a person's prompt and be replaced by an attacker's unknown intentions. This can be done by jailbreaking the system.

Direct Prompt Injections: It happens when a malicious user overwrites the user’s prompts
and this will let the attackers get the sensitive data of the user.

Indirect Prompt Injections: It happens when an LLM accepts input from external sources that can be controlled by an attacker, such as websites or files. 

Two ways to reduce the risk:
1- By manually monitoring the LLM input and output.
2- Add restrictions to the LLM, like requiring the user to accept the action before the LLM does it.

Resource: LLM01: Prompt Injection - https://genai.owasp.org/llmrisk2023-24/llm01-24-prompt-injection/


## Data

Anonymisation is like the user being anonymous, while pseudonymization replaces the user's name or email with a code or token.

Which one takes the data outside the scope of data protection law?
Anonymisation:effectively remove the possibility of identifying the person.  

Resource: Anonymisation and pseudonymisation - https://www.dataprotection.ie/en/dpc-guidance/anonymisation-pseudonymisation



## Misconception in My Track




## Open Question


