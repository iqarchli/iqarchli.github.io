# UX Design Portfolio

This portfolio showcases a selection of projects I've worked on as a UX Designer, focusing on concept development, prototyping, testing, and iteration.
Each project is written up as a case study on its own page, from the problem and the users to the design and what I learned from testing it.

Live site: [iqarchli.github.io](https://iqarchli.github.io)

---

## About
I design user experiences that balance functionality and clarity, with a focus on how complex tools can feel intuitive and efficient.
My background in computer science helps me collaborate closely with developers and product managers to bring ideas to life.

---

## Projects

### 1. [Comments in a 3D Renderer App for iOS](https://iqarchli.github.io/annotation-panel)
An annotation panel that lets users review 3D scenes on site and leave comments directly in the scene.
Comments are pinned to the view they refer to, synced through the cloud, and keep working when the connection drops.

### 2. [Collaborating on 3D projects in the Cloud](https://iqarchli.github.io/cloud-collaboration)
A web platform for sharing 3D scenes with teams and clients as presentations.
Collaborators can review the scenes and leave feedback in the browser, which speeds up reviews.

### 3. [VR User Interface Redesign](https://iqarchli.github.io/vr-redesign)
A visual redesign of a VR interface for architectural visualization, aligned with the new design system.
Existing workflows stayed the same, while panels, components, font sizes and layouts were updated and given a labelled tab bar.

### 4. [Highlighting Key Materials in 3D Renderings](https://iqarchli.github.io/highlight-materials)
A feature that lets users exclude materials and objects from White Mode, so they can highlight the parts of a scene that matter.
I tested the design with architects and changed the UI based on the findings.

---

## Design Process
Each project follows a structured UX process:
1. **Research & Problem Framing** – Understanding user needs and pain points
2. **Concept Exploration** – Ideating and sketching possible directions
3. **Prototyping** – Building interactive mockups for early testing
4. **User Testing & Feedback** – Validating assumptions and improving usability
5. **Iteration & Delivery** – Refining the final experience for production or MVP handoff

---

## Running the site locally
The site is built with [Astro](https://astro.build) and Tailwind CSS.

```sh
npm install
npm run dev      # local dev server
npm run build    # production build in dist/
```

Pushing to `main` deploys the site to GitHub Pages through the workflow in `.github/workflows/deploy.yml`.
Site content (projects, experience, CV link) lives in `src/config.ts`, and each case study is a page in `src/pages/`.
