# Payer_Services

This repository contains sample CPF merge files and sample JSON configuration files to help you deploy InterSystems Payer Services.

See the [product documentation](https://docs.intersystems.com/healthmodules/csp/docbook/DocBook.UI.Page.cls?KEY=PAGE_hsps) for details on how to deploy and use InterSystems Payer Services.  Access to this documentation requires an account. If you do not have one, please contact your InterSystems sales representative or complete the form on our [Contact Us](https://www.intersystems.com/contact-us/) page and we’ll be in touch.

A [solution overview](https://www.intersystems.com/products/healthshare/payer-services/) is available on the InterSystems website.

The Electronic Prior Authorization (ePA) solution consists of: 
- Coverage Requirements Discovery (CRD) 
- Documentation Templates and Rules (DTR) 
- Prior Authorization Support (PAS)
- Payer Integration Framework (PIF)
- FHIR Storage Manager (FHIRStorage)

|Released | CRD   | DTR   | PAS   | PIF    | FHIRStorage |
| :------ | :---- | :---- | :---- |:------ | :---------- |
| 6/2025  | 1.0.0 | 1.1.0 | 1.1.0 | (none) | (none)      |
| 4/2026  | 2.1.0 | 2.0.0 | 2.0.0 | 1.0.0  | 1.0.0       |
| 9/2026  | 3.0.0 | 3.0.0 | 3.0.0 | 1.1.0  | 1.0.0       |

The Data Exchange solution includes the Payer Data Exchange (PDex), Member Match (PDexMM) and Attribution (ATR) components.

| Released | PDex  | PDexMM | ATR   |
| :------- | :---- | :----- | :---- |
| 8/2026   | 2.0.0 | 3.0.0  | 1.0.0 |

In all cases, IRIS mirroring can be enabled by completing and running the enable-mirroring.cpf merge file located in the top folder of this repo. 
