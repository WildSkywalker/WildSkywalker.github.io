# Yi Gu's personal website

Static HTML adaptation of [Minimal Light](https://github.com/yaoyao-liu/minimal-light), served at https://wildskywalker.github.io/.

The CV maintained in Overleaf is the authoritative source for the downloadable PDF and the homepage's publications, employment, education, and service. Generated files are `index.html`, `Yi_Gu_CV.pdf`, and `cv-sync.json`; do not edit them independently. Experience leads publications, with selected LLM-related achievements copied from the CV under their original roles. The full CV contains all employment achievements and technical skills. The existing photo, personal note, research-interest sentence and profile links are website-specific content.

The local sync tooling lives alongside this checkout in `../site-tools/`. It pulls Overleaf, compiles the PDF with the existing LaTeX installation, validates and regenerates the page, then commits only the three generated files. It stops on local edits, conflicting Git history, compile failures, and unsupported CV structure. An app-managed recurring check runs on the owner's computer; it is not an Overleaf webhook or a GitHub-hosted credential integration.

Original theme CSS: `assets/css/minimal-light.css`, from upstream commit `1ea07f39518ac44644406380c83da6f89037c4fc`, with CC0 terms in `assets/licenses/minimal-light.txt`. Local responsive and typography changes are in `main.css`. No analytics or tracking scripts are included.
