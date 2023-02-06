# InfoSec_h3
## Attack

### Chapter 4: Mapping the Adversary
#### Introduction

* Gathering information about potential threats is a crucial first step before attempting to track them.

* The ATT&CK Framework is a model used to study the actions and strategies of attackers that are able to penetrate systems. It categorizes the attacker's tactics, techniques, and procedures.

* Both defensive and offensive cybersecurity experts use the ATT&CK Framework as a common language and reference tool, making it easier to communicate with others in and outside the field.

* The ATT&CK Framework is open for contribution, allowing users to submit their own tactics, techniques, and procedures to be incorporated into the framework.

#### Tactics

* Each tactic in the ATT&CK Framework represents the reasoning behind the attacker's specific behavior during the intrusion.

* The framework currently defines 14 tactics, which encompass a group of techniques used by attackers.

* Reconnaissance involves gathering as much information about the target as possible.

* Resource Development involves evaluating the target's resources, which can be acquired through purchase, theft, or development.

* Initial Access describes the attacker's first actions in the target environment.

* Execution covers the tactics used for executing malware in the target.

* Persistence involves the attacker's ability to remain in the system even after the target environment has been shut down or restarted.

* Privilege Escalation involves the attacker entering the system with a low-level account and attempting to gain higher levels of access.

* Defense Evasion encompasses all actions taken by the attacker to avoid detection.

* Credential Access involves stealing a user's information, such as login credentials, from the target environment and impersonating the user.

* Discovery involves the attacker finding out as much information about the target as possible.

* Lateral Movement involves the attacker analyzing the network configuration to reach their target.

* Collection involves gathering data from the target.

* Command and Control describes the techniques used by the attacker to communicate with the system.

* Exfiltration involves the techniques used by the attacker to steal the target's data.

* Impact encompasses the techniques and attempts to prevent access to and use of the data.

* As of the author's writing, the ATT&CK Framework includes 183 techniques and approximately 372 sub-techniques.


The ATT&CK Matrix provides an overview of the various tactics and techniques involved in an attack.

The matrix has 14 tactics, which serve as headers for the columns below. The columns contain the various techniques, which can be further expanded into sub-techniques by clicking on them.


The ATT&CK Navigator is a web-based tool for exploring and annotating the ATT&CK matrix. It allows for visualization of various elements related to security, including defensive coverage, red/blue team planning, frequency of detected techniques, and more.


#### Mapping with ATT&CK

Mapping with ATT&CK refers to the process of aligning an organization's security tools and practices with the tactics and techniques used by attackers in the cyber threat landscape. This involves identifying the coverage gaps in an organization's defenses and making informed decisions on how to fill those gaps.

One tool that can be used for mapping with ATT&CK is the MITRE ATT&CK Navigator. It is a web-based tool that allows users to visualize their coverage of the MITRE ATT&CK framework and evaluate the efficacy of their security tools.

The MITRE ATT&CK Navigator works by providing a visual representation of the matrix that showcases the tactics and techniques used by attackers, and allows users to annotate which ones their security tools cover. Users can then use this information to evaluate their overall coverage and identify gaps that need to be filled. This can help organizations to prioritize their security investments and ensure that they are effectively protected against a wide range of cyber threats.


Another tool for mapping with ATT&CK is the ThreatConnect platform. This is a cloud-based threat intelligence platform that integrates with multiple data sources to provide a comprehensive view of an organization's security posture.

Here's how the ThreatConnect platform can be used for mapping with ATT&CK:

Import the ATT&CK framework into the platform: ThreatConnect provides the ability to import the latest version of the MITRE ATT&CK framework, ensuring that users are working with up-to-date information.

Annotate the matrix with existing security tools: Users can annotate the matrix with the security tools they have in place, allowing them to see their coverage against the tactics and techniques used by attackers.

Identify gaps in coverage: By visualizing the coverage gaps, users can identify areas where they need to improve their security posture, either by investing in new tools or enhancing their existing ones.

Plan and execute remediation: With the visibility provided by ThreatConnect, users can plan and execute remediation actions to fill their coverage gaps, ensuring that their organization is protected against the latest threats.

Monitor progress: Users can track the progress of their remediation efforts and receive notifications when new threats emerge that require action. This helps to keep the organization's security posture up-to-date and aligned with the latest threats.




A tactic in the MITRE ATT&CK framework refers to a category of techniques that are used by attackers to achieve a specific objective in their attack. Each tactic is a high-level grouping of related techniques, which provides a general understanding of the attacker's methodology.

For example, one tactic is "Defense Evasion". This tactic encompasses techniques used by attackers to evade detection by the victim's security controls and hide their activities. Some techniques within the Defense Evasion tactic include:

Disabling or stopping security services
Hiding files or processes
Modifying system level permissions
Masking command and control traffic as benign network communication
Using legitimate system tools for malicious purposes.






A technique in the MITRE ATT&CK framework refers to a specific action or behavior that an attacker may use to carry out a tactic. A technique is a more detailed description of the attacker's actions and provides a deeper understanding of the attacker's methodology.

For example, one technique within the "Defense Evasion" tactic is "File Deletion". This technique involves the attacker removing or destroying data on the victim's system to hide their tracks and prevent discovery.

A sub-technique is a further refinement of a technique that provides even more specific details on the attacker's behavior. For example, within the "File Deletion" technique, a sub-technique could be "File Deletion using SDelete". This sub-technique involves the attacker using the SDelete tool to securely delete files and hide their activities.

So, in summary:

Technique: A specific action or behavior that an attacker may use to carry out a tactic.
Sub-technique: A further refinement of a technique that provides more specific details on the attacker's behavior.






A procedure refers to a set of steps that need to be followed to perform a specific task or achieve a particular outcome. Procedures are usually documented and followed in order to ensure consistent results and to avoid errors.

For example, a procedure in a security context could be a series of steps that must be followed to ensure the safe handling of sensitive data. This could include steps such as encrypting the data, transmitting it over a secure network, and storing it in a secure location. Other examples of procedures might include the steps involved in performing a software update, or the steps involved in responding to a security breach.
