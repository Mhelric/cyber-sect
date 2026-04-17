# 👾 **CyberSect: Threat Database**

## 🔑 **Class Legend**

🦠 **Malware:** Weak vs **Antivirus** (High Damage).

🌐 **Network:** Weak vs **Firewall** (Shields/Filtering).

🎭 **Social:** Weak vs **Scan/Utility** (Analysis).

🔒 **Crypto:** Weak vs **Decryption** (Shield Pierce).


## 📂 **Chapter 1: The Perimeter (Infiltration)**

**Theme:** Basic scripts and nuisances.

---

### **1. Script Kiddie**

* **Class:** 🌐 **Network**
* **Role:** Basic Attacker
* **HP:** 25 | **Dmg:** 5
* **Behavior:** **Ping Flood.** Deals low, consistent damage every turn.
* **Mitigation Cards (Rookie Suite):**
    * **Basic Firewall:** Blocks the 5 Dmg entirely with 6 Shield.
    * **Patch Update:** Mitigates damage while cycling the deck.
    * **DDoS Script:** Deals 16 Specialized Damage to finish quickly.
* **📝 CyberDex:** "An unskilled attacker who uses existing computer scripts or code to hack into computers, lacking the expertise to write their own." [Source: NIST SP 800-12 Rev 1]

---

### **2. Adware**

* **Class:** 🌐 **Network**
* **Role:** Disrupter
* **HP:** 32 | **Dmg:** 0
* **Behavior:** **Popup Spam.** Shuffles "Pop-Up Window" cards into your draw pile. 
    * **Junk Card:** Pop-Up Window (Cost: 1 RAM). Effect: Deals 2 Damage to player when played to remove from hand.
* **Mitigation Cards (Rookie Suite):**
    * **Spam Filter:** Exhausts all Pop-Ups in hand and converts them into bonus damage.
    * **Force Quit:** Provides the RAM needed to manually clear Pop-Ups if the hand is clogged.
* **📝 CyberDex:** "Software that automatically displays or downloads advertising material. It clutters resources until manually removed." [Source: CISA Security Tip ST04-016]

---

### **3. Trojan**

* **Class:** 🦠 **Malware**
* **Role:** Time Bomb
* **HP:** 50 | **Dmg:** 0 (Passive) / 20 (Active)
* **Behavior:** **The Masquerade.** Unattackable by standard cards for 3 turns. On Turn 3, it deals 20 Damage and shuffles 1x **Corrupted File** into your deck.
    * **Junk Card:** Corrupted File (Deals 2 damage when played/discarded).
* **Mitigation Cards (Rookie Suite):**
    * **Signature Match:** The only card capable of damaging the Trojan while it is Masquerading.
    * **WhoIs Lookup:** Removes the "Unattackable" status and applies Weakness to the payload.
    * **Spam Filter:** Cleans up the Corrupted Files left behind after the payload.
* **📝 CyberDex:** "A computer program that appears to have a useful function, but also has a hidden and potentially malicious function." [Source: NIST CSRC Glossary]

---

### **👑 BOSS: The Zero-Day**

* **Class:** 🦠 **Malware**
* **Role:** Chapter 1 Boss
* **HP:** 125 | **Stealth Dmg:** 10 per turn (Accumulated)
* **Phase 1: Unknown Process (Turns 1-3)**
    * **Behavior:** **False Update.** Seems to heal the player for +10 HP each turn.
    * **Deception:** This is a **Buffer Overflow**. The added HP is actually stored damage that hits all at once on Turn 3.
    * **Restriction:** Unattackable. You cannot damage the boss until the patch is deployed.
* **Phase 2: Exploit Revealed (Turn 3 Start)**
    * **The Event:** System "Crashes." All False HP is removed, and accumulated damage is dealt.
    * **The Opening:** Boss identity is revealed. **Signature Match** is now enabled for massive damage.
* **Mitigation Cards (Rookie Suite):**
    * **Basic Firewall:** Must be played during Phase 1 to "absorb" the hidden damage accumulation.
    * **Backup Recovery:** Crucial for recovering lost Integrity (HP) immediately after the Turn 3 Crash.
    * **Patch Update:** Builds shields while searching for the Signature Match finishers.
* **📝 CyberDex:** "An attack that targets a previously unknown vulnerability... meaning developers have had zero days to fix it." [Source: NIST SP 800-53]

---

## 📂 **Chapter 2: The Human Layer (Social Engineering)**

**Theme:** Deception, surveillance, and psychological manipulation.

---

### **1. Phishing Link**

* **Class:** 🎭 **Social**
* **Role:** The Decoy
* **HP:** 25 | **Counter:** 25 Dmg
* **Behavior:** **The Masquerade.** Starts as **"Unattackable"**. Standard attacks trigger **25 Counter Damage**. Shuffles **Malicious Link** junk cards into your deck every turn.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes "Unattackable" status.
    * **Spam Filter:** Exhausts **Malicious Link** cards from hand.
    * **Awareness Training:** Instantly removes all Phishing Links and grants +1 Energy.
* **📝 CyberDex:** "A digital attack that attempts to trick victims into giving up sensitive information by masquerading as a reputable entity." [Source: CISA]

---

### **2. The Keylogger**

* **Class:** 🎭 **Social**
* **Role:** The Silent Observer
* **HP:** 65 | **Dmg:** 2 Per Card Played
* **Behavior:** **Surveillance.** Passively monitors the system. The player takes **2 Damage** immediately for every card played while the Keylogger is active.
* **Mitigation Cards:**
    * **MFA:** Negates all surveillance damage on the present turn.
    * **Sandbox Environment:** Provides Shield to soak up damage from playing cards.
    * **Data Encryption:** Reflects the 2 damage per card back at the Keylogger.
* **📝 CyberDex:** "Software used to record the keystrokes of a user, often used to steal passwords and other sensitive data." [Source: NIST CSRC]

---

### **3. The Pretexter**

* **Class:** 🎭 **Social**
* **Role:** The Storyteller
* **HP:** 40 | **Heal:** 10 HP per turn to all characters on screen.
* **Behavior:** **The Trusted Source.** Starts as **"Unattackable"**. Heals all characters for 10 HP every turn. Steals **1 Max RAM** every turn if left as the last enemy while unrevealed.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes "Unattackable" status and **Stuns** the target.
    * **MFA:** Negates healing and RAM theft actions for the turn.
    * **Awareness Training:** Reveals all Social enemies and applies **Vulnerability**.
* **📝 CyberDex:** "The act of creating and using an invented scenario to engage a targeted victim to divulge information." [Source: NIST SP 800-61]

---

### **👑 BOSS: The Whaling Attack**

* **Class:** 🎭 **Social**
* **Role:** Chapter 2 Boss (The Executive Impersonator)
* **HP:** 120 | **Dmg:** 10
* **Behavior:** **High-Level Compromise.** Starts as **"Unattackable"**. Increases the cost of the highest-RAM card in hand by **+2 RAM** (capped at **5 RAM**) each turn. Deals **25 Massive Damage** after Turn 4.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes "Unattackable" status and **Stuns** the Boss.
    * **MFA:** Negates the Lockout effect and the 25 Damage strike for the turn.
    * **Decryption Key:** Resets all card costs in hand back to their original values.
    * **Awareness Training:** Removes "Unattackable" status and applies **Vulnerability**.
* **📝 CyberDex:** "A specific form of phishing that targets high-profile employees, such as CEOs and CFOs, to steal sensitive information or money." [Source: FBI IC3]
