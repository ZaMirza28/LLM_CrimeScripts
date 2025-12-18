## 12/11/2025
General idea is to bridge the gap between CTIs and detection (log data) from the ceiling to the floor.
Looking into whether using LLMs to move from CTIs to crime scripting would work.
Investigate papers by Asier, Rutger and Thomas to check for feasibility.
Question to answer is "can I build a crime script starting from a CTI report" and develop an image of what one looks like. 
If it's feasible, then we can move on concretely. 

## 19/11/2025
Look at TTP extraction reports and find the gap between CTI, TTP, and crime scripts, what we are trying to do. 

## 4/12/2025
First check the correctness of the generated report to see if there are no hallucinations or incorrect information. 
Can add a column that abstract the crime script stages more and add a column for tactics and techniques.
General idea is to do attack pattern matching with the modus operandi of attackers through a knowledge base and semantic matching using RAG. 

## 10/12/2025
Make attack flow for TU/e case with MITRE and do more Claude magic with the other reports. 

## 17/12/2025
Refine the attack flow for the TU/e cyberattack and make it more detailed (keeping in mind that there are some unexplained aspects).
Can use similarity vectors to look for compatible information in the knowledge base for MITRE ATT&CK step techniques, looking for qualitative evidence for those attack steps in the crime script.  Later on, building a mapping of stages with tactics and techniques that are in the kill chain. 

Essentially, we want to finalise the terminology and look at four or five more attacks to see which stages map to the MITRE ATT&CK techniques and to the kill chain. What gap exists, where do crime scripts overlap, and is this gap useful to inform on investigations. We are looking at the value of the crime script when compared to the other options. Another aspect is to see which tactics and techniques are most common for each stage, and to iron this detail out. Is preparation almost always linked with reconnaissance and entry with initial access etc. After the break, can look at the results and move on from there. 
