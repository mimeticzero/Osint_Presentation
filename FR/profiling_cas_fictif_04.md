#  Rapport OSINT – [Client anonyme ayant commandé sur un site e-commerce suspect]

##  Date : 04/07/2025  
##  Contexte de la demande :
> Un utilisateur a passé commande sur le site `letempsdesfleurs.fr` pour un achat de fleurs en ligne. Après paiement et réception d’un e-mail de confirmation, aucune livraison n’a été effectuée et aucune réponse n’a été obtenue de la part du site. Le client cherche à savoir si le site est frauduleux, s’il usurpe l’identité d’une entreprise réelle ou s’il s’agit d’un simple cas de mauvaise gestion.

---

##  Sources utilisées :

- [x] Google / Bing / Dorks  
- [ ] Google Images, Yandex, TinEye  
- [ ] Réseaux sociaux (Facebook, Instagram, etc.)  
- [ ] HaveIBeenPwned / Leak databases  
- [x] Whois / Archive.org  
- [x] Cartographie (Street View, Rungis site)  
- [x] Outils spécifiques utilisés : Scamdoc, Societe.com, Rungis.fr, Whois

---

##  Résumé des résultats :

| Élément analysé         | Statut   | Commentaire court                                          |
|-------------------------|----------|-------------------------------------------------------------|
| Photo(s)                | N/A      | Aucun visuel de personne analysé                           |
| Réseaux sociaux         | 🔴        | Aucune présence officielle identifiée                      |
| E-mail / Username       | 🔴        | Aucun e-mail professionnel public visible                  |
| Ville / localisation    | 🟠        | Entreprise réelle située à Rungis, mais lien non vérifié   |
| Présence en ligne       | 🔴        | Aucune mention légale, site anonyme, incohérence B2B/B2C   |

---

##  Détails de l’enquête :

### 1.  Image(s) de profil
- Non applicable : aucun profil utilisateur ou identité visuelle de particulier lié à la cible.

### 2.  Réseaux sociaux
- Aucun compte Instagram, Facebook ou autre identifié comme officiel.
- Aucun lien vers des réseaux sociaux sur le site.

### 3.  Adresse e-mail / pseudo
- Aucun e-mail professionnel public identifié.
- Le formulaire de contact ne mentionne aucun SIRET, nom légal ou e-mail vérifiable.

### 4. 🗺 Localisation (si applicable)
- Recherche de l’entreprise homonyme sur le site du Marché International de Rungis :
  - Activité déclarée : **Commerce de gros (code NAF 46.22Z)**  
  - => Activité B2B, non destinée aux particuliers.
  - Pas de lien visible avec une activité e-commerce
- Aucun lien direct établi entre le site et l’entreprise référencée sur Societe.com.

### 5. 🗃 Autres informations trouvées
- Whois du domaine `letempsdesfleurs.fr` : informations partiellement masquées
- Scamdoc : note très faible (<30%), absence de mentions légales, nombreuses alertes d’utilisateurs
- Aucun historique sur Archive.org
- Aucune trace sur des annuaires officiels (pages jaunes, Rungis, etc.)

---

##  Hypothèse finale :

> Le site `letempsdesfleurs.fr` présente de nombreux signes de **fraude potentielle**.  
> Il semble exploiter le nom ou l’image d’une entreprise réelle en B2B (basée à Rungis), sans lien vérifié ni autorisé.  
> L’absence totale de mentions légales, le manque de réponse post-commande, et l’impossibilité de joindre un interlocuteur crédible renforcent l’hypothèse d’une **usurpation d’identité commerciale à des fins d’escroquerie**.

---

##  Recommandations :

- [x] Ne pas tenter de relancer le site ou ses contacts  
- [x] Signaler le site à : https://internet-signalement.gouv.fr  
- [x] Contacter la vraie entreprise référencée pour vérifier si elle est au courant  
- [x] Contacter sa banque pour engager une procédure de remboursement (CB, chargeback)  
- [ ] Optionnel : porter plainte pour tentative d’escroquerie

---

##  Annexes :

- `captures/` : captures du site, formulaire, confirmation de commande  
- `sources.txt` :  
  - https://letempsdesfleurs.fr  
  - https://www.rungisinternational.com  
  - https://www.societe.com  
  - https://www.scamdoc.com  
  - Whois (OVH / AFNIC)  
- `rapport.pdf` (à générer si besoin)  
- `data.json` : non fourni

---

##  Clause de responsabilité :

> Ce rapport repose uniquement sur l’analyse de données publiques accessibles légalement à la date de l’enquête.  
> Aucune interaction ou intrusion avec la cible n’a été effectuée.  
> Les conclusions ne constituent pas une preuve formelle, mais une synthèse informative destinée à aider à la décision.
