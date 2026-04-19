## ⚔️ **Attack Cards (Execute)**

### **1. Ping Command**
* **Category:** [General]
* **Rarity:** Starter (Common)
* **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**.
* **Upgrade Path:** v2.0 (9 Dmg) | v3.0 (12 Dmg)
* **CyberDex:** "A utility used to test the reachability of a host on an Internet Protocol (IP) network." [RFC 792]

### **2. DDoS Script**
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Network Class: Deal **16 Damage**.
* **Upgrade Path:** v2.0 (12/20 Dmg) | v3.0 (15/25 Dmg)
* **CyberDex:** "Distributed Denial of Service: An attack that prevents authorized use of networks by exhausting resources." [NIST SP 800-61]

### **3. Signature Match**
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Malware Class: Deal **16 Damage**. (Bypasses Trojan's Masquerade).
* **Upgrade Path:** v2.0 (10/20 Dmg) | v3.0 (12/24 Dmg)
* **CyberDex:** "A recognizable pattern of data or signals that indicates a specific threat." [NIST CSRC]

### **4. Boot Scan**
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal **5 Damage**. If Malware Class: Deal **25 Damage**.
* **Upgrade Path:** v2.0 (30 Dmg) | v3.0 (35 Dmg)
* **CyberDex:** "A scan that runs at system startup to detect rootkits and malware before the OS loads." [NIST SP 800-83]

### **5. Spam Filter**
* **Category:** [Specialized] (Target: Social/Junk)
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Deal **10 Damage**. Exhaust all Status/Junk cards in hand; deal **+3 Damage** for each card removed.
* **Upgrade Path:** v2.0 (12 Dmg, +5 per Junk)
* **CyberDex:** "Software that automatically detects and deletes unsolicited bulk email to prevent phishing." [NIST SP 800-45]

### **6. Exploit Kit**
* **Category:** [General] (Combo)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**. If Target is **Vulnerable** or **Stunned**: Deal **14 Damage** and **Draw 1 Card**.
* **Upgrade Path:** v2.0 (9/18 Dmg) | v3.0 (12/22 Dmg)
* **CyberDex:** "A toolkit used by attackers to deliver a malicious payload by exploiting vulnerabilities." [NIST CSRC]

---

## 🛡️ **Defense Cards (Harden)**

### **7. Basic Firewall**
* **Category:** [General]
* **Rarity:** Starter (Common)
* **Cost:** 1 RAM
* **Base Effect:** Gain **6 Shield**.
* **Upgrade Path:** v2.0 (9 Shield) | v3.0 (12 Shield)
* **CyberDex:** "A gateway that restricts data communication traffic to and from one of the connected networks." [NIST SP 800-41]

### **8. Patch Update**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain **4 Shield**. **Draw 1 card**.
* **Upgrade Path:** v2.0 (7 Shield) | v3.0 (10 Shield)
* **CyberDex:** "The systematic notification, identification, deployment, and verification of software code revisions." [NIST SP 800-40]

### **9. Multi-Factor Auth (MFA)**
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain **5 Shield**. If Social: **Negate all enemy actions** this turn.
* **Upgrade Path:** v2.0 (8 Shield) | v3.0 (11 Shield)
* **CyberDex:** "An authentication system that requires more than one distinct authentication factor for access." [NIST SP 800-63]

### **10. Data Encryption**
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Gain **10 Shield**. If Social Class: **Reflect** all damage back at the attacker.
* **Upgrade Path:** v2.0 (15 Shield) | v3.0 (20 Shield)
* **CyberDex:** "The process of transforming information using an algorithm to make it unreadable." [NIST SP 800-111]

### **11. Sandbox Environment**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain **8 Shield**. **Draw 1 Card**.
* **Upgrade Path:** v2.0 (11 Shield) | v3.0 (14 Shield)
* **CyberDex:** "A restricted environment that prevents potentially malicious software from accessing system resources." [NIST SP 800-53]

### **12. Air Gap**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 2 RAM
* **Base Effect:** Gain **15 Shield**. Gain **+1 RAM** next turn.
* **Upgrade Path:** Read-Only (No Upgrades)
* **CyberDex:** "Manual isolation. An interface between two systems at which they are not connected physically." [NIST CSRC]

---

## 🔧 **Utility Cards (Patch)**

### **13. WhoIs Lookup**
* **Category:** [Specialized] (Investigation)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** **Remove "Unattackable"** status + **Stun** the target.
* **Upgrade Path:** v2.0 (Draw 1 Card) | v3.0 (Draw 1 Card & +1 Energy)
* **CyberDex:** "A query protocol used for accessing databases that store the registered users of an Internet resource." [RFC 3912]

### **14. Awareness Training**
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 0 RAM
* **Base Effect:** **Gain 1 Energy**. If Social: **Remove "Unattackable"** and apply **Vulnerable** to all enemies.
* **Upgrade Path:** v2.0 (Draw 1 Card) | v3.0 (Draw 1 & +1 Energy)
* **CyberDex:** "Formal education provided to users to help them identify and prevent social engineering attacks." [NIST SP 800-50]

### **15. Backup Recovery**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** **Heal 10 HP**.
* **Upgrade Path:** v2.0 (Heal 15 HP)
* **CyberDex:** "The copy of files and programs made to facilitate recovery, if necessary." [NIST SP 800-34]

### **16. Decryption Key**
* **Category:** [Specialized] (Target: Crypto/Lock)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal **5 Damage**. **Remove all Lock effects** from cards in hand.
* **Upgrade Path:** v2.0 (10 Dmg, Remove Shield/Lock) | v3.0 (15 Dmg, Remove Shield/Lock)
* **CyberDex:** "A string of bits used by a cryptographic algorithm to transform encrypted data back into original data." [NIST SP 800-57]

### **17. Signature Update**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 3 RAM
* **Base Effect:** **Passive: All attacks deal +3 Damage** for the rest of the battle.
* **Upgrade Path:** Read-Only (No Upgrades)
* **CyberDex:** "The process of updating the database of known malware signatures." [NIST SP 800-83]
