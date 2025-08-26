# 🔐 Cybersecurity MCQ  

**Question Number 14**  

## 🌍 Scenario  
At **NordShield Technologies**, the IT security team is planning to strengthen its cloud network boundaries.  
One engineer suggests:  

> “Why don’t we configure Network Security Groups (NSGs) in Azure to block all inbound traffic from the Internet?  
Would that even be possible?”  

So, what’s the right answer?  

---

## 📝 Options (Team Voices)  

A. 🇩🇰 **Eks2 – The Curious Whisper**:  
“Yes… NSGs can be tuned like gates — just close them fully and deny every inbound request, even from the Internet.”  

B. 🇪🇸 **Sofia Zaymera – The Calm Guardian**:  
“Not exactly… NSGs only allow *filtering* but cannot completely block all inbound Internet traffic.”  

C. 🇮🇹 **Isabella Konti – The Empathic Firewall**:  
“Well… it depends. Some inbound traffic rules will always be enforced by Azure, so you can’t fully deny everything.”  

D. 🇨🇳 **Maya Lin – The Rookie**:  
“I think no… because inbound Internet traffic is controlled by Azure Firewall, not by NSGs directly.”  

---

## ✅ Correct Answer  
**Correct Option: A – Yes, NSGs can be configured to deny all inbound Internet traffic.**  

---

## 💬 Team Discussion (Explanations)  

🇵🇰 **I.K. – The Unseen Mentor**:  
“Like a fortress that closes every gate at dusk, the NSG can deny every step entering from the Internet.  
The silence of denial is also protection — a choice of strength, not weakness.”  

🇷🇺 **Elina Petrova – The Cloud Whiz**:  
“By default, NSGs deny inbound traffic unless an allow rule is set.  
Admins can configure explicit deny rules to ensure that *all Internet inbound traffic* is rejected.  
This is why Option A stands correct.”  

🇪🇸 **Inky Rihan – The Phantom**:  
“Options B and C confuse the learner — but that’s the trick.  
Azure does enforce platform rules, but NSGs absolutely can shut down inbound Internet traffic at the subnet or NIC level.  
And Option D? That’s a rookie trap — Azure Firewall is separate, but NSGs already provide inbound filtering.”  

🇩🇰 **Kasper Madsen – The Joyful Specialist**:  
“Think of NSGs like a bouncer outside the club.  
If the order is ‘let nobody in,’ then nobody’s getting in — no matter how loud they knock.”  

🇮🇹 **Isabella Konti – The Empathic Firewall**:  
“When IT communicates such rules clearly, employees feel safer — knowing their cloud boundary is not porous but protected.”  

🇨🇳 **Maya Lin – The Rookie**:  
“I thought only Azure Firewall could do that. Now I see: NSGs alone can already stop all inbound Internet traffic.”  

🕶️ **ShadowNet – The Phantom Adversary** *(risk born from neglect)*:  
“If the gate is left ajar, I enter unseen. But when NSGs lock the path completely, I am left wandering in the dark.”  

---

## 🌟 Lesson  
👉 **Network Security Groups can be configured to deny all inbound Internet traffic — acting as the first line of defense in Azure.**  

---

✒️ **Closing Signature**  
✍️ Created & Curated by  
**Muhammad Naveed Ishaque (Eks2)**  
Content Creator | AI Writer | Narrative Simplifier | Cybersecurity Storyteller  

_With the inner voice of Eks2 — the whisper behind the work._  

🕊️ **Siraat Cyber Academy**  
*“The Straight Path — Empowering minds with clarity, illuminating paths with purpose.”*  
