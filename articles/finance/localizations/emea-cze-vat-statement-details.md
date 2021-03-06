---
# required metadata

title: VAT statement for the Czech Republic
description: Set up and generate the VAT statement for users in legal entities located in the Czech Republic.
author: ShylaThompson
ms.date: 03/24/2022
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

ms.search.form: TaxAuthority, TaxReportCollection, TaxReportVoucher, TaxTable
# ROBOTS: 
audience: Application User
# ms.devlang: 
ms.reviewer: kfend
# ms.tgt_pltfrm: 
ms.custom: 263614
ms.search.region: Czech Republic
# ms.search.industry: 
ms.author: kfend
ms.search.validFrom: 2016-05-31
ms.dyn365.ops.version: AX 7.0.1

---

# VAT statement for the Czech Republic

[!include [banner](../includes/banner.md)]

  > [NOTE!]
  > This feature is deprecated. For more information, see [Removed and deprecated features](../get-started/removed-deprecated-features-finance.md#vat-declaration-cz-and-control-statement-export-cz-electronic-reporting-formats-for-czech-republic).
  > For more information about VAT declaration, see [VAT declaration (Czech Republic)](emea-cze-vat-declaration-tax-declaration-model.md)

Set up and generate the VAT statement for users in legal entities located in the Czech Republic.

This topic includes country-specific information about VAT statement setup for users in legal entities in the Czech Republic. For more information about general VAT reporting, see [VAT reporting for Europe](emea-vat-reporting.md).

## Set up sales tax authorities
To generate a VAT declaration in the required format for the specific tax authority, you must set up the report layout for the sales tax authorities.

- On the <strong>Sales tax authorities</strong> page, in the <strong>General</strong> section, set the <strong>Report layout **to **Default</strong>.
- Select the same **Sales tax authority** for the **Sales tax settlement period** that you will use for the sales tax codes.

## Set up sales tax reporting codes
The following is an example of how sales tax reporting codes could be set up for VAT statement generation.

### Example

For users in legal entities in the Czech Republic, according VAT declaration in 2016, the following sales tax reporting codes could be created.

|   Sales tax reporting code   |      Description                                        |
|------------------------------|---------------------------------------------------------|
| 2101                         | ??.210 - se z??kl. sazbou dan??  - Z??klad                  |
| 2102                         | ??.210 - se z??kl. sazbou dan??  - Da??                     |
| 2151                         | ??.215 - se sn????. sazbou dan??  - Z??klad                  |
| 2152                         | ??.215 - se sn????. sazbou dan??  - Da??                     |
| 2201                         | ??.220 - se z??kl. sazbou dan??  - Z??klad                  |
| 2202                         | ??.220 - se z??kl. sazbou dan??  - Da??                     |
| 2251                         | ??.225 - se sn????. sazbou dan??  - Z??klad                  |
| 2252                         | ??.225 - se sn????. sazbou dan??  - Da??                     |
| 2301                         | ??.230 - se z??kl. sazbou dan??  - Z??klad                  |
| 2302                         | ??.230 - se z??kl. sazbou dan??  - Da??                     |
| 2351                         | ??.235 - se sn????. sazbou dan?? ??? Z??klad                   |
| 2352                         | ??.235 - se sn????. sazbou dan?? ??? Da??                      |
| 2401                         | ??.240 - se z??kl. sazbou dan??  - Z??klad                  |
| 2402                         | ??.240 - se z??kl. sazbou dan??  - Da??                     |
| 2451                         | ??.245 - se sn????. sazbou dan??  - Z??klad                  |
| 2452                         | ??.245 - se sn????. sazbou dan??  - Da??                     |
| 2501                         | ??.250 - od osob reg. v jin??m ??l.st??t?? - Z??klad          |
| 2502                         | ??.250 - od osob reg. v jin??m ??l.st??t?? - Da??             |
| 2551                         | ??.255 - od osob nereg. v jin??m ??l.st??t?? - Z??klad        |
| 2552                         | ??.255 - od osob nereg. v jin??m ??l.st??t?? - Da??           |
| 2601                         | ??.260 - se z??kl. sazbou dan?? ??? Z??klad                   |
| 2602                         | ??.260 - se z??kl. sazbou dan?? ??? Da??                      |
| 2651                         | ??.265 - se sn????. sazbou dan?? ??? Z??klad                   |
| 2652                         | ??.265 - se sn????. sazbou dan?? - Da??                      |
| 2701                         | ??.270 - se z??kl. sazbou dan??  - Z??klad                  |
| 2702                         | ??.270 - se z??kl. sazbou dan??  - Da??                     |
| 2751                         | ??.275 - se sn????. sazbou dan??  - Z??klad                  |
| 2752                         | ??.275 - se sn????. sazbou dan??  - Da??                     |
| 3101                         | ??.310 - se z??kl. sazbou dan?? - Z??klad                   |
| 3102                         | ??.310 - se z??kl. sazbou dan?? - Da??, pln?? n??rok          |
| 3103                         | ??.310 - se z??kl. sazbou dan?? - Da??, kr??c. n??rok         |
| 3151                         | ??.315 - se sn????. sazbou dan?? - Z??klad                   |
| 3152                         | ??.315 - se sn????. sazbou dan?? - Da??, pln?? n??rok          |
| 3153                         | ??.315 - se sn????. sazbou dan?? - Da??, kr??c. n??rok         |
| 3201                         | ??.320 - se z??kl. sazbou dan??  - Z??klad                  |
| 3202                         | ??.320 - se z??kl. sazbou dan??  - Da??, pln?? n??rok         |
| 3203                         | ??.320 - se z??kl. sazbou dan??  - Da??, kr??c. n??rok        |
| 3251                         | ??.325 - se sn????. sazbou dan??  - Z??klad                  |
| 3252                         | ??.325 - se sn????. sazbou dan??  - Da??, pln?? n??rok         |
| 3253                         | ??.325 - se sn????. sazbou dan??  - Da??, kr??c. n??rok        |
| 3301                         | ??.330 - se z??kl. sazbou dan?? - Z??klad                   |
| 3302                         | ??.330 - se z??kl. sazbou dan?? - Da??, pln?? n??rok          |
| 3303                         | ??.330 - se z??kl. sazbou dan?? - Da??, kr??c. n??rok         |
| 3351                         | ??.335 - se sn????. sazbou dan??  - Z??klad                  |
| 3352                         | ??.335 - se sn????. sazbou dan??  - Da??, pln?? n??rok         |
| 3353                         | ??.335 - se sn????. sazbou dan??  - Da??, kr??c. n??rok        |
| 3401                         | ??.340 - se z??kl. sazbou dan?? - Z??klad                   |
| 3402                         | ??.340 - se z??kl. sazbou dan?? - Da??, pln?? n??rok          |
| 3403                         | ??.340 - se z??kl. sazbou dan?? - Da??, kr??c. n??rok         |
| 3451                         | ??.345 - se sn????. sazbou dan??  - Z??klad                  |
| 3452                         | ??.345 - se sn????. sazbou dan??  - Da??, pln?? n??rok         |
| 3453                         | ??.345 - se sn????. sazbou dan??  - Da??, kr??c. n??rok        |
| 3501                         | ??.350 - se z??kl. sazbou dan??  - Z??klad                  |
| 3502                         | ??.350 - se z??kl. sazbou dan??  - Da??, pln?? n??rok         |
| 3503                         | ??.350 - se z??kl. sazbou dan??  - Da??, kr??c. n??rok        |
| 3551                         | ??.355 - se sn????. sazbou dan??  - Z??klad                  |
| 3552                         | ??.355 - se sn????. sazbou dan??  - Da??, pln?? n??rok         |
| 3553                         | ??.355 - se sn????. sazbou dan??  - Da??, kr??c. n??rok        |
| 3601                         | ??.360 - od osob reg. v jin??m ??l.st??t?? - Z??klad          |
| 3602                         | ??.360 - od osob reg. v jin??m ??l.st??t?? - Da??             |
| 3603                         | ??.360 - od osob reg. v jin??m ??l.st??t?? - Da??, kr??c.      |
| 3651                         | ??.365 - od osob nereg. v jin??m ??l.st??t?? - Z??klad        |
| 3652                         | ??.365 - od osob nereg. v jin??m ??l.st??t?? - Da??           |
| 3653                         | ??.365 - od osob nereg. v jin??m ??l.st??t?? - Da??, kr.      |
| 3702                         | ??.370 - p??i zm??n?? re??imu  - Da??, pln?? n??rok             |
| 3703                         | ??.370 - p??i zm??n?? re??imu  - Da??, kr??c. n??rok            |
| 3803                         | ??.380 - celkov?? suma pro kr??cen?? n??roku na odpo??et dan?? |
| 3902                         | ??.390 - celkov?? suma pln??ho n??roku na odpo??et dan??      |
| 4102                         | ??.410 - dod??n?? zbo???? do jin??ho ??l.st??tu                 |
| 4202                         | ??.420 - dod??n?? nov??ho dopr.prost??. osob?? reg.           |
| 4252                         | ??.425 - dod??n?? nov??ho dopr. prost??. osob?? nereg.        |
| 4302                         | ??.430 - v??voz zbo???? (??66)                               |
| 4402                         | ??.440 - Ost.pln??n?? osv.od dan?? s n??rok. na odpo??et      |
| 5102                         | ??.510 - Celk. usk.pln??n?? s n??rokem na odpo??et dan??      |
| 5202                         | ??.520 - Uskut. pln??n??, kter?? se nezapo??. do koef.       |
| 5302                         | ??.530 - Celk. osv.usk.pln??n?? bez n??roku na odpo??et      |
| 5402                         | ??.540 - Usk.pln??n?? nezapo??. do v??po??tu koeficientu      |
| 5503                         | ??.550 - Vypo??t. pom??r.????st odp.dan?? (??76) - Koef.       |
| 5502                         | ??.550 - Vypo??t. pom??r.????st odp.dan?? (??76)               |
| 5603                         | ??.560 - Vypo??. odp. dan?? (??76 odst.7-10) - Koef.        |
| 5602                         | ??.560 - Vypo??. odp. dan?? (??76 odst.7-10)                |
| 5702                         | ??.570 - ??prava odpo??tu dan?? (??78)                       |
| 5802                         | ??.580 - Vyrovn??n?? odpo??tu dan?? (??79)                    |
| 6002                         | ??.600 - Vr??cen?? dan??                                    |
| 7102                         | ??.710 - Vypo????d??n?? dan?? na v??stupu (??91)                |
| 7302                         | ??.730 - Da?? na v??stupu                                  |
| 7502                         | ??.750 - Odpo??et dan??                                    |
| 7532                         | ??.753 - Vlastn?? da??ov?? povinnost                        |
| 7542                         | ??.754 - Nadm??rn?? odpo??et                                |
| 7802                         | ??.780 - Zm??na da??.povinnosti p??i pod??n?? dod. p??iz.      |
| 8101                         | ??.810 - Po????zen?? zbo???? prost??edn?? osobou                |
| 8151                         | ??.815 - Dod??n?? zbo???? prost??edn?? osobou                  |

## Configure the ER model and format for the report
You can use the **Electronic reporting** workspace to review or change the VAT statement configuration. Go to the **Configurations** page and select **VAT declaration model** from the list of models. This model is common for Austria, Czech Republic, Estonia, Finland, Latvia, and Lithuania and it aggregates tax data needed for VAT declaration. To review or change the VAT statement format for users in legal entities in the Czech Republic, select **VAT declaration (CZ)**, which is a child of **VAT declaration model** in the model tree. Select it and click **Designer** on the Action Pane to review or change the format. For more information, see [Electronic reporting.](../../fin-ops-core/dev-itpro/analytics/general-electronic-reporting.md)

## Generate the VAT statement
To generate a VAT XML file, open the **Sales tax payments** page, select vouchers, and then click **Export VAT XML file**.





[!INCLUDE[footer-include](../../includes/footer-banner.md)]
