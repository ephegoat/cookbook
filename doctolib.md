# Risk Assessment of Cyber Security Framework by Doctolib

*This slide is 100% editable. Adapt it to your needs and capture your audience’s attention.*

| Individual Function Area – Subject Matter Experts Score their Functional Areas Based on Organization Structure | Scores – SME Scores Compared Against Independent Core Group | Result – Combine Scores and Compare Against Targets Set by Organization |
|-------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------|--------------------------------------------------------------------------|
| **Area 1 (I.E., Policy)**<br>**Area 2 (I.E., Network)**<br>**Area 3 (I.E., Applications)**                   | **SME Average**<br>**Core Group**<br>**Combined**          | **Tier Target**<br>**Risk Gap**                                          |

| **Identify**          |       |       |       |       |       |       |       |       |
|-----------------------|-------|-------|-------|-------|-------|-------|-------|-------|
| Business              | 4     | 4     | 4     | 4     | 4     | 4     | 4     | 0     |
| Asset                 | 3     | 3     | 3     | 3     | 3     | 3     | 4     | 1     |
| Governance            | 4     | 4     | 4     | 4     | 4     | 4     | 4     | 0     |
| Risk Asses            | 3     | 3     | 2     | 3     | 3     | 3     | 4     | 1     |
| Risk Management       | 4     | 4     | 4     | 4     | 4     | 4     | 4     | 0     |
| **Protect**           |       |       |       |       |       |       |       |       |
| Protect               | 2     | 2     | 2     | 2     | 2     | 2     | 4     | 2     |
| **Detect**            |       |       |       |       |       |       |       |       |
| Detect                | 3     | 3     | 3     | 3     | 3     | 3     | 4     | 1     |
| **Respond**           |       |       |       |       |       |       |       |       |
| Respond               | 2     | 2     | 2     | 2     | 2     | 2     | 4     | 2     |
| **Recover**           |       |       |       |       |       |       |       |       |
| Recover               | 4     | 4     | 4     | 4     | 4     | 4     | 4     | 0     |

---

### Légende des couleurs et niveaux (Tier)

- **Green – All OK**: Score = Tier Target (aucun écart)
- **Yellow – Area Needs Work**: Score < Tier Target (écart de 1)
- **Red – Close Analysis And Correction**: Score << Tier Target (écart de 2 ou plus)

---

### Définition des Tiers

- **Tier 1 - Partial**: Processus non formalisés ou partiellement documentés.
- **Tier 2 - Risk Informed**: Processus documentés, basés sur des risques identifiés.
- **Tier 3 - Repeatable**: Processus standardisés et répétés dans l’organisation.
- **Tier 4 - Adaptive**: Processus optimisés, adaptatifs et intégrés à la stratégie globale.

---

### Explication des scores (basée sur l'analyse CyberScor)

- **Identify (Business, Asset, Governance, etc.)** : Bonne gouvernance et gestion des actifs, mais absence de `security.txt` → **Asset = 3**, **Risk Asses = 3**.
- **Protect** : **CSRF_protection = False** et **Secure_cookie_flag = 0** → **Score critique : 2/4**.
- **Detect** : Présence de Sentry + Datadog → bonne visibilité → **Score = 3**.
- **Respond** : Absence de fichier `security.txt` → canal de signalement non officiel → **Score = 2**.
- **Recover** : Hébergement HDS + architecture Cloudflare → **Score = 4**.