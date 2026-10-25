# Project 3 — Part A

`index.html` is the static report, linked from the portfolio homepage. All 24
provided PNGs are copied unchanged from `../proj3/` into `media/project3/`.
`media/project3/original.png` is the original photograph panel extracted from
`11_noise_samples.png`, for the separate reference in section 1.4. No model
results were generated or retouched when building the website.

## Results included

| Section | Included evidence |
| --- | --- |
| 1.1 | Original and all three noisy inputs |
| 1.2 | Three noisy/blur pairs, including the plotted sigma values |
| 1.3 | Three original/noisy/one-step triplets |
| 1.4 | Original reference and three update/error comparisons |
| 1.5 | Six trajectory states and four-way denoiser comparison |
| 1.6 | Five conditional samples, seeds 180–184 |
| 2.1 | Five CFG samples, seeds 180–184, and comparison commentary |
| 3.1 | Campanile, two personal photos, Pink Panther web image, lion and tortoise drawings; seven starting times each |
| 3.2 | The same three inputs, seven times each, with prompts transcribed from the plots |
| 3.3 | Two anagrams, each showing both orientations and prompt labels |
| 3.4 | Two hybrids, each shown large and small |

## Submission gaps in the supplied material

- The Part A notebook from Downloads is available as `parta.ipynb`. Runtime details such
  as tensor reuse, error-map scaling, and exact hybrid blur settings cannot be
  verified from the result images alone.
- Hybrid subject labels come from the filenames and visible images. Exact
  hybrid prompt strings were unavailable and have not been invented. The
  suggested blur settings are explicitly attributed to the assignment.

The page includes a print stylesheet for saving as PDF. Part A's PDF and notebook
are separate Gradescope submissions; neither is submitted by editing this repo.
The assignment defers the Google Form until both parts are complete.

## Part B results

`partb.html` presents the results copied from `../proj3/partb/`, including the
new class-conditioned experiments, and links the Part B notebook from Downloads in
`partb.ipynb`. Section 2.4 describes the implemented class-conditioned U-Net;
the assignment has no separate deliverable for 2.4. Sections 2.5–2.6 now
include the scheduled/constant-rate training comparison and generated samples
at epochs 1, 5, and 10, including the no-scheduler model.

Part B requires the code and website PDF on Gradescope, plus the website URL in
the project Google Form after both parts are complete. Downloadable Part A and
Part B PDFs are kept in this directory.

## Layout

The report preserves the existing 48rem column, paper background, typography,
header, and footer. Comparison figures scroll within their own containers on
small screens and link to the original PNGs. All content is available without
JavaScript. Print rules remove navigation and keep figures and captions together.
