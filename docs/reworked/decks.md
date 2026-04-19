## **Rookie Suite (Chapter 1 Deck)**
**Theme:** Basic Tools. Reliable, low complexity.  
**Deck Size:** 20 Cards (10 Unique Types × 2 Copies Each)

---

### **Attack Cards (Execute)**

**1. Ping Command**
* **Type:** Attack
* **Category:** [General]
* **Rarity:** Starter (Common) — *Upgrade: 3 Copies*
* **Cost:** 1 RAM
* **Base Effect:** Deal **6 Damage**.
* **Upgrade Path:**
    * **v2.0:** Deal 9 Damage.
    * **v3.0:** Deal 12 Damage.
* **CyberDex:** "A utility used to test the reachability of a host on an Internet Protocol (IP) network." [RFC 792]

**2. DDoS Script**
* **Type:** Attack
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Common — *Upgrade: 3 Copies*
* **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Network Class: Deal **16 Damage**.
* **Upgrade Path:**
    * **v2.0:** Deal 12 Damage (Bonus: 20).
    * **v3.0:** Deal 15 Damage (Bonus: 25).
* **CyberDex:** "An attack that prevents authorized use of networks by exhausting resources." [NIST SP 800-61]

**3. Signature Match**
* **Type:** Attack
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common — *Upgrade: 3 Copies*
* **Cost:** 2 RAM
* **Base Effect:** Deal **8 Damage**. If Malware Class: Deal **16 Damage**. 
* **Note:** The only card that bypasses the Trojan's *Masquerade*.
* **Upgrade Path:**
    * **v2.0:** Deal 10 Damage (Bonus: 20).
    * **v3.0:** Deal 12 Damage (Bonus: 24).
* **CyberDex:** "A recognizable pattern of data or signals that indicates a specific threat." [NIST CSRC]

**4. Boot Scan**
* **Type:** Attack
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common — *Upgrade: 3 Copies*
* **Cost:** 2 RAM
* **Base Effect:** Deal **5 Damage**. If Malware Class: Deal **25 Damage**.
* **Upgrade Path:**
    * **v2.0:** Deal 30 Damage.
    * **v3.0:** Deal 35 Damage.
* **CyberDex:** "A scan that runs at system startup to detect rootkits and malware before the OS loads." [NIST SP 800-83]

**5. Spam Filter**
* **Type:** Attack
* **Category:** [Specialized] (Target: Social/Junk)
* **Rarity:** Uncommon — *Upgrade: 2 Copies*
* **Cost:** 1 RAM
* **Base Effect:** Deal **10 Damage**. Exhaust all Status/Junk cards in hand; deal **+3 Damage** for each card removed.
* **Upgrade Path:**
    * **v2.0:** Deal 12 Damage (+5 per Junk card).
* **CyberDex:** "Software that automatically detects and deletes unsolicited bulk email to prevent phishing." [NIST SP 800-45]

---

### **Defense Cards (Harden)**

**6. Basic Firewall**
* **Type:** Defense
* **Category:** [General]
* **Rarity:** Starter (Common) — *Upgrade: 3 Copies*
* **Cost:** 1 RAM
* **Base Effect:** Gain **6 Shield**.
* **Upgrade Path:**
    * **v2.0:** Gain 9 Shield.
    * **v3.0:** Gain 12 Shield.
* **CyberDex:** "A gateway that restricts data communication traffic to and from connected networks." [NIST SP 800-41]

**7. Patch Update**
* **Type:** Defense
* **Category:** [General]
* **Rarity:** Common — *Upgrade: 3 Copies*
* **Cost:** 1 RAM
* **Base Effect:** Gain **4 Shield**. **Draw 1 card**.
* **Upgrade Path:**
    * **v2.0:** Gain 7 Shield. Draw 1.
    * **v3.0:** Gain 10 Shield. Draw 1.
* **CyberDex:** "The systematic notification, identification, deployment, and verification of software code revisions." [NIST SP 800-40]

**8. Air Gap**
* **Type:** Defense
* **Category:** [General]
* **Rarity:** Rare — *Upgrade: Read-Only*
* **Cost:** 2 RAM
* **Base Effect:** Gain **15 Shield**. Gain **+1 RAM** next turn.
* **CyberDex:** "Manual isolation. An interface between two systems at which they are not connected physically." [NIST CSRC]

---

### **Utility Cards (Patch)**

**9. WhoIs Lookup**
* **Type:** Utility
* **Category:** [Specialized] (Investigation)
* **Rarity:** Common — *Upgrade: 3 Copies*
* **Cost:** 1 RAM
* **Base Effect:** **Remove "Unattackable"** status from target and apply **Vulnerable**.
* **Upgrade Path:**
    * **v2.0:** Apply 2 Weakness.
    * **v3.0:** Apply 2 Weakness & Draw 1.
* **CyberDex:** "A query protocol used for accessing databases that store the registered users of an Internet resource." [RFC 3912]

**10. Backup Recovery**
* **Type:** Utility
* **Category:** [General]
* **Rarity:** Uncommon — *Upgrade: 2 Copies*
* **Cost:** 1 RAM
* **Base Effect:** **Heal 10 HP**.
* **Upgrade Path:**
    * **v2.0:** Heal 15 HP.
* **CyberDex:** "The copy of files and programs made to facilitate recovery, if necessary." [NIST SP 800-34]

---

### **Summary Table for Simulation**

| Card Name | Qty in Deck | Card Type | Rarity | Upgrade Rule |
| :--- | :--- | :--- | :--- | :--- |
| **Ping Command** | 2 | Attack | Common | 3 Copies |
| **DDoS Script** | 2 | Attack | Common | 3 Copies |
| **Signature Match** | 2 | Attack | Common | 3 Copies |
| **Boot Scan** | 2 | Attack | Common | 3 Copies |
| **Spam Filter** | 2 | Attack | Uncommon | 2 Copies |
| **Basic Firewall** | 2 | Defense | Common | 3 Copies |
| **Patch Update** | 2 | Defense | Common | 3 Copies |
| **Air Gap** | 2 | Defense | Rare | No Upgrade |
| **WhoIs Lookup** | 2 | Utility | Common | 3 Copies |
| **Backup Recovery**| 2 | Utility | Uncommon | 2 Copies |

How does this finalized Chapter 1 Rookie Suite look to you? Ready to move to the Chapter 2 "Verification Suite" rewrite?
