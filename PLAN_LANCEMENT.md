# PLAN DE LANCEMENT — Kaman Chantier
> De zéro à 100 abonnés payants en 90 jours

---

## 1. POSITIONNEMENT

**Phrase de positionnement :**
> Kaman Chantier est l'application qui met fin à l'argent de chantier qui disparaît : chaque dépense est justifiée par une photo de reçu, et le propriétaire à l'étranger voit son solde exact en temps réel.

**Slogan :** *« Ton argent construit. Tu le vois. »*

**Ennemi désigné (le vrai concurrent) :** pas une autre app — c'est **le cahier + WhatsApp + la confiance aveugle**. Toute la communication attaque ce système par défaut.

**Angle émotionnel :** on ne vend pas du "suivi de dépenses", on vend **la paix familiale** et **la maison terminée**. Le reçu photographié protège aussi le superviseur honnête — c'est l'argument qui désamorce le tabou de la méfiance.

---

## 2. PRICING (FCFA) — grille définitive

| Formule | Prix mensuel | Prix annuel (2 mois offerts) | Contenu |
|---|---|---|---|
| **Découverte** | 0 F / 30 jours | — | 1 chantier, 1 superviseur, tout illimité |
| **Bâtisseur** ⭐ | **5 000 F** (≈ 8 $ / 7,60 €) | 50 000 F | 1 chantier, 2 superviseurs, reçu obligatoire, verrouillage 24 h, devise $/€ |
| **Sérénité** | **12 500 F** (≈ 20 $ / 19 €) | 125 000 F | 3 chantiers, superviseurs illimités, rapport PDF mensuel, accès famille en lecture, support prioritaire |

**Justification du pricing :**
- 5 000 F/mois = **moins d'un sac de ciment** — c'est l'ancre de comparaison à marteler partout
- Le client raisonne en $/€ : 8 $/mois est psychologiquement « le prix d'un menu fast-food » pour protéger 20-50 millions FCFA
- L'annuel (2 mois offerts) est l'offre à pousser : un chantier dure 12-24 mois, l'engagement annuel colle au cycle de vie et sécurise ta trésorerie
- Encaissement : Wave / Orange Money (payeur au pays) + carte / PayPal (diaspora). En V1, encaissement **manuel via WhatsApp** — pas besoin d'intégrer un paiement en ligne pour vendre les 50 premiers abonnements

**Objectif 90 jours :** 100 abonnés Bâtisseur = **500 000 F/mois récurrents** (~6 M F/an), avec un produit à coût marginal quasi nul (quotas Firebase).

---

## 3. LANDING PAGE (livrée : `index.html`)

- **Héro :** promesse + le "ticket de vérité" (Envoyé / Dépensé / Solde + reçus photographiés) — le produit démontré en 3 secondes
- **Structure :** douleur → fonctionnement en 3 étapes → fonctionnalités → tarifs → FAQ (objections traitées : superviseur peu technophile, pas de réseau, tensions familiales, paiement depuis l'étranger) → CTA WhatsApp
- **CTA unique :** « Démarrer sur WhatsApp » — en V1 tu closes à la main, chaque conversation est une mine d'insights
- **À faire avant mise en ligne :**
  1. Remplacer `wa.me/22500000000` par ton vrai numéro WhatsApp Business (2 occurrences)
  2. Déployer sur Vercel (glisser le fichier ou repo GitHub) — domaine conseillé : `kamanchantier.com` (~10 000 F/an)
  3. Ajouter le pixel Meta dès la semaine 2 (retargeting des visiteurs)

---

## 4. ACQUISITION — 4 canaux, dans l'ordre

### Canal 1 — Ton réseau Dallas (semaines 1-2, coût : 0 F)
Ton avantage injuste : **La Famille WE** et les églises de la diaspora à Dallas.
- Présentation de 10 min lors d'une réunion de l'association : démo live du ticket de vérité
- Offre fondateurs : **6 mois à -50 % (2 500 F/mois) pour les 20 premiers** contre un témoignage
- Objectif : 10-15 abonnés fondateurs + 3 témoignages vidéo (smartphone suffit)

### Canal 2 — Groupes Facebook diaspora (semaines 2-6, coût : 0 F)
Groupes cibles : « Ivoiriens de Dallas/Texas », « Ivoiriens de France », « Diaspora ivoirienne », « Construire en Côte d'Ivoire », groupes immobilier CI.
- **Ne jamais spammer le lien.** Poster des histoires : « Il a envoyé 14 millions, la maison est restée aux fondations » + question ouverte. Le lien vient en commentaire quand on te le demande
- 3 posts/semaine en alternant : histoire vécue / conseil chantier / capture du produit

### Canal 3 — Contenu vidéo Reels & TikTok (continu, coût : 0 F)
Formats courts avec ta stack habituelle (CapCut, HeyGen si besoin) :
- **« L'appel »** (sketch, 30 s) : « Grand frère, envoie encore 500 000 » / « C'est parti où ? » / « Aaah, fais-moi confiance non ! » → coupe → écran du solde Kaman. C'est LE format viral de ce marché
- **Démo 60 s :** le superviseur photographie un reçu → le téléphone à Dallas vibre → le solde se met à jour
- **Témoignage fondateur** face caméra
- Cadence : 3 vidéos/semaine, republiées sur la page Abidjan Digital.ia (synergie avec ta stratégie de monétisation Facebook)

### Canal 4 — Prescripteurs (mois 2-3)
- **Entreprises de BTP et tâcherons sérieux** : Kaman comme argument commercial (« travaillez avec moi, tout est transparent ») → commission 20 % sur la 1re année de chaque abonné apporté
- **Agences de transfert d'argent communautaires à Dallas** : flyer au comptoir — leur client type est exactement ta cible
- **Pasteurs / leaders communautaires** : le thème « paix des familles » résonne fort en milieu chrétien — tu sais faire

---

## 5. SCRIPT DE PROSPECTION WhatsApp (copier-coller)

**Message d'ouverture (contact tiède, diaspora) :**
> Bonjour [Prénom] 🙏 Petite question : est-ce que tu construis ou comptes construire au pays ? Je lance une application qui règle le problème que tout le monde connaît — l'argent envoyé pour le chantier dont on ne voit jamais les reçus. Chaque dépense est justifiée par une photo, et tu vois ton solde exact depuis [Dallas/Paris] en temps réel. Je cherche 20 membres fondateurs à -50 %. Je t'envoie la démo de 60 secondes ?

**Relance J+3 (si vu sans réponse) :**
> [Prénom], je te partage juste ceci 👇 [vidéo sketch « L'appel »]. Si tu connais quelqu'un qui construit au pays, transfère-lui — ça peut lui éviter beaucoup de palabres 😅

**Closing (après la démo) :**
> Voici l'offre fondateur : 30 jours gratuits, puis 2 500 F/mois pendant 6 mois (au lieu de 5 000). Tu installes, tu invites ton superviseur avec un code à 6 chiffres, et je t'accompagne personnellement au démarrage. On lance ton chantier dessus cette semaine ?

---

## 6. CALENDRIER 90 JOURS

| Phase | Semaines | Actions | Objectif |
|---|---|---|---|
| **Préparation** | S1-S2 | Finaliser MVP (CLAUDE.md → Claude Code), déployer landing, numéro WhatsApp Business, tourner 3 premières vidéos | Produit + vitrine prêts |
| **Fondateurs** | S3-S4 | Présentation La Famille WE, prospection WhatsApp réseau perso (50 contacts), onboarding manuel de chaque fondateur | 15 abonnés fondateurs |
| **Preuve sociale** | S5-S8 | 3 témoignages vidéo, publication groupes Facebook, cadence Reels ×3/sem, pixel Meta installé | 40 abonnés, 1re vidéo >10 k vues |
| **Accélération** | S9-S12 | Programme prescripteurs BTP, pub Meta ciblée diaspora (10 000-15 000 F/sem, audiences : expatriés CI aux USA/France, intérêts immobilier), rapport PDF mensuel livré (feature Sérénité) | **100 abonnés payants** |

**Indicateurs à suivre chaque semaine :** conversations WhatsApp ouvertes → démos faites → essais activés → conversions payantes (viser 30 % essai→payant grâce à l'onboarding manuel).

---

## 7. RISQUES & PARADES

| Risque | Parade |
|---|---|
| Le superviseur refuse d'utiliser l'app | Le propriétaire paie et impose ; vidéo de formation 3 min ; interface 3 boutons ; argument « le reçu te protège toi aussi » |
| Churn en fin de chantier | Pousser l'annuel ; à la livraison, proposer Mon Loyer (la maison finie devient un bien à louer → pipeline naturel entre tes deux produits) |
| Copie par un concurrent | La barrière n'est pas technique : c'est la communauté diaspora + les témoignages + la marque. Avance vite sur le contenu |
| Encaissement international | V1 : Wave via un proche au pays + PayPal manuel. V2 : Stripe/CinetPay |

---

## 8. CHECKLIST IMMÉDIATE (cette semaine)

- [ ] Générer le MVP avec `CLAUDE_Kaman_Chantier.md` dans Claude Code
- [ ] Acheter le domaine + déployer `index.html` sur Vercel
- [ ] Remplacer le numéro WhatsApp dans la landing (2 endroits)
- [ ] Créer le WhatsApp Business « Kaman Chantier » avec message d'accueil automatique
- [ ] Tourner le sketch « L'appel » (30 s) et la démo (60 s)
- [ ] Lister 50 contacts diaspora et envoyer le message d'ouverture
- [ ] Caler la présentation La Famille WE
