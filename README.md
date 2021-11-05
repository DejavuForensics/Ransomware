# Ransomware
Retrieval for Ransomware Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 89 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 89 commercial antiviruses with their respective results presented in Table 1. We used  1,050 malicious executables for 32-bit architecture. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 1 shows the results of the evaluated 89 antivirus products. Two of these antiviruses scored above 99%. These antiviruses were: BitDefender, MicroWorld-eScan. Malware detection indicates that these antivirus programs provide a robust service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 1 analyse, the proposed work points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 99.52%, depending on the antivirus being investigated. On average, the 89 antiviruses were able to detect 68.30% of the evaluated virtual pests, with a standard deviation of 27.83%. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, the Zoner antivirus wrongly stated that malware was benign in more than 90% of cases. On average, antiviruses attested false negatives in 17.76% of the cases, with a standard deviation of 18.41%. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

On average, the antiviruses were missing in 13.94% of the cases, with a standard deviation of 18.37%. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 2. We choose 3 of  1,050 malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "Malware.1" and a second company identify it as "Malware12310". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.


###### Table 2 Results of 89 commercial antiviruses:

Antivirus | Deteccion (%) | False Negative (%) | Omission (%)
--------- | ------------- | ------------------ | -------------
McAfee|97.63% |2.29% |0.07% |
McAfee-GW-Edition|97.26% |2.43% |0.29% |
Kaspersky| 95.04% |4.50% |0.44% |
BitDefender|94.53% |5.09% |0.36% |
GData|94.38% |5.02% |0.59% |
Avast |94.16% |5.46% |0.36% |
AVG|94.16% |5.61% |0.22% |
Symantec |93.05% |6.43% |0.51% |
Sophos|92.90% |6.06% |1.03% |
Panda|92.75% |6.87% |0.36% |
Microsoft|91.94% |7.31% |0.73% |
Ikarus|91.86% |2.95% |5.17% |
Fortinet|91.72% |8.13% |0.14% |
Emsisoft|91.57% |7.76% |0.66% |
ESET-NOD32|91.57% |6.79% |1.62% |
DrWeb|90.90% |7.98% |1.10% |
NANO-Antivirus|90.83% |6.06% |3.10% |
MicroWorld-eScan | 89.43%  | 8.42%  | 2.14%  |
F-Secure|89.35% |7.90% |2.73% |
VIPRE|88.76% |5.76% |5.46% |
TrendMicro-HouseCall |85.80% |11.97% |2.21% |
K7AntiVirus |85.58% |14.11% |0.29% |
AhnLab-V3|85.36% |12.93% |1.69% |
VBA32|84.92% |14.92% |0.14% |
TrendMicro|80.78% |15.74% |3.47% |
Antiy-AVL|80.78% |18.62% |0.59% |
Ad-Aware|80.41% |7.83% |11.75% |
K7GW | 80.41% |12.41% |7.16% |
Qihoo-360|78.71% |6.79% |14.48% |
Jiangmin|76.94% |22.69% |0.36% |
CAT-QuickHeal |76.79% |23.13% |0.07% |
F-Prot |73.83% |26.16% |0.0% |
Arcabit |70.95% |5.91% |23.13% |
Tencent|70.95% |8.35% |20.69% |
Cyren|70.36% |7.31% |22.32% |
Avira|69.40% |7.83% |22.76% |
Rising|69.32% |27.86% |2.80% |
MAX|67.55% |1.25% |31.18% |
ZoneAlarm|67.77% |2.36% |29.85% |
Endgame|66.14% |1.03% |32.81% |
AVware|66.14% |2.43% |31.41% |
Webroot|66.00% |2.51% |31.48% |
Zillya |64.59% |15.74% |19.66% |
Comodo|64.22% |31.04% |4.73% |
Yandex|63.41% |9.60% |26.97% |
AegisLab|63.19% |22.32% |14.48% |
Invincea |62.89% |7.53% |29.56% |
TheHacker |61.19% |38.65% | 0.14% |
Cylance|61.12% |2.36% |36.51% |
CrowdStrike|60.01% |3.69% |3.69% |
SentinelOne|58.53% |8.57% |32.88% |
ALYac |58.31% |16.70% |24.98% |
Malwarebytes |58.31% |37.17% |4.50% |
Baidu |57.28% |15.81% |26.90% |
SUPERAntiSpyware |56.46% |43.31% |0.22% |
ClamAV |50.33% |49.15% |0.51% |
ViRobot|46.85% |53.06% |0.07% |
Paloalto|44.05% |22.76% |33.18%|
Bkav | 41.09% | 45.45% | 13.45%| 
Kingsoft|39.09% |57.28% |3.62% |
TotalDefense |37.69% |59.34% |2.95% |
CMC | 25.94% |59.12%  | 14.92% |
nProtect  | 25.27% |25.86% |48.85% |
Norman|19.43% |3.69% |76.86% |
AntiVir|17.81% |4.43% |77.75% |
Agnitum|15.96% |8.79% |75.24% |
Commtouch|11.89% |10.05% |78.04% |
PCTools|7.83% |3.47% |88.69% |
Zoner|5.02% |73.31% |21.65% |
ByteHero|1.55% |23.72% |74.72% |
NOD32|1.40% |0.14% |98.44% |
WhiteArmor|1.18% |5.17% |93.64% |
VirusBuster|1.03% |0.88% |98.07% |
eTrust-Vet|0.73% |0.81% |98.44% |
eSafe|0.66% |7.61% |91.72% |
Sunbelt|0.22% |0.07% |99.70% |
Prevx|0.14% |1.10% |98.74% |
Authentium|0.14% |0.14% |99.70% |
a-squared|0.14% |0.0% |99.85% |
Alibaba|0.07% |22.46% |77.45% |
ahnlab|0.0% |0.0% |100.0% |
Command|0.0% |0.0% |100% |
SAVMail|0.0% |0.0% |100% |
FileAdvisor |0.0% |0.0% |100% |
Ewido |0.0% |0.0% |100% |
Webwasher-Gateway |0.0% |0.0% |100% |


###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus | VirusShare_000a3ea381d7d70be8b6fe1ee51dca22 | VirusShare_000adc56f2d8cd1f7b8f6b54912000e9 | VirusShare_000b28e7a5905b5bf3b80c6c60a5f828
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
Bkav | HW32.Packed.5F17| HW32.Packed.58DF | HW32.Packed. |
MicroWorld-eScan | benign| benign | Trojan.Generic.KDZ.5250 |
nProtect | omission | benign | omission |
CMC | benign| benign | benign |
CAT-QuickHeal | TrojanPWS.Zbot.Gen| Trojan.IGENERIC | TrojanPWS.Zbot.Gen |
McAfee | PWS-Zbot.gen.ahc | Artemis!000ADC56F2D8 | PWS-Zbot.gen.xd | 
Cylance | Unsafe | Unsafe | Unsafe |
AegisLab | Troj.W32.Generic!c | Uds.Dangerousobject.Multi!c | Troj.W32.Gen.lIUb |
VIPRE | Virtool.Win32.Obfuscator.as!c (v) | omission | Trojan.Win32.Agent.akm (v) |
TheHacker | Trojan/Spy.Zbot.gevq | benign | benign |
Alibaba | omission | omission | benign |
K7GW | Trojan  | Trojan ( 000609311 ) | Trojan ( 0040f07e1 ) |
K7AntiVirus | Trojan | Trojan ( 000609311 ) | Trojan ( 0040f07e1 ) |
Arcabit | Trojan.Razy.D2577F | benign | Trojan.Generic.KDZ.D1482 |
Invincea | heuristic | benign | heuristic |
Baidu | Win32.Trojan.WisdomEyes.16070401.9500.9999 | Win32.Trojan.WisdomEyes.16070401.9500.9535 | benign|
NANO-Antivirus | Trojan.Win32.Panda.bdrtpq | Trojan.Win32.Fakealert.dxpstc  | Trojan.Win32.Zbot.bobrkr|
F-Prot | W32/S-3ae86dea!Eldorado | benign | W32/Zbot.HR.gen!Eldorado |
Symantec | Packed.Generic.459 | Trojan.Gen.2 | Trojan.Zbot!g38 |
TotalDefense | omission | Win32/Dragon_i | benign |
ESET-NOD32 | Win32/Spy.Zbot.AAO | a variant of Win32/Delf.NRC | a variant of Win32/Kryptik.ASUX  |
TrendMicro-HouseCall | TSPY_ZBOT.SM14 | TROJ_GEN.R002H0CAH18 | TSPY_ZBPAK.SML |
Paloalto | generic.ml | generic.ml | generic.ml |
ClamAV | Win.Trojan.Zbot-70175 | Win.Trojan.3973235-1 | benign |
GData | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
Kaspersky | HEUR:Trojan.Win32.Generic | UDS:DangerousObject.Multi.Generic | HEUR:Trojan.Win32.Generic |
BitDefender | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
Babable | benign | omission | benign |
SUPERAntiSpyware | Trojan.Agent/Gen-Petya | benign | Trojan.Agent/Gen-FakeMS |
Rising | Spyware.Zbot!8.16B (CLOUD) | benign | Spyware.Zbot!8.16B (CLOUD) |
Tencent | Win32.Trojan.Falsesign.K | Win32.Trojan.Crypt.K | Win32.Trojan.Falsesign.L |
Ad-Aware | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
Emsisoft | Gen:Variant.Razy.153471 (B) | benign | Trojan.Generic.KDZ.5250 (B) |
Comodo | TrojWare.Win32.PWS.ZBot.XD | .UnclassifiedMalware | benign |
F-Secure | Trojan:W32/Kamala.A | omission | Trojan:W32/Kamala.A |
DrWeb | Trojan.PWS.Panda.2401 | Trojan.Fakealert.24993 | Trojan.PWS.Panda.3528 |
Zillya | omission | Trojan.Genome.Win32.136493 | Trojan.Zbot.Win32.120499 |
VIPRE | Virtool.Win32.Obfuscator.as!c (v) | omission | Trojan.Win32.Agent.akm (v) |
TrendMicro | TSPY_ZBOT.SM14 | benign | omission |
McAfee-GW-Edition | PWS-Zbot.gen.ahc | BehavesLike.Win32.Virus.tc | PWS-Zbot.gen.xd |
Fortinet | W32/ZBOT.HL!tr | omission | W32/Zbot.AAU!tr |
Sophos | Troj/Zbot-DHN | Mal/Generic-S | Troj/Zbot-DUZ |
SentinelOne | omission | static engine - malicious | static engine - malicious |
Ikarus | Trojan-PWS.Win32.Zbot | Virus.Win32.Parite | Trojan-Spy.Win32.Zbot |
Cyren | W32/S-3ae86dea!Eldorado | benign | W32/Zbot.HR.gen!Eldorado |
Jiangmin | benign | Trojan/Agent.crau | Trojan.Generic.abmlq |
Webroot | W32.Infostealer.Zeus | W32.Malware.Heur | W32.Infostealer.Zeus |
Avira | TR/Crypt.XPACK.Gen7 | TR/Crypt.CFI.Gen | TR/Pakes.lvqoue |
MAX | malware (ai score=100) | benign | malware (ai score=100) |
Antiy-AVL | benign | Trojan/Win32.SGeneric | Trojan[Spy]/Win32.Zbot |
Kingsoft | Win32.Malware.Generic.a.(kcloud) | benign | Win32.Troj.Zbot.il.(kcloud) |
Endgame | malicious (high confidence) | malicious (high confidence) | malicious (high confidence) |
Microsoft | PWS:Win32/Zbot | benign | omission |
ViRobot | Trojan.Win32.A.Zbot.322648 | Trojan.Win32.Z.Delf.2095298 |  benign |
ZoneAlarm | HEUR:Trojan.Win32.Generic | UDS:DangerousObject.Multi.Generic | HEUR:Trojan.Win32.Generic |
Avast-Mobile | benign | benign | benign |
AhnLab-V3 | Trojan/Win32.Foreign.R41177 | benign | Spyware/Win32.Zbot.R49955 |
ALYac | Gen:Variant.Razy.153471  | benign | Trojan.Generic.KDZ.5250 |
AVware | Virtool.Win32.Obfuscator.as!c (v) | Trojan.Win32.Generic.pak!cobra | Trojan.Win32.Agent.akm (v) |
TACHYON | benign | omission | Trojan-Spy/W32.ZBot.328184 |
VBA32 | BScope.Trojan-Dropper.Injector | Trojan.Delf | BScope.Malware-Cryptor.SB.01798 |
WhiteArmor | omission | Malware.HighConfidence | omission |
Malwarebytes | Trojan.Agent | omission | benign|
Panda | Trj/Genetic.gen | benign | Trj/Hexas.HEU |
Zoner | benign | omission | benign |
Yandex | TrojanSpy.Zbot!DHIuP5NKKgg | Trojan.Delf!msDHBXVvuuM | Trojan.Agent!v0Y1/43kpOQ |
eGambit | benign | benign | benign | 
AVG | Win32:Karagany | Win32:Trojan-gen | omission |
Cybereason | malicious.381d7d | benign | malicious.7a5905 |
Avast | Win32:Karagany | Win32:Trojan-gen | omission |
CrowdStrike | malicious_confidence_90% (W) | malicious_confidence_90% (W) | malicious_confidence_80% (D) |
Qihoo-360 | Win32/Trojan.Spy.6ef | Win32/Trojan.5d4 | HEUR/Malware.QVM20.Gen

## Materials and Methods

This paper proposes a database aiming at the classification of 32-bit benign and malware executables. There are  1,050 malicious executables, and 1,050 other benign executables. Therefore, our dataset is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

Virtual plagues were extracted from databases provided by enthusiastic study groups as VirusShare. As for benign executables, the acquisition came from benign applications repositories such as sourceforge, github and sysinternals. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The purpose of the creation of the database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, the proposed article, by making its database freely available, enables transparency and impartiality to research, as well as demonstrating the veracity of the results achieved. Therefore, it is hoped that the methodology will serve as a basis for the creation of new scientific works.
