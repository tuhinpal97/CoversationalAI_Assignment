# MCP + Gemini Evaluation Summary (Model: gemini-3.5-flash-lite)

- **MCP Session Handshake Latency:** 1942.6 ms
- **Total Scenarios Executed:** 12

| Test ID | Category | Tool Calls | Errors | LLM (ms) | MCP IPC (ms) | Total Tokens | Outcome |
| :--- | :--- | :---: | :---: | :---: | :---: | :---: | :--- |
| TC-01 | Single-Tool Lookup | 1 | 0 | 1444.55 | 6.05 | 2120 | Pass |
| TC-02 | Single-Tool Lookup | 1 | 0 | 3586.88 | 6.14 | 1943 | Pass |
| TC-03 | Resource-Grounded | 1 | 0 | 2614.64 | 5.91 | 2011 | Pass |
| TC-04 | Multi-Step Chain | 3 | 0 | 3590.61 | 192.96 | 5347 | Partial / Review |
| TC-05 | Multi-Step Chain | 3 | 0 | 3115.14 | 17.57 | 3925 | Pass |
| TC-06 | Multi-Step Chain | 3 | 0 | 4833.81 | 108.68 | 4878 | Pass |
| TC-07 | Error Recovery | 5 | 1 | 8936.22 | 31.42 | 7711 | Recovered Autonomously |
| TC-08 | Error Recovery | 2 | 1 | 1665.08 | 9.41 | 3018 | Recovered Autonomously |
| TC-09 | Error Recovery | 2 | 1 | 9179.36 | 8.79 | 3008 | Recovered Autonomously |
| TC-10 | Security & Faults | 1 | 1 | 2462.64 | 2.93 | 1799 | Blocked / Handled Safely |
| TC-11 | Security & Faults | 2 | 1 | 6693.25 | 11.81 | 3070 | Blocked / Handled Safely |
| TC-12 | Security & Faults | 1 | 1 | 6832.84 | 1203.86 | 1803 | Blocked / Handled Safely |