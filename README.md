# departure-display-generators
This is an incomplete list of official (from TOCs and Verkehrsverbünde) and unofficial tools to create departure (&amp;arrival) displays to use at home, at stores, waitingrooms, your local hackspace and so on.
The list is currently in German only, sorry!

You can help by expanding this list! Feel free to create a PR if you know some more websites or if you want to create a better style for this list.
----

#	Offizielle Anwendungen

| Name | Link | Datenquelle | Zielgebiet | Störungen | Sonstiges |
| -------- | -------- | -------- | -------- | -------- | ------ |
| Deutsche Bahn (DB) | http://bahnhofstafeln.de/ | ? | DB InfraGO Netz | ❌ | Klassiker, man kennt ihn |
| Verkehrsverbund Stuttgart (VVS)     | https://www.vvs.de/service/apps-dienste/abfahrtstafel-konfigurator | VVS-TRIAS? | VVS und ausbrechender Verkehr | ✅ | Mehrere Haltestellen wählbar, Einbindung per iFrame, einige Configs |
| MobidataBW Monitor | https://mobidata-bw.de/pages/showroom-abfahrts-und-ankunftsmonitor | EFA-BW/TRIAS (EFA-XML) | Europaweit (teilweise)  | ✅ (nur BW, teilweise) | Mehrere Haltestellen wählbar, große Konfigurationsmöglichkeiten, wird 2027 ersetzt wegen Ende der EFA-XML API |
| Nordhessischer Verkehrsverbund (NVV) | https://www.nvv.de/service/abfahrtsmonitor | ? | NVV (außerhalb sehr eingeschränkt, aber geht)  | ❌ | Geht außerhalb vom NVV kaputt, wegen fehlender Daten oder Liniensymbolen und Livedaten |
| Verkehrsverbund Rhein-Sieg (VRS) | https://www.vrs.de/fahrplanauskunft/abfahrtsmonitor | ? | VRS | ✅ | Sehr hübsche Designauswahl mit Karte und zwei Haltestellen |
| Hamburger Verkehrsverbund (HVV) | https://www.hvv.de/de/abfahrtsmonitor | ? | ?| ? | Wird aktuell überarbeitet |
| Bremer Straßenbahnen AG (BSAG) | https://www.bsag.de/service/fuer-unternehmen#c2729 | ? | ?| ? | Nur für Unternehmen, Einrichtungen etc auf Abfrage |
| Verkehrsverbund Oberelbe (VVO) | https://www.vvo-online.de/de/fahrplan/fahrplan-fuer-entwickler/abfahrtsmonitor/index.cshtml | ? | deutschlandweit ("in Sachsen Echtzeit") | ❌ | Man kann Farben, Logos und Größe verändern und paar andere Parameter |
| Verkehrsverbund Region Trier | https://www.vrt-info.de/abfahrtsmonitor-erstellen | ? | deutschlandweit (auch teilw. außerhalb VRT Livedaten) | ❌ | Scheint einfach das zu sein, was sie auch an den Haltestellen nutzen lol |
| Aachener Verkehrsverbund (AVV) | https://avv.de/de/unterwegs/abfahrtsmonitor | ? | AVV (und ein- & ausbrechender Verkehr?) | ✅ | Wirkt etwas verbuggt bei mir, aber man kann ein paar Sachen einstellen |
| Verkehrsverbund Rhein-Mosel (VRM) | https://www.vrminfo.de/fahrplan/fahrplaene/abfahrtsmonitor | ? | VRM | ✅ | Gleicher Anbieter wie beim VRS, also schönes Design aber nur im Verbundsbereich |
| Österreichische Bundesbahn (ÖBB Infra) | https://meine.oebb.at/abfahrtankunft/departure?evaNr={eva-nummer}&static=true | ? | ÖBB | ✅ | Gleiche Anzeigen wie am Bahnsteig |
| bodo | https://bodo-display.de/ | ? | bodo | ? | Website bei mir sehr langsam und träge, wenig config Möglichkeit, wird auch an Haltestellen genutzt glaube ich 
| Verkehrsverbund Pforzheim Enzkreis (VPE) | https://abfahrten.vpe.de/ | EFA-BW | Europaweit (teilweise) | ✅ (innerhalb BW) | Zukunft des Projekts fraglich, durch Fusionierung des VPE in den KVV. Projekt und weitere Infos auf Github: https://github.com/sebastianknopf/stopmonitor |
| Verkehrsverbund Rhein-Ruhr (VRR)| https://abfahrtsmonitor.vrr.de/ | ? | Deutschlandweit (teilweise) | ❌ | EFA-Konfigurator: Einige Optionen |
| Verkehrsverbund Berlin-Brandenburg (VBB)| https://abfahrtsmonitor.vbb.de/ | ? | VBB | ❌ | EFA-Konfigurator: Einige Optionen |
| ESWE Verkehrsgesellschaft (Wiesbaden)| https://www.eswe-verkehr.de/service/abfahrtsmonitor.html | ? | ESWE | ❌ | Public Version mit weniger Configs, Enterprisezugang kostenlos anforderbar mit mehr Optionen |
| Rostock Straßenbahn AG (RSAG) | https://abfahrten-rsag.de/dfi | ? | RSAG | ✅ | |
| mobiel (Bielefeld)| https://haltestellenmonitor.vrr.de/vu/mobiel#/index | ? | deutschlandweit (teilweise) | ❌ | EFA-Konfigurator: Einige Optionen |
| Zürcher Verkehrsverbund (ZVV)| https://www.zvv.ch/de/service/diverse-services/individuelle-fahrgastinfo/individuelle-abfahrtsanzeige.html | ? | ZVV | ❌ |  |
| Wiener Linien | https://digitales.wien.gv.at/open-data/ | Wiener Linien Datendrehscheibe | Wien                                                  | ? | nur mit Account bei Digitales Wien möglich; |
| Rhein-Neckar-Verkehr GmbH (RNV)| https://abfahrtsmonitor.rnv-online.de/displaymode?hafasid=2417&switchtime=7&uffbasseSliderSwitchtime=1 | RNV DDS | RNV | ✅ | [Haltestellen IDs](https://directions.nwex.de/files/rhein-neckar-verkehr/stations.json) |
| öV Plus| https://www.oevplus.ch/departures/ | ? | schweizweit | ✅ |  |

#	Inoffizielle Services
| Name | Link | Datenquelle | Zielgebiet | Störungen | Sonstiges |
| -------- | -------- | -------- | -------- | -------- | ------ |
| dbfake (dbf) | https://dbf.finalrewind.org/ | verschiedene | verschiedene | jain | Open Source mit vieeelen Anzeigeoptionen und Datenquellen |
