WEEK 1
1. I Completed Introduction to Pentesting
    Lesson 1. Pentesting Fundamentals
        LAB - [ACME Penetration Test](./labs/ACME-Penetration-Test.md) – ACME-Penetration-Test
        1. What is Penetration Testing?
        2. Penetration Testing Ethics
        3. Penetration Testing Methodologies
        4. Black box, White box, Grey box Penetration Testing
        5. Practical: ACME Penetration Test
    Lesson 2. I completed Principles of Security
        1. CIA- Confidentiality, Integrity, Accountability
        2. 
            A. Bell-La Padula Model – A security model focused on confidentiality. It controls access based on hierarchy/roles, this focuses on confidentiality using the rules:
            No Read Up (NRU) – users can’t read data at a higher classification than their clearance.
            No Write Down (NWD) – users can’t write data to a lower classification, to prevent leaking sensitive info. Good for military. 
            But this model has disadvantages
            It relies heavily on trust. 
            B. Biba Model - Focuses on integrity, good for software development
            No Write Up (NWU): A lower-level user cannot write to a higher-level object
            No Read Down (NRD): A higher-level user cannot read lower-level data (prevents being influenced by untrusted/corrupted sources).
            This model leads to lot of neglected important data
        3.  Threat modelling is the process of finding possible security risks in an organisation’s systems, then checking and improving the protections already in place.
            It includes Threat intelligence
            Asset identification
            Mitigation capabilities
            Risk assessment

            To help with this we use STRIDE (Spoofing identity, Tampering with data, Repudiation threats, Information disclosure, Denial of Service and Elevation of privileges) or PASTA(Process for Attack Simulation and Threat Analysis) 

            STEPS TO TAKE TO SOLVE INCIDENT
            Preparation – Do we have the right tools and plans ready if an attack happens?

            Identification – Can we correctly spot what the threat is and who caused it?
            Containment – Can we stop the attack from spreading to other systems or users?
            Eradication – Get rid of the threat completely.
            Recovery – Fix and check affected systems so things go back to normal.
            Lessons Learned – What can we improve to stop this from happening again?

2.  I completed Web-hacking
            A proxy server is a system or router that provides a gateway between users and the internet. Therefore, it helps prevent cyber attackers from entering a private network. It is a server, referred to as an “intermediary” because it goes between end-users and the web pages they visit online.
            Here I have learnt secret ways to discover where secrets are hidden on websites to be able to access website informations that can and this is good knowledge because as a web developer I quicky understand and site informations in code that makes a website vulnerable.