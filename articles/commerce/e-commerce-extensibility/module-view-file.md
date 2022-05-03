---
# required metadata

title: Module view file
description: This topic covers the module view file in Microsoft Dynamics 365 Commerce. 
author: samjarawan
ms.date: 02/20/2020
ms.topic: article
ms.prod: 
ms.technology: 

# optional metadata

# ms.search.form: 
audience: Developer
# ms.devlang: 
ms.reviewer: v-chgri
# ms.tgt_pltfrm: 
ms.custom: 
ms.assetid: 
ms.search.region: Global
# ms.search.industry: 
ms.author: samjar
ms.search.validFrom: 2019-10-31
ms.dyn365.ops.version: Release 10.0.5
---

# Module view file

[!include [banner](../includes/banner.md)]

This topic covers the module view file in Microsoft Dynamics 365 Commerce.

A module view file is a TypeScript (.ts) file that controls a module's view. It's called from the module's React component. Additional module views can be provided in various themes to render a module differently, depending on the requirements of the theme.

## Example 

The following example shows the default module view file for a new module.

```typescript
import * as React from 'react';
import { IProductFeatureViewProps } from './product-feature';

export default (props: IProductFeatureViewProps) => {
    return (
        <div className='row'>
            <h2>Config Value: {props.config.showText}</h2>
            <h2>Resource Value: {props.resources.resourceKey}</h2>
        </div>
    );
};
```

## Additional resources

[Modules overview](modules-overview.md)

[Module definition file](module-definition-file.md)

[Module React component file](module-react-file.md)

[Module data file](module-data-file.md)

[Module mock file](module-mock-file.md)

[Module test file](module-test-file.md)

[Module props.autogenerated.ts file](module-props-autogenerated-ts-file.md)


[!INCLUDE[footer-include](../../includes/footer-banner.md)]