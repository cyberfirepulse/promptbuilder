# Prompt Builder

Desktop tool for Windows to design, reuse and send high-quality AI prompts, made for cybersecurity education and technical work.

## Features

- Build prompts from clear parts: role, task, audience, style, constraints, examples and output format
- 27 ready-made templates in six categories, in English and Dutch
- Save your own templates
- Network / Cisco form that turns your requirements into a prompt
- SOC and Elastic form for monitor scripts and dashboards
- Prompt check and an explanation of every part while you work
- Send to Ollama, LM Studio or any OpenAI-compatible service
- Your data stays on your computer, in the `data` folder next to the program

## Download

Get the latest installer from the [Releases](https://github.com/cyberfirepulse/PromptBuilder/releases) page. Requires Windows 10 or 11 (64-bit).

To verify a download, compare its SHA-256 with the `.sha256` file on the release page:

```
certutil -hashfile PromptBuilderSetup_<version>.exe SHA256
```

Prompt Builder checks for updates when it starts. A new version is only installed after you agree, and only if its checksum matches.

## License

Prompt Builder needs a license key. See [PRICING.md](PRICING.md) for the editions and prices. A free 14-day Evaluation license is available by e-mail.

The source code is not public. This repository contains the installers and release information only.

## Privacy

The license check sends only your license key and a random installation ID, with no hostname, hardware ID or user name. The update check is a normal HTTPS request. Prompts are only sent to the AI service you choose yourself.

## Contact

[cyberfirepulse@gmail.com](mailto:cyberfirepulse@gmail.com)
