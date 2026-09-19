# Onfinity — open source ERP and CRM in C#/.NET

**Formerly VIENNA Advantage.** Accounting, purchasing, sales and CRM, inventory and warehouse, projects, fixed assets and HR on one database, with a low-code Application Dictionary underneath: windows, fields, rules, workflows and reports are metadata, so a vertical built on Onfinity survives every upgrade. Runs on Windows Server (IIS) with PostgreSQL or Oracle; users work in the browser. Eclipse Public Licence.

## Where to start

| | |
|---|---|
| Run it | Packages for PostgreSQL and Oracle on [SourceForge](https://sourceforge.net/projects/erp-crm-advant/files/), or the [Docker deployment](https://github.com/VIENNA-Advantage-ERP-CRM/OnfinityContainer) |
| Read about it | [What is in the free edition](https://onfinity.io/open-source-erp.php) · [Brochures, one per module](https://onfinity.io/brochures.php) · [Release notes](https://viennaadvantage.atlassian.net/wiki/spaces/VA/pages/1769505/Release+Notes) |
| Build on it | [The ISV and partner programme](https://onfinity.io/isv-program.php) · [Development guide](https://viennaadvantage.atlassian.net/wiki/spaces/VA/pages/9207809/Development+Guide) |
| Get help | [Community portal](https://login.onfinity.io/register.aspx): manuals, videos, training and tickets, free registration |

## The repositories

| Repository | What it is |
|---|---|
| [Official-VABaseFiles](https://github.com/VIENNA-Advantage-ERP-CRM/Official-VABaseFiles) | Base and core libraries, generated model classes, the print engine. Build first. |
| [Official-VAFramework](https://github.com/VIENNA-Advantage-ERP-CRM/Official-VAFramework) | The framework: the Application Dictionary, workflows, the HTML5 client. |
| [Official-VAStandard-ERP-CRM](https://github.com/VIENNA-Advantage-ERP-CRM/Official-VAStandard-ERP-CRM) | The ERP and CRM application. |
| [OnfinityContainer](https://github.com/VIENNA-Advantage-ERP-CRM/OnfinityContainer) | Docker deployment: the application in a Windows container, PostgreSQL in a Linux one. |
| [official-VAFramework-ERP-CRM-4.X](https://github.com/VIENNA-Advantage-ERP-CRM/official-VAFramework-ERP-CRM-4.X) | The earlier 4.x single-solution repository, kept for reference. |
| `VA003_OrganizationStructure`, `VA005_ProductManagement`, `VA009_PaymentManagement`, `VA011_StockManagement`, `VA012_BankStatement`, `VA027_PostDatedCheque`, `VAPRC_AdvancePricing` | Add-on modules, each installed through the Onfinity Market. |

Bug reports and pull requests are welcome on the repository they concern. Every contribution is reviewed before it goes into a release.
