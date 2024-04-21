# Thesis on MQTT-SN Implementation in OMNeT++
The repository contains resources related to my thesis work. In particular, the main PDF file provides a detailed description of the project.  Additional materials such as the presentation slides and the results discussed are also available. The related code can be found [here](https://github.com/taygumus/mqtt-sn).


## Abstract
In recent years, interest in the Internet of Things has significantly grown, highlighting the need for standards to manage connections within a Wireless Sensor Network. Due to its resource-limited characterization, evaluating effective methods to manage and to optimize communication has been a challenge.  
The objective of this thesis is to delve into the MQTT-SN protocol, proposed as a key solution, and to focus on its Quality of Service (QoS) feature assessing its behaviour within a wireless network. By implementing the protocol using the OMNeT++ discrete event simulator with its INET framework, an adequate environment is established, modeling in an efficient way the communication between the devices, supported by an extensive utilization of parameters. The evaluation is conducted using specific performance metrics and introducing intentional errors, based on a model, in order to simulate a near-real-world scenario. The collected results were analyzed to make comparisons between QoS levels. Furthermore, a secondary investigation into the number of packet retries within the protocol is conducted. The reported outcomes show that, QoS choice is directly linked with the application that make use of it, and its requirements. Indeed, a trade-off between responsiveness and reliability can serve as a solution, where one may be preferred over the other despite its disadvantages.

##  Key Tools for Content

- **LaTeX (Polimi Template on Overleaf)**: Used for document formatting. Available for use [here](https://it.overleaf.com/latex/templates/classical-format-thesis-scuola-di-ingegneria-industriale-e-dellinformazione-politecnico-di-milano/cktbjgtqkryy).

- **Mermaid Live Editor**: Primarily used for designing sequence diagrams.
