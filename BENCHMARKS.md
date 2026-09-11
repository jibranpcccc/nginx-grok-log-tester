# GrokLogTester Regex Parsing Speed & Log Schema Leaderboard

Grok pattern testing, PCRE regex performance profiling, and ingest pipelines for Nginx, HAProxy, and Ingress controllers.

⚡ **Test Grok Patterns In-Browser:** [https://groklogtester.pages.dev/](https://groklogtester.pages.dev/)

## 1. Log Parser Throughput (Logs Processed / Sec)

| Log Engine | Format | Ingestion Rate (Lines/Sec) | Memory Usage |
| :--- | :--- | :--- | :--- |
| Vector (VRL) | Combined Nginx | 340,000 lines/sec | 42 MB |
| Fluent Bit | Ingress-Nginx Regex | 185,000 lines/sec | 28 MB |
| Logstash (Grok) | Default Grok | 24,000 lines/sec | 850 MB |
| Python PCRE Regex | Compiled Regex | 65,000 lines/sec | 35 MB |

---
Maintained by [GrokLogTester](https://groklogtester.pages.dev/).
