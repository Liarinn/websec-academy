# tools

Scripts written while solving labs — built when doing something by hand
became unbearable, which is the signal that it should be automated.

Each script:
- takes the target URL / token as command-line arguments (never hardcoded)
- has a three-line docstring: what it does, how to run it, which lab prompted it

Planned:
- [ ] blind-sqli.py — extract data character by character (Stage 1)
- [ ] jwt-weak-key.py — test a token against a wordlist of signing keys (Stage 4)
