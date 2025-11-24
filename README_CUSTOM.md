# My Custom PDF Translation Platform

Based on [PDFMathTranslate](https://github.com/Byaidu/PDFMathTranslate).

## Setup

1.  Initialize the environment:
    ```bash
    ./setup.sh
    ```

2.  Start the platform:
    ```bash
    ./start.sh
    ```

## Customization

-   Modify `pdf2zh/gui.py` to change the UI title and theme.
-   Configuration is stored in `~/.config/PDFMathTranslate/config.json`.
    -   You can use `config_example.json` as a starting point.
    -   Copy it: `mkdir -p ~/.config/PDFMathTranslate && cp config_example.json ~/.config/PDFMathTranslate/config.json`

