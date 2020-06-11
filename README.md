# SEIR model basics, assumptions, and interpretation
Supporting materials for NHSEI COVID-19 Data Analytics community mini-huddle on 10 June
- Slides including detailed references
- Example basic and very stylised SEIR model for COVID-19 in Microsoft Excel

# Further examples and tools

<b>A general national UK-level model for C19 from LSHTM SAGE modellers</b> 
by Davies N et al, LSHTM CMMID nCoV Working Group <br>
<a href="https://cmmid.github.io/visualisations/covid-transmission-model">COVID-19 Transmission App</a>

<b>Another alternative SEIR webapp with visual sliders</b> 
by Gabriel Goh, <a href="https://gabgoh.github.io/COVID/">Epidemic Calculator</a>

<b>An excellent example of an operational dashboard using SEIR dynamics that has been fit to real-time Trust & PHE data</b><br> 
from the East London Health & Care Partnership - WEL Financial Strategy Team,<br> 
<a href="https://app.powerbi.com/view?r=eyJrIjoiNmI2MjM4OTAtYTBmYS00MGNhLTgzOGEtYjJhNTg0NGY0ZWU4IiwidCI6ImQyMjc2ODJmLWFiNWEtNDlmNi04NzNhLThlZmQ1MDQ1ZjBmNCJ9">"NEL COVID-19 Demand Modelling Dashboard"</a>

<b>Sub-national R0 estimates over time for the UK</b> 
from Funk S et al, LSHTM CMMID nCoV Working Group, <br>
<a href="https://epiforecasts.io/covid/posts/national/united-kingdom/"> “Temporal variation in transmission during the COVID-19 outbreak – Nationaland subnational estimates for the United Kingdom”</a>

<br>Various Python and R repositories exist for S(E)IR models </br>, including for the above examples, e.g.
- https://github.com/gabgoh/epcalc (Python)
- https://github.com/cmmid/covid-uk (R, including Rcpp with C++ style scripts and Bayesian/bootstrapped uncertainty bounds)
- https://github.com/cmmid/covidm_reports (R, with scenario modelling for various countries)
- https://github.com/ImperialCollegeLondon/covid19model/tree/master (C++, Python, and R, including stan for Bayesian uncertainty)


# Recommended reading to learn modelling
Emilia Vynnycky and Richard G White, <a href="http://anintroductiontoinfectiousdiseasemodelling.com/">An Introduction to Infectious Disease Modelling</a>

On <b>COVID-19 modelling and epidemiology</b> in general, 
my LSHTM colleagues in the Centre for Mathematical Modelling of Infectious Diseases (CMMID) nCoV working group have a fab repo of data visualisation and modelling web apps (using RShiny) and quick research reports as manuscripts are prepped for peer review.
Check it out: https://cmmid.github.io/topics/covid19/


Many thanks to Jason Pickles and Sophie Hodges from NHSE/I for inviting and coordinating to the 10 June 2020 mini-huddle.
Recording is on FutureNHS.
All queries and corrections welcome to julia dot shen dot 1 at lshtm dot ac dot uk
