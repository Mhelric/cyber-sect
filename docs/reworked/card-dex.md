# 👾 **CyberSect: Master Card Library**

## 🔑 **Class Legend**
🦠 **Malware:** Weak vs **Antivirus** (High Damage).  
🌐 **Network:** Weak vs **Firewall** (Shields/Filtering).  
🎭 **Social:** Weak vs **Scan/Utility** (Analysis).  
🔒 **Crypto:** Weak vs **Decryption** (Shield Pierce).  

---

## ⚔️ **Attack Cards (Execute)**

### **1. Ping Command**
* **Category:** [General] | **Rarity:** Starter (Common) | **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**.
* **Upgrade Path:** v2.0 (9 Dmg) | v3.0 (12 Dmg)
* **CyberDex:** "A utility used to test the reachability of a host on an Internet Protocol (IP) network." [RFC 792]

### **2. DDoS Script**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Network Class: Deal **16 Damage**.
* **Upgrade Path:** v2.0 (12/20 Dmg) | v3.0 (15/25 Dmg)
* **CyberDex:** "An attack that prevents authorized use of networks by exhausting resources." [NIST SP 800-61]

### **3. Signature Match**
* **Category:** [Specialized] (Malware) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Malware Class: Deal **16 Damage**. (Bypasses Invulnerable).
* **Upgrade Path:** v2.0 (10/20 Dmg) | v3.0 (12/24 Dmg)
* **CyberDex:** "A recognizable pattern of data or signals that indicates a specific threat." [NIST CSRC]

### **4. Boot Scan**
* **Category:** [Specialized] (Malware) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal **5 Damage**. If Malware Class: Deal **25 Damage**.
* **Upgrade Path:** v2.0 (30 Dmg) | v3.0 (35 Dmg)
* **CyberDex:** "A scan that runs at startup to detect malware before the OS loads." [NIST SP 800-83]

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
* **Base Effect:** Deal **4 Damage** to **ALL**. If Network Class: Deal **12 Damage to ALL**.
* **Upgrade Path:** Read-Only

### **8. Traffic Throttling**
* **Category:** [General] (Shield-Scaling) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Deal damage equal to current **Shield amount**.
* **Upgrade Path:** v2.0 (Shield + 5) | v3.0 (Shield + 10)

### **9. Packet Filter**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**. If Network Class: Deal **12 Damage** and **Draw 1 Card**.
* **Upgrade Path:** v2.0 (9/15 Dmg) | v3.0 (12/18 Dmg)

### **10. IP Ban**
* **Category:** [Specialized] (Network) | **Rarity:** Common | **Cost:** 3 RAM
* **Base Effect:** Deal **12 Damage**. If Network Class: Deal **30 Damage** and **Exhaust**.
* **Upgrade Path:** v2.0 (40 Dmg to Network) | v3.0 (50 Dmg to Network)

---

## 🛡️ **Defense Cards (Harden)**

### **11. Basic Firewall**
* **Category:** [General] | **Rarity:** Starter (Common) | **Cost:** 1 RAM
* **Base Effect:** Gain **6 Shield**.
* **Upgrade Path:** v2.0 (9 Shield) | v3.0 (12 Shield)

### **12. Patch Update**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **4 Shield**. **Draw 1 card**.
* **Upgrade Path:** v2.0 (7 Shield) | v3.0 (10 Shield)

### **13. Multi-Factor Auth (MFA)**
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **5 Shield**. If Social: **Negate all enemy actions** this turn.

### **14. Data Encryption**
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** Gain **10 Shield**. If Social: **Reflect** all damage back at attacker.

### **15. Sandbox Environment**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **8 Shield**. **Draw 1 Card**.

### **16. Air Gap**
* **Category:** [General] | **Rarity:** Rare | **Cost:** 2 RAM
* **Base Effect:** Gain **15 Shield**. Gain **+1 RAM** next turn.

### **17. Access Control List (ACL)**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Gain **12 Shield**.
* **Upgrade Path:** v2.0 (18 Shield)

### **18. Sinkhole**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 2 RAM
* **Base Effect:** Deal **10 Damage**. If attacked next turn: **Reflect 100% Damage**.

### **19. VPN Tunnel**
* **Category:** [General] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Gain **8 Shield**. **Retain your hand** for next turn.

### **20. Geo-Blocking**
* **Category:** [Specialized] (Network) | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** Gain **5 Shield**. If Network: **Reflect 50% Damage**.

---

## 🔧 **Utility Cards (Patch)**

### **21. WhoIs Lookup**
* **Category:** [Investigation] | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** **Remove "Invulnerable"** status + **Stun** the target.

### **22. Awareness Training**
* **Category:** [Specialized] (Social) | **Rarity:** Common | **Cost:** 0 RAM
* **Base Effect:** **Gain 1 Energy**. If Social: **Remove "Invulnerable"** and apply **Vulnerable** to all.

### **23. Backup Recovery**
* **Category:** [General] | **Rarity:** Uncommon | **Cost:** 1 RAM
* **Base Effect:** **Heal 10 HP**.

### **24. Decryption Key**
* **Category:** [Specialized] (Crypto) | **Rarity:** Common | **Cost:** 1 RAM
* **Base Effect:** Deal **5 Damage**. **Remove all Lock effects** from cards in hand.

### **25. Signature Update**
* **Category:** [General] | **Rarity:** Rare | **Cost:** 3 RAM
* **Base Effect:** **Passive: All attacks deal +3 Damage** for the rest of battle.

### **26. Packet Sniffer**
* **Category:** [Crowd Control] | **Rarity:** Common | **Cost:** 2 RAM
* **Base Effect:** **Stun ALL targets**.

### **27. Force Quit**
* **Category:** [General] | **Rarity:** Starter | **Cost:** 0 RAM
* **Base Effect:** **Gain 1 RAM**. Lose **3 HP**.

### **28. System Restore Point**
* **Category:** [General] | **Rarity:** Rare | **Cost:** 3 RAM
* **Base Effect:** **Heal 30 HP**. **Exhaust**.
