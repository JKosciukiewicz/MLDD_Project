<h1>Repository for Machine Learning in Drug Development class project, UJ 2023/2024.</h1>

<h1>PL</h1>
<h2>Cele projektu:</h2>
Celem projektu było znalezienie ciekawych zależności w dużych
publicznych zbiorach baz związków przy pomocy
narzędzi klastrowania i zmniejszenia wymiarowości danych (z wykorzystaniem algorytmu t-SNE) w celu wizualizacji.
<h2>Wyniki</h2>
Wyniki projektu pozwoliły na potwierdzenie postawionych hipotez:
<ol>
<li>W obrębie poszczególnych grup związków chemicznych można zaobserwować wspólne cechy korelujące ze źródłem ich danych.</li>
<li>Związki chemiczne nie są równomiernie rozłożone w przestrzeni chemicznej, co można zbadać poprzez analizę ich rozmieszczenia w wybranej przestrzeni.</li>
<li>Klastrowanie związków chemicznych na podstawie wartości ich aktywności odkryje niespójności pomiędzy różnymi testami biologicznymi.</li>
<li>Leki spełniające cztery kryteria Lipińskiego mają szansę stać się skutecznym lekiem doustnym.</li>
</ol>
<h2>Zawartość</h2>
<ul>
    <li><code>/data_helpers</code> - notebooki wykorzystywane do wyciągania danych baz chembl i pubchem</li>
    <li><code>/outputs</code> - wyniki eksperymentów</li>
    <li><code>/data</code> - dane do eksperymentów </li>
    <li><code>/plots</code> - wykresy wygenerowane przez notebooki</li>
    <li><code>/slides</code> - prezentacje z przedmiotu </li>
</ul>
Notebooki:
<ul>
    <li><code>Clustering_examples</code> - klastrowanie na podstawie ModlecularWeight,XLogP,HBDonorCount,HBAcceptorCount.</li>
    <li><code>Clustering_examples_8_compounds</code> - klastrowanie 8 związków na podstawie fingerprintów Morgana, pochodzenia kwasowosci i własności przeciwbólowych (test na 8 związkach).</li>
    <li><code>Clustering_examples_second_part</code> - j.w. ale na większym zbiorze związków</li>
    <li><code>Clustering_examples_new</code> - klastrowanie na podstawie ActivityValue </li>
</ul>
<h2>Uruchomienie</h2>
Stwórz srodowisko:
<code>conda env create -f environment.yml</code><br>
Uruchom:
<code>conda activate MLDD_Project</code>
<h1>EN</h1>
<h2>Objectives:</h2>
The aim of the project was to find interesting relationships in large
public collections of relationship databases using
clustering tools and reducing the dimensionality of the data (using the t-SNE algorithm) for visualisation.
<h2>Results:</h2>
The results of the project allowed confirmation of the hypotheses set out:
<ol>
<li>Within each group of chemical compounds, common features can be observed that correlate with the source of their data.</li>
<li>Chemical compounds are not uniformly distributed in chemical space, which can be investigated by analysing their distribution in the selected space.</li>
<li>clustering compounds based on their activity values will uncover inconsistencies between different bioassays.</li>
<li>drugs that meet Lipinski's four criteria have the potential to become effective oral drugs.</li>
</ol>
<h2>Contens:</h2>
<ul>
    <li><code>/data_helpers</code> - notebooks used to extract data from chembl and puchem databases</li>
    <li><code>/outputs</code> - outputs from experiments</li>
    <li><code>/data</code> - data dir for csv files </li>
    <li><code>/plots</code> - plots generated for experiments (used for slides only)</li>
    <li><code>/slides</code> - class presentations (in polish) </li>
</ul>
Notebooks:
<ul>
    <li><code>Clustering_examples</code> - clustering based on ModlecularWeight,XLogP,HBDonorCount,HBAcceptorCount values.</li>
    <li><code>Clustering_examples_8_compounds</code> - testing on 8 compounds to check te feasibility to clustering based of off Morgan fingerprint, acidity, natural origin and anaglesic properies.</li>
    <li><code>Clustering_examples_second_part</code> - same experiment on larger dataset</li>
    <li><code>Clustering_examples_new</code> - clustering based on ActivityValue </li>
</ul>
<h2>How to run</h2>
Create env:
<code>conda env create -f environment.yml</code><br>
Run env:
<code>conda activate MLDD_Project</code>