# Reproducible computation at scale in R

Data analysis can be slow. Some computations take several minutes, hours, or even days to finish. Afterwards, if you update your code or data, your hard-earned results may no longer be valid. How much of that valuable output can you keep, and how much runtime must you endure all over again? For workflows implemented in R, the [`drake`](https://github.com/ropensci/drake) package can help. It analyzes your project, skips steps with up-to-date results, and orchestrates the rest with optional distributed computing. At the end, drake provides evidence that your results match the underlying code and data, which increases your ability to trust your work.

# Venue

This talk is part of the [2019 ASA Symposium on Data Science and Statistics](https://ww2.amstat.org/meetings/sdss/2019/onlineprogram/AbstractDetails.cfm?AbstractID=306396)
