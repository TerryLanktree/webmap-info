# Web Mapping Solutions currently available within the BC Government

## Problem Statement
People internal to government are not familiar with web mapping tools/services that are available/suitable to them -  IIT, GeoBC, and DataBC want to provide a consistent message about these tools and services.

## Summary of existing code or frameworks for Web Mapping currently in use within the Government of British Columbia

see [Detailed Capabilities Comparison](DetailedComparison.md) for more information 

|                                                                                                                                                       | Internet Mapping Framework 2                                                                                                                                                                                                                      | BC Map Hub                                                                                                                                                                                                                                                                                                                             | Simple Map Kit                                                                                                                                            | Common Web Mapping                                                                                                                                                                                                                                                                                                                               |
|---------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|                                                                                                                                                         | IMF2                                                                                                                                                                                                                                              | AGO                                                                                                                                                                                                                                                                                                                             | SMK                                                                                                                                                       | CWM                                                                                                                                                                                                                                                                                                                                              |
|                                                                                                                                                         |                                                                                                                                                                                                                                                   |                                                                                                                                                                                                                                                                                                                                        |                                                                                                                                                           |                                                                                                                                                                                                                                                                                                                                                  |
| Overview                                                                                                                                                |  [description](/docs/0003-DataBC-IMF2.md)                                                                                                                                                                             |  [description](/docs/0004-AGO-BCMapHub.md)                                                                     |  [description](/docs/0002-DataBC-SMK.md)                                         |  [description](/docs/0001-IIT-CWM.md)                                                                                                                                                                                            |
| Future Direction                                                                                                                                        | Platform Maturity - Minor UI Updates                                                                                                                                                                                   | Continued vigilance on data governance and content publication                                                                                                                                                                                                                                                    | Positioned as light weight points on a map replacement for DMF (An older government framework which uses the Google API). Community involvement, source code on GitHub. Optional support and hosting model from DataBC | Platform Maturity - Minor UI Updates                                                                                                                                                                                                                                                                                                                |
| Contact                                                                                                                            | DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                                                                                                                                |  DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                                                                                                                                                                                                                      |  DataBC Client Engagement - datamaps@gov.bc.ca                                                                                                               | Common Services Manager IITD                                                                                                                                                                                                                                                                                                                     |
| Architecture                                                                                                                                            | Custom BC Gov't Web services and tools on top of Geocortex Essentials/ArcGIS Server/BCGW                                                                                                                                                          | Licensed cloud based service running on elastic Amazon cloud                                                                                                                                                                                                                                                |  javascript libraries - deploy anywhere                                                                                                                            | Custom BC Gov't Framework on top of Geoserver and Open Layers 2                                                                                                                                                                                                                                                                        |
| Technology                                                                                                                                            |  .NET, IIS, HTML5 Viewer, ArcGIS rest services                                                                                                                                                         | Cloud based, HTML5 Viewers, ArcGIS rest services                                                                                                                                                                                                                                               | javascript, leaflet, arcgis javascript api, OGC WMS/WFS, ArcGIS Rest                                                                                                                           |  javascript, openlayers, OGC WMS/WFS, ISSS Platform (Liferay/Tomcat)                                                                                                                                                                                                                                                                        |
| Examples                                                                                                                                                | [iMapBC](https://maps.gov.bc.ca/ess/hm/imap4m) Consultative Area Database, Major Projects, ACDF, Traditional Use Studies,                                                                                                                                                                         | [BC Map Hub](https://governmentofbc.maps.arcgis.com/home/index.html) (BC's ArcGIS Online subscription), [EmergencyMapBC](https://governmentofbc.maps.arcgis.com/apps/webappviewer/index.html?id=950b4eec577a4dc5b298a61adab41c06)                                                                                                                                                                   | [Truck Route Planner](https://bcgov.github.io/smk-tlink/), [Assisted Living and Residential Care Locations](http://moh-qa.apps.gov.bc.ca/alrc/?)                                                                                                                      |[Natural Resource Online Services](https://portal.nrs.gov.bc.ca/web/client/explore), [Mineral Tenures Online](https://www.mtonline.gov.bc.ca/mtov/map/mto/cwm.jsp?site=mem_mto_min-view-title), [Integrated Land & Resource Registry (ILRR)](https://a100.gov.bc.ca/ext/ilrr/jsp/mapviewer/ilrr-mapviewer.jsp)                                                                                                                                                                                                                                                                                                                   |
