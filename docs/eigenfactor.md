
# Eigenfactor Score & Article Influence Score

## What it is
The Eigenfactor score (or Eigenfactor) is a measure of a journal’s influence in a network of all journals, whereby [a journal is considered influential if it is cited frequently by other influential journals](https://crln.acrl.org/index.php/crlnews/article/view/7804/7804). Thus, the Eigenfactor is analogous to the [Eigenvector centrality (or prestige score)](http://en.wikipedia.org/wiki/Eigenvector_centrality) from graph theory, which is also the basis of Google’s PageRank algorithm. Technically, the Eigenfactor of a journal is [defined as the percentage of the total weighted citations the journal receives from all other journals in the network](http://www.eigenfactor.org/methods.pdf). The [Article Influence Score](https://crl.acrl.org/index.php/crl/article/view/16080/17526) is the Eigenfactor Score divided by the number of articles published by the journal in the past five years.

## How it works
*Conceptual calculation* <br>
 
Conceptually, the Eigenfactor is calculated iteratively via an infinite random walk through the scientific literature. Imagine a researcher who selects at random a journal article published in year Y. After reading the article, the researcher selects at random a journal from the article’s list of references, and proceeds to read a paper from the cited journal published in year Y. The researcher proceeds to read a random paper from the next list of cited journals, and the process continues ad infinitum. The [frequency with which the model researcher visits each journal gives a measure of that journal’s importance within the network of journals—and this frequency, expressed as a percentage](https://www.jneurosci.org/content/28/45/11433), is essentially the Eigenfactor of the journal. Because of the structure of the citation network of journals, the researcher will more frequently visit large and influential (well-cited) journals. The Eigenfactor score is thus a [measure of a journal's total use by the scientific community](http://www.eigenfactor.org/about.php).

*Practical Use* <br>

 - Where to find: The Eigenfactor and Article Influence Scores are available annually for all journals in Clarivate Analytics’ Journal Citation Reports (JCR) database. 
 - How to use: The Eigenfactor can be used to compare the citation influence of journals in different fields but of similar size. To compare journals of different sizes as well, one should better use the Article Influence score.
 - Time windows: The calculation uses a 5-year citation window and a 1-year publication window. Journal self-citations are excluded. 
 - The Eigenfactor Score and Article Influence Score can be applied to many contexts (i.e. groups of papers linked by citations), and at the level of an author, department, institution, or country. Their chief use, however, lies in comparing journals. 


## What to keep in mind

 - Eigenfactor is size-dependent. Journals that publish a high volume of papers (and thus have more opportunities to be cited) are more likely to have a higher Eigenfactor, all else being the same. If a journal doubles in size while the quality of its articles remains constant, we would expect its Eigenfactor score to double. Because the Eigenfactor score is size-dependent, it should not be used to directly compare two journals of very different size. 
 - Article Influence score is size-normalized: Comparison of different-sized journals is best done via the Article Influence Score, which is a size-normalized Eigenfactor.
 - Independent of field: The Eigenfactor and Article Influence Scores correct for differences in citation practices across different research fields, which means we can compare Eigenfactors (or Article Influence scores) of journals across fields. 
 - The Eigenfactor algorithm was created by Carl Bergstrom and Jevin West at the University of Washington. Their methods are described in a detailed methods white paper and the code is publicly available. The metric can be difficult to understand and reproduce without technical expertise. 


## Learn more

Sugimoto, C. R. & Lariviere, V. (2020). *Measuring Research: What Everyone Needs to Know*. Oxford University Press. https://dx.doi.org/10.1093/wentk/9780190640118.001.0001


## Related Metrics
[Journal Impact Factor]()
[Field Normalized Citation Indicators]()
[Relative Citation Ratio]()
