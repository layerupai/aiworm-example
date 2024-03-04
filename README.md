# GenAI Worms - LLM Vulnerability Demonstration for educational purposes

### Description
This Python code simulates a Generative AI (GenAI) powered email client designed to illustrate potential vulnerabilities within GenAI ecosystems to adversarial inputs, specifically focusing on the propagation of self-replicating worms. This educational tool serves as a practical component to accompany the research findings presented in "ComPromptMized: Unleashing Zero-click Worms that Target GenAI-Powered Applications," shedding light on the security implications of integrating GenAI into email systems.

### Features
* Email Client Simulation: A simple simulation of an email client that uses OpenAI's API for processing incoming emails and generating responses based on the content of past emails.
* Adversarial Self-replicating Prompts: Demonstrates the concept of adversarial self-replicating prompts that can replicate themselves in the output of a GenAI model, perform malicious activity, and propagate to new hosts within the GenAI ecosystem.
* Simulated Database: Includes a simulated database of past emails to provide context for the GenAI model when generating responses.

## Demo
[![GenAI Worms Explained: The Emerging Cyber Threat to LLMs](https://img.youtube.com/vi/ECvek8JFXG4/0.jpg)](http://www.youtube.com/watch?v=ECvek8JFXG4)

### Requirements
* Python 3.6 or newer.
* Access to OpenAI's GPT (specifically tested with OpenAI's Python API client).
  
### Installation
* Clone the repository or download the source code.
* Ensure you have Python 3.6 or newer installed.
* Install the required Python packages: `pip install openai`

Usage
To run the simulation, you will need to replace `"your-openai-key"` with your actual OpenAI API key in the `EmailClient` class initialization.

```

python email_client_simulation.py

```

### Research and References
This simulation is based on findings from "ComPromptMized: Unleashing Zero-click Worms that Target GenAI-Powered Applications" by Stav Cohen, Ron Bitton, and Ben Nassi. Read the full paper [here](https://sites.google.com/view/compromptmized/home). 

## Disclaimer
This code is intended for educational and research purposes only. The authors do not encourage malicious use of the techniques demonstrated within this simulation.

For more information or questions regarding this educational simulation, please refer to the contact details provided in the research paper.
