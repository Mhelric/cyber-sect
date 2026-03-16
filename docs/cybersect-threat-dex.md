# 👾 CyberSect: Threat Database v1.2

## 🔑 Class Legend

* 🦠 **Malware:** Weak vs **Antivirus** (High Damage).
* 🌐 **Network:** Weak vs **Firewall** (Shields/Filtering).
* 🎭 **Social:** Weak vs **Scan/Utility** (Analysis).
* 🔒 **Crypto:** Weak vs **Decryption** (Shield Pierce).

---

## 📂 Chapter 1: The Perimeter (Infiltration)

**Theme:** Basic scripts and nuisances.

### 1. Script Kiddie

* **Class:** 🌐 **Network**
* **Role:** Basic Attacker
* **HP:** 25 | **Dmg:** 5
* **Behavior:** **Ping Flood.** Deal low, consistent damage every turn.
* **📝 CyberDex:** "An unskilled attacker who uses existing computer scripts or code to hack into computers, lacking the expertise to write their own." [Source: NIST SP 800-12 Rev 1]

### 2. Adware

* **Class:** 🌐 **Network**
* **Role:** Disrupter
* **HP:** 32 | **Dmg:** 0
* **Behavior:** **Popup Spam.** Shuffles "Pop-Up Window" cards into your draw pile.
    * *Card: Pop-Up Window* (Cost: 1 RAM). Effect: Play this card to remove it from your hand. Take 2 Damage.
* **📝 CyberDex:** "Software that automatically displays or downloads advertising material. It clutters resources until manually removed." [Source: CISA Security Tip ST04-016]

### 3. Trojan

* **Class:** 🦠 **Malware**
* **Role:** Time Bomb
* **HP:** 50 | **Dmg:** 0 (Passive) / 20 (Active)
* **Behavior:** **Payload.** Does nothing for 3 turns (Masquerading), then deals massive damage.
* **📝 CyberDex:** "A computer program that appears to have a useful function, but also has a hidden and potentially malicious function." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Zero-Day

* **Class:** 🦠 **Malware**
* **Role:** **Chapter 1 Boss**
* **HP:** 125
* **Base Dmg:** 10 (Enrages to 15 Dmg if Shield is broken early).
* **Behavior:** **Unpatched Vulnerability.** Starts with a massive **50 Shield**. You can either wait 3 turns for the shield to naturally decay to 0, *or* aggressively break the shield to expose its HP early.
* **📝 CyberDex:** "An attack that targets a previously unknown vulnerability... meaning developers have had zero days to fix it." [Source: NIST SP 800-53]

---

## 📂 Chapter 2: The Human Factor (Deception)

**Theme:** Tricks, traps, and user error.

### 1. Phishing Link

* **Class:** 🎭 **Social**
* **Role:** Trap
* **HP:** 25 | **Dmg:** 25 (Counter)
* **Behavior:** **Bait Hook.** Counters if attacked directly. Instantly dies if targeted by a **Scan (Utility)** card.
* **📝 CyberDex:** "A technique for attempting to acquire sensitive data... in which the perpetrator masquerades as a legitimate business." [Source: NIST SP 800-83 Rev. 1]

### 2. Keylogger

* **Class:** 🎭 **Social**
* **Role:** Resource Thief
* **HP:** 65 | **Dmg:** 2 per card
* **Behavior:** **Surveillance.** Deals damage every time you play a card (simulating keystroke tracking).
* **📝 CyberDex:** "Software or hardware that tracks the keys struck on a keyboard... to monitor actions or steal information." [Source: MITRE ATT&CK: T1056.001]

### 3. Pretexter

* **Class:** 🎭 **Social**
* **Role:** Support
* **HP:** 40 | **Dmg:** 0
* **Behavior:** **Social Engineering.** Heals other enemies.
* **📝 CyberDex:** "An attacker creates a fabricated scenario (the pretext) to persuade a victim to release information." [Source: NIST SP 800-61 Rev. 2]

### 👑 BOSS: The Whaling Attack

* **Class:** 🎭 **Social**
* **Role:** **Chapter 2 Boss**
* **HP:** 100
* **Base Dmg:** 8. (Supplementary Dmg from "Fake Login" cards).
* **Behavior:** **Impersonation.** Targets the highest-cost card in your hand and applies "Locked." You must pay 1 extra RAM to unlock and play it. Shuffles "Fake Login" (Take 2 Damage) cards into your draw pile.
* **📝 CyberDex:** "A specific type of phishing attack that targets high-profile employees, such as the CEO or CFO." [Source: CISA Security Tip ST04-014]

---

## 📂 Chapter 3: Network Chaos (Propagation)

**Theme:** Speed, swarms, and replication.

### 1. Polymorphic Worm

* **Class:** 🦠 **Malware**
* **Role:** Multiplier
* **HP:** 32 | **Dmg:** 8
* **Behavior:** **Replication.** Summons a copy of itself at the end of every turn.
* **📝 CyberDex:** "A self-replicating, self-propagating, self-contained program that uses networking mechanisms to spread itself." [Source: NIST CSRC Glossary]

### 2. Botnet Node

* **Class:** 🌐 **Network**
* **Role:** Swarm
* **HP:** 12 | **Dmg:** 3 (+2 per ally)
* **Behavior:** **Sync Attack.** Damage scales based on how many other Bots are alive.
* **📝 CyberDex:** "A collection of compromised computers (bots)... co-opted to perform malicious tasks under remote control." [Source: NIST SP 800-115]

### 3. Logic Bomb

* **Class:** 🦠 **Malware**
* **Role:** The Nuke
* **HP:** 80 | **Dmg:** 999 (Delayed)
* **Behavior:** **Countdown.** Counts down to zero. Taking damage pauses the timer.
* **📝 CyberDex:** "Code intentionally inserted into software that will set off a malicious function when specified conditions are met." [Source: NIST SP 800-12]

### 👑 BOSS: The C2 Server

* **Class:** 🌐 **Network**
* **Role:** **Chapter 3 Boss**
* **HP:** 160
* **Base Dmg:** 0. (Relies entirely on scaling damage from summoned Botnets).
* **Behavior:** **Bot Herder.** Never attacks directly. Summons infinite Botnet Nodes. Invulnerable while Bots are alive.
* **📝 CyberDex:** "Command and Control: A server controlled by an attacker to send commands to systems compromised by malware." [Source: MITRE ATT&CK: T1071]

---

## 📂 Chapter 4: Advanced Threats (Persistence)

**Theme:** Locking resources and invulnerability.

### 1. Ransomware

* **Class:** 🔒 **Crypto**
* **Role:** Locker
* **HP:** 55 | **Dmg:** 10
* **Behavior:** **Encryption.** Applies "Lock" status to cards in your hand, making them unplayable.
* **📝 CyberDex:** "Malicious software that denies access to a computer system or data until a ransom is paid." [Source: CISA Security Tip ST19-001]

### 2. Rootkit

* **Class:** 🔒 **Crypto**
* **Role:** Tank
* **HP:** 100 | **Dmg:** 12
* **Behavior:** **Deep Persistence.** Regenerates a massive Shield every turn.
* **📝 CyberDex:** "Tools that enable an unauthorized user to gain control of a computer system without being detected." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Polymorphic Engine

* **Class:** 🔄 **Variable** (Shapeshifter)
* **Role:** **Chapter 4 Boss**
* **HP:** 150
* **Base Dmg:** 15.
* **Behavior:** **Mutation.** Changes its Class Weakness every turn (Malware -> Network -> Crypto). Striking it with a card that *matches* its current weakness **refunds 1 RAM**.
* **📝 CyberDex:** "Malware that changes its code signatures each time it runs to evade detection by traditional antivirus." [Source: NIST CSRC Glossary]

---

## 📂 Chapter 5: The Final Breach

**Theme:** The ultimate test of all skills.

### 👑 FINAL BOSS: The APT (Advanced Persistent Threat)

* **Class:** 💀 **Omni-Class**
* **Role:** **Final Boss**
* **HP:** 250
* **(Phase 1):** Dmg: 0 (Summons Swarm).
* **(Phase 2):** Dmg: 15.
* **(Phase 3):** Dmg: 0 (Counts down to 999).
* **Behavior:** **The Kill Chain.**
* **Phase 1:** Summons Botnets (Requires Crowd Control).
* **Phase 2:** Locks Cards (Requires Decryption).
* **Phase 3:** Logic Bomb Countdown (Requires DPS).


* **Signature Move:** **Data Exfiltration** (Instant Loss if Player HP < 20%).
* **📝 CyberDex:** "An adversary with sophisticated levels of expertise... allowing it to achieve objectives using multiple attack vectors." [Source: NIST SP 800-39]

---

### 📊 The Total Count

* **Standard Threats (Trash Mobs):** 11 Unique Enemies
* **High-Value Targets (Bosses):** 5 Unique Bosses
* **Grand Total:** **16 Unique Enemies**
* **HP:** 32 | **Dmg:** 0
* **Behavior:** **Popup Spam.** Shuffles "Pop-Up Window" cards into your draw pile.
    * *Card: Pop-Up Window* (Cost: 1 RAM). Effect: Play this card to remove it from your hand. Take 2 Damage.
* **📝 CyberDex:** "Software that automatically displays or downloads advertising material. It clutters resources until manually removed." [Source: CISA Security Tip ST04-016]

### 3. Trojan

* **Class:** 🦠 **Malware**
* **Role:** Time Bomb
* **HP:** 50 | **Dmg:** 0 (Passive)  20 (Active)
* **Behavior:** **Payload.** Does nothing for 3 turns (Masquerading), then deals massive damage.
* **📝 CyberDex:** "A computer program that appears to have a useful function, but also has a hidden and potentially malicious function." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Zero-Day

* **Class:** 🦠 **Malware**
* **Role:** **Chapter 1 Boss**
* **HP:** 125
* **Behavior:** **Unpatched Vulnerability.** Starts Invulnerable. You must survive 3 turns to "Analyze" it before you can deal damage.
* **📝 CyberDex:** "An attack that targets a previously unknown vulnerability... meaning developers have had zero days to fix it." [Source: NIST SP 800-53]

---

## 📂 Chapter 2: The Human Factor (Deception)

**Theme:** Tricks, traps, and user error.

### 1. Phishing Link

* **Class:** 🎭 **Social**
* **Role:** Trap
* **HP:** 25 | **Dmg:** 25 (Counter)
* **Behavior:** **Bait Hook.** Counters if attacked directly. Instantly dies if targeted by a **Scan (Utility)** card.
* **📝 CyberDex:** "A technique for attempting to acquire sensitive data... in which the perpetrator masquerades as a legitimate business." [Source: NIST SP 800-83 Rev. 1]

### 2. Keylogger

* **Class:** 🎭 **Social**
* **Role:** Resource Thief
* **HP:** 65 | **Dmg:** 2 per card
* **Behavior:** **Surveillance.** Deals damage every time you play a card (simulating keystroke tracking).
* **📝 CyberDex:** "Software or hardware that tracks the keys struck on a keyboard... to monitor actions or steal information." [Source: MITRE ATT&CK: T1056.001]

### 3. Pretexter

* **Class:** 🎭 **Social**
* **Role:** Support
* **HP:** 40 | **Dmg:** 0
* **Behavior:** **Social Engineering.** Heals other enemies.
* **📝 CyberDex:** "An attacker creates a fabricated scenario (the pretext) to persuade a victim to release information." [Source: NIST SP 800-61 Rev. 2]

### 👑 BOSS: The Whaling Attack

* **Class:** 🎭 **Social**
* **Role:** **Chapter 2 Boss**
* **HP:** 100
* **Behavior:** **Impersonation.** Steals cards from your hand and uses them against you. Shuffles "Fake Login" damage cards into your deck.
* **📝 CyberDex:** "A specific type of phishing attack that targets high-profile employees, such as the CEO or CFO." [Source: CISA Security Tip ST04-014]

---

## 📂 Chapter 3: Network Chaos (Propagation)

**Theme:** Speed, swarms, and replication.

### 1. Polymorphic Worm

* **Class:** 🦠 **Malware**
* **Role:** Multiplier
* **HP:** 32 | **Dmg:** 8
* **Behavior:** **Replication.** Summons a copy of itself at the end of every turn.
* **📝 CyberDex:** "A self-replicating, self-propagating, self-contained program that uses networking mechanisms to spread itself." [Source: NIST CSRC Glossary]

### 2. Botnet Node

* **Class:** 🌐 **Network**
* **Role:** Swarm
* **HP:** 12 | **Dmg:** 3 (+2 per ally)
* **Behavior:** **Sync Attack.** Damage scales based on how many other Bots are alive.
* **📝 CyberDex:** "A collection of compromised computers (bots)... co-opted to perform malicious tasks under remote control." [Source: NIST SP 800-115]

### 3. Logic Bomb

* **Class:** 🦠 **Malware**
* **Role:** The Nuke
* **HP:** 80 | **Dmg:** 999 (Delayed)
* **Behavior:** **Countdown.** Counts down to zero. Taking damage pauses the timer.
* **📝 CyberDex:** "Code intentionally inserted into software that will set off a malicious function when specified conditions are met." [Source: NIST SP 800-12]

### 👑 BOSS: The C2 Server

* **Class:** 🌐 **Network**
* **Role:** **Chapter 3 Boss**
* **HP:** 160
* **Behavior:** **Bot Herder.** Never attacks directly. Summons infinite Botnet Nodes. Invulnerable while Bots are alive.
* **📝 CyberDex:** "Command and Control: A server controlled by an attacker to send commands to systems compromised by malware." [Source: MITRE ATT&CK: T1071]

---

## 📂 Chapter 4: Advanced Threats (Persistence)

**Theme:** Locking resources and invulnerability.

### 1. Ransomware

* **Class:** 🔒 **Crypto**
* **Role:** Locker
* **HP:** 55 | **Dmg:** 10
* **Behavior:** **Encryption.** Applies "Lock" status to cards in your hand, making them unplayable.
* **📝 CyberDex:** "Malicious software that denies access to a computer system or data until a ransom is paid." [Source: CISA Security Tip ST19-001]

### 2. Rootkit

* **Class:** 🔒 **Crypto**
* **Role:** Tank
* **HP:** 100 | **Dmg:** 12
* **Behavior:** **Deep Persistence.** Regenerates a massive Shield every turn.
* **📝 CyberDex:** "Tools that enable an unauthorized user to gain control of a computer system without being detected." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Polymorphic Engine

* **Class:** 🔄 **Variable** (Shapeshifter)
* **Role:** **Chapter 4 Boss**
* **HP:** 150
* **Behavior:** **Mutation.** Changes its Class Weakness every turn (Malware  Network  Crypto). You must wait for the right turn to strike.
* **📝 CyberDex:** "Malware that changes its code signatures each time it runs to evade detection by traditional antivirus." [Source: NIST CSRC Glossary]

---

## 📂 Chapter 5: The Final Breach

**Theme:** The ultimate test of all skills.

### 👑 FINAL BOSS: The APT (Advanced Persistent Threat)

* **Class:** 💀 **Omni-Class**
* **Role:** **Final Boss**
* **HP:** 250
* **Behavior:** **The Kill Chain.**
* **Phase 1:** Summons Botnets (Requires Crowd Control).
* **Phase 2:** Locks Cards (Requires Decryption).
* **Phase 3:** Logic Bomb Countdown (Requires DPS).


* **Signature Move:** **Data Exfiltration** (Instant Loss if Player HP < 20%).
* **📝 CyberDex:** "An adversary with sophisticated levels of expertise... allowing it to achieve objectives using multiple attack vectors." [Source: NIST SP 800-39]

---

Here is the total breakdown of unique hostile units in the game:

### 📊 The Total Count

* **Standard Threats (Trash Mobs):** 11 Unique Enemies
* **High-Value Targets (Bosses):** 5 Unique Bosses
* **Grand Total:** **16 Unique Enemies**

---

### 📝 Breakdown by Chapter

| Chapter | Standard Enemies | Boss | Total New Units |
| --- | --- | --- | --- |
| **1. The Perimeter** | Script Kiddie, Adware, Trojan | The Zero-Day | **4** |
| **2. Human Factor** | Phishing, Keylogger, Pretexter | Whaling Attack | **4** |
| **3. Network Chaos** | Worm, Botnet, Logic Bomb | C2 Server | **4** |
| **4. Advanced Threats** | Ransomware, Rootkit | Polymorphic Engine | **3** |
| **5. Final Breach** | *(Reuses Elite Enemies)* | The APT | **1** |
* **Role:** Disrupter
* **HP:** 40 | **Dmg:** 0
* **Behavior:** **Popup Spam.** Shuffles "Pop-Up Window" cards into your draw pile.
    * *Card: Pop-Up Window* (Cost: 1 RAM). Effect: Play this card to remove it from your hand. Take 2 Damage.
* **📝 CyberDex:** "Software that automatically displays or downloads advertising material. It clutters resources until manually removed." [Source: CISA Security Tip ST04-016]

### 3. Trojan

* **Class:** 🦠 **Malware**
* **Role:** Time Bomb
* **HP:** 60 | **Dmg:** 0 (Passive)  20 (Active)
* **Behavior:** **Payload.** Does nothing for 3 turns (Masquerading), then deals massive damage.
* **📝 CyberDex:** "A computer program that appears to have a useful function, but also has a hidden and potentially malicious function." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Zero-Day

* **Class:** 🦠 **Malware**
* **Role:** **Chapter 1 Boss**
* **HP:** 150
* **Behavior:** **Unpatched Vulnerability.** Starts Invulnerable. You must survive 3 turns to "Analyze" it before you can deal damage.
* **📝 CyberDex:** "An attack that targets a previously unknown vulnerability... meaning developers have had zero days to fix it." [Source: NIST SP 800-53]

---

## 📂 Chapter 2: The Human Factor (Deception)

**Theme:** Tricks, traps, and user error.

### 1. Phishing Link

* **Class:** 🎭 **Social**
* **Role:** Trap
* **HP:** 30 | **Dmg:** 25 (Counter)
* **Behavior:** **Bait Hook.** Counters if attacked directly. Instantly dies if targeted by a **Scan (Utility)** card.
* **📝 CyberDex:** "A technique for attempting to acquire sensitive data... in which the perpetrator masquerades as a legitimate business." [Source: NIST SP 800-83 Rev. 1]

### 2. Keylogger

* **Class:** 🎭 **Social**
* **Role:** Resource Thief
* **HP:** 80 | **Dmg:** 2 per card
* **Behavior:** **Surveillance.** Deals damage every time you play a card (simulating keystroke tracking).
* **📝 CyberDex:** "Software or hardware that tracks the keys struck on a keyboard... to monitor actions or steal information." [Source: MITRE ATT&CK: T1056.001]

### 3. Pretexter

* **Class:** 🎭 **Social**
* **Role:** Support
* **HP:** 50 | **Dmg:** 0
* **Behavior:** **Social Engineering.** Heals other enemies.
* **📝 CyberDex:** "An attacker creates a fabricated scenario (the pretext) to persuade a victim to release information." [Source: NIST SP 800-61 Rev. 2]

### 👑 BOSS: The Whaling Attack

* **Class:** 🎭 **Social**
* **Role:** **Chapter 2 Boss**
* **HP:** 120
* **Behavior:** **Impersonation.** Steals cards from your hand and uses them against you. Shuffles "Fake Login" damage cards into your deck.
* **📝 CyberDex:** "A specific type of phishing attack that targets high-profile employees, such as the CEO or CFO." [Source: CISA Security Tip ST04-014]

---

## 📂 Chapter 3: Network Chaos (Propagation)

**Theme:** Speed, swarms, and replication.

### 1. Polymorphic Worm

* **Class:** 🦠 **Malware**
* **Role:** Multiplier
* **HP:** 40 | **Dmg:** 8
* **Behavior:** **Replication.** Summons a copy of itself at the end of every turn.
* **📝 CyberDex:** "A self-replicating, self-propagating, self-contained program that uses networking mechanisms to spread itself." [Source: NIST CSRC Glossary]

### 2. Botnet Node

* **Class:** 🌐 **Network**
* **Role:** Swarm
* **HP:** 15 | **Dmg:** 3 (+2 per ally)
* **Behavior:** **Sync Attack.** Damage scales based on how many other Bots are alive.
* **📝 CyberDex:** "A collection of compromised computers (bots)... co-opted to perform malicious tasks under remote control." [Source: NIST SP 800-115]

### 3. Logic Bomb

* **Class:** 🦠 **Malware**
* **Role:** The Nuke
* **HP:** 100 | **Dmg:** 999 (Delayed)
* **Behavior:** **Countdown.** Counts down to zero. Taking damage pauses the timer.
* **📝 CyberDex:** "Code intentionally inserted into software that will set off a malicious function when specified conditions are met." [Source: NIST SP 800-12]

### 👑 BOSS: The C2 Server

* **Class:** 🌐 **Network**
* **Role:** **Chapter 3 Boss**
* **HP:** 200
* **Behavior:** **Bot Herder.** Never attacks directly. Summons infinite Botnet Nodes. Invulnerable while Bots are alive.
* **📝 CyberDex:** "Command and Control: A server controlled by an attacker to send commands to systems compromised by malware." [Source: MITRE ATT&CK: T1071]

---

## 📂 Chapter 4: Advanced Threats (Persistence)

**Theme:** Locking resources and invulnerability.

### 1. Ransomware

* **Class:** 🔒 **Crypto**
* **Role:** Locker
* **HP:** 70 | **Dmg:** 10
* **Behavior:** **Encryption.** Applies "Lock" status to cards in your hand, making them unplayable.
* **📝 CyberDex:** "Malicious software that denies access to a computer system or data until a ransom is paid." [Source: CISA Security Tip ST19-001]

### 2. Rootkit

* **Class:** 🔒 **Crypto**
* **Role:** Tank
* **HP:** 120 | **Dmg:** 12
* **Behavior:** **Deep Persistence.** Regenerates a massive Shield every turn.
* **📝 CyberDex:** "Tools that enable an unauthorized user to gain control of a computer system without being detected." [Source: NIST CSRC Glossary]

### 👑 BOSS: The Polymorphic Engine

* **Class:** 🔄 **Variable** (Shapeshifter)
* **Role:** **Chapter 4 Boss**
* **HP:** 180
* **Behavior:** **Mutation.** Changes its Class Weakness every turn (Malware  Network  Crypto). You must wait for the right turn to strike.
* **📝 CyberDex:** "Malware that changes its code signatures each time it runs to evade detection by traditional antivirus." [Source: NIST CSRC Glossary]

---

## 📂 Chapter 5: The Final Breach

**Theme:** The ultimate test of all skills.

### 👑 FINAL BOSS: The APT (Advanced Persistent Threat)

* **Class:** 💀 **Omni-Class**
* **Role:** **Final Boss**
* **HP:** 300
* **Behavior:** **The Kill Chain.**
* **Phase 1:** Summons Botnets (Requires Crowd Control).
* **Phase 2:** Locks Cards (Requires Decryption).
* **Phase 3:** Logic Bomb Countdown (Requires DPS).


* **Signature Move:** **Data Exfiltration** (Instant Loss if Player HP < 20%).
* **📝 CyberDex:** "An adversary with sophisticated levels of expertise... allowing it to achieve objectives using multiple attack vectors." [Source: NIST SP 800-39]

---

Here is the total breakdown of unique hostile units in the game:

### 📊 The Total Count

* **Standard Threats (Trash Mobs):** 11 Unique Enemies
* **High-Value Targets (Bosses):** 5 Unique Bosses
* **Grand Total:** **16 Unique Enemies**

---

### 📝 Breakdown by Chapter

| Chapter | Standard Enemies | Boss | Total New Units |
| --- | --- | --- | --- |
| **1. The Perimeter** | Script Kiddie, Adware, Trojan | The Zero-Day | **4** |
| **2. Human Factor** | Phishing, Keylogger, Pretexter | Whaling Attack | **4** |
| **3. Network Chaos** | Worm, Botnet, Logic Bomb | C2 Server | **4** |
| **4. Advanced Threats** | Ransomware, Rootkit | Polymorphic Engine | **3** |
| **5. Final Breach** | *(Reuses Elite Enemies)* | The APT | **1** |
