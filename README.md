# SoK : Software Energy Monitoring Tools

## Literature Management

An excel sheet [literature management](/literature-management.xlsx) is used to organise and document the selection of literature considered for this study (e.g., identify seed papers for the snowballing methodology, track inclusion/exclusion, notes, etc.).

## Bibliography workflow (Zotero + BibTeX)

The project uses two BibTeX files in [bib folder](/draft/bib/):

- [main-zotero.bib](/draft/bib/main-zotero.bib) : Never edit this manually. I locally sync this file with our shared Zotero collection**"SoK : Software Energy Monitoring Tools"** from the Group Library **"JT Iness and Jason"**
- [temp-manual.bib](/draft/bib/temp-manual.bib) : Used for quickly adding references in the[main.tex](/draft/main.tex)

In [LaTeX](/draft/main.tex), both are loaded:

```
\bibliographystyle{IEEEtran}
\bibliography{bib/main-zotero.bib,bib/temp-manual.bib}
```

### How to add a reference?

1. (Skip this if in a hurry) Add the reference to the shared Zotero collection **"SoK : Software Energy Monitoring Tools"** from our Zotero Group **"JT Iness and Jason"**.
2. If you need to cite it right away, manually export your reference (BibTeX) into`temp-manual.bib`.
3. I'll periodically sync `main-zotero.bib` with our Zotero Collection, so it becomes permanent.
