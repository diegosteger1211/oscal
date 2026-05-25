# OSCAL ICS Example Bundle

Repository target:
https://github.com/diegosteger1211/oscal

Upload all six JSON files directly into the repository root, not into subfolders.

Raw URLs used inside the JSON files:

- Profile: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-profile.json
- Component Definition: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-component-definition.json
- SSP: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-ssp.json
- Assessment Plan: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-assessment-plan.json
- Assessment Results: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-assessment-results.json
- POA&M: https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-poam.json

Recommended import order in OSCAL Viewer:

1. ics-packaging-cell-profile.json
2. ics-packaging-cell-component-definition.json
3. ics-packaging-cell-ssp.json
4. ics-packaging-cell-assessment-plan.json
5. ics-packaging-cell-assessment-results.json
6. ics-packaging-cell-poam.json

Important:
The GitHub repository must be public, or the OSCAL Viewer cannot fetch the raw files.
After upload, test the raw URL in the browser first, for example:
https://raw.githubusercontent.com/diegosteger1211/oscal/main/ics-packaging-cell-ssp.json

If the URL returns JSON directly, the OSCAL Viewer can resolve the dependency.
