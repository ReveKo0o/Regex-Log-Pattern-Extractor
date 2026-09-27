# REGEX & LOG PATTERN EXTRACTOR https://reveko0o.github.io/Regex-Log-Pattern-Extractor/

Built out of sheer boredom and the frustration of manually parsing messy logs and CTF data dumps. Before integrating this into the main launcher suite, I wanted to test it in my own local workspace and fine-tune the regex rules. 

<img width="959" height="632" alt="image" src="https://github.com/user-attachments/assets/0384d946-947f-4ef0-8273-c73e2f821620" />



It runs entirely **client-side**, keeping everything fast, private, and self-contained with zero backend servers.

---

## What Does It Do?

<img width="621" height="182" alt="image" src="https://github.com/user-attachments/assets/0ad8bcd6-64f4-42ec-9264-6fc9b5e0e9be" />


When you paste raw, noisy logs, curl commands, or text dumps, it instantly applies a clean developer filter:

* **IP Address Extractor:** Captures all IPv4 addresses within the text and deduplicates them (`Unique`).
* **URL & Domain Scraper:** Extracts domains and HTTP/HTTPS links using an intelligent negative lookahead pattern to prevent IP addresses from accidentally mixing in.
* **Contextual Correlation:** Pinpoints exact line relationships—mapping out which specific IP addresses appear on the same lines alongside which URLs or endpoints.

---

## How It Works

1. Open `index.html` in any modern web browser (or publish it via GitHub Pages).
2. Paste your raw logs or text data into the top input area (`RAW INPUT LOG / TEXT DATA`).
3. Click the **[+] EXTRACT & ANALYZE PATTERNS** button.
4. View the results instantly across the panels:
   * Unique IP addresses
   * Cleaned URL list
   * Contextual line-by-line IP-to-URL mapping

---
