Programming Background
================

## Comparing R to other programming languages

*What are your thoughts on R vs. whatever other software you’ve used?
What functionality do you like about R? What parts do you miss about
your other language? Do you consider R a difficult language to learn?*

After my brief forays into Base SAS in ST555 and ST513, I find that the
syntax of R has been more lexically intuitive and easier to recall.
Importing, exploring, and modifying simple data in R has (so-far)
required a one-line function, whereas one must recall a paragraph of
syntax for the various SAS “DATA” and “PROC” steps. I may have
overlooked the equivalent of RStudio’s `help()` function in SAS, but I
distinctly remember perusing lengthy SAS documentation web pages for
details that are otherwise at my fingertips in RStudio.

Creating simple files with R Markdown and `knitr` has also been far
easier than with the SAS Output Delivery System (ODS). On the other
hand, SAS output was highly customizable. I recall modifying cell
widths, text size and alignment, background colors, and a variety of
plot properties in ST555, but I have stuck with defaults while working
with R. This may change when we explore `ggplot2`.

Our default development environments for SAS and R - SAS Studio and
RStudio, respectively - have been phenomenal on the Windows and Mac
operating systems, but the `tidyverse` package was surprisingly
difficult to install in RStudio on Ubuntu. Ultimately, I resorted to an
[online blog
post](https://blog.zenggyu.com/en/post/2018-01-29/installing-r-r-packages-e-g-tidyverse-and-rstudio-on-ubuntu-linux/)
to identify and install a slew of missing dependencies. Now that the
clud-based SAS OnDemand for Academics has completely replaced SAS
University Edition, getting started with SAS is, by comparison, a more
seamless process on Linux. The only drawback I have faced with SAS
OnDemand for Academics is its integration with a local installation of
Jupyter, which requires users to create [several configuration
files](https://support.sas.com/ondemand/saspy.html). The Anaconda
ecosystem, on the other hand, provides [out-of-the-box
support](https://docs.anaconda.com/anaconda/navigator/tutorials/r-lang/)
for the R kernel in Jupyter.

## Example R Markdown output

![](../images/pressure-1.png)<!-- -->
