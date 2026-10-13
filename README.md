# gemini-cli-wif-lab

W2-MCPCONF-OWNPROJECT-WIF lab (own infra only). Purpose: measure whether attacker-authored
gemini-cli workspace configuration (`.gemini/settings.json`), executed at CLI startup in a
WIF-configured GitHub Actions workflow, can reach and use the workflow's federated GCP
credentials against the engagement's OWN project (`riftweldproject`). Benign payload only
(markers + credential-use proof + inline teardown). Temporary lab; torn down by the owner
after capture.
