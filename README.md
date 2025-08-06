# 🔍 To analyze a suspicious email and identify signs of phishing using manual inspection and online tools.

## Phishing Indicators Identified:

| **Indicator**                 | **Explanation**                                                                                                                                                                                                                 |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Suspicious Sender Address** | The sender domain (`bank-verification.com`) is **not** the official domain of any real bank. This is a common spoofing tactic.                                                                                                  |
| **Urgent Language**           | Phrases like **“Urgent”, “Compromised”, “Failure to respond”** are meant to cause panic and pressure the victim into quick action.                                                                                              |
| **Suspicious URL**            | The link says “verify now,” but the actual URL points to `fakebanklogin.com`, which is unrelated to any real bank.                                                                                                              |
| **Generic Greeting**          | It uses “Dear Customer” instead of addressing the user by name, showing it's likely a mass phishing attempt.                                                                                                                    |
| **Threat of Consequences**    | Threatening account suspension is a manipulation tactic to scare users into clicking the malicious link.                                                                                                                        |
| **Spelling/Grammar Errors**   | Phrasing like “confirm your details immediately” and “Failure to respond…” are slightly unnatural or unprofessional.                                                                                                            |
| **Email Header Analysis**     | Using tools like [MxToolbox](https://mxtoolbox.com/EmailHeaders.aspx) or [Google's message header analyzer](https://toolbox.googleapps.com/apps/messageheader/) can reveal mismatches between sender and actual source servers. |

## 🛠 Tools Used for Analysis:
- MxToolbox – to analyze email headers
- URLVoid / VirusTotal – to check the legitimacy of URLs
- Hover-to-Reveal Link – browser technique to view real link behind anchor text
- Common Sense & Pattern Recognition – identifying psychological triggers and social engineering tactics

## 🧠 Conclusion:
This email exhibits multiple characteristics of a phishing attack including spoofed sender, suspicious URL, urgency, and generic content. Users should never click on such links or provide personal information unless verified.
