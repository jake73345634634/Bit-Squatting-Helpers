
<h3>🐬 Bit Squatting Helpers</h3>
<p>
  <a href="https://en.wikipedia.org/wiki/Bitsquatting">Wikipedia</a> •
  <a href="https://www.youtube.com/watch?v=aT7mnSstKGs">Defcon</a>
</p>

---
✨ Bitsquatting is a form of cybersquatting which relies on bit-flip errors that occur during the process of making a DNS request.

This repository contains a script to generate domains that differ by a single bit, query GoDaddy to check the availability, and return the results.

---
<h4>Usage</h4>

```
PS D:\Bit-Squatting-Helpers> python3 bitsquat.py --api-key REDACTED --domain github.com
[-] github.com
[+] çithub.com
[-] 'ithub.com
...
```
