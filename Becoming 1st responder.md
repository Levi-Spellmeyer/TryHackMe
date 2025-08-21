

<h1>Becoming a First Responder</h1> 
<p>this room covers first responders work and what to do if you are a first responder to a cyber incident. </p>

<hl>
<h3>Volatility of Evidence</h3>
<p>Most important thing to remember is to not disconnect power or network connections as this may alarm malicious actor that they are compromised or clear caches that could hold important information. Order of volatility is as follows (most volatile at the top):</p>

1. Registers and cache - Most volatile and in most instances is not captured as it changes to much
2. Routing Table, ARP Cache, Process Table, Kernel Statistics and Memory - We want to know if and who the compromised host communicated with (Routing). We capture the memory, if possible, to try and get a picture of what process where ran and what they do.
3. Temporary File system - Files that are stored on host while interacting with application
4.  Disk - Important for legal action and for the sake of checking host logs to determine threat actor's actions
5.  Remote Logging and Monitoring - Preserve all logs as far back as possible to potentially trace long term threat actor activity.
6.  Physical configuration and network topology - helps create scope of incident
7. Archival Media - Backups can be used for comparisons.

<p>Don't trust software and processes on the infected host. Use programs on usb or other devices to collect evidence</p>

---

<h3>Provided Links</h3>
- [RFC 3227 - Guidelines for Evidence Collection and Archiving](https://datatracker.ietf.org/doc/html/rfc3227#section-2.1)
