# Vulnerabilities Management: 5 Ways to Find and Fix Open-Source Vulnerabilities

![](https://cdn.pixabay.com/photo/2016/12/21/17/39/cyber-security-1923446_960_720.png)
*Image source: [Pixabay](https://pixabay.com/illustrations/cyber-security-internet-security-1923446/)*

## Overview

Open source adoption continues to grow at enterprises and other organizations. Development teams often use well-built operating systems, libraries, and frameworks as the building blocks of commercial or non-commercial applications. Ready-made open source software like database programs can support internal IT infrastructure. 

Using open source components is a cost-effective way to meet the need for speed and agility with modern development practices. However, open source comes with its own security challenges, and failing to meet them can expose organizations to serious vulnerabilities. Read on to find out about open source security issues and five ways to find and fix these issues. 
## Open Source Security Issues

**Lack of open source visibility**

This open source security risk comes from poor management of open source use rather than an inherent lack of security in open source components and software. Just [28 percent of organizations](https://www.csoonline.com/article/3157377/open-source-software-security-challenges-persist.html) regularly analyze applications to get visibility into which open source components their dev teams are using. Without a full and transparent open source inventory, vulnerabilities in applications can easily go unnoticed. 

**Not applying updates on time**

Another risk responsible for many recent high-profile data breaches is the failure to promptly apply updates to open source components. Patches in open source projects often address vulnerabilities that can expose organizations to serious vulnerability issues. Opportunistic hackers can easily see when an open source project is updated to address a security issue, and they can use this knowledge to find victims that are slow to update. 

**Lack of security standardization**

The community-driven way of maintaining open source projects leads to a lack of security standardization across the industry. Just [42 percent of project maintainers audit open source code](https://thenewstack.io/ossmaintainer_security/) at least once per quarter. Furthermore, many of the leading public Github repositories do not have security documentation. 

When open source maintainers find and fix problems, most of them add the security-related announcements to the release notes. However, the majority of maintainers do not catalog vulnerabilities in the CVE database due to both a lack of understanding of the process and not enough time. 

## 5 tips for Finding and Fixing Open Source Vulnerabilities

**1. Set Open Source Rules and Standards**

It’s tough to blame developers to using vulnerable components without a consistent set of standards around open source use. Organizations need to prioritize creating an open source policy that clearly educates about open source risks and instructs on best practices for safe open source use. 

Standards can include having to prove the security of the component before using it and never downloading components from untrusted repositories. 

**2. Learn About CVSS v3**

Developers and IT security teams should become familiar with the [CVSS v3 changes](https://resources.whitesourcesoftware.com/blog-whitesource/cvss-v3-creates-new-challenges-for-developers) that score vulnerabilities differently from previous versions. Some vulnerabilities rated medium severity under the previous CVSS version would receive a high severity rating in the new version, calling for faster remediation. CVSS v3 is the latest update to the Common Vulnerability Scoring System, which quantifies the severity of vulnerabilities. 

Not all vulnerabilities are equally severe, and an important part of securing open source is knowing the issues that need immediate remediation. 

**3. Get an Open Source Inventory**

Getting a transparent inventory of all open source components and dependencies you use is imperative in finding and fixing vulnerabilities. Disregard outdated methods like spreadsheets—development teams need something more efficient that runs with minimal effort and doesn’t waste their time. 

Software composition analysis solutions run continuously and generate an inventory of all the components that make up an application. Some tools even come with automated security and license policy enforcement. Make sure you have an inventory of components both in development and in production. 

**4. Always Use Updated Components**

A good inventory also shows the latest version of each open source component. Use this to your advantage and encourage developers to always update components promptly. It’s important to remember that the latest patches often address important vulnerabilities for which no official CVE database entry exists yet because developers didn’t create one. 

An automated tool like commit watcher can help you keep a closer eye on security issues by scanning the release notes or messages accompanying code commits for phrases such as “XSS attack fix”. Proactively monitoring commits like this can lead to faster detection of vulnerabilities and quicker updates. 

**5. Consider Building Components In-House**

If an open source project is active and well-supported with a reasonably sized developer community, there is no reason to stop using it. However, you should consider building your own in-house tools to replace unsupported or expired components. The time and cost to build a replacement tool are well-spent if they give you back control over security. 

Some larger companies have even started to build libraries and components as replacements for unsupported projects and release them under an open source license. Microsoft is an example of this, and the result has been more trust and respect from open source developers. Another positive of releasing back into the open source community is improved component security due to more developers submitting patches and revisions.

## Conclusion

Open source components are generally safe if organizations manage their use properly. Having a large community of active developers contributing to and maintaining an open source project doesn’t guarantee anything about security, so it is important to have your own defenses in place. 

Document an open source policy, get visibility into open source components, and keep up with the CVSS v3 to assess vulnerability severity. Lastly, make sure that any tools you use for finding and fixing open source vulnerabilities facilitate DevOps, Agile, and CI/CD practices by not slowing down development.
