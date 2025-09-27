# playwright-smoke-test
Simple Playwright smoke test using pytest to open Google and validate title.

## How to run
```bash
pip install -r requirementsPST.txt
pytest -q --html=report.html --self-contained-html


-> Opens Google in a browser.

-> Validates page title contains "Google".

-> Generates HTML report (report.html).
