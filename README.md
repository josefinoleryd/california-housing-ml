# Examinerande uppgift Machine learning-kurs 

## Syfte 

Detta projekt syftar till att med california housing-datasetet implementera både en övervakad och en oövervakad maskininlärningsmodell.

Den fiktiva beställaren, Avocado Toast Estates (ATE), vill dels ha en konkret modell som de kan använda som beslutsstöd. Modellen ska snabbt kunna klassificera bostadsområden som "högprisområde" eller "ej högprisområde" och på så sätt hjälpa ATE att spara tid och pengar. 

Avocado Toast Estates är också nyfikna på om det finns "naturliga grupper" i datan och är villiga att betala dyra konsultpengar för en kreativ undersökning med hjälp av PCA och KMeans.

ATE var mycket tydliga med att det var två olika uppdrag och vill därför ha två olika notebooks. 

## Innehåll/struktur 

Börja här! I california-housing-analysis.ipynb 

Här får du följa hela ML-flödet med att träna och testa en klassificeringsmodell. Detta är alltså uppdrag 1; ta fram en klassificeringsmodell. 

Gå sedan vidare till cluster-analysis.ipynb. Det här är uppdrag 2; kreativ undersökning med hjälp av PCA och KMeans. 

I slutet av rapporten visar det sig att 5 outliers har förstört hela klustringen. 

Därför skapades en kopia av cluster-analysis.ipynb. 

Det enda som skiljer dessa notebooks åt är att cluster-analysis-2.ipynb har strängare hantering av outliers och producerar därför ett bättre resultat. 

Jag rekommendrar att läsa igenom hela cluster-analysis.ipynb, sedan bara ögna igenom cluster-analysis-2.ipynb och sen fokusera på de sista delarna vilket är resultat av PCA och KMeans och slutsatser. 

Eller om man är helt ointresserad av att se hur det ser ut när 5 outliers förstör alltihopa så hoppar man direkt till cluster-analysis-2.ipynb!

## Installation och hur man kör 

Python version 3.13.7

1. Klona projektet från Github: git clone https://github.com/josefinoleryd/california-housing-ml.git
2. Installera nödvändiga paket: pip install -r requirements.txt
3. Öppna california-housing-analysis 
4. Öppna cluster-analysis eller cluster-analysis-2 
5. Klicka på "Run All" 

## Teknikstack

* Programmeringsspråk: Python 
* Dataanalys och beräkningar: pandas och numpy 
* Visualisering: matplotlib och seaborn
* Maskininlärning: scikit-learn
* Rapport och genomförande: Jupyter Notebook 
* Versionshantering: Git och Github