# Advanced geocoding

Instead of just having the spot address, we get the closest poi label. Perso (blue) vs Pro (red).

Ordered as follows:

		if algo in ('pro',):
		        sorting_order = ('business-services', 'public-transport', 'restaurant', 'shop',)
		    elif algo in ('perso',):
		        sorting_order = ('public-transport', 'restaurant', 'shop',)


## Full day

-  Full day
	-  Time range: 24/7
	-  [Full day heatmap](https://tiphaine.github.io/maas-demo/demo/advanced-poi-labels/paris-2019-04-18-final_dbscan-diff_heatmap_poi.html)


## Time range

-  Day
	-  Time range: Lundi au vendredi / 8h-19h
	-  [Day heatmap](https://tiphaine.github.io/maas-demo/demo/advanced-poi-labels/paris-2019-04-18-final_dbscan-diff_heatmap_poi_day.html)
- Morning
	- Time range: Lundi au vendredi / 8h-10h
	- [Morning heatmap](https://tiphaine.github.io/maas-demo/demo/advanced-poi-labels/paris-2019-04-18-final_dbscan-diff_heatmap_poi_morning.html)
- 	Noon
	-  Time range: Lundi au vendredi / 11h-14h
	-  [Noon heatmap](https://tiphaine.github.io/maas-demo/demo/advanced-poi-labels/paris-2019-04-18-final_dbscan-diff_heatmap_poi_noon.html)
-  Afternoon
	-  Time range: Lundi au vendredi / 13h-19h
	-  [Afternoon heatmap](https://tiphaine.github.io/maas-demo/demo/advanced-poi-labels/paris-2019-04-18-final_dbscan-diff_heatmap_poi_afternoon.html)
