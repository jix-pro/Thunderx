# Thunderx

![](./docs/images/logo/Malcolm_outline_banner_dark.png)

Thunderx is a powerful network traffic analysis tool suite designed with the following goals in mind:

* **Easy to use** – Thunderx accepts network traffic data in the form of full packet capture (PCAP) files, Zeek logs, and Suricata alerts. These artifacts can be uploaded via a simple browser-based interface or passively captured live and forwarded to Thunderx using lightweight forwarders. In either case, the data is automatically normalized, enriched, and correlated for analysis.
* **Powerful traffic analysis** – Visibility into network communications is provided through two intuitive interfaces: OpenSearch Dashboards, a flexible data visualization plugin with dozens of prebuilt dashboards providing an at-a-glance overview of network protocols; and Arkime, a powerful tool for finding and identifying the network sessions comprising suspected security incidents.
* **Streamlined deployment** – Thunderx operates as a cluster of software containers – isolated sandboxes that each serve a dedicated function of the system. This container-based deployment model, combined with a few simple scripts for setup and run-time management, makes Thunderx suitable to be deployed quickly across a variety of platforms and use cases; whether it be for long-term deployment on a Linux server in a security operations center (SOC) or for incident response on a Macbook for an individual engagement.
* **Secure communications** – All communications with Thunderx, both from the user interface and from remote log forwarders, are secured with industry standard encryption protocols.
* **Permissive license** – Thunderx is comprised of several widely used open-source tools, making it an attractive alternative to security solutions requiring paid licenses.
* **Expanding control systems visibility** – While Thunderx is great for general-purpose network traffic analysis, its creators see a particular need in the community for tools providing insight into protocols used in industrial control systems (ICS) environments. Ongoing Malcolm development will aim to provide additional parsers for common ICS protocols.

Although all the open-source tools that make up Thunderx are already available and in general use, Thunderx provides a framework of interconnectivity that makes it greater than the sum of its parts.

In short, Thunderx provides an easily deployable traffic analysis tool suite for network security monitoring.


