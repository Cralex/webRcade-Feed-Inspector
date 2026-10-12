# webЯcade Feed Inspector

A lightning-fast, client-side companion web app for analyzing and exploring **[webЯcade](https://www.webrcade.com/)** ROM feeds. 

Runs entirely in your browser with no backend servers or remote database required. Your feed data stays private and is processed 100% locally on your machine.

---

## Features

*   **Multi-Format Support:** Load feeds directly via URL, upload raw `.json` files, or drop `.zip` archives / Base64-encoded feed strings.
*   **Library Dashboard:** Instantly view total game counts, categories, and unique emulated systems.
*   **Interactive Charts:** 
    *   **Doughnut Chart:** Breakdown of your top consoles/systems by game volume.
    *   **Timeline Bar Graph:** Visual history of when games were added to your library over time.
*   **🎲 Random Game Roulette:** Can't decide what to play? Pulls a random game with its thumbnail, system badge, and description, with a button to reshuffle.
*   **Recent Additions & System Breakdown:** Detailed tabs highlighting recently added titles and comprehensive system-by-system inventories.

---

## Built With

*   **[Tailwind CSS](https://tailwindcss.com/)** — Utility-first styling & dark mode UI.
*   **[Alpine.js](https://alpinejs.dev/)** — Lightweight reactive state management and tab navigation.
*   **[Chart.js](https://www.chartjs.org/)** — Dynamic analytical graphs and visualizations.
*   **[JSZip](https://stuk.github.io/jszip/)** — Client-side `.zip` archive extraction.

Made using Gemini to get things started quickly. Bugs are likely. Pull requests welcome!
