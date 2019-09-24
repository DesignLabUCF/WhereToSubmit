## Publication Outlets

This resource is designed to answer the following questions: 
1. "***Where do I publish my work?***". 
2. "***How do you judge the quality of a journal/conference?***"
3. "***Is this journal legit?***".

There are many (correct) answers, but these are common questions in trans-displinary research. Nothing replaces recommendations of your top peers and your advisors - ask for advice.

#### Where to Publish?

* Look at most relevant papers - where are they published?
* You should seek out the advice of your peers and colleagues.
* You should look where they are publishing on [Google Scholar](https://scholar.google.com/).
* Look at the editorial board and advisory boards - make sure the top people in the field are on it.

#### Order of Significance
  1. journals  
  2. conferences (with dual submission)  
  3. conferences  
  4. symposiums

#### Journal Rankings

Journal rankings and metrics externally evualate an academic journal's impact and quality. These Journal rankings and metrics are intended to reflect the place of a journal within its field, the relative difficulty of being published in that journal, and the prestige associated with it. They also differ from displine to disipline due to observed bibliometric measures and behavior in each displine. 

You can look up journal rankings (as well as find highly rated journals per topic) from [UCF Library's JCR InCities database](https://guides.ucf.edu/database/JCR) [(about)](https://clarivate.libguides.com/ld.php?content_id=42730408).

We have attempted to organize a few fields rankings and metrics (*bias alert* - mostly ones I submit or read).

* [**Energy**](Energy.md)
* [**Computer Graphics**](ComputerGraphics.md)
* [**Optics**](Optics.md)
* [**Smart Cities**](SmartCities.md)
* [**Simulation**](Simulation.md)
* [**Cultural Heritage**](CulturalHeritage.md)
* [**Computational Physics**](ComputationalPhysics.md)
* [**Cognitive Science**](CogSci.md)

#### Be Wary of Predatory Journals!
Because they have become so common, there are various [listings of predatory journals](https://beallslist.weebly.com) out there. If you don't find your journal [listed officially](https://www.researchgate.net/publication/320410854_Scopus_indexed_journals_updated_list_2018) with [SCOPUS](https://www.elsevier.com/solutions/scopus), it is likely predatory.

#### Ranking Information

- [**Impact Factor (IF)**](https://en.wikipedia.org/wiki/Impact_factor): The impact factor (IF) of an academic journal is a measure reflecting the average number of citations to recent articles published in the journal. It is frequently used as a proxy for the relative importance of a journal within its field, with journals with higher impact factors deemed to be more important than those with lower ones. 

- [**H index**](https://en.wikipedia.org/wiki/H-index): The h-index is an index that attempts to measure both the productivity and citation impact of the published body of work of a scientist or scholar. The index is based on the set of the scientist's most cited papers and the number of citations that they have received in other publications.

- [**Altmetric**](https://www.altmetric.com): Altmetrics are [**metrics and qualitative data**](https://www.altmetric.com/about-altmetrics/what-are-altmetrics/) that are complementary to traditional, citation-based metrics. A single research output may live online in multiple websites and can be talked about across dozens of different platforms. They can include (but are not limited to) peer reviews on Faculty of 1000, citations on Wikipedia and in public policy documents, discussions on research blogs, mainstream media coverage, bookmarks on reference managers like Mendeley, and mentions on social networks such as Twitter. (WARNING: Becareful not to make this an end goal.)

- [**Eigenfactor Score**](eigenfactor.org): a rating of the total importance of a scientific journal. Journals are rated according to the number of incoming citations, with citations from highly ranked journals weighted to make a larger contribution to the eigenfactor than those from poorly ranked journals. Eigenfactor scores and Article Influence scores are calculated by [**eigenfactor.org**](eigenfactor.org). 

- **5 year - Impact Factor (IF):** The impact factor (IF) of an academic journal is a measure reflecting the average number of citations to recent articles published in the journal. It is frequently used as a proxy for the relative importance of a journal within its field, with journals with higher impact factors deemed to be more important than those with lower ones based over 5 years. 

- [**Source Normalized Impact per Paper (SNIP)**](https://arxiv.org/abs/1005.4906): Source Normalized Impact per Paper (SNIP) measures contextual citation impact by weighting citations based on the total number of citations in a subject field. The impact of a single citation is given higher value in subject areas where citations are less likely, and vice versa. t is defined as the ratio of a journal's citation count per paper and the citation potential in its subject field. It aims to allow direct comparison of sources in different subject fields. Citation potential is shown to vary not only between journal subject categories – groupings of journals sharing a research field – or disciplines (e.g., journals in Mathematics, Engineering and Social Sciences tend to have lower values than titles in Life Sciences), but also between journals within the same subject category. 
  
- [**SCImago Journal Rank (SJR)**](http://lib.guides.umd.edu/bibliometrics/SJR): SCImago Journal Rank (SJR indicator) is a measure of scientific influence of scholarly journals that accounts for both the number of citations received by a journal and the importance or prestige of the journals where such citations come from. The SJR indicator is a variant of the eigenvector centrality measure used in network theory. Such measures establish the importance of a node in a network based on the principle that connections to high-scoring nodes contribute  more to the score of the node. The SJR indicator, which is inspired by the PageRank algorithm, has been developed to be used in extremely large and heterogeneous journal citation networks. It is a size-independent indicator and its values order journals by their "average prestige per article" and can be used for journal comparisons in science evaluation processes.


## Helpful Notes

[**Overleaf**](https://www.overleaf.com) is fantastic for live preview LaTeX editing. Overleaf also has an [online gallery of templates](https://www.overleaf.com/gallery), to which many official organizations upload their LaTeX templates ([SPIE](https://www.overleaf.com/latex/templates/tagged/spie), [OSA](https://www.overleaf.com/latex/templates/tagged/osa-official), [Elsevier](https://www.overleaf.com/latex/templates/elseviers-complex-article-service-cas-latex-double-column-template/hhzpymgjmxfk), etc.). Always make sure they up-to-date before using of course, but they are a great start to getting your paper in a similar (or exact) format for submittal.

Overleaf can also read directly from a custom Git repository, so you can store your files in your own repo. However, at the time of writing this, you must use a repo for just the paper itself, not as a subdirectory of an existing repo (i.e. the main .tex file needs to be at the root). If you house all your paper files in a subdirectory of an existing Git repo, you cannot instruct Overleaf to start editing/viewing from that subdirectory. [It looks like there is a work around using Git submodules](https://abyvinod.github.io/gitsubmodules.html).

[Notepad++](https://notepad-plus-plus.org) editor has a [MarkdownViewerPlusPlus](https://github.com/nea/MarkdownViewerPlusPlus) plugin with live editing viewer. It is mostly (though not 100%) consistent with [GitHub Markdown](https://guides.github.com/features/mastering-markdown).

[Sublime](https://www.sublimetext.com/) editor also has a [Markdown Live Preview](https://packagecontrol.io/packages/MarkdownLivePreview) package for live editing of [Markdown syntax files](https://en.wikipedia.org/wiki/Markdown) (to run it press `Alt+m`). Though it is even less consistent with GitHub Markdown.

