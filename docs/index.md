# PayloadsAllTheThings

A list of useful payloads and bypasses for Web Application Security.

## Summary

This repository is a collection of payloads, techniques, and resources for web application penetration testing and security research.

## Categories

| Category | Description |
|----------|-------------|
| [API Key Leaks](API-Key-Leaks/README.md) | Techniques for finding and exploiting leaked API keys |
| [Command Injection](Command-Injection/README.md) | OS command injection payloads and techniques |
| [CSRF Injection](CSRF-Injection/README.md) | Cross-Site Request Forgery attack vectors |
| [Directory Traversal](Directory-Traversal/README.md) | Path traversal and local file inclusion payloads |
| [File Inclusion](File-Inclusion/README.md) | Local and Remote File Inclusion techniques |
| [File Upload](File-Upload/README.md) | Malicious file upload techniques and bypasses |
| [GraphQL Injection](GraphQL-Injection/README.md) | GraphQL-specific injection techniques |
| [Insecure Deserialization](Insecure-Deserialization/README.md) | Deserialization attack payloads |
| [LDAP Injection](LDAP-Injection/README.md) | LDAP injection techniques |
| [NoSQL Injection](NoSQL-Injection/README.md) | NoSQL database injection payloads |
| [Open Redirect](Open-Redirect/README.md) | Open redirect techniques and bypasses |
| [Prototype Pollution](Prototype-Pollution/README.md) | JavaScript prototype pollution attacks |
| [Server Side Request Forgery](Server-Side-Request-Forgery/README.md) | SSRF payloads and techniques |
| [Server Side Template Injection](Server-Side-Template-Injection/README.md) | SSTI payloads for various template engines |
| [SQL Injection](SQL-Injection/README.md) | SQL injection payloads and techniques |
| [Stored XSS](Stored-XSS/README.md) | Persistent cross-site scripting payloads |
| [Type Juggling](Type-Juggling/README.md) | PHP type juggling techniques |
| [Upload Insecure Files](Upload-Insecure-Files/README.md) | Insecure file upload examples |
| [Web Cache Deception](Web-Cache-Deception/README.md) | Web cache deception techniques |
| [Web Sockets](Web-Sockets/README.md) | WebSocket attack techniques |
| [XPATH Injection](XPATH-Injection/README.md) | XPath injection payloads |
| [XSS Injection](XSS-Injection/README.md) | Cross-site scripting payloads and bypasses |
| [XXE Injection](XXE-Injection/README.md) | XML external entity injection payloads |

## Personal Notes

> **Note (personal):** I'm using this fork primarily to study SSRF and SSTI techniques for a CTF series. The SQL Injection and XSS Injection sections have been especially useful — worth reading those READMEs end-to-end before diving into the others.
>
> **Study order that worked for me:** XSS Injection → CSRF Injection → SSRF → SSTI → SQL Injection. Starting with XSS first gave good context for understanding how client-side trust issues escalate into server-side ones.
>
> **CTF-specific reminder:** For SSTI, Jinja2 (Python/Flask) and Twig (PHP) are the most common in CTFs. Freemarker (Java) shows up occasionally in HackTheBox machines — worth having a cheat sheet handy for that one too.
>
> **Useful external refs:** [HackTricks SSTI](https://book.hacktricks.xyz/pentesting-web/ssti-server-side-template-injection) and [PortSwigger Web Security Academy](https://portswigger.net/web-security) are good companions to the payloads here.
