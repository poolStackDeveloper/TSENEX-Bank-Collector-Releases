## TSENEX Bank Collector v1.0.9

- Windows x64 update package
- Detects successful certificate login at 100 ms intervals
- Starts transaction collection immediately after the authenticated page appears
- Returns directly to the protected transaction page when KB lands on the corporate home page
- Removes repeated full-page action scans from login completion checks
- Opens the protected KB transaction route immediately when collection starts
- Clicks the certificate login button as soon as the page exposes it
- Removes redundant page reloads and fixed pre-login waits
- Downloads the latest 31 days of KB transactions on every collection
- Relies on file-level and transaction-level deduplication for overlapping downloads
- Opens certificate login from KB's protected corporate transaction page
- Verifies the enterprise obiz context and transaction return target before prompting
- Avoids the generic login route that returned users to the public home page
- Preserves the verified certificate session without reopening the login-protected page
- Rechecks stale certificate return URLs against the protected transaction page
- Writes URL and authentication-state metadata beside failure screenshots
- Preserves Korean error messages in the collector log
- Collects only registered accounts visible in the currently selected corporate certificate
- Detects KB form-based Excel downloads and saves the completed XLS file reliably
- Treats a valid query with no transactions as a successful empty result
- Certificate passwords, ERP secrets, account settings, and bank data are excluded
- SHA-256 checksum is provided for package validation

### Files

- TSENEX-Bank-Collector-win-x64.zip
- TSENEX-Bank-Collector-win-x64.zip.sha256
