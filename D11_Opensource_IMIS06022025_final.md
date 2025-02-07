# IMIS Scaling Up Phase II
## Open-Source Base IMIS



**Table of Contents**

[**1.**	**Introduction** ](#_toc189741401)

[**2.**	**Evolution of IMIS**](#_toc189741402)

[**3.**	**Base IMIS V1.0.0**](#_toc189741403)

[*3.1*	*Functional Modules of Base IMIS*](#_toc189741404)

[*3.2*	*Roles and Permissions	18*](#_toc189741405)

[*3.3*	*IMIS Driven Sanitation Service Delivery Chain*](#_toc189741406)

[3.3.1	Entities in IMIS-driven sanitation service delivery model](#_toc189741407)

[3.3.2	Processes in IMIS-driven sanitation service delivery model](#_toc189741408)

[*3.4*	*Technical Stack*](#_toc189741409)

[**4.**	**IMIS Implementation Framework for New Cities**](#_toc189741410)

[**5.**	**Accessing IMIS**](#_toc189741411)

[*5.1*	*Organization Structure**](#_toc189741412)

[*5.2*	*Branch Structure**](#_toc189741413)

[*5.3*	*Version Management**](#_toc189741414)

[*5.4*	*Organization Maintenance**](#_toc189741415)

[**6.**	**License**](#_toc189741416)

[*6.1*	*License Text*](#_toc189741417)

[*6.2*	*Full License*](#_toc189741418)






# 1. <a name="_toc189741401"></a>**Introduction**
   <a name="_toc189741402"></a><p style='text-align: justify;'>The Integrated Municipal Information System (IMIS) is an open-source GIS-based Digital Public Infrastructure (DPI) that serves as both a municipal information system and a software solution. The IMIS is primarily designed to enhance city's sanitation system and services; however, it also has capability to assist city in managing and streamlining other urban services. Initially developed as a platform to help managing cities faecal sludge, IMIS has evolved into a robust system that supports in advancing Citywide Inclusive Sanitation (CWIS) and contributes in achieving Sustainable Development Goal (SDG) 6.2. It enables efficient municipal service delivery through real-time data tracking of sanitation service chain, centralized data aggregation, integrated spatial analysis tools, monitoring KPIs and served as a sub-national public data system to manage sanitation data and monitor city's CWIS indicators.</p>

# 2. **Evolution of IMIS**
   The development of IMIS has undergone multiple phases of growth, expanding from its initial scope into a more comprehensive tool.

   **2016-2017:** 

- <p style='text-align:justify'>SNV Bangladesh, under BMGF funded CWIS project, established GIS-based Database of Khulna and Jhenaida in Bangladesh with complete database of sanitation system to support Faecal Sludge Management (FSM) service with the technical support of Innovative Solution Pvt. Ltd. (ISPL). The survey and GIS data preparation work was supported by Khulna University.</p>

**2018-2019:** 

- <p style='text-align:justify'>IMIS was conceptualized as part of the GIS-based FSM Information System development activity of SNV Bangladesh, with ISPL leading the overall project process, including conceptualization, system architecture design, and technical development. The architecture of IMIS was inherited from ISPL's expertise and prior experience in designing and developing GIS-based Municipal Information System (GMIS) under the ADB-funded SMUSDP project in Nepal. IMIS was developed and implemented in SNV's two project towns in Jhenaida and Khulna.</p>

**2020-2021:** 

- <p style='text-align:justify'>IMIS was further customized and scaled up across multiple municipalities in Bangladesh by SNV, with the technical support of the local company Streamtech Ltd (STL). ISPL transferred its knowledge and technology to STL, which then engaged in replicating and ensuring the system's smooth operation.</p>

**2021-2022:**

- <p style='text-align:justify'>IMIS was completely redesigned, restructured, and redeveloped from scratch by ISPL, incorporating capabilities to support the CWIS approach in the overall planning, management, and monitoring & evaluation of sanitation systems and services.</p> 
- <p style='text-align:justify'>The new ISPL version IMIS was implemented in Mahalaxmi Municipality, Nepal, to support ENPHO in implementing ISO 24521.</p>

**2023:** 

- <p style='text-align:justify'>GWSC-AIT, in collaboration with ISPL, initiated the scaling up of IMIS as a public data system for local governments, including the development of a standardized Base IMIS streamlining CWIS approach. Lakxmipur Paurashova in Bangladesh and Birendranagar Municipality in Nepal were selected as pilot towns for implementation.</p>
- <p style='text-align:justify'>A new milestone was achieved with the integration of IMIS and the Electronic Building Permit System (eBPS) in Mahalaxmi Municipality. This integration allows the city to update newly constructed buildings and containment structures in the IMIS building and containment database while ensuring the construction of standard septic tanks.
</p>

**2024:** 

- <p style='text-align:justify'>Open-source Base IMIS was developed with built in major 22 CWIS indicators and many additional tools for urban management decision support system. ISPL version IMIS developed in 2021-2022 was taken as the foundation for developing the standard Base IMIS (version 1.0.0)</p>
- <p style='text-align:justify'> An extensive technical training by ISPL in collaboration with GWSC-AIT and ITNBUET was conducted to capacitate local IT companies in Bangladesh to customize and deployment of Base IMIS for localizing and scaling up IMIS in Bangladesh and the region.</p>

**2025:** 

- <p style='text-align:justify'>As a significant milestone in the development of IMIS, the open-source Base IMIS (version 1.0.0) has been released to the public as a Digital Public Infrastructure (DPI) under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license. It can be downloaded, customized, and used freely.<p style='text-align:justify'>

# 3. <a name="_toc189741403"></a>**Base IMIS V1.0.0**
   <p style='text-align:justify'>Base IMIS is the foundation of the IMIS platform, structured to provide a scalable, open-source, and interoperable solution for local authorities. It typically includes the core features and functionalities of IMIS, which can then be further customized or expanded based on specific municipal needs for their municipal governance and efficient sanitation service delivery. Base IMIS, the open-source GIS-based Digital Public Infrastructure (DPI), functions as both a municipal information system and a software solution, integrating data, processes, and services to enhance municipal governance—particularly in sanitation management in CWIS approach to achieve SDG 6.2. The Base IMIS serves as the foundation offering core features and functionalities that can be customized or expanded to meet the specific needs of municipalities.</p>

   <p style='text-align:justify'>Base IMIS offers municipalities data-driven decision-making tools to strengthen governance across various sectors. By leveraging open-source technologies and Geographic Information Systems (GIS), it facilitates:</p>

- Planning, management, and monitoring of sanitation systems using the CWIS approach.
- End-to-end FSM (Faecal Sludge Management) service chain oversight, including real-time data tracking.
- Generation and visualization of CWIS indicators for performance assessment.
- Intuitive dashboards for tracking CWIS indicators, Key Performance Indicators (KPIs), and other essential municipal governance metrics.

<p style='text-align:justify'>As a sub-national public data system, Base IMIS contributes to national-level monitoring by feeding data into centralized systems, supporting Citywide Inclusive Sanitation (CWIS) indicators and other critical metrics for achieving sanitation targets.</p>

<p style='text-align:justify'>Beyond sanitation management, with its modular and scalable design, Base IMIS empowers local authorities by providing a unified, data-driven framework that enhances efficiency, accountability, and service delivery in municipal governance.</p>

|<p>![](cwis.png)</p><p><a name="_ref189688225"></a>*Figure 1 Planning, Management and Monitoring & Evaluation Framework for implementing CWIS Approach*</p>|
| - |
|<p style='text-align:justify'> IMIS supports the Planning, Management, and Monitoring & Evaluation (M&E) framework for CWIS systems and services (see [Figure 1](#_ref189688225)). This framework emphasizes a structured approach to achieving inclusive and sustainable sanitation outcomes. The Planning component focuses on equitable and gender-inclusive strategies, sustainable financing, and transparent pricing mechanisms. The Management component ensures the safe, accountable, and financially sustainable operation of sanitation systems. The M&E component assesses service quality, equitable distribution, and the performance of sanitation authorities. Together, these components create a continuous feedback loop that helps municipalities refine their strategies and align them with national sanitation goals.</p>
| 


## 3.1 <a name="_toc189741404"></a>Functional Modules of Base IMIS

   <p style='text-align:justify'>Base IMIS comprises of ten functional modules ([Figure 2](#_ref189688233)), seven of which are core modules to manage sanitation systems and services in CWIS approach, whereas remaining three value-added modules enhance complementary municipal services, including property tax collection, solid waste management, and water supply billing. Combined with the <b>Urban Management Decision Support System (UMDSS)</b>—a powerful tool for spatial analysis, mapping, and decision-making—IMIS empowers municipalities to adopt CWIS principles while contributing to broader urban governance.</p>

   The seven core modules include:

- Building Information Management System (BIMS)
- Utility Information Management System (UIMS)
- Faecal Sludge Information Management System (FSIMS)
- Community/Public Toilet Information Management System (CTPIMS)
- Sewer Connection Information Management System (SCIMS)
- Public Health Information Support System (PHISS)
- Urban Management Decision Support System (UMDSS)

The three value-added modules are:

- Property Tax Collection Information Support System (PTCISS)
- Solid Waste Information Support System (SWISS)
- Water Supply Information Support System (WSISS)

<p style='text-align:justify'>Data required for six out of seven core modules (excluding Urban Management Decision Support System) such as buildings, containments, roads, etc. have to be created prior to the implementation of IMIS and migrated in the system. Such data needs to be updated in the IMIS as changes occur, e.g. new buildings constructed in the city after its implementation needs to be updated in the system by the responsible department such as building permit department. If any changes have occurred in the attribute information of the geographical features, they also need to be updated. Service data like the data to be captured in the process of containment emptying, service providers information, etc. will be maintained after implementation of IMIS. The data maintained by the six data models have a direct impact in sanitation related analysis and CWIS indicators. </p>

<p style='text-align:justify'>The value-added modules primarily support property tax collection, solid waste management, and water supply billing units, utilizing IMIS as a digital infrastructure to enhance services and improve revenue collection processes. Unlike the core modules, these value-added modules rely on data imported from respective municipal departments and units which are created during their regular business processes, as IMIS does not create data for them. There is no direct impact of these data in analyzing sanitation related data and analyzing Citywide Inclusive Sanitation (CWIS) approach. Refer <a href="https://github.com/base-imis/additional_resources/blob/master/GIS%20Data%20Creation%20Resource%20Materials/Resource%20Materials%20-%20GIS%20Data%20Creation.pdf"> GIS Data Creation Material </a> to know more about GIS data creation work and the <a href='https://github.com/base-imis/web_app/blob/master/documentations/data_dictionary/data_dictionary.md'> Data Dictionary </a> know more about the types of data required to be maintained in IMIS. </p>

<p style='text-align:justify'>UMDSS out of seven core IMIS modules do not create data itself, it consolidates data from other modules to facilitate decision-making related to sanitation systems, services, and broader urban management issues through its various analytical tools. Access to these modules is determined by the functional roles of municipal staff, executives, and stakeholders, ensuring their integration into daily municipal operations for effective management.</p>

<p style='text-align:justify'>The use of these modules must be embedded into the regular workflows of corresponding departments or units within the municipality. For instance, the FSTP operator, responsible for recording logs of feacal sludge disposed of at the FSTP, is required to use the "Sludge Collection" functional sub-module within FSIMS. Similarly, emptying operators must use the IMIS-provided mobile application to capture data during containment emptying processes under the relevant sub-modules. This integration ensures that information within IMIS is continuously updated without the need for additional resources dedicated solely to data entry.</p>

<p style='text-align:justify'>Each of these ten functional modules is discussed in detail in subsequent sections of this chapter. Additionally, IMIS includes a dedicated Settings module, which focuses on system administration and is covered at the end of the chapter. This structured approach ensures that IMIS is seamlessly integrated into the municipality's operational framework, supporting both sanitation and urban management.</p>

|<p>![](functional_module_of_imis.png)</p> <p>
<a name="_ref189688233"></a>*Figure 2 Functional Modules of IMIS*</p> 



## 1. **Building Information Management System (BIMS)**

<p style='text-align:justify'>The BIMS is a core module of the IMIS that serves as a comprehensive database of all buildings within a municipality. It encompasses detailed information about each building, including: Physical attributes (structure type, number of floors, and year of construction); Location details (address and geographical coordinates with building footprints; Usage and ownership (Building usage, ownership status, and associated tax codes); Utilities and services (sources of water, solid waste management services, access to sanitation, access to roads, etc); Demographics and classifications (basic demographic data and classifications for low-income community areas). Buildings are central to IMIS, functioning as the foundational entities that interconnect all other components essential for efficient municipal service delivery.</p>

<p style='text-align:justify'>The building database in IMIS is established using a GIS framework. High-resolution satellite or drone imagery is used to digitize building footprints, which are then verified through field checks and house-to-house surveys. House-to-house survey also collects all other required attributes data about buildings. </p>

<p style='text-align:justify'>New buildings constructed post-IMIS implementation are recorded through the IMIS mobile application during the building permit process and updated for new constructions. The app, currently available for Android, captures building footprints and related data for new structures. Additional building attributes are updated during municipality's business process in delivering various services such as sanitation assessments, sanitation service delivery and other services. However, this need to be incorporated in municipality's service delivery policy. </p>

<p style='text-align:justify'>BIMS provides interactive dashboard dedicated for building related information. This dashboard provides visual insights into building data from multiple perspectives. BIMS provides comprehensive interfaces and tools for data entry, updates, queries, and analysis. The system has map-based integration feature that provides geospatial visualization tools for location identification. The module has data extraction tools that has capability for generating data in various formats, including CSV, Shapefiles, and KML files.</p>

<p style='text-align:justify'>BIMS offers municipalities valuable insights into Building infrastructure status, utility and service access and the critical data for planning, management and monitoring and evaluation of sanitation system and services in CWIS approach.</p>

<p style='text-align:justify'>The data maintained by BIMS helps municipality to monitor the CWIS indicators such as (i) Ratio of LIC access to population access, (ii) Population with access to safe individual toilets, and (iii) Low income community (LIC) population with access to safe individual toilets.</p>

## 2. **Utility Information Management System (UIMS)**
<p style='text-align:justify'> <b>UIMS</b>, a core module of the <b>IMIS</b> is designed to manage detailed spatial and attribute data for municipal utilities such as roads, stormwater drains, water supply networks, and sewer systems. UIMS plays a critical role in achieving <b>CWIS</b> by enabling municipalities to monitor sanitation infrastructure, identify service gaps, and ensure equitable access to sanitation services, particularly for low-income community (LIC) areas. Through its integration with the <b>BIMS</b>, UIMS provides granular insights into utility connectivity for each building, including sewer and drainage links, and water supply access. This integration helps municipalities target underserved areas, plan infrastructure expansions, and prioritize investments in sanitation services.</p>

<p style='text-align:justify'>A key feature of UIMS is its interactive dashboard, which delivers real-time visualizations on sanitation-related utilities. The system empowers municipalities to monitor sanitation coverage trends, identify gaps, and make data-driven decisions to address inequities in service delivery. UIMS also includes advanced map-based input tools integrated with the **UMDSS**, allowing municipalities to add or update utility infrastructure directly within the platform. Currently this tool is available for creating and updating road only. In case of other utilities, they need to be digitized and merged with existing data and import in corresponding utilities database of IMIS with the help of skilled GIS people. In case of attribute data, they can be updated for all kind of utilities directly from the user interface. UMDSS has provided tools to export data in flexible formats, such as CSV, SHP, and KML ensuring seamless sharing and integration with other municipal services.</p>

## 3. **Faecal Sludge Information Management System (FSIMS)**

<p style='text-align:justify'>The FSIMS is another core and most important module CWIS. This module enables municipality to digitalize and manage all data related to sanitation systems and services. FSIMS digitalize the complete sanitation service chain from application request for emptying service to the safe disposal of faecal sludge at the treatment plant and the reuse of the treated waste.</p>

<p style='text-align:justify'>The FSIMS is further categorized into five sub-modules:</p> 

<p style='text-align:justify'> a. FSM Dashboard (FSMD): The FSMD provides information related FSM services, overall, from containment emptying to transfer and disposal of waste in the FSTP. FSMD provides information about the number of containments; service providers; resources used for service delivery; applications received and responded; containments emptying status, volume of sludge collected, emptied and disposed; and the revenue generated, </p> 



<p style='text-align:justify'>b Containment Information Management System (CIMS): The CIMS maintains the information about the containments in the city, with their location information and attribute information such as building identification number (in case of multiple building served one containment, BIN of main building responsible for taking care of the containment), sanitation system type, dimensions, volume, last emptying date, next emptying date, etc. If a building is connected to a sewer network, that information is maintained in the building database. However, this module does not include a separate feature for adding new containments, if new containment must be added, it has to be updated in corresponding building in building database, through BIMS. A containment may be shared by multiple buildings or vice versa.</p>

<p style='text-align:justify'>c. Service Provider Information Management System (SPIMS): The SPIMS maintains the information related to the sanitation service providers registered with the city that provide emptying services within the city. This information is maintained by municipal authority whereas, two other functionalities employee information and desludging vehicles for service provider to maintain their information about their employees and the desludging vehicles. Only those service providers, employee and vehicles registered in this system are eligible to provide emptying, transporting and disposing faecal sludge in the FSTP or area designated by the municipality. These information help municipality and service provider for efficient management of the resources and efficient service delivery. The information provided by SPIMS also helps monitoring KPIs set by municipality for service provider and tracking emptying vehicle to ensure that the waste emptied from the containment is transported and disposed in the area designated for disposing waste or FSTP allocated by the municipality.</p>

<p style='text-align:justify'>d. Treatment Plant Information Management System (TPIMS): The TPIMS maintains the information related to the treatment plants that could be FSTP, Centralized Wastewater Treatment Plant, Decentralized Waste Water Treatment Plant or Co-treatment Plant, those used by the city to dispose and treat collected faecal sludge or waste water. In addition to this, this sub-module also maintains water sample test data with the standard parameters used for monitoring the performance of the treatment plants in the city. </p>

<p style='text-align:justify'>The information maintained by TPIMS along the information maintained by BIMS and the ESIMS, helps municipal to monitor the CWIS indicators such as (i) FS treatment capacity as a % of total FS generated from non-sewered connections, (ii) FS treatment capacity as a % of volume disposed at the treatment plant, (iii) WW treatment capacity as a % of total WW generated from sewered connections and greywater and supernatant generated from non-sewered connections, and (iv) Effectiveness of FS treatment in meeting prescribed standards for effluent discharge.</p>

<p style='text-align:justify'>e. Emptying Service Information Management System (ESIMS): The Emptying Service IMS digitalizes the sanitation service chain and enables the city to manage the entire sanitation service chain, starting from application requests for emptying service from the customer to the safe disposal of feacal sludge at the treatment plant. All the activities involved in this process can be monitored in real-time through ESIMS. The module is divided into four categories according to the different stages of the sanitation service chain i.e. application, emptying, sludge collection and feedback. The complete service chain is managed and maintained through the application section; however, the individual sections maintain further detailed information. There are several functional modules under this sub-module: 

- <p style='text-align:justify'>Application – this functional module is accessible to helpdesk and FSTP operator. The helpdesk use it for receiving and maintaining application for customer's emptying request and collecting and maintain feedback data. FSTP operator use it for updating sludge transferred from the emptied containment and disposed in the FSTP. There is a function to generate report of emptying service under this functional module. Helpdesks generally are the part of the municipality's sanitation department, emptier are part of the service providers and FSTP operators can be part of the municipality or the private operator as of municipality's policy.</p>

- <p style='text-align:justify'> Emptying – there is an easy-to-use native mobile application (android) that allows collection of the emptying information while providing the emptying service, such information can be updated in real-time. The mobile application is used by emptier to collect the information such as emptying start and end time, number of trips, total cost for emptying, and the payment receipt number. Emptying details can be viewed in real-time by help desk and other municipal staff who has access to this module.</p>

- <p style='text-align:justify'>Sludge collection – FSTP operator in FSTP updates the FS disposal record that includes date, time and volume of waste disposed in the FSTP through the functional module Application through the web app as the waste is transferred and disposed in FSTP. Help desk can view these records in real-time through this functional module.</p>

- Feedback – this functional module is accessible to the helpdesk, after completing sanitation service chain from emptying to disposal of the waste in the FSTP. 
- Help desks – this functional module is used to create help desk and update their information. Help desk generally are under municipality itself, but the system has capability of managing multiple help desks.</p>

<p style='text-align:justify'>Data maintained by FSIMS along with the building data and LIC data enables CWIS Information Management System to generate CWIS indicators such as (i) IHHL onsite sanitation system that have been desludged, (ii) Collected FS disposed at the treatment plant or designated disposal site, (iii) Low income onsite sanitation systems that have been desludged, (iv) FS collected from LIC that is disposed at treatment plant or designated area, (v) Educational institutions where FS generated is safely transported to TP or safely disposed in situ, (vi) Healthcare facilities where FS generated is safely transported to TP or safely disposed in situ, and (vii) Desludging services completed mechanically or semi-mechanically.</p>

<p style='text-align:justify'>The data export tools under FSIMS allow users to export data in CSV, Shape and KML format where applicable.</p>

## 4. **Community Toilet / Public Toilet Information Management System (PTCTIMS)**

<p style='text-align:justify'>The PTCTIMIS is another core module of the system that maintains the information about the Public Toilets (PT) and Community Toilets (CT) in the city. The module enables municipal authority to maintain geographic locations of the PTs and the CTs in the city with their capacities and facilities along with daily user logs in case of PTs. In case of CTs, PTCTIMS maintains the number of households and the population served by CTs, based on the household and population data maintained by building database in the system. Data export feature of the module enables users to export data PT/CT data in CSV format. Mapping features of UMDSS with this data enables municipal authorities to map the locations of the PTs/CTs with their operational condition and it has also provided a tool to map the buildings which are served by a specific CT.</p>

<p style='text-align:justify'>CT information along with building information maintained by PTCTIMS helps monitoring four major CWIS indicators (i) Dependent population with access to safe shared facilities, (ii) Shared facilities that adhere to principles of universal design, (iii) Shared facility users who are women, and (iv) Average distance from household to shared facility. Similarly, PT information along with containment emptying data enables municipal authority to monitor CWIS indicators (i) PT where feacal sludge generated is safely transported to treatment plant or safely disposed in situ, (ii) PT that adhere to principles of universal design, and (iii) PT users who are women.</p>

## 5. **Sewer Connection Information Support System (SCISS)**

<p style='text-align:justify'>The SCISS is a core module that enables the city to maintain information on new sewer connections established between a building and sewer network within the city. This module provides a native mobile application (android) that allows the collection of the unique ID of both the building and the corresponding sewer network through a field survey. The collected building ID as well as sewer ID are maintained by this module, and once approved it is reflected in the BIMS, which updates the sanitation system and utility information of the building.</p>

## 6. **Public Health Information Support System (PHISS)**

<p style='text-align:justify'>PHISS is another core module of the IMIS, designed to empower municipalities in monitoring and addressing public health and sanitation challenges. PHISS enables the collection and maintenance of water sample data from various sources, including groundwater, surface water, and treated wastewater, to ensure compliance with water contamination standards. This functionality directly aligns with the CWIS objective of monitoring environmental outcomes associated with sanitation systems. Additionally, PHISS records and tracks cases of waterborne diseases across the city, providing municipalities with crucial data to understand and mitigate public health risks.</p>

<p style='text-align:justify'>One of the standout features of PHISS is its ability to maintain spatial and attribute data related to hotspot areas where waterborne diseases, such as diarrhea, cholera, dysentery, and typhoid, have been detected. The system also tracks fatalities linked to these diseases, offering a comprehensive overview of the impact on affected households and populations. By integrating this information with the UDSS municipal authorities can conduct detailed analyses of disease prevalence and its underlying causes. This data-driven approach enables strategic planning, targeted interventions, and efficient allocation of resources to reduce health risks in vulnerable areas.</p>

<p style='text-align:justify'>Water sample data and waterborne cases data maintained by PHISS helps municipality to monitor the CWIS indicators (i) Water contamination compliance of the water sources such as groundwater, surface water and treated wastewater, and (ii) Incidence of feacal-oral pathway diseases (e.g. diarrhea, cholera, dysentery and typhoid). With this information, municipalities can assess the effectiveness of sanitation systems in protecting public health and identify areas requiring urgent attention. By addressing these indicators, PHISS supports municipalities in achieving CWIS objectives, ensuring safe water quality and reducing the prevalence of sanitation-related diseases. The data export tools under PHISS allows users to export data in CSV, Shape and KML format where applicable.</p>

## 7. **Urban Management Decision Support System (UMDSS)**

<p style='text-align:justify'>The UMDSS is one of the core and powerful tool in IMIS, it provides advanced capabilities for spatial analysis, mapping, data export, and dashboard visualizations. These tools empower city authorities to engage in evidence-based planning, management, monitoring, and decision-making for planning, management and monitoring and evaluation of sanitation system and services as well as a broader municipal urban management activities. In addition to the UMDSS module, there are IMIS Dashboard, Building Dashboard under BIMS, FSM Dashboard under FSIMS, Utility Dashboard of IMIS, CWISIMS Module including CWIS and KPI dashboard under CWISIMS are also has been considered as the components of UMDSS.</p>

**7.1 UMDSS**

The UMDSS provides Export Data and Map Feature Sub-modules.

Export Data:

- <p style='text-align:justify'>The Export Data sub-module enables users to export data layers in flexible formats such as SHP and KML. Users can customize exports by selecting specific ward(s) or combining layers to suit their needs.</p>

Map Feature:

- <p style='text-align:justify'>The Map Feature is a powerful interactive map interface which provides a dynamic platform to visualize and analyze spatial data created by various modules and sub-modules in IMIS. It displays all spatial information with categorical styling based on attribute inforation, presenting summarized layers at city, ward and 0.5 km grid levels.</p>

- <p style='text-align:justify'>The interface includes various spatial and complex tools provide both basic and advanced functionalities, catering to a wide range of municipal operations. From navigation and visualization to sanitation-specific analyses and data updates, these features enhance decision-making by offering precise and actionable insights. These tools are – (i) Navigation and Map Interaction Tools (Zoom In & Zoom Out, Municipal Extent, Navigate, Info,  Coordinate Information, Locate Point by Coordinate, Measurement Tools, Measure Distance, Measure Area, (ii) Measurement Tools (Measure Distance, Measure Area), (iii) Printing and Support Tools (Print Map, Help), (iii) Sanitation-Specific Analysis Tools (Find Nearest Road, Find Building Connected to Containment, Find Containment Connected to Building, Find Associated Building, (iv) Editing Tools (Add Roads, Remove Markers)</p>

- <p style='text-align:justify'>The integration of tools like Find Nearest Road and Containment Analysis directly supports Citywide Inclusive Sanitation (CWIS) goals, while features like Measure Area, Print Map, and Add Roads contribute to broader urban management and planning efforts. By using these tools, municipal authorities can efficiently monitor sanitation systems, plan infrastructure upgrades, and ensure equitable service delivery across the city.</p>

- UMDSS also offer some specialized tools – (i) Service Delivery Tools for tracking (Applications, Emptied Applications Not Reached to Treatment Plant, Containments Proposed to Be Emptied, Feedback Chart (FSM Service Quality), (ii) General Tools for tracking (Buildings by Structure Type, Property Tax Collection, Water Supply), (iii) Data Export Tools (Filter by Wards, Export Data Set, Building Owner Information), (iv) Decision Tools (Tax Due Buildings, Sewers Potential Buildings, Buildings to Sewer, Buildings to Road, Hard to Reach Buildings, Building Close to Water Bodies, Buildings Using Community Toilets, Area Population), (V) Summary Information Tools (Summary Information Buffer Filter, Water Bodies Buffer Summary Information, Wards Summary Information, Road Buffer Summary Information, Point Buffer Summary Information).

  These tools enhance decision-making by providing targeted insights into property, utility, and demographic data. They allow municipalities to analyze specific areas, prioritize interventions, and support efficient planning, management and monitoring and evaluation of CWIS sanitation system and services, and overall urban management. 

 **7.2 CWIS Information Management System (CWISIMS):**

<p style='text-align:justify'>CWISIMS is a vital module of the **IMIS** that provides tools to generate CWIS indicators for the city and Key Performance Indicators (KPIs) to monitor the performance of sanitation service providers for a specified year. CWISIMS allows municipalities to set targets for each indicator in alignment with city policies and standards, and it includes a dashboard for the visualization of these indicators. The generated indicator data is maintained in a database, enabling easy access and review when needed, ensuring effective monitoring and planning.</p>

<p style='text-align:justify'>i. CWIS Dashboard - The CWIS Dashboard tracks 22 sanitation indicators <a href="https://github.com/base-imis/additional_resources/blob/master/CWIS%20Indicators%20in%20IMIS.pdf">(more information here)</a>, which are generated annually. These indicators are calculated by data maintained across various modules and sub-modules within IMIS, making them integral to understanding citywide sanitation performance. The indicators are based on the CWIS framework developed by Athena Informatics, ensuring consistency with globally recognized standards for inclusive sanitation monitoring. This dashboard provides municipalities with a centralized platform for tracking sanitation progress and assessing the effectiveness of implemented policies and services.</p>

 <p style='text-align:justify'>ii. KPI Dashboard – The KPI Dashboard complements the CWIS Dashboard by focusing on the performance of sanitation service providers. It monitors seven critical KPIs (1.Application Resposne Efficiency, 2. Customer Satisfaction, 3. PPE Compliance, 4. Safe Desludging, 5. Faecal Sludge Collection Ration, 6. Resonse Time, 7. Inclusion), which are also generated annually, using sanitation service data related to faecal sludge management (FSM) service delivery. These KPIs are designed to evaluate the efficiency and quality of services provided by sanitation operators, based on metrics developed by SNV Bangladesh. By leveraging this dashboard, municipalities can benchmark service provider performance and identify areas for operational improvement within their sanitation systems.</p>

<p style='text-align:justify'>CWISIMS, through its dual focus on CWIS indicators and KPIs, provides municipalities with robust tools for monitoring and improving their sanitation systems. By aligning indicator and KPI tracking with international standards and municipal goals, it ensures data-driven decision-making and continuous improvement in sanitation service delivery and management.</p>

**7.3 Dashboards**

<p style='text-align:justify'>There are all together six Dashboards considerd as the components of UDSS of the IMIS includes six dashboards that serve as its core components: (i) IMIS Dashboard, (ii) Building Dashboard, (iii) FSM Dashboard, (iv) Utility Dashboard, (v) CWIS Dashboard, and (vi) KPI Dashboard. Five of these dashboards have been discussed under their respective functional modules and sub-modules. The remaining dashboard, the IMIS Dashboard, is detailed below.</p>

<p style='text-align:justify'>The IMIS Dashboard serves as the central platform within the IMIS, offering a comprehensive overview of municipal data. It integrates information on building infrastructure, utilities (such as roads, drains, sewer, and water supply), sanitation systems and services, public and community toilets, public health, tax collection, water bill payments, and solid waste management. This dashboard provides municipalities with a unified interface for monitoring and managing citywide operations effectively, supporting informed decision-making and efficient service delivery.</p>

<p style='text-align:justify'>The Urban Management Decision Support System (UMDSS) enables municipalities to implement Citywide Inclusive Sanitation (CWIS) principles, supporting the planning, monitoring, and management of sanitation systems and services through a CWIS-focused approach. It also enhances revenue collection processes, including tax collection, water bill payments, and fees for solid waste management services, while providing actionable spatial insights to improve overall urban management. With its powerful analytical tools, UMDSS empowers municipalities to achieve greater efficiency, transparency, and inclusivity, not only in sanitation management but also in broader urban governance and service delivery.</p>  

## 8. Property Tax Collection Information Support System (PTCISS)

<p style='text-align:justify'>PTCISS is a value-added module integrated into the IMIS, designed to help municipalities monitor and manage property tax collection citywide through powerful map-based visualization tools. It enables city authorities to import property tax data maintained by the municipal property tax collection department into IMIS using a user-friendly data import tool supporting CSV formats. Once the data is integrated, property tax collection information is displayed in graphical formats on the IMIS dashboard and visualized on maps using tools provided by UMDSS. This facilitates quick and intuitive analysis of tax collection status across various parts of the city.</p>

<p style='text-align:justify'>Mapping property tax data provides actionable insights by identifying high-default areas (regions with a significant number of defaulters) and efficient collection zones (areas with fewer defaulters or higher compliance rates). These insights enable the property tax department to focus on areas requiring attention, thereby improving efficiency and compliance. The information generated by PTCISS empowers city authorities to engage in strategic planning and evidence-based decision-making, allowing them to: (a) develop better tax collection strategies, (b) formulate effective policies to increase compliance, and (c) plan for equitable tax management across different city regions.</p>

<p style='text-align:justify'>PTCISS also includes Data Export Tools, enabling municipal authorities to export building data along with their tax payment status. Additionally, it highlights mismatched tax records between the building data maintained in IMIS and the input tax data provided by the property tax department. This functionality helps identify and resolve discrepancies, ensuring data accuracy and transparency.</p>

<p style='text-align:justify'>Currently, PTCISS relies on periodic manual updates using CSV-based imports to maintain data accuracy. However, the system is designed to be future-ready, with the capability to support real-time data integration through an API if the city's property tax collection system provides connectivity access. This upgrade would enable automated and efficient data synchronization as municipal technology evolves.</p>

<p style='text-align:justify'>By leveraging the features and insights provided by PTCISS, municipalities can streamline property tax management, improve transparency, and enhance revenue collection efficiency. These improvements contribute significantly to better urban governance and equitable service delivery.</p>




## 9. Solid Waste Information Support System (SWISS)

<p style='text-align:justify'>The SWISS that enhances the management of solid waste services and fee collection. The module includes a tool for importing a municipality's solid waste customer data, including their last solid waste management service fee payment date, in CSV format. Based on this imported data, the SWISS module generates and maintains solid waste management customer records in IMIS, along with their fee payment status. It also provides tools to export building data with their solid waste service fee payment status and identifies discrepancies by highlighting records that exist in the municipality's solid waste customer database but are missing from IMIS.</p>

<p style='text-align:justify'>Using the imported data, UMDSS in IMIS helps municipal authorities map buildings with or without solid waste management services and their respective fee payment statuses. This mapping capability enables municipalities to monitor service coverage, assess the status of fee collections, and identify geographic trends in solid waste management service delivery. By integrating solid waste management customer data with building records in IMIS, the SWISS module equips municipal authorities with actionable insights to make informed decisions regarding solid waste services.</p>

<p style='text-align:justify'>The visualized data provided by SWISS supports municipalities in formulating policies to enhance the solid waste management service and fee collection processes. It also aids in optimizing resource allocation and improving overall service delivery by identifying areas requiring attention or adjustments. This integration is currently carried out manually on a periodic basis to ensure the data in IMIS remains up-to-date. Like the PTCISS module, SWISS does not yet support real-time data integration through an API.</p>

## 10. Water Supply Information Support System (WSISS)

<p style='text-align:justify'>The WSISS is another value-added module within the IMIS, designed to enhance the management of water supply services and fee collection. The WSISS includes a data importing tool that allows municipalities to upload water supply customer data, including their last fee payment date, in CSV format. Based on this imported data, the WSISS module generates and maintains records of water supply customers along with their fee payment status. It also provides tools to export building data with their water supply service and fee payment statuses and highlights discrepancies by identifying records present in the municipality's water supply customer database but missing in IMIS.</p>

<p style='text-align:justify'>Using the imported data, the UMDSS in IMIS enables municipal authorities to visualize the water supply fee payment status of buildings in maps of the City within IMIS. This capability allows municipalities to monitor fee collection statuses and assess geographic trends in water supply fee payments. By integrating water supply customer data with building information in IMIS, the WSISS module equips municipal authorities with actionable insights to make informed decisions regarding water supply services.</p>

<p style='text-align:justify'>The visualized data provided by WSISS supports the development of policies aimed at improving water supply fee collection processes, optimizing resource allocation, and enhancing overall service delivery. This integration helps municipalities target areas requiring attention, ensuring more effective and equitable water supply service management.</p>

<p style='text-align:justify'>Currently, as with the PTCISS and SWISS modules, the integration of data into WSISS must be carried out manually on a periodic basis to maintain accuracy.</p>

##  11. **Settings**

<p style='text-align:justify'>  This is a module to allows administrators to manage user access and control permissions within the system. Features includes : </p>

<p style='text-align:justify'>User Credentials - **s**ecurely store and manage user authentication details, including usernames, passwords options.</p>

<p style='text-align:justify'>Roles Management- Create and assign roles to users, defining their access level and responsibilities. Roles can be customized to reflect specific job functions.</p>

<p style='text-align:justify'>Permissions Control - fine-tune access by assigning permissions to roles or individuals, ensuring users can only interact with data and features relevant to their role.</p>

## 3.2 <a name="_toc189741405"></a>**Roles and Permissions**

   <a name="_hlk189691742"></a> <p style='text-align:justify'>The IMIS is equipped with pre-defined roles and permissions within the system that govern the extent to which the modules and their functionalities can be accessed. This role-based approach ensures visibility of modules, tools and features according to the responsibilities assigned to the role. The pre-defined roles can be easily updated and modified as per the requirements of the city through the Settings section of IMIS, and new roles beyond the pre-defined ones can be added as well.</p>

   <p style='text-align:justify'>The pre-defined roles are categorized according to the type of user. The IMIS has been developed with 5 different types of users and 17 pre-defined roles categorized within the user types:</p>

1. Municipality
   -  Municipality - Super Admin
   -  Municipality - Executive
   -  Municipality - Building Permit Department
   -  Municipality - Building Surveyor
   -  Municipality - Infrastructure Department
   -  Municipality - Tax Department
   -  Municipality - Water Billing Unit
   -  Municipality - Solid Waste Management Department
   -  Municipality - Sanitation Department
   -  Municipality - IT Admin
   -  Municipality - Public Health Department
   -  Municipality - Help Desk
1. Service Provider
   -  Service Provider – Admin
   -  Service Provider - Emptying Operator
   -  Service Provider - Help Desk	
1. Treatment Plant
   -  Treatment Plant - Admin
1. Help Desk
   -  Municipality - Help Desk
   -  Service Provider - Help Desk	
1. Guest
   -  Guest

For detailed role and permission setup, refer to the [Roles & Permission Matrix](https://github.com/base-imis/web_app/blob/master/documentations/code_documents/18%20-%20Roles%20%26%20Permission%20Matrix.md). 
## 3.3 <a name="_toc189741406"></a>**IMIS Driven Sanitation Service Delivery Chain**
   IMIS digitalizes the entire sanitation service delivery chain, enabling cities to efficiently manage each stage—from customer requests for emptying services to the safe disposal of fecal sludge at treatment plants. The sanitation service delivery model described below is currently implemented in IMIS. However, when deploying IMIS in new cities, customization may be required to align with the specific requirements and needs of the city. This component of IMIS—the sanitation service delivery model—is one of its strongest features, providing a comprehensive software solution that manages the entire service delivery chain. It offers a holistic approach to sanitation service management, ensuring efficiency, transparency, and accountability throughout the process. The IMIS-driven sanitation service chain, as currently implemented, is illustrated in [Figure 3](#mergeformat).

|<p>![](imis_sanitation_service.png)</p> <p>
 <a name="_ref189689217"></a>*Figure 3 IMIS driven sanitation service delivery chain*</p> 

## 3.3.1 <a name="_toc189741407"></a>**Entities in IMIS-driven sanitation service delivery model** 

There are six key entities in IMIS driven sanitation service model as discussed below: 

1. <p style='text-align:justify'><b>Customer</b> – The customer is the person who owns or resides in the building where the containment emptying service is required. Customer is responsible for requesting containment emptying service, receiving service, and paying a service fee to the service provider. Customer is also responsible for providing feedback, when contacted by help desk after the emptying service is completed. </p>

1. <p style='text-align:justify'><b>Help desk (HD)</b> –The HD is a key interface between customers and the SP. It receives applications from customer for emptying containment, logs the application in IMIS and assigns work to SSP. The HD receives applications through a dedicated central hotline or in person at the HD office.</p> 

   <p style='text-align:justify'>The HD is also responsible for collecting feedback from the customers and supporting on other aspects of FSM such as collecting and redressal grievances, advising on septic tank designs, and providing information on trained masons and different other sanitation-specific inquiries. The HD can be a part of the sanitation section of the city established on its premises or it can be a part of the service providers themselves.</p>  

1. <p style='text-align:justify'><b>Service Provider (SP)</b> – SP is responsible to take job orders from the help desk for emptying service, scheduling the service delivery date and time in consultation with the customer, and mobilize the ETO for emptying. SP must also maintain information about the emptying service provider, all human resources and infrastructure used in delivering services in IMIS.</p>

1. <p style='text-align:justify'><b>Emptying and Transport Operator (ETO)</b> – ETO is a team of driver and helpers and are a part of the service provider that are mobilized in the site for containment emptying. ETO is responsible for emptying containment, transporting and disposing collected FS in the FSTP designated by the city, collecting and updating information required after containment emptying through a mobile app provided for this purpose.</p>

1. <p style='text-align:justify'><b>Fecal Sludge Treatment Plant Operator (FSTPO)</b> - FSTPO is a staff member of an entity operating the FSTPO. The FSTPO updates daily sludge collection details, and lab reports on treated effluents and co-composting in IMIS. </p>

1. <p style='text-align:justify'><b>Sanitation Department</b> – Sanitation Department is responsible for overall monitoring and management of sanitation service using IMIS that includes monitoring of Help Desk, SSP, ETO, FSTPO; and generating reports and submitting them to concerned agencies and departments.</p>

## 3.3.2 <a name="_toc189741408"></a>**Processes in IMIS-driven sanitation service delivery model**

<p style='text-align:justify'> There are eight key processes involved in the IMIS-driven sanitation service delivery model in Faridpur – a) Process Application, b) Process Work Order, c) Maintain Sludge Disposal Record, d) Feedback Record e) Maintain Co-Composting Sales Record f) Maintain Quality Testing Record g) Submit Reports and h) CWIS Indicators Reporting. </p>

### A. **Process Application**

<p style='text-align:justify'><b>A1. Request for emptying service</b> -The Customer initiates the process by requesting emptying service to the HD through a help-line number or, in-person when their containment (septic tank/pit/ holding tank) requires emptying. Related information collected from the customer includes address of the building (Street Name/ Code, House Number/ BIN and ward number), applicant details (name, gender and contact information), application details (proposed emptying date and emergency desludging status). The HD assigns an appropriate registered service provider as well then submits the emptying application in IMIS which is automatically forwarded as a work order to the SSP, including the application registration code. </p>

### B. **Process Work Order** 

<p style='text-align:justify'><b>B1. Receiving work order</b> – The SSP receives auto generated work order in both the web and mobile application with application code and details. The SP calls the corresponding customer and confirms the emptying date, time, and updates application information in IMIS if required. IMIS automatically generates and forwards the application code and the customer's contact number to the ETO through the IMIS mobile application. </p>

<p style='text-align:justify'><b>B2. Emptying process</b> – The ETO empties the containment and updates emptying details through the mobile app in IMIS. IMIS provides real time updates to both the SP and HD on the information submitted through the field. In case of multiple trips required, the ETO updates emptying details after completion of all trips and the FSTP operator get notified about the forthcoming arrival of the vacutug after emptying the first trip.     </p>

### C. **Maintain Sludge Disposal Record** 

<p style='text-align:justify'><b>C1. Sludge disposal record</b> – The FSTPO logs records of information of sludge disposal at the FSTP in IMIS. Information such as vehicle number, vehicle capacity, arrival time, treatment plant ID where the sludge is disposed are collected in IMIS. IMIS provides real time updates to the SP and the HD about the completion of sludge disposal work. </p>

### D. **Maintain Feedback Record** 

<p style='text-align:justify'><b>D1. Feedback record</b> – After receiving the emptying service completion message in IMIS from ETO and FSTPO, the help desk calls customer for collecting feedback about the emptying service. Collected feedback are updated in IMIS. </p>

### E. **Maintain Quality Testing Record**   

<p style='text-align:justify'><b>E1. Effluent test record</b> - The FSTPO periodically collects a sample of the final effluent and performs a treatment efficiency test with help of a lab. The FSTPO updates the effluent test report in IMIS. The original lab report is sent to the Sanitation Unit. This enables the Sanitation Unit to monitor the quality of effluent to assess the treatment effectiveness of the FSTP through IMIS. </p>

### F. **Submit Reports** 

<p style='text-align:justify'><b>F1. Sanitation Services report</b> – The sanitation unit generates the monthly report of the sanitation services provided directly through IMIS and submits to the appropriate authorities and departments as needed. </p>

<p style='text-align:justify'><b>F2. KPI report</b> – The sanitation unit generates the yearly KPI report directly through IMIS and submits to the appropriate authorities and departments as needed. </p>

<p style='text-align:justify'><b>F3. Application report</b> – The sanitation unit generates the individual application report directly through IMIS and submits to the appropriate authorities and departments as needed. </p>

<p style='text-align:justify'><b>F4. FSTP operation report</b> – The sanitation unit generates a monthly metrics on FSTP operation information (records of sludge disposal and information on drying beds use for sludge disposal) directly through IMIS and submits to the appropriate agencies and department as needed.   

### G. **CWIS indicators**   

<p style='text-align:justify'><b>G1. Generate CWIS indicators</b> – The sanitation unit generates yearly CWIS indicators of the city and submits to concerned agencies and departments at the end of the year. However, authorised users with access to IMIS can view these records on the CWIS indicators dashboard or generate them as needed. </p>

## 3.4 <a name="_toc189741409"></a>**Technical Stack**
   <p style='text-align:justify'>IMIS is developed with a PHP backend utilizing the Laravel framework to manage core business logic, API development, and database interactions. The frontend is built using HTML5, CSS3, and JavaScript (ES6+) to create dynamic UI components and a responsive user interface. Bootstrap is integrated to ensure responsiveness across various devices. IMIS uses PostgreSQL as its relational database, enhanced with the PostGIS extension for spatial data processing, which is essential for the platform's spatial visualization and analysis tools.</p>

   <p style='text-align:justify'>GeoServer, deployed on Apache Tomcat, is used to render and serve spatial data layers. It integrates with PostGIS to provide efficient map rendering and data visualization, serving spatial data through Web Map Services (WMS) and Web Feature Services (WFS) for interactive mapping. OpenLayers is employed on the frontend for the map interface, facilitating interaction and visualization of spatial data. The integration between GeoServer and OpenLayers enables IMIS to display real-time, dynamic maps with fast spatial data rendering.</p>


|<p>![](archi.png)</p> 

<p style='text-align:justify'>IMIS is containerized using Docker, allowing for streamlined deployment on Linux OS (Ubuntu 22.04). Docker Compose is used to orchestrate containers, with the application running on virtual machine (VM) instances and Nginx acting as the reverse proxy and web server. NPM handles package management for JavaScript libraries and frontend dependencies, while Composer manages Laravel framework dependencies.</p>

<p style='text-align:justify'>Various third-party libraries and packages are integrated to enhance functionality, including DataTables for displaying large datasets on the frontend, DomPDF for PDF generation, MapFishPrint for map printing, and AdminLTE for dashboards and navigation panels. The codebase is version-controlled using Git, with repositories organized within a GitHub organization structure, further detailed in Section 5.</p>

# 4. <a name="_toc189741410"></a>**IMIS Implementation Framework for New Cities**
   <p style='text-align:justify'>The successful implementation of IMIS in a new city requires systematic planning, coordination, and adherence to structured processes. The following outlines the recommended approach for deploying IMIS in a new city:</p>

### 1. **Understanding IMIS: Features, Functions, Capabilities, and Strengths**

<p style='text-align:justify'>Before implementing IMIS in a new city, the team responsible must have a comprehensive understanding of the system, including its features, functions, and capabilities. A thorough knowledge of IMIS is essential to ensure successful deployment and effective utilization. The team should familiarize themselves with why IMIS was developed, the modules it comprises, the features it offers, and the types of information it manages. This foundational understanding is critical for aligning IMIS with the city's requirements and ensuring a seamless implementation process. To support this, several resource materials are available, including the IMIS website, the Base IMIS Document, the IMIS Brochure, the IMIS Banner, and the IMIS Orientation Presentation. These materials provide detailed insights into the system and serve as essential references during implementation. Additionally, if further clarity is required, the team can request a live demo through the IMIS website to gain a more practical understanding of the system.</p>

### 2. **Readiness Assessment & Requirement Analysis** 

<p style='text-align:justify'>The readiness assessment & requirement analysis is a crucial component for the implementation of IMIS in a new city. This step is carried out through multiple interactions with the city officials and concerned stakeholders, as the output of this analysis drives the customization and implementation of IMIS. The following activities are recommended to be carried out to ensure the city officials understand the IMIS, and the team responsible for implementing IMIS can understand the requirements of the city.</p>

1. **Orientation of City Officials:**
- <p style='text-align:justify'>Conduct orientation session(s) for city officials to introduce the IMIS, highlighting its features, functions, and capabilities. Utilize existing resources provided in <a href="https://github.com/base-imis/additional_resources/tree/master">GitHub</a> to ensure that officials fully understand the strengths and potential of the system.</p>
- Ensure the city is informed of the following policy directives necessary for the successful implementation of IMIS: 
  - Clear separation of authority(s) and responsibility(s) among the different units/departments, divisions and the other stakeholders) regarding
  - A detailed chain of command regarding the process of collecting, transporting, disposing, treating, and reuse of disposed waste.
  - Basic standard, qualification, and/or experience for all human resource(s), as well as equipment(s) being used in overall sanitation chain
  - Process of mandatory data collection from the end user, as well as data entry schedule and procedure(s).
  - A standard KPIs for all internal and external parties involved in the complete sanitation service chain.
  - CWIS indicators for monitoring and evaluation of CWIS.
- During the orientation session(s), obtain confirmation from the city leadership to proceed with the implementation of IMIS.

2. **Conduct the readiness assessment**

<p style='text-align:justify'> The IMIS readiness assessment must be conducted based on the IMIS Readiness Framework provided in <a href='https://github.com/base-imis/additional_resources/blob/master/Resource%20Materials%20for%20Readiness%20Assessment.pdf'>GitHub</a>. The IMIS readiness assessment is a structured evaluation process designed to assess the city's readiness for implementing IMIS to enhance planning, management, and monitoring and evaluation of sanitation systems and services, following the Citywide Inclusive Sanitation (CWIS) approach. IMIS readiness assessment serves as a valuable feasibility analysis tool to make informed decisions about IMIS implementation for developing investment plan, strategies to mitigate potential obstacles or challenges that may arise in the process of implementing IMIS. Three distinct aspects of readiness are assessed, each of which holds equal importance.</p>

- <p style='text-align:justify'>Data readiness- This component studies the existing availability of data and information in the city, enables to identify the data gaps and develop strategies and methodologies to collect the data either through secondary sources or a GIS-based census survey.</p>
- <p style='text-align:justify'>e-Governance Initiatives and IT readiness: This component studies the existing e-governance initiatives of the city, evaluates the readiness of the city in terms of IT infrastructure and capacity of the officials to migrate to digital systems. This section provides insight into the extent of capacity building activities that shall be required to familiarize the city officials with digital systems. </p>
- <p style='text-align:justify'>IMIS-driven sanitation service delivery readiness: This component studies the city's existing sanitation service delivery model, identifying key entities and business processes currently implemented. Based on this study, the study team must develop and propose a revised, IMIS-driven model that aligns with the city's needs and operational environment. The proposed service delivery model must be shared with the concerned officials and finalized.</p>

3.  **Propose New Modules & Develop Update Mechanisms:**
- <p style='text-align:justify'>Study the city's planning, management, and monitoring & evaluation requirements, and propose new modules that will not only address these needs but also enhance the capabilities of IMIS to better serve the city's objectives.</p>
- <p style='text-align:justify'>The initial dataset is developed through a census survey, but continuous updates will be required once the system is implemented. To facilitate this, study the workflows of key departments in the city, such as the Building Permit Department, Infrastructure Department, and Tax Departments, to create efficient update mechanisms for the information stored in the seven core modules of IMIS. Based on this analysis, propose new strategies and workflows that seamlessly integrate the data update process into the IMIS. As much as possible, the update mechanisms should be embedded within the city's existing business processes to minimize additional workload. Additionally, propose suitable data collection tools for capturing spatial data, if necessary.</p>

4. **Customization Requirements**
- <p style='text-align:justify'> <b >Develop a Detailed Customization Document</b> - Create a comprehensive document that outlines the city-specific customization requirements for the Integrated Municipal Information System (IMIS). This document should be based on the findings of the readiness assessment and should clearly define the necessary modifications and enhancements needed to tailor the system to the city's unique needs.</p>
- <p style='text-align:justify'> <b>Determine the Level of Customization</b> - Assess the level of customization required for the IMIS system to ensure it effectively addresses the city's specific requirements. This involves identifying key functionalities that need to be added, modified, or enhanced to ensure the system aligns with the city's operational processes, regulations, and goals. The document should provide a clear roadmap for implementing these changes.</p>

### 3. GIS Data Creation Process
- <p style='text-align:justify'> <b>Study Existing Data Situations</b> - Based on the readiness assessment, review the current data to understand the existing spatial and attribute information. Based on this review, identify the necessary data to be collected. This includes both spatial data (geographic coordinates, mapping layers, etc.) and attribute data (descriptive information related to the spatial data). Additionally, define the specific data layers required for the GIS system. Refer to the <a href='https://github.com/base-imis/web_app/tree/master/documentations/data_dictionary'>data dictionary</a>, <a href='https://github.com/base-imis/other_resources/blob/main/Building%20Questionnaire.pdf'>survey questionnaire</a> and <a href='https://github.com/base-imis/additional_resources/tree/master/GIS%20Data%20Creation%20Resource%20Materials'>GIS Data Creation Resource Materials</a> for further information.</p>
- <p style='text-align:justify'> <b>Data Collection Tools and Survey Development</b> - Develop the necessary tools for data collection, including survey questionnaires. These tools should be designed to capture both spatial and attribute data accurately. Once developed, conduct the survey to gather the required data for GIS creation.</p>
- <p style='text-align:justify'> <b>Data Cleaning and Processing</b> - After collecting the data, perform data cleaning to remove any inconsistencies, inaccuracies, or incomplete entries. The cleaned data should be processed according to the specifications outlined in the <a href='https://github.com/base-imis/web_app/tree/master/documentations/data_dictionary'>data dictionary</a>. This ensures that the data is correctly formatted and ready for migration and integration into the GIS system.</p>

### 4. **Customization of IMIS**
- <p style='text-align:justify'> <b>Create GitHub Organization and Repository</b> - Establish a new GitHub organization specifically for the city based on the existing <a href='https://github.com/base-imis'>GitHub organization</a>. Create a replica of the existing GitHub organization to ensure a separate customized version of each document is maintained.</p>
- <p style='text-align:justify'> <b>Deploy IMIS Locally for Development and Customization</b> - Set up a local deployment of IMIS with the provided database. Follow the deployment documentation provided in <a href='https://github.com/base-imis/deployment_documentation'>GitHub</a>. This environment will serve as the foundation for development and customization efforts.</p>
- <p style='text-align:justify'> <b>Import Data:</b> Import the processed data collected through primary and secondary sources into the newly deployed IMIS instance, ensuring that the imported data aligns with the system's structure and supports the forthcoming customizations.</p>
- <p style='text-align:justify'> <b>Customization</b> and <b>Development of New Modules:</b> Customize the system and develop new modules as outlined Customization Requirements. This includes adapting the IMIS platform to the city's specific needs, while ensuring that new functionalities are seamlessly integrated.</p>
- <p style='text-align:justify'> <b>System Testing:</b> Conduct thorough testing to confirm that all existing and newly developed features function as expected. This ensures that the system remains operational and reliable post-customization.</p>
- Key Customization Considerations
  - <p style='text-align:justify'><b>Maintain Linkages with Building IMS:</b> Ensure that the existing linkages between the Building Information Management System (IMS) and other systems remain intact during customization.</p>
  - <p style='text-align:justify'><b>Preserve Relational Database Structure:</b> Ensure that the relational database structure of the system is preserved and not disrupted by new customizations.</p>
  - <p style='text-align:justify'><b>Integrate New Modules with Existing Ones:</b> New modules should be integrated with the existing modules wherever possible to ensure interoperability and prevent the creation of isolated, siloed systems.</p>
  - <p style='text-align:justify'><b>Impact Analysis for Customization:</b> Perform in-depth impact analysis before carrying out any customization. This ensures that modifications do not negatively affect the functionality of other modules, with particular attention given to the Urban Management Decision Support System (UMDSS).</p>
  - <p style='text-align:justify'><b>Incorporation of Spatial Information:</b> Integrate spatial information as extensively as possible, ensuring that the newly maintained spatial data is accessible within the Urban Management Decision Support System (UMDSS).</p>

- <p style='text-align:justify'><b>Update Technical Documentation:</b> Ensure that all <a href='https://github.com/base-imis/web_app/tree/master/documentations'>technical documentation</a> is updated to reflect the changes made during the customization process. This includes providing accurate documentation of the source code, database changes, and any adjustments to the system's architecture.</p>
- <p style='text-align:justify'><b>Update User Manuals and Existing Documentation:</b> Revise the <a href='https://github.com/base-imis/user_manual'>user manuals</a> and other documentation based on the customizations and new features implemented. This ensures that users are well-informed about the updates and can fully utilize the new functionalities of the system.</p>
### 5. **Deployment of IMIS**
- <p style='text-align:justify'><b>Obtain Government Server for Deployment:</b> Secure the necessary government server to host the production environment for the Integrated Municipal Information System (IMIS). This ensures that the deployment is conducted on a reliable and secure infrastructure that meets the city's requirements.</p>
- <p style='text-align:justify'><b>Deploy IMIS for Production:</b> Deploy the IMIS system in the production environment, incorporating the collected data and the customized version of the system tailored for the city. Follow the deployment documentation provided in <a href='https://github.com/base-imis/deployment_documentation'>GitHub</a>. Ensure that all necessary configurations are applied and the system is fully operational, with the ability to handle live data and real-time user interactions.</p>
### 6. **Capacity Building for IMIS**
-  <p style='text-align:justify'><b>Training on IMIS Usage for Stakeholders:</b> Organize capacity-building sessions to ensure stakeholders are proficient in using the IMIS. Training content will be adapted using provided resources and will be customized to reflect the specific changes and updates made during the IMIS development and customization phases.</p>
- <p style='text-align:justify'><b>Required Capacity Building Programs:</b></p>

|**SN**|**Capacity Building Program**|**Target Audience**|
| - | - | - |
|1\.|CWIS and IMIS for Policy Makers|Political leaders including Mayors, ward chairpersons/council members|
|2\.|CWIS and IMIS for Executives|Chief executive officers and department heads|
|3\.|Training on IMIS for Planning, Management, and Monitoring & Evaluation of CWIS|Department head of Engineering department, section head of Urban Planning, section head of Sanitation|
|4\.|Training on IMIS for Help Desk|Help desk staff|
|5\.|Training on IMIS for Sanitation Service Provider (SSP)|SSP staff and Vacuum Tug operators|
|6\.|Training on IMIS for FSTP Operators|FSTP operators|
|7\.|Data Integration and Visualization using IMIS|Staff of holding tax department, water billing section, trade licensing section|
|8\.|Data Capturing of New Building Footprints and Containment Information|Staff of building permit section / holding tax assessment unit|
|9\.|Maintaining Utility Data (e.g., Roads, Stormwater Drain)|Staff of Engineering department|
|10\.|Basic GIS Data Management|Data/IT support staff|
|11\.|Handholding Support|All IMIS users as mentioned in the training targets|
|12\.|Follow-up Support|All IMIS users|

### 7.  **Annual Maintenance Support**
- <p style='text-align:justify'><b>Provide Ongoing Technical Assistance:</b> Offer continuous support for the IMIS system through annual maintenance, which will include bug fixes, server maintenance, and any necessary technical assistance. This ensures that the system remains operational, updated, and secure for all users.</p>


<a name="_ref189693623"></a><a name="_ref189693627"></a>
# 5. <a name="_toc189741411"></a>**Accessing IMIS**

<p style='text-align:justify'>The resources related to IMIS such as the web-application source code, technical documentation and other corresponding resource materials are maintained on GitHub and can be access through <a href='https://github.com/base-imis'>https://github.com/base-imis</a>. This GitHub organization contains five repositories ([Figure 4](#mergeformat)) that provide comprehensive information and documentation on IMIS. The organization provides the following documentation and source code:</p>

- Source code for web app with technical documentation, data dictionary and geoserver documentation. 
- Source code for mobile app with technical documentation
- Deployment manuals for Linux and Windows Environment
- User manuals for web and mobile applications
- Additional resource materials such IMIS readiness assessment framework, building survey questionnaire, IEC materials, etc.

All these documentations are maintained according to the structure provided in Section 4.1

<p style='text-align:justify'>When deploying the IMIS to a new city, it is highly recommended to create an exact replica of this organization with all repositories and maintain a separate instance of the entire organization.</p>

## 5.1. <a name="_toc178241128"></a><a name="_toc189741412"></a>**Organization Structure** 
   The structure of the GitHub organization for Base IMIS is presented below:


|<p>![](git.png)</p> <p>
<a name="_ref189657774"></a>*Figure 4 IMIS GitHub Structure*</p> 

   

The organization named **IMIS** is divided into five repositories:

1. <b>**web-app**</b>: The web-app repository maintains the source code for the IMIS web application. In addition to the files and folders related to the source code, a sub-folder named "documentation" is also included, which contains the following:
   1. <p style='text-align:justify'><b>code_documents</b>: This sub-folder contains the detailed technical documentation related to the source code of IMIS. The code documentations are further divided into individual files that cover different aspects of the source code. This documentation is developed to provide clarity on the source code of the IMIS, and how the different functions and features have been implemented. </p>
   1. <p style='text-align:justify'><b>geoserver_documents</b>: This sub-folder includes the detailed parameters necessary for configuring the geoserver for IMIS. Setting up the geoserver is a critical part of the IMIS deployment process, involving various configurations. This document outlines the essential parameters and information required for the configuration process.</p>
   1. <p style='text-align:justify'><b>data_dictionary</b>: This sub-folder contains two essential documents: the IMIS Data Dictionary and the Entity Relationship Diagram (ERD). The Data Dictionary details all the database tables along with their corresponding attributes, while the ERD illustrates the relationships established between these tables.</p>

   
1. <p style='text-align:justify'><b>deployment_documentation</b>: This repository contains the necessary documentation and supporting source code required for systematically deploying IMIS in Linux and Windows environment. It is recommended to follow the deployment documentation extensively to ensure a smooth and bug-free deployment process. It includes the following documentation:

   1. <p style='text-align:justify'><b>deployment_manuals</b>: The Deployment User Manuals provide a comprehensive, step-by-step guide for deploying an instance of IMIS, covering the web application, database and geoserver for Linux and Windows environments. These manuals include detailed instructions, solutions for common issues, and additional recommendations. Two separate manuals are provided: one for deploying in a Linux environment, intended for production instances, and another for Windows, designed for local development and source code customization.</p>
   1. <p style='text-align:justify'><b>docker_config</b>: This sub-folder contains the source code and configuration files for deploying IMIS using Docker containers in Linux environment. The purpose and use of this source code is further elaborated in the Deployment User Manual for Linux Environment. </p>
   1. <p style='text-align:justify'><b>database</b>: This sub-folder includes the database compatible with the latest version of IMIS. It provides two types of databases: a blank database ('base_imis.sql') and a database populated with sample data ('base_imis_sample_db.sql'). Detailed guidance on using these databases is provided in the deployment manuals.</p>
   1. <p style='text-align:justify'><b>geoserver_setup</b>: This sub-folder contains the essential resources for configuring the geoserver workspace required for IMIS. It includes a zip file (`base_imis.rar`) with a pre-configured workspace compatible with geoserver and a configuration file (`config.yml`) for setting up the print function. Both resources are explained in detail in the deployment manual.</p>
   1. <p style='text-align:justify'><b>sample_import_data</b>: This sub-folder includes sample data sets that the deployment team can use to test the data import process into the blank database. Detailed instructions on utilizing these data sets are provided in the Deployment Manuals.</p>

1. <p style='text-align:justify'><b>user_manual</b>: This repository contains user manuals for both the web application and the mobile application. There are four user manuals in total: 

   1. <p style='text-align:justify'><b>Web App Master User Manual:</b> A complete guide to the IMIS web application, covering modules and their features to help users effectively utilize the platform.</p>
   1. <p style='text-align:justify'><b>Building Information Collection (BIC) Mobile App User Manual:</b> Step-by-step instructions for collecting building footprint data for newly constructed or missing buildings within the IMIS.</p>
   1. <p style='text-align:justify'><b>Emptying Information Collection (EIC) Mobile App User Manual:</b> A guide for sanitation service providers to efficiently use the EIC app for collecting and managing emptying service data.</p>
   1. <p style='text-align:justify'><b>Sewer Connection Information Collection (SCIC) Mobile App User Manual:</b> Instructions for municipal staff to record and manage new sewer connections, ensuring accurate data collection and integration.</p>
1. <p style='text-align:justify'><b>additional_resources:</b> In addition to the source code and technical documentation, this repository also includes a range of supplementary resources designed to provide further clarity and information on IMIS. These resources include the Building Questionnaire, CWIS Indicators in IMIS, IMIS Brochure, IMIS Poster, and more. All these documents are maintained within this repository.</p>

 ## 5.2 <a name="_toc178241129"></a><a name="_toc189741413"></a>**Branch Structure** 
<p style='text-align:justify'>Each repository within the organization has two branches, namely the master branch and the development branch. The master branch maintains the latest stable version of the code which has been tested extensively and is bug free. The development branch maintains the latest version of the code that is being developed currently and might not be stable and bug free. The master branch is hosted in a server that can be accessible upon request; however, the development branch is hosted in a server that is not accessible to the public.</p>

## 5.3 <a name="_toc178241130"></a><a name="_toc189741414"></a>**Version Management**
<p style='text-align:justify'>Version management is handled by assigning tags with each release. The development branch is continuously updated across all repositories within the organization. However, the master branch is only updated periodically, after all necessary testing and debugging have been completed to ensure stability. When the master branch is updated to match the development branch, a tag is added to indicate the current stable system. This process is applied to all repositories when updating the master branch.</p>

<p style='text-align:justify'>Minor patches or fixes are reflected in the third decimal (V1.0.x), minor features or functions are shown in the second decimal (V1.x.0), and new modules or major features are indicated by the first decimal (Vx.0.0). The relevant documentation is updated similarly, with each repository maintained accordingly whenever the master branch is updated. </p>


## 5.4 <a name="_toc178241131"></a><a name="_toc189741415"></a>**Organization Maintenance**
<p style='text-align:justify'>The Innovative Solution Pvt. Ltd. (ISPL) development in collaboration with Global Water & Sanitation Center – Asian Institute of Technology (GWSC-AIT) team will oversee the maintenance of the organization and its associated documentation. For organizations established to implement IMIS in new cities, the designated local consultant responsible for deployment or annual maintenance will manage the cloned organization.

<p style='text-align:justify'>All repositories within the organization will be protected from external write access when shared publicly. Developers interested in contributing new features or modules to IMIS are required to fork the repository, implement their changes, and submit a pull request (PR) to the development branch of the respective repository. Upon receiving the PR, the maintenance team will review and validate the proposed changes before deciding to merge or reject the request. If a PR is rejected, detailed feedback and comments will be provided directly within the pull request.</p>


# 6. <a name="_toc189741416"></a>**License**
<p style='text-align:justify'>The Base IMIS is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. The official license text and corresponding full license are presented below.</p>

   ## 6.1 <a name="_toc178241134"></a><a name="_toc189741417"></a>**License Text**
   <p style='text-align:justify'>Base IMIS © 2022-2025 by <a href='https://innovativesolution.com.np'>Innovative Solution Pvt. Ltd (ISPL)</a> & <a href='https://www.gwsc.ait.ac.th/'>GWSC-AIT</a> is licensed under <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1'>CC BY-NC-SA 4.0</a> 

   <p style='text-align:justify'>Note: For the sake of brevity, the organizations will be referred to as ISPL and GWSC-AIT in the license notice in all documentations, websites, and other resource materials.</p>

   ## 6.2 <a name="_toc189741418"></a>**Full License**
   <p style='text-align:justify'>By exercising the Licensed Rights (defined below), You accept and agree to be bound by the terms and conditions of this Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ("Public License"). To the extent this Public License may be interpreted as a contract, You are granted the Licensed Rights in consideration of Your acceptance of these terms and conditions, and the Licensor grants You such rights in consideration of benefits the Licensor receives from making the Licensed Material available under these terms and conditions.</p>

**Section 1 -- Definitions.**

1. <p style='text-align:justify'>Adapted Material means material subject to Copyright and Similar Rights that is derived from or based upon the Licensed Material and in which the Licensed Material is translated, altered, arranged, transformed, or otherwise modified in a manner requiring permission under the Copyright and Similar Rights held by the Licensor. For purposes of this Public License, where the Licensed Material is a musical work, performance, or sound recording, Adapted Material is always produced where the Licensed Material is synched in timed relation with a moving image.</p>
1. <p style='text-align:justify'>Adapter's License means the license You apply to Your Copyright and Similar Rights in Your contributions to Adapted Material in accordance with the terms and conditions of this Public License.</p>
1. <p style='text-align:justify'>BY-NC-SA Compatible License means a license listed at <a href='https://creativecommons.org/compatiblelicenses'>creativecommons.org/compatiblelicenses</a>, approved by Creative Commons as essentially the equivalent of this Public License.</p>
1. <p style='text-align:justify'>Copyright and Similar Rights means copyright and/or similar rights closely related to copyright including, without limitation, performance, broadcast, sound recording, and Sui Generis Database Rights, without regard to how the rights are labeled or categorized. For purposes of this Public License, the rights specified in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s2b'>2(b)(1)-(2)</a> are not Copyright and Similar Rights.</p>
1. <p style='text-align:justify'>Effective Technological Measures means those measures that, in the absence of proper authority, may not be circumvented under laws fulfilling obligations under Article 11 of the WIPO Copyright Treaty adopted on December 20, 1996, and/or similar international agreements.</p>
1. <p style='text-align:justify'>Exceptions and Limitations means fair use, fair dealing, and/or any other exception or limitation to Copyright and Similar Rights that applies to Your use of the Licensed Material.</p>
1. <p style='text-align:justify'>License Elements means the license attributes listed in the name of a Creative Commons Public License. The License Elements of this Public License are Attribution, NonCommercial, and ShareAlike.</p>
1. <p style='text-align:justify'>Licensed Material means the artistic or literary work, database, or other material to which the Licensor applied this Public License.</p>
1. <p style='text-align:justify'>Licensed Rights means the rights granted to You subject to the terms and conditions of this Public License, which are limited to all Copyright and Similar Rights that apply to Your use of the Licensed Material and that the Licensor has authority to license.</p>
1. <p style='text-align:justify'>Licensor means the individual(s) or entity(ies) granting rights under this Public License.</p>
1. <p style='text-align:justify'>NonCommercial means not primarily intended for or directed towards commercial advantage or monetary compensation. For purposes of this Public License, the exchange of the Licensed Material for other material subject to Copyright and Similar Rights by digital file-sharing or similar means is NonCommercial provided there is no payment of monetary compensation in connection with the exchange.</p>
1. <p style='text-align:justify'>Share means to provide material to the public by any means or process that requires permission under the Licensed Rights, such as reproduction, public display, public performance, distribution, dissemination, communication, or importation, and to make material available to the public including in ways that members of the public may access the material from a place and at a time individually chosen by them.</p>
1. <p style='text-align:justify'>Sui Generis Database Rights means rights other than copyright resulting from Directive 96/9/EC of the European Parliament and of the Council of 11 March 1996 on the legal protection of databases, as amended and/or succeeded, as well as other essentially equivalent rights anywhere in the world.</p>
1. <p style='text-align:justify'>You means the individual or entity exercising the Licensed Rights under this Public License. Your has a corresponding meaning.</p>

**Section 2 -- Scope.**

1. License grant.

   1. <p style='text-align:justify'>Subject to the terms and conditions of this Public License, the Licensor hereby grants You a worldwide, royalty-free, non-sublicensable, non-exclusive, irrevocable license to exercise the Licensed Rights in the Licensed Material to:</p>

      1. <p style='text-align:justify'>reproduce and Share the Licensed Material, in whole or in part, for NonCommercial purposes only;</p>

      1. <p style='text-align:justify'>produce, reproduce, and Share Adapted Material for NonCommercial purposes only.</p>
   1. <p style='text-align:justify'>Exceptions and Limitations. For the avoidance of doubt, where Exceptions and Limitations apply to Your use, this Public License does not apply, and You do not need to comply with its terms and conditions.</p>
   1. <p style='text-align:justify'>Term. The term of this Public License is specified in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s6a'>6(a)</a>.</p>
   1. <p style='text-align:justify'>Media and formats; technical modifications allowed. The Licensor authorizes You to exercise the Licensed Rights in all media and formats whether now known or hereafter created, and to make technical modifications necessary to do so. The Licensor waives and/or agrees not to assert any right or authority to forbid You from making technical modifications necessary to exercise the Licensed Rights, including technical modifications necessary to circumvent Effective Technological Measures. For purposes of this Public License, simply making modifications authorized by this Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s2a4'>2(a)(4)</a> never produces Adapted Material.</p>
   1. Downstream recipients.

      1. <p style='text-align:justify'>Offer from the Licensor -- Licensed Material. Every recipient of the Licensed Material automatically receives an offer from the Licensor to exercise the Licensed Rights under the terms and conditions of this Public License.</p>
      1. <p style='text-align:justify'>Additional offer from the Licensor -- Adapted Material. Every recipient of Adapted Material from You automatically receives an offer from the Licensor to exercise the Licensed Rights in the Adapted Material under the conditions of the Adapter's License You apply.</p>
      1. <p style='text-align:justify'>No downstream restrictions. You may not offer or impose any additional or different terms or conditions on, or apply any Effective Technological Measures to, the Licensed Material if doing so restricts exercise of the Licensed Rights by any recipient of the Licensed Material.</p>
   1. <p style='text-align:justify'>No endorsement. Nothing in this Public License constitutes or may be construed as permission to assert or imply that You are, or that Your use of the Licensed Material is, connected with, or sponsored, endorsed, or granted official status by, the Licensor or others designated to receive attribution as provided in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3a1A'>3(a)(1)(A)(i)</a>.</p>
1. Other rights.
   1. <p style='text-align:justify'>Moral rights, such as the right of integrity, are not licensed under this Public License, nor are publicity, privacy, and/or other similar personality rights; however, to the extent possible, the Licensor waives and/or agrees not to assert any such rights held by the Licensor to the limited extent necessary to allow You to exercise the Licensed Rights, but not otherwise.</p>
   1. <p style='text-align:justify'>Patent and trademark rights are not licensed under this Public License.</p>
   1. <p style='text-align:justify'>To the extent possible, the Licensor waives any right to collect royalties from You for the exercise of the Licensed Rights, whether directly or through a collecting society under any voluntary or waivable statutory or compulsory licensing scheme. In all other cases the Licensor expressly reserves any right to collect such royalties, including when the Licensed Material is used other than for NonCommercial purposes.</p>

**Section 3 -- License Conditions.**

<p style='text-align:justify'>Your exercise of the Licensed Rights is expressly made subject to the following conditions.</p>

1. <p style='text-align:justify'>Attribution.

   1. <p style='text-align:justify'>If You Share the Licensed Material (including in modified form), You must:</p>

      1. <p style='text-align:justify'>retain the following if it is supplied by the Licensor with the Licensed Material:</p>

         1. <p style='text-align:justify'>identification of the creator(s) of the Licensed Material and any others designated to receive attribution, in any reasonable manner requested by the Licensor (including by pseudonym if designated);</p>

         1. <p style='text-align:justify'>a copyright notice;</p>

         1. <p style='text-align:justify'>a notice that refers to this Public License;</p>

         1. <p style='text-align:justify'>a notice that refers to the disclaimer of warranties;</p>

         1. <p style='text-align:justify'>a URI or hyperlink to the Licensed Material to the extent reasonably practicable;</p>

      1. <p style='text-align:justify'>indicate if You modified the Licensed Material and retain an indication of any previous modifications;</p>

      1. <p style='text-align:justify'>indicate the Licensed Material is licensed under this Public License, and include the text of, or the URI or hyperlink to, this Public License.</p>

   1. <p style='text-align:justify'>You may satisfy the conditions in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3a1'>3(a)(1)</a> in any reasonable manner based on the medium, means, and context in which You Share the Licensed Material. For example, it may be reasonable to satisfy the conditions by providing a URI or hyperlink to a resource that includes the required information.</p>
   1. <p style='text-align:justify'>If requested by the Licensor, You must remove any of the information required by Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3a1A'>3(a)(1)(A)</a> to the extent reasonably practicable.</p>

1. <p style='text-align:justify'>ShareAlike.

   1. <p style='text-align:justify'>In addition to the conditions in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3a'>3(a)</a>, if You Share Adapted Material You produce, the following conditions also apply.</p>

      1. <p style='text-align:justify'>The Adapter's License You apply must be a Creative Commons license with the same License Elements, this version or later, or a BY-NC-SA Compatible License.</p>
      1. <p style='text-align:justify'>You must include the text of, or the URI or hyperlink to, the Adapter's License You apply. You may satisfy this condition in any reasonable manner based on the medium, means, and context in which You Share Adapted Material.</p>
      1. <p style='text-align:justify'>You may not offer or impose any additional or different terms or conditions on, or apply any Effective Technological Measures to, Adapted Material that restrict exercise of the rights granted under the Adapter's License You apply.</p>

**Section 4 -- Sui Generis Database Rights.**

<p style='text-align:justify'>Where the Licensed Rights include Sui Generis Database Rights that apply to Your use of the Licensed Material:</p>

1. <p style='text-align:justify'>for the avoidance of doubt, Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s2a1'>2(a)(1)</a> grants You the right to extract, reuse, reproduce, and Share all or a substantial portion of the contents of the database for NonCommercial purposes only;</p>
1. <p style='text-align:justify'>if You include all or a substantial portion of the database contents in a database in which You have Sui Generis Database Rights, then the database in which You have Sui Generis Database Rights (but not its individual contents) is Adapted Material, including for purposes of Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3b'>3(b)</a>; and</p>
1. <p style='text-align:justify'>You must comply with the conditions in Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s3a'>3(a)</a> if You Share all or a substantial portion of the contents of the database.</p>

For the avoidance of doubt, this Section [4](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s4) supplements and does not replace Your obligations under this Public License where the Licensed Rights include other Copyright and Similar Rights.

**Section 5 -- Disclaimer of Warranties and Limitation of Liability.**

1. <p style='text-align:justify'>Unless otherwise separately undertaken by the Licensor, to the extent possible, the Licensor offers the Licensed Material as-is and as-available and makes no representations or warranties of any kind concerning the Licensed Material, whether express, implied, statutory, or other. This includes, without limitation, warranties of title, merchantability, fitness for a particular purpose, non-infringement, absence of latent or other defects, accuracy, or the presence or absence of errors, whether or not known or discoverable. Where disclaimers of warranties are not allowed in full or in part, this disclaimer may not apply to You.</p>
1. <p style='text-align:justify'>To the extent possible, in no event will the Licensor be liable to You on any legal theory (including, without limitation, negligence) or otherwise for any direct, special, indirect, incidental, consequential, punitive, exemplary, or other losses, costs, expenses, or damages arising out of this Public License or use of the Licensed Material, even if the Licensor has been advised of the possibility of such losses, costs, expenses, or damages. Where a limitation of liability is not allowed in full or in part, this limitation may not apply to You.</p>
1. <p style='text-align:justify'>The disclaimer of warranties and limitation of liability provided above shall be interpreted in a manner that, to the extent possible, most closely approximates an absolute disclaimer and waiver of all liability.</p>

**Section 6 -- Term and Termination.**

1. <p style='text-align:justify'>This Public License applies for the term of the Copyright and Similar Rights licensed here. However, if You fail to comply with this Public License, then Your rights under this Public License terminate automatically.</p>
1. <p style='text-align:justify'>Where Your right to use the Licensed Material has terminated under Section 6(a), it reinstates:</p>

   1. <p style='text-align:justify'>automatically as of the date the violation is cured, provided it is cured within 30 days of Your discovery of the violation; or</p>
   1. <p style='text-align:justify'>upon express reinstatement by the Licensor.</p> <p style='text-align:justify'>For the avoidance of doubt, this Section <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s6b'>6(b)</a> does not affect any right the Licensor may have to seek remedies for Your violations of this Public License.</p>

1. <p style='text-align:justify'>For the avoidance of doubt, the Licensor may also offer the Licensed Material under separate terms or conditions or stop distributing the Licensed Material at any time; however, doing so will not terminate this Public License.</p>
1. <p style='text-align:justify'>Sections <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s1'>1</a>, <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s5'>5</a>, <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s6'>6</a>, <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s7'>7</a>, and <a href='https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode.en#s8'>8</a> survive termination of this Public License.</p>

**Section 7 -- Other Terms and Conditions.**

1. <p style='text-align:justify'>The Licensor shall not be bound by any additional or different terms or conditions communicated by You unless expressly agreed.</p>
1. <p style='text-align:justify'>Any arrangements, understandings, or agreements regarding the Licensed Material not stated herein are separate from and independent of the terms and conditions of this Public License.</p>

**Section 8 -- Interpretation.**

1. <p style='text-align:justify'>For the avoidance of doubt, this Public License does not, and shall not be interpreted to, reduce, limit, restrict, or impose conditions on any use of the Licensed Material that could lawfully be made without permission under this Public License.</p>
1. <p style='text-align:justify'>To the extent possible, if any provision of this Public License is deemed unenforceable, it shall be automatically reformed to the minimum extent necessary to make it enforceable. If the provision cannot be reformed, it shall be severed from this Public License without affecting the enforceability of the remaining terms and conditions.</p>
1. <p style='text-align:justify'>No term or condition of this Public License will be waived and no failure to comply consented to unless expressly agreed to by the Licensor.</p>
1. <p style='text-align:justify'>Nothing in this Public License constitutes or may be interpreted as a limitation upon, or waiver of, any privileges and immunities that apply to the Licensor or You, including from the legal processes of any jurisdiction or authority.</p>

