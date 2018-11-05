# What is DMARC

*Domain-based Message Authentication, Reporting and Conformance (DMARC)* is an email authentication technology to stop exact-domain email spoofing (e.g. if "example.com" is protected by DMARC, only emails send from "any@example.com" are authenticated, and "any@example.net" emails can bypass the authentication system). The other exact-domain email spoofing protection systems such as Sender Policy Framework (SPF) and DomainKeys Identified Mail (DKIM) alone have vulnerabilities, which allow attackers to bypass those mechanisms. Built on top of SPF and DKIM, DMARC provides features to cover weaknesses of SPF and DKIM ("DMARC Alignment" feature), and additionally allows owner of a domain to control how the receiver mailbox provider should deal with email authentication failures("DMARC Policy" feature). To eliminate mistakes of configuring the DMARC (valid emails can be rejected too), "DMARC Reporting" feature gives a visibility to understand who actually sends an email from particular domain, which helps administrators to tune and configure SPF and DKIM records correctly and find out sources of threats. _DMARC is the only true way of preventing exact-domain phishing attacks_.

## Specifications 

- [Domain-based Message Authentication, Reporting and Conformance (DMARC), RFC 7489](http://tools.ietf.org/html/rfc7489) - Updated on February 5, 2015
- [Interoperability Issues between DMARC and Indirect Email Flows, RFC7960](http://tools.ietf.org/html/rfc7960) - Updated on September, 2016


## Features

### DMARC Policy
TODO

### DMARC Alignment
TODO

### DMARC Reporting
TODO






