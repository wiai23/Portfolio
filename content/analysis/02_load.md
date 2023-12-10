Utvärdering av webbplatsers laddningstid och användbarhet
=======================



Urval
-----------------------

Jag gjorde ett urval på publika platser samt en djurpark för att få lite olika webbplatser.

Metod
-----------------------

Vid insamling av mätvärden använde jag <a href="https://pagespeed.web.dev/">Google Pagespeed</a> och devtools flik networks.

Resultat
-----------------------
<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vSDdNP9V-_YWxE1i4dCwQYYIf-a2kk37YGrCO_rLYGSJ4K7GMIpHgvU1s5w-7bNCdFhOqazj3A57wsa/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false" title="Mätvärden"></iframe>
</div>


![Skansen](../image/skansen.PNG?w=25%)
<a href="https://skansen.se/en/">Skansen</a>
Performance 81/100
Laddningstiden på webbsidan var ganska lång, cirka 10 sekunder och det borde finnas förbättringspotential så att laddning går fortare.

![SVT](../image/svt.PNG?w=25%)
<a href="https://www.svt.se/">SVT</a>
Performance 68/100
När jag mätte med Google Pagespeed via mobil så tog den längre tid i jämförelse med laddning via desktop.

![1177](../image/1177.PNG?w=25%)
<a href="https://www.1177.se/">1177</a>
Performance 79/100
Vid de olika försöken att ladda sidan så varierade tiden ganska mycket.

Analys
-----------------------

De vanligaste förbättringsåtgärderna för mitt urval av webbplatser. På Skansens webbsida skulle att optimera bilderna kunna förbättra laddningstiden på sidan. För SVT skulle borttag av render-blocking resources kunna förbättra så att sidan laddas snabbare. På webbsidan för 1177 är en förbättring att reducera oanvända JavaScript och minska oanvända CSS.

Min rangordning av webbsidorna är 1. SVT 2. 1177 3. Skansen. Det troliga att Skansen kom sist är att Skansen hade många icke optimiserade resurser.

Jag uppfattar snabb laddningstid som undgefär en halv sekund och lång är flera sekunder. SVT och 1177 laddade på cirka en halv sekund vilket för mig är en snabb laddningstid. Medan Skansen låg på över 10 sekunder.

Referenser
-----------------------

<a href="https://pagespeed.web.dev/">Google Pagespeed</a>

<a href="https://skansen.se/en/">Skansen</a>

<a href="https://www.svt.se/">SVT</a>

<a href="https://www.1177.se/">1177</a>

Övrigt
-----------------------

Författare William Alinder.