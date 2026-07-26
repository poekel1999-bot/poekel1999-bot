# Hi, I'm Martin 👋

I am an independent software developer and technical researcher focused on building privacy-first, security-focused systems and exploring new possibilities in software engineering.

My work spans programming-language and compiler development, native applications, operating systems, secure communication, business software, and experimental security architecture.

## Current focus

### Cipher

Cipher is an experimental privacy- and security-focused programming language with an LLVM backend.

The project explores how security, privacy, and safe data handling can be enforced by the language and compiler, rather than depending entirely on developer discipline, external libraries, or runtime checks.

Current areas of development include:

* Compile-time information-flow control
* Tracking and restricting sensitive data
* Capability-based security
* Native machine-code generation
* Fail-closed security behavior
* Cryptographic and runtime safety
* Secure asynchronous and network operations
* Memory- and integer-safety hardening
* Filesystem and path-confinement security
* Regression testing for security-critical behavior
* New language-level privacy and security guarantees

## Security and software research

My work is not limited to AI research. I conduct ongoing technical research into software security, programming-language design, compiler guarantees, cryptographic systems, operating-system architecture, and previously unexplored approaches to privacy and application safety.

This includes:

* Investigating weaknesses in software and system designs
* Performing repeated security-focused reviews and adversarial audits
* Designing protections that prevent insecure behavior by construction
* Exploring security properties that can be enforced at compile time
* Researching alternatives to conventional permission and trust models
* Developing new approaches to data ownership, privacy, and controlled information flow
* Testing whether unusual or ambitious technical ideas can be converted into working systems
* Revisiting limitations that are normally accepted as unavoidable and searching for stronger solutions

The goal is not only to reproduce existing software patterns, but also to investigate what becomes possible when security and privacy are treated as foundational language and system properties.

## Other work

Alongside Cipher, I work on projects involving:

* Operating-system development
* Privacy-focused applications
* Secure communication systems
* Internal business and workflow software
* Web and mobile applications
* File and data protection
* AI-assisted software engineering
* Experimental software architecture

## AI safety research

One research direction investigates how programming languages, compilers, and automated verification can make software generated or modified by AI coding agents safer.

This includes evaluating whether compiler-enforced information-flow control, capability restrictions, and fail-closed rules can detect and prevent security failures in AI-generated software.

AI-assisted development is also used as part of a broader review process in which different models inspect architecture, implementations, tests, and security assumptions. Their findings are manually evaluated, tested, and incorporated where technically justified.

## Development approach

I prefer building systems with security, privacy, maintainability, and clear architecture as foundational requirements rather than adding them after development.

My projects use iterative implementation, automated testing, adversarial review, repeated security-focused audits, and cross-model technical analysis to identify weaknesses and improve the underlying design.

I actively explore unconventional possibilities, but treat implementation, testing, reproducibility, and verifiable behavior as the standard for determining whether an idea succeeds.

## Current status

Public technical documentation and reproducible research material for Cipher are being prepared.

The primary Cipher source repository is currently private while the project architecture, documentation, intellectual property, and public research scope are being reviewed.
