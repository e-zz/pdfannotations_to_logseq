# pdfannotations_to_logseq
Import pdf into logseq but also import annotations made from other softwares

## Status
* work in progress. The highlights don't appear at the right location on logseq but the pdf coordinates are very confusing (help welcome). But at least you can see them in the annotation panel and clicking on them leads you to the right page. If you use an "ink" annotation, this script will automatically create a "rectangular area" highlight in logseq linked to an image that includes the whole ink.

## Usage
* `python -m pip install -r requirements.txt`
* `python __init__.py path_to_pdf --md_path path_to_md --edn_path path_to_edn`

## TODO
* fix: the location of the highlights in logseq is wrong (meaning they don't appear at the right location in logseq's pdf reader) Currently I rely on blind workarounds and the areas don't appear at the right location. It's still usable to quickly go to the right page though. [Link to a helpful discussion](https://github.com/e-zz/logseq-pdf-extract/discussions/3#discussioncomment-7888760)
* infer color via numpy instead of colormath (broken)


## credits
* [pdfannots](https://github.com/0xabu/pdfannots/)
