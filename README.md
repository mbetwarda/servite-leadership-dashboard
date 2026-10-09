# Servite Leadership Dashboards

Password-protected financial dashboards for the Servite High School leadership team
(leadership overview plus department pages, budget vs actual).

`index.html` contains only encrypted data (AES-256-GCM, PBKDF2-SHA256 key). Nothing is
readable without the password, which is shared with the leadership team separately.

Source data: Blackbaud Financial Edge NXT General Ledger reports and the FY 2026–27
Original Operating Budget. Updated monthly.
