# Payer_Services

This repository contains sample CPF merge files and sample JSON configuration files to help you deploy InterSystems Payer Services.

See the [product documentation](https://docs.intersystems.com/healthmodules/csp/docbook/DocBook.UI.Page.cls?KEY=PAGE_hsps) for details on how to deploy and use InterSystems Payer Services.  Access to this documentation requires an account. If you do not have one, please contact your InterSystems sales representative or complete the form on our [Contact Us](https://www.intersystems.com/contact-us/) page and we’ll be in touch.

A [solution overview](https://www.intersystems.com/products/healthshare/payer-services/) is available on the InterSystems website.

ePriorAuth (Electronic Prior Authorization) consists of: 
- Coverage Requirements Discovery (CRD) 
- Documentation Templates and Rules (DTR) 
- Prior Authorization Support (PAS)

The ePriorAuth subfolder is for sample merge.cpf files that combine the individual components' merge files, to provide an example of a merge file that should work for setting up all three together. The config.json files for each component module cannot be combined in this way as of ePA 1.0. 

| ePA version | CRD   | DTR   | PAS   |
| :---------- | :---- | :---- | :---- |
| 1.0         | 1.0.0 | 1.1.0 | 1.1.0 |