# How-to-Embed-PDF-Document-in-HTML-Web-Page
How to Embed PDF Document in HTML Web Page

## embed PDF document on the web page
```
<embed src="files/Brochure.pdf" type="application/pdf" width="100%" height="600px" />
```

## Disable and Hide Toolbar in PDF Web Viewer
```
<embed src="files/Brochure.pdf#toolbar=0&navpanes=0&scrollbar=0" type="application/pdf" width="100%" height="600px" />
```

## Specifying Parameters in URL

* http://example.com/doc.pdf#Chapter5
* http://example.com/doc.pdf#page=5
* http://example.com/doc.pdf#page=3&zoom=200,250,100
* http://example.com/doc.pdf#zoom=100
* http://example.com/doc.pdf#page=72&view=fitH,100

## PDF Document View Configuration

* page=pagenum – Specifies a number (integer) of the page in the document. The document’s first page has a pagenum value of 1.
* zoom=scale – Sets the zoom and scroll factors, using float or integer values. For example, a scale value of 100 indicates a zoom value of 100%.
* view=Fit – Set the view of the displayed page.
* scrollbar=1|0 – Turns scrollbars on or off.
* toolbar=1|0 – Turns the toolbar on or off.
* statusbar=1|0 – Turns the status bar on or off.
* navpanes=1|0 – Turns the navigation panes and tabs on or off.
