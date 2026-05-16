# Awesome Field Service Management [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of field service management (FSM), CMMS, and service business resources — software, integrations, APIs, reports, and communities.

Field service management (FSM) covers everything from job scheduling and dispatching to invoicing, parts tracking, and customer communication for businesses that send technicians into the field. This list focuses on **production-ready tools** with active maintenance, particularly highlighting the **Danish and Nordic** ecosystem where commercial FSM solutions are tightly integrated with local ERP and tax systems.

Maintained by [FieldService](https://fieldservice.dk) — a Danish FSM platform integrated with e-conomic, Uniconta, and Microsoft 365. We open source what we learn.

## Contents

- [Commercial Platforms](#commercial-platforms)
  - [Enterprise](#enterprise)
  - [Mid-market](#mid-market)
  - [SMB](#smb)
- [Danish & Nordic Platforms](#danish--nordic-platforms-)
- [Open Source FSM & CMMS](#open-source-fsm--cmms)
- [Integrations & APIs](#integrations--apis)
  - [ERP & Accounting](#erp--accounting)
  - [Maps & Routing](#maps--routing)
  - [Communication](#communication)
  - [Identity & Auth](#identity--auth)
- [Danish-specific APIs](#danish-specific-apis-)
- [Industry Reports & Statistics](#industry-reports--statistics)
- [Blogs & Newsletters](#blogs--newsletters)
- [Podcasts](#podcasts)
- [Books](#books)
- [Communities](#communities)
- [Tools for Service Businesses](#tools-for-service-businesses)
- [Related Lists](#related-lists)

## Commercial Platforms

### Enterprise

- [ServiceMax](https://servicemax.com) - Asset-centric FSM acquired by PTC, deep manufacturing/industrial focus.
- [Salesforce Field Service](https://www.salesforce.com/products/field-service/overview/) - Native module on Salesforce platform, strong for enterprise CRM-integrated workflows.
- [ServiceNow Field Service Management](https://www.servicenow.com/products/field-service-management.html) - ITSM-flavored FSM with strong automation and AI scheduling.
- [IFS Field Service Management](https://www.ifs.com/solutions/service-management) - Enterprise FSM with deep ERP integration, strong in oil & gas, telecom.
- [IBM Maximo](https://www.ibm.com/products/maximo) - Asset management leader with full FSM capabilities.
- [Oracle Field Service](https://www.oracle.com/cx/service/field-service/) - Predictive scheduling using machine learning, enterprise scale.
- [SAP Field Service Management](https://www.sap.com/products/crm/field-service-management.html) - Native integration with SAP S/4HANA.

### Mid-market

- [ServiceTitan](https://servicetitan.com) - HVAC, plumbing, electrical specialist with strong financial reporting.
- [Jobber](https://getjobber.com) - User-friendly FSM for SMB service businesses, strong onboarding.
- [Housecall Pro](https://www.housecallpro.com) - Home services focused (HVAC, plumbing, electrical, garage doors).
- [FieldEdge](https://fieldedge.com) - HVAC and plumbing-specific with QuickBooks integration.
- [WorkWave](https://www.workwave.com) - Route optimization-led FSM for last-mile services.
- [Simpro](https://www.simprogroup.com) - Trade services with strong job-costing.
- [FieldPulse](https://www.fieldpulse.com) - All-in-one for trade contractors.
- [mHelpDesk](https://www.mhelpdesk.com) - Quotes, scheduling, and invoicing for small contractors.
- [ServiceFusion](https://www.servicefusion.com) - GPS-tracked FSM with built-in time tracking.

### SMB

- [Connecteam](https://connecteam.com) - Workforce management with scheduling and time tracking, mobile-first.
- [Workiz](https://workiz.com) - Designed for field service SMBs (locksmiths, cleaning, junk removal).
- [Service Autopilot](https://www.serviceautopilot.com) - Lawn care and cleaning specialist.
- [Method:CRM](https://www.method.me) - QuickBooks-native FSM for small contractors.
- [Vonigo](https://www.vonigo.com) - Service business booking with strong multi-location support.
- [The Service Program](https://www.theserviceprogram.com) - Pest control, HVAC, lawn care for small operators.

## Danish & Nordic Platforms 🇩🇰

- [FieldService](https://fieldservice.dk) - Danish FSM with native e-conomic, Uniconta, and Microsoft 365 integration. Built for Danish service SMBs.
- [Apacta](https://apacta.com) - Construction-focused Danish FSM with strong project management.
- [Ordrestyring.dk](https://ordrestyring.dk) - Order-centric FSM for Danish trade businesses.
- [Hallerup](https://hallerup.net) - Service management with focus on Danish HVAC/plumbing.
- [Timegrip](https://timegrip.dk) - Danish time-tracking with GPS for field technicians.
- [BusinessWith](https://businesswith.dk) - Danish business management with service module.
- [Limetech](https://www.limetech.io) - Swedish CRM with service capabilities.
- [Visma Severa](https://www.visma.com/severa/) - Nordic professional services automation.

## Open Source FSM & CMMS

- [Snipe-IT](https://snipeitapp.com) - Open source IT asset management, often used alongside FSM for inventory.
- [GLPI](https://glpi-project.org) - IT service management with asset tracking, French-origin OSS.
- [OpenMAINT](https://www.openmaint.org) - Open source CMMS for asset and maintenance management.
- [iTop ITSM](https://www.itophub.io) - IT service management platform with FSM extensions.
- [Worklenz](https://worklenz.com) - Open core service work tracking.
- [Tracmor](https://www.tracmor.com) - Free asset and inventory tracking for small operators.

## Integrations & APIs

### ERP & Accounting

- [e-conomic API](https://restdocs.e-conomic.com) - Danish cloud accounting REST API, most used among Danish SMBs.
- [Uniconta API](https://www.uniconta.com/api/) - Danish ERP for mid-market, .NET-friendly API.
- [Dinero API](https://api.dinero.dk) - Lightweight Danish accounting for sole proprietors.
- [Billy API](https://www.billy.dk/api/) - Danish invoicing for freelancers and small businesses.
- [Microsoft Dynamics 365 Business Central](https://learn.microsoft.com/en-us/dynamics365/business-central/dev-itpro/api-reference/v2.0/) - Microsoft's ERP with full REST API.
- [Visma e-conomic](https://www.visma.com/products/) - Visma Group's accounting suite.
- [Microsoft Graph](https://learn.microsoft.com/en-us/graph/overview) - Unified API for Microsoft 365 data (calendar, mail, files, Teams).
- [QuickBooks Online API](https://developer.intuit.com/app/developer/qbo/docs/get-started) - North American accounting standard.
- [Xero API](https://developer.xero.com) - UK/AU/NZ accounting platform.

### Maps & Routing

- [Google Maps Platform](https://cloud.google.com/maps-platform) - Geocoding, routing, places, used by most commercial FSM.
- [Mapbox](https://www.mapbox.com) - Custom maps and routing with developer-friendly pricing.
- [HERE Technologies](https://www.here.com) - Strong in fleet and logistics routing.
- [OSRM (Open Source Routing Machine)](https://project-osrm.org) - High-performance open source routing.
- [OpenRouteService](https://openrouteservice.org) - Free routing API based on OpenStreetMap.
- [Valhalla](https://valhalla.github.io/valhalla/) - Open source routing engine used by Mapbox and Mapzen.

### Communication

- [Twilio](https://www.twilio.com) - SMS and voice notifications for technicians and customers.
- [SendGrid](https://sendgrid.com) - Transactional email for job confirmations and invoices.
- [Postmark](https://postmarkapp.com) - Reliable transactional email with strong delivery.
- [Pusher](https://pusher.com) - Real-time updates for dispatcher dashboards.
- [Vonage](https://www.vonage.com) - Voice and messaging APIs for customer notifications.

### Identity & Auth

- [Auth0](https://auth0.com) - SaaS authentication used by many FSM platforms.
- [MitID Erhverv](https://www.mitid-erhverv.dk) - Danish business identity verification.
- [NemLog-in](https://nemlog-in.dk) - Danish public sector single sign-on.
- [Clerk](https://clerk.com) - Modern authentication for SaaS apps.

## Danish-specific APIs 🇩🇰

- [DAWA - Danmarks Adressers Web API](https://dawa.aws.dk) - Official Danish address API, free, used for autocomplete and geocoding.
- [CVR API (virk.dk)](https://datacvr.virk.dk/data/cvr-help/cvr-api) - Danish company register, public business data.
- [Datafordeleren](https://datafordeler.dk) - Danish authoritative public data (BBR, geo, weather).
- [Statistik Banken](https://www.dst.dk/da/Statistik/statistikbanken) - Danmarks Statistik's open data warehouse.
- [Vejdirektoratet API](https://www.vejdirektoratet.dk/api) - Danish road and traffic data.
- [DMI Open Data](https://opendatadocs.dmi.govcloud.dk) - Danish meteorological forecasts and observations.
- [Skat.dk Erhverv](https://skat.dk/erhverv) - Danish tax authority business resources.

## Industry Reports & Statistics

- [The Service Council Annual Survey](https://www.theservicecouncil.com) - Most cited FSM industry benchmark, free executive summary.
- [Gartner Magic Quadrant for Field Service Management](https://www.gartner.com) - Annual vendor positioning for enterprise FSM.
- [Forrester Wave: Field Service Management](https://www.forrester.com) - Vendor analysis with deep capability breakdown.
- [Field Service News Reports](https://fieldservicenews.com/reports) - Free industry reports on trends and AI adoption.
- [Fortune Business Insights FSM Market](https://www.fortunebusinessinsights.com) - Market sizing and growth projections.
- [TSIA Field Services Benchmark](https://www.tsia.com) - Service performance benchmarking.

## Blogs & Newsletters

- [Field Service News](https://fieldservicenews.com) - Largest dedicated FSM publication.
- [The Service Council Blog](https://www.theservicecouncil.com/blog) - Industry thought leadership.
- [FieldServiceDigital](https://www.fieldservicedigital.com) - Technology-focused FSM coverage.
- [FieldService Blog](https://fieldservice.dk/blog) - Danish-language FSM trends and case studies.
- [Service Strategies](https://servicestrategies.com/blog/) - Service operations and customer success.
- [TSIA Blog](https://www.tsia.com/resources/blog) - Technology services industry research.

## Podcasts

- [Field Service Insider Podcast](https://fieldservicenews.com/podcast/) - Industry leaders interviewed weekly.
- [Smarter Services Podcast](https://www.theservicecouncil.com/podcast) - The Service Council's flagship show.
- [The Service Industry Success Podcast](https://serviceindustrysuccess.com/podcast/) - SMB-focused field service tips.
- [B2B Power Hour](https://www.b2bpowerhour.com) - B2B sales including field services.

## Books

- [Field Service Management for Dummies](https://www.dummies.com) - Approachable introduction for new FSM managers.
- [The Service Profit Chain](https://www.amazon.com/Service-Profit-Chain-Companies-Satisfaction/dp/0684832569) - Heskett, Sasser & Schlesinger — foundational service business economics.
- [Servicemanagement og marketing](https://www.saxo.com) - Danish-language service management textbook (Grönroos translation).
- [Strategic Service Management](https://www.amazon.com/Strategic-Service-Management-Christopher-Lovelock/dp/0136107214) - Lovelock & Wirtz — service strategy and operations.

## Communities

- [r/sysadmin](https://reddit.com/r/sysadmin) - 1M+ IT professionals discussing service management.
- [r/msp](https://reddit.com/r/msp) - 200k+ managed service providers.
- [r/HVAC](https://reddit.com/r/HVAC) - 400k+ HVAC technicians and contractors.
- [r/electricians](https://reddit.com/r/electricians) - 500k+ electrical trade professionals.
- [r/Plumbing](https://reddit.com/r/Plumbing) - Plumbing trade community.
- [r/smallbusiness](https://reddit.com/r/smallbusiness) - 1.7M+ small business owners.
- [r/iværksætteri](https://reddit.com/r/iværksætteri) - 55k+ Danish entrepreneurs.
- [Jobber Community](https://community.getjobber.com) - Jobber users discussing operations.
- [ServiceMax Community](https://community.servicemax.com) - Enterprise FSM peer discussion.

## Tools for Service Businesses

- [Calendly](https://calendly.com) - Customer-facing booking, often used as a lightweight scheduler add-on.
- [Cal.com](https://cal.com) - Open source booking platform.
- [Toggl Track](https://toggl.com/track/) - Lightweight time tracking when full FSM is overkill.
- [Loom](https://loom.com) - Video walkthroughs for remote troubleshooting and training.
- [SignWell](https://www.signwell.com) - E-signature for service agreements.

## Related Lists

- [awesome-saas](https://github.com/marcobiedermann/awesome-saas) - Software as a service resources.
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) - Self-hosted alternatives for business software.
- [awesome-foss-alternatives](https://github.com/sfermigier/awesome-foss-alternatives) - Free and open source SaaS alternatives.
- [awesome-search-engine-optimization](https://github.com/thospfuller/awesome-search-engine-optimization) - SEO resources useful for service businesses.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a pull request. The short version: production-ready tools with active maintenance only, follow the existing format, and submit alphabetically within sections.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [FieldService](https://fieldservice.dk) has waived all copyright and related or neighboring rights to this work.
