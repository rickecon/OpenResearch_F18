## MACS 40?00: Open Research Methods (Fall 2018) ##

|  | [Dr. Richard Evans](https://sites.google.com/site/rickecon/) |
|--------------|--------------------------------------------------------------|
| Email | rwevans@uchicago.edu |
| Office | 208 McGiffert House |
| Office Hours | T 9:30-11:30am |
| GitHub | [rickecon](https://github.com/rickecon) |

* **Meeting day/time**: M,W 1:30-2:50pm, Saieh Hall, Room 242
* Office hours also available by appointment

## Prerequisites ##

Familiarity coding in either Python or R, basic understading of `Git` and [GitHub.com](https://github.com/).


## Recommended Texts (not required) ##

* Chacon, Scott and Ben Straub, [*Pro Git: Everything You Need to Know about Git*](https://git-scm.com/book/en/v2), 2nd edition, Apress (2014).


## Course description ##

The purpose of this course is to give students experience in the broad set of skills and tools for managing, collaborating on, and contributing to open source research projects. Transparency and replicability of research have received renewed emphasis in recent years due to the increased prevalence and sophistication of empirical and computational methods as well as the increased availability of large high frequency data sources. This course focuses on the open source programming languages of Python and R, but the principles could be applied to projects using any language.

The course will present the common open source software development workflow as an efficient structure for collaborative academic research. We will learn `Git` and GitHub basic tools and methods. We will practice multiple levels of documentation ranging from in-code docstrings to full PDF and HTML documentation tools. Students will implement continuous integration testing and regression testing in their own open source repositories. And students will learn how to set an environment with specific library and package versions. We will also discuss methods for anonymizing propietary data or creating synthetic datasets that can be used by the general public.


## Course Objectives and Learning Outcomes ##

* Open Research: open source, transparent, replicable, usable, collaborative
* Altruism vs. self interest
	* Open research as a marketing tool
	* Brings collaborators to you
	* Giving something away makes others willing to give to you
	* Will your ideas be stolen if you make them open?
* Open research as a tool facilitating collaboration
* GitHub basics
	* Open source workflow
	* Issue tracking
	* Using "help wanted" labels
* Continuous integration testing
* Regression testing
* Documentation
	* Code modularity
	* Code docstrings
	* GitHub `REAME.md` files
	* Sphinx/Readthedocs documentation
	* JupyterLab notebooks
	* Separate papers, technical appendices
* Replicability
	* Setting the environment
	* synthetic/dymmy data for proprietary data
	* writing packages


<!--- ## Grades ##

Grades will be based on the four categories listed below with the corresponding weights.

Assignment                   | Points |   Percent  |
-----------------------------|--------|------------|
Problem Sets                 |   50   |    62.5%   |
Project initial presentation |    5   |     6.3%   |
Project final presentation   |    5   |     6.3%   |
Project paper                |   20   |    25.0%   |
**Total points**             | **80** | **100.0%** |

* **Homework:** I will assign 5 problem sets throughout the term.
	* You must write and submit your own computer code, although I encourage you to collaborate with your fellow students. I **DO NOT** want to see a bunch of copies of identical code. I **DO** want to see each of you learning how to code these problems so that you could do it on your own.
	* Problem set solutions, both written and code portions, will be turned in via a pull request from your private [GitHub.com](https://git-scm.com/) repository which is a fork of the class master repository on my account. (You will need to set up a GitHub account if you do not already have one.)
	* Problem sets will be due on the day listed in the Daily Course Outline section of this syllabus (see below) unless otherwise specified. Late homework will not be graded.
* **Project:** The project will either be a replication of an existing structural estimation paper or an original estimation project. I will approve each project. The final writeup of the project will be worthIt will be worth 20 points, which is equivalent to two homework assignments. The initial in-class presentation of your project proposal and your final in-class presentation of your project results will each be worth 5 points. The project write up will be due on Wednesday, March 8, the day after regular classes end (first reading day).


## Daily Course Schedule ##

|  Date   | Day |           Topic             | Readings | Homework |
|---------|---|-------------------------------------|---------|-----|
| Jan.  3 | W | Introduction                        |         |     |
| Jan.  8 | M | Structural vs. reduced form disc.   | K2010   | [PS1](https://github.com/rickecon/StructEst_W18/blob/master/ProblemSets/PS1/PS1.pdf) |
|         |   |                                     | R2010   |     |
| Jan. 10 | W | Maximum likelihood estimation (MLE)  | [Notes](https://github.com/rickecon/StructEst_W18/blob/master/Notebooks/MLE/MLest.ipynb) |     |
| Jan. 15 | M | **No class (Martin Luther King, Jr. Day)** |  |     |
| Jan. 17 | W | Maximum likelihood estimation (MLE)  |        |     |
| Jan. 22 | M | Compare ML and GMM                  | FMS1995 | [PS2](https://github.com/rickecon/StructEst_W18/blob/master/ProblemSets/PS2/PS2.pdf) |
| Jan. 24 | W | Generalized method of moments (GMM) | [Notes](https://github.com/rickecon/StructEst_W18/blob/master/Notebooks/GMM/GMMest.ipynb) | [PS3](https://github.com/rickecon/StructEst_W18/blob/master/ProblemSets/PS3/PS3.pdf) |
| Jan. 29 | M | Generalized method of moments (GMM) | H1982   |     |
| Jan. 31 | W | Simulated Method of Moments (SMM)   | [Notes](https://github.com/rickecon/StructEst_W18/blob/master/Notebooks/SMM/SMMest.ipynb) |     |
| Feb.  5 | M | Simulated Method of Moments (SMM)   | DM2004  | [PS4](https://github.com/rickecon/StructEst_W18/blob/master/ProblemSets/PS4/PS4.pdf) |
|         |   |                                     | S2008   |       |  
| Feb.  7 | W | Proposal guidelines, example presentation, topics | [Notes](https://github.com/rickecon/StructEst_W18/blob/master/Project/Proposal/ProposalPresent.pdf)   |     |
| Feb. 12 | M | Workshop presentations, sign up     |     | [PS5](https://github.com/rickecon/StructEst_W18/blob/master/ProblemSets/PS5/PS5.pdf) |
| Feb. 14 | W | Student proposal presentation       |         | Prop |
| Feb. 19 | M | Project: Data Description           | ASV2013 |     |
| Feb. 21 | W | Project: Model Description          |         |     |
| Feb. 26 | M | Project: Estimation Section         |         |     |
| Feb. 28 | W | Project: Concl., Intro., Abstract   |         |     |
| Mar.  5 | M | Student project presentation        |         | Prsnt|
| Mar.  7 | W | Student project presentation        |         | Prsnt|
| Mar. 16 | Fr | Student project write-up is due (5pm) |         | Proj |


## References ##

* Adda, Jerome and Russell Cooper, *Dynamic Economics: Quantitative Methods and Applications*, MIT Press (2003)
* Altonji, Joseph G., Anthony A. Smith, Jr., and Ivan Vidangos, "Modeling Earnings Dynamics," *Econometrica*, 84:4, pp. 1395-1454 (July 2013)
* Brock, William A. and Leonard J. Mirman, "Optimal Economic Growth and Uncertainty: The Discounted Case," *Journal of Economic Theory*, 4:3, pp. 479-513 (June 1972)
* Davidson, Russell and James G. MacKinnon, *Econometric Theory and Methods*, Oxford University Press (2004)
* Duffie, Darrell and Kenneth J. Singleton, "Simulated Moment Estimation of Markov Models of Asset Prices", *Econometrica*, 61:4, pp. 929-952 (July 1993)
* Fuhrer, Jeffrey C. and George R. Moore, and Scott D. Schuh, "Estimating the Linear-quadratic Inventory Model: Maximum Likelihood versus Generalized Method of Moments," *Journal of Monetary Economics*, 35:1, pp. 115-157 (Feb. 1995).
* Gourieroux, Christian and Alain Monfort, *Simulation-based Econometric Methods*, Oxford University Press (1996)
* Hansen, Lars Peter, "Large Sample Properties of Generalized Method of Moments Estimators," *Econometrica*, 50:4, pp.1029-1054 (July 1982)
* Hansen, Lars Peter and Kenneth J. Singleton, "Generalized Instrumental Variables Estimation of Nonlinear Rational Expectations Models", *Econometrica*, 50:5, pp. 1269-1286 (September 1982)
* Keane, Michael P., "Structural vs. Atheoretic Approaches to Econometrics," *Journal of Econometrics*, 156:1, pp. 3-20 (May 2010).
* Laroque, G. and B. Salanie, "Simulation Based Estimation Models with Lagged Latent Variables", *Journal of Applied Econometrics*, 8:Supplement, pp. 119-133 (December 1993)
* Lee, Bong-Soo and Beth Fisher Ingram, "Simulation Estimation of Time Series Models", *Journal of Econometrics*, 47:2-3, pp. 197-205 (February 1991)
* McDonald, James B., "Some Generalized Functions for the Size Distribution of Income," *Econometrica* 52:3, pp. 647-665 (May 1984)
* McDonald, James B. and Yexiao Xu, "A Generalization of the Beta Distribution with Applications," *Journal of Econometrics*, 66:1-2, pp. 133-152 (March-April 1995)
* McDonald, James B., Jeff Sorensen, and Patrick A. Turley, "Skewness and Kurtosis Properties of Income Distribution Models," *Review of Income and Wealth*, 59:2, pp. 360-374 (June 2013)
* McFadden, Daniel, "A Method of Simulated Moments for Estimation of Discrete Response Models without Numerical Integration," *Econometrica*, 57:5, pp. 995-1026 (September 1989)
* Newey, Whitney K. and Kenneth D. West, "A Simple, Positive, Semi-definite, Heteroskedasticy and Autocorrelation Consistent Covariance Matrix," *Econometrica*, 55:3, pp. 703-708 (May 1987)
* Rust, John, "Comments on: 'Structural vs. Atheoretic Approaches to Econometrics' by Michael Keane," *Journal of Econometrics*, 156:1, pp. 21-24 (May 2010).
* Smith, Anthony A. Jr., "[Indirect Inference](http://www.econ.yale.edu/smith/palgrave7.pdf)," *New Palgrave Dictionary of Economics*, 2nd edition, (2008).
-->


## Disability services ##

If you need any special accommodations, please provide us with a copy of your Accommodation Determination Letter (provided to you by the Student Disability Services office) as soon as possible so that you may discuss with me how your accommodations may be implemented in this course.