---
title: Ohjeistus elinkaaritietojen vientiin
description: Ohjeistus tuotteen elinkaarta koskevien tietojen viennin tekemiseen
ms.date: 12/16/2020
layout: ContentPage
ms.openlocfilehash: 5e9dddbff5fac32e6d3cf8ef0943151d2dfe5e35
ms.sourcegitcommit: 6ea3221fd5475440480515f04f33988656d71748
ms.translationtype: HT
ms.contentlocale: fi-FI
ms.lasthandoff: 11/02/2021
ms.locfileid: "3546796"
---
# <a name="lifecycle-data-export-guidance"></a>Ohjeistus elinkaaritietojen vientiin
Tässä asiakirjassa käydään läpi tuotteen vientitiedoston käyttäminen.

## <a name="query-information"></a>Tietojen käsittely
Excel-asiakirjassa on kenttiä, joiden avulla voi tunnistaa tuotetaulukkoon täytetyt tiedot.

### <a name="end-of-support"></a>Tuen päättymispäivä
Tuen päättymisajankohdan arvo suodattaa tuotteet joko tuen päättymispäivän tai niiden julkistuksen päättymispäivän mukaan.

Mahdollisia arvoja: Kaikki (ei suodattimia käytössä), vuosi ja aikaväli.

### <a name="family"></a>Perhe
Perheen arvo suodattaa tuotteet tuoteperheen mukaan, joka on tuotteiden ylätaso hierarkiassa.

Mahdolliset arvot: Kaikki (ei suodattimia käytössä), perheen nimi

### <a name="group"></a>Ryhmä
Ryhmän arvo suodattaa määritetyille ylätasoilleen (perheisiin) kuuluvat tuotteet laajemman ryhmän perusteella.

Mahdollisia arvoja: Kaikki (ei suodattimia käytössä), ryhmän nimi

## <a name="table-columns"></a>Taulukon sarakkeet
Tuotetaulukko koostuu sarakkeista, jotka määrittävät tuotteen, versiot, julkaisut ja niihin liittyvät tuen päivämäärät.

> [!NOTE]
> Kullekin tuotteen, version ja julkaisun yhdistelmälle varataan oma rivi.

### <a name="product"></a>Tuote
Tuotteen nimi.

### <a name="edition"></a>Versio
Version sarake täytetään, kun tuotteesta on eri versioita. Kun tuoteversiota ei ole, tämä kenttä jää tyhjäksi.

### <a name="release"></a>Julkaisu
Julkaisujen sarake täytetään, kun tuotteesta on eri julkaisuja.
Kun tuotteella on vain yksi julkaisu, tämä kenttä on tyhjä.

### <a name="support-policy"></a>Tukikäytäntö
Tämä kenttä määrittää, mitä tukikäytäntöä tuote noudattaa.

Mahdollisia arvoja: [kiinteä](/lifecycle/policies/fixed), [moderni](/lifecycle/policies/modern), komponentti

### <a name="start-date"></a>Alkamispäivä
Tuotteen tuen alkamisen päivä.

### <a name="mainstream-date"></a>Mainstream-päivämäärä
Kun tukikäytäntönä on **kiinteä** tai **komponentti**, tämä ilmaisee tuotteen Mainstream-päättymispäivän.
  
Kun tukikäytäntö on **moderni**, sarake jää tyhjäksi.

### <a name="extended-end-date"></a>Laajennetun tuen päättymispäivä
Kun tukikäytäntönä on **kiinteä** tai **komponentti**, tämä ilmaisee tuotteen laajennetun tuen päättymispäivän.

Kun tukikäytäntö on **moderni**, sarake jää tyhjäksi.

### <a name="retirement-date"></a>Poistumispäivä
Kun tukikäytäntönä on **kiinteä** tai **komponentti**, tämä jää tyhjäksi.

Kun tukikäytäntönä on **moderni**, tähän tulee tuotteen poistumispäivämäärä.

### <a name="release-start-date"></a>Julkaisun alkamispäivä
Päivämäärä, jolloin julkaisun tuki on alkanut. Kun tuotteella on vain yksi julkaisu, tämä kenttä on tyhjä.
 
### <a name="release-end-date"></a>Julkaisun päättymispäivä
Kenttä ilmaisee julkaisun tuen päättymispäivämäärän.
Kun tuotteella on vain yksi julkaisu, tämä kenttä on tyhjä.

### <a name="docs-url"></a>Docs Url
Laajennetun dokumentaation URL-osoite.
