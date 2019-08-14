# 5 Open Source Vulnerabilities You Should Know About
Whether you are a developer who directly uses open source software, libraries, and frameworks in your work, or you are reading from a business perspective, you probably understand the usefulness of open source in terms of facilitating the agility required of modern software development teams. 

An important early advocate of the free software model was Bruce Perens, who published the Debian Free Software Guidelines, which later became The Open Source Definition. Thanks to people like Perens, modern developers get free access to well-built code which they can adapt to their needs and use as the building blocks for proprietary applications. 

A [2018 report](https://www.synopsys.com/content/dam/synopsys/sig-assets/reports/2018-ossra.pdf) featuring an audit of 1,100 commercial codebases found 96 percent of them used open source components and the average number of components per application was 257. According to the report, this figure is consistent with similar audits conducted on thousands of other codebases over the previous two years. 

However, [research from 2017](https://www.slideshare.net/secret/bEoOc8BYLU48Zj) found that 1 in 18 downloaded open source components contained a vulnerability. So, combined research shows that open source adoption is widespread but that organizations and development teams aren’t managing their open source usage adequately. 

This article discusses five important open source vulnerabilities along with some best practices for improved open source vulnerability management and better security ([see this article by WhiteSource](https://resources.whitesourcesoftware.com/blog-whitesource/open-source-vulnerability-management) with some insights on the subject). 

**1. ShellShock**

News of the Shellshock privilege escalation vulnerability that targeted web servers first came to light in 2014. The family of exploits targets the Unix Bash shell, which is used by many web applications. It gives attackers a means to execute arbitrary commands and thus gain unauthorized access to a system, facilitating the creation of a botnet which can perform DDoS attacks.  

This is a particularly interesting example of a vulnerability that refuses to go away because it is very low-cost to attempt to exploit it. Surprisingly, [according to IBM](https://securityintelligence.com/cheap-shock-why-shellshock-is-still-a-thing/), 10 percent of servers remain unpatched for this flaw.  

**2. SegmentSmack**

A moderate vulnerability known as SegmentSmack in the Linux Kernel was found in July 2018. Some media outlets reported that this bug didn’t affect enterprise-grade distributions of Linux, however, this was proven to be untrue when [Red Hat announced](https://access.redhat.com/articles/3553061) that Red Hat Enterprise Linux versions 7 and 6 were both affected by the vulnerability, necessitating an update to the Linux kernel. 

This vulnerability makes the list because it is relatively recent, many developers use Red Hat as a platform for software development, and it just goes to show the importance of doing proper research on bugs to see whether they actually affect you.

 
**3. glibc**

Anyone involved in web development should know about the glibc vulnerability, not because it remains unfixed for a significant portion of companies, but because it’s an example of a zero-day vulnerability that went unrecognized for eight years! 

The exploit found its way into glibc version 2.9 2008 but was only patched in the 2016 release of glibc 2.23. The majority of Internet-facing applications use glibc, which is an open source library. The glibc vulnerability highlights the need for a preventative vulnerability detection tool that can detect and alert you on zero-day exploits before they cause damage. 

**4. Heartbleed**

Heartbleed, which 99% of devs have no doubt heard of, is an OpenSSL vulnerability. First disclosed back in 2014, Heartbleed put sensitive information at risk by enabling hackers to steal information normally protected by SSL or TLS encryption. The healthcare industry was impacted profoundly by Heartbleed. 

Given that in industries such as healthcare, 80 percent of software vulnerabilities are over three months old, it’s worth reminding you of the Heartbleed bug as a case-in-point on the importance of maintaining visibility over open source components and their vulnerabilities. Shockingly, it was revealed in 2017 that almost 200,000 websites were still vulnerable to the Heartbleed bug; nearly three years after a fix was released. 


**5. Apache Struts** 

Even people outside of development circles became familiar with Apache Struts when it was revealed that a vulnerability in Struts was behind the infamous Equifax data breach of 2017, for which a patch existed but was not applied by Equifax. The 2017 vulnerability again exemplifies the potential magnitude of what happens when you don’t update your open source software. 

However, and tying in nicely here, a more recent vulnerability was found in the same [Apache Struts](https://www.infosecurity-magazine.com/news/crypto-jackers-exploit-critical/) framework when it was found hackers could trivially and maliciously install a popular cryptocurrency miner on victim systems by exploiting improper validation of namespace input data.

## Closing Thoughts

The existence of vulnerabilities is no reason to halt the use of open source software in development. After all, this model continues to prove its benefits both to individual developers and entire organizations.
