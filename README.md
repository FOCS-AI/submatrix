# submatrix
A dataset of publicly available physical optical network connections (subsea cables)


## Overview 
- Internet Backbone, List and Visualisation of Submarine Networks (Optical Fiber Cables) under the sea for connecting continents 
- Data Source: https://cablemap.info/_default.aspx
- Converted Using: https://mygeodata.cloud/
- Found on https://en.wikipedia.org/wiki/Internet_backbone#/media/File:Submarine_cable_map_umap.png

## Data Types 
- KML (Original) 
- GeoJSON (In this repository) 

## CableMap
- KML: Originally downloaded from https://cablemap.info/_default.aspx

<img width="1669" alt="image" src="https://github.com/FOCS-AI/submarine-networks/assets/8778046/4f691c40-edd5-4116-b8ba-772d8a6dd2d1"> 


## Infrapedia 
- Latest Crowdsourced Data is now maintained at: https://www.infrapedia.com/ but is unavailable for download.

<img width="1669" alt="image" src="https://github.com/FOCS-AI/submarine-networks/assets/8778046/27bb13be-8924-49a1-bbcb-53076cb60084">

## TeleGeography
- Submarine Cable Map: The Submarine Cable Map is based on the authoritative data found in TeleGeography’s Transport Networks Research Service.
- As of early 2023, we believe there are nearly 1.4 million kilometers of submarine cables in service globally.
- Some cables are quite short, like the 131 kilometer CeltixConnect cable between Ireland the United Kingdom. In contrast, others are incredibly long, such as the 20,000 kilometer Asia America Gateway cable.
- FAQ https://www2.telegeography.com/submarine-cable-faqs-frequently-asked-questions?__hstc=196094579.1852b6f62ae5461a699aa7e80e055c6a.1620827506168.1626126220956.1626139254572.81&__hssc=196094579.1.1626139254572&__hsfp=3839890209
- Map https://www.submarinecablemap.com/

<img width="1669" alt="image" src="https://github.com/FOCS-AI/submarine-networks/assets/8778046/9a7f34ae-bd36-41fd-b918-3ce26cdf47d3">



## Our repository
- GeoJSON: Each Cable Network downloaded from cable maps has its geoJSON file and has been converted using https://mygeodata.cloud/.
- We use Folium to generate interactive maps for visualising the network. 

## List of Cables: 
- To assess if links are active or decommissioned, check Infrapedia. However, their data is also crowdsourced, so it might only be somewhat reliable. 

| Cable Network | File Format |
|-|-|
| AAE_1_Asia_Africa_Europe | .geojson |
| AAG_Asia_American_Gateway | .geojson |  
| ACE | .geojson |
| AC_1 | .geojson |
| AC_2 | .geojson |
| ADRIA_1 | .geojson |
| AEConnect | .geojson |
| AKORN_Alaska_Oregon | .geojson |
| ALBA_1 | .geojson |
| ALETAR | .geojson |
| ALPAL_2 | .geojson |
| ANTILLAS_I | .geojson |
| APCN | .geojson |
| APCN2 | .geojson |
| APG_Asia_Pacific_Gateway | .geojson |
| APHRODITE_2 | .geojson |
| APNG_2 | .geojson |
| APX_East | .geojson |
| APX_West | .geojson |
| ARCOS_1 | .geojson |  
| ASH_American_Samoa_Hawaii | .geojson |
| ATLANTIS_2 | .geojson |
| Alaska_United_East | .geojson |
| Alaska_United_West | .geojson |
| Alexandros | .geojson |
| Alonso_de_Ojeda | .geojson |
| America_Movil_1 | .geojson |
| Americas_1_North | .geojson |
| Americas_1_South | .geojson |
| Americas_II | .geojson |
| Amerigo_Vespucci | .geojson |
| Antilles_Crossing | .geojson |
| Apollo | .geojson |
| Arctic_Fibre | .geojson |
| Ariane_2 | .geojson |
| Asia_Submarine_Express_ASE | .geojson |
| Atlas_Offshore | .geojson |
| Australia_Japan_Cable | .geojson |
| Australia_Singapore_Cable | .geojson |
| BAHAMAS_2 | .geojson |
| BALTICA | .geojson |
| BARSAV | .geojson |
| BBG_Bay_of_Bengal_Gateway | .geojson |
| BCS_East | .geojson |
| BCS_East_West_Interlink | .geojson |
| BCS_North_I | .geojson |
| BCS_North_II | .geojson |
| BDNSi | .geojson |
| BERYTAR | .geojson |
| BICS | .geojson |
| BP_Fiber_Backbone | .geojson |
| BRICS_Cable | .geojson |
| BSFOCS | .geojson |
| BT_MT1 | .geojson |
| BT_Manx_NI | .geojson |
| Balkans_Italy_Network | .geojson |
| Basslink_Telecom | .geojson |
| Bharat_Lanka_Cable_System | .geojson |  
| Bicentenario | .geojson |
| Botnia | .geojson |
| CADMOS | .geojson |
| CANTAT_3 | .geojson |
| CANUS_1 | .geojson |
| CBUS | .geojson |
| CC4 | .geojson |
| CC5 | .geojson |
| CFX_1 | .geojson |
| CIOS | .geojson |
| CIRCE_North | .geojson |
| CIRCE_South | .geojson |
| COLUMBUS_II | .geojson |
| COLUMBUS_III | .geojson |
| CORSAR_Corsica_Sardinia | .geojson |
| CUCN | .geojson |
| C_Lion | .geojson |
| CanaLink | .geojson |
| Caucasus_Cable_System | .geojson |
| Cayman_Jamaica | .geojson |
| CeltixConnect | .geojson |
| Challenger | .geojson |
| Concerto_1 | .geojson |
| Corfu_Bar | .geojson |
| Danica_North | .geojson |
| Danica_South | .geojson |
| Danice_submarine_cable | .geojson |
| Denmark_Germany_2 | .geojson |
| Denmark_Norway_5 | .geojson |
| Denmark_Norway_6 | .geojson |
| Denmark_Poland_2 | .geojson |
| Denmark_Sweden_15 | .geojson |
| Denmark_Sweden_16 | .geojson |
| Dumai_Melaka | .geojson |
| EAC | .geojson |
| EASSY | .geojson |
| ECFS | .geojson |
| EESF_2_Finland_Estonia_2 | .geojson |
| EESF_3_Finland_Estonia_3 | .geojson |
| EIG | .geojson |
| ESAT_1 | .geojson |
| ESAT_2 | .geojson |
| Emerald_Bridge_Fibres | .geojson |
| Estepona_Tetuan | .geojson |
| Estonia_Sweden_1 | .geojson |
| FARICE_1 | .geojson |
| FARLAND | .geojson |
| FLAG_ATLANTIC_NORTH | .geojson |
| FLAG_Alcatel_Lucent_Optical_Network_FALCON | .geojson |
| FLAG_Atlantic_FA_1 | .geojson |
| FLAG_Europe_Asia_FEA | .geojson |
| FLAG_North_Asia_Loop_FNAL | .geojson |
| FOG_Fibre_Optic_Gulf | .geojson |
| Far_East_Submarine_Cable_System | .geojson |
| Fehmarn_Belt | .geojson |
| Fibralink | .geojson |
| Finland_Sweden_4_SFS_4 | .geojson |
| Flores_Covo_Cable_System | .geojson |
| GLO1 | .geojson |
| GO_1 | .geojson |
| G_P | .geojson |
| Gemini | .geojson |  
| Georgia_Russia | .geojson |
| Global_Carribean_Network_GCN | .geojson |
| GlobeNet | .geojson |
| Gondwana_1 | .geojson |
| Greenland_Connect | .geojson |
| Gulf_Bridge_International | .geojson |
| HANNIBAL | .geojson |
| HANTRU_1 | .geojson |
| HAWK | .geojson |
| HONOTUA_Domestic | .geojson |
| HONOTUA_International | .geojson |
| HUGO | .geojson |
| Hawaiki | .geojson |
| Hibernia_Atlantic | .geojson |
| Hibernia_Express | .geojson |
| Hokkaido_Sakhalin_Cable_System_HSCS | .geojson |
| ITUR | .geojson |
| I_ME_WE | .geojson |
| Islalink | .geojson |
| Italy_Albania | .geojson |
| Italy_Greece | .geojson |
| Italy_Libya | .geojson |
| JAKABARE | .geojson |
| JONAH | .geojson |
| Japan_US | .geojson |
| KAFOS | .geojson |
| KINYRAS | .geojson |
| Kategat_1 | .geojson |
| Kodiak_Kenai | .geojson |
| Korea_Japan_Cable_Network_KJCN | .geojson |
| Kuwait_Iran | .geojson |
| LANIS_1 | .geojson |
| LANIS_2 | .geojson |
| LEV | .geojson |
| LIME | .geojson |
| LION | .geojson |
| LION2 | .geojson |
| Landing_Points | .geojson |
| Loukkos | .geojson |
| MAYA_1 | .geojson |
| MCT_Cable_System | .geojson |
| MENA | .geojson |
| MINERVA | .geojson |
| MONET | .geojson |
| MainOne | .geojson |
| Matrix_cable_system | .geojson |
| MedNautilus | .geojson |
| Med_Cable | .geojson |
| Melita_1 | .geojson |
| Mid_Atlantic_Crossing_MAC | .geojson |
| Moana | .geojson |
| Moratelindo_Batam_Dumai_Cable_MBDC | .geojson |
| Moratelindo_International_Cable_MIC_1 | .geojson |
| NorSea_Com_1 | .geojson |
| NorthStar | .geojson |
| PAN_AM | .geojson |
| PCCS | .geojson |
| PC_1 | .geojson |
| PPC_1 | .geojson | 
| Pan_American_Crossing_PAC | .geojson |
| Pangea_Baltic_Loop | .geojson |
| Pangea_North | .geojson |
| Pangea_South | .geojson |
| Pencan_6 | .geojson |
| Pishgaman_Oman_Iran_POI | .geojson |
| Qatar_UAE_Submarine_Cable_System | .geojson |
| RIOJA_3 | .geojson |
| RJK | .geojson |
| RNAL | .geojson |
| ROTACS | .geojson |
| Russia_Japan_Cable_Network_RJCN | .geojson |
| SACS | .geojson |
| SAFE | .geojson |
| SAS_1 | .geojson |
| SAS_Samoa_American_Samoa | .geojson |
| SAT_2 | .geojson |
| SAT_3 | .geojson |
| SAex | .geojson |
| SAm_1 | .geojson |
| SEACOM | .geojson |
| SEAK | .geojson |
| SEAS | .geojson |
| SEA_ME_WE_3 | .geojson |  
| SEA_ME_WE_4 | .geojson |
| SEA_ME_WE_5 | .geojson |
| SHEFA_2 | .geojson |
| SJC | .geojson |
| SLT_Dhiraagu | .geojson |
| SMPR_1 | .geojson |
| SOLAS | .geojson |
| Scandinavian_Ring_North | .geojson |
| Scandinavian_Ring_South | .geojson |
| Seabras_1 | .geojson |
| Silphium | .geojson |
| Sirius_North | .geojson |
| Sirius_South | .geojson |
| South_American_Crossing_SAC | .geojson |
| Southern_Cross | .geojson |
| Suriname_Guyana_SG_SCS | .geojson |
| Svalbard_Undersea_Cable_System | .geojson |
| Sweden_Finland_Link_SFL | .geojson |
| TAGIDE_2 | .geojson |
| TAT_14 | .geojson |
| TEAMS | .geojson |
| TE_North | .geojson |
| TGN_Atlantic | .geojson |
| TGN_Gulf | .geojson |
| TGN_Northern_Europe | .geojson | 
| TGN_Transpacific | .geojson |
| TGN_Western_Europe | .geojson |
| TPC_5CN | .geojson |
| TSE_1 | .geojson |
| TURCYOS_1 | .geojson |
| TURCYOS_2 | .geojson |
| TURMEOS_1 | .geojson |
| Tamares_Telecom | .geojson |
| Tangerine | .geojson |
| Tasman_2 | .geojson |
| Tasman_Global_Access | .geojson |
| Tata_Indicom_TIISCS | .geojson |
| Tata_TGN_Intra_Asia_TGN_IA | .geojson |
| Telstra_Bass_Strait_1 | .geojson |
| Telstra_Bass_Strait_2 | .geojson |
| Telstra_Endeavour | .geojson |
| Thailand_Indonesia_Singapore_TIS | .geojson |
| Thailand_Vietnam_Hong_Kong_T_V_H | .geojson |
| Tonga_Fiji | .geojson |
| Trans_Pacific_Express | .geojson |
| Transworld_TWA_1 | .geojson |
| Trapani_Kelibia_KELTRA_2 | .geojson |  
| Trident | .geojson |
| Trinidad_Curaco | .geojson |
| UGARIT | .geojson |
| UK_Channel_Isles_7 | .geojson |
| UK_Germany_6 | .geojson |
| ULYSSES | .geojson |
| ULYSSES_2 | .geojson |
| UNISUR | .geojson |
| Unity | .geojson |
| VMSCS | .geojson |
| Vanuatu_Fiji_Interchange_Cable_Network | .geojson |
| Ventspils_Farosund_Stockholm | .geojson |
| WACS | .geojson |
| WARF | .geojson |
| WASACE | .geojson |
| i2i | .geojson |

