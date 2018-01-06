# java-bag
# Bag
- Legyen egy Bag<T> generikus osztályunk, mely egy zsákot valósít meg. A zsák olyan halmaz, mely többször tartalmazhatja ugyanazt az elemet.
- Legyen egy Map<T, Integer> adattagja, melyet a nulla paraméteres konstruktor megfelelően feltölt.
- Legyen egy add(T element) metódusa. Ellenőrizze, hogy van-e már ilyen kulcs a zsákban, ha nincs, tegye bele 1 értékkel. Ha van, kérdezze le az aktuális értéket, és tegye bele az eggyel megnövelt értéket. (Azt tároljuk a  map-ben, hogy melyik objektum hányszor van a zsákban.)
- Legyen egy egész visszatérési értékű countOf(T element) metódusa, mely megadja, hogy hányszor van az elem a zsákban. Ha nincs az elemhez mint kulcshoz rendelve semmilyen érték a map-ben, adjon vissza 0-t.
- Legyen a zsáknak egy remove metódusa is egy elem kivételére.
- - Csökkentse eggyel a megadott elem darabszámát a zsákban.
- - Ha 0-ra csökken a darabszám, vegye ki a megfelelő kulcs-érték párt a map-ből, hogy ne tároljunk feleslegesen adatokat. (Ehhez keressünk megfelelő metódust a java.util.Map interfészben.)
- - Ha az elem nem volt a zsákban, dobjunk NotInBagException nem ellenőrzött kivételt (származzon a RuntimeException-ből).
- Teszteljük le a zsák osztályunkat.

http://kitlei.web.elte.hu/segedanyagok/felev/2017-2018-osz/java-hun/feladatok.html
