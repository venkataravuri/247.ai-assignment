<img src="https://careers-gua.247-inc.com/SpringboardGUAV2/resources/assets-common/img/logo.png" width="10%" height="10%" alt="247.ai logo" />

## :telephone_receiver: Design a AI-driven Voice based Customer Conversation System :robot:

### System Design Interview - Problem Statement

Here is my understanding (or) transcript :pencil2: of the problem statement :question: prescribed, as an assignment over call. :calling:

#### :hourglass: Background

A fictitious company provides customer support services to multiple clients. Until now, calls were answered by human agents. Due to the increasing volume of calls and the need to streamline the support process, the company wants to deploy an AI BOT to handle these conversations over IP telephony.

####  :open_book: Requirements

1. The system should receive IP-based calls where customers describe their issues, concerns, or tasks in natural language.
2. AI BOT should answer every customer call.
3. The AI BOT must determine the customer's intent by analyzing the voice conversation.
4. The system should be able to record the call, generate a transcript, and measure the BOT's understanding quality.
5. The BOT's response to the customer should be derived from previous human agent responses to similar queries, issues, or concerns.
6. The system have access to a corpus of previous human agent voice conversations and transcriptions.
7. The AI BOT can also query other business systems to compose a data-driven response.
8. The system should measure metrics that would be of interest to company executives (CXOs) and evaluate the overall performance and efficiency of the platform.

#### :scroll: Constraints

1. The system should be hosted on public cloud preferably Google Cloud.
2. Solution can leverage open-source software and AI/ML models. If needed adopt Commercial-off-the-Shelf (COTS) tools and cloud provider SaaS services.

#### :toolbox: Ask

Design an AI BOT solution to handle these conversations over IP telephony. The proposed system design should capture following,

1. A high-level architecture diagram of the system.
2. A detailed explanation of each component in the system.
3. Process & Data flow diagrams showing how data moves between components.
4. List out the technologies choosen to implement the solution. Justification for technology choices made.
5. A strategy to ensure high availability, scalability, and security of the system.
6. Potential challenges and their proposed solutions.
7. Design storage and search mechanisms for the transcripts and voice recordings.

## :rocket: Solution :100:

This document captures h**igh-level solution** of _re-engineered_ and _re-architected_ solution that replaces existing human-agent centric customer support call centre with :brain: an **AI/ML driven**, :robot: **BOT oriented**, 🚀 **scalable**, 〰️ **elastic** & 🏢 a **multi-tenant** autonomous call centre solution.

* The 🎡 **To-Be System Architecture** is explained through various architecture views such as ```Functional Architecture, Technical Architecture, Deployment Architecture, Component Designs, Technology Choices``` and more, each addressing unique concerns of various stakeholders & audience.
* Highlights how the proposed solution addresses limitations & constraints for current system with modern AI technology advances.

### Functional Analysis & Design

A quick use-case analysis has yielded essential buisness functions which are mapped into system fuctions. Related system functions are grouped into functional modules later to be translated into software components.

| Functional Module | Description | Critical System Functions|
| --- | --- | --- |
| Voice Gateway | 
|
|

#### Non-Functional Requirments
Solution should adhere to folloiwng NFRs,

1. Low-latency: Being a voice based conversational system, it should process requests in sub-second, so that caller should not feel any delay.
2. Multi-language: Support multiple spoken languages, should detect language automatically and reply in same language.
3. Should have gaurdrails against toxcity, bias.
4. 

### Solution Architecture

<img src="images/solution.jpg" width="100%" height="100%" alt="Solution Architecture" />

Click here to modify [Miro](https://miro.com/app/board/uXjVMrUCYIg=/?share_link_id=799154363440) diagram.

<img src="images/index.jpg" width="20%" height="20%" alt="Text Index" />

Click here to modify [Miro](https://miro.com/app/board/uXjVMrUCYIg=/?share_link_id=799154363440) diagram.

<img src="images/search.jpg" width="20%" height="20%" alt="Search Embeddings" />

Click here to modify [Miro](https://miro.com/app/board/uXjVMrUCYIg=/?share_link_id=799154363440) diagram.

<img src="images/answer.jpg" width="100%" height="100%" alt="Question Answer" />

Click here to modify [Miro](https://miro.com/app/board/uXjVMrUCYIg=/?share_link_id=799154363440) diagram.

### Technical Architecture

<img src="images/tech-stack.jpg" width="80%" height="80%" alt="Tech Stack" />

Click here to modify [Miro](https://miro.com/app/board/uXjVMrUCYIg=/?share_link_id=799154363440) diagram.

#### Component Designs

#### Process Flows & Information Models 

### Deployment Architecture

### Performance Assurance

### Security Architecture, Privacy and Compliance

#### References

