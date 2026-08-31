## TSENEX Bank Collector v1.0.5

- Windows x64 update package
- Uses KB's current corporate transaction page instead of the retired parent menu URL
- Preserves the verified certificate session without reopening the login-protected page
- Recovers stale certificate return URLs through the corporate banking home page
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
