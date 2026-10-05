# Contributing to Metasploit Cheat Sheet

Thank you for helping keep this cheat sheet accurate and up to date!

## Legal Notice

All contributions must relate to **authorized security testing, CTF challenges, research, or defensive use**. Do not contribute content that facilitates unauthorized access to systems.

## How to Contribute

### Reporting Issues

Use GitHub Issues to:
- Report outdated commands or syntax
- Suggest missing commands or modules
- Report broken links

### Proposing Changes

1. Fork this repository
2. Create a feature branch: `git checkout -b add/command-name` or `fix/section-name`
3. Make your changes
4. Submit a Pull Request using the provided template

### Guidelines

- Keep examples concise and copy-paste ready
- Use `msf6 >` prompt prefix for msfconsole commands and `meterpreter >` for Meterpreter
- Add inline comments (`# comment`) to explain non-obvious options
- Reference the relevant module path or CVE where applicable
- Do not include specific IP addresses, hostnames, or credentials — use placeholders like `<LHOST>`, `<RHOST>`, `<TARGET>`
- Verify commands against a current Metasploit Framework release before submitting

## Code of Conduct

Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).
