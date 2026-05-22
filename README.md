# V2X-SenseComm Website

This repository hosts the project website for **V2X-SenseComm**, a multimodal V2X sensing and communication dataset for urban V2I integrated sensing and communication research.

The website introduces the dataset overview, urban scenarios, storage format, data generation tutorial, code repository, publication status, and dataset download information.

## Website Contents

- **Overview**: brief introduction to the V2X-SenseComm dataset and supported ISAC tasks.
- **Scenarios**: urban V2X scene catalog with training/test split information.
- **Dataset**: dataset modalities, directory structure, file contents, and loading examples.
- **Tutorials**: data generation workflow from OSM maps to synchronized sensing and communication samples.
- **Code**: project code repository link.
- **Publications**: placeholder for related papers.
- **Download**: placeholder for the future Hugging Face dataset release.

## Repository Structure

```text
website/
|-- README.md
`-- docs/
    |-- index.html
    |-- styles.css
    `-- assets/
        `-- figures/
```

## Local Preview

The website is a static HTML/CSS page and can be previewed directly in a browser. For a local server preview, run:

```bash
cd website/docs
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy with GitHub Pages

1. Push this repository to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Select **Deploy from a branch**.
5. Choose the `main` branch and the `/docs` folder.
6. Save the setting and wait for GitHub Pages to finish deployment.

## Update Guide

- Edit page content in `docs/index.html`.
- Edit visual styles in `docs/styles.css`.
- Put scenario, dataset, and tutorial figures under `docs/assets/figures/`.
- Update the Code, Publications, and Download sections after the repository, papers, and Hugging Face dataset are released.

## License

Website content and assets will follow the license selected for the V2X-SenseComm project.
