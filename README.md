# HICSS-Influence
Joint project focused on the development of a specialized visualization tool aimed at understanding the influence of HICSS papers on other fields along with identifying the most influential authors and groups in HICSS.

<h3>Overview</h3>

Spurred by the 50th anniversary of the Hawaiian Conference on System Sciences (HICSS), a joint project involving 6 researchers was undertaken to develop a set of visualization tools that could help analyze and understand how HICSS has changed over time and the influence it has had on other academic/research fields.  Towards this end the major questions to be answered were:
<ul>
<li>What other ﬁelds have been inﬂuenced by work presented at HICSS?
<li>What topics have persisted, come and gone in the HICSS community over the last 50 years?
<li>Can we develop tools that will help organizers better understand what their community and related communities are talking about?
<li>Can we identify productive and inﬂuential researchers and groups in the HICSS community (ranking)?
</ul>

<h3>Data</h3>

To answer these and other questions, a data set of HICSS citations was created by combining citation data from the Microsoft Academic Graph collection of scientific publications along data from the HICSS proceedings/papers for the years from 1995 to 2015.  This resulted in citation data for 10,321 HICSS papers from the conference proceedings. This enabled us to analyze the "inﬂuence of HICSS papers across the overall network of scientiﬁc publications. To rank papers, we calculated Article-level Eigenfactor Scores, a citation-based metric that takes into account both number and quality of incoming ci-tations. Using this data set, we identiﬁed the most productive and inﬂuential HICSS authors over the last 20 years."


<h3>Tools For Data Exploration</h3>

To better understand and visualize the data set -- three visualization tools were developed including:

<li> Citation Visualization: shows HICSS papers (by track) represented as the central node, and surrounding papers as inﬂuential papers that have cited HICSS papers. The surrounding papers appear over time, so that more recent papers appear further out from the center. The sizes of the nodes are scaled by the paper-level Eigenfactor scores (i.e., a larger circle represents a paper that has been cited by many other important papers).
<li>HICSS Voyager: allows a user to explore the prevalence of terms and bigrams, charting the occurrence of that term in HICSS papers for every year between 1995 and 2015. A line chart of these counts is then presented, either in raw counts or normal-
<li> Track Explorer: plots either the number of articles or the combined influence of all the articles within each of the HICSS tracks between 1996 and 2015.

<h3>Tool Demo and Associated Paper</h3>

More details about the project are provided in the following paper:

<a href = "http://scholar-dot-eigenfactor-dot-org.s3.amazonaws.com/hicss/HICSS_50.pdf">Measuring the HICSS Influence</a>

and online demo is also provided at:

<a href="http://scholar.eigenfactor.org/hicss">Demo of HICSS Visualization Tools</a>
