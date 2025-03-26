# shiny_apps
shiny apps for data visualization

# Volcano Plot Shiny App

This Shiny app generates volcano plots from differential expression data.

## Usage

1.  Clone this repository to your local machine.
2.  Open R and set your working directory to the app's directory.
3.  If you use the renv package, run `renv::restore()`.
4.  Run the app using `shiny::runApp()`.
5.  Upload your CSV data file.
6.  Adjust the parameters and click "Generate Plot."

## Data Format

The input CSV file must have the following columns:

* `p_val`
* `logFC`
* `AveExpr`
* `p_val_adj`
* `gene_names`
* `Gene`
* `X_row`

## Dependencies

* shiny
* ggplot2
* ggrepel
* ggpubr
* dplyr
* renv (optional, but recommended)

## Example

[SampleVolcanoPLot.png](https://github.com/sciptHUB/shiny_apps/edit/main/README.md#:~:text=SampleVolcanoPLot-,SampleVolcanoPLot,-.png)

## License

None
