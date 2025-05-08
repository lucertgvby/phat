# 🛡️ PHAT – Phishing Header Analyzer Tool

![grafik](https://github.com/user-attachments/assets/703b647f-ee1e-42bd-9c83-8d5bf0af6493)


Graphical PowerShell application designed to help investigators, security analysts, and IT professionals examine email headers for signs of phishing or spoofing. The tool parses headers from `.eml` and `.msg` files, highlights important fields, and provides insights into SPF, DKIM, and DMARC results.

---

## 🎯 Features

- GUI-based interface using `System.Windows.Forms`
- Load `.eml` or `.msg` files directly
- Parses and highlights:
  - `SPF`, `DKIM`, and `DMARC` results
  - Common headers like `From`, `To`, `Subject`, etc.
  - All `Received` routes
- Color-coded verdicts (green for pass, red for fail)
- Export results to:
  - Plain text (`.txt`)
  - Comma-separated values (`.csv`)
- Includes banner image support (via Base64)

---

## 💻 Screenshot

![grafik](https://github.com/user-attachments/assets/d162b115-f20e-47cb-a0cf-aab76e422769)


---

## 🚀 How to Use

1. **Run the script** in a PowerShell console:
   ```powershell
   .\phat.ps1
   ```
2. Paste headers manually or load a .eml/.msg file.

3. Click "Check" to parse and display header information.

4. Optionally, click "Export TXT" or "Export CSV" to save the analysis.


🛠 Requirements

    Windows PowerShell

    .NET Framework (for Windows Forms)

    PowerShell Execution Policy allowing script execution (e.g. RemoteSigned)
    

This tool is intended for educational and forensic purposes only. Use it responsibly and legally.


