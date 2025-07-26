
# OSINT Report – Analysis of Redirection to OnlyFans Content

## Date: 06/30/2025

---

## Context of the Request

Analysis of an Instagram DM received from the account `@hannah.guy_ig`, suspected to be part of a network of fake profiles used to promote an OnlyFans account.

---

## 1. Information Received

**Message received:**  
`"Did you see @its.hazeldee? The hottest model I've seen out there.. ✨ To be honest, I think you got all your chances!"`

---

## 2. Profile Investigation

###  `@hannah.guy_ig`
- Public account  
- 400 followers / 800 following (mostly male users)  
- Last visible post: 206 weeks ago (~4 years)  
- Recent activity only through private messages  
- Bio: empty or missing  

**→ Hypothesis:** Dormant account used exclusively for automated DMs

###  `@its.hazeldee`
- 35,000 followers / 282 following (almost exclusively female)
- Last post: 27 weeks ago (~6 months)
- OnlyFans link in bio
- Mostly male audience
- Low interaction: no recent stories or replies

###  `@its_hazeldee`
- Secondary version: same photos, same name style
- 8,000 followers
- Same OnlyFans link
- Similar follower/following pattern

---

## 3. Target Platform

**OnlyFans: `hazel_dee`**
- Active account, online at the time of analysis
- Linked from both Instagram profiles

---

## 4. Connection Visualization

*See attached Maltego graph:*  
![Capture d'écran 2025-07-01 222542](https://github.com/user-attachments/assets/2cb98b86-717c-4b5a-8607-93415d3f4fba)


---

## 5. Instagram Account Analysis

- `@hannah.guy_ig` is inactive publicly for over 200 weeks but used as a **DM bait**
- `@its.hazeldee` and `@its_hazeldee` show:
  - **Identical visuals**
  - **Same audience targeting (men)**
  - A single redirection path to **OnlyFans commercial content**

**→ It is highly likely that this structure forms a semi-automated promo network**, built around:
- Recycled dormant accounts
- Variants of attractive female profiles
- Funnel logic: DM → dual profile → paid content

---

## 6. Conclusion

All indicators suggest that `@hannah.guy_ig` is used in an aggressive marketing or social spam strategy, directing traffic to a legitimate OnlyFans account (`hazel_dee`).

While no direct financial scam was identified, the multi-profile funnel and DM tactics imply an **automated network** that may be replicated across other platforms or profiles.

---

## 7. Recommendations

-  Do not engage with these accounts
-  Report to Instagram as spam or fraudulent redirection
-  Block accounts if additional DMs are received
-  Archive this case as an OSINT example of “recycled passive profiles”

---

## Attachments

- https://www.instagram.com/hannah.guy_ig/  
- https://www.instagram.com/its.hazeldee/  
- https://www.instagram.com/its_hazeldee/  
- https://onlyfans.com/hazel_dee

---

## Legal Disclaimer

> This report is based solely on publicly accessible data at the time of investigation.  
> No direct interaction, intrusion, or manipulation was performed.  
> This document is provided for informational purposes only and does not constitute legal evidence.
