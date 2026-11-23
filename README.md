# Logan Slacktish — Engineering Portfolio

General Engineering Endevours in progress and currently completed.

## Projects currently featured

- **Orbital mechanics simulation:** MATLAB trajectory propagation using two-body dynamics and Earth's J₂ perturbation model.
- **Automated golf ball sorter:** completed Arduino project using TCRT5000 IR sensing, a TCS3200 color sensor, MG996R servos, and a three-basket output arrangement. Includes CAD and build descriptions.
- **Hybrid rocket motor test stand (Nittany Rocket Labs):** modular, load-cell-equipped stand designed around a motor clamp envelope up to 8 in. diameter and motors producing up to 2.5 kN thrust. The redesigned structure was evaluated in FEA under a 5 kN applied load after the initial model identified a critical failure location.
- **Thin-walled structural analysis:** mechanics-of-materials study of shear flow and structural response.
- **Mechanical design work:** overview of CAD and design workflow.

## Preview locally

Open `index.html` in a browser, or run a local static server from this directory:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then Save.
4. The project site URL is:
   https://logoslack-1.github.io/ProjectPortfolio/

## Project-content accuracy

The hybrid rocket test stand page describes pre-fabrication FEA and redesign. It does not claim physical hot-fire testing. The 5 kN value is the applied load in the redesigned FEA model, compared with the motor's stated 2.5 kN maximum thrust. This comparison is not presented as a certified factor of safety or physical proof-load result. Material properties, mesh settings, and detailed boundary conditions are not listed because they were not supplied.

The golf-ball sorter bill of materials follows the quantities listed in the supplied engineering portfolio. Add a final wiring diagram, source code, and measured sorting test data as those become available.
