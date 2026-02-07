# Taba: Tool to Analyze Binding Affinity 
 
<B>Note:</B> We are currently updating Taba to integrate it with SAnDReS 2.0 (<a href = "https://pubmed.ncbi.nlm.nih.gov/38900052/" title = "de Azevedo WF Jr, Quiroga R, Villarreal MA, da Silveira NJF, Bitencourt-Ferreira G, da Silva AD, Veit-Acosta M, Oliveira PR, Tutone M, Biziukova N, Poroikov V, Tarasova O, Baud S. SAnDReS 2.0: Development of machine-learning models to explore the scoring function space. J Comput Chem. 2024; 45(27):2333-2346. doi: 10.1002/jcc.27449. PMID: 38900052.">de Azevedo et al., 2024</a>). Taba 2.0 will employ DOME statistics (<a href = "https://pubmed.ncbi.nlm.nih.gov/34316068/" title = "Walsh I, Fishman D, Garcia-Gasulla D, Titma T, Pollastri G; ELIXIR Machine Learning Focus Group; Harrow J, Psomopoulos FE, Tosatto SCE. DOME: recommendations for supervised machine learning validation in biology. Nat Methods. 2021; 18(10): 1122-1127. doi: 10.1038/s41592-021-01205-4.">Walsh et al., 2021</a>) to evaluate machine-learning models and explore the scoring function space concept with additional regression methods available in <a href = "https://scikit-learn.org/stable/" title = "Sckit-Learn">Scikit-Learn</a> library (<a href = "https://doi.org/10.48550/arXiv.1201.0490" title =  "Pedregosa F, Varoquaux G, Gramfort A, Michel V, Thirion B, Grisel O, Blondel M, Prettenhofer P, Weiss R, Dubourg V, Verplas J, Passos A, Cournapeau D, Brucher M, Perrot M, Duchesnay E. Scikitlearn: Machine Learning in Python. J Mach Learn Res., 2011; 12:2825–2830. DOI: 10.48550/arXiv.1201.0490">Pedregosa et al., 2011</a>). We expect to release a new version of Taba in 2027.
                                            <a href = "https://www.scopus.com/authid/detail.uri?authorId=7006435557" title =  "Link to Scopus to Dr. Walter Filgueira de Azevedo, Jr.">Dr. Walter F. de Azevedo, Jr.</a> (Posted on January 28, 2026) 
<br> </br>                                           
<H2>Taba Citation</H2>

Please cite the following reference (<a href="https://www.ncbi.nlm.nih.gov/pubmed/31410856">da Silva AD et al., 2020</a>) if the Taba program was useful.

<a href="https://onlinelibrary.wiley.com/toc/1096987x/2020/41/1">
<img src="https://drive.usercontent.google.com/download?id=1bePrioau7cqicFbewNjiqi6Yw-bAyzhZ&export=view&authuser=0" width=200 align=left title="da Silva AD, Bitencourt-Ferreira G, de Azevedo WF Jr. Taba: A Tool to Analyze the Binding Affinity. J Comput Chem. 2020; 41(1): 69-73."></a>

da Silva AD, Bitencourt-Ferreira G, de Azevedo WF Jr. Taba: A Tool to Analyze the Binding Affinity. J Comput Chem. 2020; 41(1): 69-73. <a href="https://doi.org/10.1002/jcc.26048">doi: 10.1002/jcc.26048</a>.   <a href="https://www.ncbi.nlm.nih.gov/pubmed/31410856">PubMed</a>  
<p>&nbsp;</p>
Taba is free software: you can redistribute it and/or modify it under the terms of the <a href="https://www.gnu.org/licenses/gpl.txt">GNU General Public License</a> as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version. You can use a higher version as well.  
<br> </br>
<br> </br>
<br> </br>
<H2>Additional Reference for Taba</H2>
<a href = "https://doi.org/10.1007/978-1-0716-4949-7" title = "de Azevedo WF Jr, editor. Docking screens for drug discovery. 2nd ed. New York, NY: Springer; 2026.">
<img src="https://drive.usercontent.google.com/download?id=1qWkaR3YMBMcfofbC9uYrq-gSfsR1BTjx&export=view&authuser=0" width=200 align=left title="de Azevedo WF Jr, editor. Docking screens for drug discovery. 2nd ed. New York, NY: Springer; 2026.">
</a>
<p>
de Azevedo WF Jr, editor. Docking screens for drug discovery. 2nd ed. New York, NY: Springer; 2026. <a href = "https://doi.org/10.1007/978-1-0716-4949-7" title = "de Azevedo WF Jr, editor. Docking screens for drug discovery. 2nd ed. New York, NY: Springer; 2026.">DOI: 10.1007/978-1-0716-4949-7</a>
</p>
<a href="https://www.amazon.com/Docking-Screens-Discovery-Methods-Molecular-ebook/dp/B0FVTT27Z9">
<img src="https://drive.usercontent.google.com/download?id=1ktGUzRY-SOoRjdvc6xKzzBNXzB6ibJfc&export=view&authuser=0" width=100 align=left title="de Azevedo WF Jr, editor. Docking screens for drug discovery. 2nd ed. New York, NY: Springer; 2026.">
</a>
</a>
<br> </br>
<br> </br>
<br> </br>
<br> </br>
<br> </br>
<H2>How to install Taba</H2>
You need to have Python 3 installed on your computer to run Taba. In addition, you also need NumPy (1.14.5*), Matplotlib, scikit-learn (0.19.1*), pyqt4 and SciPy (1.1.0*). <br>
<font size="-1">*You can use higher versions as well.<font>

<h4>Windows</h4>

Step 1. Download Taba (available <a href="https://github.com/azevedolab/taba/blob/master/TABA_dist.zip"> here</a>)

Step 2. Unzip the zipped file (TABA_dist)

Step 3. Copy TABA_dist directory to c:\

Step 4. Open a command prompt window (Terminal) and type: cd c:\TABA_dist

then type: python taba.py

This launches GUI window for Taba. That´s it, good Taba session. See help for additional information about how to run Taba.

<h4>Linux</h4>

Step 1. Download Taba (available <a href="https://github.com/azevedolab/taba/blob/master/TABA_dist.zip"> here</a>)

Step 2. Unzip the zipped file (TABA_dist)

Step 3. Copy TABA_dist directory to the directory of your choice 

Step 4. Open a terminal and type cd /your personal directory/TABA_dist

then type: python taba.py

This launches GUI window for Taba. That´s it, good Taba session. See help for additional information about how to run Taba.


Taba was developed by Amauri Duarte and Dr. Walter F. Azevedo Jr. (walter@azevedolab.net)

Last update of the code on December 04, 2019.
<br> </br>
<h2>Prof. Dr. Walter F. de Azevedo, Jr.</h2>
<img src="https://drive.usercontent.google.com/download?id=1ao9REI0b_bCbjDy2pu4k3Tbr35LCB5Qt&export=view&authuser=0" width=200 align=left title="Walter Filgueira de Azevedo, Jr. October 02, 2024. Alfenas-MG. Brazil."></a>
<p>
My scientific interests are interdisciplinary, with three main emphases: <a href = "https://doi.org/10.3390/molecules24030637" title = "Nussinov R, Tsai CJ, Shehu A, Jang H. Computational Structural Biology: Successes, Future Directions, and Challenges. Molecules. 2019 Feb 12;24(3):637. doi: 10.3390/molecules24030637">computational structural biology</a>, <a href = "https://www.ibm.com/topics/artificial-intelligence" title = "What is AI?">artificial intelligence</a>, and <a href = "http://www.scholarpedia.org/article/Complex_systems" title = "Complex systems">complex systems</a>. In my studies, I developed several free software programs to explore the concept of <a href = "https://www.eurekaselect.com/article/84362" title = "Heck GS, Pintro VO, Pereira RR, de Ávila MB, Levin NMB, de Azevedo WF. Supervised Machine Learning Methods Applied to Predict Ligand- Binding Affinity. Curr Med Chem. 2017;24(23):2459-2470.">Scoring Function Space</a>. </p>
<p>
As a result of my research, I published over 200 scientific works about protein structures, computer models of complex systems, and simulations of protein systems. These publications have generated over 12,000 citations on <a href = "https://scholar.google.com/citations?user=HWwJXJUAAAAJ&hl=pt-BR" title = "Link to Google Scholar">Google Scholar (h-index of 63)</a> and more than 10,000 citations and an <a href = "https://www.scopus.com/authid/detail.uri?authorId=7006435557" title = "de Azevedo Junior, Walter Filgueira. Scopus ID: 7006435557">h-index of 58 in Scopus</a>.   

Due to the impact of my work, I have been ranked among the most influential researchers in the world (Fields: Biophysics, Biochemistry & Molecular Biology, and Biomedical Research) according to a database created by <a href = "https://pubmed.ncbi.nlm.nih.gov/33064726/" title = "Ioannidis JPA, Boyack KW, Baas J. Updated science-wide author databases of standardized citation indicators. PLoS Biol. 2020 Oct 16;18(10):e3000918. doi: 10.1371/journal.pbio.3000918. PMID: 33064726; PMCID: PMC7567353.">Journal Plos Biology</a> (see news <a href = "https://www.pucrs.br/en/blog/research-database-includes-7-pucrs-professors-among-most-influential-in-the-world/" title = "Research database includes 7 PUCRS professors among most influential in the world">here</a>). The application of the same set of metrics recognized the influence of my work from 2021 to 2025 (<a href = "https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/3" title = "August 2021 data-update for Updated science-wide author databases of standardized citation indicators">Baas et al., 2021</a>; <a href = "https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/4" title = "September 2022 data-update for Updated science-wide author databases of standardized citation indicators">Ioannidis, 2022</a>, <a href = "https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/6" title = "October 2023 data-update for Updated science-wide author databases of standardized citation indicators">2023</a>, <a href = "https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/7" title = "August 2024 data-update for Updated science-wide author databases of standardized citation indicators">2024</a>, and <a href = "https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/8" title = "August 2025 data-update for Updated science-wide author databases of standardized citation indicators">2025</a>). Not bad for a poor guy who was a shoe seller at a store in São Paulo and had the opportunity to study at the University of São Paulo with a scholarship for food and housing. I was 23 when I initiated my undergraduate studies and was the first in my family to have access to higher education.
<br> </br>
<a href="https://www.scopus.com/authid/detail.uri?authorId=7006435557" title = "Link to Scopus">
<img src="https://drive.usercontent.google.com/download?id=1K_1skqZBcdmgJK41OJJcr4hbXepXHje_&export=view&authuser=0" width=800 alt="Link to Scopus"></a>  
<br><i>Document and Citation Trends (<a href="https://www.scopus.com/authid/detail.uri?authorId=7006435557" title = "Link to Scopus">Scopus ID: 7006435557</a>) (Data captured on January 30, 2026)</i></br>
<br> </br>
Regarding scientific impact (<a href = "https://www.sciencenews.org/article/rating-researchers" title = "Rating Researchers">Peterson, 2005</a>), Hirsch said that for a physicist, an h-index of 45 or higher could mean membership in the National Academy of Sciences of the USA. So far, there have been no invitations. No hard feelings because I am in good company. <a href = "https://theconversation.com/carl-sagans-scientific-legacy-extends-far-beyond-cosmos-240885" title = "Carl Sagan’s scientific legacy extends far beyond ‘Cosmos’">Carl Sagan</a> was never allowed into the National Academy of Sciences. According to an analysis of citations performed on Nov. 9, 2024 (<a href = "https://theconversation.com/carl-sagans-scientific-legacy-extends-far-beyond-cosmos-240885" title = "Carl Sagan’s scientific legacy extends far beyond ‘Cosmos’">The Conversation</a>), his work accumulates more than 1,000 citations per year on Google Scholar. Indeed, his current citation rate exceeds that of many members of the <a href = "https://www.nasonline.org/membership/" title = "National Academy of Sciences">National Academy of Sciences</a>. 

I will continue working in science with low-budget and interdisciplinary projects and combating <a href = "https://revistapesquisa.fapesp.br/en/the-seeds-of-mistrust/" title = "The seeds of mistrust: A new dictionary focuses on the varieties of denialism that confuse public opinion in Brazil and around the world. Ana Paula Orlandi, da Revista Pesquisa FAPESP">denialism</a> with science. The fight against <a href = "https://revistapesquisa.fapesp.br/en/the-seeds-of-mistrust/" title = "The seeds of mistrust: A new dictionary focuses on the varieties of denialism that confuse public opinion in Brazil and around the world. Ana Paula Orlandi, da Revista Pesquisa FAPESP">denialism</a> is a continuing work, and scientists should not forget their role in a complex society where social media has given the right to speak to legions of imbeciles.

“Social media gives the right to speak to legions of imbeciles who previously only spoke at the bar after a glass of wine, without damaging the community. They were immediately silenced, but now they have the same right to speak as a Nobel Prize winner. It’s the invasion of imbeciles.”

Umberto Eco. Source: <a href = "https://quoteinvestigator.com/2024/03/21/social-media/" title = "Quote Origin: Social Media Gives the Right To Speak To Legions of Imbeciles Who Previously Only Spoke in Bars After Drinking">Quote Investigator</a>
</p>
<br> </br>
"Let the light of science end the darkness of denialism." My quote (<a href = "https://doi.org/10.2174/092986732838211207154549" title = "DOI:10.2174/092986732838211207154549">DOI:10.2174/092986732838211207154549</a>). 
<br> </br>
