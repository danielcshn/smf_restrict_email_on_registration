<div align="center">
  <h3> Restrict Email Providers / Domains / TLDs on Registration </h3>
  <hr>
  <p>Compatibility: SMF 2.1.X, Simple Machines</p>
  <hr>
</div>

<div align="center">
  
[![GitHub issues](https://img.shields.io/bitbucket/issues/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/issues)
[![GitHub watchers](https://img.shields.io/github/watchers/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/watchers)
[![GitHub forks](https://img.shields.io/github/forks/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/fork)
[![GitHub stars](https://img.shields.io/github/stars/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/stargazers)
[![License](https://img.shields.io/github/license/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/blob/main/LICENSE)
[![GitHub last commit](https://img.shields.io/github/last-commit/danielcshn/smf_restrict_email_on_registration?style=for-the-badge)](https://github.com/danielcshn/smf_restrict_email_on_registration/commits/main)

</div>

---

## Description:
This modifications allows the administrator to restrict or accept certain E-Mail Providers and/or Domains during the registration process. This is extremely useful to fight spam and block disposable email services, or to only allow registrations from specific country domains or corporate domains.

## Features:
- <b>Restrict Providers:</b> Block specific email providers (e.g., @hotmail.com, @gmail.com). Anyone trying to register with these providers will be rejected.
- <b>Accept Providers:</b> Create an exclusive list of email providers. If you fill this list, ONLY users with these providers can register. Anyone else will be rejected.
- <b>Restrict Domains/TLDs:</b> Block entire domain suffixes or country codes (e.g., .ru, .cn, .xyz).
- <b>Accept Domains/TLDs:</b> Create an exclusive list of accepted domain suffixes (e.g., .es, .ar, .com). ONLY users whose email ends with these domains will be able to register.
- <b>Languages: </b> English, Spanish, Spanish Latin, Italian, Portuguese Brazilian.

## How to use:
1. Install the mod via Package Manager.
2. Go to the mod settings section in your Admin Panel.
3. Enable the restriction feature by checking the box.
4. Fill in the comma-separated lists for the providers or domains you wish to restrict or exclusively accept.

| :warning: IMPORTANT NOTE          |
|:--------------------------------------|
| Keep the "Accepted" lists empty unless you want to aggressively block EVERY OTHER provider or domain! |

---

## 📝 License

```
MIT License

Copyright (c) 2026 danielcshn

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```