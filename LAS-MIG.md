# Nilssons Allservice – premium redesign

Lokal webbplatsleverans, skapad 19 november 2026. Ingen publicering eller kontakt med företaget har gjorts.

## Öppna webbplatsen

Öppna **index.html** i en modern webbläsare. All formgivning, alla bilder och alla vyer finns inbyggda i filen. Den kan flyttas och öppnas utan mappen assets och fungerar även utan internet. E-post, telefon och externa länkar kräver lämplig app eller uppkoppling.

**redigerbar.html** är samma webbplats med externa bildfiler och är enklare att redigera. Behåll mappen **assets** bredvid den filen.

## Innehåll

17 vyer: startsida, tjänsteöversikt, åtta tjänstesidor, Om oss, arbetsområden, bildgalleri, vanliga frågor, kontakt, offert och integritet. Navigationen använder adresser som `index.html#/tjanster/grasklippning`.

Startsidan har en fotografisk hero över hela sidbredden och minst hela första skärmhöjden. Två manuella säsongsval växlar bild och information. Navigationen är transparent över heron och får solid bakgrund längre ned och på undersidor. På korta skärmar får heron växa för att text och kontroller ska få plats.

Övriga funktioner: responsiv layout, ljust och mörkt färgtema, mobilmeny, klickbara telefon- och mejllänkar, områdesväljare, filtrerbart bildgalleri, tillgänglig bildvisare och offertflöde i tre delar. **Designed by Ekom** länkar till https://ekom.se.

## Offert och kontakt

Formulären **förbereder ett mejl**, utan att skicka det. Besökaren granskar och skickar själv i sin e-postapp. Ett textunderlag kan laddas ned och användas i annan e-posttjänst. Bilder bifogas manuellt i mejlet.

I offertflödet är telefonnummer obligatoriskt och besökarens e-postadress valfri, i linje med originalets offertupplägg. Kontaktformuläret har samma enhetliga val i redesignen. Snöröjning och halkbekämpning är avgränsat till **Hjo kommun** i såväl innehåll som offertkontroll.

Den faktiska mejllänken på originalwebbplatsen går till **pnilssonallservice@gmail.com**, även när länktexten visar info@nilssonsallserviceforhjoab.se. Leveransen använder den verkliga länkmottagaren och visar samma Gmail-adress öppet. Detta finns dokumenterat i KALLOR.md. Mottagning har inte testats genom att skicka mejl.

Ingen server, databas eller extern formulärtjänst krävs. Uppgifter sparas bara i minnet i den öppna fliken och töms vid omladdning eller stängning. Automatiskt inskick kräver en separat konfigurerad och testad mottagartjänst.

## Företagsuppgifter och bilder

Företagsnamn, org.nr 559396-8968, adress, telefon, öppettider, arbetsområde och tjänsteutbud är kontrollerade mot originalwebbplatsen. Företagsidentitet stöds också av externa registeruppgifter. Källor och verifieringsgränser finns i **KALLOR.md** och **foretagsuppgifter.json**. Kontrollera uppgifterna med företaget inför publicering.

Originallogotypen och samtliga foton är hämtade från företagets ursprungliga webbplats. Fotona är **Pexels-illustrationer**, inte verifierade kundprojekt eller bilder på företagets medarbetare. Detta framgår i galleriet och bildkällorna. Inga påhittade recensioner, projekt, kunder, teamprofiler, certifieringar eller svarstidslöften har lagts till.

**bildkallor.json** innehåller källadresser, mått, beskärningar och kontrollsummor för bildfilerna. Bilderna har endast beskurits, skalats och komprimerats. Inga generativa bildändringar har gjorts.

## Publicering

Paketet fungerar på vanlig statisk webbhosting. Mapparna `begaer-offert` och `kontakta-oss` innehåller vidarekopplingar till motsvarande vy och bevarar originalets huvudsakliga undersidesadresser vid uppladdning.

Vyerna har egna sidtitlar, men är inte separata serverrenderade SEO-sidor. En framtida fullständig SEO-migrering bör ge tjänsterna egna sökbara adresser och anpassa metadata, omdirigeringar och strukturerade företagsuppgifter.

## Kontrollerad leverans

Alla 17 vyer har kontrollerats vid 320, 390, 768, 1024 och 1440 pixlars bredd. Heron har även testats på stora skärmar och liggande små skärmar. Inga överlappningar, avklippta rubriker eller sidledsöverflöden hittades.

Säsongsval, områdesväljare, vinteravgränsning till Hjo, galleri/filter, tangentbordsnavigation, mobilmeny, formulärvalidering, valfri e-postadress, mejlutkast och textnedladdningar är testade. Inga mejl har skickats.

Den fristående filen har också öppnats utan internet: inbyggda bilder och vyer fungerar utan externa HTTP-anrop. Moderna webbläsare krävs för bildformatet AVIF och den inbyggda bildvisaren.

Automatisk kontroll av startsidan: Lighthouse 80 för prestanda och 100 för tillgänglighet, tekniska rekommendationer och grundläggande SEO. Detta är ett lokalt, simulerat mobiltest, inte ett löfte om sökplacering eller resultat på en viss hosting. Den fristående filen är cirka 0,63 MB och ZIP-paketet cirka 0,87 MB.

## Förhandsvisning

Den tillfälliga förhandsvisningen på datorn fungerar bara medan den lokala förhandsvisningen är igång. För att öppna leveransen oberoende av den: packa upp ZIP-filen och öppna index.html i webbläsaren. Färgtemats startkod har också en reserv för webbläsare med det äldre matchMedia-gränssnittet.
