---
speakers:
  - Frédéric Bogaerts
  - Naghmeh Ivaki
  - José Fonseca 
name: 'Using AI to Inject Vulnerabilities in Python Code'
categories:
  - 'Session 2 (chair: Aleš Smrčka)'
---


Developing software that is free of vulnerabilities is an ongoing challenge for developers, as their impact may not be apparent until they are exploited. Although security tools can help identify vulnerabilities, their effectiveness is questionable. In order to address this challenge and assist developers in implementing more secure code, we aim to develop AI-based vulnerability injection techniques.

Our research specifically focuses on building AI models that can detect potential locations in the code for vulnerability injection. To train these models, we created a dataset including vulnerable and secure (i.e., patched) versions of Python code collected from open-source repositories. Our preliminary results show that our methodology successfully identifies potential locations where a vulnerability could be injected with high accuracy. We also compared our approach with the use of Regular Expressions (RegEx) created based on the vulnerability patches. As a result, our AI approach outperformed the RegEx by a large margin.
