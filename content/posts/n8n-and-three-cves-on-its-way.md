+++
date = '2025-07-31T22:10:37-03:00'
draft = false
author = 'Security Research Team' 
title = 'N8N and three CVEs on its way'
+++

[n8n](https://n8n.io/) is basically Lego for automation: you snap little blocks *— called nodes —* together to make something cool for you or your team. There are trigger nodes, action nodes, logic nodes, you name it. Chain them up and voilà: *“when someone clicks, hit this API; if the response is 200 OK, drop a message in my Telegram.”*

This takes a ton of grunt work off dev teams and even lets non-coders get things done.

But heads-up: mis-configure it or ignore security best practices and n8n turns into a **double-edged sword**.

---

*— Whoever threads finely in the code uncovers holes beneath the carpet —*

### [[CVE-2025-49595](https://github.com/advisories/GHSA-pr9r-gxgp-9rm8)] Denial of Service via Malformed Binary Data Requests

asd
`code`

### [[CVE-2025-52554](https://github.com/advisories/GHSA-gq57-v332-7666)] Improper Authorization through its /stop endpoint 


```
code
```

### [[CVE-2025-XXXXX](https://github.com/advisories/xxxxx)] XSS to ATO

asd
...

---

### Conclusion

Get to reading code. Human errors are the security researcher's lunch and code is the plate on which those errors are served.

Thanks for reading! *ACK*
