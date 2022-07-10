## 3.2.0 (2022-07-10)
- fix formatter bug (thanks @maikebing)

## 3.1.9 (2021-08-16)
- fix bug: #32 Misplaced format If there are UTF-8 characters in the data (thanks @haptear)

## 3.1.8 (2021-08-07)
- fix bug: #30 Misplaced format If there are UTF-8 characters in the data (thanks @haptear)

## 3.1.7 (2021-04-20)
- allow developer support their datasource

## 3.1.6 (2021-04-20)
- fix bug #25 List crashed when using with string type

## 3.1.5 (2021-02-28)
- introduce WithHeaderTextAlignment, allow user custom header alignment, if it's not defined, it will get text alignment setting, default is left
- fix bug: double header formatter

## 3.1.4 (2021-02-22)
- support text alignment center
- change order of items in enum TableAligntment
- remove titleAlignment (use TextAlignment instead)
- restructure project

## 3.1.3 (2021-02-21)
- meta rows should be invoked when table is building
- table title alignment (left/right/center)

## 3.1.2 (2021-02-12)
- fix title coloring issue when using table alignment center/right

## 3.1.1 (2021-02-12)
- fix bug table alignment

## 3.1.0 (2021-02-12)
- add test project
- allow custom BorderLeft, BorderRight, BorderTop, BorderBottom
- re-implement custom format builder
- color table title (text color & background color)
- replace old formats (markdown, alternative ...) by CustomFormat builder
- Trim table line/border/divider if all chars are space
- allow custom padding left, padding right of cell content
- rename some variables
- fix bug: allow using title on old formats
- add new method .WithFormatter, allow user re-format content/header value

## 3.0.0 (2021-01-31)
- support Table alignment (left, center and right)
- implement table ChartMap to support box-drawing characters and header ChartMap
- does not throw exception when data null/empty
- support DescriptionAttribute for List<class obj> (custom column header text)
- re-implement MetaRow, support multi row
- remove AppConstants, replace with builder.ColumnLength & builder.RowLength
- remove ConsoleTableBuilderOption
- support TextAligment (Left and Right)
- support Column MinLength
- support table title
- add TrimColumn extension (replace for Option.TrimColumn)
- remove MetaRowPositions.None
- fix typo


## 2.0.3 (2020-08-14)
Feature
  - Support .net framework 3.5
