## TSENEX Bank Collector v1.0.6

- Windows x64 update package
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
