> Text extracted from the submitted PDF. Student IDs removed. Tables and visual page layout may differ; no claim is made that this reproduces the original PDF layout.

## Original page 1

 
Final Research Project 
SEC 1101: Introduction to Cybersecurity 
First Semester 
1447 - 2025 
The Dual-Use Dilemma:  
A Comprehensive Analysis of Artificial 
Intelligence in Cybersecurity—Defensive 
Automations, Offensive Weaponization, and 
the Adversarial Frontier 
 
Student :  
Abdulrahman Ali Alhazmi 
[student ID removed] 
Instructor : 
Dr. Wissam Nabil Omar Eid 
 
 
 
DECEMBER 20, 2025 
 
Department of Computer Science and Artificial Intelligence 
College of Computing 
Umm Al-Qura University 

## Original page 2

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
1 
 
Abstract 
The integration of Artificial Intelligence (AI) into the cybersecurity domain has 
fundamentally altered the strategic landscape of information security, creating a "dual-use" 
dilemma where the same technologies empower both defenders and adversaries. This 
research project provides a comprehensive analysis of this paradigm shift, tracing the 
evolution of cyber defense from static signature-based detection to dynamic, AI-driven 
Autonomous Security Operations Centers (SOCs). It critically examines the mechanisms of 
defensive AI, including unsupervised learning for anomaly detection and behavioral 
biometrics. Conversely, the report investigates the weaponization of AI by threat actors, 
detailing the emergence of "Dark LLMs" like WormGPT, deepfake fraud, and neural-
network-triggered malware such as DeepLocker. Furthermore, the study explores the nascent 
field of Adversarial Machine Learning (AML), analyzing how AI models themselves are 
targeted through evasion and poisoning attacks. The research concludes that while AI is an 
indispensable asset for modern defense, reliance on it necessitates rigorous governance 
frameworks, such as the NIST AI RMF, to mitigate the risks of adversarial manipulation and 
ethical bias. The future of cybersecurity will be defined not by the mere adoption of AI, but 
by the resilience and trustworthiness of the autonomous agents deployed. 
Table of Contents 
1.0 Project Definition and Methodological Framework 1.1 Analysis of Academic 
Requirements and Research Objectives 1.2 Topic Selection and Rationale 1.3 Scope and 
Structure of the Report 

## Original page 3

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
2 
 
2.0 Historical Context and the Evolution of Cyber Defense 2.1 First Generation: 
Signature-Based Detection (The Static Era) 2.2 Second Generation: Heuristics and Rules-
Based Analysis 2.3 Third Generation: The AI and Machine Learning Paradigm 
3.0 Artificial Intelligence in Defensive Operations 3.1 The Autonomous Security 
Operations Center (SOC) 3.1.1 Unified Data Ingestion and Normalization 3.1.2 
Hyperautomation and Agentic AI 3.2 Immune System Technology: Unsupervised Learning 
in Action 3.2.1 Behavioral Baselines and Pattern of Life 3.3 Biometric Continuous 
Authentication 3.3.1 Behavioral Biometrics 
4.0 The Weaponization of AI: The Offensive Frontier 4.1 Generative AI and "Dark 
LLMs" 4.1.1 WormGPT and FraudGPT 4.2 Deepfakes: The Erosion of Trust 4.2.1 The Arup 
Case Study 4.3 AI-Powered Malware: DeepLocker 4.3.1 Neural Network Trigger 
Mechanisms 
5.0 The New Battleground: Adversarial Machine Learning (AML) 5.1 Taxonomy of 
Attacks 5.1.1 Evasion Attacks (Adversarial Examples) 5.1.2 Data Poisoning Attacks 5.1.3 
Model Extraction 5.2 Defensive Countermeasures 
6.0 Governance, Ethics, and Future Trajectories 6.1 The Regulatory Landscape 6.2 
Ethical Implications 6.3 Future Outlook (2025-2030) 
7.0 Conclusion 
Table 1: Comparative Analysis of Potential Research Topics  
Table 2: Comparison of Traditional vs. AI-Driven SOC Architectures 
Table 3: Summary of Key Findings 
References 

## Original page 4

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
3 
 
1.0 Project Definition and Methodological Framework 
1.1 Topic Selection and Rationale 
The selection of a suitable topic for this research involved a comparative analysis of several 
emerging domains within cybersecurity, evaluating them based on relevance, depth of 
available literature, and potential for critical debate.  
Table 1: Comparative Analysis of Potential Research Topics 
Potential Topic Relevance to CYS Depth of Available 
Literature 
Critical Debate 
Potential 
Selection Decision 
IoT Security High (Proliferation of 
devices) 
High (Technical 
specs available) 
Moderate 
(Standardization 
issues) 
Rejected (Focus often 
limited to device 
hardening) 
Blockchain in Cyber Moderate (Niche 
application) 
Moderate (Emerging 
field) 
High 
(Decentralization vs. 
Control) 
Rejected (Too narrow 
for exhaustive 15k 
word scope) 
Zero Trust 
Architecture 
High (Industry 
standard) 
High 
(Implementation 
guides) 
Low (Consensus 
exists on benefits) 
Rejected (More 
procedural than 
analytical) 
AI in Cybersecurity Critical 
(Transformative 
technology) 
Very High (Rapidly 
evolving) 
Very High (Dual-use 
nature, ethics, 
adversarial attacks) 
Selected 
The analysis indicates that "Artificial Intelligence in Cybersecurity" offers the most fertile 
ground for a comprehensive research project. It encompasses the dual-use dilemma—where 
the same technology empowers both defenders and attackers—providing ample material for 
the "detailed analysis" and "ethical implications" sections required by the assignment.1 
Furthermore, the rapid evolution of Generative AI (GenAI) and Adversarial Machine 

## Original page 5

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
4 
 
Learning (AML) allows for a forward-looking discussion on current trends and future 
predictions, satisfying the requirement to explore "future predictions".1 
1.3 Scope and Structure of the Report 
This report adopts a holistic approach to the subject, structured to lead the reader from 
historical context to advanced technical concepts. Section 2.0 establishes the historical 
evolution of cyber defense, contrasting legacy methods with modern AI paradigms. Section 
3.0 provides a deep technical dive into AI-driven defense, specifically the architecture of 
Autonomous Security Operations Centers (SOCs). Section 4.0 pivots to the offensive 
weaponization of AI, analyzing tools like WormGPT and DeepLocker. Section 5.0 introduces 
the complex field of Adversarial Machine Learning (AML), detailing mathematical attack 
vectors like the Fast Gradient Sign Method (FGSM). Finally, Section 6.0 and 7.0 address 
governance, ethical frameworks (NIST AI RMF), and future strategic implications. 
2.0 Historical Context and the Evolution of Cyber Defense 
To fully appreciate the disruptive impact of Artificial Intelligence on cybersecurity, one must 
first understand the limitations of the paradigms that preceded it. The history of cybersecurity 
is effectively a chronicle of the escalating complexity between attack vectors and defensive 
countermeasures. This evolution can be categorized into three distinct generations, each 
defined by the dominant technology used to identify and neutralize threats. 
2.1 First Generation: Signature-Based Detection (The Static Era) 
The nascent stages of cybersecurity, primarily spanning the 1980s and 1990s, were 
characterized by signature-based detection mechanisms. During this period, the threat 
landscape was relatively static; viruses were static pieces of code that, once written, did not 
change their structure as they propagated from system to system.2 Organizations relied on 
antivirus software—such as early iterations of Norton or McAfee—which functioned 

## Original page 6

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
5 
 
essentially as digital librarians. These systems maintained a database of known "signatures" 
(unique file hashes or byte sequences) associated with confirmed malware. 
When a file entered a network or was accessed on a disk, the antivirus engine would scan it, 
calculating its hash and comparing it against the database. If a match was found, the file was 
flagged and quarantined. This deterministic approach offered a high degree of certainty; false 
positives were rare because a match meant the file was identical to a known threat.3 However, 
this model suffered from a fatal flaw known as the "Patient Zero" problem. For a signature to 
exist, at least one organization had to be infected, the malware analyzed by a researcher, and 
a signature update pushed to all users. In the gap between the initial infection and the 
database update—a window that could last days or weeks—systems remained entirely 
vulnerable. As cybercriminals began utilizing polymorphism (where malware changes its 
code slightly with each iteration to alter its hash), signature-based detection became 
increasingly inadequate.4 
2.2 Second Generation: Heuristics and Rules-Based Analysis 
As threats evolved in the 2000s, the industry moved toward heuristic analysis and rules-based 
intrusion detection systems (IDS). This approach attempted to overcome the rigidity of 
signatures by looking for suspicious characteristics or behaviors rather than exact code 
matches.5 Heuristics might flag a program not because it matched a known virus, but because 
it was attempting to modify system files in a way that was typical of malware. 
Simultaneously, "anomaly detection" began to emerge, though in a rudimentary form. These 
systems established a static baseline of network traffic—for instance, defining that "Web 
Server A should only communicate on Port 80 and 443." Any deviation from these pre-
defined rules would trigger an alert. While this improved the detection of unknown threats 
(zero-days), it introduced a new problem: the "false positive paradox".6 Legitimate user 
behaviour is often unpredictable; an employee working late might access servers at unusual 

## Original page 7

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
6 
 
hours, or a new software update might communicate over a different port. Rules-based 
systems lacked the nuance to distinguish these benign anomalies from malicious ones, 
leading to alert fatigue where security analysts were overwhelmed by thousands of 
meaningless warnings.7 
2.3 Third Generation: The AI and Machine Learning Paradigm 
The current era involves the integration of Artificial Intelligence and Machine Learning (ML) 
into the core of defense strategies. This shift was necessitated by the explosion of data and 
the "speed of code" at which modern attacks occur. Unlike static rules, AI models are 
probabilistic and dynamic. They utilize Deep Learning (DL) and neural networks to ingest 
massive amounts of unstructured data—logs, network traffic, user behavior, cloud 
telemetry—to learn complex, multidimensional patterns of "life" within a network.4 
This transition represents a move from "detection" to "prediction" and "autonomous 
response." AI systems do not wait for a known signature; they establish a bespoke baseline 
for every user and device in an environment. If a device that typically transfers small amounts 
of text data suddenly begins uploading gigabytes of encrypted files to a rare external IP 
address, the system identifies this as anomalous based on the deviation from the learned 
pattern, not a static rule.8 This capability is critical for detecting "living off the land" attacks, 
where adversaries use legitimate system tools (like PowerShell) to conduct malicious 
activities—attacks that would otherwise be invisible to legacy antivirus solutions.9 
3.0 Artificial Intelligence in Defensive Operations 
The integration of AI into cyber defense mechanisms has become the cornerstone of modern 
enterprise security strategies. The sheer volume of telemetry data generated by modern IT 
infrastructures—often reaching terabytes per day—exceeds the processing capacity of human 
analysts. AI serves as a force multiplier, automating the analysis of this data to identify 
threats with greater speed and accuracy than previously possible. 

## Original page 8

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
7 
 
3.1 The Autonomous Security Operations Center (SOC) 
The concept of the "Autonomous SOC" represents the zenith of AI application in defense. 
Traditional SOCs are often plagued by inefficiencies: siloed tools, manual data correlation, 
and high analyst turnover due to burnout.10 The AI-driven SOC fundamentally restructures 
this environment by delegating Tier 1 (triage) and Tier 2 (investigation) tasks to AI agents, 
reserving human expertise for strategic decision-making and threat hunting.11 
3.1.1 Unified Data Ingestion and Normalization 
The foundation of an AI-driven SOC is its ability to ingest and normalize data from diverse 
sources. In a typical enterprise, security data is fragmented across Endpoint Detection and 
Response (EDR) tools, firewalls, cloud platforms (AWS, Azure), and Identity and Access 
Management (IAM) systems. An autonomous SOC utilizes AI to aggregate these disparate 
signals into a "unified context fabric".12 
● Mechanism: The AI engine normalizes inconsistent log formats into a standardized schema. 
It then correlates events across time and infrastructure. For example, a failed login on a cloud 
portal (IAM signal) followed immediately by a PowerShell execution on a laptop (EDR 
signal) are linked into a single "incident" narrative. This correlation reduces the noise of 
isolated alerts, presenting analysts with a coherent story rather than a disjointed list of logs.13 
3.1.2 Hyperautomation and Agentic AI 
Beyond detection, the modern SOC employs "Agentic AI"—autonomous software agents 
capable of executing complex workflows without human intervention. This is often referred 
to as "hyperautomation".11 Unlike traditional Security Orchestration, Automation, and 
Response (SOAR) platforms that follow rigid, linear playbooks (e.g., "If X happens, do Y"), 
Agentic AI possesses reasoning capabilities. 
● Adaptive Response: If an AI agent detects a potential ransomware infection, it can 
dynamically decide the best course of action based on the asset's criticality and the attack's 

## Original page 9

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
8 
 
severity. It might autonomously isolate the infected endpoint from the network to prevent 
lateral movement, revoke the compromised user credentials, and initiate a snapshot of the 
system for forensic analysis—all within seconds.14 
● Quantitative Impact: Empirical data supports the efficacy of this approach. Organizations 
deploying AI-driven SOCs report up to a 92% reduction in triage time and can handle 99% 
of routine analyst tasks autonomously.15 Furthermore, AI-based threat detection systems have 
been shown to identify attacks 85% faster than traditional methods, significantly reducing 
the "dwell time" attackers have within a network.16 
Table 2: Comparison of Traditional vs. AI-Driven SOC Architectures 
Feature Traditional SOC AI-Driven / Autonomous SOC 
Data Analysis Manual review of aggregated 
logs 
Automated normalization and 
correlation of telemetry 
Detection Method Rule-based, signature matching Behavioral anomaly detection, 
predictive analytics 
Response Time Minutes to Hours (Human 
speed) 
Seconds (Machine speed) 
False Positives High (Rule fragility) Reduced (Context-aware 
filtering) 
Analyst Role Alert triage, repetitive 
investigation 
Strategic threat hunting, policy 
governance 
Scalability Linear (Requires more staff for 
more data) 
Exponential (AI scales with 
data volume) 
3.2 Immune System Technology: Unsupervised Learning in Action 
A dominant philosophy in AI defense is the "immune system" approach, pioneered by 
companies like Darktrace. This methodology draws a biological parallel: just as the human 

## Original page 10

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
9 
 
immune system does not need to know the name of a virus to attack it (recognizing it simply 
as "non-self"), digital immune systems do not need to know the specific signature of a cyber 
threat to identify it.8 
3.2.1 Behavioral Baselines and Pattern of Life 
This technology utilizes unsupervised machine learning to establish a "pattern of life" for 
every entity in the digital ecosystem—users, devices, and containers. It learns what is normal: 
User A typically accesses the HR server between 9 AM and 5 PM from a London IP address; 
Server B typically sends 50MB of data daily to a specific backup location. 
● Deviation Detection: When an event occurs that mathematically deviates from this 
probabilistic baseline—such as User A accessing the HR server at 3 AM from a North Korean 
IP address, or Server B attempting to upload 500GB of data to an unknown Dropbox 
account—the system flags it as anomalous.4 
● Case Study (Ransomware): In a documented incident involving a healthcare organization, 
Darktrace's AI detected a "low and slow" attack where a device was encrypting files over the 
SMB protocol. Although the specific ransomware strain was unknown (a zero-day), the 
behavior of rapid, high-volume file modification was fundamentally anomalous for that 
device. The AI autonomously interrupted the connection, enforcing a "digital antibody" 
response that neutralized the threat seconds after it began, preventing widespread data loss.8 
3.3 Biometric Continuous Authentication 
Security creates friction; users hate complex passwords and repeated login prompts. AI 
resolves this conflict through Biometric Continuous Authentication, moving security from 
a "gatekeeper" model (checking ID at the door) to a "bodyguard" model (constant 
monitoring).18 

## Original page 11

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
10 
 
3.3.1 Behavioral Biometrics 
Unlike static biometrics (fingerprint, FaceID) which validate identity only at the moment of 
access, behavioral biometrics leverage AI to analyze how a user interacts with a device. Deep 
learning models ingest data points such as typing rhythm (keystroke dynamics), mouse 
movement curvature, touchscreen swipe speed, and even gyroscope data indicating how a 
phone is held.18 
● Fraud Prevention: If a legitimate user's session is hijacked by an attacker (via a remote 
access trojan or stolen cookie), the interaction patterns will shift. The attacker will not type 
with the same cadence or move the mouse with the same distinct habits as the victim. The AI 
detects this behavioral divergence in real-time and can silently lock the account or trigger a 
step-up authentication challenge (e.g., requesting a facial scan).19 This capability is crucial for 
financial institutions preventing account takeovers (ATO) and fraud.16 
4.0 The Weaponization of AI: The Offensive Frontier 
The democratization of AI is a double-edged sword. The same algorithms that allow 
defenders to predict threats enable adversaries to execute attacks with unprecedented 
sophistication, speed, and scale. "Offensive AI" lowers the barrier to entry for cybercrime, 
allowing relatively unskilled actors to launch campaigns that previously required nation-state 
capabilities.20 
4.1 Generative AI and "Dark LLMs" 
The release of Large Language Models (LLMs) has revolutionized social engineering. While 
commercial models like ChatGPT have safety filters (RLHF - Reinforcement Learning from 
Human Feedback) to prevent misuse, cybercriminals have developed "Dark LLMs"—
uncensored models trained specifically on malicious datasets.21 

## Original page 12

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
11 
 
4.1.1 WormGPT and FraudGPT 
WormGPT emerged in 2023 as a prominent example of this trend. Built upon the open-
source GPT-J 6B model, it was fine-tuned on a vast corpus of malware-related data, including 
exploit codes and phishing templates.22 
● Capabilities: WormGPT excels at generating Business Email Compromise (BEC) attacks. It 
can craft highly personalized, persuasive emails that mimic the tone and style of executives, 
devoid of the spelling errors and awkward phrasing that typically betray phishing attempts.21 
● Economic Model: These tools are marketed on dark web forums under a "Cybercrime-as-a-
Service" model. For a subscription fee (e.g., roughly $200/month or €60-500 depending on 
the variant), adversaries gain access to a tool capable of generating polymorphic malware 
code, writing fraudulent invoices, and automating the creation of phishing pages.22 
● Evolution: Newer variants, such as WormGPT 4, have reportedly integrated advanced 
features like obfuscation to bypass defensive filters, further complicating detection efforts.21 
4.2 Deepfakes: The Erosion of Trust 
Generative AI has extended the attack surface to audio and video, creating a crisis of 
authenticity. "Deepfakes" utilize Generative Adversarial Networks (GANs) or diffusion 
models to create hyper-realistic synthetic media that can bypass voice biometrics and deceive 
human targets. 
4.2.1 The Arup Case Study 
A watershed moment in AI-enabled fraud occurred in early 2024 involving the engineering 
firm Arup. An employee in the finance department received a message purportedly from the 
company's CFO requesting a confidential transaction. Suspicious, the employee requested a 
video call. 
● The Deception: The attackers orchestrated a live video conference where the CFO and 
several other colleagues were present. However, every participant other than the victim was a 

## Original page 13

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
12 
 
deepfake—AI-generated real-time avatars responding to the conversation. Convinced by the 
visual evidence, the employee authorized transfers totaling HK$200 million (approximately 
US$25 million).24 
● Implications: This incident underscores that "seeing is believing" is a defunct concept in 
cybersecurity. Standard verification procedures (call-backs, video confirmation) are 
vulnerable to real-time AI manipulation. 
4.3 AI-Powered Malware: DeepLocker 
Beyond social engineering, AI is being integrated directly into malware payloads to enhance 
stealth and targeting precision. DeepLocker, a proof-of-concept developed by IBM Research, 
illustrates the potential of "AI-locked" malware.26 
4.3.1 Neural Network Trigger Mechanisms 
Traditional malware relies on simple logic (e.g., if date == X, execute payload). This logic is 
easily discoverable by security analysts through reverse engineering. DeepLocker, however, 
conceals its malicious payload within a benign carrier application (like a video conferencing 
app) and encrypts it. The decryption key is not stored in the code but is derived from the 
output of a deep neural network (DNN). 
● Targeting: The DNN is trained to recognize a specific target—for example, a specific face, 
voice pattern, or geolocation. The malware runs innocuously on thousands of machines, 
continuously feeding sensor data (webcam images, microphone audio) into the neural 
network. 
● Execution: Only when the neural network recognizes the specific target (e.g., the CEO's face 
appears in the webcam), it generates the correct decryption key to unlock the payload (e.g., 
WannaCry ransomware). This makes the malware highly targeted and extremely difficult to 
analyze, as the trigger condition is hidden within the opaque weights of the neural network 
("black box" AI) rather than in readable code.28 

## Original page 14

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
13 
 
5.0 The New Battleground: Adversarial Machine Learning 
(AML) 
As reliance on AI for defense grows, the AI models themselves become high-value targets. 
Adversarial Machine Learning (AML) is the discipline concerned with attacking and 
defending ML systems. These attacks do not exploit software bugs (like buffer overflows) but 
rather exploit the fundamental mathematical properties of learning algorithms.30 
5.1 Taxonomy of Attacks 
The NIST publication Adversarial Machine Learning: A Taxonomy and Terminology of 
Attacks and Mitigations (NIST AI 100-2) categorizes these threats into three primary vectors: 
Evasion, Poisoning, and Extraction.31 
5.1.1 Evasion Attacks (Adversarial Examples) 
Evasion attacks target the inference phase of the AI lifecycle. The attacker creates an 
"adversarial example"—an input that has been subtly modified to deceive the model while 
appearing normal to humans.30 
● Mathematical Mechanism: Techniques like the Fast Gradient Sign Method (FGSM) 
calculate the gradient of the model's loss function with respect to the input data. By applying 
a perturbation ($\epsilon$) in the direction of the gradient, the attacker pushes the input 
across the decision boundary. 
○ Formula: $x' = x + \epsilon \cdot \text{sign}(\nabla_x J(\theta, x, y))$.32 
○ Where $x$ is the original input (e.g., an image of a stop sign), $y$ is the correct label, and 
$\theta$ represents the model parameters. 
● Impact: In a cybersecurity context, an attacker could add imperceptible "noise" bytes to a 
malware file. To a human analyst or a traditional hash check, the file looks malicious. 
However, the AI-based antivirus, fooled by the perturbation, classifies it as "benign" 

## Original page 15

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
14 
 
software, allowing the malware to bypass detection.34 
5.1.2 Data Poisoning Attacks 
Poisoning attacks target the training phase. If an attacker can inject malicious data into the 
training set, they can fundamentally alter the model's behavior.35 
● Backdoor Attacks: The attacker injects data that teaches the model to associate a specific 
"trigger" with a wrong classification. For example, in a facial recognition system for building 
access, an attacker might poison the training data with images of unauthorized people 
wearing a specific pair of glasses, labeled as "authorized." Once deployed, anyone wearing 
those glasses (the trigger) is granted access, creating a permanent backdoor in the AI.37 
● Label Flipping: A simpler form where the attacker accesses the training dataset and flips the 
labels of malicious samples to "benign." This is particularly dangerous for systems that use 
"online learning" to update their models based on new data streams.36 
5.1.3 Model Extraction 
These attacks violate the confidentiality of the AI system. An attacker queries the model's API 
with a large number of inputs and records the outputs (predictions and confidence scores). By 
analyzing the relationship between inputs and outputs, the attacker can train a "surrogate 
model" that mimics the proprietary model's behavior.38 This allows adversaries to steal 
intellectual property or to test evasion attacks offline before launching them against the real 
target, avoiding detection. 
5.2 Defensive Countermeasures 
Defending against AML is challenging and often involves a trade-off between robustness and 
accuracy. 
● Adversarial Training: The most effective defense is to train the model on adversarial 
examples. By including FGSM or PGD (Projected Gradient Descent) generated attacks in the 
training set, the model learns to recognize and ignore the perturbations.40 

## Original page 16

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
15 
 
● Defensive Distillation: This involves training a secondary "student" model to predict the 
probability outputs (soft labels) of a "teacher" model, rather than hard class labels. This 
smooths the model's decision boundaries, making it less sensitive to the small perturbations 
used in gradient-based attacks.4 
● Data Sanitization: Rigorous scrubbing of training data to identify and remove outliers or 
poisoned samples before training begins.3 
 
 
 
 
6.0 Governance, Ethics, and Future Trajectories 
6.1 The Regulatory Landscape 
Recognizing the systemic risks posed by AI, governments and standards bodies are racing to 
establish governance frameworks. 
● NIST AI Risk Management Framework (AI RMF): This voluntary framework provides a 
structure (Govern, Map, Measure, Manage) for organizations to manage AI risks. It 
emphasizes characteristics of trustworthy AI, including validity, reliability, safety, security, 
and resiliency.43 
● EU AI Act: A landmark regulation that categorizes AI systems by risk level. "High-risk" AI 
systems (which include many critical infrastructure and biometric ID systems) face strict 
compliance obligations regarding data governance, transparency, and human oversight.44 
6.2 Ethical Implications 
The deployment of AI in security raises profound ethical questions. 

## Original page 17

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
16 
 
● Bias and Fairness: AI models trained on biased datasets can perpetuate discrimination. 
Facial recognition algorithms used in security surveillance have historically demonstrated 
higher error rates for certain demographic groups, leading to potential false accusations or 
denial of access.45 
● Privacy vs. Surveillance: AI-driven behavioral analytics require the continuous monitoring 
of user activity. This blurs the line between necessary security monitoring and intrusive 
employee surveillance, raising concerns about "purpose drift" where security data is used for 
performance metrics.46 
6.3 Future Outlook (2025-2030) 
The trajectory of AI in cybersecurity points toward "machine-on-machine" conflict. We are 
entering an era of Agentic AI, where autonomous AI agents will not only detect threats but 
actively hunt them, patch systems, and negotiate responses.13 Conversely, we must anticipate 
the rise of autonomous malware—agents capable of self-propagation, lateral movement, and 
decision-making within a target network without command-and-control (C2) communication, 
making them impervious to traditional network blocking strategies.47 By 2030, the "cyber 
arms race" will likely evolve into a contest of algorithmic superiority, where the resilience of 
an organization's AI models is as critical as the strength of its firewalls. 
 
7.0 Conclusion 
The integration of Artificial Intelligence into cybersecurity represents a paradigm shift of 
equal magnitude to the invention of the internet itself. It is a double-edged sword that 
empowers defenders with the ability to analyze data at scale and respond to threats at 
machine speed, while simultaneously arming adversaries with tools to automate sophisticated 
attacks and bypass traditional verification methods. The research presented in this report 

## Original page 18

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
17 
 
highlights that the transition to AI-driven defense is not merely an option but a survival 
imperative in the face of exponential threat growth. Technologies like the Autonomous SOC 
and immune system anomaly detection offer the only viable path to securing complex digital 
ecosystems against the sheer volume of modern attacks. 
However, this reliance on AI introduces a new, critical vulnerability: the susceptibility of the 
AI systems themselves to adversarial manipulation. As demonstrated by the analysis of 
Adversarial Machine Learning (AML), the models we trust to protect us can be deceived by 
imperceptible perturbations or poisoned data. Therefore, the future of cybersecurity lies not in 
the blind adoption of AI, but in the cultivation of Secure AI. This requires a holistic strategy 
that combines advanced technical defenses—such as adversarial training and defensive 
distillation—with rigorous governance frameworks like the NIST AI RMF. 
Looking toward 2030, the industry must prepare for a "machine-on-machine" conflict where 
human reaction times are insufficient. In this era, the victor in the cyber domain will be 
determined not by who possesses the largest datasets, but by who deploys the most resilient, 
ethically governed, and autonomously capable intelligence. Organizations must treat AI 
models as high-value assets requiring their own dedicated defense perimeters, ensuring that 
the guardians of our digital infrastructure remain incorruptible. 
Domain Key Trend Implication 
Defense Shift to Autonomous SOCs Reduced response times; shift of 
human role to strategy. 
Offense Democratization of capabilities via 
Dark LLMs 
Lower barrier to entry; increase in 
sophisticated phishing. 
Identity Deepfakes compromising 
biometrics 
"Zero Trust" must extend to 
audio/visual verification. 

## Original page 19

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
18 
 
Vulnerability Adversarial Machine Learning 
(AML) 
AI models are the new attack 
surface (poisoning/evasion). 
Regulation Emergence of AI-specific 
frameworks (NIST) 
Compliance will require 
documenting AI robustness/safety. 
 
 
 
 
 
 
Works cited 
References 
[1] P. Radanliev, O. Santos, and U. D. Ani, "Generative AI cybersecurity and 
resilience," IEEE Access, vol. 12, pp. 109470-109493, 2024. [Online]. 
Available: https://ieeexplore.ieee.org/document/10623653/    
[2] SentinelOne, "History and evolution of AI in cybersecurity," SentinelOne Blog, 2024. 
[Online]. Available: https://www.sentinelone.com/cybersecurity-101/data-and-ai/artificial-
intelligence-in-cybersecurity/    
[3] Swimlane, "Autonomous SOC: Next-Gen Security Operations Center," Swimlane Blog, 
2024. [Online]. Available: https://swimlane.com/blog/autonomous-soc-next-gen-security-
operations-center/    

## Original page 20

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
19 
 
[4] IBM Security, "Cost of a Data Breach Report 2024," IBM, 2024. [Online]. 
Available: https://www.ibm.com/reports/data-breach    
[5] Darktrace, "The Enterprise Immune System: White Paper," Darktrace, 2023. [Online]. 
Available: https://www.darktrace.com/en/resources/    
[6] SlashNext, "WormGPT: The Generative AI Tool Cybercriminals Are Using to Launch 
Business Email Compromise Attacks," SlashNext Blog, July 2023. [Online]. 
Available: https://slashnext.com/blog/wormgpt-the-generative-ai-tool-cybercriminals-are-
using/    
[7] H. Davidson, "Finance worker pays out $25m after video call with deepfake 'chief 
financial officer'," The Guardian, Feb. 2024. [Online]. 
Available: https://www.theguardian.com/technology/2024/feb/04/finance-worker-pays-
out-25m-after-video-call-with-deepfake-chief-financial-officer    
[8] D. Kirat, J. Jang, and M. Stoecklin, "DeepLocker: Concealing Targeted Attacks with AI 
Locksmithing," in Black Hat USA, 2018. [Online]. 
Available: https://research.ibm.com/publications/deeplocker-concealing-targeted-attacks-
with-ai-locksmithing    
[9] T. Balarabe, "Adversarial Machine Learning: A Taxonomy and Terminology," Medium, 
2023. [Online]. Available: https://medium.com/@tahirbalarabe2    
[10] TensorFlow, "Adversarial example using FGSM," TensorFlow Core, 2024. [Online]. 
Available: https://www.tensorflow.org/tutorials/generative/adversarial_fgsm    

## Original page 21

 
 
FINAL RESEARCH PROJECT        INTRODUCTION TO CYBERSECURITY - SEC 1101 
 
20 
 
[11] NIST, "Adversarial Machine Learning: A Taxonomy and Terminology of Attacks and 
Mitigations (NIST AI 100-2)," National Institute of Standards and Technology, Jan. 2024. 
[Online]. Available: https://csrc.nist.gov/pubs/ai/100/2/e2023/final 
 
