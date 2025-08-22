# MrFlooder404
This a Powerful DDoS Script (PHP).


# Ultra Fast HTTP Flooder

A high-performance HTTP Flooder tool built in PHP, designed for testing the resilience and load-handling capacity of web servers. Equipped with multiple attack modes, real-time statistics, random path injection, and terminal-based colorful output.

---

## Features

- **Ultra Fast**: Utilizes `curl_multi_exec()` and `fsockopen` for rapid, parallel requests.
- **Multiple Modes**: Choose between `curl_multi` and raw socket-based attacks.
- **Multi-method Support**: Attack using GET, POST, or HEAD HTTP methods.
- **Random Paths**: Sends requests to randomized URLs to bypass basic caching.
- **Live Statistics**: Shows total requests, success rate, and time left.
- **Terminal Colors**: Enhanced readability with colored outputs.
- **Success % Counter**: Measures effectiveness of the flood in real-time.
- **Supports Termux**: Fully compatible with Android Termux terminal.

---

## Requirements

- PHP 5.6 or higher
- `php-curl` enabled
- Compatible with Linux, Termux, MacOS

---


## Installation 
- Required Package
```bash
pkg install python -y 
pkg install git -y 
pkg install php -y
```
- Cloning Repository 
```bash
git clone https://github.com/mrdavid404/MrFlooder404.git

cd MrFlooder404
```
## Usage

```bash
php MrFlood777.php
```

Then follow the prompt:

1. Enter **target URL**
2. Enter **number of threads per batch**
3. Enter **attack duration in seconds**
4. Choose **HTTP method** (GET/POST/HEAD)
5. Select **mode** (1 = curl_multi, 2 = raw socket)

---

## Example

```bash
Target URL: http://example.com
Threads per batch: 50
Attack duration: 60
Method: GET
Mode: 1
```

---

## Legal Disclaimer

This tool is created for **educational and stress-testing** purposes **only**. The author is **not responsible** for any misuse or illegal activity involving this script.

Use it **only on servers you own or have permission to test**.

---
## Key 🗝️ 

```bash
AHShowev(PR1NCE)
```

## Author

- **Name**: AH Showev (Prince)
- **Facebook**: [AH Showev H](https://www.facebook.com/mr.david.404.prince)
- **GitHub**: [mrdavid404](https://github.com/mrdavid404)
- **Telegram**: [Mr David](https://t.me/mrdavid404_bot)
