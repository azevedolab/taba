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

then type: 
<pre>    python taba.py</pre>

This launches GUI window for Taba. That´s it, good Taba session. See help for additional information about how to run Taba.

<h4>Linux</h4>

Step 1. Download Taba (available <a href="https://github.com/azevedolab/taba/blob/master/TABA_dist.zip"> here</a>)

Step 2. Unzip the zipped file (TABA_dist)

Step 3. Copy TABA_dist directory to the directory of your choice 

Step 4. Open a terminal and type cd /your personal directory/TABA_dist

then type:
<pre>    python taba.py</pre>

This launches GUI window for Taba. That´s it, good Taba session. See help for additional information about how to run Taba.


Taba was developed by Amauri Duarte and Dr. Walter F. Azevedo Jr. (walter@azevedolab.net)

Last update of the code on December 04, 2019.
<br> </br>
<h2><a href = "https://github.com/azevedolab/About-Me" title = "About Prof. Walter Filgueira de Azevedo, Jr."> About Me </a> </h2> 
<a href="https://scholar.google.com/citations?user=HWwJXJUAAAAJ" title = "Link to Google Scholar">
<img src="https://drive.usercontent.google.com/download?id=1rL_DWbMj6timTlYlhn9Hwm1acq8AU4QV&export=view&authuser=0" height=24 alt="Link to Google Scholar"></a>  
<a href="https://www.scopus.com/authid/detail.uri?authorId=7006435557" title = "Link to Scopus">
<img src="https://drive.usercontent.google.com/download?id=1URGO8UDkZV_4wX_4c0_gUvhEjfnUyqCQ&export=view&authuser=0" height=24 alt="Link to Scopus"></a>
<a href="https://www.webofscience.com/wos/author/record/581112" title = "Link to Web Of Science">
<img src="https://drive.usercontent.google.com/download?id=1pEf0pZ9go-xPspc5xw_dR46fm-QfQalb&export=view&authuser=0" height=24 alt="Link to Web Of Science"></a>
<a href="https://heyzine.com/flip-book/7141841e54.html" title = "Link to Curriculum Vitae">
<img src="https://drive.usercontent.google.com/download?id=1dBTT8igB-ykqF6L3FaffrGcv-2FaNNJy&export=view&authuser=0" height=24 alt="Link to Curriculum Vitae"></a>

<br> </br>

