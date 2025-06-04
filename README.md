# kexporter

> 🧾 Exportateur de salons ou fils Discord au format HTML, avec rendu fidèle à l'interface Discord.  
> 🧾 Export Discord channels or threads to HTML, with a layout close to Discord's UI.

![PyPI](https://img.shields.io/pypi/v/kexporter?style=flat-square&color=0a7cdb)
![Code Usage](https://img.shields.io/badge/code%20used-90%%25-0a7cdb?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/ton-user/kexporter?style=flat-square&color=0a7cdb)
![GitHub forks](https://img.shields.io/github/forks/ton-user/kexporter?style=flat-square&color=0a7cdb)
![Downloads](https://img.shields.io/pypi/dt/kexporter?style=flat-square&color=0a7cdb)
![License](https://img.shields.io/badge/license-GPL--3.0-0a7cdb?style=flat-square)
![Issues](https://img.shields.io/github/issues/ton-user/kexporter?style=flat-square&color=0a7cdb)

---

## 🇫🇷 À propos

`kexporter` est un module Python qui permet d’exporter des messages de salons ou de fils Discord vers un fichier HTML statique, visuellement proche de l’interface réelle de Discord.

Il est utile pour :
- archiver des conversations importantes ;
- créer des rapports client / ticket ;
- documenter des échanges dans un format lisible hors ligne.

---

## 🇬🇧 About

`kexporter` is a Python module that exports messages from Discord channels or threads into a static HTML file, visually similar to Discord's native interface.

Useful for:
- archiving important discussions;
- generating client or ticket transcripts;
- creating offline-readable message logs.

---

## 📦 Installation

**PyPI:**

```bash
pip install kexporter
```

**TestPyPI:**

```bash
pip install --index-url https://test.pypi.org/simple/ --extra-index-url https://pypi.org/simple kexporter
```

---

## ⚙️ Utilisation / Usage

```python
from kexporter import export

# Exemple fictif / Example usage
await export(channel, output_path="transcript.html")
```

⚠️ Ton bot Discord doit avoir la permission de lire l'historique.  
⚠️ Your bot must have permission to read message history.

---

## ✅ Fonctionnalités / Features

- ✅ Export HTML statique / Static HTML export
- 🖼️ Avatars et pseudos / Avatars and usernames
- 🕒 Horodatage des messages / Timestamped messages
- 🎨 Rendu fidèle à Discord / Discord-like layout
- 📎 Pièces jointes supportées (optionnel) / Attachment support (optional)
- 🔧 Facilement intégrable / Easy to integrate

---

## 🖼️ Aperçu / Preview

*(Ajoutez une capture ici / Add a screenshot here)*  
`transcript.html`

---

## 🔧 Dépendances / Dependencies

- `discord.py >= 2.0`
- `jinja2 >= 3.0`

---

## 📄 Licence / License

**GPL v3.0 - Licence libre avec obligation de partage à l’identique**  
**GPL v3.0 - Free license with copyleft clause**

> Ce logiciel est distribué sous la licence GNU GPL v3. Toute redistribution, modification ou intégration dans un autre projet **doit mentionner l’auteur original** et conserver la même licence (GPL v3 ou compatible).  
> This software is licensed under the GNU GPL v3. Any redistribution, modification, or integration into another project **must credit the original author** and preserve the same license (GPL v3 or compatible).

🔗 [Texte complet de la licence](https://www.gnu.org/licenses/gpl-3.0.fr.html)

---

## 🙋‍♂️ Auteur / Author

Développé par [Kushh](https://github.com/itsKushh)  
Developed by [Kushh](https://github.com/itsKushh)

Contact : [its.kushh.dev@gmail.com](mailto:its.kushh.dev@gmail.com)

---

## 💡 Contribuer / Contributing

Les pull requests sont bienvenues ! Forkez le projet et proposez vos idées.  
Pull requests are welcome! Fork the project and share your ideas.
