# Atom Builder 3D

A bilingual Bangla/English 3D atom explorer for NCTB Class 8 science learners. Build atoms visually, inspect particle structure, and test your understanding through an interactive quiz.

**Created and maintained by MD Raiyan Ibne Kamal** · [GitHub profile](https://github.com/raiyanibnekamal) · [Project repository](https://github.com/raiyanibnekamal/Atom-Builder-3D) · [Live site](https://raiyanibnekamal.github.io/Atom-Builder-3D/)

## Highlights

- Three.js-powered 3D atom visualization with animated nucleus, electron shells, lighting, and orbit motion.
- Builder mode with drag-and-drop placement of protons, neutrons, and electrons.
- 10 guided element targets: Hydrogen (H), Helium (He), Lithium (Li), Beryllium (Be), Boron (B), Carbon (C), Nitrogen (N), Oxygen (O), Fluorine (F), and Neon (Ne).
- 12-question quiz with instant feedback, explanations, score tracking, and restart support.
- Learn mode with atomic number, proton, neutron, electron, shell configuration, and mass number tables.
- English/Bangla language toggle with bilingual element facts and learning content.
- Mouse and touch rotation, scroll/pinch-style zoom behavior, sound effects, progress tracking, and responsive layout.
- No build step or package installation required. Three.js and web fonts are loaded from CDNs.

## Learning Model

The explorer uses the simplified neutral-atom model used throughout the learning experience:

- Atomic number (Z) = number of protons.
- A neutral atom has the same number of electrons as protons.
- Mass number (A) = protons + neutrons.
- Electrons are distributed across shells using the project shell capacities `[2, 8, 8, 18, 8]` for the supported targets.

The embedded dataset includes particle counts, shell configurations, element categories, bilingual names, and fun facts for each target element.

## Run Locally

Open `index.html` directly in a modern browser, or serve the folder with any static web server:

```text
python -m http.server 8000
```

Then visit `http://localhost:8000/`.

A WebGL-capable browser and an internet connection are recommended because the app loads Three.js and fonts from CDNs.

## GitHub Pages

The project is live here: **[Open Atom Builder 3D](https://raiyanibnekamal.github.io/Atom-Builder-3D/)**.

Source code: **[GitHub repository](https://github.com/raiyanibnekamal/Atom-Builder-3D)**. This is a static HTML project published from the `main` branch with GitHub Pages.

The repository is owned and published by [raiyanibnekamal](https://github.com/raiyanibnekamal). The source, learning content, interface, interaction logic, and Three.js visualization in this repository were created for this project by the author named above.

## Project Structure

```text
index.html        Main application: markup, styles, datasets, and JavaScript
README.md         Project documentation
```

## Credits

Created by **MD Raiyan Ibne Kamal**.

Built with HTML, CSS, JavaScript, and [Three.js](https://threejs.org/). Designed as an interactive companion for NCTB Class 8 science topics on atomic structure.
