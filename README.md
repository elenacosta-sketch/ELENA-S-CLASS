# Ms Elena’s Class

An English classroom website with a pastel pink and purple design, levels A1–C2, skills practice, games and teaching resources.

## Included

- Six CEFR learning sections and six communicative skills.
- 36 grammar lessons with 108 questions, explanations and examples.
- Linked Genially websites and classroom games.
- Vocabulary PDFs for 1º–4º ESO.
- A2 / 2º ESO and B2 / 4º ESO mediation tasks, learning sequences and teacher notes.
- Bachillerato writing worksheets for Units 5, 6 and 7.

A1 and B1 mediation archives are not included because their original uploads exceeded the transfer limit. Grammar Factory 1 has been removed.

## View locally

This is a static website with no build step. From this directory, run:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## GitHub Pages

Use Settings → Pages → Deploy from a branch → main → / (root). The .nojekyll file is included. Website links and document paths are relative, so the site supports a repository subpath.

## Edit the website

- index.html: page layout, worksheet titles and external resource links.
- style.css: colours and responsive styling.
- app.js: starter skills activities and level colours.
- grammar-data.js: grammar rules, examples, questions and answer explanations.
- grammar-practice.js: grammar lesson interface.
- mediation-data.js and vocabulary-data.js: classroom resource catalogues.
- resources/: original uploaded teaching documents.

Favourites, practice progress and draft notes are saved in each visitor’s browser. Listening starters use browser speech synthesis. Internet access is needed for external resources and web fonts.


## Upload using the GitHub website

1. Extract the ZIP on your computer.
2. Create a repository called ms-elenas-class in your GitHub account.
3. Choose Add file → Upload files, and upload the extracted files and folders. The index.html file must be at the repository root. Upload in batches if GitHub limits the number of files per upload.
4. Open Settings → Pages and select Deploy from a branch → main → / (root), then Save.
5. GitHub displays the published website URL after deployment.

A ZIP uploaded as a single file does not become a GitHub Pages website: extract it first. Public GitHub Pages publishing makes all included resource files accessible to visitors.
