Indonesian census 2010
======================
This repository contains code to make structured, machine-readable data out of the tables in the [PDF file](http://bps.go.id/eng/download_file/Population_of_Indonesia_by_Village_2010.pdf) of the 2010 Indonesian census. 



The data is available in multiple formats:

|Type|Note|
|---|---|
|[Fusion table: population per village](https://www.google.com/fusiontables/DataSource?docid=1OlmGuziakXDKU7EB-By-xUZH_2YiQdTGP5HWMohG)|based on CSV file [`population_indonesian_villages.csv`](https://github.com/digitalheir/Indonesia-Census-2010/blob/master/population_indonesian_villages.csv)|
|[Fusion table: population per municipality](https://www.google.com/fusiontables/DataSource?docid=1su6q9up2aM42sRSIJk6Qmg1y_u04fjm0bCJ4uKFV)||

To facilitate geocoding, the tables contain a column with all location information concatenated (country + province + municipality + district + village). 

Aditionally, I have changed the name "GUN0NG KAPHO" (with the number 0) to "GUNONG KAPHO"  (with the letter 'O').

[![Heat map of Indonesian population](https://leibniz.cloudant.com/assets/binary/indonesia-heat-map-no-labels.png)](https://www.google.com/fusiontables/DataSource?docid=1OlmGuziakXDKU7EB-By-xUZH_2YiQdTGP5HWMohG&pli=1#chartnew:id=9)
[![Pie chart of Indonesian population per province](https://leibniz.cloudant.com/assets/binary/indonesia-chart.png)](https://www.google.com/fusiontables/DataSource?docid=1OlmGuziakXDKU7EB-By-xUZH_2YiQdTGP5HWMohG&pli=1#chartnew:id=9)

More information 
================
|Source|URL|
|---|---|
|Wikipedia|https://en.wikipedia.org/wiki/Indonesian_2010_census|
|Statistics Indonesia|http://www.bps.go.id/eng/menutab.php?tabel=1&kat=1&id_subyek=12|
