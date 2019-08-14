# 5 Open Source SIEM Solutions to Consider
![](https://cdn.pixabay.com/photo/2018/05/14/16/25/cyber-security-3400657_1280.jpg)

Security Information and Event Management (SIEM) is a type of IT security system or software that gathers log and event data from different components of an organization’s IT infrastructure, monitors security threats in real-time using correlation rules, and allows security professionals to visualize threats on a central dashboard. 

SIEM software is also useful in assisting organizations with meeting their compliance requirements. In fact, the need to simplify compliance with regulations like [PCI DSS](https://resources.infosecinstitute.com/siem-use-cases-pci-dss-3-0-part-1/#gref) is one of the main factors that drives the adoption of SIEM software. SIEM automates many aspects of compliance, including gathering compliance data and producing relevant reports. PCI DSS is a regulation that organizations accepting credit card payment need to comply with. 

For example, PCI DSS requirement 12.5.4 stipulates that organizations should administer user accounts, including additions, deletions, and modifications. A SIEM use case to meet this requirement is to monitor event data for the addition, deletion, or modification of user credentials. 

To get more technical information on the specifics of what SIEM is and how it works, check out this [what is SIEM?](https://www.exabeam.com/siem-guide/what-is-siem/) guide.
 
### Open Source vs Paid SIEM

Organizations looking to add SIEM capabilities to their IT security and compliance arsenal can generally choose between either a commercial product or open source software and tools. Commercial SIEM systems are generally more feature-rich and they include all core SIEM capabilities such as event correlations and reporting. Furthermore, when purchasing an enterprise-level SIEM tool, you’ll usually get support included for that tool with the cost price. 

However, many organizations and smaller businesses either cannot afford such products or they prefer working with open source tools. It is quite possible to implement an open source SIEM solution, but it’s important to note that when using open source, this will typically involve bringing multiple tools together to achieve the required functionality. 

The beauty of the open source model is that you get high-quality code and SIEM capabilities for free and you can modify the code as you wish. The following are some examples of SIEM tools you can use if you opt to go down the open source route. 

### Open Source SIEM Tools

**1. OSSIM**

OSSIM is an open source SIEM system that combines native log storage and correlation capabilities with a range of tools from other open source projects to help it closely replicate the functionality of a proprietary SIEM system. 

The open source projects integrated with OSSIM include OpenVAS, Munin, and Snort. Users access all available tools and configurations from a browser-based interface. OpenVAS is an open source vulnerability assessment tool that uses correlations between logs and vulnerability scanners to identify advanced threats. 

OSSIM is an excellent option for smaller SIEM deployments but it may experience performance issues when scaling it up to the needs of a large organization. 

**2. OSSEC**

OSSEC is an open source [intrusion detection system](https://searchsecurity.techtarget.com/definition/intrusion-detection-system) (IDS) that monitors host computer systems for suspicious network activity. This tool works with a slew of operating systems, including Windows, MacOS, Solaris, and Linux. 

The architecture of OSSEC is such that you can use it on multiple types of systems, including computers, firewalls and routers. You can monitor multiple systems from a centralized location and integrate it with a visualization dashboard like Kibana, giving you a more intuitive view over network activity data and alerts. OSSEC also has a log analysis engine that can correlate log data.   

**3. SIEMonster**

This open source SIEM software is available in both free and premium options. This particular tool is composed of a range of underlying open source components that deliver most of the major functions expected of any SIEM software. 

There is a [Kibana](https://github.com/elastic/kibana) user interface to enable data visualization and a separate Mine|Meld user interface for threat intelligence purposes. You can also set up event-based alerts from the dashboard. 

**4. Prelude**

Prelude is another handy open source SIEM project. Prelude is similar to OSSIM in that it is a framework that unifies other open source projects to deliver necessary SIEM functions. Prelude gathers log and event data from many sources and stores the data in the IDMEF format. Among the main SIEM capabilities are the ability to set up correlation rules, data filtering, analytic tools, and data visualization. 

There is a commercial counterpart to Prelude, and the official documentation highlights that the open source version is for evaluation, research and test purposes in very small environments. Therefore, larger organizations might have trouble in getting adequate performance from this tool. 

**5. ELK**

The ELK stack is an open source solution composed of three different open source projects: Elasticsearch, Logstash, and Kibana. You’ve already found out about Kibana as a visualization tool. Elasticsearch is a search and analytics engine and Logstash is a data processing pipeline. The ELK stack is not a SIEM tool in itself but it can be used for SIEM purposes. 

Logstash can receive log data from multiple sources and correlate that data while Elasticsearch helps to store and index data. Together with Kibana, this stack provides the building block for a robust SIEM system. However, the ELK stack does not come with inbuilt reporting or alerting, and you may have to pay an extra fee for those components. 

**Wrap Up**

There are some really good open source options available for organizations looking to implement SIEM. The main limitations are typically performance at scale and steep learning curves. Whether you opt for commercial or open source, SIEM can help with a range of IT security and compliance functions. 
