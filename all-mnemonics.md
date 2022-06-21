
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

Risk Management
SLE = AV * EF

Single Loss Expectancy (SLE) - Negative impact for one-time occurrence
Asset Value (AV)
Exposure Factor (EF) - If a flood will damage 40% of your data center, EF is 40%
ARO

Annual Rate of Occurance
ALE = ARO * SLE

🍺 = 😍 (get it?)
Ale makes arousal
Annual Loss Expectancy = Rate of Occurrence - Single Loss Expectancy
Threat Modeling
STRIDE - Microsoft threat modeling tool

S poofing
T ampering
R epudiation - attacker can deny participation
I nformation disclosure
D enial of service
E levation of privilege
Control Types
PTA keeps the children safe!

P hysical - Tangible. Locks, guards, alligator moats, etc.
T echincal/Logical - Automated or electronic systems.
A dministrative - Policy, signage.
Due Care vs Due Diligence
Imagine you have a pool. To protect children and animals from drowning in your pool, you exercise due care by building a fence around the pool. Regularly checking the fence for vulnerabilities and correcting them demonstrates due diligence.

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