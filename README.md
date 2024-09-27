# MailRanger - Email Access Checker

## 🔴 IMPORTANT! READ!!

MailRanger is a powerful tool designed for educational and research purposes. However, performing (D)DoS attacks or *credential stuffing* on email accounts or services that you do not own (or for which you do not have permission to test) is **illegal!**

Improper use of this tool may result in legal consequences. The developer will not be held responsible for any illegal or unauthorized activity carried out with MailRanger. Please use this tool responsibly and ethically, always respecting the privacy and rights of others.

---

## 🔴 IMPORTANT NOTICE

MailRanger has reached the end of its support lifecycle. Future updates and enhancements will be provided through **Email Ranger X**, which aims to offer a broader range of features and improved functionality.

The current version is **0.10.2**, which includes foundational features with plans for further development.

---

## 📜 Overview

MailRanger is a robust email access checker designed for educational purposes. It allows users to verify email accounts against IMAP servers and search for specific keywords within the inbox. Built with Python, this tool employs multithreading for efficient processing and provides a clear console interface to monitor progress.
---
![MailRanger X](https://raw.githubusercontent.com/EquipeRanger/MailRangerX/refs/heads/main/final.png)
## 🔧 Features

- **IMAP Server Integration:** Automatically detects IMAP servers for various email domains.
- **Keyword Search:** Checks inbox emails for specific keywords.
- **Multithreading Support:** Processes multiple email accounts concurrently for faster results.
- **User-Friendly Console Interface:** Displays real-time statistics on hits, found keywords, and errors.
- **Result Logging:** Saves hits, found accounts, and invalid accounts into separate text files.

## 📦 Installation

### Prerequisites

- Python 3.7 or higher
- Required Python packages:
  - `imaplib`
  - `concurrent.futures`
  - `colorama`
  - `dns.resolver`
  - `tqdm`
  - `tkinter`
  - `threading`

You can install the required packages using:

```bash
pip install -r requirements.txt

