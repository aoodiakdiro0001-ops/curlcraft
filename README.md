# 🌀 CurlCraft — CURL to Code (MIT)

Paste curl → runnable code in **10 languages**: Python, JavaScript, Go,
Rust, PHP, Bash, PowerShell, Ruby, Java, C#. Plus header extractor and
sponsor slots. UI in EN/TR/AR. Static single file.

## Parser (all local)

Tokenizer handles quotes, `\` continuations; extracts method, URL,
multi-headers, multi `-d` bodies (auto-POST), `--json`, basic auth,
insecure/follow/timeout/proxy/UA/compressed/cookies, `-G` query folding.

## Money & contact

- `CONFIG.ads` (AdSense/Carbon) footer slot.
- `CONFIG.sponsors[]` — `{name,url,img,desc}` renders sponsor cards;
  empty = elegant placeholders (Hosting / API Gateway / Cloud).
- Donate: BTC + USDT-TRC20 + IBANs live.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd curlcraft
python3 -m http.server 8080
```

## License

MIT. Verify generated code before production use.
