# Wikipedia Category Translator (En → Pa)

A lightweight, browser-based tool designed to help Wikimedia contributors easily translate English Wikipedia categories into their Punjabi Wikipedia equivalents.

[**Live Demo**](https://kuldeepburjbhalaike.github.io/Category-Translator/)
## 🚀 Features

* **Bulk Translation:** Accepts a list of English categories (one per line).
* **Smart Formatting:** Automatically handles inputs with or without `[[Category:...]]` syntax.
* **Visual & Raw Output:**
    * **Table:** Shows side-by-side comparisons with direct links to the categories.
    * **Copy Box:** Generates a ready-to-paste list of Punjabi categories (e.g., `[[ਸ਼੍ਰੇਣੀ:ਇਤਿਹਾਸ]]`).
* **Dark Mode:** Features a modern "Slate Blue" dark mode that syncs with your system preferences automatically.
* **No Server Required:** Runs entirely in the browser using the MediaWiki API.

## 🛠️ How to Use

1.  Open the tool.
2.  Paste a list of English categories into the input box.
    * *Example:* `History of Punjab` or `[[Category:Sikhism]]`
3.  Click **"Get Punjabi Links"**.
4.  The tool will fetch data from the Wikipedia API.
5.  Copy the results from the "Punjabi Categories" box or click the links in the table to verify.

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
* **API:** [MediaWiki Action API](https://www.mediawiki.org/wiki/API:Main_page) (fetching `langlinks`)

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
