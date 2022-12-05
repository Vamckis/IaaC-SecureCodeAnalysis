# IaaC-SecureCodeAnalysis
- pip3 install checkov

## KICS
- brew install Checkmarx/tap/kics
- export KICS_QUERIES_PATH=/opt/homebrew/opt/kics/share/kics/assets/queries

### If QueryPath (-q) is not provided, tool will use default path ./assets/queries

echo 'export KICS_QUERIES_PATH=/usr/local/opt/kics/share/kics/assets/queries' >> ~/.zshrc
- kics scan -p <code path> -q <queries path if above command fails> --report-formats "all" -o ./Report
