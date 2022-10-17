# Roadmap

We ([textualize.io](https://www.textualize.io/)) are actively building and maintaining Textual. 

We have many new features in the pipeline. This page will keep track of that work.

## Features

High-level features we plan on implementing.

- [ ] Command interface
    * [ ] Command menu
    * [ ] Fuzzy search
- [ ] Configuration (.toml based extensible configuration format)
- [x] Devtools
    * [ ] Browser-inspired devtools interface with integrated DOM view, log, and REPL
- [ ] Reactive state
- [x] Themes 
    * [ ] Customize via config 
    * [ ] Builtin theme editor

## Widgets

Widgets are key to making user friendly interfaces. The builtin widgets should cover many common (and some uncommon) use-cases. The following is a list of the widgets we have built or are planning to build.

- [x] Buttons
    * [x] Error / warning variants
- [ ] Color picker
- [x] Checkbox
- [ ] Content switcher
- [x] DataTable
    * [x] Cell select
    * [ ] Row / Column select
    * [ ] API to update cells / rows 
    * [ ] Lazy loading API
- [ ] Date picker
- [ ] Drop-down menus
- [ ] Form Widget
    * [ ] Serialization / Deserialization
    * [ ] Export to `attrs` objects
    * [ ] Export to `PyDantic` objects
- [ ] Image support
  - [ ] Half block
  - [ ] Braile
  - [ ] Sixels, and other image extensions
- [x] Input
    * [ ] Validation
    * [ ] Error / warning states
    * [ ] Template types: IP address, physical units (weight, volume), currency, credit card etc
- [ ] Markdown viewer (more dynamic than Rich markdown, with scrollable code areas / collapseable sections)
- [ ] Plots
  - [ ] bar chart
  - [ ] line chart
  - [ ] Candlestick chars
- [ ] Progress bars
    * [ ] Style variants (solid, thin etc)
- [ ] Radio boxes
- [ ] Sparklines
- [ ] Tabs
- [ ] TextArea (multi-line input)
    * [ ] Basic controls
    * [ ] Syntax highlighting
    * [ ] Indentation guides
    * [ ] Smart features for various languages
