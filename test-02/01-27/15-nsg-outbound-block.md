# 🔐 Cybersecurity MCQ  

**Question Number 15**  

## 🌍 Scenario  
At **BlueWave Digital Systems**, the security team is reviewing cloud egress traffic policies.  
One engineer asks:  

> “Can we configure Azure Network Security Groups (NSGs) so that **all outbound traffic to the Internet** is blocked completely?”  

---

## 📝 Options (Team Voices)  

A. 🇩🇰 **Eks2 – The Curious Whisper**:  
“Yes, NSGs can be tightened to close every outbound path, even to the Internet — but only if the right deny rules are applied.”  

B. 🇪🇸 **Sofia Zaymera – The Calm Guardian**:  
“Not exactly… NSGs are more about inbound control; you’ll need a firewall to block outbound traffic fully.”  

C. 🇮🇹 **Isabella Konti – The Empathic Firewall**:  
“Well, Azure enforces certain mandatory rules, so it might *seem* like you can’t fully block outbound traffic.”  

D. 🇨🇳 **Maya Lin – The Rookie**:  
“I think outbound Internet traffic is always allowed by default, so NSGs can’t stop it directly.”  

---

## ✅ Correct Answer  
**Correct Option: A – Yes, NSGs can be configured to deny all outbound Internet traffic.**  

---

## 💬 Team Discussion (Explanations)  

🇵🇰 **I.K. – The Unseen Mentor**:  
“Like a fortress that not only closes its gates but bars every secret tunnel — the NSG can silence all outbound footsteps to the Internet.  
This silence is safety, a discipline that preserves integrity.”  

🇷🇺 **Elina Petrova – The Cloud Whiz**:  
“By default, NSGs allow outbound Internet traffic. But administrators can add explicit deny rules at subnet or NIC level to block all outbound communication. That’s why Option A is correct.”  

🇪🇸 **Inky Rihan – The Phantom**:  
“Options B and C confuse learners. While it’s true Azure Firewalls provide advanced egress control, NSGs already allow full outbound blocking. Option D is the rookie trap — assuming defaults cannot be changed.”  

🇩🇰 **Kasper Madsen – The Joyful Specialist**:  
“Think of NSGs like your parents during exam week: ‘No going out!’ And unless you sneak past them (which you can’t here), you’re staying inside.”  

🇮🇹 **Isabella Konti – The Empathic Firewall**:  
“Employees benefit when outbound traffic is restricted — less risk of data leaks or malicious software ‘phoning home’ to the Internet.”  

🇨🇳 **Maya Lin – The Rookie**:  
“I thought outbound was always open… but now I see, NSGs can deny it completely if we configure them that way.”  

🕶️ **ShadowNet – The Phantom Adversary** *(risk born from neglect)*:  
“When outbound gates are left open, I ride the traffic unseen, stealing data in whispers.  
But when NSGs close the exits, I am trapped, silenced before my schemes begin.”  

---

## 🌟 Lesson  
👉 **NSGs in Azure can be used to deny *all outbound Internet traffic*, protecting against data exfiltration and malicious connections.**  

---

✒️ **Closing Signature**  
✍️ Created & Curated by  
**Muhammad Naveed Ishaque (Eks2)**  
Content Creator | AI Writer | Narrative Simplifier | Cybersecurity Storyteller  

_With the inner voice of Eks2 — the whisper behind the work._  

🕊️ **Siraat Cyber Academy**  
*“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”*  
