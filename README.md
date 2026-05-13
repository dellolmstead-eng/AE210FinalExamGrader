# AE210 Final Exam Web Grader (v3.1.1)

Browser grader for the AE210 Final Exam Jet11 workbook. Runs locally in the browser using the same checks as `Final_Exam_autograde_Olmstead_Fall_2025_v01.m`.

## Usage

1. Open `docs/index.html` (or serve the `docs/` folder).
2. Drop a completed Final Exam Jet11 workbook using `Jet11_AE210 FINAL EXAM_Lastname_Firstname.xlsm` from this repo.
3. Review the score summary, deductions, and bonus flags; results stay client-side.

## Parity testing

Use `docs/test_runner.html` with matching expected outputs to compare against MATLAB logs.

## Notes

- The Final Exam template workbook and sample files are tracked directly in this repo.
- The `docs/` folder here is a local copy (no longer shared), so edits apply only to the Final Exam web grader.
- Sample files for this grader live in `samples/` within this folder.
- Archival prep: this repo is self-contained; keep `docs/` and `samples/` with the repo when moving or zip'ing it.
