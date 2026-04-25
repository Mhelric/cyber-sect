# 👾 **CyberSect: Master Card Library**

## 🔑 **Class Legend**
* 🦠 **Malware:** Weak vs **Antivirus** (High Damage).
* 🌐 **Network:** Weak vs **Firewall** (Shields/Filtering).
* 🎭 **Social:** Weak vs **Scan/Utility** (Analysis).
* 🔒 **Crypto:** Weak vs **Decryption** (Shield Pierce).

---

## ⚔️ **Attack Cards (Execute)**

### **1. Ping Command**
* **Category:** [General] | **Rarity:** Starter | **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**.
* **Upgrade Path:** v2.0 (9 Dmg) | v3.0 (12 Dmg)

### **2. DDoS Script**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Network: Deal **16 Damage**.
* **Upgrade Path:** v2.0 (12/20 Dmg) | v3.0 (15/25 Dmg)

### **3. Signature Match**
* **Category:** [Specialized] (Malware) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Malware: Deal **16 Damage**. (Bypasses **Invulnerable**).
* **Upgrade Path:** v2.0 (10/20 Dmg) | v3.0 (12/24 Dmg)

### **4. Boot Scan**
* **Category:** [Specialized] (Malware) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **5 Damage**. If Malware: Deal **25 Damage**.
* **Upgrade Path:** v2.0 (30 Dmg) | v3.0 (35 Dmg)

### **5. Spam Filter**
* **Category:** [Specialized] (Social/Junk) | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** Deal **10 Damage**. Exhaust all Status/Junk cards in hand; deal **+3 Damage** each.
* **Upgrade Path:** v2.0 (12 Dmg, +5 per Junk)

### **6. Exploit Kit**
* **Category:** [General] (Combo) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**. If Target is **Vulnerable** or **Stunned**: Deal **14 Damage** and **Draw 1 Card**.
* **Upgrade Path:** v2.0 (9/18 Dmg) | v3.0 (12/22 Dmg)

### **7. Flood Gate**
* **Category:** [Specialized] (Network) | **Rarity:** Rare | **Cost:** 3 RAM
* **Base Effect:** Deal **4 Damage** to **ALL**. If Network: Deal **12 Damage to ALL**.
* **Upgrade Path:** Read-Only (No Upgrades)

### **8. Traffic Throttling**
* **Category:** [General] (Shield-Scaling) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal damage equal to current **Shield amount**.
* **Upgrade Path:** v2.0 (Shield + 5) | v3.0 (Shield + 10)

### **9. Packet Filter**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**. If Network: Deal **12 Damage** and **Draw 1 Card**.
* **Upgrade Path:** v2.0 (9/15 Dmg) | v3.0 (12/18 Dmg)

### **10. IP Ban**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 3 RAM
* **Base Effect:** Deal **12 Damage**. If Network: Deal **30 Damage** and **Exhaust**.
* **Upgrade Path:** v2.0 (40 Dmg to Network) | v3.0 (50 Dmg to Network)

### **25. Heuristic Strike**
* **Category:** [Specialized] (Malware/Crypto) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal 10 Damage. If **Malware/Crypto**: Deal **20 Damage**.
* **Upgrade Path:** v2.0 (14/24 Dmg) | v3.0 (18/30 Dmg)
* **CyberDex:** "Analyzing code for suspicious properties (heuristics) rather than exact signature matches." [NIST SP 800-83]

### **26. Quarantine**
* **Category:** [General] (Containment) | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** Deal **10 Damage**. **Stun** target for 1 turn. **Exhaust**.
* **Special:** Triggers **+15 Bonus Damage** (Buffer Overflow) if used on Ransomware during its "Sale" phase.
* **Upgrade Path:** v2.0 (Cost: 0 RAM)
* **CyberDex:** "Isolating files to prevent the spread of malicious software." [NIST SP 800-61]

### **35. SQL Injection**
* **Category:** [General] (Bypass) | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Deal **15 Damage**. Stun enemy.
* **Upgrade Path:** v2.0 (17 Dmg) | v3.0 (20 Dmg)
* **CyberDex:** "Exploiting backend vulnerabilities to bypass security layers and access data directly." [MITRE T1190]

---

## 🛡️ **Defense Cards (Harden)**

### **11. Basic Firewall**
* **Category:** [General] | **Rarity:** Starter | **Cost:** 1 RAM
* **Base Effect:** Gain **6 Shield**.
* **Upgrade Path:** v2.0 (9 Shield) | v3.0 (12 Shield)

### **12. Patch Update**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **4 Shield**. **Draw 1 card**.
* **Upgrade Path:** v2.0 (7 Shield) | v3.0 (10 Shield)

### **13. Multi-Factor Auth (MFA)**
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **5 Shield**. If Social: **Negate all enemy actions** this turn.
* **Upgrade Path:** v2.0 (8 Shield) | v3.0 (11 Shield)

### **14. Data Encryption**
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Gain **10 Shield**. If Social: **Reflect** all damage back at attacker.
* **Upgrade Path:** v2.0 (15 Shield) | v3.0 (20 Shield)

### **15. Sandbox Environment**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **8 Shield**. **Draw 1 Card**.
* **Upgrade Path:** v2.0 (11 Shield) | v3.0 (14 Shield)

### **16. Air Gap**
* **Category:** [General] | **Rarity:** Rare | **Cost:** 2 RAM
* **Base Effect:** Gain **15 Shield**. Gain **+1 RAM** next turn.
* **Upgrade Path:** Read-Only (No Upgrades)

### **17. Access Control List (ACL)**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Gain **12 Shield**.
* **Upgrade Path:** v2.0 (18 Shield)

### **18. Sinkhole**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Deal **10 Damage**. If attacked next turn: **Reflect 50% Damage**.
* **Upgrade Path:** v2.0 (100% Reflection)

### **19. VPN Tunnel**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **8 Shield**.
* **Upgrade Path:** v2.0 (11 Shield) | v3.0 (14 Shield)

### **20. Geo-Blocking**
* **Category:** [Specialized] (Network) | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** Gain **5 Shield**. If Network: **Reflect 50% Damage**.
* **Upgrade Path:** v2.0 (8 Shield, Reflect 100%)

### **22. Honeypot** *(Note: Shares ID with Awareness Training)*
* **Category:** [General] (Decoy) | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Gain **10 Shield**. **Draw 1 Card**.
* **Upgrade Path:** v2.0 (14 Shield Draw 2)
* **CyberDex:** "A decoy system designed to attract and analyze potential intruders." [NIST SP 800-83]

### **30. Code Signing**
* **Category:** [Specialized] (Anti-Tamper) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Gain **12 Shield**. Apply **"Integrity Lock"** to the player for **2 turns**.
* **Special:** While active, cards cannot be **Locked or Discarded** by enemy effects.
* **Upgrade Path:** v2.0 (15 Shield) | v3.0 (18 Shield)
* **CyberDex:** "Digitally signing code to confirm the author and guarantee the integrity of software." [NIST CSRC]

---

## 🔧 **Utility Cards (Patch)**

### **21. WhoIs Lookup**
* **Category:** [Investigation] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** **Remove "Invulnerable"** status + **Stun** the target.
* **Upgrade Path:** v2.0 (Draw 1 Card) | v3.0 (Draw 1 & +1 Energy)

### **22. Awareness Training** *(Note: Shares ID with Honeypot)*
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 0 RAM
* **Base Effect:** **Gain 1 Energy**. If Social: **Remove "Invulnerable"** and apply **Vulnerable** to all.
* **Upgrade Path:** v2.0 (Draw 1 Card) | v3.0 (Draw 1 & +1 Energy)

### **23. Backup Recovery**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** **Heal 10 HP**.
* **Upgrade Path:** v2.0 (Heal 15 HP)

### **24. Decryption Key**
* **Category:** [Specialized] (Crypto) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal **5 Damage**. **Remove all Lock effects** from cards in hand.
* **Upgrade Path:** v2.0 (10 Dmg, Remove Shield/Lock) | v3.0 (15 Dmg, Remove Shield/Lock)

### **25. Signature Update** *(Note: Shares ID with Heuristic Strike)*
* **Category:** [General] | **Rarity:** Rare | **Cost:** 3 RAM
* **Base Effect:** **Passive: All attacks deal +3 Damage** for the rest of battle.
* **Upgrade Path:** Read-Only (No Upgrades)

### **26. Packet Sniffer** *(Note: Shares ID with Quarantine)*
* **Category:** [Crowd Control] | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** **Stun ALL targets**.
* **Upgrade Path:** v2.0 (Stun ALL & Draw 1) | v3.0 (Stun ALL & Apply 1 Weakness)

### **27. Force Quit**
* **Category:** [General] | **Rarity:** Starter | **Cost:** 0 RAM
* **Base Effect:** **Gain 1 RAM**. Lose **3 HP**.
* **Upgrade Path:** v2.0 (Lose 2 HP) | v3.0 (Gain 2 RAM, Lose 3 HP)

### **28. System Restore Point**
* **Category:** [General] | **Rarity:** Rare | **Cost:** 3 RAM
* **Base Effect:** **Heal 30 HP**. **Exhaust**.
* **Upgrade Path:** Read-Only (No Upgrades)

### **33. Threat Intelligence**
* **Category:** [General] (Investigation) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Put vulnerable to enemy **Gain 1 RAM**.
* **Upgrade Path:** v2.0 (Gain 2 RAM) | v3.0 (Cost 0 ram)
* **CyberDex:** "Analyzing threat information to provide context for defense decision-making." [NIST SP 800-150]

### **34. Sample Submission**
* **Category:** [Specialized] (Malware/Crypto) | **Rarity:** Uncommon | **Cost:** 0 RAM
* **Base Effect:** Deal 5 Damage. If **Malware/Crypto**: **Gain 2 RAM**.
* **Upgrade Path:** v2.0 (Gain 3 RAM)
* **CyberDex:** "Sending suspicious files to an authority for automated behavior analysis." [CISA Malware Analysis]

### **43. Privilege Escalation**
* **Category:** [General] (Override) | **Rarity:** Rare | **Cost:** 0 RAM
* **Base Effect:** Lose **10 HP**. **Gain 5 RAM**.
* **Upgrade Path:** Read-Only (No Upgrades)
* **CyberDex:** "Taking advantage of design flaws to gain elevated access to system resources." [MITRE T1068]
