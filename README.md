
<!-- README.md is generated from README.Rmd. Please edit that file -->

<p align="center">

<img src="man/figures/gt_logo_1x.png" height="500px">

</p>

<p align="center">

[![lifecycle](https://img.shields.io/badge/lifecycle-maturing-blue.svg)](https://www.tidyverse.org/lifecycle/#maturing)
[![CRAN
status](https://www.r-pkg.org/badges/version/gt)](https://cran.r-project.org/package=gt)
[![Travis build
status](https://travis-ci.com/rstudio/gt.svg?token=P7T9dzi5RLEq9j2Yepx5&branch=master)](https://travis-ci.com/rstudio/gt)
[![Coverage
status](https://codecov.io/gh/rstudio/gt/branch/master/graph/badge.svg)](https://codecov.io/github/rstudio/gt?branch=master)

</p>

With the **gt** package, anyone can make wonderful-looking tables using
the **R** programming language.

-----

-----

<img src="man/figures/gt_tables.png">

-----

-----

The **gt** philosophy: we can construct a wide variety of useful tables
with a cohesive set of table parts. These include the table heading, the
boxhead, the stub, summary rows, and footnotes.

-----

-----

<img src="man/figures/gt_parts_of_a_table.png">

-----

-----

You decide which table parts you need for the task at hand with a API
that is both straightforward yet powerful.

**Create/Modify Table Components**

  - `gt()` – create a **gt** table object
  - `gt_preview()` – preview a **gt** table object
  - `tab_heading()` – add a table heading
  - `tab_stubhead_caption()` – add caption text to the stubhead
  - `tab_stub_block()` – arrange a table stub into blocks
  - `tab_boxhead_panel()` – arrange a boxhead into panels
  - `tab_footnote()` – add one or more footnotes
  - `tab_source_note()` – add a source note citation
  - `tab_style()` – add custom styles to one or more cells
  - `tab_options()` – modify the table output options

**Format Data**

  - `fmt()` – set a column format with a formatter function
  - `fmt_number()` – format numeric values
  - `fmt_scientific()` – format values to scientific notation
  - `fmt_percent()` – format values as a percentage
  - `fmt_currency()` – format values as currencies
  - `fmt_date()` – format values as dates
  - `fmt_time()` – format values as times
  - `fmt_datetime()` – format values as date-times
  - `fmt_missing()` – format missing values
  - `fmt_passthrough()` – format by simply passing data through
  - `text_transform()` – perform targeted text transformation with a
    function

**Modify Columns**

  - `cols_align()` – set the alignment of columns
  - `cols_move()` – move one or more columns
  - `cols_move_to_start()` – move one or more columns to the start
  - `cols_move_to_end()` – move one or more columns to the end
  - `cols_hide()` – hide one or more columns
  - `cols_label()` – relabel one or more columns
  - `cols_split_delim()` – create group names and column labels via
    delimited column names
  - `cols_merge()` – merge two columns to a single column with a
    formatter
  - `cols_merge_uncert()` – merge two columns to a value + uncertainty
    column
  - `cols_merge_range()` – merge two columns to a value range column

**Modify Rows**

  - `blocks_arrange()` – modify the ordering of the stub block groups

**Add Rows**

  - `summary_rows()` – add summary rows using aggregation functions

**Export Table**

  - `write_rtf()` – save a **gt** table object as an RTF file
  - `as_raw_html()` – get the HTML content of a **gt** table
  - `extract_summary()` – extract a summary table from a **gt** table
    object

**Shiny**

  - `render_gt()` – a **gt** display table render function for use in
    Shiny
  - `gt_output()` – create a **gt** display table output element for
    Shiny

## Code of Conduct

Please note that this project is released with a [Contributor Code of
Conduct](CODE_OF_CONDUCT.md). By participating in this project you agree
to abide by its terms.

## License

MIT © RStudio, Inc.
