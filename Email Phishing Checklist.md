# Email Phising/Spam Checklist

### 1. Email Header:

- [ ] Sender email address.
- [ ] Sender IP address.
- [ ] Reverse lookup of the sender IP address.
- [ ] Email subject line.
- [ ] Recipient email address (this information might be in the CC/BCC field).
- [ ] Reply-to email address (if any).
- [ ] Date/time.
  - **Tools:** - [Messageheader](https://toolbox.googleapps.com/apps/messageheader/analyzeheader), [Message Header Analyzer](https://mha.azurewebsites.net/),[Mailheader](https://mailheader.org), [IPinfo.io](https://ipinfo.io/), [Talos Reputation Center](https://talosintelligence.com/reputation)

### 2. Email Body:

- [ ] Any URL links (if an URL shortener service was used, then we'll need to obtain the real URL link).
- [ ] The name of the attachment.
- [ ] The hash value of the attachment (hash type MD5 or SHA256, preferably the latter).
  - **Tools:** - [URL Extractor](https://www.convertcsv.com/url-extractor.htm), [CyberChef](https://gchq.github.io/CyberChef/), [VirusTotal](https://www.virustotal.com/gui/)

### 3. Malware Sandbox:

- Follow the [Malware Checklist](https://github.com/algenisromero/CyberSec_Checklists/blob/1da3e6aee808aa873338d2e7227a03f6e4cac471/Malware%20Analysis%20Checklist.md) to analyze any possible malware extracted from email.
  - **_Tools:_** [Any.Run](https://app.any.run/), [Hybrid Analysis](https://www.hybrid-analysis.com/), [JOESecurity](https://www.joesecurity.org/)

### 4. Mitigation & Detection

- [ ] Block pishing/spam email addresses in mail clients.
- [ ] Block email attachement from unknown sources.
- [ ] Remove your email address from data broker lists.
- [ ] Use antimalware/antivirus software.
- [ ] Use of automation tools to speed up the analysis process.

### 5. Document, Report & Share:

- [ ] Document your findings.
- [ ] Create a report or executive summary from analysis results.
- [ ] Share with the cyber community.



</br>
</br>

> **_Warning:_** Be careful not to click on any links or attachments in the email accidentally.
