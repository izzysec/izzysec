<h1 align="center">Isabel Mill</h1>

<p align="center">
  <b>Security Researcher at Check Point Research</b><br>
  Offensive security, vulnerability research and AI-assisted code review
</p>

<p align="center">
  <a href="https://izzysec.github.io"><img src="https://img.shields.io/badge/blog-izzysec.github.io-e8a0b8?style=flat-square&labelColor=0e1114" alt="Blog"></a>
  <a href="https://x.com/izzysecurity"><img src="https://img.shields.io/badge/X-@izzysecurity-e8a0b8?style=flat-square&labelColor=0e1114&logo=x&logoColor=white" alt="X"></a>
  <a href="https://www.linkedin.com/in/isabel-mill-bb5a05177"><img src="https://img.shields.io/badge/LinkedIn-Isabel%20Mill-e8a0b8?style=flat-square&labelColor=0e1114&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

---

I look for the places where developer tools trust things they shouldn't: config files that ship inside a repository, URLs that end up in a shell, and code review screens that don't show what actually runs. Most of my findings sit somewhere in the software supply chain, in tools that developers and build servers run every day.

## CVEs

- **[CVE-2026-105802](https://izzysec.github.io/git-lfs-config-injection-cve-2026-105802/)** · Git LFS · High  
  A line break in a submodule URL injects Git config that makes Git LFS run an attacker's program.
- **[CVE-2026-95106](https://izzysec.github.io/gitea-duplicate-tree-cve-2026-95106/)** · Gitea · Critical  
  Duplicate tree entries let reviewers see one file while checkout and CI run another.
- **[CVE-2026-5917](https://izzysec.github.io/libgit2-ssh-command-injection-cve-2026-5917/)** · libgit2 · High  
  An unquoted path in libgit2's SSH command lets a crafted Git URL run commands on the SSH server, as you.
- **[CVE-2025-61260](https://izzysec.github.io/codex-cli-config-injection-cve-2025-61260/)** · OpenAI Codex CLI · Critical  
  Project-local config files make Codex CLI launch an attacker's command the moment you open it in a folder.

Full write-ups live on [izzysec.github.io](https://izzysec.github.io).

## Projects

- **[ai-offensive-code-review](https://github.com/izzysec/ai-offensive-code-review)**  
  Point it at a codebase and get an attack surface map, data flows and security conditions worth validating, with file paths and line numbers instead of severity guesses.
- **[NullReport](https://nullreport.app)**  
  A self-hosted, AI-assisted penetration test report generator. Findings become a reusable library, reports export as branded DOCX, and client data never leaves your machine. [Docs](https://docs.nullreport.app) · [GitHub](https://github.com/nullreport)

## Certifications

- **ARTE**, AWS Red Team Expert
- **eWPTX**, Web Application Penetration Tester eXtreme

## Contact

The easiest way to reach me is a DM on [X](https://x.com/izzysecurity) or [LinkedIn](https://www.linkedin.com/in/isabel-mill-bb5a05177).
