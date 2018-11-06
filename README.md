## What is DMARC
*Domain-based Message Authentication, Reporting and Conformance (DMARC)* is an email authentication technology to stop exact-domain email spoofing (e.g. if "example.com" is protected by DMARC, only emails send from "any@example.com" are authenticated, and "any@example.net" emails can bypass the authentication system). The other exact-domain email spoofing protection systems such as Sender Policy Framework (SPF) and DomainKeys Identified Mail (DKIM) alone have vulnerabilities, which allow attackers to bypass those mechanisms. Built on top of SPF and DKIM, DMARC provides features to cover weaknesses of SPF and DKIM ("DMARC Alignment" feature), and additionally allows owner of a domain to control how the receiver mailbox provider should deal with email authentication failures("DMARC Policy" feature). To eliminate mistakes of configuring the DMARC (valid emails can be rejected too), "DMARC Reporting" feature gives a visibility to understand who actually sends an email from particular domain, which helps administrators to tune and configure SPF and DKIM records correctly and find out sources of threats. _DMARC is the only true way of preventing exact-domain phishing attacks_.

## Specifications 

- [Domain-based Message Authentication, Reporting and Conformance (DMARC), RFC 7489](http://tools.ietf.org/html/rfc7489) - Updated on February 5, 2015
- [Interoperability Issues between DMARC and Indirect Email Flows, RFC7960](http://tools.ietf.org/html/rfc7960) - Updated on September, 2016
- [Sender Policy Framework (SPF) for Authorizing Use of Domains in Email, RFC7208](https://tools.ietf.org/html/rfc7208) - Updated on April, 2014
- [DomainKeys Identified Mail (DKIM) Signatures, RFC6376](https://tools.ietf.org/html/rfc6376) - Updated on September, 2011
- [Simple Mail Transfer Protocol (SMTP), RFC5321](https://tools.ietf.org/html/rfc5321) - Updated on October, 2008
- [Internet Message Format(IMF), RFC5322](https://tools.ietf.org/html/rfc5322) - Updated on October, 2008


## DMARC Aggregated Report Analyzers

### Open Source Projects

- [End-to-end DMARC report generation tool supporting PowerBI](https://gallery.technet.microsoft.com/scriptcenter/Harvest-DMARC-items-for-9c0d911a)
- [A Perl based tool to parse DMARC reports](https://github.com/techsneeze/dmarcts-report-parser)

### Free Online Analizers (with limitations)

- [EasyDMARC](https://easydmarc.com) - [DMARC Aggregated Reports XML Analyzer](https://easydmarc.com/tools/dmarc-aggregated-reports)
- [Dmarcian](https://dmarcian.com) - [XML to Human Converter](https://dmarcian.com/xml-to-human-converter/)

<a href="https://twitter.com/intent/tweet?button_hashtag=DMARC&ref_src=twsrc%5Etfw" class="twitter-hashtag-button" data-show-count="false">Tweet #DMARC</a><script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>







