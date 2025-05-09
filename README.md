# Autopsy-Triage

## Objective

To investigate a suspected insider threat scenario using the Autopsy forensic tool as part of a TryHackMe room. The goal was to perform initial forensic triage on a disk image and extract key artifacts indicating data leakage or suspicious activity.

## Skills Learned

- Navigated Autopsy’s UI to examine disk image metadata and system artifacts
- Identified installed programs and suspicious tools (e.g., Eraser) through program analysis
- Analyzed browser history and keyword searches to uncover user intent
- Traced network file access and extracted IP-related activity
- Interpreted user notes, password hints, and hash values of flagged binaries


## Tools Used

- TryHackMe Platform – Virtual lab environment hosting the Autopsy challenge room
- Autopsy – Main forensic tool used for disk image analysis, artifact extraction, and metadata review
- Windows OS Environment – Base system for running the analysis tools


## Scenario

An employee was suspected of leaking company data. A disk image was retrieved from the machine. You are assigned to perform the initial analysis. Further action will be determined based on the initial findings.

## Steps Taken

Q1. What is the name of an Installed Program with the version number of 6.2.0.2962?<br>
Ans : Eraser<br>
O/P: <img src="https://github.com/user-attachments/assets/8b92a391-d19e-4927-bbbb-e5d6a482fde1" /><br><br>

Q2. A user has a Password Hint. What is the value?<br>
Ans : IAMAN<br>
O/P: <img src="https://github.com/user-attachments/assets/5fac4eba-30c0-4380-abe7-b539a9038d89" /><br><br>

Q3. Numerous SECRET files were accessed from a network drive. What was the IP address?<br>
Ans : 10.11.11.128<br>
O/P: <img src="https://github.com/user-attachments/assets/5dcde791-b971-44b0-93d6-739d72b225a8" /><br><br>

Q4. What web search term has the most entries?<br>
Ans : Information leakage cases<br>
O/P: <img src="https://github.com/user-attachments/assets/c51a50c1-a80b-4926-ba91-95f41bc3db69" /><br><br>

Q5. What was the web search conducted on 3/25/2015 21:46:44?<br>
Ans : anti-forensic tools<br>
O/P: <img src="https://github.com/user-attachments/assets/21dc2aea-1c7c-4cdc-80c8-f81faa90f2a7" /><br><br>

Q6. What MD5 hash value of the binary is listed as an Interesting File?<br>
Ans : fe18b02e890f7a789c576be8abccdc99<br>
O/P: <img src="https://github.com/user-attachments/assets/cf12d6fb-abc1-4b77-b8f9-29c635e49c15" /><br><br>

Q7. What self-assuring message did the 'Informant' write for himself on a Sticky Note? (no spaces)<br>
Ans : Tomorrow...Everything will be OK...<br>
O/P: <img src="https://github.com/user-attachments/assets/9cae9c55-1e60-433c-8542-6d29473f7b7f" /><br><br>

## Conclusion

Through this TryHackMe Autopsy room, I gained hands-on experience in using Autopsy for real-world digital forensic analysis. Despite the absence of a complete disk image, I successfully extracted and analyzed metadata to identify insider threat indicators, demonstrating my capability in forensic triage and evidence interpretation.

