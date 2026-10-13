# Security Policy

> A web version of this policy also lives at [isaacadjei.me/security-policy](https://isaacadjei.me/security-policy).

This is the security policy for all my projects, software or hardware. I keep the full version here in one place so every repository can point to it.

## Reporting a vulnerability

> [!IMPORTANT]
> Please report a security problem privately. Do not open a public issue, pull request or discussion for it.

The preferred route is GitHub's private vulnerability reporting. Open the affected repository's **Security** tab and choose **Report a vulnerability**. You can also go straight to `https://github.com/zaccesss/<repo>/security/advisories/new` with the repository's name in place of `<repo>`. For the website, use [the report form for isaacadjei.me](https://github.com/zaccesss/isaacadjei.me/security/advisories/new). Only you and I can see the report, it supports attachments and the fix can be tracked against it.

You can also email contact@isaacadjei.me with the subject line `Security Disclosure`. If email is not convenient, the [contact page](https://isaacadjei.me/contact) works too, though it takes no attachments, so paste any supporting material inline.

Please include:

- the affected repository, URL or component
- your browser, device and operating system where relevant
- steps to reproduce it or a proof of concept
- what you expected to happen and what actually happened
- the impact you think it could have

## Response timeline

- Acknowledgement within 3 business days
- Assessment and triage within 7 business days
- A fix or a mitigation plan within 30 days for valid issues

## Scope

This covers the code, hardware designs and content in my repositories, along with my sites at [isaacadjei.me](https://isaacadjei.me) (and all its subdomains) and [zacess.com](https://zacess.com).

Vitafolio, PHAEMOS and MELOPHOS each have their own policy, so report issues in those projects there: [Vitafolio](https://github.com/zaccesss/vitafolio/blob/main/SECURITY.md), [PHAEMOS](https://github.com/phaemos/.github/blob/main/SECURITY.md) and [MELOPHOS](https://github.com/melophos/.github/blob/main/SECURITY.md).

## Out of scope

- Third-party services and platforms I use, for example GitHub, a hosting provider or a cloud service. Please report those to the provider directly.
- Vulnerabilities in third-party dependencies. Those are best raised with the dependency itself, though I am glad to know if one affects a project of mine.
- Denial of service attacks or volumetric testing of any kind.
- Social engineering or phishing attempts targeting me or visitors.
- Issues that need physical access to my devices.
- Missing security headers with no practical exploit path.
- Reports from automated scanners without manual validation.

## Good faith

I will not take legal action against researchers who act in good faith, follow this policy and do not access, modify or delete data beyond what is needed to show the vulnerability. Valid reporters are credited on the [Hall of Fame](https://isaacadjei.me/hall-of-fame).

## After you report

Please give me a reasonable chance to fix the issue before disclosing it publicly. I will happily credit you when I write up the fix, if you would like that.
