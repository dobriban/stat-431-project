# Stat 431 project
 
This is the description of the final project for Stat 431, Spring 2020, at the University of Pennsylvania.
 
 The ongoing Covid-19 pandemic has cut the academic year off and affected each of our lives. Given its urgency, a lot of work is being done to mitigate its effects. Some of that work, and some decisions being made, is informed by statistics. Given this, in this project you will aim to understand some aspect of how statistics is used to learn about Covid-19. As the instructor, I think this is important for you to appreciate that statistical thinking is crucial, even in this time of crisis.
 
 You will read a paper that addresses any aspect of the pandemic, and write a short summary/report/essay on how statistics is being used. There are many aspects of Covid-19 that use statistics, and you are free to choose what interests you most:
 
 
 ## Epidemiological aspects:
  - estimating the reproductive number of the virus & other aspects (e.g., mean interval between infection and symptoms/incubation period [both mean and other percentiles], epidemic doubling time, mean serial interval, onset-to-first-medical-visit and onset-to-
admission distribution, serial interval distribution, i.e.,  the delay between illness onset dates in successive cases in chains of transmission)
      + a specific interesting problem is estimating R_0 based on the serial interval distribution and the doubling time
  - estimating the mortality rate for various groups (e.g., first understand the demographics of the cases, then understand possible sampling biases)
  - estimating the effectiveness of interventions like masks, travel bans, and social distancing in reducing the spread
  - estimating and modelling the growth rate 
 
 ## Medical aspects:
  - estimating the need for various medical resources (beds, masks)
  - estimating the effectiveness of vaccinces and other treatments (e.g., what is the effect of wearing various types of masks?)
  
 ## Economic aspects:
  - estimating the economic impact and losses due to the virus (e.g., increase in unemployment rate, decrease in rate of growth of GDP)
  - evaluating the impact on the stock market (e.g., assessing the magnitude of the crash)

Other aspects: feel free to choose other aspects if you are interested. Moreover, you are free to supplement your work by looking at other readings.

### Special notes
 * of course, it will may be hard to do summaries at the highest quality. However, before anyone accuses us of being dilettantes, it is important to remember that the goal of this project is an exercise of your critical reading & understanding skills. And specifically, it is about practicing your knowledge of statistics to wade through primary sources, to sort out fact and fiction about a critically important problem. 
 * a more active perspective instead of reading papers may be to do your own data analysis & visualization to help understand Covid-19. There are several statistical analyses and visualizations that give valuable insights: [JHU cases map](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6), [Nextstrain phylogenetic tree](nextstrain.org), [covid-19 dashboards](https://covid19dashboards.com/). However, doing this in a quality fashion takes a lot of time & energy, so, while being valuable, I think it may be outside of the scope of this class.

## Instructions: 

For each (and many more aspects) there is an extensive body of scientific work being done. You only need to read one paper, and to your best ability, summarize the statistical aspects. Here are a few questions you should answer:

1. what is the goal of the study?
2. what type of data do they use? is it observational, experimental (refer to the sections where we studied this)? what does it measure (case medical characteristics, questionnaires)? are there any possible biases in the data?
3. what type of statistical tools do they use?
 * 3a. how do they visualize the data? do they use histograms, boxplots, etc? is it compelling?
 * 3b. what kind of statistical methods do they use? e.g., data summarization (mean/median, standard deviation), hypothesis testing, confidence intervals, p-values,  regression analysis,
 * 3c. if possible, go in some detail about one or two examples. e.g., what was the quantity estimated? how did they set up the model? how did they estimate? 
4. what do they conclude? how does the data support the conclusions? 
5. what are your overall impressions? what were the strong points, what were the limitations, what could be improved? 

I anticipate that 3c may be challenging for many papers, because they may use advanced statistical methods that we have not covered in the class. I have a few comments and suggestions: first, the goal is not to understand in 100% detail the subtleties of the technique, but rather to appreciate how the methods are used. The goal is to understand the methods as well as you can, based on the training in the class, and based on your independent research. You are expected to look up relevant methods that appear in the work on the internet and spend some time understanding them. This will also be a valuable experience - no matter how many statistics classes you take, in your work you will always encounter new methods, and you need to be prepared to learn about them on the spot. Even more, as informed citizens of the future, it will serve you well to be able to read beyond what is presented to you in a processed way in popular press.

Also I anticipate that some aspects may require you to do some indepenent reading. For instance, if you talk about estimating the basic reproduction number <img src="https://render.githubusercontent.com/render/math?math=R_0">
, then you first need to understand what that is, and what models are used to estimate it. 

For some of the papers, you will need to look at the supplementary material to understand what is being done. The main body of papers often just briefly describes the methods, and the details (which can be crucial) are often reported in supplementary materials.

Your report should be about 5 pages double-spaced, standard font size and standard formatting (standard margin). You can work in groups of at most two. You should turn in your project on Canvas (there will be an Assignment created for this), by 5pm EST on May 5th 2020 (this was the date of the original final exam). 

The University of Pennsylvania's Code of Academic Integrity applies: https://catalog.upenn.edu/pennbook/code-of-academic-integrity/. Please add the phrase "This paper represents my own work in accordance with the Code of Academic Integrity" to your paper and sign below.

## References:

Here are a few relevant references: 

### Warmup and orientation

The materials below can serve as a helpful orientation into the extensive literature. However, they themselves are not appropriate to be a main source that you summarize.

* A.S. Fauci et al., [Covid-19 — Navigating the Uncharted, N Engl J Med 2020; 382:1268-126](https://www.nejm.org/doi/full/10.1056/NEJMe2002387). An overview of some basic facts and work. Has pointers to work that is suitable to summarize in the project.

### Scientific articles

The articles below can be summarized as part of the project. They are arranged into groups based on their length, complexity, and difficulty. You can choose papers from any group, but if you choose a smaller paper, then you are expected to cover it in more detail & the correctness standard is also higher. For the more complex papers, you are not expected to summarize them in full technical detail.

### Epidemiology and medicine

#### Basic level

* C. Huang et al, [Clinical features of patients infected with 2019 novel coronavirus in Wuhan, China, Lancet 2020; 395: 497–506](https://www.thelancet.com/journals/lancet/article/PIIS0140-6736(20)30183-5/fulltext). An epidemiological study structured in a direct & easy to read way. Good choice for a summary. This is perhaps the simplest one to summarize.

* Q. Li et al., [Early Transmission Dynamics in Wuhan, China, of Novel Coronavirus–Infected Pneumonia
, N Engl J Med 2020; 382:1199-1207](https://www.nejm.org/doi/full/10.1056/NEJMoa2001316). Similar later study.

#### Medium to high level

* C. Wang et al., [Evolving Epidemiology and Impact of Non-pharmaceutical Interventions on the Outbreak of Coronavirus Disease 2019 in Wuhan, China](https://www.medrxiv.org/content/10.1101/2020.03.03.20030593v1). [Video](https://harvard.zoom.us/rec/play/v8Ytceqqqzs3GNzB4gSDB_59W9TsK6Ks13RI_6cLxB62BSUAOlumZeRAZLC7e1vif7xIyy6HL_uXyNHw?startTime=1584118874000) by prof. Xihong Lin from HSPH. Another, bigger, epidemiological study. Fits SEIR model to estimate R_0, see here for background: [Simple SIR model](https://www.idmod.org/docs/hiv/model-compartments.html), [More sophisticated SEIRS model](https://www.idmod.org/docs/hiv/model-seir.html). More readable, but perhaps less scientifically rigorous exposition: [link](https://medium.com/@tomaspueyo/coronavirus-act-today-or-people-will-die-f4d3d9cd99ca). Quote from the last one, a particularly insightful and readable paragraph: 

> How can you estimate the true ones? It turns out, there’s a couple of ways. [...]
> First, through deaths. If you have deaths in your region, you can use that to guess the number of true current cases. We know approximately how long it takes for that person to go from catching the virus to dying on average (17.3 days). That means the person who died on 2/29 in Washington State probably got infected around 2/12.
> Then, you know the mortality rate. For this scenario, I’m using 1% (we’ll discuss later the details). That means that, around 2/12, there were already around ~100 cases in the area (of which only one ended up in death 17.3 days later).
> Now, use the average doubling time for the coronavirus (time it takes to double cases, on average). It’s 6.2. That means that, in the 17 days it took this person to die, the cases had to multiply by ~8 (=2^(17/6)). That means that, if you are not diagnosing all cases, one death today means 800 true cases today.

* Q. Zhao et al, [A novel analysis of the epidemic outbreak of coronavirus disease 2019
](http://www.statslab.cam.ac.uk/~qz280/papers/covid-2019-1.pdf), preprint. This work, done in part by Wharton stats faculty and alumni, argues that the epidemic doubling time (before lockdown in Wuhan) was cca 2.8 days, much lower than the cca 7 days estimated in other works (eg the Li et al paper cited above). They achieve this by careful analysis of cases that left Wuhan before the lockdown. [Data](https://github.com/qingyuanzhao/2019-nCov-Data), [analysis](https://htmlpreview.github.io/?https://github.com/qingyuanzhao/2019-nCov-Data/blob/master/1st-Report/Feb6.html)

* N v Dorelman et al, [Aerosol and Surface Stability of SARS-CoV-2 as Compared with SARS-CoV-1, N Engl J Med 2020
](https://www.nejm.org/doi/full/10.1056/nejmc2004973). An influential article evaluating the stability of SARS-CoV-2 and
SARS-CoV-1 in aerosols and on various surfaces, and estimating their decay rates using a Bayesian regression model. Good example of using sophisticated statistical methods to tackle an important problem. See the [supplement](https://www.nejm.org/doi/suppl/10.1056/NEJMc2004973/suppl_file/nejmc2004973_appendix.pdf), pages 3-5 for their methods.

* C.J. Wang et al., [Response to COVID-19 in Taiwan
Big Data Analytics, New Technology, and Proactive Testing](https://jamanetwork.com/journals/jama/fullarticle/2762689). An apparently effective set of measures in Taiwan.

* L. Yan et al., [Prediction of criticality in patients with severe Covid-19 infection using three clinical features: a machine learning-based prognostic model with clinical data in Wuhan](https://www.medrxiv.org/content/10.1101/2020.02.27.20028027v2). A statistical/machine learning model that identified three clinical features predictive of disease severity.

* R. Li et al., [Substantial undocumented infection facilitates the rapid dissemination of novel coronavirus (SARS-CoV2)
, Science  16 Mar 2020](https://science.sciencemag.org/content/early/2020/03/24/science.abb3221). Argues that a lot of infection is undocumented: "We estimate 86% of all infections were undocumented (95% CI: [82%-90%]) prior to 23 January 2020 travel restrictions." This is a very important study. However, the model is a bit beyond the level of this class, and so it may take you some additional readinng to understand it.

* S. Flaxman et al., [Estimating the number of infections and the impact of nonpharmaceutical interventions on COVID-19 in 11 European countries](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-Europe-estimates-and-NPI-impact-30-03-2020.pdf). Using a hierarchical Bayesian statistical model, estimates that a large number of deaths have been averted in Europe because of infection-control measures such as national lockdowns.

### Economics, finance, social, etc

#### Medium to high level

* W McKibbin, R Fernando, [The Global Macroeconomic Impacts of COVID-19: Seven Scenarios](https://www.brookings.edu/wp-content/uploads/2020/03/20200302_COVID19.pdf), Bookings Institution 3.2.2020. Detailed description of their Dynamic stochastic general equilibrium (DSGE) model can be found in the paper [W McKibbin & A Triggs](https://cama.crawford.anu.edu.au/sites/default/files/publication/cama_crawford_anu_edu_au/2018-04/17_2018_mckibbin_triggs_v1.pdf)
  * Referred to in UN report [Shared responsibility, global solidarity: Responding to the socio-economic impact of covid-19](https://www.un.org/sites/un2.un.org/files/sg_report_socio-economic_impact_of_covid19.pdf). Fig 3 is a good example of a statistical method for illustrating the impact on unemployment. "According to the UN International Labour Organization (ILO), five to 25 million jobs will be eradicated, and the world will lose $860 billion to $3.4 trillion in labor income." [ILO article](https://www.ilo.org/global/topics/coronavirus/impacts-and-responses/WCMS_739047/lang--en/index.htm)
<> (* S Ramelli, AF Wagner, [Feverish Stock Price Reactions to Covid-19](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3560319). Studies stock market reactions. See also easy-to-read summary (of the first version, Mar 9) at [VoxEU](https://voxeu.org/article/what-stock-market-tells-us-about-consequences-covid-19))
* [OECD Economic Outlook, Mar 2020](https://read.oecd-ilibrary.org/economics/oecd-economic-outlook/volume-2019/issue-2_7969896b-en#page1). Uses NIGEM model developed by the Nat'l Inst of Econ and Soc Research, see [here](https://nimodel.niesr.ac.uk/index.php?t=5). See also discussion of [use of models at OECD](http://www.oecd.org/officialdocuments/publicdisplaydocumentpdf/?cote=ECO/WKP(2016)60&docLanguage=En)
* Gormsen and Koijen, [Coronavirus: Impact on Stock Prices and Growth Expectations](https://retirementincomejournal.com/wp-content/uploads/2020/03/SSRN-id3556143.pdf) Uses dividend futures, contracts that pay the dividends of the aggregate stock market in a given year, to forecast GDP returns.


## Other resources
 * [WHO paper database](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/global-research-on-novel-coronavirus-2019-ncov)
 * An analysis of the papers with the highest impact and attention at [Altmetric](https://www.altmetric.com/blog/the-altmetrics-of-coronavirus-how-research-has-shaped-our-understanding/), and their updated database [dimensions.ai](https://app.dimensions.ai/discover/publication?search_text=%222019-nCoV%22%20OR%20%22COVID-19%22%20OR%20%E2%80%9CSARS-CoV-2%E2%80%9D%20OR%20%22HCoV-2019%22%20OR%20%22hcov%22%20OR%20%22NCOVID-19%22%20OR%20%20%22severe%20acute%20respiratory%20syndrome%20coronavirus%202%22%20OR%20%22severe%20acute%20respiratory%20syndrome%20corona%20virus%202%22%20OR%20((%22coronavirus%22%20%20OR%20%22corona%20virus%22)%20AND%20(Wuhan%20OR%20China%20OR%20novel))&search_type=kws&search_field=full_search&and_facet_year=2020&order=altmetric)
 * [COVID-19 Open Research Dataset](https://pages.semanticscholar.org/coronavirus-research) from Allen Institute for AI & partners, tens of thousands of articles in machine readable format, and tools to  parse the
 * reviews of papers by an expert team at Mt Sinai Immunology: [Twitter](https://twitter.com/SinaiImmunol/status/1241526700741144576)
 * summary of work being done at UCL, UK: [link](https://www.ucl.ac.uk/news/2020/mar/covid-19-ucl-academics-mobilise-provide-critical-advice-and-expert-comment)
 * up-to date data: [Worldometers](https://www.worldometers.info/coronavirus/#countries), [1point3acres](https://coronavirus.1point3acres.com/en), 
 * predictive models:
    * [Institute for Health Metrics and Evaluation, UW](http://covid19.healthdata.org/projections), [Paper](https://www.medrxiv.org/content/10.1101/2020.03.27.20043752v1), [Code](https://github.com/ihmeuw-msca/CurveFit), [Methods pdf](https://github.com/dobriban/CurveFit/blob/master/docs/methods.pdf). Used in the White House address (See below) 
    * [Imperial College, Mar 17 2020](https://www.imperial.ac.uk/media/imperial-college/medicine/sph/ide/gida-fellowships/Imperial-College-COVID19-NPI-modelling-16-03-2020.pdf)
    * Note on low quality models on the [Statistical Modeling blog](https://statmodeling.stat.columbia.edu/2020/03/31/and-the-band-played-on-low-quality-studies-being-published-on-covid19-prediction/)
    * Other discussion on modelling in [Science News](https://www.sciencemag.org/news/2020/03/mathematics-life-and-death-how-disease-models-shape-national-shutdowns-and-other)
    * Coverage in NY Times, Mar 31 2020.
    > **Models predicting expected spread of the virus in the U.S. paint a grim picture.**
    > The coronavirus studies that appear to have convinced President Trump to prolong disruptive social distancing in the United States paint a grim picture of a pandemic that is likely to ravage the country over the next several months, killing close to 100,000 Americans and infecting millions more. 
![alt text](https://github.com/dobriban/stat-431-project/blob/master/nytimes_3.31.2020_models.png "Coverage in NY Times, Mar 31 2020.")
    * Statistical models take a prominent role in a White House address: [![White House address](http://img.youtube.com/vi/CWFOKznwNhQ/0.jpg)](https://www.youtube.com/watch?v=CWFOKznwNhQ&feature=youtu.be&t=891 "White House address")
    * Statistical models also form the core of the discussion in a NY Governor's address, 4.5.2020. Quote: "by the data, we could be either very near the apex, or the apex could be a plateau & and we could be on it right now, we won't know until a few days [...] that's what the statisticians will tell you today".  [![NY Gov. Cuomo address, 4.5.2020](http://img.youtube.com/vi/kR0DXoWYS50/0.jpg)](https://www.youtube.com/watch?v=kR0DXoWYS50&feature=youtu.be&t=260 "NY Gov. Cuomo address") 
 * [Chicago Booth Initiaive on Global Markets (IGM)](http://www.igmchicago.org/covid-19/)
 * [Collection of articles in Science](https://www.sciencemag.org/coronavirus-research-commentary-and-news?intcmp=ghd_cov), many other sources temporarily collected and accessible through [Google Scholar](https://scholar.google.com/)
* [International Capital Market Association (ICMA) COVID-19 Market Updates](https://www.icmagroup.org/Regulatory-Policy-and-Market-Practice/covid-19-market-updates/), [Market data and commentary](https://www.icmagroup.org/Regulatory-Policy-and-Market-Practice/covid-19-market-updates/market-data-and-commentary/). Documents market data, focus on Europe.
* [Institute for Supply Management, March 2020 Manufacturing report](https://www.instituteforsupplymanagement.org/ISMReport/MfgROB.cfm?SSO=1). Documents decrease in manufacturing and production. 
* Are crime rates declining? [Chicago tribune article](https://www.chicagotribune.com/coronavirus/ct-coronavirus-chicago-police-new-crime-stats-20200331-utnr2apdtbdzhagsehlzvq4lvi-story.html), [Philly police crime maps](https://www.phillypolice.com/crime-maps-stats/), [Weekly reports](https://drive.google.com/drive/folders/1eo4BIOGHcibOTcHRsGoEEiNrrCsuVOdH). Is there enough data to conclude that crime rates are declining? What kind of statistical methods may one use to argue about this?


 






