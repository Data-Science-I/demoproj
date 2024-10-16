#' Title
#'
#' @param df dataframe
#' @param varx x variable name in df
#' @param vary y variable name in df
#'
#' @return ggplot scatterplot of vary vs varx
#' @export
#'
#' @importFrom ggplot2 ggplot
#' @importFrom ggplot2 geom_point
#'
#' @examples
#' df <- data.frame(x = rnorm(10), y = rnorm(10))
#' diamond_plot(df, 'x', 'y')
diamond_plot <- function(df, varx, vary){
  ggplot(df, aes(x=get(varx), y=get(vary))) +
    geom_point(shape=23, fill="blue", color="darkred", size=3)
}
