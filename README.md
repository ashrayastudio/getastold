# As Told support website

Static website and support-email privacy notice for `getastold.com`.
This is not the iOS application or its full privacy policy.

## Routes

- `/` — product update and shared support contact.
- `/privacy` — website hosting and support-email privacy.
- `/privacy.html` — the same privacy document.

`getastold.app` is the intended path-preserving companion redirect.
DNS, HTTPS and deployment readiness must be verified independently of source.

## Checks

```sh
python3 -B validate_site.py
python3 -B validate_site.py --self-test
```

GitHub Pages serves only `main:/docs`, keeping internal instructions and
validation code off the website. No dependency installation,
JavaScript, analytics, external assets or build framework is needed.
