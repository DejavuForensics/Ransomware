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

Antivírus | VirusShare_001627d61a1bde3478ca4965e738dc1e | VirusShare_075efef8c9ca2f675be296d5f56406fa | VirusShare_0dab86f850fd3dafc98d0f2b401377d5
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------

Bkav | HW32.Packed.5F17| 
MicroWorld-eScan | benign
CMC | benign
CAT-QuickHeal | TrojanPWS.Zbot.Gen
McAfee | PWS-Zbot.gen.ahc
Cylance | Unsafe
AegisLab | Troj.W32.Generic!c
TheHacker | Trojan/Spy.Zbot.gevq
K7GW | Trojan 
K7AntiVirus | Trojan 
Arcabit | Trojan.Razy.D2577F
Invincea | heuristic
Baidu | Win32.Trojan.WisdomEyes.16070401.9500.9999
NANO-Antivirus | Trojan.Win32.Panda.bdrtpq
F-Prot | W32/S-3ae86dea!Eldorado
Symantec | Packed.Generic.459
ESET-NOD32 | Win32/Spy.Zbot.AAO
TrendMicro-HouseCall | TSPY_ZBOT.SM14
Paloalto | generic.ml
ClamAV | Win.Trojan.Zbot-70175
Kaspersky | HEUR:Trojan.Win32.Generic
BitDefender | Gen:Variant.Razy.153471
Babable | benign
SUPERAntiSpyware | Trojan.Agent/Gen-Petya
Tencent | Win32.Trojan.Falsesign.K
Ad-Aware | Gen:Variant.Razy.153471
Emsisoft | Gen:Variant.Razy.153471 (B)
Comodo | TrojWare.Win32.PWS.ZBot.XD
F-Secure | Trojan:W32/Kamala.A
DrWeb | Trojan.PWS.Panda.2401
VIPRE | Virtool.Win32.Obfuscator.as!c (v)
TrendMicro | TSPY_ZBOT.SM14
McAfee-GW-Edition | PWS-Zbot.gen.ahc
Fortinet | W32/ZBOT.HL!tr
Sophos | Troj/Zbot-DHN
Ikarus Trojan-PWS.Win32.Zbot
Cyren | W32/S-3ae86dea!Eldorado
Jiangmin | benign
Webroot | W32.Infostealer.Zeus
Avira | TR/Crypt.XPACK.Gen7
MAX | malware (ai score=100)
Antiy-AVL | benign
Kingsoft | Win32.Malware.Generic.a.(kcloud)
Endgame | malicious (high confidence)
Microsoft | PWS:Win32/Zbot
ViRobot | Trojan.Win32.A.Zbot.322648
ZoneAlarm | HEUR:Trojan.Win32.Generic
Avast-Mobile | benign
AhnLab-V3 | Trojan/Win32.Foreign.R41177
ALYac | Gen:Variant.Razy.153471 
AVware | Virtool.Win32.Obfuscator.as!c (v)
TACHYON | benign
VBA32 | BScope.Trojan-Dropper.Injector
Malwarebytes | Trojan.Agent
Panda | Trj/Genetic.gen
Zoner | benign
Rising | Spyware.Zbot!8.16B (CLOUD)
Yandex | TrojanSpy.Zbot!DHIuP5NKKgg
SentinelOne | static engine - malicious
eGambit | benign
GData | Gen:Variant.Razy.153471
AVG | Win32:Karagany 
Cybereason | malicious.381d7d
Avast | Win32:Karagany
CrowdStrike | malicious_confidence_90% (W)
Qihoo-360 | Win32/Trojan.Spy.6ef



| HW32.Packed.58DF
| benign
| benign
| benign
| Trojan.IGENERIC
| Artemis!000ADC56F2D8
| Unsafe
| Trojan.Win32.Generic.pak!cobra
| benign
| Trojan ( 000609311 )
| Trojan ( 000609311 )
| benign
| benign
Win32.Trojan.WisdomEyes.16070401.9500.9535
| benign
Trojan.Gen.2
Win32/Dragon_i
TROJ_GEN.R002H0CAH18', u'update': u'20180206'}, u'
generic.ml', u'update': u'20180206'}, u'
Win.Trojan.3973235-1', u'update': u'20180206'}, u'
GData': {u'detected': False, u'version': u'A:25.15932B:25.11523', u'result': None, u'update': u'20180206'}, u'
UDS:DangerousObject.Multi.Generic', u'update': u'20180206'}, u'
BitDefender': {u'detected': False, u'version': u'7.2', u'result': None, u'update': u'20180206'}, u'
Trojan.Win32.Fakealert.dxpstc', u'update': u'20180206'}, u'
Trojan.Win32.Z.Delf.2095298', u'update': u'20180206'}, u'
SUPERAntiSpyware': {u'detected': False, u'version': u'5.6.0.1032', u'result': None, u'update': u'20180206'}, u'
Rising': {u'detected': False, u'version': u'25.0.0.1', u'result': None, u'update': u'20180206'}, u'
Ad-Aware': {u'detected': False, u'version': u'3.0.3.1010', u'result': None, u'update': u'20180206'}, u'
Emsisoft': {u'detected': False, u'version': u'4.0.2.899', u'result': None, u'update': u'20180206'}, u'
UnclassifiedMalware', u'update': u'20180206'}, u'
Trojan.Fakealert.24993', u'update': u'20180206'}, u'
Trojan.Genome.Win32.136493', u'update': u'20180205'}, u'
TrendMicro': {u'detected': False, u'version': u'9.862.0.1074', u'result': None, u'update': u'20180206'}, u'
BehavesLike.Win32.Virus.tc', u'update': u'20180206'}, u'
Mal/Generic-S', u'update': u'20180206'}, u'
static engine - malicious', u'update': u'20180115'}, u'
Cyren': {u'detected': False, u'version': u'5.4.30.7', u'result': None, u'update': u'20180206'}, u'
Trojan/Agent.crau', u'update': u'20180206'}, u'
W32.Malware.Heur', u'update': u'20180206'}, u'
TR/Crypt.CFI.Gen', u'update': u'20180206'}, u'
Trojan/Win32.SGeneric', u'update': u'20180206'}, u'
Kingsoft': {u'detected': False, u'version': u'2013.8.14.323', u'result': None, u'update': u'20180206'}, u'
Microsoft': {u'detected': False, u'version': u'1.1.14500.5', u'result': None, u'update': u'20180206'}, u'
malicious (high confidence)', u'update': u'20171130'}, u'
Uds.Dangerousobject.Multi!c', u'update': u'20180206'}, u'
UDS:DangerousObject.Multi.Generic
Avast-Mobile': {u'detected': False, u'version': u'180206-00', u'result': None, u'update': u'20180206'}, u'
AhnLab-V3': {u'detected': False, u'version': u'3.11.3.19504', u'result': None, u'update': u'20180206'}, u'
ALYac': {u'detected': False, u'version': u'1.1.1.5', u'result': None, u'update': u'20180206'}, u'
Trojan.Win32.Generic.pak!cobra
MAX': {u'detected': False, u'version': u'2017.11.15.1', u'result': None, u'update': u'20180206'}, u'
Trojan.Delf
Malware.HighConfidence
Panda': {u'detected': False, u'version': u'4.6.4.2', u'result': None, u'update': u'20180206'}, u'
a variant of Win32/Delf.NRC
Win32.Trojan.Crypt.K
Trojan.Delf!msDHBXVvuuM
Virus.Win32.Parite
eGambit': {u'detected': False, u'version': u'v4.3.0', u'result': None, u'update': u'20180206'}, u'
Fortinet': {u'detected': False, u'version': u'5.4.247.0', u'result': None, u'update': u'20180206'}, u'
Win32:Trojan-gen
| benign
Win32:Trojan-gen
malicious_confidence_90% (W)
Win32/Trojan.5d4

## Materials and Methods

This paper proposes a database aiming at the classification of 32-bit benign and malware executables. There are  1,050 malicious executables, and 1,050 other benign executables. Therefore, our dataset is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

Virtual plagues were extracted from databases provided by enthusiastic study groups as VirusShare. As for benign executables, the acquisition came from benign applications repositories such as sourceforge, github and sysinternals. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The purpose of the creation of the database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, the proposed article, by making its database freely available, enables transparency and impartiality to research, as well as demonstrating the veracity of the results achieved. Therefore, it is hoped that the methodology will serve as a basis for the creation of new scientific works.
