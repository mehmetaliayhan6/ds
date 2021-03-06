---
# required metadata

title: VAT statement details for Latvia
description: This topic explains how to set up the VAT statement for legal entities in Latvia.
author: ShylaThompson
ms.date: 06/20/2017
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
ms.custom: 266864
ms.search.region: Latvia
# ms.search.industry: 
ms.author: kfend
ms.search.validFrom: 2016-11-30
ms.dyn365.ops.version: Version 1611

---

# VAT statement details for Latvia

[!include [banner](../includes/banner.md)]

This topic explains how to set up the VAT statement for legal entities in Latvia.

This topic includes country/region-specific information about the setup of the value-added tax (VAT) statement for legal entities in Latvia only. For more information about the implementation of VAT statements, see [VAT reporting for Europe](emea-vat-reporting.md).

## Set up sales tax authorities
To generate a VAT declaration in the required format for the appropriate tax authority, you must set up the report layout for sales tax authorities. On the **Sales tax authorities** page, set the **Report layout** field to **Default**. Select the same sales tax authority for the sales tax settlement period that will be used for the sales tax codes.

## Set up sales tax reporting codes
Here is an example that shows how you might set up sales tax reporting codes on the **Report setup** FastTab of the **Sales tax codes** page to generate a VAT statement.

| Sales tax reporting code | Description (English)                                                                    | Description                                                                              | XML tag name |
|--------------------------|------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|--------------|
| 41                       | Standard rate tax amount                                                                 | Ar standartlikmi apliekamie dar??jumi                                                     | R41          |
| 411                      | Domestic transactions for which the recipient of the goods or services pays the tax      | Iek??zem?? veiktie dar??jumi, par kuriem nodokli maks?? pre??u vai pakalpojumu sa????m??js       | R411         |
| 42                       | Reduced rate tax amount                                                                  | Ar samazin??to likmi apliekamie dar??jumi                                                  | R42          |
| 45                       | Goods that are delivered to European Union (EU) member states                            | Uz ES dal??bvalst??m pieg??d??t??s preces                                                     | R45          |
| 46                       | Amount of custom sales in stock                                                          | ??rpuskopienas pre??u pieg??des muitas noliktav??s un br??vaj??s zon??s                         | R46          |
| 47                       | New vehicles delivered to EU countries                                                   | Uz ES dal??bvalst??m pieg??d??tie jaunie transportl??dzek??i                                   | R47          |
| 48                       | Provided services                                                                        | Par sniegtajiem pakalpojumiem                                                            | R48          |
| 481                      | Export goods                                                                             | Eksport??t??s preces                                                                       | R48\_1       |
| 482                      | The transactions other countries                                                         | Cit??s valst??s veiktie dar??jumi                                                           | R48\_2       |
| 49                       | Not taxable transactions                                                                 | Ar PVN neapliekamie dar??jumi                                                             | R49          |
| 50                       | Goods and services that are received from EU member states(standard rate)                | No ES dal??bvalst??m sa??emt??s preces un pakalpojumi (standartlikme)                        | R50          |
| 51                       | Goods and services that are received from EU member states (reduced rate)                | No ES dal??bvalst??m sa??emt??s preces (samazin??t?? likme)                                    | R51          |
| 54                       | Received services                                                                        | Par sa??emtajiem pakalpojumiem                                                            | R54          |
| 61                       | Imported goods for the company's economic activities                                     | Par import??taj??m prec??m                                                                  | R61          |
| 62                       | Domestic goods and services for the company's economic activities                        | Par prec??m un pakalpojumiem iek??zem??                                                     | R62          |
| 63                       | Calculated tax prepayment                                                                | Apr????in??t?? PVN summa saska???? ar likuma 92.panta pirm??s da??as 4.punktu (iz??emot 64.rindu) | R63          |
| 64                       | Calculated tax prepayment for goods and services that are received from EU member states | Apr????in??t?? PVN summa par prec??m un pakalpojumiem, kas sa??emti no ES dal??bvalst??m         | R64          |
| 65                       | The compensation paid to farmers                                                         | Lauksaimniekiem izmaks??t?? kompens??cija                                                   | R65          |
| 66                       | Not payable tax prepayment                                                               | PVN summa, kas nav atskait??ma k?? priek??nodoklis                                          | R66          |
| 67                       | Tax amount reduction calculated for previous tax periods                                 | Iepriek????jos taks??cijas periodos samaksai valsts bud??et?? apr????in??t?? nodok??a samazin??jums | R67          |
| 57                       | Calculated prepayment tax amount reduction for previous tax periods                      | Iepriek????jos taks??cijas periodos atskait??t?? priek??nodok??a samazin??jums                   | R57          |

## Configure the Electronic reporting model and format for the report
To review or change the VAT statement configuration, on the **Reporting configurations** page, select **VAT declaration model** in the list of models. Then click **Designer** to review or change the model. To review or change the VAT statement format, on the **Reporting configurations** page, select **VAT declaration (LV)**, and then click **Designer**.

## Generate a VAT statement
To generate a VAT XML file, on the **Sales tax payments** page, select one or more vouchers, and then click **Export VAT XML file**.





[!INCLUDE[footer-include](../../includes/footer-banner.md)]