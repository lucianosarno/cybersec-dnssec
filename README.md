# DNSSEC Process Diagrams

This repository contains professional diagrams designed to clarify the Domain Name System Security Extensions (DNSSEC) process. The diagrams illustrate both the standard DNS resolution flow and highlight potential attack scenarios that can arise in the absence of DNSSEC protection.

## Purpose

- **Educational Clarity:** The diagrams aim to provide a clear, visual explanation of how DNSSEC secures DNS queries and responses.
- **Comprehensive Coverage:** Both typical DNS resolution steps and vulnerabilities exploitable without DNSSEC are depicted, helping users understand the importance of DNSSEC in modern internet infrastructure.

## Contents

- **technical_version.mmd:** A detailed sequence diagram showing the step-by-step DNS resolution process, including where DNSSEC validation occurs and what happens if DNSSEC is not present.
- **executive_version.mmd:** A high-level overview suitable for non-technical audiences, summarizing the key points of DNSSEC and its role in preventing attacks.

## Attack Scenarios

The diagrams also demonstrate how attackers can exploit DNS when DNSSEC is not implemented, such as:

- Cache poisoning
- Man-in-the-middle attacks
- Unauthorized DNS record modifications

## Usage

These diagrams are intended for:

- Security professionals
- Network engineers
- Educators and students
- Anyone interested in understanding DNSSEC and DNS security

## License

This repository is provided for educational and informational purposes. Please refer to the LICENSE file for usage terms.

---

For questions or suggestions, feel free to open an issue or contact the repository maintainer.
