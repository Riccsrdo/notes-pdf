Hi!

These are my personal notes taken during the last three semesters on my
master degree in Cybersecurity in Sapienza!

Note that these are notes taken during lessons. They might contain errors, 
specifically grammatical errors :D.
They won't be corrected.

Notes are inside different folders.
You can find them in the file named `main.pdf`.

*For me*:
Remember to install LatexWorkshop, HyperSnips (for snippets), Paste Image.
For Paste Image, copy this inside the `setting.json`:
```json
{
    "pasteImage.path": "${currentFileDir}/images",
    "pasteImage.basePath": "${currentFileDir}",
    "pasteImage.insertPattern": "\\begin{figure}[htbp]\n\t\\centering\n\t\\includegraphics[width=0.8\\textwidth]{images/${imageFileName}}\n\t\\caption{Caption}\n\t\\label{fig:${imageFileName}}\n\\end{figure}",
    "pasteImage.forceUnixStyleSeparator": true,
    "pasteImage.showInputs": true
}
```

Also, remember to remap the CTRL+ALT+V in VScode, or it won't work.
