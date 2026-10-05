# loqr

Download or open [`index.html`](index.html) in a browser to create a QR code for text, a URL, or a Wi-Fi network. The page is self-contained and works locally without dependencies or sending data elsewhere.

Wi-Fi passwords are used only while generating the QR code and cleared from the form afterward. Choose whether to include the network name, password, or both as visible text on the Wi-Fi QR picture; selected details are included in the downloaded SVG. The page's Content Security Policy blocks external resources and network connections.

The QR encoder supports error-correction level L, versions 1–10. The maximum payload is 271 UTF-8 bytes; for Wi-Fi, this limit includes the format prefix and escaped network details, so the available space for the SSID and password is smaller.
