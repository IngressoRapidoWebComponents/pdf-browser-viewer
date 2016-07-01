[![bower version](https://img.shields.io/bower/v/pdf-browser-viewer.svg)](https://libraries.io/bower/pdf-browser-viewer)
[![open issues](https://img.shields.io/github/issues/IngressoRapidoWebComponents%2Fpdf-browser-viewer.svg)](https://github.com/IngressoRapidoWebComponents/pdf-browser-viewer/issues)
[![license](https://img.shields.io/github/license/IngressoRapidoWebComponents%2Fpdf-browser-viewer.svg)](https://github.com/IngressoRapidoWebComponents/pdf-browser-viewer/blob/master/LICENSE)


# \<pdf-browser-viewer\>

PDF viewer using native browser object as application/pdf

_[Demo and API docs](https://ingressorapidowebcomponents.github.io/components/pdf-browser-viewer/)_

Example:
```html
    <pdf-browser-viewer id="pdfViewer" file="[[pdfUrl]]" width="100%"></pdf-browser-viewer>
```

Data Bind with Blob example:
```js
    this.pdfUrl = URL.createObjectURL(blob);
```

Clear PDF container example:
```js
    this.$.pdfViewer.clear();
```

Message example:
```html
    <pdf-browser-viewer
        file="[[pdfUrl]]"
        not-supported-message="Not supported by your browser"
        not-supported-link-message="see the file here!">
    </pdf-browser-viewer>
```

Card example:
```html
    <pdf-browser-viewer
        file="[[pdfUrl]]"
        card elevation="3"
        download-label="Baixar">
    </pdf-browser-viewer>
```