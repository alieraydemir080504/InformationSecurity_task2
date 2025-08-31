# InformationSecurity_task2

## x) Read and Summarize

### Abstract

- Anti virus and intrusion detection systems are valuable tools to minimize vulnerabilities
- But there have been new threats which are threatening national security information such as the “Advanced Persistent Threat” (APT)
- These foes may use advanced tequniques to crack the security barriers of systems
- Those who are responsible for defending these systems can gather knowledge about these adversaries and create counter measures such as feedback loops
- A kill chain model can be used for describing several phases, indicators and patterns for such attacks
- The use of such a model can be very useful for successfully countering adversary attacks

### 3.2 Intrusion Kill Chain

- A kill chain in general is a process which tries to counter adversary actions
- The "chain" word is being used because of the end-to-end processes which are linked closely to the other components of this model like finx, fix, track, etc.
- In the expanded version of this concept, the attacker will try to breach into the system and work through his/her objectives
- The intrusion kill chain is being defined as reconnaissance, weaponization, delivery, exploitation, installation, command and control and actions on objectives
- Reconnaissance: Targets are bein picked which are usally being represented as email adresses or mailing lists, conference proceedings or information on technologies
- Weaponization: Seemingly harmless PDFs who are supposed to be client application files for example, could used used as a weapon which is being delivered to the systems
- Delivery: Basically these weaponized files are being transferred to the target, them mostly being websites, email attachements and USBs
- Exploitation: After the delivery of the weapon, which includes evil code, it can dig into vulnerable systems which then executes its code to harm the system
-  Installation: It enables for the trojan to keep itself alive in the system to create more harm
-  Command and Control (C2): APT malware must be interacted with manually, as soon as the C2 channel is created, the agressors have “hands on the keyboard” entry in the target system
-  Actions on Objectives: Just after successfully completing all the pahses before, the attacker can continue with their goals. The attackers may just gather some information from the victim or just try to get a better hold of the environment itself
- Own question: For the defender, which one of these phases is usually the hardest to defend? How do you proceed and what exactly are the difficulties?

## a) Tactics, tools and procedures

- Tactics focus on the "why" the attacker does what he does. What their goals are and what steps and stucture they utilize to reach their goal. An example of such a tactic would be the "Privilege Escalation" where the attacker tries to gain higher-level permissions to get access or to gain intel on a network which would normally require elevated permissions. Attacker usally take advantage of system weaknesses to execute this tactic.

- The Techniques on the other hand focus much rather on the "how" of the attacker. The methods they are using to breach the defenses of a system. Such a technique would be e.g. "Compromise accounts" where the attacker may utilize a workers account and damage relationships and trust between other parties in the name of the said worker. Since this technique lies outside of the scope of enterprise defenses and controls, it cannot be easily migitated.

- A Subtechnique is nothing more than a more detailed version of a technique. It just specifies a technique in a slightly different approach/direction. E.g. under the technique "Compromise accounts" we have "Social Media Accounts" which as said before, the attacker executes actions in the name of the victim. But for this subtechnique it is specifically for social media, like purchasing/forcing credentails from 3rd party sites.

- Procedures show  the different ways how attackers use their techniwues and subtechniques to reach their goal. E.g. for the subtechnique "Compromise Accounts: Social Media Accounts" the was the "Leviathan" which has breached social media accounts to conduct social engineering attacks or the "Sandstorm Team" who created credential capture webpages to manipulate existing, legitimate social media accounts.
