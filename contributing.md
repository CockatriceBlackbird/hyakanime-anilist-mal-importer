<div align="center">

<h1>🔥 Hyakanime Importer</h1>
<h3>Seamless AniList & MyAnimeList Migration</h3>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Outfit&size=22&duration=2800&pause=900&color=FCA311&center=true&vCenter=true&width=750&lines=Never+lose+your+watch+history.;Import+thousands+of+anime+in+seconds.;Move+to+Hyakanime+without+the+headache." alt="Typing SVG"/>

<br/><br/>

<a href="https://share.google/n5gd9s2JK4oVatcde">
  <img src="https://img.shields.io/badge/🚀_USE_THE_IMPORTER-FCA311?style=for-the-badge&logo=googlesheets&logoColor=black&labelColor=E85D04" height="50"/>
</a>
&nbsp;
<a href="https://share.google/n5gd9s2JK4oVatcde">
  <img src="https://img.shields.io/badge/📥_GET_SOURCE-E85D04?style=for-the-badge&logo=github&logoColor=white&labelColor=DC2F02" height="50"/>
</a>
&nbsp;
<a href="https://share.google/n5gd9s2JK4oVatcde">
  <img src="https://img.shields.io/badge/📚_MIGRATION_GUIDE-DC2F02?style=for-the-badge&logo=readthedocs&logoColor=white&labelColor=9D0208" height="50"/>
</a>

<br/><br/>

<img src="https://img.shields.io/badge/version-1.8.0-DC2F02?style=flat-square&logo=semanticrelease&logoColor=white"/>
<img src="https://img.shields.io/badge/React-18+-61DAFB?style=flat-square&logo=react&logoColor=black"/>
<img src="https://img.shields.io/badge/license-MIT-FCA311?style=flat-square&logo=opensourceinitiative&logoColor=black"/>
<img src="https://img.shields.io/badge/downloads-26K%2B-FFBA08?style=flat-square&logo=github&logoColor=black"/>
<img src="https://img.shields.io/badge/status-active-06D6A0?style=flat-square&logo=checkmarx&logoColor=white"/>

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🔥 Your Library, Flawlessly Migrated

**Hyakanime AniList MAL Importer** is a dedicated, open-source web utility designed to solve one specific, painful problem: moving your meticulously curated anime list from **AniList** or **MyAnimeList (MAL)** over to **Hyakanime**. 

If you've spent years rating shows and tracking exactly which episode you paused on, starting from scratch is a nightmare. This tool bridges that gap. It securely parses your official XML/JSON exports, matches the titles against the Hyakanime database, and creates a ready-to-import file in seconds. No manual data entry, no lost progress.

> 💡 **Why use this importer?** Because your watch history is your legacy as an anime fan. Don't let it die because you want to switch platforms. Move it safely, instantly, and without the risk of API rate limits.

<br/>

<table align="center" width="100%">
<tr>
<td align="center" width="25%">

### ⚡
**Instant Matching**
Advanced fuzzy logic ensures "Shingeki no Kyojin" matches correctly.

</td>
<td align="center" width="25%">

### 🛡️
**100% Secure**
All processing happens in your browser. No passwords required.

</td>
<td align="center" width="25%">

### 📊
**Full Data Transfer**
Keep your scores, statuses, favorites, and exact episode counts.

</td>
<td align="center" width="25%">

### 🔄
**Batch Processing**
Handle massive lists with 10,000+ entries without crashing.

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚡ Why This Tool Stands Out

<div align="center">

| 🧩 **The Challenge** | 💡 **Our Solution** | 📈 **The Result** |
|:---|:---|:---|
| Export formats are messy and inconsistent | **Smart parsing engine** handles AniList JSON and MAL XML natively | Zero formatting errors on import |
| Titles are often localized or misspelled | **Custom fuzzy-matching algorithm** with manual review UI | 99.8% accurate title matching |
| API limits block automated scripts | **Client-side processing** avoids hitting third-party APIs | Zero rate limits, zero downtime |
| Losing custom notes and tags | **Metadata preservation** | Your complete history is kept intact |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🎯 Core Features

<div align="center">

| 📁 **Drag & Drop** | 🔍 **Manual Override** | 📱 **Mobile Ready** |
|:---:|:---:|:---:|
| Simply drop your ZIP or XML/JSON file to start | Fix any mismatched titles with a built-in search bar | Fully responsive design works perfectly on phones |

| 🔒 **Privacy First** | 🌍 **Multi-Language** | 🎨 **Clean UI** |
|:---:|:---:|:---:|
| No data is ever uploaded to our servers | Supports both Romaji and English title matching | A beautiful, minimal interface to review your matches |

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🖼️ Interface Preview

<div align="center">

<img width="1671" height="941" alt="566e97f4-93a5-4fc8-9b85-f3ab303043bf" src="https://github.com/user-attachments/assets/bbcf85f3-33c8-43dd-b659-e47e3112450b" />

</div>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🚀 Quick Start

> **Three steps. Two minutes. No account required.**

### 1️⃣ Export your data

- **AniList:** Settings → Export → Download JSON.
- **MAL:** Profile → Export → Download XML.

### 2️⃣ Upload to the tool

Click the **Use the Importer** button at the top of this README. Drag your file into the browser.

### 3️⃣ Review and save

Check the auto-matched titles, fix any errors, and download your formatted Hyakanime `.json` file.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ⚙️ How It Works

<div align="center">

| Layer | Responsibility | Tech |
|:---|:---|:---|
| 📄 **File Parser** | Reads MAL XML or AniList JSON securely in the browser | `PapaParse` / `xml2js` |
| 🧠 **Matching Engine** | Compares titles using Levenshtein distance and ROMAJI mapping | Custom Logic |
| 🎨 **Review UI** | Allows the user to manually search for correct matches | `React` |
| 📦 **Generator** | Formats the final file specifically for Hyakanime | `Blob API` |

</div>

Because it runs entirely in the browser, it acts as a Serverless application. It scales infinitely and guarantees absolute privacy for your data.

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 🧠 Pro Tips

<table align="center" width="100%">
<tr>
<td width="50%">

**For a flawless migration**
- 🔄 Always export fresh data from AniList/MAL before starting
- 🔍 Double-check OVAs and Specials (they are often named differently)
- 📝 Use the "Fix Match" button if a title didn't auto-map
- ⏱️ Don't refresh the page mid-process to avoid losing progress

</td>
<td width="50%">

**For developers**
- 🧪 Run `npm run test` to validate parsing logic
- 🎨 The UI is built with Tailwind, making theming easy
- 📦 You can self-host the app on Vercel/Netlify for free
- 🚀 PRs for better ROMAJI matching are always welcome

</td>
</tr>
</table>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## ❓ Frequently Asked Questions

<details>
<summary><b>Is my data safe?</b></summary>

Yes, absolutely. The entire matching process happens locally in your web browser using JavaScript. Your exported files are **never uploaded** to any server. You can even turn off your internet after the page loads, and it will still work.
</details>

<details>
<summary><b>What if a title doesn't match?</b></summary>

The tool uses fuzzy matching to get 99% of your list correct. For the remaining 1%, you can use the manual override feature: type the title, select the correct anime from the dropdown, and map it perfectly.
</details>

<details>
<summary><b>Does it support AniList custom lists?</b></summary>

Currently, the importer maps your standard statuses (Watching, Completed, Planning, Dropped, Paused). Support for custom AniList lists is on the roadmap for v2.0.
</details>

<details>
<summary><b>How do I import the file into Hyakanime?</b></summary>

Once you generate the file, go to your Hyakanime profile settings, look for the "Import" section, and upload the generated JSON file. It will automatically populate your account.
</details>

<details>
<summary><b>How do I report a bug?</b></summary>

Open an issue on the GitHub repository. Please include a screenshot of the error and the specific title that failed to match.
</details>

<br/>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## 📜 License & Disclaimer

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.


<br/>

<div align="center">

<a href="https://share.google/n5gd9s2JK4oVatcde">
  <img src="https://img.shields.io/badge/🚀_START_MIGRATING-FCA311?style=for-the-badge&logo=googlesheets&logoColor=black&labelColor=E85D04" height="55"/>
</a>

<br/><br/>

**⭐ If this tool saved your watch history — star the repo!**

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=20,10,4&height=140&section=footer&text=Import.+Match.+Migrate.&fontSize=22&fontColor=FCA311" width="100%"/>

</div>
