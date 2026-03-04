*This project has been created as part of the 42 curriculum by <your_login>.*

# NetPractice

## Description

NetPractice is a practical networking project focused on understanding the fundamentals of computer networks. The objective is to configure small-scale simulated networks so that devices can communicate correctly.

Through 10 progressive levels, this project develops a solid understanding of TCP/IP addressing, subnet masks, default gateways, and routing logic. Each exercise presents a non-functioning network diagram that must be fixed by adjusting IP configurations and routing parameters.

This project demonstrates the ability to reason about network architecture, troubleshoot connectivity issues, and apply core networking concepts in a structured and time-constrained environment.

## Objectives

* Configure valid IP addresses
* Apply correct subnet masks
* Identify network and broadcast addresses
* Configure default gateways
* Understand the role of routers and switches
* Restore connectivity in segmented networks

## Instructions

### Running the training interface

1. Download the project files from the NetPractice page.
2. Extract them into a directory of your choice.
3. Run the following script:

```
./run.sh
```

This will start a local web server and automatically open the training interface in your browser.

If the script does not work, you can manually start the server:

```
python3 -m http.server 49242
```

Then open your browser and navigate to:

```
http://localhost:49242
```

### Completing the levels

* Enter your login in the interface to generate your personal configuration.
* Complete all 10 levels by correcting the network settings.
* Use the "Check again" button to validate your configuration.
* After successfully completing each level, click "Get my config" to export the configuration file.

### Submission requirements

* A total of 10 exported configuration files must be submitted.
* One file per level.
* All 10 files must be placed at the root of the Git repository.
* Only files present in the repository are evaluated.

During peer evaluation, three random levels must be solved within a limited time without external tools (a simple calculator is tolerated).

## Technical Concepts Covered

* TCP/IP addressing
* IPv4 structure
* Subnet masks and CIDR notation
* Network and broadcast addresses
* Default gateway configuration
* Router vs switch roles
* Basic routing logic
* OSI model overview

## Resources

To complete this project, the following topics were studied and applied:

* TCP/IP networking fundamentals
* Subnetting principles
* Default gateway behavior
* Network segmentation
* OSI layers and their responsibilities

Recommended references:

* Official networking documentation and TCP/IP references
* Educational articles on subnetting and IP addressing
* Practical subnet calculation exercises

### Use of AI

AI tools were used to:

* Clarify networking concepts
* Review theoretical explanations
* Refine documentation structure and wording

All technical configurations and networking reasoning were completed manually to ensure full understanding and accountability.

## Professional Value

NetPractice strengthens analytical reasoning, troubleshooting skills, and structured problem-solving in network environments. It reflects the ability to understand low-level infrastructure concepts that are fundamental to backend systems, DevOps practices, and distributed architectures.

This project highlights practical knowledge of network configuration and the capacity to diagnose and resolve connectivity issues under evaluation constraints.
