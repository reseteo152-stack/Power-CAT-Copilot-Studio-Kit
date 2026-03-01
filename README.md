# Power CAT Copilot Studio Kit

The **Power CAT Copilot Studio Kit** is a comprehensive set of capabilities designed to augment [Microsoft Copilot Studio](https://aka.ms/CopilotStudio). The kit helps makers develop, govern, and test custom agents, use a large language model to validate AI-generated content, optimize prompts, and track aggregated key performance indicators of their custom agents.

<img width="1879" height="1136" alt="new_landing_page" src="https://github.com/user-attachments/assets/e0dbbb47-d92b-489e-b517-a0b9cc336b81" />

# Features
## Testing capabilities  
Copilot Studio Kit allows makers to configure agents, tests and test sets, and use them to batch test their custom agents. Test runs produce detailed results including latencies, observed responses and run level aggregates. Different test types include response match, attachment match, topic match, multi-turn and generative answers which leverages AI Builder for response analysis. 

***Copilot Studio Kit test automation now supports user-defined rubrics for generative answers.***

More information on [testing capabilities](./TESTING_CAPABILITIES.md) 

## Compliance Hub
Compliance Hub helps organizations define and enforce governance policies for Copilot Studio agents at scale. It continuously evaluates agent configurations collected via Agent Inventory against configurable risk thresholds, automatically creating compliance cases when violations are detected and tracking them through an SLA-driven review lifecycle.

Administrators can configure thresholds, risk levels, SLA timers and enforcement actions (manual review, quarantine, delete), while makers are guided to remediate issues through Teams/Outlook notifications, intake forms, and dashboards showing open cases and compliance posture. This enables makers to innovate freely within Copilot Studio, while ensuring a consistent, auditable level of compliance across all agents.

More information on [Compliance Hub](./COMPLIANCE_HUB.md) 

## Rubrics refinement *(New!)*
Rubrics Refinement is a powerful capability in Copilot Studio Kit that enables you to create, test, and iteratively improve reusable evaluation standards (rubrics) for AI-generated responses. This feature helps ensure that AI grading of your agent's responses aligns with human judgment and organizational quality standards.

More information on [Rubrics Refinement](./RubricRefinement/01-rubrics-refinement-overview.md) 

## Conversation KPIs
Conversation KPIs are designed to help makers track and analyze the performance of their custom agents. This feature complements the existing analytics built-in the Copilot Studio and simplifies the process of understanding conversation outcomes by providing aggregated data in Dataverse rather than requiring you to analyze the complex conversation transcripts. 

More information on [conversation KPIs](./CONVERSATION_KPIS.md)

## SharePoint synchronization
SharePoint synchronization allows makers to configure periodical selective content synchronization from SharePoint locations to custom agent knowledge base as files.

More information on [SharePoint synchronization](./FILE_SYNCHRONIZATION.md)

## Prompt Advisor
Prompt Advisor allows makers to develop effective prompts while learning useful prompt engineering skills. Prompts entered in the advisor tool will be analyzed and receive a confidence evaluation with detailed reasoning for the score. Advisor also provides a list of suggested refined prompts implementing various prompt techniques. Makers can select from these optimized prompts to iteratively refine and improve their input.

More information on [Prompt Advisor](./PROMPT_ADVISOR.md)

## Webchat Playground
Webchat Playground simplifies customizing the appearance and behavior of the copilot agent webchat, including colors, fonts, thumbnails and initials. Easy to use UI allows makers to define the look and feel of their webchat, and HTML is generated with the specified styles. 

More information on [Webchat Playground](./WEBCHAT_PLAYGROUND.md)

## Adaptive Cards Gallery
Adaptive Cards Gallery provides makers with a dozen built-in adaptive card templates for different scenarios. They demonstrate the extensibility of the adaptive card visuals and behavior, and provide examples on the agent side implementation as well on things like dynamic data binding.

More information on [Adaptive Cards Gallery](./ADAPTIVE_CARDS_GALLERY.md)

## Agent Inventory
Agent Inventory provides administrators with a tenant-wide view to all Copilot Studio custom agents in their organization, including detailed information on the features they are using, authentication mode, knowledge sources, orchestration type and more. Agent Inventory ships with a dashboard and the data can be exported for use in other applications.

More information on [Agent Inventory](./AGENT_INVENTORY.md)

## Agent Review Tool
Agent Review Tool is a solution analysis tool that can be used to review your agents for any potential issues or anti-patterns that might have negative impact on the performance or the security of your agent. After analyzing the solution, Agent Review Tool presents the findings in easy to interpret format, with severity and details on how to address the issue.

More information on [Agent Review Tool](./AGENT_REVIEW_TOOL.md)

## Conversation Analyzer
Conversation Analyzer allows makers to analyze the conversations of their custom agents using custom prompts to get additional insights.

More information on [Conversation Analyzer](./CONVERSATION_ANALYZER.md)

## Agent Value Summary dashboard

The Agent Value Component is a modular tool for classifying agents in Microsoft Copilot Studio by type, behavior, and value, helping organizations understand their role, align them with strategy, and measure their impact. Results are presented visually on Agent Value dashboard.

More information on [Agent Value dashboard](./AGENT_VALUE_SUMMARY_DASHBOARD.md)

## Automated testing using Power Platform Pipelines (Advanced)

This feature allows users to automate the testing and deployment of Copilot Studio custom agents using Power Platform Pipelines. The goal is to ensure that agents are automatically validated through test runs before they are deployed to target environments (production). By integrating Power Automate flows with Dataverse and the Copilot Studio Kit, this approach introduces a quality gate into the deployment process. Only agents that pass the required amount of test cases are allowed to proceed, ensuring higher reliability and reducing manual intervention. This method supports continuous delivery practices and enhances the overall governance of the deployment lifecycle.

More information on [automated testing using Power Platform Pipelines](./AUTOMATED_TESTING.md)

# Setup instructions and documentation

There is a Setup Wizard in the Kit which allows easy editing of connection references and environment variables as well as turning on cloud flows. After deploying the Kit from either AppSource or GitHub, you may access the Setup Wizard from the Home-page of the Copilot Studio Kit. Please see additional information [here](./SETUP_WIZARD.md).

- [Prerequisites](./PREREQUISITES.md)
- [Installation instructions](./INSTALLATION_INSTRUCTIONS.md)
- [Configure users and teams](/SETUP_USERS_AND_TEAMS.md)
- [Configure agents](./CONFIGURE_COPILOTS.md)
- [Configure tests](./CONFIGURE_TESTS.md)
- [Run tests](./RUN_TESTS.md)
- [Analyze test results](./ANALYZE_TEST_RESULTS.md)
- [Troubleshooting](./TROUBLESHOOT.md)

Optionally
- [Enable user authentication support](./ENABLE-AUTHENTICATION.md)
- [Enable Application Insights support](./ENABLE-APPINSIGHTS.md)

For information on required licenses on Power Platform, and AI builder credits consumption, please see [Prerequisites](./PREREQUISITES.md)

# Known limitations

As of the latest release:
- Custom agent end user authentication support in test automation is limited Entra Id V2 with SSO.

## Latest release

The latest shipped version is available via **[Releases](https://github.com/microsoft/Powercat-Copilotstudio-Accelerator/releases)**. From there, you can download the latest version of all managed solutions that have been tested and are ready for use. 

Stay up to date with our releases by **subscribing** to them: 
1. Select **Watch**
2. Select **Custom** > **Releases** > **Apply** to receive notifications about our releases

# About this GitHub repo

The Power CAT Copilot Studio Kit GitHub Repo contains the source, releases, issues and backlog items of all components that are part of the Power CAT Copilot Studio Kit.

## Submit a feature request

Let us know by filing an issue. 
Before submitting your issue please search the [issues](https://github.com/microsoft/Powercat-Copilotstudio-Accelerator/issues) to ensure your issue has not already been reported

If your bug or feature request has already been reported, join the conversation by commenting and adding your reaction. Please use reactions to vote and not "+1" comments.
- 👍: upvote
- 👎: downvote

## Microsoft Open Source Code of Conduct

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).

Resources:

- [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/)
- [Microsoft Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/)
- Contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with questions or concerns

## Trademarks 

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft trademarks or logos is subject to and must follow [Microsoft’s Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general). Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship. Any use of third-party trademarks or logos are subject to those third-party’s policies.

## Security

Microsoft takes the security of our software products and services seriously, which includes all source code repositories managed through our GitHub organizations, which include [Microsoft](https://github.com/Microsoft), [Azure](https://github.com/Azure), [DotNet](https://github.com/dotnet), [AspNet](https://github.com/aspnet), [Xamarin](https://github.com/xamarin), and [our GitHub organizations](https://opensource.microsoft.com/).

If you believe you have found a security vulnerability in any Microsoft-owned repository that meets Microsoft's [Microsoft's definition of a security vulnerability](https://docs.microsoft.com/en-us/previous-versions/tn-archive/cc751383(v=technet.10)), please report it to us as described below.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, please report them to the Microsoft Security Response Center (MSRC) at [https://msrc.microsoft.com/create-report](https://msrc.microsoft.com/create-report).

If you prefer to submit without logging in, send email to [secure@microsoft.com](mailto:secure@microsoft.com).  If possible, encrypt your message with our PGP key; please download it from the the [Microsoft Security Response Center PGP Key page](https://www.microsoft.com/en-us/msrc/pgp-key-msrc).

You should receive a response within 24 hours. If for some reason you do not, please follow up via email to ensure we received your original message. Additional information can be found at [microsoft.com/msrc](https://www.microsoft.com/msrc).

Please include the requested information listed below (as much as you can provide) to help us better understand the nature and scope of the possible issue:

  * Type of issue (e.g. buffer overflow, SQL injection, cross-site scripting, etc.)
  * Full paths of source file(s) related to the manifestation of the issue
  * The location of the affected source code (tag/branch/commit or direct URL)
  * Any special configuration required to reproduce the issue
  * Step-by-step instructions to reproduce the issue
  * Proof-of-concept or exploit code (if possible)
  * Impact of the issue, including how an attacker might exploit the issue

This information will help us triage your report more quickly.

If you are reporting for a bug bounty, more complete reports can contribute to a higher bounty award. Please visit our [Microsoft Bug Bounty Program](https://microsoft.com/msrc/bounty) page for more details about our active programs.
GitHub Availability Report

Company news
GitHub Availability Report: February 2021
Introduction In February, we experienced no incidents resulting in service downtime to our core services. This month’s GitHub Availability Report will provide initial details around an incident from March 1…

Keith Ballinger · March 3, 2021

Company news
GitHub Availability Report: January 2021
Introduction In January, we experienced one incident resulting in significant impact and degraded state of availability for the GitHub Actions service. January 28 04:21 UTC (lasting 3 hours 53 minutes)…

Keith Ballinger · February 2, 2021

Company news
GitHub Availability Report: December 2020
In December, we experienced no incidents resulting in service downtime. This month’s GitHub Availability Report will provide a summary and follow-up details on how we addressed an incident mentioned in November’s report.

Keith Ballinger · January 6, 2021

Company news
GitHub Availability Report: November 2020
Introduction In November, we experienced two incidents resulting in significant impact and degraded state of availability for issues, pull requests, and GitHub Actions services. November 2 12:00 UTC (lasting 32…

Keith Ballinger · December 2, 2020

Company news
GitHub Availability Report: October 2020
In October, we experienced one incident resulting in significant impact and degraded state of availability for multiple services.

Keith Ballinger · November 4, 2020

Company news
GitHub Availability Report: September 2020
In September, we experienced one incident resulting in significant impact to the GitHub Pages service.

Keith Ballinger · October 7, 2020

Company news
GitHub Availability Report: August 2020
Introduction In August, we experienced no incidents resulting in service downtime. This month’s GitHub Availability Report will dive into updates to the GitHub Status Page and provide follow-up details on…

Keith Ballinger · September 2, 2020

Company news
GitHub Availability Report: July 2020
Last month we introduced GitHub’s monthly availability report to address service disruptions and share our learnings with the community.

Keith Ballinger · August 5, 2020

Company news
Introducing the GitHub Availability Report
What is the Availability Report? Historically, GitHub has published post-incident reviews for major incidents that impact service availability. Whether we’re sharing new investments to infrastructure or detailing site downtimes, our…

Keith Ballinger · July 8, 2020
Posts pagination
GitHub Availability Report

Company news
GitHub Availability Report: May 2022
In May, we experienced three distinct incidents resulting in significant impact to multiple services across GitHub.com. This report also sheds light into the billing incident that impacted Actions and Codespaces users in April.

Jakub Oleksy · June 1, 2022

Company news
GitHub Availability Report: April 2022
In April, we experienced three distinct incidents resulting in significant impact and degraded state of availability for Codespaces and GitHub Packages.

Jakub Oleksy · May 4, 2022

Company news
GitHub Availability Report: March 2022
In March, we experienced several incidents resulting in significant impact to multiple GitHub services.

Jakub Oleksy · April 6, 2022

Company news
GitHub Availability Report: February 2022
In February, we experienced one incident resulting in significant impact to multiple GitHub services.

Jakub Oleksy · March 2, 2022

Company news
GitHub Availability Report: January 2022
In January, we experienced no incidents resulting in service downtime to our core services.

Scott Sanders · February 2, 2022

Company news
GitHub Availability Report: December 2021
In December, we experienced no incidents resulting in service downtime to our core services.

Scott Sanders · January 5, 2022

Company news
GitHub Availability Report: November 2021
In November, we experienced one incident resulting in significant impact and degraded state of availability for multiple services.

Scott Sanders · December 1, 2021

Company news
GitHub Availability Report: October 2021
In October, we experienced one incident resulting in significant impact and degraded state of availability for the GitHub Codespaces service.

Scott Sanders · November 4, 2021

Company news
GitHub Availability Report: September 2021
In September, we experienced no incidents resulting in service downtime to our core services.

Scott Sanders · October 6, 2021

Company news
GitHub Availability Report: August 2021
In August, we experienced two distinct incidents resulting in significant impact and degraded state of availability for Git operations, API requests, webhooks, issues, pull requests, GitHub Pages, GitHub Packages, and GitHub Actions services.

Scott Sanders · September 1, 2021

Company news
GitHub Availability Report: July 2021
In July, GitHub experienced no incidents resulting in service downtime to our core services.

Keith Ballinger · August 4, 2021

Company news
GitHub Availability Report: June 2021
In June, we experienced no incidents resulting in service downtime to our core services.

Keith Ballinger · July 7, 2021

Company news
GitHub Availability Report: May 2021
In May, we experienced two incidents resulting in significant impact to multiple GitHub services.

Scott Sanders · June 2, 2021

Company news
GitHub Availability Report: April 2021
In April, we experienced two incidents resulting in significant impact and degraded state of availability for API requests and the GitHub Packages service, specifically the GitHub Packages Container registry service.…

Keith Ballinger · May 5, 2021
Octocats building the engineering blog
Company news
GitHub Availability Report: March 2021
In March, we experienced three incidents resulting in significant impact and degraded state of availability for issues, pull requests, webhooks, API requests, GitHub Pages, and GitHub Actions services. Follow up…

Keith Ballinger · April 7, 2021
Posts pagination
GitHub Availability Report

Company news
GitHub Availability Report: July 2023
In July, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · August 9, 2023
An illustration of two octocats repairing a robot.
Company news
GitHub Availability Report: June 2023
In June, we experienced two incidents that resulted in degraded performance across GitHub services.  June 7 16:11 UTC (lasting 2 hours 28 minutes) On June 7 at 16:11 UTC, GitHub…

Jakub Oleksy · July 12, 2023

Company news
GitHub Availability Report: May 2023
In May, we experienced four incidents that resulted in degraded performance across GitHub services. This report also sheds light into three April incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · June 14, 2023

Company news
Addressing GitHub’s recent availability issues
GitHub recently experienced several availability incidents, both long running and shorter duration. We have since mitigated these incidents and all systems are now operating normally. Read on for more details about what caused these incidents and what we’re doing to mitigate in the future.

Mike Hanley · May 16, 2023

Company news
GitHub Availability Report: April 2023
In April, we experienced four incidents that resulted in degraded performance across GitHub services. This report also sheds light into three March incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · May 3, 2023

Company news
GitHub Availability Report: March 2023
In March, we experienced six incidents that resulted in degraded performance across GitHub services. This report also sheds light into a February incident that resulted in degraded performance for GitHub Codespaces.

Jakub Oleksy · April 5, 2023

Company news
GitHub Availability Report: February 2023
In February, we experienced three incidents that resulted in degraded performance across GitHub services. This report also sheds light into a January incident that resulted in degraded performance for GitHub Packages and GitHub Pages and another January incident that impacted Git users.

Jakub Oleksy · March 1, 2023

Company news
GitHub Availability Report: January 2023
In January, we experienced two incidents, one that resulted in degraded performance for Packages and Pages and another that impacted Git users.

Jakub Oleksy · February 1, 2023

Company news
GitHub Availability Report: December 2022
In December, we did not experience any incidents that resulted in degraded performance across GitHub services. This report sheds light into an incident that impacted customers using GitHub Packages and GitHub Pages in November.

Jakub Oleksy · January 4, 2023

Company news
GitHub Availability Report: November 2022
In November, we experienced two incidents that resulted in degraded performance across GitHub services. This report also sheds light into an incident that impacted Codespaces in October.

Jakub Oleksy · December 7, 2022

Company news
GitHub Availability Report: October 2022
In October, we experienced four incidents that resulted in degraded performance across GitHub services. This report also sheds light into an incident that impacted Codespaces in September.

Jakub Oleksy · November 2, 2022

Company news
GitHub Availability Report: September 2022
In September, we experienced one incident that resulted in degraded performance across GitHub services. We also experienced one incident resulting in significant impact to Codespaces. We are still investigating that incident and will include it in next month’s report. This report also sheds light into an incident that impacted Codespaces in August and an incident that impacted Actions in August.

Jakub Oleksy · October 5, 2022

Company news
GitHub Availability Report: August 2022
In August, we experienced one incident resulting in significant impact to Codespaces. We’re still investigating that incident and will include it in next month’s report. This report also sheds light into an incident that impacted Codespaces in July.

Jakub Oleksy · September 7, 2022

Company news
GitHub Availability Report: July 2022
In July, we experienced one incident that resulted in degraded performance for Codespaces. This report also acknowledges two incidents that impacted multiple GitHub.com services in June.

Jakub Oleksy · August 3, 2022

Company news
GitHub Availability Report: June 2022
In June, we experienced four incidents resulting in significant impact to multiple GitHub.com services. This report also sheds light into an incident that impacted several GitHub.com services in May.

Jakub Oleksy · July 6, 2022
Posts pagination
GitHub Availability Report

Company news
GitHub Availability Report: October 2024
In October, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · November 14, 2024

Company news
GitHub Availability Report: September 2024
In September, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · October 10, 2024

Company news
GitHub Availability Report: August 2024
In August, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · September 11, 2024

Company news
GitHub Availability Report: July 2024
In July, we experienced four incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · August 14, 2024

Company news
GitHub Availability Report: June 2024
In June, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · July 12, 2024

Company news
GitHub Availability Report: May 2024
In May, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · June 12, 2024

Company news
GitHub Availability Report: April 2024
In April, we experienced four incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · May 10, 2024

Company news
GitHub Availability Report: March 2024
In March, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · April 10, 2024

Company news
GitHub Availability Report: February 2024
In February, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · March 13, 2024

Company news
GitHub Availability Report: January 2024
In January, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · February 14, 2024

Company news
GitHub Availability Report: December 2023
In December, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · January 17, 2024

Company news
GitHub Availability Report: November 2023
In November, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · December 13, 2023

Company news
GitHub Availability Report: October 2023
In October, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · November 13, 2023

Company news
GitHub Availability Report: September 2023
In September, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · October 11, 2023

Company news
GitHub Availability Report: August 2023
In August, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · September 13, 2023
Posts pagination
GitHub Availability Report

Company news
GitHub availability report: January 2026
In January, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · February 11, 2026

Company news
GitHub Availability Report: December 2025
In December, we experienced five incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · January 14, 2026

Company news
GitHub Availability Report: November 2025
In November, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · December 11, 2025

Company news
GitHub Availability Report: October 2025
In October, we experienced four incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · November 13, 2025

Company news
GitHub Availability Report: September 2025
In September, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · October 8, 2025

Company news
GitHub Availability Report: August 2025
In August, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · September 11, 2025

Company news
GitHub Availability Report: July 2025
In July, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · August 13, 2025

Company news
GitHub Availability Report: June 2025
In June, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · July 16, 2025

Company news
GitHub Availability Report: May 2025
In May, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · June 11, 2025

Company news
GitHub Availability Report: April 2025
In April, we experienced three incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · May 14, 2025

Company news
GitHub Availability Report: March 2025
In March, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · April 16, 2025

Company news
GitHub Availability Report: February 2025
In February, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · March 12, 2025

Company news
GitHub Availability Report: January 2025
In January, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · February 12, 2025

Company news
GitHub Availability Report: December 2024
In December, we experienced two incidents that resulted in degraded performance across GitHub services.

Jakub Oleksy · January 15, 2025

Company news
GitHub Availability Report: November 2024
In November, we experienced one incident that resulted in degraded performance across GitHub services.

Jakub Oleksy · December 13, 2024
Posts pagination
https://github.com/github/docs/issues/new/choosehttps://github.com/prettier/angular-html-parser.git
Configurar la transferencia a Dynamics 365 Customer Service
Integra con Microsoft 365 Copilot y Teams
Ampliar Microsoft 365 Copilot con agentes
Utiliza Copilot Tuning para afinar modelos para Microsoft 365 Copilot
Configurar el inicio de sesión único con Microsoft Entra ID para los agentes en Microsoft Teams
Contenido relacionado
Explora productos y servicios relacionados con Microsoft.

Power Platform
Recurso de aprendizaje único para aplicaciones y características de Power Platform, como la documentación de administración, conectores, desarrolladores e instrucciones.

Power Apps
Cree rápidamente aplicaciones con poco código que modernizan los procesos y resuelven los desafíos comerciales difíciles de su organización con Power Apps.

Power Automate
Cree flujos de trabajo automatizados entre sus aplicaciones y servicios favoritos para sincronizar archivos, obtener notificaciones, recopilar datos y mucho más.

Power BI
Convierta los orígenes de datos no relacionados en conocimientos coherentes, visualmente inmersivos e interactivos.

Power Pages
Diseñe, hospede y administre sitios web de empresas seguros, modernos y con poco código.

SDK de agentes de Microsoft 365
Compile agentes de compilación que se puedan implementar en los canales de su elección, con estructura para gestionar la comunicación necesaria.

Extensibilidad de Microsoft 365 Copilot
Personalice Microsoft 365 Copilot con agentes y use acciones y conectores para ampliar las aptitudes y conocimientos de Copilot.

Microsoft Agent 365
Infórmate sobre Microsoft Agent 365, una plataforma para gestionar agentes dentro de una organización.

Microsoft Agents Framework
Explora Microsoft Agents Framework, un kit de desarrollo de código abierto para construir agentes de IA y flujos de trabajo multiagente.

Microsoft Foundry para IA
Infórmate sobre Microsoft Foundry, una plataforma unificada de Azure como servicio para operaciones de IA empresarial, creadores de modelos y desarrollo de aplicaciones.

Centro de arquitectura de Power Platform y Copilot Studio
Examine las arquitecturas de referencia y las ideas de soluciones para Power Platform y Copilot Studio.

Dynamics 365
Descubra la próxima generación de aplicaciones CRM y ERP.

Microsoft Azure
Explore el conjunto cada vez mayor de servicios informáticos en la nube para ayudar a su organización a satisfacer sus desafíos empresariales.

Desarrolle sus aptitudes
Mejora tus conocimientos y habilidades en Copilot Studio con estos recursos.

Dominando Copilot Studio
Su guía de referencia para crear y personalizar agentes en Microsoft Copilot Studio.

Eventos para convertirte en agente en un día
Aprenda a crear agentes de inteligencia artificial de código bajo con Copilot Studio en un taller gratuito, práctico y dirigido por instructores.

Academia de Agentes de Copilot Studio
Domina el arte de construir agentes usando Copilot Studio. Mejora las habilidades de tu equipo con lecciones seleccionadas.

Centro de aprendizaje de Copilot
Descubra herramientas, orientación y soporte para la adopción, protección y administración de experiencias de Microsoft Copilot y personalizadas en su organización.

Centro de aprendizaje de IA
Desarrolle habilidades prácticas para liberar el potencial de la IA y prepárese para la innovación de la IA utilizando Microsoft Cloud.

Adopción de Copilot Studio
Consulte los recursos de adopción de Copilot Studio.

Escenarios de Copilot Studio
Explora escenarios del agente para iniciar tus proyectos con recursos descargables.

Copilot Studio Blog
Manténgase actualizado con el blog de Copilot Studio, el origen de las noticias del agente con tecnología de IA.