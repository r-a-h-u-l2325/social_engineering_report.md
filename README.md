# social_engineering_report.md

Objective: Research and write a detailed report on social engineering attacks such as phishing, pretexting, and baiting.

SOCIAL ENGINEERING ATTACKS:- Social Engineering attacks are psychological manipulations that exploit human behavior and trust to gain unauthorized access to systems,data,or physical locations.Unlike traditional hacking,which relies on exploiting technical bulnerabilities,social engineering targets the weakest link in cybersecurity.These attacks are prevalent,effective, and increasingly sophisticated, making them one of the top cybersecurity threats faced by organizations globally.

Working of Social Engineering Attack:-
social engineering relies on deception,manipulation, and persuasion.The attacker impersonates a trusted individual,authority figure, or colleague to trick the victim into Divulging confidential information(e.g.,passwords,PINs, or credentials),Clicking malicious links or downloading malware,granting physical or digital access to restricted systems.

The attackers typically follows a process:
1) Research: Gather information about the target(company structure,employee names,email formats,etc)
2) Engagement: Initiate contact using email,phone,social media, or in person.
3) Exploitation: Manipulate the victim into performing an action.
4) Executiom: Use the gained access or information to complete the attack.


Now we will discuss about the types of social engineering attacks

1) Phishing
Phishing is a form of social engineering attack in which cybercriminals deceive users into revealing sensitive information such as login credentials,credit card numbers, or personal data by pretending to be a trustworthy entity.It typically occurs through emails,messages, or fake websites that appear legitimate.The main goal of phishing is to steal data,compromise systems or gain unauthorized access to networks and accounts.

Working of Phishing
1) Attackers collect email addresses,roles, or company info via data leaks or public records.
2) A fake but convincing email or message is created, mimicking a legitimate entity(e.g., bank,employer,government)
3) Email or message is sent to the target with a link or attachment.
4) Target is lured into clicking a malicious link or downloading a file.
5) Victim enters sensitive information or unknowingly installs malware/keylogger.
6) Collected data is used to commit fraud,financial theft,or further infiltrate systems.

Types of Phishing Attacks
* Email Phishing: Generic emails are sent to many users(e.g.,fake bank alerts)
* Spear Phishing: Targeted attack aimed at specific individuals using personal information.
* Whaling: Targets high profile individuals like CEOs or CFOs.
* Smishing: Phishing via SMS messages.
* Vishing: Voice phishing using phone calls pretending to be banks,support agents.

Case Studies of Phishing Attacks

1) Google and Facebook(2013-2015)
A lithuanian man created a fake company impersonating Quanta Computer,a legitimate taiwanese vendor that supplied hardware to both googlr and facebook.He registered a fraudulent company with a similar name and set up corresponding email addresses.He sent fake invoices and phishing emails requesting payments for services that appeared legitimate.Multiple payments were made to accounts controlled by the attacker.

Impact:- approximately $100 million was stolen.The stolen funds were transferred through Latvia,Cyprus,Slovakia,Lithuania,Hungary and Hong Kong to conceal their origin.

Detection and Response:- U.S. law enforcement agencies, including the FBI, launched an international investigation.The man was arrested in lithuania in 2017,extradited to the U.S., and                             pleaded guilty.Some of the stolen funds were recovered.

2) Sony Pictures Hack(2014)
In sony pictures hack spear phishing emails were sent to sony employees,disguised as messages from apple requesting email and password verification.Employees fell for the scam and entered their credentials.Attackers used this information to penetrate deeper into the network.The attacker was later attributed to a hacker group known as 'Guardians of Peace' allegedly sponsored by North Korea.The initial attack occured in september 2014 but in november 2014, a massive breach had taken place.

Impact:-Leak of 100 terabytes of data including unreleased movies,personal employee data,executive emails with sensitive conversations,salary information and social security numbers.
        Financial damage estimated in million of dollors.
        severage damage to sony's reputation and employee trust.

Detection and Response:- Sony shut down parts of its network.
                         FBI attributed the attack to North Korean actors.
                         Sony enhanced security measures post-incident,including identity verification training and phishing simulations.

3) Colonial Pipeline Ransomware Attack(2021)
In this attack attackers gained through a compromised VPN account-likely credentials obtained via phishing or from a prior data breach.The credentials did not use multi-factor authentication.The dark side ransomware group encrypted systems and demanded ransom.The attack began on May 7,2021.Colonial shut down the entire pipeline to contain the breach.

Impact:- Widespread fuel shortages in several U.S. states.
         Panic buying and fuel surges.
         The company paid 4.4 million dollor bitcoin to the attackers.
         U.S. government later recovered 2.3 million dollor of that amount.

Detection and Response:-FBI and cybersecurity teams responded quickly.
                        Prompt public notification and ransom payment helped limit downtime.
                        Colonial upgraded its security infrastructure post-incident.

 Impacts on Organizations:-
 1) Financial Loss:- Ransom payments ,fraud,legal fines, and operational disruptions.
 2) Reputational Damage:- Loss of customer trust and brand credibility.
 3) Legal and Compliance Risks:- Violations of GDPR,HIPAA, or other data protection laws.
 4) Operational Downtime:- Systems and Services may be halted for investigation and recovery.
 5) Intellectual Property Theft:- Leaks of proprietary data,plans,or sensitive communications.

Research Findings on Phishing Trends:-
Based on reports from organizations like Verizon(DBIR),Proofpoint and IBM:
                                                                           90%+ of cyber attacks begin with phishing.
                                                                           Spear Phishing is 3x more successful than standard phishing.
                                                                           Employee click rates are highest during COVID-19 related phishing emails.
                                                                           Average cost of a data breach due to phishing is over $4.9 million.
                                                                           AI-generated phishing emails are harder to detect and more successful than traditional ones.

PREVENTIVE MEASURES

Technical Controls:-
                     Email Filtering and Anti-Spam Tools: Use services like Mimecast, Proofpoint, Microsoft Defender.
                     Multi-Factor Authentication (MFA): Protect access even if credentials are stolen.
                     Domain-Based Message Authentication (DMARC): Prevent email spoofing.
                     Security Awareness Tools: Phish testing and simulations (e.g., KnowBe4, Cofense).
                     Browser and URL Filtering: Block access to known phishing domains.


 Organizational & Human Controls:-
                                   Security Awareness Training: Teach employees to identify suspicious emails.
                                   Incident Response Plan: Define steps for detecting and responding to phishing.
                                   Least Privilege Principle: Limit user access to only what is necessary.
                                   Reporting Mechanism: Allow easy reporting of suspicious emails internally.


 Real-World Examples of Prevention:-
                                     Google implemented FIDO2 security keys company-wide, virtually eliminating employee phishing-related breaches.
                                     Twitter (post-2020 breach) enforced stricter MFA and security training after a social engineering attack compromised internal tools.
                                     Microsoft reported that MFA blocks 99.9% of automated phishing attempts.
                                                                           


2) Pretexting
Pretexting is a form of social engineering attack where an attacker fabricates a believable scenario or identity (a “pretext”) to trick a victim into divulging sensitive information or performing actions they normally wouldn’t. The attacker often impersonates authority figures like IT support, HR personnel, bank officials, or law enforcement officers to establish credibility and exploit the trust of the victim.Pretexting typically involves extensive research about the target and is often more sophisticated than phishing, as it requires real-time interaction and manipulation.

Working of Pretexting
1) The attacker gathers personal or organizational information (names, titles, procedures).This can be done via social media, dumpster diving, leaked databases, or other open sources (OSINT).
2) The attacker builds a convincing persona (e.g., an auditor, IT admin, new employee).The pretext often includes specific jargon, knowledge, and context to appear legitimate.
3) Contact is made via phone, email, text, or even in person.The attacker exploits human trust or fear to extract data (e.g., login credentials, SSN, bank info).
4) Once trust is gained, the attacker asks for confidential information or requests an action (e.g., wire transfer, password reset).
5) Attackers may chain pretexting with phishing or other attacks for broader compromise.


Case Studies of Pretexting Attacks

1) Hewlett-Packard (HP) Boardroom Pretexting Scandal(2006)
In 2006, Hewlett-Packard (HP), one of the world’s largest tech companies, became embroiled in a corporate espionage scandal. The company was investigating media leaks from boardroom meetings.HP hired external investigators to identify the source of leaks to journalists.These investigators used pretexting to obtain phone records of board members, HP employees, and journalists.Investigators impersonated the individuals and contacted telecom providers pretending to be them, using publicly available personal data (like social security numbers or birth dates) to bypass identity checks.The phone companies, deceived by these false identities, gave out detailed phone logs.

Impact:-The scandal became public after media exposure and drew widespread criticism.
        U.S. Congressional hearings were held, and lawsuits were filed.HP’s Chairwoman, Patricia Dunn,resigned.
        Legal action was taken against the investigators and HP officials, including criminal charges related to identity theft and fraud.

Consequences for HP:- Severe damage to public trust and corporate image.
                      Fines and legal expenses.
                      Brought legal scrutiny to pretexting and led to changes in data privacy legislation.


2) Verizon Customer Support Breach(2017)
Verizon, a major U.S. telecom company, faced a serious data breach in mid-2017, compromising millions of customer records.An attacker posed as an internal Verizon employee or contractor from an outsourced support firm.Using phone calls and chat-based interactions, they convinced a legitimate employee to grant them access to Verizon's customer service support portal.
This portal had access to customer records, including names, phone numbers, account PINs, and more.Data from 6 million customers was eventually leaked and found stored on an unsecured Amazon Web Services (AWS) server.

Impact:-Exposure of millions of customer records.
        Public backlash about data handling and vendor security.
        The incident drew attention to weaknesses in third-party vendor practices and identity verification protocols.

Consequences for Verizon:- Embarrassment and reputational damage.
                           Verizon had to overhaul its security protocols and vendor access policies.
                           It spurred industry-wide concern about supply chain attacks and poor pretexting awareness among employees.


3) Twitter Bitcoin Scam(July 2020)
In July 2020, Twitter suffered one of the most high-profile cybersecurity breaches in history when attackers took control of prominent Twitter accounts.Attackers used pretexting to impersonate Twitter IT support staff.They contacted several Twitter employees via phone, claiming to be from the internal IT department.By building trust, they convinced employees to share their credentials for internal administrative tools.With admin access, attackers hijacked over 130 verified Twitter accounts, including those of Elon Musk, Barack Obama, Bill Gates, Apple, and others.The compromised accounts posted Bitcoin scam messages, promising to double cryptocurrency sent to a wallet address.

Impact:- Major reputation damage to Twitter.
         Stock prices fell temporarily.
         The FTC and FBI launched investigations.
         A 17-year-old Florida teenager and two others were arrested and charged with computer crimes and fraud.

Consequences for Twitter:- Twitter implemented temporary restrictions on posting for verified accounts.
                           They restructured internal access controls and strengthened internal employee training.
                           Twitter committed to overhauling access management and internal tools.

Impacts on Organizations:-
1)Reputational Damage: Loss of public trust (as in HP and Twitter).
2)Financial Losses: Fraudulent transactions, lawsuits, fines.
3)Legal Consequences: Violations of privacy laws (e.g., GDPR, HIPAA).
4)Operational Disruption: Internal audits, policy revisions, employee re-training.
5)Data Breach: Exposure of PII (Personally Identifiable Information), credentials, and business secrets.

Research Findings:-
Key Trends:
           Pretexting attacks are rising in sophistication and frequency, especially in sectors like finance, healthcare, and tech.
           Human factor remains the weakest link; even well-trained staff can fall victim if protocols are weak.
           Attackers use multi-channel attacks – combining emails, calls, and SMS to reinforce legitimacy.

Data from Verizon DBIR (2024):
                               Pretexting accounted for 27% of social engineering breaches.
                               90% of pretexting attacks targeted people in positions of authority (e.g., managers, executives).
                               Average cost per incident: $130,000 to $1 million, depending on data sensitivity.

PREVENTIVE MEASURES

Organizational Level:
                      Security Awareness Training:Regular sessions on social engineering tactics.Simulation drills and red-team assessments.
                      Strict Verification Protocols:Multi-factor authentication (MFA) for access requests.Callback verification before fulfilling sensitive requests.
                      Least Privilege Principle:Limit data access based on job roles.Segregation of duties to avoid single points of failure.
                      Incident Response Plan:A rapid response strategy to detect and handle social engineering attacks.
                      Internal Audits:Periodic checks on access logs and abnormal behaviors.

Employee-Level:
                Never share credentials over calls or emails—even if the person claims to be from IT or management.
                Verify the identity of anyone requesting sensitive information.
                Report suspicious interactions immediately.
                Be cautious with unsolicited requests that create urgency.


 Real-World Examples of Prevention:-
                                     Google and Facebook: Both companies lost over $100 million due to a pretexting-based email scam in 2013–2015. Post-incident, they strengthened                                                                 verification procedures and educated employees on advanced social engineering tactics.
                                     Banks and Financial Institutions: Many have adopted voice biometrics and transaction anomaly detection to prevent fraud stemming from impersonation.



3) Baiting
Baiting is a form of social engineering attack that lures victims into a trap by offering something enticing, such as free software, digital media, or physical goods, to manipulate them into compromising their system or revealing confidential information. The attack capitalizes on human curiosity or greed and typically involves the delivery of malware via digital downloads or infected physical media like USB drives.

Working of Baiting
1)The attacker creates a tempting lure — this could be a free music/video file, fake job offer, software, or an abandoned USB device labeled “Confidential” or “Payroll Info.”
2)The bait is delivered either digitally (malicious links or attachments) or physically (USB drives placed in public spaces like lobbies or parking lots).
3)Victims, driven by curiosity or benefit, plug in the USB drive or download the file.
4)Upon access, malware is executed, enabling:
                                             Unauthorized access to sensitive data
                                             Installation of ransomware/keyloggers
                                             System compromise or backdoor creation
5)The attacker gains access to credentials, private information, or network infrastructure.


Case Studies of  Baiting Attacks

1) The USB Drop Experiment by University of Illinois (2016)
Researchers from the University of Illinois Urbana-Champaign, in collaboration with Google, conducted a real-world experiment to measure how effective baiting attacks using USB drives could be.

Execution:
297 USB flash drives were scattered intentionally across the university campus in locations like:
                                                                                                 Parking lots
                                                                                                 Hallways
                                                                                                 Cafeterias
                                                                                                 Study lounges
The drives were labeled with various enticing or curiosity-piquing labels such as:
                                                                                  Final Exam Answers
                                                                                  Confidential Salary Info
                                                                                  Nudes
                                                                                  Photos
Inside each USB was a file that, when clicked, opened a survey that tracked how many people opened it. Some also contained a benign script to simulate malware execution (no actual harm was done).

Results:
        48% (almost half) of the dropped USB drives were picked up and plugged into university computers.
        Many users clicked the files, despite having cybersecurity awareness training.
        Only a few people reported the drive to university authorities or IT support.
        The majority ignored potential security consequences, acting out of curiosity or personal gain.

Impact & Significance:
                      Though it was a controlled experiment, the results highlighted serious real-world implications:
                      Employees/students often ignore basic cyber hygiene.
                      In real scenarios, malicious USBs could have delivered malware, stolen credentials, or allowed network infiltration.
                      The study showed that even well-educated individuals in a tech-savvy environment could fall victim to baiting.


2) Stuxnet – A Nation-State USB Baiting Attack (Iran, 2010)
Stuxnet was a highly sophisticated cyber-weapon discovered in 2010, believed to be a joint effort by the U.S. and Israeli intelligence. It was designed to sabotage Iran's nuclear program by targeting the Programmable Logic Controllers (PLCs) used in uranium enrichment.

Execution:
          The Natanz nuclear facility in Iran was air-gapped (not connected to the internet), making remote attacks impossible.
          Attackers used infected USB flash drives to deliver the Stuxnet worm.
          These USBs were likely intentionally planted where employees would find and use them—an example of classic baiting combined with espionage.
          Once plugged in, the malware automatically installed itself and silently spread through the internal network.
          Stuxnet specifically sought out Siemens Step7 software controlling centrifuges and issued commands to spin them at unsafe speeds, causing mechanical failure.

Impact:
       1,000 centrifuges (about 10%) of Iran's capability were destroyed.
       Delayed Iran’s nuclear enrichment efforts significantly.
       Caused confusion among Iranian engineers as the worm reported normal readings while sabotaging operations.
       Considered the first cyber weapon to cause physical destruction via malware.

Significance:
             Proved that baiting with USBs can be effective against high-security air-gapped systems.
             Highlighted how social engineering, combined with technical expertise, can breach even the most secure infrastructures.

Research Findings:-
                    Human curiosity is a consistent vulnerability, often outweighing cybersecurity awareness.
                    Baiting is more effective than phishing when physical media is used, especially in organizations without device-use policies.
                    Studies show that employees with basic security training still fall for baiting when the bait aligns with their interests (e.g., resume files for HR staff).

Preventive Measures:
To mitigate baiting attacks, organizations must adopt a multi-layered defense strategy:

Technical Controls:-
                    Endpoint Protection: Ensure systems have up-to-date antivirus and endpoint detection software.
                    Disable Autorun: Prevent automatic execution of removable media.
                    USB Port Control: Block or restrict USB usage using device control solutions.
                    Network Segmentation: Limit access to critical systems from endpoints.

Policy and Awareness:-
                      Security Training: Conduct regular awareness programs highlighting baiting and real examples.
                      Clear Policies: Implement strict media handling policies — no unauthorized devices allowed.
                      Incident Response Protocols: Train staff on how to report suspicious devices or activities.

Physical Security:-
                   Secure Premises: Monitor for suspicious items, particularly in public or high-traffic areas.
                   Surveillance & Audits: Use CCTV and conduct random checks for compliance.

Real-World Examples:
                    Government Agencies: Often targeted via baiting because of isolated networks.
                    Corporate Espionage: Cases where employees were baited with fake job offers via USB devices, leading to data leaks.



4) Tailgating(Piggybacking)
Tailgating, also known as "piggybacking," is a type of physical security breach in which an unauthorized person gains access to a restricted area by following an authorized individual without consent or proper credentials. It is a form of social engineering attack that exploits human behavior, particularly politeness and trust.Unlike cyber attacks that target digital systems, tailgating targets the physical security perimeter of an organization and can lead to theft, espionage, sabotage, or data compromise.

Working of Tailgating
1)The attacker monitors the premises to identify routines, access points, and employees.
2)The attacker walks closely behind an authorized individual entering a secure area.May carry props (e.g., fake ID, clipboard, uniform, boxes) to appear legitimate.
3)The authorized person either knowingly or unknowingly allows the attacker to enter (often by holding the door open as a courtesy).
4)Once inside, the attacker may install malicious devices, steal data or assets, or carry out sabotage or surveillance.

Case Studies of  Tailgating Attacks

1)Target Corporation Breach (2013)
Although primarily known as a cyberattack, deeper investigations reveal that physical security lapses—including tailgating-like activity at a third-party vendor’s site—played a role in the massive data breach.
Attack Execution:
                 The attackers targeted a third-party HVAC company that had remote access to Target’s network for billing and system maintenance.
                 Security experts suspect that attackers might have physically accessed systems at the vendor's office. Employees reported strange individuals seen around restricted                      zones during off-hours. Tailgating was not ruled out due to weak internal badge checks.
                 The attackers stole login credentials, installed malware on POS systems across 1,800 Target stores, and collected card data of millions of customers.

Impact:
       40 million debit/credit card records stolen.
       Additional 70 million customer records (emails, phone numbers, addresses) compromised.
       Estimated loss: Over $162 million (including lawsuits, fines, and settlements).
       CEO and CIO of Target resigned after the breach.

Key Tailgating Link:
                    Investigations found physical access control at the HVAC vendor’s office to be non-compliant with best practices—doors were often held open for others, and visitors                      weren’t required to badge in, allowing potential attackers to piggyback or tailgate.


2) Heathrow Airport Security Breach (2017)
A major UK airport—Heathrow—was compromised when a USB drive containing top-secret airport security data was found on a London street.
Attack Execution:
 A civilian found a USB stick on the street containing over 2 GB of unencrypted, classified documents. These included:
                                                                                                                      Locations of security cameras and tunnels.
                                                                                                                      The exact route the Queen takes during security checks.            
                                                                                                                      Timing of airport patrols and evacuation procedures.

 The investigation revealed that an unauthorized person may have gained access to sensitive security zones. It was suspected that the attacker tailgated into restricted staff-only areas  at the airport—particularly those used by cleaning or maintenance staff.
 Once inside, the attacker could have used unattended terminals or connected devices to transfer data onto the USB.

Impact:
        Major threat to national security.
        Heathrow Airport fined £120,000 by the UK’s Information Commissioner’s Office (ICO) for violating the Data Protection Act.
        Reputation damage; highlighted gross negligence in physical and digital security integration.

Key Tailgating Link: 
                     Heathrow staff were found to often permit unauthorized entry into secure locations under the assumption that people in uniforms were legitimate—classic tailgating                        behavior. Security doors lacked mantraps or anti-tailgating sensors.

Research Findings:-
Research studies in security management highlight the high frequency and low detection rate of tailgating incidents:

Ponemon Institute (2021 Report):
                                68% of companies reported at least one physical breach due to tailgating in the last year.
                                55% of those incidents involved employees holding doors for strangers without checking credentials.

SANS Institute:
               Many organizations focus heavily on cybersecurity but under-invest in physical access controls, creating vulnerabilities.

Research by HID Global:
                       70% of security professionals admitted that tailgating is “difficult to prevent without surveillance and awareness training.”

Impact on Organizations:-
1) Data Theft:Attackers may physically steal laptops, USB drives, or documents.
2)Espionage:Trade secrets or confidential plans may be copied or photographed.
3)Infrastructure Sabotage:Insertion of rogue devices like keyloggers, packet sniffers, or USB malware.
4)Regulatory Fines:Non-compliance with physical security standards (e.g., HIPAA, ISO 27001) may result in heavy penalties.
5)Reputation Damage:Loss of customer and stakeholder trust.

                        
Preventive Measures:-
1) Multi-Factor Access Controls:Install biometric systems, keycards, or PINs with anti-tailgating sensors.
                                Use mantraps or turnstiles that allow only one person at a time.

2) Security Awareness Training:Educate employees about tailgating risks and the importance of challenging unknown individuals.
                               Promote a "No badge, No entry" policy.

3) Surveillance & Monitoring:Deploy CCTV cameras, motion sensors, and real-time monitoring near access points.

4) Security Personnel:Position guards at sensitive entries during peak hours.Conduct random badge checks.
5) Visitor Protocols:Enforce strict visitor log-ins, badge issuance, and escorts for non-employees.
6) Penetration Testing & Red Team Exercises:Simulate tailgating attempts to test employee responses and system effectiveness.

Real-World Examples:
                    Google’s “Zero Trust” Campus Policy:
                                                        Every area is treated as untrusted—employees must reauthenticate when moving between zones.
                    Facebook’s Secure Access Points:
                                                    Facebook uses ID turnstiles, badge verification, and facial recognition cameras to mitigate tailgating.
                    IBM’s Training Initiative:
                                               Employees are shown re-enactments of tailgating attacks during onboarding.











                      

                         
