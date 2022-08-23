<div align="center">
"Jesus said to him, I am the way, the truth, and the life: no man comes to the Father, but by me." - John 14:6 (AKJV)
</div>

<hr>

<div align="center">
    <a href="https://github.com/0xR3V/Bibles#introduction">Introduction</a>
    -
    <a href="https://github.com/0xR3V/Bibles#a-list-of-all-the-bibles">A List of All the Bibles</a>
    -
    <a href="https://github.com/0xR3V/Bibles#special-thanks">Special Thanks</a>
    -
    <a href="https://github.com/0xR3V/Bibles#contact-me">Contact Me</a>
</div>

# Introduction
This repository contains **Public Domain** bibles in different languages and versions written in groff mom syntax.

There is a directory for each language, as well as a sub-directory for each version of that language.

Each version includes 3 directories and 2 files:
- **The New Testament**
- **The Old Testament**
- **The Old Testament & The New Testament**
- **LICENSE**
- **SKIPTOCENTRY.mom** - Introducing a new macro to skip a specific entry heading level in the table of content in `stylesheet.mom`.

Each directory with 4 files:
- **stylesheet.mom** - where all styling will take place.
- Pre-generated **PDF** file.
- A file containing bible content written in mom syntax.
- **README.md**

Here's an example:
```txt
English
└── Bible in Basic English (BBE)
   ├── The New Testament
   │  ├── BBE-the-new-testament.mom
   │  ├── BBE-the-new-testament.pdf
   │  ├── README.md
   │  └── stylesheet.mom
   ├── The Old Testament
   │  ├── BBE-the-old-testament.mom
   │  ├── BBE-the-old-testament.pdf
   │  ├── README.md
   │  └── stylesheet.mom
   ├── The Old Testament & The New Testament
   │  ├── BBE.mom
   │  ├── BBE.pdf
   │  ├── README.md
   │  └── stylesheet.mom
   ├── LICENSE
   └── SKIPTOCENTRY.mom
```

The **PDF** file is generated using `stylesheet.mom`, and the default design in `stylesheet.mom` is for **A5** papers. Also you can change every detail in `stylesheet.mom`,  such as the paper size to **A4** or **LETTER**.
However, before making any changes, consult first mom's documentation. More information can also be found in `stylesheet.mom`


# A List of All the Bibles
- [ ] العربية (Arabic) (AR)
	- [ ] الكتاب المقدس - فان دايك (SVD)
- [ ] English (EN)
	- [x] A Conservative Version (ACV)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/A%20Conservative%20Version%20(ACV)/The%20New%20Testament/ACV-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/A%20Conservative%20Version%20(ACV)/The%20Old%20Testament/ACV-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/A%20Conservative%20Version%20(ACV)/The%20Old%20Testament%20%26%20The%20New%20Testament/ACV.pdf">Download The Old Testament \& The New Testament</a>
	- [ ] Aionian Bible
	- [x] American King James Version (AKJV)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/American%20King%20James%20Version%20(AKJV)/The%20New%20Testament/AKJV-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/American%20King%20James%20Version%20(AKJV)/The%20Old%20Testament/AKJV-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/American%20King%20James%20Version%20(AKJV)/The%20Old%20Testament%20%26%20The%20New%20Testament/AKJV.pdf">Download The Old Testament \& The New Testament</a>
	- [ ] American Standard Version (ASV)
	- [x] Bible in Basic English (BBE)
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Bible in Basic English (BBE)/The New Testament/BBE-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Bible%20in%20Basic%20English%20(BBE)/The%20Old%20Testament/BBE-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Bible%20in%20Basic%20English%20(BBE)/The%20Old%20Testament%20%26%20The%20New%20Testament/BBE.pdf">Download The Old Testament \& The New Testament</a>
	- [x] Darby Translation (DARBY)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/Darby%20Translation%20(DARBY)/The%20New%20Testament/DARBY-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/Darby%20Translation%20(DARBY)/The%20Old%20Testament/DARBY-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/English/Darby%20Translation%20(DARBY)/The%20Old%20Testament%20%26%20The%20New%20Testament/DARBY.pdf">Download The Old Testament \& The New Testament</a>
	- [ ] Douay-Rheims 1899 American Edition (DRA)
	- [ ] Geneva Bible 1599
	- [x] King James Version (KJV)
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/King%20James%20Version%20(KJV)/The%20New%20Testament/KJV-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/King%20James%20Version%20(KJV)/The%20Old%20Testament/KJV-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/King%20James%20Version%20(KJV)/The%20Old%20Testament%20%26%20The%20New%20Testament/KJV.pdf">Download The Old Testament \& The New Testament</a>
	- [ ] Montgomery New Testament (MNT)
	- [ ] Revised King James New Testament (RKJNT)
	- [ ] The Emphasized Bible by J. B. Rotherham (Rotherham)
	- [ ] The Living Oracles NT (TLO)
	- [ ] Twentieth Century New Testament (TCNT)
	- [x] Updated King James Version (UKJV)
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Updated%20King%20James%20Version%20(UKJV)/The%20New%20Testament/UKJV-the-new-testament.pdf">Download The New Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Updated%20King%20James%20Version%20(UKJV)/The%20Old%20Testament/UKJV-the-old-testament.pdf">Download The Old Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/English/Updated%20King%20James%20Version%20(UKJV)/The%20Old%20Testament%20%26%20The%20New%20Testament/UKJV.pdf">Download The Old Testament \& The New Testament</a>
	- [ ] Webster Bible
	- [ ] Weymouth NT 1912 (Weymouth)
	- [ ] World English Bible (WEB)
	- [ ] World Messianic Bible
	- [ ] Young's Literal Translation (YLT)
- [ ] Español (Spanish) (ES)
	- [x] Reina-Valera Antigua (RVA)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Espa%C3%B1ol%20(Spanish)/Reina-Valera%20Antigua%20(RVA)/Nuevo%20Testamento%20(The%20New%20Testament)/RVA-nuevo-testamento.pdf">Descarga Nuevo Testamento</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Espa%C3%B1ol%20(Spanish)/Reina-Valera%20Antigua%20(RVA)/Viejo%20Testamento%20(The%20Old%20Testament)/RVA-viejo-testamento.pdf">Descarga Viejo Testamento</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Espa%C3%B1ol%20(Spanish)/Reina-Valera%20Antigua%20(RVA)/Viejo%20Testamento%20y%20Nuevo%20Testamento%20(The%20Old%20Testament%20%26%20The%20New%20Testament)/RVA.pdf">Descarga Viejo Testamento y Viejo Testamento</a>
	- [ ] Versión Biblia Libre
- [x] Français (French) (FR)
	- [x] La Sainte Bible
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/Fran%C3%A7ais%20(French)/La%20Sainte%20Bible/Nouveau%20Testament%20(The%20New%20Testament)/fra_fob-nouveau-testament.pdf">Télécharger Le Nouveau Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/Fran%C3%A7ais%20(French)/La%20Sainte%20Bible/L'Ancien%20Testament%20(The%20Old%20Testament)/fra_fob-l'ancien-testament.pdf">Télécharger L'Ancien Testament</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/Fran%C3%A7ais%20(French)/La%20Sainte%20Bible/L'Ancien%20Testament%20et%20Nouveau%20Testament%20(The%20Old%20Testament%20%26%20The%20New%20Testament)/fra_fob.pdf">Télécharger L'Ancien Testament et Le Nouveau Testament</a>
	- [x] Louis Segond (LSG)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Fran%C3%A7ais%20(French)/Louis%20Segond%20(LSG)/Nouveau%20Testament%20(The%20New%20Testament)/LSG-nouveau-testament.pdf">Télécharger Le Nouveau Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Fran%C3%A7ais%20(French)/Louis%20Segond%20(LSG)/L'Ancien%20Testament%20(The%20Old%20Testament)/LSG-l'ancien-testament.pdf">Télécharger L'Ancien Testament</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Fran%C3%A7ais%20(French)/Louis%20Segond%20(LSG)/L'Ancien%20Testament%20et%20Nouveau%20Testament%20(The%20Old%20Testament%20%26%20The%20New%20Testament)/LSG.pdf">Télécharger L'Ancien Testament et Le Nouveau Testament</a>
- [x] Italiano (Italian) (IT)
	- [x] Conferenza Episcopale Italiana (CEI)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Italiano%20(Italian)/Conferenza%20Episcopale%20Italiana%20(CEI)/Nuovo%20Testamento%20(The%20New%20Testament)/CEI-nuovo-testamento.pdf">Scarica Nuovo Testamento</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Italiano%20(Italian)/Conferenza%20Episcopale%20Italiana%20(CEI)/Vecchio%20Testamento%20(The%20Old%20Testament)/CEI-vecchio-testamento.pdf">Scarica Vecchio Testamento</a>
		- <a href="https://raw.githubusercontent.com/0xR3V/Bibles/main/Italiano%20(Italian)/Conferenza%20Episcopale%20Italiana%20(CEI)/Vecchio%20Testamento%20e%20Nuovo%20Testamento%20(The%20Old%20Testament%20%26%20The%20New%20Testament)/CEI.pdf">Scarica Vecchio Testamento e Nuovo Testamento</a>
	- [x] Giovanni Diodati Bibbia 1649 (ITADIO)
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Italiano%20(Italian)/Giovanni%20Diodati%20Bibbia%201649%20(ITADIO)/Nuovo%20Testamento%20(The%20New%20Testament)/ITADIO-nuovo-testamento.pdf">Scarica Nuovo Testamento</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Italiano%20(Italian)/Giovanni%20Diodati%20Bibbia%201649%20(ITADIO)/Vecchio%20Testamento%20(The%20Old%20Testament)/ITADIO-vecchio-testamento.pdf">Scarica Vecchio Testamento</a>
		- <a href="https://github.com/0xR3V/Bibles/raw/main/Italiano%20(Italian)/Giovanni%20Diodati%20Bibbia%201649%20(ITADIO)/Vecchio%20Testamento%20e%20Nuovo%20Testamento%20(The%20Old%20Testament%20%26%20The%20New%20Testament)/ITADIO.pdf">Scarica Vecchio Testamento e Nuovo Testamento</a>

More bible versions/languages will be added in the future.

# Special Thanks
- To [Peter Schaffter](https://schaffter.ca/about-me.html) (The Creator of [mom](https://schaffter.ca/mom/mom-01.html)), who created the `SKIPTOCENTRY.mom` file and patched several bugs discovered while working on this project.

# Contact Me
Please contact me or open an issue if you have any concerns or suggestions.
- Email: `r3veal@protonmail.ch`

<div align="right">
<p>
	<strong>...All The Glory To God.</strong>
</p>
</div>
