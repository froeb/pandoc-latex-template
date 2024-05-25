# Eisvogel Pandoc LaTeX Template (Forked and Enhanced)

This is a forked and enhanced version of the Eisvogel LaTeX template for Pandoc. It builds upon the original template's strengths while adding new features, improved error handling, and better support for internationalization and Beamer presentations.

## Key Features

   **Enhanced Font Handling:**
    *   Improved support for non-Western European alphabets (e.g., CJK, Devanagari, Arabic).
    *   Better compatibility with PDFTeX, offering high-quality font options even for this engine.
    *   Intelligent font fallbacks to ensure your document always looks its best.
*   **Comprehensive Error Handling:**
    *   Checks for missing packages, fonts, and image files.
    *   Provides informative error messages to help you troubleshoot issues.
*   **Expanded Beamer Support:**
    *   Well-organized Beamer-specific configurations.
    *   More customization options for themes, colors, and layouts.
    *   Improved handling of slide breaks, table of contents, and captions.
*   **Code Refactoring for Clarity and Maintainability:**
    *   The template's source code has been significantly refactored to improve readability, making it easier to understand, maintain, and extend.
*   **Additional Features:**
    *   Zero-width non-joiner support for languages like Persian and Hindi.
    *   Customizable blockquote styling.
    *   Flexible caption positioning and styling.
    *   Support for SVG images.
    *   And more!

## Installation and Usage

1.  **Download:** Clone or download this repository.
2.  **Pandoc Command:** Use the following Pandoc command to apply the template:

```bash
pandoc -s your_document.md --template eisvogel.tex -o your_document.pdf
```

**Use code with caution.**

Customization: Explore the various options in the template to tailor it to your needs. Refer to the comments in the eisvogel.tex file for detailed explanations of each option.

## Compatibility
This template is designed to be fully compatible with Pandoc and works seamlessly with both PDFTeX and XeLaTeX/LuaLaTeX engines. It should work with most Pandoc documents created for the original Eisvogel template.

## Disclaimer

This forked Eisvogel LaTeX template is currently under development and may contain bugs or issues that could affect its functionality. While we have made every effort to ensure compatibility with the original template and have added several improvements, we cannot guarantee that it will work perfectly in all scenarios.

Users are encouraged to test this template thoroughly and report any problems they encounter. We are actively seeking collaborators who can help identify and fix these issues to make the template more robust and reliable.

A better tested version, still with various improvements over the original version, can be found in the previous branch.

## Cooperation Clause

We are actively seeking collaborators who are experienced with LaTeX, Pandoc, and template development. If you are interested in contributing to this project, please contact us. We are particularly interested in individuals who can:

Help identify and fix any remaining bugs or inconsistencies in the template.
Assist in testing the template with a wider range of Pandoc documents.
Provide feedback on the template's usability and suggest further improvements.
Contribute to the development of new features and enhancements.
By working together, we can create a powerful and versatile LaTeX template that serves the needs of the Pandoc community.

## Acknowledgments
This template is based on the excellent work of Pascal Wagler and John MacFarlane, the creators of the [original Eisvogel template](https://github.com/Wandmalfarbe/pandoc-latex-template).

