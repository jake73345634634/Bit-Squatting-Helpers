<h3>🐬 Bit Squatting Helpers</h3>
<p>
  <a href="https://en.wikipedia.org/wiki/Bitsquatting">Wikipedia</a> •
  <a href="https://www.youtube.com/watch?v=aT7mnSstKGs">Defcon</a>
</p>

---
✨ Bitsquatting is a form of cybersquatting which relies on bit-flip errors that occur during the process of making a DNS request.

Generate domains that differ by a single bit and query GoDaddy to check the availability.

---
<h4>Requirements</h4>

A GoDaddy API key is required. See [here](https://developer.godaddy.com/getstarted) to get started.

---
<h4>Usage</h4>

```
PS D:\Bit-Squatting-Helpers> python3 bitsquat.py --api-key REDACTED --domain github.com --verbose
[-] github.com
[+] çithub.com
[-] 'ithub.com
...
```
