Report Summary

┌──────────────────────────────────────────────────────────────────────────────────┬────────────┬─────────────────┬─────────┐
│                                      Target                                      │    Type    │ Vulnerabilities │ Secrets │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ fest-backend:0.2 (debian 13.7)                                                   │   debian   │       164       │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ Python                                                                           │ python-pkg │        8        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/blinker-1.9.0.dist-info/METADATA          │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/click-8.5.0.dist-info/METADATA            │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/flask-3.1.2.dist-info/METADATA            │ python-pkg │        1        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/itsdangerous-2.2.0.dist-info/METADATA     │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/jinja2-3.1.6.dist-info/METADATA           │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/markupsafe-3.0.4.dist-info/METADATA       │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/pip-26.2.2.dist-info/METADATA             │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/psycopg2_binary-2.9.10.dist-info/METADATA │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/werkzeug-3.1.3.dist-info/METADATA         │ python-pkg │        4        │    -    │
└──────────────────────────────────────────────────────────────────────────────────┴────────────┴─────────────────┴─────────┘
Legend:
- '-': Not scanned
- '0': Clean (no security findings detected)


fest-backend:0.2 (debian 13.7)
==============================
Total: 164 (UNKNOWN: 1, LOW: 61, MEDIUM: 58, HIGH: 44, CRITICAL: 0)

┌────────────────────┬─────────────────────┬──────────┬──────────────┬───────────────────────────────────┬───────────────┬──────────────────────────────────────────────────────────────┐
│      Library       │    Vulnerability    │ Severity │    Status    │         Installed Version         │ Fixed Version │                            Title                             │
├────────────────────┼─────────────────────┼──────────┼──────────────┼───────────────────────────────────┼───────────────┼──────────────────────────────────────────────────────────────┤
2026-10-28T10:43:25+05:30       INFO    [vuln] Vulnerability scanning is enabled
2026-10-28T10:43:25+05:30       INFO    [secret] Secret scanning is enabled
2026-10-28T10:43:25+05:30       INFO    [secret] If your scanning is slow, please try '--scanners vuln' to disable secret scanning
2026-10-28T10:43:25+05:30       INFO    [secret] Please see https://trivy.dev/docs/v0.76/guide/scanner/secret#recommendation for faster secret detection
2026-10-28T10:43:26+05:30       INFO    Detected OS     family="debian" version="13.7"
2026-10-28T10:43:26+05:30       INFO    [debian] Detecting vulnerabilities...   os_version="13" pkg_num=87
2026-10-28T10:43:26+05:30       INFO    Number of language-specific files       num=1
2026-10-28T10:43:26+05:30       INFO    [python-pkg] Detecting vulnerabilities...
2026-10-28T10:43:26+05:30       WARN    Using severities from other vendors for some vulnerabilities. Read https://trivy.dev/docs/v0.76/guide/scanner/vulnerability#severity-selection for details.

Report Summary

┌──────────────────────────────────────────────────────────────────────────────────┬────────────┬─────────────────┬─────────┐
│                                      Target                                      │    Type    │ Vulnerabilities │ Secrets │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ fest-backend:0.2 (debian 13.7)                                                   │   debian   │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ Python                                                                           │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/blinker-1.9.0.dist-info/METADATA          │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/click-8.5.0.dist-info/METADATA            │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/flask-3.1.2.dist-info/METADATA            │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/itsdangerous-2.2.0.dist-info/METADATA     │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/jinja2-3.1.6.dist-info/METADATA           │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/markupsafe-3.0.4.dist-info/METADATA       │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/pip-26.2.2.dist-info/METADATA             │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/psycopg2_binary-2.9.10.dist-info/METADATA │ python-pkg │        0        │    -    │
├──────────────────────────────────────────────────────────────────────────────────┼────────────┼─────────────────┼─────────┤
│ usr/local/lib/python3.13/site-packages/werkzeug-3.1.3.dist-info/METADATA         │ python-pkg │        0        │    -    │
└──────────────────────────────────────────────────────────────────────────────────┴────────────┴─────────────────┴─────────┘
Legend:
- '-': Not scanned
- '0': Clean (no security findings detected)

0
WARNING: This output is designed for human readability. For machine-readable output, please use --format.
IMAGE              ID             DISK USAGE   CONTENT SIZE   EXTRA
fest-backend:0.2   13d26c94d524        208MB         51.4MB
