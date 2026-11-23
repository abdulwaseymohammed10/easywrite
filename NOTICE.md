# EasyWrite — licences and notices

EasyWrite is a free writing helper for Windows. It bundles or downloads these free components, unmodified:

| Component | What it does | Licence | Source |
|---|---|---|---|
| LanguageTool 6.6 | Spelling and grammar checking | LGPL 2.1 or later | https://languagetool.org · https://github.com/languagetool-org/languagetool |
| Eclipse Temurin 21 (JRE) | Runs LanguageTool | GPL 2.0 with Classpath Exception | https://adoptium.net · https://github.com/adoptium |
| llama.cpp (build b12448) | Runs the AI model | MIT | https://github.com/ggml-org/llama.cpp |
| Llama 3.2 3B Instruct (Q4_K_M GGUF) | AI rewriting | Llama 3.2 Community License | https://www.llama.com · quantized by bartowski on Hugging Face |
| Microsoft Visual C++ runtime | Needed by llama.cpp | Microsoft redistributable licence | https://learn.microsoft.com/cpp/windows/latest-supported-vc-redist |
| certifi | Trusted certificate list for downloads | MPL 2.0 | https://github.com/certifi/python-certifi |

**Built with Llama.** Llama 3.2 is licensed under the Llama 3.2 Community License,
Copyright © Meta Platforms, Inc. All Rights Reserved. The full licence text is in
[LICENSE-Llama-3.2.txt](LICENSE-Llama-3.2.txt) and is included with every release.
Use of Llama 3.2 must follow Meta's Acceptable Use Policy: https://www.llama.com/llama3_2/use-policy

The component files are published unchanged in the `tools-v1` release of this repository so that setup
can download exact, tested versions from one place. Each component's source code is available at the
links above.
