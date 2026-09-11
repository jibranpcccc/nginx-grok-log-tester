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

## 📚 In-Depth Technical Implementation Guides

| Target Engineering Query | Production Reference & Guide URL |
| :--- | :--- |
| **Nginx Log Grok Pattern Generator** | [https://groklogtester.pages.dev/nginx-access-log-grok-pattern-generator/](https://groklogtester.pages.dev/nginx-access-log-grok-pattern-generator/) |
| **Aws Alb Access Log Regex Parser** | [https://groklogtester.pages.dev/aws-alb-access-log-regex-parser/](https://groklogtester.pages.dev/aws-alb-access-log-regex-parser/) |
| **Docker Json Log Grok Pattern Regex** | [https://groklogtester.pages.dev/docker-json-log-grok-pattern/](https://groklogtester.pages.dev/docker-json-log-grok-pattern/) |
| **Grok Pattern Tester Syslog Rfc5424** | [https://groklogtester.pages.dev/syslog-rfc-5424-grok-pattern/](https://groklogtester.pages.dev/syslog-rfc-5424-grok-pattern/) |

