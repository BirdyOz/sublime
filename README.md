# Sublime-cleanHTML

## CleanHTML for Sublime Text

This ST3 plugin performs a range of HTML cleaning and code sanitisation functions.   It is particularly good at cleaning up messy code that is  generated by the Moodle ATTO editor.

**Tag Removal**

* Unnecessary tags (span, section, article etc.)
* Specific Empty tags (p, strong, em, li, h[1-6], b, ol, ul, etc.)
* Poorly nested tags (li>p, ul>ul, ol>ol, p>p, p>ul, p>div etc.)

**Attribute removal**

* font-sizes (style = "font-size....)
* YUI id's created by the ATTO editor (id = "yui......)

**Deep cleaning (optional)**

* All style attributes (style = "....)

**Table cleaning (optional)**

* All table tags (table, tbody, tr, th, thead, td, caption)

## Dependancies

This plugin invokes functions from other Sublime Text Packages:

<ul>
    <li><a href="https://packagecontrol.io/packages/Emmet" target="_blank">Emmet - Packages - Package Control</a></li>
    <li><a href="https://packagecontrol.io/packages/HTML-CSS-JS%20Prettify" target="_blank">HTML-CSS-JS Prettify - Packages - Package Control</a></li>
</ul>

Please ensure that you have these plugins installed, prior to running CleanHTML

## Usage

1. Launch Package Control
2. Type 'Clean HTML'
3. Choose cleaning mode (Normal/Deep/Table)

Keboard shortcuts (Mac)

* <kbd>CMD</kbd> + <kbd>Shift</kbd> + <kbd>\\</kbd> - Normal
* <kbd>CMD</kbd> + <kbd>Opt</kbd> + <kbd>\\</kbd> - Deep
* <kbd>CMD</kbd> + <kbd>Shift</kbd>  + <kbd>Opt</kbd> + <kbd>\\</kbd> - Normal



