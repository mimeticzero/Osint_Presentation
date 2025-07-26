
#  OSINT Report – [Anonymous job applicant]

##  Date: 07/04/2025  
##  Case overview:
> The subject submitted an application to a website (`affinita.agency`) advertising a remote job opportunity. Personal details were shared (name, age, city), but the subject received only vague responses and became suspicious. The objective was to verify the legitimacy of the site and assess the risk of fraud or data misuse.

---

##  Sources used:

- [x] Google / Bing / Dorks  
- [ ] Google Images, Yandex, TinEye  
- [ ] Social Media (Facebook, Instagram, etc.)  
- [x] HaveIBeenPwned / Leak databases  
- [x] Whois / Archive.org  
- [ ] Mapping (Maps, Street View, SunCalc)  
- [x] Specialized tools: Maltego CE, Scamdoc, Reddit, Scamadviser

---

##  Summary of findings:

| Analyzed element        | Status   | Short comment                                       |
|-------------------------|----------|-----------------------------------------------------|
| Website                 | 🔴        | Recently registered, no legal notices              |
| Associated email        | 🔴        | Masked via PrivacyProtect service                  |
| Hosting/IP              | 🟠        | Server located in Ukraine, limited transparency    |
| Referenced company      | 🔴        | No confirmed connection with legitimate business   |
| Online reputation       | 🔴        | Reddit reports suggest recruitment scam pattern    |

---

##  Investigation details:

### 1. Profile picture(s)
- Not applicable – no personal images or avatars involved.

### 2.  Social media presence
- No official or personal social profiles found linked to the domain.
- No company social accounts detected.

### 3. Email / username
- WHOIS contact: `aaaffb5c05e70717ca@privacyprotect.org`
- Email is anonymized, commonly seen in domain registrations using privacy shields.
- No leaks or matches found in public databases.

### 4. Geolocation (if applicable)
- IP geolocated to Ukraine (Kyiv)
- Website does not mention any specific address, country, or legal entity.
- No geographic correlation with the applicant.

### 5. Additional intelligence
- No legal notice or company identification on the site (in violation of EU regulations)
- Domain is new (registered in 2024) and protected via privacy services
- Reddit thread reports a nearly identical case of suspected employment scam linked to the same domain
- The domain name resembles an actual company ("Affinità") but with no verifiable link

---

## Final assessment:

> The site `affinita.agency` exhibits multiple red flags commonly associated with **employment fraud or data harvesting schemes**.  
> While visually professional, it lacks any legal disclosures, confirmed business registration, or traceable online identity.  
> The evidence strongly suggests a **fake recruitment site leveraging brand confusion and anonymity to gather personal data**.

---

## Recommendations:

- [x] Do not share any further personal information  
- [x] Report the site to relevant authorities (e.g. internet-signalement.gouv.fr or Pharos)  
- [x] Monitor inbox and phone for suspicious contact attempts  
- [ ] (Optional) File a police complaint if data misuse is suspected

---

## Attachments:

- `captures/` : Screenshots of website (homepage, job form, lack of legal pages)  
- `sources.txt` :  
  - https://affinita.agency  
  - https://scamadviser.com/check-website/affinita.agency  
  - https://www.reddit.com/r/Scams/comments/1lrqe9e/recently_applied_for_a_job_looks_very_sketchy/  
  - Whois data via Maltego  
- `report.pdf` : Available on request  
- `data.json` : Not provided

---

## Disclaimer:

> This report is based solely on publicly available, legally accessible information at the time of the investigation.  
> No direct interaction or intrusion with the target was performed.  
> The conclusions are not legally binding and are meant as informational guidance only.
