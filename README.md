# OWASP-REPORTS-GUIDE
This guide to reporting is a best fit for consultancy-based reports


## template


 <details>
  <summary>1. Introduction </summary>

   1.1 Version Control <br/>
   1.2 Table of Contents <br/>
   1.3 The Team <br/>
   1.4 Scope <br/>
   1.5 Limitations <br/>
   1.6 Timeline <br/>
   1.7 Disclaimer <br/>
   
</details>

<details>
  <summary> 2. Executive summary </summary>
   it aims at providing executives with:
   <br/>
   1.The objective of the test
   <br/>
   2.Key findings in a business context, such as possible compliance issues, reputation damage
   <br/>
   3.The strategic recommendations on how the business can stop the issues from happening again
   <br/>
  
</details>


<details>
  <summary> 3. Findings </summary>
  Each finding should be detailed with the following information:

    Reference ID, which can be used for communication between parties and for cross-references across the report.
    The vulnerability title, such as “User Authentication Bypass”.
    The likelihood or exploitability of the issue, based on various factors such as:
        How easy it is to exploit.
        Whether there is working exploit code for it.
        The level of access required.
        Attacker motivation to exploit it.
    The impact of the vulnerability on the system.
    Risk of the vulnerability on the application.
        Some suggested values are: Informational, Low, Medium, High, and Critical. Ensure that you detail the values you decide to use in an appendix. This allows the reader to understand how each score is determined.
        On certain engagements it is required to have a CVSS score. If not required, sometimes it is good to have, and other times it just adds complexity to the report.
    Detailed description of what the vulnerability is, how to exploit it, and the damage that may result from its exploitation. Any possibly-sensitive data should be masked, for example, passwords, personal information, or credit card details.
    Detailed steps on how to remediate the vulnerability, possible improvements that could help strengthen the security posture, and missing security practices.
    Additional resources that could help the reader to understand the vulnerability, such as an image, a video, a CVE, an external guide, etc.

Format this section in a way that best delivers your message.

Always ensure that your descriptions provide enough information for the engineer reading this report to take action based on it. Explain the finding thoroughly and provide as much technical detail as might be necessary to remedy it.
</details>

<details>
  <summary>Appendices </summary>
  Multiple appendices can be added, such as:

    Test methodology used.
    Severity and risk rating explanations.
    Relevant output from tools used.
        Make sure to clean the output and not just dump it.
    A checklist of all the tests conducted, such as the WSTG checklist. These can be provided as attachments to the report.
</details>


<details>
  <summary>References</summary>
  research links here
</details>

## REFERENCES 
[OWASP GUIDE](https://owasp.org/www-project-web-security-testing-guide/stable/5-Reporting/README)


