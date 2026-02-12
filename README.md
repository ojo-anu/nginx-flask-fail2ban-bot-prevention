# Nginx + Flask + Fail2Ban Bot Prevention System

## Overview
This project demonstrates a practical bot-prevention and intrusion mitigation system using:

- **Nginx** as a reverse proxy
- **Flask** as the backend application
- **Fail2Ban** for automated IP banning

The system detects repeated unauthorized access attempts to protected routes (e.g. `/admin`) and automatically bans offending IP addresses.

---

## Architecture

Client → Nginx → Flask  
    ↘ Fail2Ban monitors Nginx logs and bans malicious IPs

---

## Features

- Reverse proxy with real client IP forwarding
- Automated detection of suspicious requests
- IP banning using Fail2Ban
- Proof of ban via Fail2Ban jail status

---

## Proof of IP Ban

![Fail2Ban Ban Status](screenshots/fail2ban-ban-status.png)

---

## Technologies Used

- Nginx
- Flask (Python)
- Fail2Ban
- Linux (Ubuntu Server)

---

## Use Cases

- Bot mitigation
- Admin panel protection
- Brute-force prevention
- SOC / Blue Team practice
- Home lab security projects

---

## Disclaimer

This project is for educational and lab purposes only.
