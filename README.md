# OSSEM Detection Model (DM)

[![Open Source Love](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
![Open_Threat_Research Community](https://img.shields.io/badge/Open_Threat_Research-Community-brightgreen.svg)
[![Twitter](https://img.shields.io/twitter/follow/OSSEM_Project.svg?style=social&label=Follow)](https://twitter.com/OSSEM_Project)

This part of the project focuses on defining the required data in form of data objects and the relationships among each other needed to facilitate the creation of data analytics and validate the detection of adversary techniques. We have also extended this concept to the MITRE-ATT&CK framework [here)](docs/mitre_attack).

## Available documents
|File|Description|
|---|---|
|[OSSEM Event Mappings (YAML file)](relationships/_all_ossem_relationships.yml)|Security event logs mapped to OSSEM relationships (Includes ATT&CK data sources metadata)||
|[ATT&CK Data Sources Definitions](docs/mitre_attack/data_sources_definition.md)|Official definitions extracted from the ATT&CK framework||
|[ATT&CK Event Mappings (MD file)](docs/mitre_attack/attack_events_mappings.md)|Security event logs mapped to ATT&CK Data Sources Objects||
|[ATT&CK Event Mappings (YAML file)](docs/mitre_attack/attack_relationships.yml)|Security event logs mapped to ATT&CK Data Sources Objects||
|[ATT&CK Event Mappings (CVS file)](docs/mitre_attack/attack_events_mappings.csv)|Security event logs mapped to ATT&CK Data Sources Objects||

## References
* [Defining ATT&CK Data Sources, Part I: Enhancing the Current State](https://medium.com/mitre-attack/defining-attack-data-sources-part-i-4c39e581454f)
* [Defining ATT&CK Data Sources, Part II: Operationalizing the Methodology](https://medium.com/mitre-attack/defining-attack-data-sources-part-ii-1fc98738ba5b)
* [ATT&CK Data Sources GitHub repository](https://github.com/mitre-attack/attack-datasources)
* [CAR Analytics](https://car.mitre.org/wiki/Main_Page)
* [Common Information Model](https://github.com/Cyb3rWard0g/OSSEM/blob/master/common_information_model)
* [STIX Cybox ObjectRelationshipVOcab-1.1](http://stixproject.github.io/data-model/1.2/cyboxVocabs/ObjectRelationshipVocab-1.1/)
* [Cybox Object](http://cyboxproject.github.io/documentation/objects/)
* [STIX Version 2.0. Part 4 - Cyber Observable Object](https://docs.oasis-open.org/cti/stix/v2.0/stix-v2.0-part4-cyber-observable-objects.html)
* [Finding Cyber Threats with ATTCK Based Analytics](https://www.mitre.org/sites/default/files/publications/16-3713-finding-cyber-threats%20with%20att%26ck-based-analytics.pdf)
* [CAR Analytics Data Model](https://car.mitre.org/wiki/Data_Model)
* [Quantifying your hunt - not your parent's red teaming](http://www.irongeek.com/i.php?page=videos/bsidescharm2018/track-1-06-quantify-your-hunt-not-your-parents-red-teaming-devon-kerr)