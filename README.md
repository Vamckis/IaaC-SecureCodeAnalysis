# IaaC-SecureCodeAnalysis
- pip3 install checkov

## KICS
- brew install Checkmarx/tap/kics
- export KICS_QUERIES_PATH=/opt/homebrew/opt/kics/share/kics/assets/queries

### If QueryPath (-q) is not provided, tool will use default path ./assets/queries
- kics scan -p . -q /Users/vamsisukla/assets/queries --report-formats "all" -o ./Report
