---
title: Elinkaaritietojen vienti
description: Tuotteen elinkaaren tietojen vieminen
ms.date: 01/06/2021
layout: ContentPage
ms.openlocfilehash: 4a27cd96ddaa1b3d128d9f1d711504d88c28e36e
ms.sourcegitcommit: f24c8653f7fd67e5b3f9f41e17b47edcecb5856e
ms.translationtype: HT
ms.contentlocale: fi-FI
ms.lasthandoff: 01/06/2021
ms.locfileid: "1367560"
---
# <a name="lifecycle-data-export"></a>Elinkaaritietojen vienti

## <a name="export-all-products"></a>Vie kaikki tuotteet
Vie kaikkien tuotteiden elinkaaritiedot napsauttamalla alla olevaa linkkiä:

> [!div class="nextstepaction"]
> [Vie kaikki tuotteet](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export)

## <a name="export-products-by-family-and-group"></a>Tuotteiden vieminen perheen ja ryhmän mukaan
Valitse perhe ja sitten vietävä ryhmä. Huomautus: Vienti alkaa, kun ryhmän arvo on valittuna. 

> [!div class="op_multi_selector" title1="Perhe" title2="Ryhmä"]
> - [(.NET | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET'))
> - [(.NET | .NET)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='.NET',group='.NET'))
> - [(Azure | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure'))
> - [(Azure | AI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='AI'))
> - [(Azure | Azure)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Azure'))
> - [(Azure | Tietokannat)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Databases'))
> - [(Azure | Muu)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Azure',group='Other'))
> - [(Dynamiikka | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics'))
> - [(Dynamics | Dynamics)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics'))
> - [(Dynamics | Dynamics 365)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20365'))
> - [(Dynamics | Dynamics AX)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20AX'))
> - [(Dynamics | Dynamics C5)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20C5'))
> - [(Dynamics | Dynamics CRM)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20CRM'))
> - [(Dynamics | Dynamics GP)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20GP'))
> - [(Dynamics | Dynamics NAV)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20NAV'))
> - [(Dynamics | Dynamics POS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20POS'))
> - [(Dynamics | Dynamics RMS)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20RMS'))
> - [(Dynamics | Dynamics SL)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Dynamics%20SL'))
> - [(Dynamics | Muu)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Dynamics',group='Other'))
> - [(Expression | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression'))
> - [(Expression | Expression)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Expression',group='Expression'))
> - [(Microsoft 365 | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365'))
> - [(Microsoft 365 | Enterprise Mobility + Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Enterprise%20Mobility%20%2B%20Security'))
> - [(Microsoft 365 | Identity Management)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20365',group='Identity%20Management'))
> - [(Microsoft Connected Services Framework | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework'))
> - [(Microsoft Connected Services Framework | Connected Services Framework)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Connected%20Services%20Framework',group='Connected%20Services%20Framework'))
> - [(Microsoft Customer Care Framework | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework'))
> - [(Microsoft Customer Care Framework | Customer Care Framework)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Customer%20Care%20Framework',group='Customer%20Care%20Framework'))
> - [(Microsoft Edge | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge'))
> - [(Microsoft Edge | Edge)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Edge',group='Edge'))
> - [(Microsoft Internet Explorer | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer'))
> - [(Microsoft Internet Explorer | Internet Explorer)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Internet%20Explorer',group='Internet%20Explorer'))
> - [(Microsoft Office | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office'))
> - [(Microsoft Office | Client)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Client'))
> - [(Microsoft Office | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Security'))
> - [(Microsoft Office | Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Office',group='Server'))
> - [(Microsoftin palvelimet | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers'))
> - [(Microsoftin palvelimet | BizTalk Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='BizTalk%20Server'))
> - [(Microsoftin palvelimet | Commerce Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Commerce%20Server'))
> - [(Microsoftin palvelimet | Content Management Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Content%20Management%20Server'))
> - [(Microsoftin palvelimet | Host Integration Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Host%20Integration%20Server'))
> - [(Microsoftin palvelimet | Intelligent Application Gateway)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Intelligent%20Application%20Gateway'))
> - [(Microsoftin palvelimet | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20Servers',group='Security'))
> - [(Microsoft System Center | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center'))
> - [(Microsoft System Center | System Center)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Microsoft%20System%20Center',group='System%20Center'))
> - [(Silverlight | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight'))
> - [(Silverlight | Silverlight)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Silverlight',group='Silverlight'))
> - [(SQL Server | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server'))
> - [(SQL Server | Power BI)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='Power%20BI'))
> - [(SQL Server | SQL Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='SQL%20Server',group='SQL%20Server'))
> - [(Visual Studio | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio'))
> - [(Visual Studio | Visual Studio)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Visual%20Studio',group='Visual%20Studio'))
> - [(Windows | Kaikki)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows'))
> - [(Windows | Client)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Client'))
> - [(Windows | IoT)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='IoT'))
> - [(Windows | Mobile)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Mobile'))
> - [(Windows | Security)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Security'))
> - [(Windows | Server)](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(family='Windows',group='Server'))

## <a name="export-products-by-end-of-support-date"></a>Vie tuotteet ennen tuen päättymispäivää
Valitse vuosi, kun haluat nähdä tuotteet, joiden tuki päättyy. Huomautus: Vienti alkaa, kun Vuosi-arvo on valittuna.

> [!div class="op_single_selector"]
> - [Seuraavat 12 kuukautta](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=12))
> - [Seuraavat 6 kuukautta](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportMonths=6))
> - [2016](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2016))
> - [2017](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2017))
> - [2018](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2018))
> - [2019](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2019))
> - [2020](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2020))
> - [2021](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2021))
> - [2022](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2022))
> - [2023](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2023))
> - [2024](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2024))
> - [2025](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2025))
> - [2026](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2026))
> - [2027](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2027))
> - [2028](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2028))
> - [2029](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2029))
> - [2030](https://app-omaha-prod.azurewebsites.net/api/PublishedListings/Export(endOfSupportYear=2030))
