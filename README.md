# Detection Engineering Portfolio – Sigma Rules & SIEM Translation

This repository documents my hands-on learning and implementation of Detection Engineering concepts through Sigma rule creation and SIEM translation.

The project focuses on building practical detections based on real attack behaviours mapped to the MITRE ATT&CK framework. I developed Sigma rules covering process creation, network activity, registry changes, file operations, and authentication events, then translated them into Splunk, Elastic, and Microsoft Sentinel formats to understand how detections are implemented across different platforms.

The objective of this project was not only to write detection rules, but also to understand the full detection lifecycle — from identifying attacker techniques, analysing logs, creating detection logic, reducing false positives, and making detections operationally useful for SOC environments.

This repository includes:

* Sigma detection rules organised by MITRE ATT&CK tactics
* Splunk, Elastic, and Microsoft Sentinel query conversions
* Detection rationale and engineering decisions
* False positive analysis and tuning considerations
* Real-world attack technique mapping
* Notes and documentation created throughout the learning process

Coming from a SOC Analyst background, this project was built as a way to deepen my understanding of Detection Engineering and move beyond alert investigation into designing detections that are scalable, maintainable, and production-oriented.

This is an ongoing project and will continue to expand with additional ATT&CK techniques, detection improvements, testing methodology, and automation.
