# Prompt Builder

Desktop tool for Windows to design, reuse and send high-quality AI prompts, made for cybersecurity education and technical work.

## Features

- Build prompts from clear parts: role, task, audience, style, constraints, examples and output format
- Ready-made templates organised by topic, in English and Dutch
- Save your own templates
- Network / Cisco form that turns your requirements into a prompt
- SOC and Elastic form for monitor scripts and dashboards
- Prompt check and an explanation of every part while you work
- Send to Ollama, LM Studio or any OpenAI-compatible service
- Your data stays on your computer, in the `data` folder next to the program

## Create a program / Programma maken

Version 2.9.0 adds a visible **Templates > Create a program** category for Python, PowerShell, Rust, C#, JavaScript/TypeScript and another language. Fill in goal, platform, application type, input/output and features. Prompts request complete source files, project structure, dependencies, error handling and setup/start instructions. Your selected AI generates the code; Prompt Builder does not run it automatically.

Versie 2.9.0 voegt **Sjablonen > Programma maken** toe, met expliciete sjablonen per programmeertaal. Vul het doel, platform, type programma, invoer/uitvoer en de functies in. De prompt vraagt om volledige bronbestanden, projectstructuur, afhankelijkheden, foutafhandeling en installatie- en startinstructies. Je gekozen AI maakt de code; Prompt Builder voert deze niet automatisch uit.

The separate `programma-maken.pbpack.json` can also be imported into an existing version supporting template packs. Het losse pakket kan ook worden geïmporteerd in een bestaande versie met pakketondersteuning.

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
