# 👾 **CyberSect: Threat Database**

## 🔑 **Class Legend**

🦠 **Malware:** Weak vs **Antivirus** (High Damage).

🌐 **Network:** Weak vs **Firewall** (Shields/Filtering).

🎭 **Social:** Weak vs **Scan/Utility** (Analysis).

🔒 **Crypto:** Weak vs **Decryption** (Shield Pierce).

---

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
* **Behavior:** **The Masquerade.** **Invulnerable** to standard cards. On Turn 4, it deals 20 Damage to the player and on itself then shuffles 1x **Corrupted File** into your deck.
    * **Junk Card:** Corrupted File (Deals 2 damage when played/discarded).
* **Mitigation Cards (Rookie Suite):**
    * **Signature Match:** The only card capable of damaging the Trojan while it is **Invulnerable**.
    * **WhoIs Lookup:** Removes the **Invulnerable** status and applies Weakness to the payload.
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
    * **Restriction:** **Invulnerable**. You cannot damage the boss until the patch is deployed.
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
* **Behavior:** **The Masquerade.** Starts as **Invulnerable**. Standard attacks trigger **25 Counter Damage**. Shuffles **Malicious Link** junk cards into your deck every turn.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes **Invulnerable** status.
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
* **Behavior:** **The Trusted Source.** Starts as **Invulnerable**. Heals all characters for 10 HP every turn. Deals 10 damage every turn if left as the last enemy while remaining **Invulnerable**.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes **Invulnerable** status and **Stuns** the target.
    * **MFA:** Negates healing and RAM theft actions for the turn.
    * **Awareness Training:** Reveals all Social enemies and applies **Vulnerability**.
* **📝 CyberDex:** "The act of creating and using an invented scenario to engage a targeted victim to divulge information." [Source: NIST SP 800-61]

---

### **👑 BOSS: The Whaling Attack**

* **Class:** 🎭 **Social**
* **Role:** Chapter 2 Boss (The Executive Impersonator)
* **HP:** 120 | **Dmg:** 10
* **Behavior:** **High-Level Compromise.** Starts as **Invulnerable**. Increases the cost of the highest-RAM card in hand by **+2 RAM** (capped at **5 RAM**) each turn. Deals **25 Massive Damage** after Turn 4.
* **Mitigation Cards:**
    * **WhoIs Lookup:** Removes **Invulnerable** status and **Stuns** the Boss.
    * **MFA:** Negates the Lockout effect and the 25 Damage strike for the turn.
    * **Decryption Key:** Resets all card costs in hand back to their original values.
    * **Awareness Training:** Removes **Invulnerable** status and applies **Vulnerability**.
* **📝 CyberDex:** "A specific form of phishing that targets high-profile employees, such as CEOs and CFOs, to steal sensitive information or money." [Source: FBI IC3]

---

## 📂 **Chapter 3: Network Intrusion (Propagation)**

**Theme:** Speed, swarms, and replication.

---

### **1. Polymorphic Worm (The Multiplier)**

* **Class:** 🦠 **Malware**
* **Stats:** 32 HP (Parent) / 16 HP (Copy) | **Dmg:** 8
* **Behavior: Recursive Propagation**
    * **Alpha Node:** The larger Parent worm starts as the only threat. As long as it is alive, it is the "Source."
    * **Self-Replication:** At the end of every turn, the Parent summons one **Worm Copy** (up to a maximum of 4 copies on the field).
    * **Source Termination:** Once the Parent is defeated, replication stops. Existing copies remain but can no longer multiply.
* **Mitigation Strategy (Containment):**
    * **Signature Match:** Two hits (4 RAM) delete the Source node on Turn 1 before it spreads.
    * **Flood Gate:** Damages every instance of the code simultaneously to prevent being overwhelmed.
    * **Heuristic Strike:** High efficiency specialized damage (18 vs Malware) for only 1 RAM.
* **📝 CyberDex:** "A self-replicating, self-propagating program that uses networking mechanisms to spread itself." [Source: NIST CSRC Glossary]

---

### **2. Botnet Node (The Swarm)**

* **Class:** 🌐 **Network**
* **Stats:** 12 HP | **Dmg:** 3 (+1 per active ally)
* **Behavior: Sync Attack**
    * **Networked Strength:** Nodes use a shared protocol to synchronize strikes.
    * **Calculated Scaling:** Damage scales based on total bots present (Max 4). 1 Node: 3 Dmg; 4 Nodes: 24 Total Dmg.
    * **Bandwidth Cap:** Maximum of 4 Botnet Nodes can be maintained on screen at once.
* **Mitigation Strategy (Traffic Control):**
    * **IP Ban:** Stuns the target to remove its "Sync" contribution for the turn.
    * **Packet Filter:** Deletes a 12 HP node and draws 2 cards to find more AOE.
    * **Traffic Throttling:** Uses established Shields to "Shield Bash" bots for 2 RAM.
* **📝 CyberDex:** "A collection of compromised computers co-opted to perform malicious tasks under remote control." [Source: NIST SP 800-115]

---

### **3. Logic Bomb (The Nuke)**

* **Class:** 🦠 **Malware**
* **Stats:** 80 HP | **Dmg:** 999 (Instant System Failure)
* **Behavior: The Dormant Execution**
    * **The Countdown:** A **4-Turn** timer is displayed. If it hits zero, it deals 999 damage.
    * **The Pause Mechanism:** **Every time an Attack Card is used on the Bomb**, the timer pauses and does not decrement that turn.
    * **The Reset:** If a turn passes without taking attack damage, the timer drops by 1.
* **Mitigation Strategy (Sanitization):**
    * **Ping Command:** 1 RAM to keep the timer from ticking down.
    * **Boot Scan:** Primary damage dealer (25 Dmg vs Malware) to defuse the 80 HP core.
    * **Quarantine:** Stuns the target and pauses the timer, ensuring total isolation.
* **📝 CyberDex:** "Code intentionally inserted into software that sets off a malicious function when specified conditions are met." [Source: NIST SP 800-12]

---

### **👑 BOSS: The C2 Server (Command & Control)**

* **Class:** 🌐 **Network**
* **Stats:** 160 HP | **Dmg:** 0 (Indirect)
* **Behavior: The Mastermind Protocol**
    * **Command Latency:** Summons **2 Botnet Nodes** every **3 turns** (Max 4 bots on field).
    * **Encrypted Shielding:** While at least one Botnet Node is active, the Server is **Invulnerable**.
    * **The Vulnerability Window:** **Invulnerable** only drops once all proxies (bots) are cleared.
    * **Bot Herder:** Never attacks directly; relies on synchronized botnet damage.
* **Mitigation Strategy (Infiltration):**
    * **Flood Gate:** Wipes the bot swarm in one turn to expose the Server core.
    * **IP Ban (Reworked):** The "Assassin" card dealing 30-50 damage to Network classes to burst the 160 HP.
    * **Traffic Throttling:** Converts surviving defense (Shields) into massive offense during the window.
* **📝 CyberDex:** "A server controlled by an attacker to send commands to systems compromised by malware." [Source: MITRE ATT&CK: T1071]
