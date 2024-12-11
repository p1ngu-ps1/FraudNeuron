# Fraud Neuron (F.N) - Framework for Cyber Fraud Intelligence

## What is it?

Fraud Neuron (F.N) is a framework designed to provide large organizations and Cyber Threat Intelligence (CTI) analysts with a modeling approach tailored to their specific needs. Developed by AXUR researchers, the model aims to address the growing complexity of contemporary frauds, characterized by the use of Artificial Intelligence, the democratization of hacking, and commonly low levels of Information Security in companies across Latin America.

The model is partially inspired by the MITRE ATT&CK framework, which is used to map Techniques, Tactics, and Procedures (TTPs) of malicious actors in the Cyber Domain. MITRE is undoubtedly one of the most comprehensive models available in the market, widely used by CTI companies in the US and Europe. However, it has significantly lower effectiveness when applied to analyze cyber-attacks and malicious activities that leverage the cyber domain for frauds. Activities such as identity theft, tax evasion, or the use of criminal infrastructure to carry out attacks are often classified under TTPs designed to explain other phenomena.

It is important to note that Fraud Neuron **does not replace** MITRE ATT&CK. Instead, its purpose is to address the specific needs of the threat landscape involving behaviors related to frauds, which are not the main focus of MITRE ATT&CK. While MITRE ATT&CK is an excellent framework for understanding cyber-attacks and malicious activities, it does not directly address the unique aspects of fraud-related activities.

Considering the importance of accuracy for the effectiveness of analysis, F.N was created to offer more robust conceptual options for tackling digital fraud issues in the complex landscape of modern fraud. The model is designed to help organizations of various kinds and their analysts extract better and more structured Cyber Intelligence from fraud-related data.

## How does it work?

F.N offers a modularized data structure for fraud analysis, focusing on concepts related to the use of the digital environment to perpetrate frauds. It is, therefore, a data structure for breaking down a fraud into its components. Similar to MITRE ATT&CK, F.N provides various concepts distributed across the stages of a fraud, allowing malicious actions to be decomposed into different processes commonly observed by the Intelligence community.

This decomposition occurs into Tactics (fraud phases), Techniques (methods used in those phases), and Procedures (specific contextual actions within a fraud, typically not classified), or TTPs.

These concepts are not fixed and, like MITRE ATT&CK, are continually updated and reorganized based on feedback from the Intelligence community.

## What is the Data Structure?

The data structure is based on primary objects, which are the TTPs (Tactics and the Techniques associated with each Tactic), and secondary objects, which are the metadata of the Tactics and Techniques, organized in a `.JSON` format.

## How to Access the Framework

Fraud Neuron can be accessed and utilized through the platform at [neuron.axur.com](https://neuron.axur.com), where you can explore and interact with the data and model for your fraud analysis needs.

## How to Contribute

We welcome contributions to improve the Fraud Neuron framework. To contribute, please submit a **Pull Request** with the suggested changes. Specifically, you should modify the data presented in the `dataset.json` file to reflect your proposed updates or additions.

### Steps to Contribute:
1. Fork the repository.
2. Make the necessary changes in the `dataset.json` file.
3. Ensure your modifications are well-structured and aligned with the existing framework.
4. Submit a Pull Request with a description of your changes.

We appreciate your contributions to enhance and evolve the Fraud Neuron framework!
