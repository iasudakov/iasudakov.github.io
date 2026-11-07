# Ilia Sudakov — academic website

A self-contained HTML/CSS website. Open `index.html` locally, or upload all files to the root of a GitHub Pages repository. No build step or external fonts are required.

This is the current preferred academic design: system typography, blue links, subtle section rules, inline contact links, and captioned research figures.

## Content

- About presents the biography and research interests; the publications below provide the project details.
- Publications retain their author lists, statuses, resource links, and expandable personal contributions.
- Paper summaries are always visible; My contribution opens with native HTML disclosure controls, including without JavaScript.
- Earlier workshop acceptances appear as status notes; resource links point to the current paper, code, or project page.
- The CV links point to the existing Google Drive document.
- Contact links use small monochrome inline SVG icons alongside their text labels. No icon fonts, scripts, or external downloads are needed.
- The layout adapts to desktop and mobile widths, with native HTML disclosure controls.

## Research figures

The illustrations use consistent 4:3 preview areas and preserve the original proportions without cropping. They are 190 px wide on desktop, 150 px on tablets, and up to 230 px below the paper text on mobile. The files are unmodified figures from the associated research materials:

- `assets/ar-classifier.png`: method diagram from https://arxiv.org/html/2603.19122v2/randar_main_scheme_eccv.png (Sudakov, Babenko, and Baranchuk).
- `assets/mmd.png`: method diagram from https://github.com/yandex-research/dlm-mmd/blob/main/assets/mmd.png (Drobyshevskiy, Sudakov, et al.; repository Apache-2.0 license).
- `assets/registers-without.png` and `assets/registers-with.png`: PCA visualizations from https://quickjkee.github.io/registers-project-page/ (Starodubcev, Sudakov, et al.; project page CC BY-SA 4.0). These are shown side by side in HTML, without changing the images. Source paths: `static/images/pca/cat_noreg_b07_t01.png` and `static/images/pca/cat_reg_b07_t01.png`.
- `assets/spectral-reconstruction.png`: Figure 3(b), page 6, from the author-supplied manuscript *A Spectral Perspective on Continuous Diffusion Language Models*. The panel was extracted from the PDF at 400 dpi with its token labels, position indices, legend, and highlighting intact. It illustrates positional errors and repeated tokens in reconstructions from low- and high-frequency Qwen3.5 0.8B representations.

The paper entries identify their authors and link to public publications or project pages where available. Existing PNG figures retain their original pixel content; the spectral panel is a faithful rendering of the manuscript figure. Licensing links for the sources above: https://www.apache.org/licenses/LICENSE-2.0 and https://creativecommons.org/licenses/by-sa/4.0/.

Canonical and Open Graph URLs target https://iasudakov.github.io/.
