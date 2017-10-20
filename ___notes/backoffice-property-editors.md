# Umbraco back-office ideas
## Property Editors

* [ ] Searchable multiple-selection dropdown list - using [chosen](https://github.com/harvesthq/chosen) JavaScript library
* [ ] Screengrab / Image preview - using [html2canvas](https://github.com/niklasvh/html2canvas)
* [ ] Better Markdown editor - using [EpicEditor](https://github.com/OscarGodson/EpicEditor)
* [ ] Enhanced Content/Media picker - XPath filtering; Set start-node; breadcrumb to show path; (potential core or uComponents)
* [x] ~~MNTP improvements - Member picker, User Picker, FileSystem picker (CSS, JS), Examine/Lucene-powered~~
  * Done in [nuPickers](https://github.com/uComponents/nuPickers)
* [ ] [Literally Canvas](http://literallycanvas.com/) - HTML5 drawing widget. Save image as data-uri (base64) or file/media.
* [ ] (Nokia's) [HERE](http://here.com/) map integration - using [jHERE](http://jhere.net/), (similar API - [dev info](https://developer.here.com/)).
* [x] ~~On/Off [FlipSwitch](http://proto.io/freebies/onoff/) - a better version of [ToggleBox](http://ucomponents.codeplex.com/wikipage?title=ToggleBox), using pure CSS3.~~
  * Done in [Switcher](https://our.umbraco.org/projects/backoffice-extensions/switcher) (not using FlipSwitch, though)
* [ ] ISBN field + validator, (for both ISBN-10 and ISBN-13). (Potential to support other standards: EAN/JAN, UPC GTIN)
* [x] ~~OpenGraph - give a URL, use [OpenGraph-Net](https://github.com/ghorsey/OpenGraph-Net) library to pull in meta-data. Store as XML/JSON.~~
  * Done in [Open-Graph DataType](https://github.com/leekelleher/umbraco-opengraph)
* [ ] Bootswatch picker - using the [Bootswatch API](http://news.bootswatch.com/post/22193315172/bootswatch-api) to display a dropdown of current themes and a thumbnail preview.
* [ ] Published XML data-type - so that you can see the currently published state of the XML for that content node.
* [ ] Advanced DatePicker (single- or multi-mode; with or without time, per date). Localizeable, of course.
