name: Automated Test Failure
description: File a test report.
- **Workflow**: `${{ github.workflow }}`
- **Job**: `${{ github.job }}`
- **Commit**: `${{ github.sha }}`