# Ihor Honcharuk Portfolio

Static HTML site for Cloudflare Pages.

## Structure
- `index.html`: homepage with professional positioning, experiences and contact links.
- `skills/*.html`: nine clickable skills area pages with anchors for every skill tag.
- `experience/nordea.html`: first detailed, employer-specific experience page.

## Publishing
Copy all files and folders to the root of the GitHub repository `ihorhoncharuk-portfolio` and commit to `main`. Cloudflare Pages uses no build command and `/` as output. **Do not upload only index.html:** otherwise links to skill and Nordea pages will return 404.

Details marked pending must be reviewed before they are promoted as professional accomplishments. Cloud platform experience is not claimed. CV PDF download is deliberately inactive until a publishable PDF is prepared.

## Resume download

The Contact section links to `assets/Ihor_Honcharuk_CV_EN.pdf`. Keep the `assets/` folder when deploying. Review the CV before publishing because it contains personal contact details and older employment information.


## Icons (v2.2)
Messenger icons in `assets/icons/` are Font Awesome Free 6.7.2 brand vector marks (CC BY 4.0 icons; attribution: Font Awesome, https://fontawesome.com). Brand names/logos are trademarks of their respective owners; no endorsement implied. The CV-document icon is custom artwork. Messenger/app links may behave differently by platform and account privacy settings.


Version 2.3: four About Me overview cards are accessible links to the matching detailed technical pages (Data platforms, Production operations, Infrastructure, Kubernetes operations).

## Version 2.4: Data Platforms
- `skills/data-platforms.html`: dedicated landing page linked from the Data platforms homepage card.
- `skills/etl-development.html`: detailed Informatica PowerCenter areas, plus DataStage reserved chapter.
- `skills/oracle-dwh-sql.html`: detailed Oracle DWH administration, SQL, Data Pump and SAP BusinessObjects chapter.
- Exact employer assignment for all newly supplied Informatica and Oracle DWH activities requires final confirmation.


## v2.5 — Production Operations

- Added `skills/production-operations.html`: detailed Nordea page containing Monitoring & Observability (ITRS Geneos, Splunk, Grafana, InfluxDB, Prometheus, AppDynamics), Disaster Recovery, Change Management, Incident Management, and Problem Management.
- Linked homepage Production operations card and monitoring skills to the new page.
- Old `skills/monitoring-reliability.html` directs visitors to the consolidated page.
- No changes to other employers’ detailed histories or the approved contacts.


## First Production Release
- Added `skills/infrastructure.html` with 8 agreed sections.
- Updated homepage Infrastructure card and Containerization & Kubernetes Operations heading.
- Fixed duplicate `<style>` opening tags on generated pages.
- All pages, icons and CV PDF must be uploaded together to repository root.
