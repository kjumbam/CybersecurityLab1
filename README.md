# CybersecurityLabs
Lab activity for Security+ preparation and cybersecurity skills development.

WHAT THIS PROJECT IS ABOUT

This project contains all the details and findings from a recent "security checkup" we did for Botium Toys. Botium Toys is a small fictional company in the U.S. that makes and sells toys. They have one main building that acts as their office, toy store, and storage warehouse.

However, Botium Toys' online store has become super popular, with customers all over the U.S. and even in other countries. Because of this, their IT (Information Technology) team is under a lot of pressure to keep everything running smoothly online, worldwide.

So, the IT manager decided to do an internal security checkup. She wanted to make sure the company stays compliant with rules and keeps running smoothly as it grows, without any big problems. She believes this checkup will help make their computer systems safer and find any potential risks or weak spots. She also wants to make sure they follow rules for taking online payments and doing business in places like the European Union (E.U.).

The main goal of this checkup was to give a clear picture of the risks (like security breaches or fines) the company might face because of its current security situation.

WHAT YOU'LL FIND HERE

This project includes:

•	Cybersecurity Basics: Simple explanations of different types of security measures and how they work to prevent, fix, detect, or stop problems.
•	Botium Toys Story: The background story of Botium Toys, their computer setup, and why they needed this security checkup.
•	Checkup Goals: What we aimed to achieve with this security review.
•	Current IT equipment: A list of all the computer-related equipment and systems the IT team manages.
•	Risk Report: What potential problems we found, how serious they are, and how they could affect the business.
•	Security Checklist: A list showing which security measures Botium Toys currently has in place and which ones are missing.
•	Rules Checklist: A look at how well Botium Toys is following important rules like those for handling credit cards (PCI DSS) and protecting E.U. customer data (GDPR).
•	Our Advice: Simple suggestions for how Botium Toys can make things safer and follow all the necessary rules.
 
HOW TO UNDERSTAND THIS PROJECT

To get started, just read through the documents in this repository. There's no computer code to run, as this project is all about the security analysis and findings.

What You Need:

You just need a program that can open PDF and Word documents.

What's Inside:

•	Control-categories.docx: Explains the different types of security controls (rules, tech, physical).
•	SCENARIO for Course 2 PORTFOLIO ACTIVITY.docx: The story of Botium Toys and why this security checkup was done.
•	Botium-Toys-Scope-goals-and-risk-assessment-report.docx: Details about what the checkup covered, its goals, what IT equipment Botium Toys has, and what risks were found.
•	Controls and compliance checklist exemplar (1).pdf: The completed checklist showing what security measures and rules Botium Toys follows and doesn't follow.
 
WHAT WE FOUND

Missing Security Steps:

Our checkup showed Botium Toys needs to improve in several key areas:

•	"Need-to-Know" Access: Right now, all employees can see customer data. This needs to be limited so only those who need to see it can, to reduce risks.
•	Disaster Plans: There are no plans for what to do if a major problem hits (like a power outage or data breach). This is crucial to keep the business running.
•	Strong Passwords: Employee passwords are too simple, making it easy for bad guys to guess them and get into secure information.
•	Separate Jobs: The company CEO currently handles day-to-day operations and payroll. This should be separated to prevent fraud and limit access to sensitive data.
•	Intrusion Detection System (IDS): They don't have a system that watches for and flags suspicious activity on their network, which could mean intruders go unnoticed.
•	Data Backups: There are no copies of important data, meaning if something gets lost or stolen, it could be gone for good and impact the business.
•	Data Scrambling (Encryption): They aren't scrambling sensitive information (like credit card numbers) to protect it. This is a big security gap.
•	Password Manager: There's no central system to help employees manage their passwords, which can lead to forgotten passwords and slower work.
•	Old Systems Care: While they do keep an eye on older computer systems, there's no regular schedule for checking them or clear steps for fixing problems. This puts these systems at risk.

Not Following All the Rules:

Botium Toys also needs to step up its game in following important rules:

•	Credit Card Rules (PCI DSS):

o	Not everyone who sees credit card info should.
o	Credit card info isn't encrypted (scrambled) and is too easily accessed by all employees.
o	They need stronger password rules.

•	E.U. Data Rules (GDPR):

o	E.U. customer data isn't kept private enough (again, due to no encryption).
o	They've listed their IT assets, but haven't classified them (like saying which data is super sensitive).

•	Security Trust (SOC):

o	They don't have clear rules about who can access what (like the "need-to-know" access and separate jobs mentioned earlier).
o	Sensitive personal info (PII/SPII) isn't kept private because it's not encrypted.
o	While data is available, access should only be given to those who absolutely need it for their job.

What They Are Doing Right:

It's not all bad! Botium Toys does have some good security in place:

•	Firewall: They have a working firewall that blocks bad internet traffic.
•	Antivirus: They have antivirus software installed and checked regularly by their IT team.
•	Physical Security: Their building has good locks, working security cameras (CCTV), and fire alarms/sprinklers.
•	Data Accuracy: Their data is generally correct and complete.
•	E.U. Breach Plan: They have a plan to tell E.U. customers within 72 hours if their data is exposed in a security breach.
•	Privacy Rules: They've created and are enforcing privacy rules for their IT team and other employees.
 
OUR ADVICE (WHAT NEEDS TO BE DONE)

To make Botium Toys much safer and ensure they follow all the rules, they should:

•	Put Key Security Measures In Place: They urgently need to start using "need-to-know" access, create disaster plans, set up stronger password rules, separate job duties, install an Intrusion Detection System (IDS), encrypt all sensitive data, and get a central password management system.
•	Manage Old Systems Better: Create a regular schedule for checking and maintaining older computer systems, and have clear steps for what to do if problems pop up.
•	Organize Data: Properly categorize all their IT assets to help figure out what other security steps are needed to protect sensitive information.
•	Fix Rule-Following Issues: They must work on fixing all the problems we found with PCI DSS, GDPR, and SOC compliance, especially regarding who can access what data, encrypting data, and securely handling credit card and customer personal information.
 
HOW YOU CAN HELP

This project is a report, so there's no code to contribute to directly. However, if you have ideas on how to make this report clearer, more accurate, or better presented, we'd love to hear them!
 
LICENSE

This project is for learning about cybersecurity audits. It doesn't have a special open-source license.
<img width="468" height="645" alt="image" src="https://github.com/user-attachments/assets/c1d869b3-f61d-46b5-a88c-354c177eebdb" />
