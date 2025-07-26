#  Rapport OSINT – [Candidat(e) anonyme ayant postulé à une offre en ligne]

##  Date : 04/07/2025  
##  Contexte de la demande :
> Un utilisateur souhaite vérifier la légitimité d’un site web (`affinita.agency`) sur lequel il a postulé à une offre d’emploi. Il a communiqué ses informations personnelles (nom, ville, âge) mais n’a reçu qu’une réponse vague. Le doute persiste quant à une éventuelle arnaque ou usurpation.

---

##  Sources utilisées :

- [x] Google / Bing / Dorks  
- [ ] Google Images, Yandex, TinEye  
- [ ] Réseaux sociaux (Facebook, Instagram, etc.)  
- [x] HaveIBeenPwned / Leak databases  
- [x] Whois / Archive.org  
- [ ] Cartographie (Maps, Street View, SunCalc)  
- [x] Outils spécifiques utilisés : Maltego CE, Scamdoc, Reddit, Scamadviser

---

##  Résumé des résultats :

| Élément analysé         | Statut   | Commentaire court                                       |
|-------------------------|----------|----------------------------------------------------------|
| Site web                | 🔴        | Domaine récent, pas de mentions légales                 |
| E-mail lié              | 🔴        | Adresse masquée via PrivacyProtect.org                  |
| IP / hébergeur          | 🟠        | Serveur basé en Ukraine, peu de transparence            |
| Entreprise mentionnée   | 🔴        | Aucune preuve de lien avec une société enregistrée      |
| Réputation en ligne     | 🔴        | Témoignages Reddit évoquant une arnaque à l’emploi      |

---

##  Détails de l’enquête :

### 1.  Image(s) de profil
- Non applicable (pas d’image de personne ou de profil social analysé)

### 2.  Réseaux sociaux
- Aucun réseau social identifié lié au domaine
- Aucune page officielle ou activité sociale trouvée

### 3.  Adresse e-mail / pseudo
- Adresse WHOIS : `aaaffb5c05e70717ca@privacyprotect.org`
- Adresse anonymisée, non liée à une entreprise identifiable
- Aucun lien trouvé dans les bases de données publiques connues

### 4. 🗺 Localisation (si applicable)
- IP du site hébergée en Ukraine (Kyiv)
- Aucune mention géographique sur le site lui-même
- Aucun lien géographique avec l’identité utilisée

### 5.  Autres informations trouvées
- Le site n’affiche aucune **mention légale**, ni coordonnées
- Le nom de domaine a été enregistré récemment (2024)
- Sur Reddit, plusieurs témoignages évoquent une arnaque à l’emploi utilisant un faux job dans la tech/dating
- Le nom est très proche d’une entreprise légitime (“Affinità”) mais sans lien direct ni preuve d’affiliation

---

##  Hypothèse finale :

> Le site `affinita.agency` présente des éléments caractéristiques d’un site frauduleux.  
> Il utilise un design professionnel et une marque ressemblant à une entreprise réelle pour inspirer confiance, mais **aucun élément légal, structurel ou numérique ne permet de confirmer son authenticité**.  
> **Forte probabilité de tentative de collecte de données personnelles à des fins frauduleuses** (type arnaque à l’emploi).

---

##  Recommandations :

- [x] Ne plus fournir d’informations personnelles  
- [x] Signaler le site aux autorités compétentes (ex : internet-signalement.gouv.fr)  
- [x] Surveiller toute tentative de contact ultérieure (e-mail, SMS, téléphone)  
- [ ] (Optionnel) Porter plainte en cas d’usage abusif des données transmises

---

##  Annexes :

- `captures/` : Captures du site (page d’accueil, formulaire, absence de mentions légales)  
- `sources.txt` :  
  - https://affinita.agency  
  - https://scamadviser.com/check-website/affinita.agency  
  - https://www.reddit.com/r/Scams/comments/1lrqe9e/recently_applied_for_a_job_looks_very_sketchy/  
  - Whois via Maltego  
- `rapport.pdf` : Export sur demande  
- `data.json` : (non fourni)

---

##  Clause de responsabilité :

> Ce rapport repose uniquement sur l’analyse de données publiques accessibles légalement à la date de l’enquête.  
> Aucune interaction ou intrusion avec la cible n’a été effectuée.  
> Les conclusions ne constituent pas une preuve formelle, mais une synthèse informative destinée à aider à la décision.
