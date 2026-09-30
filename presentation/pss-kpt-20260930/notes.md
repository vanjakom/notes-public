# OSM
  
OSM је база података.  
  
https://openstreetmap.org је само сервис за преглед мапе.  

# OSM екосистем
  
Око OSM постоји екосистем алата и сервиса који читају и   
мењају базу.   
  
Измене (промена постојећих или додавање нових података) се уносе уз помоћ   
едитора преко интеpфејса за комуникацију са базом (API).  
https://wiki.openstreetmap.org/wiki/API_v0.6  
  
Едитори могу бити опште намене или тематски - усмерени ка групи података.  
  
Општи:  
https://ideditor.com (Edit на https://openstreetmap.org)  
  
https://josm.openstreetmap.de  
  
https://level0.osmz.ru  
  
Анализа и измена података ПСС у OSM:  
https://github.com/vanjakom/osm-pss-integration  
  
Едитори за мобилне уређаје:  
https://vespucci.io  
  
https://github.com/bryceco/GoMap  
  
https://streetcomplete.app/  
  
https://every-door.app/  
  
Преглед и коришћење података:  
https://github.com/openstreetmap-carto/openstreetmap-carto  
  
https://overpass-turbo.eu  
  
https://hiking.waymarkedtrails.org  
  
https://opentopomap.org/  
  
https://garmin.opentopomap.org  
  
https://brouter.de  
  
https://staze.pss.rs  
  
https://github.com/vanjakom/pss-map-v1/  
  
Мобилне апликације:  
https://www.alltrails.com  
  
https://www.locusmap.app  
  
https://osmand.net  
  
https://organicmaps.app  
  
https://maps.me  

# tile
  
https://tile.openstreetmap.org/0/0/0.png  
  
https://tile.openstreetmap.org/1/0/0.png  
https://tile.openstreetmap.org/1/1/0.png  
https://tile.openstreetmap.org/1/0/1.png  
https://tile.openstreetmap.org/1/1/1.png  
  
https://tile.openstreetmap.org/12/2280/1476.png  

# OSM data model
  
tags - map, list of key, value pairs. key must be unique.  
  
node - longitude, latitude, tags  
noderef - pointer to node  
  
way - list of noderefs, tags  
wayref - pointer to way  
  
relation - mixed list of noderef, wayref, relationref, tags  
relationref - pointer to relation  

# OSM node
пијаћа вода  
https://www.openstreetmap.org/node/9909056459  
  
https://level0.osmz.ru/?url=n9909056459  
```  
node 9909056459: 44.1277537, 20.0154494  
  amenity = drinking_water  
```  
  
https://wiki.openstreetmap.org/wiki/Tag:amenity%3Ddrinking_water  

# OSM way
Планинарски дом „На пољани”  
https://www.openstreetmap.org/way/690352197  
  
https://level0.osmz.ru/?url=w690352197  
```  
way 690352197  
  addr:housenumber = 12  
  addr:street = Краљев сто  
  building = yes  
  building:levels = 2  
  capacity = 32  
  ele = 1000  
  int_name = Planinarski dom „Na poljani”  
  name = Планинарски дом „На пољани”  
  name:sr = Планинарски дом „На пољани”  
  name:sr-Latn = Planinarski dom „Na poljani”  
  note = 32 kreveta / 32 beds  
  operator = Milomir Milošević: +381 14 236-377;Dušan Obradović: +381 64 461-3414;+381 62 851-7096  
  ref:RS:kucni_broj = 6840535  
  tourism = alpine_hut  
  website = www.magles.org.rs/index.php/planinarski-domovi  
  
  nd 6476853370  
  nd 6476853371  
  nd 6476853372  
  nd 6476853373  
  nd 6476853370  
```  
  
https://wiki.openstreetmap.org/wiki/Tag:tourism%3Dalpine_hut  

# OSM relation
Дивчибаре центар - Планинарски дом „На Пољанама”  
https://www.openstreetmap.org/relation/14281022  
  
https://level0.osmz.ru/?url=r14281022  
```  
relation 14281022  
  ascent = 170  
  descent = 149  
  distance = 5.9 km  
  name = Дивчибаре центар - Планинарски дом „На Пољанама”  
  name:sr = Дивчибаре центар - Планинарски дом „На Пољанама”  
  name:sr-Latn = Divčibare centar – Planinarski dom „Na Poljanama“  
  network = rwn  
  operator = Magleš PSD  
  osmc:symbol = red:red_round::5:white  
  ref = 3-22-5  
  roundtrip = no  
  route = hiking  
  source = pss_staze  
  type = route  
  website = https://pss.rs/terenipp/divcibare-centar-planinarski-dom-na-poljanama/  
  
  wy 36192682  
  wy 1464303301  
  wy 36192681  
  wy 861215082  
  wy 861215083  
  wy 36192087  
  wy 1039705920  
  wy 36191266  
  wy 1462260901  
  wy 1462260900  
  wy 861215072  
  wy 1072195388  
  wy 1295793262  
  wy 36219194  
  wy 1072195390  
  wy 892184952  
  wy 892184948  
  wy 892184949  
  wy 892184934  
  wy 884223775  
  wy 631654118  
  wy 884223770  
  wy 964894719  
  wy 252140446  
  wy 252140436  
  wy 1072195391  
  wy 1248012467  
  wy 484429138  
  wy 473446368  
  wy 936931660  
```  
  
https://wiki.openstreetmap.org/wiki/Hiking  
  
https://wiki.openstreetmap.org/wiki/Tag:route%3Dhiking  

# OSM Notes
  
Интегрисане у OSM homepage.  
  
http://openstreetmap.org/?layers=N  
  
Могућност додавања без логовања (анонимно).  

# ОСМ Заједница у Србији
  
OSM Вики странице:  
https://wiki.openstreetmap.org  
  
https://wiki.openstreetmap.org/wiki/WikiProject_Serbia  
  
https://wiki.openstreetmap.org/wiki/Serbia/Beleske/Dobrodosli  
  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti  
  
https://wiki.openstreetmap.org/wiki/Serbia/Mapping_Serbia  
  
vanjakom: Како мапирати:  
https://github.com/vanjakom/zanimljiva-geografija/blob/master/blog/kako_mapirati.md  
  
Сајт OSM заједнице у Србије:  
https://openstreetmap.rs  
  
OSM форум: Србија:  
https://forum.openstreetmap.org/viewforum.php?id=62  
  
Телеграм канал заједнице:  
https://t.me/osm_sr  

# Пројекти од интереса за планинаре
  
https://wiki.openstreetmap.org/wiki/Serbia/PD_Kablar_staze  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/NP_Tara_staze  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Unos_planinarskih_staza_na_teritoriji_Nacionalnog_parka_Đerdap  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Unos_planinarskih_staza_na_teritoriji_SRP_Obedska_bara  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Unos_pešačkih_staza_na_teritoriji_SRP_Deliblatska_peščara  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Unos_pešačkih_staza_na_teritoriji_SRP_Gornje_Podunavlje  
  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/PSS_staze  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Planinarske_staze_Grze  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Odrzavanje_pesackih_staza_Srbije  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Evropski_pešački_put_E7  
https://wiki.openstreetmap.org/wiki/Serbia/Projekti/Vodic_za_planinare  
  
Планинари и OSM:  
  
https://wiki.openstreetmap.org/wiki/Serbia/Beleske/Planinari_i_OSM  

# Демо: Map data и Query tool
  
https://www.openstreetmap.org/#map=17/44.104113/19.990252  

# Демо: Overpass turbo
  
Пијаћа вода на Дивчибарама:  
https://overpass-turbo.eu/s/2xe8  

# Демо: додавање забелешке и измена OSM
  
Креираћемо забелешку и решити је изменом OSM базе.  
  
Продавница је затворена:  
https://www.openstreetmap.org/node/13592011429  

# Демо: додавање планинарске стазе
  
https://pss.rs/terenipp/narcisu-u-pohode/  
  
https://vanjakom.github.io/osm-pss-integration/dataset/osm-state.html  

