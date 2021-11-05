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
