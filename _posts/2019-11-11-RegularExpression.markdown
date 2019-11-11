Part 1:
#1
\b[eat]+[senigry]+|eat\b
\beat(s|en|ing|ery|er)?|ate\b

#2
(M[aou']+m+[ae]+r)[ ]?([AaEeIl]*)?[\s-]?([GK][adhz]+[f]+[iy])

#3
[IiEeHh][isṣ]+[bfp]\w+n


Part 2:
#1
^\t(\w+), (\w+)$


#2
Vienna|Graz|Linz|Salzburg|Innsbruck|Klagenfurt|Villach|Wels|Sankt Pölten|Dornbirn|Wiener Neustadt|Steyr|Feldkirch|Bregenz|Leonding|Klosterneuburg|Baden bei Wien|Wolfsberg|Leoben|Krems|Traun|Amstetten|Lustenau|Kapfenberg|Mödling|Hallein|Kufstein|Traiskirchen|Schwechat|Braunau am Inn|Stockerau|Saalfelden|Ansfelden|Tulln|Hohenems|Spittal an der Drau|Telfs|Ternitz|Perchtoldsdorf|Feldkirchen|Bludenz|Bad Ischl|Eisenstadt|Schwaz|Hall in Tirol|Gmunden|Wörgl|Wals-Siezenheim|Marchtrenk|Bruck an der Mur|Sankt Veit an der Glan|Korneuburg|Neunkirchen|Hard|Vöcklabruck|Lienz|Rankweil|Hollabrunn|Enns|Brunn am Gebirge|Ried im Innkreis|Bad Vöslau|Waidhofen|Knittelfeld|Trofaiach|Mistelbach|Zwettl|Völkermarkt|Götzis|Sankt Johann im Pongau|Gänserndorf|Gerasdorf bei Wien|Ebreichsdorf|Bischofshofen|Groß-Enzersdorf|Seekirchen am Wallersee|Sankt Andrä

Copy list, find ", " and replace by "|"

#3
Lower Austria: (\b[\w ]+)(?=( \(L.*a\)))
Salzburg: (\b[\w ]+)(?=( \(S.*g\)))