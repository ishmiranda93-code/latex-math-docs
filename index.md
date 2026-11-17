# LaTeX Math for Confluence — Documentation

LaTeX Math is a Confluence Cloud macro by Seventh Visual. Write LaTeX in a
page and get properly typeset mathematics, rendered by KaTeX entirely in
your browser.

## Getting started
1. Edit a Confluence page and insert the **LaTeX Math** macro.
2. The editor opens with a starter example (an aligned equation block and a
   fraction). Replace it with your own LaTeX — the preview updates as you type.
3. Save. The LaTeX source is stored in the page itself, as the macro's
   content, and renders for every reader of the page.

## Writing equations
- Wrap each equation in `$$ … $$` or `\[ … \]`. Several equations can live in
  one macro, one after another.
- Aligned blocks (`\begin{aligned} … \end{aligned}`), fractions, roots,
  superscripts and subscripts are supported by the KaTeX renderer.
- Custom preambles and `\usepackage` are not supported.

## If an equation has a typo
Each equation renders on its own. An equation that can't be rendered shows a
short, plain-language note ("This equation couldn't be rendered. Check the
LaTeX — an unknown command or a missing brace is the usual cause.") and the
rest of the equations on the page still render. You will never see a raw
parser error.

## Good to know
- **Length:** a macro holds up to 32,000 characters of LaTeX.
- **Display equations:** the macro renders display-style mathematics in its
  own block on the page.

## Privacy
The app collects no data, stores nothing outside your Confluence page, and
requests no permissions. See the privacy policy for details.

## Support
Support is provided by Seventh Visual via the contact channels on the
Atlassian Marketplace listing.
