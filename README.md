# Core Web Vitals and Page Speed Performance Auditor

[![Core Web Vitals Auditor](https://img.shields.io/badge/TAVARDT-Core%20Web%20Vitals-5b3cf5.svg)](https://tools.tavardt.com/ca/core-web-vitals-checker/)
[![Jurisdiction](https://img.shields.io/badge/Jurisdiction-Canada-00C853.svg)](https://ag.tavardt.com/ca/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits bilingual page speed, TTFB latency, compression efficiency, and layout stability.

Developed and maintained by the web performance engineering division of **[TAVARDT Canada](https://ag.tavardt.com/ca/)**.

---

## Core Web Vitals Audit Capabilities

* **Server Response and TTFB Analysis**: Precise measurement of initial Time to First Byte latency across Canadian networks.
* **Render-Blocking Resource Inspection**: Detection of synchronous CSS stylesheets and JavaScript assets delaying initial rendering.
* **Visual Stability Audit (CLS)**: Verification of explicit image dimensions and lazy loading implementations to eliminate layout shifts.
* **HTTP Compression Verification**: Audits Brotli and Gzip payload compression configuration.
* **W3C Performance Health Score**: Quantitative 0 to 100 performance score with prioritized remediation guidance.

---

## Installation and Execution

Requires Python 3.8 or higher.

```bash
git clone https://github.com/TAVARDT-Canada/core-web-vitals-tester-ca.git
cd core-web-vitals-tester-ca
python cwv_tester.py https://company.ca
```

To output results in structured JSON format:

```bash
python cwv_tester.py https://company.ca --json
```

---

## Comprehensive Web Diagnostic

For full web performance audits and real-world loading simulations:

* **[Official Core Web Vitals Checker Tool](https://tools.tavardt.com/ca/core-web-vitals-checker/)**
* **[TAVARDT Canada Enterprise Portal](https://ag.tavardt.com/ca/)**

---

## Web Performance and Speed Optimization Advisory

For Canadian digital platforms aligning with W3C Standards and Canadian Digital Performance Architecture, contact the specialists at **[TAVARDT Canada](https://ag.tavardt.com/ca/contact/)**.
