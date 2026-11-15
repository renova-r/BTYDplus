# BTYDplus 1.2.0.9002

- vignettes/BTYDplus-HowTo.Rmd renders with rmarkdown::html_vignette instead of pdf_document; content unchanged.
- Removed the prebuilt inst/doc copies (BTYDplus-HowTo.pdf, .R, .Rmd) and the stale build/vignette.rds; R CMD build regenerates the vignette output, so each build ships exactly one.

# BTYDplus 1.2.0.9001

Renova release based on CRAN BTYDplus 1.2.0.

- man/abe.mcmc.DrawParameters.Rd and pggg/pnbd files link \link[coda]{mcmc.list}.
- man/pnbd.mcmc.DrawParameters.Rd replaces itemize with item entries.
- Release metadata: Renova version and attribution; README and license text; stale MD5 removed.
