# Lytos

[![npm](https://img.shields.io/npm/v/lytos-cli)](https://www.npmjs.com/package/lytos-cli)

**Votre IA oublie tout. Lytos règle ça.** · **[Read in English 🇬🇧](https://github.com/getlytos/.github/blob/main/profile/README.md)**

---

### Le moment où tout bascule

Un développeur code avec un agent IA. Il explique sa stack, ses conventions, ses contraintes. L'IA produit du bon code. Session suivante — elle a tout oublié. Il réexplique. Encore. Et encore.

Alors il essaie un persona : *"Tu es un développeur Senior avec 15 ans d'expérience."* Le ton change. La qualité non. Un costume ne crée pas de la connaissance. C'est le contexte qui en crée.

Le problème n'est pas l'IA. C'est ce que l'IA sait quand elle commence à travailler.

> *"Un agent déguisé en senior dev ne connaît pas votre code. Il connaît le mot 'senior'."*

### Et si l'IA se souvenait ?

Chaque session commence avec la constitution du projet, les conventions de l'équipe, les décisions passées, le sprint en cours — chargés automatiquement, depuis des fichiers qui vivent dans le dépôt Git.

C'est Lytos. Pas un outil IA de plus. Une **méthode** qui structure ce dont n'importe quel agent IA a besoin pour faire son meilleur travail.

```bash
npm install -g lytos-cli && lyt init
```

Une commande. L'IA comprend le projet dès la première session.

---

**Sans Lytos :**
```
Dev : "On utilise Tailwind, pas CSS modules. Et on écrit les tests avant de commiter."
IA  : "Compris !" (jusqu'à la prochaine session, où elle oublie tout)
```

**Avec Lytos :**
```
L'IA lit .lytos/ au démarrage → stack, conventions, sprint, décisions passées.
Fini de réexpliquer. Une vraie session de travail dès la première ligne.
```

> *"L'agile a structuré la collaboration humaine. Lytos structure la collaboration avec l'IA."*

---

### Un projet ne devrait pas dépendre d'un modèle

Claude aujourd'hui. GPT demain. Gemini le mois prochain. Les modèles changent tous les 3-6 mois — les APIs évoluent, les prix bougent, des fonctionnalités disparaissent. Quand le contexte projet vit dans l'historique de chat d'un fournisseur, chaque changement signifie recommencer à zéro.

Tout dans Lytos est du **Markdown dans Git**. Le manifest, les rules, la memory — des fichiers texte que l'équipe possède, versionne, relit et migre librement. L'IA est un moteur. Les moteurs se changent. La fondation reste.

Ça tourne sur Claude Code aujourd'hui. Ça tournera sur ce qui sera le mieux demain. Le contexte ne bouge pas.

> *"Choisissez votre IA. Ne lui appartenez pas."*

---

### Trois chemins

**→ Essayer** — `npm install -g lytos-cli && lyt init`

**→ Apprendre en faisant** — [lytos-learn](https://github.com/getlytos/lytos-learn/blob/main/docs/README-fr.md) — un tutoriel guidé en 7 étapes

**→ Comprendre la méthode** — [lytos.org/fr](https://lytos.org/fr/)

**→ Pour les équipes et formateurs** — [Kit formateur](https://lytos.org/fr/philosophy/trainers/)

---

### Dépôts

| Dépôt | Description |
|-------|-----------|
| **[lytos-method](https://github.com/getlytos/lytos-method)** | La méthode — manifest, skills, rules, memory. Compatible tout outil IA |
| **[lytos-cli](https://github.com/getlytos/lytos-cli)** | Le CLI — `lyt init` · `lyt board` · `lyt lint` · `lyt doctor` · `lyt start` · `lyt close` |
| **[lytos-learn](https://github.com/getlytos/lytos-learn)** | Tutoriel pratique — apprendre Lytos en construisant une todo API |
| **[lytos-website](https://github.com/getlytos/lytos-website)** | Documentation — [lytos.org](https://lytos.org) |
