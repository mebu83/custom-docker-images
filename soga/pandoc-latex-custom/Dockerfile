FROM pandoc/latex

RUN tlmgr install forest
RUN tlmgr install koma-script
RUN tlmgr install tcolorbox
RUN tlmgr install tikzfill
RUN tlmgr install pdfcol
RUN tlmgr install listingsutf8
RUN tlmgr install pgfplots
RUN tlmgr install datatool
RUN tlmgr install filecontents
RUN tlmgr install tikzmark
RUN tlmgr install glossaries
RUN tlmgr install awesomebox
RUN tlmgr install fontawesome5
RUN apk update
RUN apk add bash python3 py3-pip
RUN python3 -m pip install --upgrade pip install pandoc-latex-environment pandocfilters