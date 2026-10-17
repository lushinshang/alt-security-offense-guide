# 路徑還沒封上，鏈就已經跑完：讀 ALT Security《The Evolution of AI-Enabled Cyber Offense》

深度導讀 ALT Security 白皮書《The Evolution of AI-Enabled Cyber Offense》（頁面自報發布日 2026-08-01）。導讀把白皮書的論點拆開，對照 OpenAI 技術報告與多份獨立資料，標出哪些是單一廠商說法、哪些有獨立佐證。

**線上閱讀：** https://lushinshang.github.io/alt-security-offense-guide/

## 200字介紹

ALT Security 白皮書主張，AI 讓攻擊鏈的每一段都在壓縮，防守方該管的是 exposure window，在攻擊者走完之前先關掉通往關鍵資產的 path。發布者是賣攻擊路徑驗證產品的廠商，成本估算與現場引述都是單方說法。導讀對照 OpenAI 技術報告、METR、M-Trends 2026、CrowdStrike 等來源：時間壓縮有獨立數字佐證，把壓縮歸因給 AI 仍是推論；OpenAI–Hugging Face 事件的細節也與報告有落差。文末整理五點可以帶走的話。

## 檔案

| 檔案 | 說明 |
|---|---|
| `index.html` | 獨立網頁，CSS／JS 內嵌，圖片為相對路徑，不依賴外部函式庫 |
| `images/` | `web/zh/` 為 6 張說明圖的 WebP（依圖不同為 16:9、9:16 或 1:1）；`web/og_1200x675.png` 為預覽圖 |
| `alt-security-offense-guide.md` | 正式導讀 Markdown |
| `README.md` | 本檔 |
| `share_post.md` | 社群分享文 |
| `share_line.txt` | LINE 分享文 |
| `share_linkedin.txt` | LinkedIn 分享文 |
| `.gitignore` | 忽略 `qa_*.png` 與 `*.normalized.md` |

## 原始素材

- ALT Security 白皮書：https://alt.security/resources/wp-the-evolution-of-ai-enabled-cyber-offense
- OpenAI 技術報告（PDF）：https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf

## 查證來源

- ALT Security 白皮書：https://alt.security/resources/wp-the-evolution-of-ai-enabled-cyber-offense
- OpenAI 技術報告：https://cdn.openai.com/pdf/67869394-cb91-4c12-888c-5cbd85c7814c/OpenAI-Hugging-Face%20Incident-Technical-Report.pdf
- METR：https://metr.org/blog/2026-08-26-openai-hugging-face-incident-investigation/
- Anthropic attack-navigator：https://www.anthropic.com/research/attack-navigator
- Google Cloud／Mandiant M-Trends 2026：https://cloud.google.com/blog/topics/threat-intelligence/m-trends-2026
- CrowdStrike 2026 Global Threat Report：https://crowdstrike.com/en-us/press-releases/2026-crowdstrike-global-threat-report
- GTIG：https://cloud.google.com/blog/topics/threat-intelligence/from-prompting-to-autonomy-the-evolution-of-adversarial-ai
- Lawfare：https://www.lawfaremedia.org/article/the-ai-revolution-in-cyber-conflict
- TechInformed（報導 International AI Safety Report 2026）：https://techinformed.com/ai-still-cant-run-reliable-end-to-end-cyberattacks-without-humans-report-finds/
- Cloud Security Alliance：https://labs.cloudsecurityalliance.org/research/csa-research-note-autonomous-ai-agent-intrusion-openai-huggi/
- INCIBE-CERT：https://www.incibe.es/index.php/en/incibe-cert/publications/cybersecurity-highlights/security-incident-involving-openais-ai-agents-targeting-hugging-face
- UK NCSC：https://www.ncsc.gov.uk/sites/default/files/2026-06/Preparing-for-a-%E2%80%98vulnerability-patch-wave%E2%80%99_0.pdf

導讀者查證過程紀錄不在本 repo。
