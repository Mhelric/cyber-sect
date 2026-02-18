# 👾 CyberSect: Card Database (Master Protocol Library)

* **[General]:** Reliable effects that work on any enemy.
* **[Specialized]:** Cards that trigger a bonus effect if the target matches a specific **Class** (Signature Match).

## Database Statistics

**Total Unique Cards:** 45

**Breakdown by Category:**
* **General Cards:** 30 (Universal tools)
* **Specialized Cards:** 15 (Class-specific counters)

**Breakdown by Rarity:**
* **Common / Starter:** 24 Cards (53%)
* **Uncommon:** 14 Cards (31%)
* **Rare:** 7 Cards (16%)

**Breakdown by Class Affinity:**
* **Script Kiddie:** 11 Cards
* **Network Engineer:** 12 Cards
* **Threat Hunter:** 11 Cards
* **Pen Tester:** 11 Cards

---

## Upgrade Rules (Patch Management)
* **Common Cards:** Max Level 3 (v3.0). Requires 3 Duplicates per tier.
* **Uncommon Cards:** Max Level 2 (v2.0). Requires 2 Duplicates per tier.
* **Rare Cards:** Max Level 1 (v1.0). Read-Only code. No upgrades.

---

## 1. Script Kiddie Deck (Rookie)
**Theme:** Basic Tools. Reliable, low complexity.

### Attack Cards (Execute)

**1. Ping Command**
* **Category:** [General]
* **Rarity:** Starter (Common)
* **Cost:** 1 RAM
* **Base Effect:** Deal 6 Damage.
* **Upgrade Path:**
    * v2.0: Deal 9 Damage.
    * v3.0: Deal 12 Damage.
* **CyberDex:** "A utility used to test the reachability of a host on an Internet Protocol (IP) network." [RFC 792]

**2. DDoS Script**
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal 8 Damage. If Network Class: Deal 16 Damage.
* **Upgrade Path:**
    * v2.0: Deal 10 Damage (Bonus: 20).
    * v3.0: Deal 12 Damage (Bonus: 24).
* **CyberDex:** "Distributed Denial of Service: An attack that prevents authorized use of networks by exhausting resources." [NIST SP 800-61]

**3. Signature Match**
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal 8 Damage. If Malware Class: Deal 16 Damage.
* **Upgrade Path:**
    * v2.0: Deal 10 Damage (Bonus: 20).
    * v3.0: Deal 12 Damage (Bonus: 24).
* **CyberDex:** "A recognizable pattern of data or signals that indicates a specific threat." [NIST CSRC]

**4. Boot Scan** (New!)
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal 5 Damage. If Malware: Deal 25 Damage.
* **Upgrade Path:**
    * v2.0: Deal 30 Damage.
    * v3.0: Deal 35 Damage.
* **CyberDex:** "A scan that runs at system startup to detect rootkits and malware before the OS loads." [NIST SP 800-83]

**5. Spam Filter** (New!)
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Deal 5 Damage. If Social: Exhaust (Remove) all Status Cards ("Junk") in your hand.
* **Upgrade Path:**
    * v2.0: Deal 8 Damage.
* **CyberDex:** "Software that automatically detects and deletes unsolicited bulk email to prevent phishing." [NIST SP 800-45]

### Defense Cards (Harden)

**6. Basic Firewall**
* **Category:** [General]
* **Rarity:** Starter (Common)
* **Cost:** 1 RAM
* **Base Effect:** Gain 6 Shield.
* **Upgrade Path:**
    * v2.0: Gain 9 Shield.
    * v3.0: Gain 12 Shield.
* **CyberDex:** "A gateway that restricts data communication traffic to and from one of the connected networks." [NIST SP 800-41]

**7. Patch Update**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain 4 Shield. Draw 1 card.
* **Upgrade Path:**
    * v2.0: Gain 7 Shield. Draw 1.
    * v3.0: Gain 10 Shield. Draw 1.
* **CyberDex:** "The systematic notification, identification, deployment, and verification of software code revisions." [NIST SP 800-40]

**8. Air Gap**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 3 RAM
* **Base Effect:** Gain 20 Shield. You cannot play any more cards this turn.
* **Upgrade Path:** Read-Only (No Upgrades).
* **CyberDex:** "Manual isolation. An interface between two systems at which they are not connected physically." [NIST CSRC]

**9. Multi-Factor Auth (MFA)** (New!)
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. If Social: Prevent all **Debuffs** this turn.
* **Upgrade Path:**
    * v2.0: Gain 8 Shield.
    * v3.0: Gain 11 Shield.
* **CyberDex:** "An authentication system that requires more than one distinct authentication factor for access." [NIST SP 800-63]

### Utility Cards (Patch)

**10. Force Quit**
* **Category:** [General]
* **Rarity:** Starter (Common)
* **Cost:** 0 RAM
* **Base Effect:** Gain 1 Energy. Lose 3 HP.
* **Upgrade Path:**
    * v2.0: Gain 1 Energy. Lose 2 HP.
    * v3.0: Gain 2 Energy. Lose 3 HP.
* **CyberDex:** "The act of terminating a running process or application to free up system resources." [System Admin Fundamentals]

**11. WhoIs Lookup**
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Apply Weakness. If Social Class: Stun the target and Exhaust.
* **Upgrade Path:**
    * v2.0: Apply 2 Weakness. If Social: Stun.
    * v3.0: Apply 2 Weakness & Draw 1. If Social: Stun.
* **CyberDex:** "A query protocol used for accessing databases that store the registered users of an Internet resource." [RFC 3912]

**12. Backup Recovery**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Heal 10 HP. Remove 1 Debuff.
* **Upgrade Path:**
    * v2.0: Heal 15 HP. Remove 1 Debuff.
* **CyberDex:** "The copy of files and programs made to facilitate recovery, if necessary." [NIST SP 800-34]

---

## 2. Network Engineer Deck (Defense)
**Theme:** Tank / Sustainability.

### Attack Cards (Execute)

**13. IP Ban**
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal 5 Damage. If Network Class: Stun the target and Exhaust.
* **Upgrade Path:**
    * v2.0: Deal 8 Damage. If Network: Stun.
    * v3.0: Deal 11 Damage. If Network: Stun.
* **CyberDex:** "A security measure that prevents connection requests from a specific IP address." [NIST SP 800-61]

**14. Traffic Throttling**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal Damage equal to current Shield amount.
* **Upgrade Path:**
    * v2.0: Cost reduced to 1 RAM.
    * v3.0: Deal Damage equal to Shield + 5.
* **CyberDex:** "The intentional slowing of an internet service to regulate network traffic and minimize congestion." [FCC Rules]

**15. Sinkhole**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Deal 10 Damage. If enemy attacks next turn, Reflect 50% of damage.
* **Upgrade Path:**
    * v2.0: Deal 10 Damage. Reflect 100% of damage.
* **CyberDex:** "Redirecting malicious traffic to a specific server where it can be analyzed or discarded." [NIST SP 800-115]

**16. Packet Filter** (New!)
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal 6 Damage. If Network: Draw 2 Cards.
* **Upgrade Path:**
    * v2.0: Deal 9 Damage.
    * v3.0: Deal 12 Damage.
* **CyberDex:** "A firewall technique used to control network access by monitoring outgoing and incoming packets." [NIST SP 800-41]

**17. Flood Gate** (New!)
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Rare
* **Cost:** 2 RAM
* **Base Effect:** Deal 4 Damage to ALL enemies. If Network: Deal 12 Damage to ALL enemies.
* **Upgrade Path:** Read-Only.
* **CyberDex:** "A mechanism to control the volume of traffic allowed into a network segment to prevent congestion." [IETF RFC 4774]

### Defense Cards (Harden)

**18. Access Control List (ACL)**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Gain 15 Shield.
* **Upgrade Path:**
    * v2.0: Gain 20 Shield.
    * v3.0: Gain 25 Shield.
* **CyberDex:** "A list of permissions attached to an object, specifying which users are granted access." [NIST CSRC]

**19. VPN Tunnel**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Gain 8 Shield. Retain your hand (do not discard) for next turn.
* **Upgrade Path:**
    * v2.0: Gain 12 Shield. Retain hand.
* **CyberDex:** "A protected information system link utilizing tunneling and security controls." [NIST SP 800-77]

**20. Load Balancer**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. Gain +1 Energy next turn.
* **Upgrade Path:** Read-Only (No Upgrades).
* **CyberDex:** "A device that distributes network traffic across a number of servers to increase capacity." [CISA ST04-015]

**21. Geo-Blocking** (New!)
* **Category:** [Specialized] (Target: Network)
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. If Network: Dodge the next attack.
* **Upgrade Path:**
    * v2.0: Cost reduced to 0 RAM.
* **CyberDex:** "Technology that restricts access to internet content based upon the user's geographical location." [NIST SP 800-53]

### Utility Cards (Patch)

**22. Honeypot**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Taunt. Gain 20 Temporary HP (Enemy attacks this instead of you).
* **Upgrade Path:**
    * v2.0: Taunt. Gain 30 Temporary HP.
* **CyberDex:** "A system designed to be attractive to potential intruders, serving as a decoy." [NIST SP 800-83]

**23. Packet Sniffer**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 0 RAM
* **Base Effect:** Look at top 3 cards of draw pile. Discard any number of them.
* **Upgrade Path:**
    * v2.0: Look at top 4 cards. Discard any.
    * v3.0: Look at top 5 cards. Discard any.
* **CyberDex:** "Software that observes and records network traffic. Used for troubleshooting and analysis." [NIST SP 800-94]

**24. System Restore Point**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 3 RAM
* **Base Effect:** Heal 25 HP. Exhaust (Remove from deck).
* **Upgrade Path:** Read-Only (No Upgrades).
* **CyberDex:** "A feature that allows users to revert their computer's state to that of a previous point in time." [NIST SP 800-34]

---

## 3. Threat Hunter Deck (Attack)
**Theme:** Aggressive DPS / Malware Removal.

### Attack Cards (Execute)

**25. Heuristic Strike**
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal 10 Damage. If Malware Class: Deal 18 Damage.
* **Upgrade Path:**
    * v2.0: Deal 14 Damage (Bonus: 24).
    * v3.0: Deal 18 Damage (Bonus: 30).
* **CyberDex:** "Examining code for suspicious properties (heuristics) rather than looking for an exact signature match." [NIST SP 800-83]

**26. Quarantine**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Deal 8 Damage. Disable (Stun) target for 1 turn. Exhaust.
* **Upgrade Path:**
    * v2.0: Cost reduced to 1 RAM.
* **CyberDex:** "The process of isolating files to prevent the spread of malicious software." [NIST SP 800-61]

**27. Mass Purge**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Deal 6 Damage to ALL enemies.
* **Upgrade Path:**
    * v2.0: Deal 10 Damage to ALL enemies.
* **CyberDex:** "Sanitization: A process to render access to target data on the media infeasible." [NIST SP 800-88]

### Defense Cards (Harden)

**28. Sandbox Environment**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain 8 Shield. Draw 1 Card.
* **Upgrade Path:**
    * v2.0: Gain 11 Shield. Draw 1.
    * v3.0: Gain 14 Shield. Draw 1.
* **CyberDex:** "A restricted, controlled execution environment that prevents potentially malicious software from accessing system resources." [NIST SP 800-53]

**29. Kill Switch**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. If shield is broken, deal 10 Damage back.
* **Upgrade Path:**
    * v2.0: Gain 5 Shield. If broken, deal 18 Damage back.
* **CyberDex:** "A mechanism used to shut down or disable machinery or a program as quickly as possible." [CISA ICS Glossary]

**30. Code Signing** (New!)
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. If Malware: Gain 15 Shield.
* **Upgrade Path:**
    * v2.0: Gain 18 Shield.
    * v3.0: Gain 21 Shield.
* **CyberDex:** "Cryptographic technique to confirm the software author and guarantee the code has not been altered." [NIST CSRC]

### Utility Cards (Patch)

**31. Signature Update**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 2 RAM
* **Base Effect:** Gain +3 Strength (All attacks deal +3 Damage) for the rest of the battle.
* **Upgrade Path:** Read-Only (No Upgrades).
* **CyberDex:** "The process of updating the database of known malware signatures." [NIST SP 800-83]

**32. Decompile**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 0 RAM
* **Base Effect:** Apply 2 Vulnerable (Target takes +50% damage from next 2 hits).
* **Upgrade Path:**
    * v2.0: Apply 3 Vulnerable.
    * v3.0: Apply 3 Vulnerable & Draw 1.
* **CyberDex:** "The process of translating machine code back into source code to analyze the internal logic." [CISA Malware Analysis]

**33. Threat Intelligence**
* **Category:** [General]
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Scry 3 (Order top 3 cards). Gain 1 Energy.
* **Upgrade Path:**
    * v2.0: Scry 5. Gain 1 Energy.
    * v3.0: Scry 5. Gain 2 Energy.
* **CyberDex:** "Threat information that has been aggregated and analyzed to provide context for decision-making." [NIST SP 800-150]

**34. Sample Submission** (New!)
* **Category:** [Specialized] (Target: Malware)
* **Rarity:** Uncommon
* **Cost:** 0 RAM
* **Base Effect:** Deal 5 Damage. If Malware: Gain 2 Energy.
* **Upgrade Path:**
    * v2.0: Gain 3 Energy.
* **CyberDex:** "Sending suspicious files to a central authority or sandbox for automated analysis." [CISA Malware Analysis]

---

## 4. Pen Tester Deck (Control)
**Theme:** High Cost / High Impact.

### Attack Cards (Execute)

**35. SQL Injection**
* **Category:** [General] (Utility)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Deal 12 Damage. Tag: Decryption (This attack ignores Shields).
* **Upgrade Path:**
    * v2.0: Deal 16 Damage. Decryption.
    * v3.0: Deal 20 Damage. Decryption.
* **CyberDex:** "An attack technique used to exploit websites that construct SQL statements from user-supplied input." [MITRE T1190]

**36. Reverse Shell**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 3 RAM
* **Base Effect:** Deal 15 Damage. Gain +1 Energy next turn.
* **Upgrade Path:**
    * v2.0: Deal 20 Damage. Gain +2 Energy next turn.
* **CyberDex:** "A type of shell in which the target machine communicates back to the attacking machine." [CISA Malware Analysis]

**37. Exploit Kit**
* **Category:** [General] (Combo)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal 5 Damage. If Target has Status Effect (Weak/Stun): Deal 20 Damage.
* **Upgrade Path:**
    * v2.0: Deal 8 Damage (Bonus: 25).
    * v3.0: Deal 11 Damage (Bonus: 30).
* **CyberDex:** "A toolkit used by attackers to deliver a malicious payload by exploiting vulnerabilities." [NIST CSRC]

**38. Brute Force** (New!)
* **Category:** [Specialized] (Target: Crypto)
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Deal 10 Damage. If Crypto: This attack Ignores Defense (Shield Pierce).
* **Upgrade Path:**
    * v2.0: Deal 15 Damage.
* **CyberDex:** "An attack method involving an exhaustive procedure that tries all possibilities, one by one." [NIST CSRC]

### Defense Cards (Harden)

**39. Data Encryption**
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 2 RAM
* **Base Effect:** Gain 10 Shield. If Social Class: Reflect all damage.
* **Upgrade Path:**
    * v2.0: Gain 15 Shield. If Social: Reflect.
    * v3.0: Gain 20 Shield. If Social: Reflect.
* **CyberDex:** "The process of transforming information using an algorithm to make it unreadable." [NIST SP 800-111]

**40. IP Spoofing**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 1 RAM
* **Base Effect:** Gain 5 Shield. Dodge the next attack (Take 0 Damage).
* **Upgrade Path:**
    * v2.0: Cost reduced to 0 RAM.
* **CyberDex:** "The creation of Internet Protocol packets with a false source IP address." [NIST SP 800-61]

**41. Cold Storage** (New!)
* **Category:** [Specialized] (Target: Crypto)
* **Rarity:** Rare
* **Cost:** 2 RAM
* **Base Effect:** Gain 15 Shield. If Crypto: Retain your Shield for the next turn.
* **Upgrade Path:** Read-Only.
* **CyberDex:** "An offline wallet or storage system used for storing sensitive data, inaccessible from the internet." [CISA Security Tip]

### Utility Cards (Patch)

**42. Decryption Key**
* **Category:** [Specialized] (Target: Crypto)
* **Rarity:** Common
* **Cost:** 1 RAM
* **Base Effect:** Deal 5 Damage. If Crypto Class: Remove all Shields and Lock effects.
* **Upgrade Path:**
    * v2.0: Deal 10 Damage. Remove Shields/Lock.
    * v3.0: Deal 10 Damage. Remove Shields/Lock & Draw 1.
* **CyberDex:** "A string of bits used by a cryptographic algorithm to transform encrypted data back into original data." [NIST SP 800-57]

**43. Privilege Escalation**
* **Category:** [General]
* **Rarity:** Rare
* **Cost:** 0 RAM
* **Base Effect:** Lose 5 HP. Gain 2 Energy.
* **Upgrade Path:** Read-Only (No Upgrades).
* **CyberDex:** "Taking advantage of a bug or design flaw to gain elevated access to resources." [MITRE T1068]

**44. Social Engineering Toolkit (SET)**
* **Category:** [General]
* **Rarity:** Uncommon
* **Cost:** 2 RAM
* **Base Effect:** Apply Confused (Enemy attacks itself next turn).
* **Upgrade Path:**
    * v2.0: Cost reduced to 1 RAM.
* **CyberDex:** "An open-source penetration testing framework designed for social engineering attacks." [TrustedSec]

**45. Awareness Training** (New!)
* **Category:** [Specialized] (Target: Social)
* **Rarity:** Common
* **Cost:** 0 RAM
* **Base Effect:** Gain 1 Energy. If Social: Apply 2 Vulnerable.
* **Upgrade Path:**
    * v2.0: Apply 3 Vulnerable.
    * v3.0: Apply 3 Vulnerable & Draw 1.
* **CyberDex:** "Formal education provided to users to help them identify and prevent social engineering attacks." [NIST SP 800-50]
