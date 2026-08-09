# OSINT & Digital Forensics Investigation

> A practical cybersecurity project exploring how Open-Source Intelligence (OSINT) tools can support digital crime investigations through entity mapping, infrastructure discovery, and investigative analysis.

![Cybersecurity](https://img.shields.io/badge/Domain-Cybersecurity-red)
![OSINT](https://img.shields.io/badge/Focus-OSINT-blue)
![Digital Forensics](https://img.shields.io/badge/Focus-Digital%20Forensics-purple)
![Maltego](https://img.shields.io/badge/Tool-Maltego-orange)
![Shodan](https://img.shields.io/badge/Tool-Shodan-black)

Introduction

OSINT formally known as Open-Source intelligence is a tool used to gather publicly available information from a large number of sources such as social media platforms, news articles, websites and databases. Within investigating digital crime OSINT can help to uncover valuable intelligence to support law enforcement in identifying criminal activity and can be used in the chain of custody to gain convictions. The use of OSINT tools can help to track online behaviour uncovering connections between criminals and monitor emerging threats in real time. The accessible nature of OSINT as an open source make it cost efficient method to gather intelligence without breaching privacy laws. In this report there will be an examination of the effectiveness and practical applications of OSINT tools in digital crime investigations. The report aims to evaluate how platforms that are OSINT assist in gathering open-source data to support investigative decision making.

Methodology

The methodology will be a mix of qualitative research and technical evaluation of selected OSINT tools that can be used in digital forensics investigations. Data collection cane be publicly available from diverse sources whilst maintaining operational security. The first time of collection will be passive collection osint from scraping websites, using APIs (Twitter, LinkedIn) or deep web sources. There is the need to monitor public social media posts, analyse GitHub repositories and active scraping of public records. The next time of collection would be semi-passive collection using automated reconnaissance tools that stimulate regular browsing patterns. This will encompass sending traffic that mimics normal internet behaviour to forbidden by law information while staying undetected. Then the final method is active collection so direct probing with targets (ports scans, vulnerability assessments and social engineering, entailing network scanning, friend requests to private profiles and direct messaging (Gill, 2023).
 The focus will be on the tool’s usability, functionality and integration of these tools used for investigations of digital crimes. The primary tools used in OSINT investigations include:
•	Maltego used for network mapping
•	Shodan for device discovery
•	Google Dorks for targeted web searches
•	Social media scraping tools used for online presence analysis.
These tools work in conjunction with each other and there will be a comparative approach assessing how they all collect and process data from various open sources to help to identify:
•	Identifying threat actors
•	Mapping digital infrastructures
•	Uncovering entities such as domains, IP addresses, email account and analysing the relationships between them (Hassan, 2025).
Comparison of two major tools
Below is a comparison table of two major OSINT tools used to conduct digital crime investigations. The table highlights the benefits and the impacts.
Tool	Benefits	Impacts

Maltego	GLA (graphical link analysis): Visualises relationships between entities for easier interpretation. 

OSINT integration: Pulls data from social media, WHOIS, DNS, breach database.

Transforms: Automates expansion of leads into connected entities.

Collaboration: Teams can share investigation graphs (cybervie, 2021).	Steep learning curve: Requires training to use effectively.

Limited free edition: Community version restricts results per transform.

Dependent on data sources: Quality of results depends on connected APIs and datasets.

Resource intensive: Graphs can become complex and heavy to process.

Shodan	Device discovery: Identifies exposed IoT, servers and industrial systems.

Real time exposure monitoring: Helps track network assets visible on the internet.

Simple queries: Easy to search by port or organisation (djekic, 2023).	Surface-level data: Focuses on banners and metadata and not deep relationships.

Snapshot-based: May not reflect current device status.

Potential false positives: Results can be outdated or misclassified (djekic, 2023).








The methodology diagram below describes the best process taken to choose a tool to conduct a digital forensic investigation. 
 
Figure 1. Methodology diagram

<img width="613" height="474" alt="a1" src="https://github.com/user-attachments/assets/a94a07c8-7401-454d-a72b-77083fbb49a5" />



Findings and scenarios
After careful consideration the chosen OSINT tool suitable for investigating an alias by the name of Faisal Saleem is Maltego. The reason for selecting this tool to is because it’s a powerful tool for link analysis as it allows mapping relationships, organisation and digital entities as in this case. It’s a tool that is widely used by the cybersecurity and law enforcement agencies because it can help to show any hidden connections quickly. The entity mapping means that an investigator can start with one lead such as a name as an entity and then expand into connected domains or accounts. The system integrates with external data providers such as WHOSIS and social media. The visualisations tools such as interactive graphs make complex investigations much easier to interpret. 

OSINT investigation process and flowchart

The diagram below illustrates a systematic investigation process for using Maltego with three main phases. The first phase is configuration of the Maltego parameters and tools for the Faisal Saleem investigation. The next phase is the data collection stage involving gathering and analysing social media information, particularly Instagram profiles. The last phase is the analysis and verification stage validating findings and generating reports.
 
Figure 2. the investigative work flow diagram


<img width="614" height="182" alt="a2" src="https://github.com/user-attachments/assets/9d51b581-de75-46bc-9497-f003a65efca9" />


List of transforms/plugins for data mining- this allows access to various types of application servers using the data hub.


 
Figure 3. Maltego main screen


<img width="581" height="284" alt="a3" src="https://github.com/user-attachments/assets/3ab3cc2e-ae61-40a9-a166-489766b6bf83" />



Here is an example of a transform, which allows web developers to feature special information in web searches.
 
Figure 4. Maltego, transform is one of the options in the entity palette


<img width="580" height="244" alt="a4" src="https://github.com/user-attachments/assets/56bdca64-0a8e-40aa-8b1e-c0fc8b9f8258" />


Once you have selected the plugins you can perform your search by selecting a new graph from the menu and is accessed like this.
 
Figure 5.Maltego, create new graph tab


<img width="601" height="231" alt="a5" src="https://github.com/user-attachments/assets/f7f2f9a3-911b-47f6-84ad-08d1fdbf0727" />



A blank graph will appear allowing you to start a new case.
 
Figure 6.Maltego, new graph screen


<img width="614" height="252" alt="a6" src="https://github.com/user-attachments/assets/aff23a53-d038-4dfc-bbb1-2ce5526a69da" />

The next step is to access the entity palette and if you are conducting an investigation on a person(entity) then you can type person to get the drag and drop icon to begin the mapping process, which shown below.
 
Figure 7. Maltego, entity search


<img width="556" height="210" alt="a7" src="https://github.com/user-attachments/assets/49251673-86dd-4e72-9e10-2eb5e2f3b54e" />


Once we have dragged and dropped the person entity from the palette on to the graph, we can then add the name of the entity we wish to find out the information on as shown below.
 
Figure 8. Maltego, entity ready for investigation


<img width="565" height="216" alt="a8" src="https://github.com/user-attachments/assets/f255d99e-ada3-4546-bd21-ea55ef78b4da" />


The next step is to right click onto the person entity where the list of plugins/ transforms is available to conduct searches. Which is shown below:
 
Figure 9. Maltego, select plugin


<img width="555" height="130" alt="a9" src="https://github.com/user-attachments/assets/4f36fc77-0e82-4bcd-a3b0-5491c7582059" />


Select to run all datasets transforms as seen below
 
Figure 10. Maltego datasets transforms


<img width="602" height="222" alt="a10" src="https://github.com/user-attachments/assets/07008195-26a7-440d-8d17-d76fa2c71c58" />


9.	Select to run all datasets transforms will show all the alias under the name faisal saleem.
 
Figure 11. Maltego, alias mapping



<img width="612" height="253" alt="a11" src="https://github.com/user-attachments/assets/037c08ba-e84b-4d6b-b21f-9b31a98e2253" />


If we choose to a search for all GitHub profiles under this name, in the same way you click the plugin and press enter and a new map is made as seen below showing all the GitHub in the name Faisal saleem.
 
Figure 12. Maltego, GitHub search under alias names


<img width="566" height="294" alt="a12" src="https://github.com/user-attachments/assets/bce90a82-0497-41e9-b6dc-990e707db94e" />

Below is another search for everybody Instagram profiles with this name (Faisal Saleem).  


Figure 13.Maltego, Instagram search under alias name

Discussion of results (or Analysis or Interpretation)

Analysing the finding of Maltego it is correct to say that Maltego is a magnifying glass for investigators as they can start with a single clue such as a suspicious domain and you can uncover entire networks related to the entity. This makes it an excellent tool for threat intelligence and digital forensics. Upon successful completion of the investigation the alias social media profile could be accessed to gain credible open-source intelligence to make a profile for the chain of custody with evidence to incriminate if necessary.
  
Conclusions and Recommendations

During the investigation phase, using Maltego and search using alias faisal saleem it’s evident that the tool uses sophisticated algorithms to identify and map relationships across media platforms thus creating detailed visual maps. This is advantageous as the platforms automated capabilities allow for large datasets to be processed quickly saving time in investigations and better productivity. The platform leverages technology to analyse social media presence in particular Instagram in this case by collecting and analysing profile information and metadata. 



