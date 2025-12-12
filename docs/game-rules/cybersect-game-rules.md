# CyberSect – Game Rules

## 1. Core Concept
**CyberSect** is a single-player, turn-based card game where you play as a **Blue Team Operator** defending a network. You mitigate threats (Malware) using a deck of **Protocols** (Cards).

## 2. The Operational Loop
1.  **Monitor:** Select a compromised node (Level) on the Map.
2.  **Engage:** Battle waves of malware (Standard: 2 Waves | Boss: 3-4 Waves).
3.  **Remediate:** Reduce Enemy Integrity (HP) to 0 while protecting System Stability (Player HP).
4.  **Analyze:** Victory grants **Cyber Points (CP)** and Data Logs (Card Rewards).
5.  **Patch:** Spend CP at the **Repository (Shop)** to buy cards or upgrade existing ones.
6.  **Certify:** Defeating Chapter Bosses unlocks new **Job Specializations**.

## 3. Operator Progression (Classes)
* **Tier 1: Script Kiddie (Rookie):** Balanced starter stats.
* **Tier 2: Firewall Guardian:** Focuses on Defense (Shields).
* **Tier 2: Antivirus Specialist:** Focuses on Offense (Attacks).
* **Tier 2: Ethical Hacker:** Focuses on Utility (Control/Debuffs).

## 4. Card Architecture
All cards cost **RAM** (Energy) to use. Cards are divided by function, but **any card** can have a specialized effect.

### **Functional Types**
* 🗡️ **Execute (Attack):** Deals damage to Enemy Integrity.
* 🛡️ **Harden (Defense):** Grants **Firewall** (Shield) points.
* 🔧 **Patch (Utility):** Heals, draws cards, or applies Status Effects.

### **The "Signature Match" Mechanic**
**Attack, Defense, and Utility** cards can all have a **Condition**.

* **Generic Cards:** Reliable, mid-range effects that work on everyone. (e.g., "Deal 10 Damage").
* **Specialized Cards:** Have a **Weaker Base Effect** but a **Powerful Bonus** if the target matches a specific malware type.
    * *Example Attack:* **"Deep Clean"** (Deal 5 Dmg. **If Worm:** Deal 25 Dmg).
    * *Example Defense:* **"Traffic Shaper"** (Shield 5. **If DDoS:** Shield 25).
    * *Example Utility:* **"Decryption Tool"** (Heal 5 HP. **If Ransomware:** Remove "Lock" Status).

## 5. Runtime (Turn Structure)
1.  **Fetch Phase:** Draw 2 cards (Hand limit: 10).
2.  **Allocation Phase:** Gain **RAM** (Refills to max, usually 3-4).
3.  **Execute Phase:** Play cards.
4.  **Intrusion Phase:** Enemy attacks/actions occur.
5.  **Garbage Collection:** Start/End of turn effects resolve (Poison/Stun).

## 6. Defense Metrics
* **Integrity (Health):** Reaching 0 causes a System Crash (Level Fail).
* **Firewall (Shield):** Temporary hit points. Blocks damage. Resets to 0 at the start of your turn.
* **RAM (Energy):** Resource to play cards.
* **Throttling:** In Boss battles, reshuffling your deck causes Overheating (-5 Integrity).

## 7. Status Conditions (Simplified)
We focus only on the critical network states.

| Icon | Name | Effect |
| :--- | :--- | :--- |
| 💤 | **Latency (Stun)** | Target cannot act next turn. |
| 🦠 | **Memory Leak (Poison)** | Target loses X Integrity at the start of their turn. |
| 🔒 | **Encrypted (Lock)** | Player cannot use a specific card for X turns. |
| 🛡️ | **Firewall (Shield)** | Absorbs incoming damage. |

## 8. Loot & Economy

### **Clearance Levels (Drop Rates)**
* **Standard Enemies:** High chance of **Common**. Low chance of **Uncommon**.
* **Mini-Bosses:** Guaranteed **Uncommon** choice. Small chance of **Rare**.
* **Chapter Bosses:** Guaranteed **Rare** choice.

### **The Repository (Shop)**
Sells cards for **Cyber Points (CP)**. Inventory improves as you advance Chapters.
* **Stock:** 5 Cards + Upgrade Station.

## 9. Upgrade System ("Patch Management")
Upgrading cards improves their stats (Damage/Shield) or lowers their RAM cost. However, hardware has limits.

| Rarity | Upgrade Limit | Logic |
| :--- | :--- | :--- |
| **Common** | **Max Level 3** (Upgrade 2 times) | Highly customizable generic scripts. |
| **Uncommon** | **Max Level 2** (Upgrade 1 time) | Specialized tools with one optimized version. |
| **Rare** | **Max Level 1** (No Upgrades) | Enterprise tools. Powerful immediately, but static. |

## 10. The CyberDex
* **In-Game Database:** Unlocks entries for every Enemy and Card encountered.
* **Content:** Contains the **Game Rule** and the **Real World Definition** (sourced from NIST/MITRE).