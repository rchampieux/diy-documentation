# Relative Citation Ratio (RCR)

## What it is
The RCR is an article-level metric that indicates the scientific influence of an article relative to other NIH-funded articles published in the same year and same discipline (field-normalized).


## How it works
The RCR is calculated as the ratio of the citation rate (number of citations per year) of an article to the expected citation rate for an article published in the same year and same discipline. The discipline of an article is dynamically determined by its co-citation network, i.e. the set of articles that are cited by the same articles that cite the article of interest. The expected citation rate is determined by calculating the field citation rate -- the mean citation rate of the journals in the co-citation network -- and then transforming the field citation rate to the expected citation rate using the equation from doing a regression of the the article citation rates vs the field citation rates of all NIH-funded articles in a given year, leading to a [median RCR of 1.0 for NIH-funded publications](https://icite.od.nih.gov/stats).

The RCR was developed by the NIH Office of Portfolio Analysis, and the [methodology was published in PLoS Biology](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002541). The publicly available [iCite tool](https://icite.od.nih.gov/) can be used to find the RCR of articles that are indexed in PubMed.


## What to keep in mind
- *Disciplinary scope* - The RCR was developed by the NIH and is only available for articles that are indexed in PubMed,. As it is currently implemented, it is only for use with articles with a biomedical focus. This biomedical focus is reflected in the benchmark of 1.0 as the median RCR for NIH-funded publications. While the range of disciplines is limited, because of the field-normalization, the RCR can be used to compare the impact of articles across different biomedical disciplines.
- *Time scope* - Currently the iCite tool provides RCR values for articles published since 1980. Due to the delay in accumulating citations, articles from the previous year will be assigned a provisional RCR only if the article has 5 or more citations and articles from the year before that will all be assigned a provisional RCR. This is updated in October (start of the NIH fiscal year). For example in October 2020, articles from 2020 with 5 or more citations will be assigned a provisional RCR, articles from 2019 will all be assigned a provisional RCR, and the RCR for articles from 2018 will no longer have a provisional status.
- *Use and criticisms of the RCR* - The RCR is a relatively new metric, first [introduced in a preprint in 2015](https://www.biorxiv.org/content/10.1101/029629v1). Since that time it has had significant uptake; the RCR has been [used by NIH for strategic planning](https://www.nature.com/news/nih-metric-that-assesses-article-impact-stirs-debate-1.18734), integrated into Digital Science’s [ReadCube](https://www.readcube.com/home) and [Dimensions products](https://app.dimensions.ai/discover/publication), and been employed as a metric in dozens of published analyses. It has also been subject to a number of criticisms, with multiple criticisms of the property that, unlike raw citation counts, the RCR may decrease over time, either due to a [decrease in relative influence](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2002536) or even in some anomalous cases due to [an increase in citations](https://www.cwts.nl/blog?article=n-q2u294&title=nihs-new-citation-metric-a-step-forward-in-quantifying-scientific-impact). The authors have countered that the [former is a desirable characteristic](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.2003552), and the [latter is exceedingly rare](https://journals.plos.org/plosbiology/article?id=10.1371/journal.pbio.1002541).
- *Potential future development* - Researchers have [extended the use of the RCR methodology across different disciplines](https://www.sciencedirect.com/science/article/pii/S1751157718303559) using the Scopus database, but this is not yet an option for the metrics consumer.

## Learn more
- Hutchins, B. I., Yuan, X., Anderson, J. M., & Santangelo, G. M. (2016). Relative Citation Ratio (RCR): A New Metric That Uses Citation Rates to Measure Influence at the Article Level. *PLOS Biology*, 14(9), e1002541. https://doi.org/10.1371/journal.pbio.1002541


## Related metrics

Last updated April 2022
