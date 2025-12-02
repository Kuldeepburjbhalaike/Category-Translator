# Interwiki Checker (En → Pa)

A lightweight, browser-based tool designed to help Punjabi Wikimedians easily check if English Wikipedia articles or categories exist on Punjabi Wikipedia.

[**Tool Link**](https://kuldeepburjbhalaike.github.io/Interwiki-Checker/)

## 🚀 Features

* **Dual Modes:** Switch easily between checking **Articles** and **Categories**.
* **Smart Search:**
    * **Auto-Capitalization:** Automatically fixes input case (e.g., `history of india` → `History of India`).
    * **Redirects:** Follows English Wikipedia redirects to find the correct title automatically.
* **Bulk Checking:** Accepts a list of English titles (one per line).
* **Visual & Raw Output:**
    * **Table:** Shows side-by-side comparisons with direct links to the Punjabi pages.
    * **Copy Box:** Generates a ready-to-paste list of Wikilinks (e.g., `[[ਸ਼੍ਰੇਣੀ:ਇਤਿਹਾਸ]]` or `[[ਪੰਜਾਬ ਦਾ ਇਤਿਹਾਸ]]`).
* **Dark Mode:** Features a modern "Slate Blue" dark mode that syncs with your system preferences.
* **No Server Required:** Runs entirely in the browser using the MediaWiki API.

## 🛠️ How to Use

1.  Open the tool.
2.  **Select a Mode:** Choose "Check Articles" or "Check Categories".
3.  Paste a list of English titles into the input box.
    * *Article Example:* `History of Punjab` (or lowercase `history of punjab`)
    * *Category Example:* `Sikhism` or `Category:Sikhism`
4.  Click **"Check Availability"**.
5.  The tool will fetch data from the Wikipedia API.
6.  Copy the results from the "Available on Punjabi Wiki" box or use the table to verify links.

## 📦 Installation / Hosting

You can host this tool for free using **GitHub Pages**.

1.  **Fork** this repository or create a new one.
2.  Add the `index.html` file containing the source code.
3.  Go to your repository **Settings** → **Pages**.
4.  Under **"Build and deployment"**, set the **Source** to `Deploy from a branch`.
5.  Select `main` (or `master`) as the branch and click **Save**.
6.  Wait a minute, and GitHub will provide your live URL.

## 💻 Tech Stack

* **HTML5 & CSS3** (Responsive, Dark Mode variables)
* **JavaScript** (Fetch API, Async/Await)
* **API:** [MediaWiki Action API](https://www.mediawiki.org/wiki/API:Main_page) (fetching `langlinks`, `redirects`, and `converts`)

## 🤝 Contributing

Contributions are welcome! If you find a bug or want to add support for another language, feel free to open an issue or submit a pull request.

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---
Made with ❤️ by [Kuldeep](https://meta.wikimedia.org/wiki/User:Kuldeepburjbhalaike)
