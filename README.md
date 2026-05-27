## 🏜️ Hermosillo Quest

An interactive, single-page web application designed for exploring cultural, musical, and recreational activities in Hermosillo, Sonora, during April 2026. 

This project transforms unstructured, plain-text community data into a dynamic, user-friendly digital experience. It features a retro-arcade 8-bit aesthetic to make the process of discovering local events engaging and accessible for non-technical users.

## 🕹️ Key Features

* **Categorized Exploration:** Activities are organized into 7 clear categories (*Expogan 2026, Shows & Cinema, Art & Books, Workshops, General Events, Concerts,* and *Contests*).
* **Smart Randomized Generation:** The "Roll Activity" algorithm suggests random events within a selected category while preventing consecutive duplicates in the same session.
* **Global Random Selection:** The "Random from All" feature allows users to discover activities across all categories instantly, automatically highlighting the corresponding section.
* **Cost & Venue Transparency:** Every generated result features dynamic badges indicating location, date, additional notes, and cost status (`FREE` or `PAID`).
* **Full Inventory View:** A toggleable comprehensive list allows traditional, linear browsing of all embedded events.

## ⚙️ Architecture & Technical Specifications

* **100% Client-Side:** Built using pure HTML5, CSS3, and Vanilla JavaScript. No external backend, databases, or third-party dependencies are required.
* **Zero-Setup Portability:** Fully self-contained. The application can be executed offline by simply opening the `.html` file in any modern web browser.
* **UI/UX Best Practices:** Interface designed following Nielsen's Usability Heuristics, emphasizing error prevention (disabling commands when context is missing) and system status visibility via smooth arcade-style visual feedback.

## 📂 Source Data Credit

All event information embedded in this application was compiled and originally published by user **u/Yggrmn** on the Reddit community **r/hermosillo** under the thread *"Cosas que pasan en HMO y no te enteras" (April 2026)*. This project serves as an interactive implementation to solve information dispersion, fully recognizing the original author as the data source.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `hermosillo_quest.html` in any web browser (Chrome, Firefox, Edge, Safari).
3. *(Optional)* If hosted via **GitHub Pages**, it runs instantly from any mobile or desktop browser without downloading files.
