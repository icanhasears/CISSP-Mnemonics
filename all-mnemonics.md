
Mnemonics all

NIST SP800-37
People can see I am always monitor
1. Prepare
2. Categoraize information systems
3. Select security controls
4. Implement security controls
5. Assess controls
6. Authorize the system
7. Monitor security controls


Risk Analysis Steps
For Quantitative Risk Analysis
1. Inventory Assets and assign an asset value (AV)
2. Identify Threats - Research each asset and produce a list of all possible threats of each asset (and calculate EF and SLE)
3. Perform a threat analysis to calculate the liklihood of each threat being realised in a year (ARO)
4. Estimate the potential loss by calculating the anualized loss expectancy (ALE)
5. Reasearch countermeasures for each threat and then calculate the changes to ARO and ALE based on the applied countermeasures
6. Perform a cost / benifit analysis of each of our counteremasures to determine cost vs reward

Qualitative - less acurate, based on scoring system = subjective...

    Delphi Technique
    - Anonymous feedback and response process used to arrive at a consensus

Loss potential = what would be lost if the threat agent is successful in exploiting a vulnerability
Delayed loss = the amount of loss that can occure *over time*

Risk Management
SLE = AV * EF% (as decimal)

Single Loss Expectancy (SLE) - Negative impact for one-time occurrence
Asset Value (AV)
Exposure Factor (EF) - If a flood will damage 40% of your data center, EF is 40%
ARO

Annual Rate of Occurance
ALE = ARO * SLE

End to end example:
Office building - $ 200 000
Hurricane damage esimate 50%
Hurricane provability is 1 in 10 years (10%)
SLE = AV * EF 200 000 * .50 = $100 0000
ALE - SLE *ARO 100 000 * 0.10 = $10 000

Safeguards must not cost more than ALE - Safeguard evaluation : 
    - ALE before safeguadrd - ALE after safeguard - Cost of safeguar = value of safeguard
    ALE1 - ALE2 - ACS = value of safeguard

Conrols gap is the difference between total risk and residual risk:
total risk - controls gap = residual risk

Total Risk
Threat * vulnerabilities * asset value = total risk

Risk 
Risk = Threat * Vulnerability

🍺 = 😍 (get it?)
Ale makes arousal
Annual Loss Expectancy = Rate of Occurrence - Single Loss Expectancy


Threat Modeling
Either focused on:
- Assets - uses asset valuation results to identify threats to the valuable assets
- Attackers - Identify potential attackers and identify threats based on the attackers goals
- Software - Considers potential threats against the software the org develops

STRIDE - Microsoft threat modeling tool

S poofing
T ampering
R epudiation - attacker can deny participation
I nformation disclosure
D enial of service
E levation of privilege
Control Types
PTA keeps the children safe!

PASTA - focuses on developing countermeasures based on asset value:
Stage 1 : Definition of Objectives
Stage 2 : Definition of technical scope
Stage 3 App decomposition and Analysis 
Stage 4 : Threat analysis
Stage 5 WEakness and Vulnerability analysis
Stage 6 Attack modeling and Simulation
Stage 7 Risk analysis and management


VAST - GOAL is scalable integration of threat managfement into an Agile programming environment
Visual
Agile
Simple
Threat

DREAD - based on answer to 5 questions
- Damage potential
- Reproducibility 
- Exploitability
- Affected users
- Discoverability

TRIKE - focused on acceptable risk
                   
P hysical - Tangible. Locks, guards, alligator moats, etc.
T echincal/Logical - Automated or electronic systems.
A dministrative - Policy, signage.
Due Care vs Due Diligence
Imagine you have a pool. To protect children and animals from drowning in your pool, you exercise due care by building a fence around the pool. Regularly checking the fence for vulnerabilities and correcting them demonstrates due diligence.

BCP - Business continuity planning ( issues thatpertain to information security in)
*How to continue business
*focus on whole business
Overall polict
1. Strategy development
2. Provisions and processes
3. Plan approval
4. Plan implementation
5. Training and education

DRP -returning the IT infrastructure to operation
*focus on technical aspects
Part of BCP policy

Due Care - A vendor engaging in a reasonable and expected manner for the circumstance
Due Diligence - Demonstrates due care
Domain 3: Security Engineering
Security Models
Brewer-Nash
Brewer-Nash is also known as "The Chinese Wall" and protects against conflict of interest. Remember Chinese "brew" tea. 🍵

Simple Security vs *-Security
You must read before you can write. So reading is "simpler" than writing. This makes reading the simple security model and writing the *-security model.

Integrity vs Confidentiality models
Integrity Models have the letter "I" in them.
Bell LaPadula and Biba - Since Biba has an "I" I it, it is integrity. The two are opposite so Bell is confidentiality. For some something confidential you don't want a subject reading up above their security. So Bell has a no read up property. With this we can extract read and write for both Biba and Bell
Bell	Biba
No Read Up	Read Up
Write Down	No Write Down
Domain 4: Communications & Network Security
Factorization of Primes vs Discreet Logs
Found this somewhere else but it made me laugh and was easy to remember: Mr. Diffie-Hellman and Dr. ElGamal are phantom poopers! They leave discreet logs!

DES Modes of Operation
Most important thing here is remember strength from weakest to strongest. No clear mnemonic to do this. My approach:

Remember the first and the last.
The center 3 are alphabetical by name and/or abbreviation.
ECB - Electronic Code Block (also the only one that doesn't support an initialization vector)
CBC - Cipher Block Chaining
CFB - Cipher Feedback
OFB - Output Feedback Mode
CTR - Counter
Cloud Computing Operating Model
IaaS, PaaS, SaaS - Remember Pizza as a Service

Domain 7: Security operations
Fire Classes and Extinguisher Types
Type	Mneumonic	Description
A	Ash	Ordinary solid combustibles
B	Boil, Bubble	Flammable liquids and gasses
C	Circuits	Electrical equipment
D	Dent	Combustible metals
K	Kitchen	Oils and fats
Domain 8: Software Development Security
Ring computing model
Remember "Zero KODU"

Layer	Purpose
0	Kernal
1	Operating System
2	Drivers
3	User

The IDEAL model and SW-CMM momorization:

I...I, Dr. Ed am lo(w)

IDEAL:
-Initiating
- Diagnosing
- Establishing
- Acting
- Learning

SW-CMM
- Initial - no processes cant control caos
- Repeatable - Reactive
- Defined - Proactive
- Managed - measured and controlled (quantitative)
- Optimizing - hard for most orgs (process improvement)



Categories for controls:

You have 3 cats so you want to call PTA (spelled peta) . Physical Technical Administrative

Then ---- Preventative, Detective, Corrective, Detterent, Recovery, Compensating, Directive

Hashing

Has an HA or MD in the name

Asymmetric

DEREK-Q

Diffie, El gamal, RSA, ECC, Knapsack, Quantum

Symmetric

23BRAIDS

2fish, 3DES, Blowfish, RC5, AES, IDEA, DES, Skipjack

Ciphers

Stream -RC4

Block - Everything else

SW-CMM

I Ran Down My Ostrich

Initial, Repeatable, Defined, Managed, Optimized

Common Criteria

Evaluation Assurance Levels

1 to 7

Fun Stress Method Medical-Doctors Seem Somewhat Verifiably Foolish

Functionally, Structurally, Methodically, Methodically Designed, Semiformally, Semiformally Designed, Verified, Formally Verified

Incident Response (Forensics)

Please Don’t Rub My Red Round Rash, Larry

Prepare, Detect, Response, Mitigate, Reporting, Recovery, Remediation, Lesson Learned

SDLC

IDIOD - Don’t be an IDIOD, learn SDLC

Initiation, Design, Implement, Operations/Maintenance, Disposal

SDLC – CBK

I Reckon All Dem Dere Taters’re Really Delicious

Initiation, Requirements, Architecture, Design, Develop, Testing, Release, Disposal

RMF

Crime Scene Investigators Always Act Modestly

Categorize, Select, Implement, Assess, Authorize, Maintain

OWASP ASWS

AMDI

Automated, Manual, Design, Internal

Forensic Incident Response

I Prefer Coffee Everytime Anyone Provides Donuts

Identification, Preservation, Collection, Examination, Analysis, Presentation, Decision

(ISC)² Ethics

PAPA

Protect, Act, Provide, Advance

ISO

Raging Crackheads Risk Health

Requirements, Code of practice, Risk Management, Health

27001, 27002, 27005, 27799

COBIT

Has IT in it; IT governance

Quantitative Risk Analysis

Drinking ALE makes me SLEep AROund

ALE= SLE x ARO

Fire Types

Class A – turn to ASH -paper

Class B – things that BOIL – liquids

Class C – Current – Electricity

Class D – Things that Detonate or Dent – Metals

Class K - Kitchen