# UiPath Document Understanding

The UiPath Document Understanding framework facilitates the processing of incoming files, from file digitization to extracted data validation, all in an open, extensible, and versatile environment.

# Requirements
- Create asset with name **DuAPIKey**  and provide value as Document Understanding API Key.

# Files Supported
-   files that are images
    -   supported images formats are .png, .gif, .jpe, .jpg, .jpeg, .tiff, .tif, .bmp
    -   for multi-page TIFF files, OCR is applied for each page
-   PDF pages that
    -   do not expose any machine readable content
    -   contain images that cover a significant area of the page.