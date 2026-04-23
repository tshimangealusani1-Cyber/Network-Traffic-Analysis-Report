# 🧪 Network Traffic Analysis Report

## 📌 Overview

I analyzed captured network traffic using Wireshark to understand protocol behavior and detect anomalies.

---

## 🔍 DNS Analysis

Observed domain name resolution processes.

**Findings:**

* Queries sent to DNS servers
* Valid responses received

**Conclusion:**
DNS functioning normally.

---

## 🔗 TCP Analysis

Observed TCP handshake process.

**Findings:**

* SYN → SYN-ACK → ACK
* Normal connection establishment

**Conclusion:**
TCP sessions established correctly.

---

## 📡 ICMP Analysis

Analyzed ping traffic.

**Findings:**

* Echo request and reply packets

**Conclusion:**
Network connectivity stable.

---

## 🔐 HTTPS Analysis

Observed encrypted traffic.

**Findings:**

* TLS communication
* Secure sessions established

**Conclusion:**
Secure communication functioning.

---

## 🚨 Suspicious Activity

Observed:

* Repeated DNS queries
* Multiple connection attempts

**Assessment:**
Possible automated traffic, no confirmed malicious activity.

---

## 📊 Summary

| Category            | Status |
| ------------------- | ------ |
| DNS                 | Normal |
| TCP                 | Normal |
| ICMP                | Normal |
| HTTPS               | Normal |
| Suspicious Activity | Low    |

---

## 📈 Conclusion

Traffic appears normal with minor anomalies.

Continuous monitoring is recommended.

---
