NADURL (Not a data url) is a simple website that takes a base64 encoded string after the "?" at the end of the url and writes that to the document. Due to Github pages limits, the url cannot have more than  8216 characters. This leaves a maximum of 8188 characters for base64 text, or 6141 bytes of data. This was specifically created for the Nintendo 3DS web browser so that I could share pages to it via a QR code. It does not accept data url when reading a QR code (As with most QR readers), so I had to do it this way instead.

This version is titled "a". If a different version is released, it will be put in a seperate repo.
