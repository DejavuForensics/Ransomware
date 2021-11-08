# Ransomware
Retrieval for Ransomware Malware Analysis

## Commercial Antivirus Limitation

Technically, the modus operandi for the identification of malicious files and servers refers to consult in named blacklist databases. The VirusTotal platform issues the diagnoses regarding malignant characteristics related to files and web servers.

When it comes to suspicious files, VirusTotal issues the diagnostics provided by the world's leading commercial antivirus products. Regarding suspicious web servers, VirusTotal uses the database responsible for sensing virtual addresses with malicious practices.

VirusTotal has Application Programming Interface (APIs) that allow programmers to query the platform in an automated way and without the use of the graphical web interface. The proposed paper employs two of the APIs made available by VirusTotal. The first one is responsible for sending the investigated files to the platform server. The second API, in turn, makes commercial antivirus diagnostics available for files submitted to the platform by the first API.

Initially, the executable malwares are sent to the server belonging to the VirusTotal platform. After that, the executables are analyzed by the 86 commercial antiviruses linked to VirusTotal. Therefore, the antivirus provides its diagnostics for the executables submitted to the platform. VirusTotal allows the possibility of issuing three different types of diagnostics: malware, benign and omission.

Then, through the VirusTotal platform, the proposed paper investigates 86 commercial antiviruses with their respective results presented in Table 1. We used  1,174 malicious executables for 32-bit architecture. The goal of the work is to check the number of virtual pests cataloged by antivirus. The motivation is that the acquisition of new virtual plagues plays an important role in combating malicious applications. Therefore, the larger the database of malwares blacklisted, the better it tends to be the defense provided by the antivirus.

As for the first possibility of VirusTotal, the antivirus detects the malignity of the suspicious file. In the proposed experimental environment, all submitted executables are public domain malwares. Therefore, in the proposed study, the antivirus hits when it detects the malignity of the investigated executable. Malware detection indicates that the antivirus provides a robust service against cyber-intrusions. As larger the blacklist database, better tends to be the defense provided by the antivirus.

In the second possibility, the antivirus attests to the benignity of the investigated file. Therefore, in the proposed study, when the antivirus attests the benignity of the file, it is a case of a false negative – since all the samples are malicious. That is, the investigated executable is a malware; however, the antivirus attests to benignity in the wrong way.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

In the third possibility, the antivirus does not emit opinion about the suspect executable. The omission indicates that the file investigated has never been evaluated by the antivirus neither it has the robustness to evaluate it in real time. The omission of the diagnosis by the antivirus points to its limitation on large-scale services.

Table 1 shows the results of the evaluated 86 antivirus products. Two of these antiviruses scored above 97%. These antiviruses were: McAfee and McAfee-GW-Edition (same vendor). Malware detection indicates that these antivirus programs provide a robust service against cyber-intrusions.

A major adversity in combating malicious applications is the fact that antivirus makers do not share their malware blacklists due to commercial disputes. Through Table 1 analyse, the proposed work points to an aggravating factor of this adversity: the same antivirus vendor does not even share its databases between its different antivirus programs. Note, for example, that McAfee and McAfee-GW-Edition antiviruses belong to the same company. Their blacklists, though robust, are not shared with each other. Therefore, the commercial strategies of the same company hinder the confrontation with malware. It complements that antivirus vendors are not necessarily concerned with avoiding cyber-invasions, but with optimizing their business income.

Malware detection ranged from 0% to 97.63%, depending on the antivirus being investigated. On average, the 86 antiviruses were able to detect 55.22% of the evaluated virtual pests, with a standard deviation of 30.05%. The high standard deviation indicates that the detection of malicious executables may suffer abrupt variations depending on the antivirus chosen. It is determined that the protection, against cybernetic invasions, is due to the choice of a robust antivirus with a large and updated blacklist.

As for the false negatives, on average, antiviruses attested false negatives in 13.15% of the cases, with a standard deviation of 11.49%. Tackling the benignity of malware can lead to irrecoverable damage. A person or institution, for example, would rely on a particular malicious application when, in fact, it is malware.

On average, the antiviruses were missing in 31.71% of the cases, with a standard deviation of 31.88%. The omission of the diagnosis points to the limitation of these antiviruses that have limited blacklists for detection of malware in real time.

It is included as adversity, in the combat to malicious applications, the fact of the commercial antiviruses do not possess a pattern in the classification of the malwares as seen in Table 2. We choose 3 of  1,174 malwares samples in order to exemplify the miscellaneous classifications of commercial antiviruses. In this way, the time when manufacturers react to a new virtual plague is affected dramatically. As there is no a pattern, antiviruses give the names that they want, for example, a company can identify a malware as "HW32.Packed.5F17" and a second company identify it as " Uds.Dangerousobject.Multi!c". Therefore, the lack of a pattern, besides the no-sharing of information among the antivirus manufacturers, hinders the fast and effective detection of a malicious application.

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
ahnlab|0.0% |0.0% |100.00% |
Command|0.0% |0.0% |100.00% |
SAVMail|0.0% |0.0% |100.00% |
FileAdvisor |0.0% |0.0% |100.00% |
Ewido |0.0% |0.0% |100.00% |
Webwasher-Gateway |0.0% |0.0% |100.00% |


###### Table 3 Miscellaneous classifications of commercial antiviruses:

Antivírus | VirusShare_000a3ea381d7d70be8b6fe1ee51dca22 | VirusShare_000adc56f2d8cd1f7b8f6b54912000e9 | VirusShare_000b28e7a5905b5bf3b80c6c60a5f828
--------- | ------------------------------------------- | ------------------------------------------- | --------------------------------------------
McAfee | PWS-Zbot.gen.ahc | Artemis!000ADC56F2D8 | PWS-Zbot.gen.xd | 
McAfee-GW-Edition | PWS-Zbot.gen.ahc | BehavesLike.Win32.Virus.tc | PWS-Zbot.gen.xd |
Kaspersky | HEUR:Trojan.Win32.Generic | UDS:DangerousObject.Multi.Generic | HEUR:Trojan.Win32.Generic |
BitDefender | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
GData | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
Avast | Win32:Karagany | Win32:Trojan-gen | omission |
AVG | Win32:Karagany | Win32:Trojan-gen | omission |
Symantec | Packed.Generic.459 | Trojan.Gen.2 | Trojan.Zbot!g38 |
Sophos | Troj/Zbot-DHN | Mal/Generic-S | Troj/Zbot-DUZ |
Panda | Trj/Genetic.gen | benign | Trj/Hexas.HEU |
Microsoft | PWS:Win32/Zbot | benign | omission |
Ikarus | Trojan-PWS.Win32.Zbot | Virus.Win32.Parite | Trojan-Spy.Win32.Zbot |
Fortinet | W32/ZBOT.HL!tr | omission | W32/Zbot.AAU!tr |
Emsisoft | Gen:Variant.Razy.153471 (B) | benign | Trojan.Generic.KDZ.5250 (B) |
ESET-NOD32 | Win32/Spy.Zbot.AAO | a variant of Win32/Delf.NRC | a variant of Win32/Kryptik.ASUX  |
DrWeb | Trojan.PWS.Panda.2401 | Trojan.Fakealert.24993 | Trojan.PWS.Panda.3528 |
NANO-Antivirus | Trojan.Win32.Panda.bdrtpq | Trojan.Win32.Fakealert.dxpstc  | Trojan.Win32.Zbot.bobrkr|
MicroWorld-eScan | benign| benign | Trojan.Generic.KDZ.5250 |
F-Secure | Trojan:W32/Kamala.A | omission | Trojan:W32/Kamala.A |
VIPRE | Virtool.Win32.Obfuscator.as!c (v) | omission | Trojan.Win32.Agent.akm (v) |
TrendMicro-HouseCall | TSPY_ZBOT.SM14 | TROJ_GEN.R002H0CAH18 | TSPY_ZBPAK.SML |
K7AntiVirus | Trojan | Trojan ( 000609311 ) | Trojan ( 0040f07e1 ) |
AhnLab-V3 | Trojan/Win32.Foreign.R41177 | benign | Spyware/Win32.Zbot.R49955 |
VBA32 | BScope.Trojan-Dropper.Injector | Trojan.Delf | BScope.Malware-Cryptor.SB.01798 |
TrendMicro | TSPY_ZBOT.SM14 | benign | omission |
Antiy-AVL | benign | Trojan/Win32.SGeneric | Trojan[Spy]/Win32.Zbot |
Ad-Aware | Gen:Variant.Razy.153471 | benign | Trojan.Generic.KDZ.5250 |
K7GW | Trojan  | Trojan ( 000609311 ) | Trojan ( 0040f07e1 ) |
Qihoo-360 | Win32/Trojan.Spy.6ef | Win32/Trojan.5d4 | HEUR/Malware.QVM20.Gen |
Jiangmin | benign | Trojan/Agent.crau | Trojan.Generic.abmlq |
CAT-QuickHeal | TrojanPWS.Zbot.Gen| Trojan.IGENERIC | TrojanPWS.Zbot.Gen |
F-Prot | W32/S-3ae86dea!Eldorado | benign | W32/Zbot.HR.gen!Eldorado |
Arcabit | Trojan.Razy.D2577F | benign | Trojan.Generic.KDZ.D1482 |
Tencent | Win32.Trojan.Falsesign.K | Win32.Trojan.Crypt.K | Win32.Trojan.Falsesign.L |
Cyren | W32/S-3ae86dea!Eldorado | benign | W32/Zbot.HR.gen!Eldorado |
Avira | TR/Crypt.XPACK.Gen7 | TR/Crypt.CFI.Gen | TR/Pakes.lvqoue |
Rising | Spyware.Zbot!8.16B (CLOUD) | benign | Spyware.Zbot!8.16B (CLOUD) |
MAX | malware (ai score=100) | benign | malware (ai score=100) |
ZoneAlarm | HEUR:Trojan.Win32.Generic | UDS:DangerousObject.Multi.Generic | HEUR:Trojan.Win32.Generic |
Endgame | malicious (high confidence) | malicious (high confidence) | malicious (high confidence) |
AVware | Virtool.Win32.Obfuscator.as!c (v) | Trojan.Win32.Generic.pak!cobra | Trojan.Win32.Agent.akm (v) |
Webroot | W32.Infostealer.Zeus | W32.Malware.Heur | W32.Infostealer.Zeus |
Zillya | omission | Trojan.Genome.Win32.136493 | Trojan.Zbot.Win32.120499 |
Comodo | TrojWare.Win32.PWS.ZBot.XD | .UnclassifiedMalware | benign |
Yandex | TrojanSpy.Zbot!DHIuP5NKKgg | Trojan.Delf!msDHBXVvuuM | Trojan.Agent!v0Y1/43kpOQ |
AegisLab | Troj.W32.Generic!c | Uds.Dangerousobject.Multi!c | Troj.W32.Gen.lIUb |
Invincea | heuristic | benign | heuristic |
TheHacker | Trojan/Spy.Zbot.gevq | benign | benign |
Cylance | Unsafe | Unsafe | Unsafe |
CrowdStrike | malicious_confidence_90% (W) | malicious_confidence_90% (W) | malicious_confidence_80% (D) |
SentinelOne | omission | static engine - malicious | static engine - malicious |
ALYac | Gen:Variant.Razy.153471  | benign | Trojan.Generic.KDZ.5250 |
Malwarebytes | Trojan.Agent | omission | benign|
Baidu | Win32.Trojan.WisdomEyes.16070401.9500.9999 | Win32.Trojan.WisdomEyes.16070401.9500.9535 | benign|
SUPERAntiSpyware | Trojan.Agent/Gen-Petya | benign | Trojan.Agent/Gen-FakeMS |
ClamAV | Win.Trojan.Zbot-70175 | Win.Trojan.3973235-1 | benign |
ViRobot | Trojan.Win32.A.Zbot.322648 | Trojan.Win32.Z.Delf.2095298 |  benign |
Paloalto | generic.ml | generic.ml | generic.ml |
Bkav | HW32.Packed.5F17| HW32.Packed.58DF | HW32.Packed. |
Kingsoft | Win32.Malware.Generic.a.(kcloud) | benign | Win32.Troj.Zbot.il.(kcloud) |
TotalDefense | omission | Win32/Dragon_i | benign |
CMC | benign| benign | benign |
nProtect | omission | benign | omission |
Norman | omission |omission |omission |
AntiVir | omission |omission |omission |
Agnitum | omission |omission |omission |
Commtouch | omission |omission |omission |
PCTools | omission |omission |omission |
Zoner | benign | omission | benign |
ByteHero | omission |omission |omission |
NOD32 | omission |omission |omission |
WhiteArmor | omission | Malware.HighConfidence | omission |
VirusBuster| omission |omission |omission |
eTrust-Vet| omission |omission |omission |
eSafe| omission |omission |omission |
Sunbelt| omission |omission |omission |
Prevx| omission |omission |omission |
Authentium| omission |omission |omission |
a-squared| omission |omission |omission |
Alibaba| omission |omission |omission |
ahnlab| omission |omission |omission |
Command| omission |omission |omission |
SAVMail| omission |omission |omission |
FileAdvisor| omission |omission |omission |
Ewido| omission |omission |omission |
Webwasher-Gateway| omission |omission |omission |

## Materials and Methods

This paper proposes a database aiming at the classification of 32-bit benign and malware executables. There are  1,174 ransomwares, and 1,174 other benign executables. Therefore, our dataset is suitable for learning with artificial intelligence, since both classes of executables have the same amount.

Virtual plagues were extracted from databases provided by enthusiastic study groups as VirusShare which is a repository of malware samples to provide security researchers, incident responders, forensic analysts, and the morbidly curious access to samples of live malicious code. As for benign executables, the acquisition came from benign applications repositories such as sourceforge, github and sysinternals. It should be noted that all benign executables were submitted to VirusTotal and all were its benign attested by the main commercial antivirus worldwide. The diagnostics, provided by VirusTotal, corresponding to the benign and malware executables are available in the virtual address of our database.

The purpose of the creation of the database is to give full possibility of the proposed methodology being replicated by third parties in future works. Therefore, the proposed article, by making its database freely available, enables transparency and impartiality to research, as well as demonstrating the veracity of the results achieved. Therefore, it is hoped that the methodology will serve as a basis for the creation of new scientific works.

## Executable Feature Extraction

The extraction of features of executables employs the process of disassembling. Then, the algorithm, referring to the executable, can be studied and later classified by the neural networks described in the next section. In total, 649 features of each executable are extracted, referring to the groups mentioned above. The pescanner tool are employed in order to extract the features of executables. Next, the groups of features extracted from the executables investigated are detailed.
######	Histogram of instructions, in assembly, referring to the mnemonic.
######	Number of subroutines invoking TLS (Transport Layer Security).
######	Number of subroutines responsible for exporting data (exports).  
######	APIs (Application Programming Interface) used by the executable.
######	Features related to clues that the computer has suffered fragmentation on its hard disk, as well as accumulated invalid boot attempts.  
######	Application execution mode. There are two options:
-	software with a graphical interface (GUI);
-	software running on the console.
######	Features related to the Operating System. Our digital forensics examines if the tested file tries to:
-	identify the current operating system user name;
-	access APIs in order to create and manage current OS user profiles;
-	detect the number of milliseconds since the system was initialized;
-	execute an operation in a specific file;
-	identify the version of the Windows Operating System in use;
-	monitor internal message traffic among system processes;
-	alter the Windows startup settings and contents (STARTUPINFO);  
-	allow applications to access functionality provided by shell of the operating system, as well as alter it; 
-	change the logon messages at Windows OS startup; 
-	change native applications linked to standard dialog boxes in order to open and save files, choosing color and font, among other customizations;
-	configure Windows Server licensing ; 
-	configure Windows Server 2003;
-	change the system's power settings;
-	open a process, service, or native library of the Operating System; 
-	exclude the context of certificates linked to the Operating System; 
-	copy an existing file to a new file; 
-	create, open, delete, or alter a file;
-	create and execute new process(s); 
-	create new directory(s); 
-	search for specific file(s);  
-	create a service object and add it to the control manager database for a certain service; 
-	encrypt data. It is a typical strategy of ransomwares which sequester the victim's data through cryptography. To decrypt the data, the invader asks the user for a monetary amount so that he victim can have all his data back;
-	access file systems, devices, processes, threads and error handling of the system;
-	change the sound and audio device properties of the system;
-	access graphical content information for monitors, printers, and other Windows OS output devices; 
-	use and/or monitor the USB port;
-	control a driver of a particular device; 
-	investigate if a disk drive is a removable, fixed, CD / DVD-ROM, RAM or network drive;
######	Features related to Windows Registry (Regedit). It is worth noting that the victim may not be free from malware infection even after its detection and elimination. The persistence of malefactions, even after malware exclusion, occurs due to the insertion of malicious entries (keys) in Regedit. Then, when the operating system boots, the cyber-attack restarts because of the malicious key invoking the vulnerability exploited by malware (eg: redirect Internet Explorer home page). Then, our antivirus audits if the suspicious application tries to:
-	detect the NetBIOS name of the local computer. This name is established at system startup, when the system reads it in the registry (Regedit);
-	terminate a key of a specific registry; 
-	create a key from in a specific registry. If the key already exists in Regedit, then it will be read; 
-	delete a key and its values in Regedit; 
-	enumerate and   open subkeys of a specific open registry. 
######	Features related to spywares such as keyloggers (capture of keyboard information in order to theft of passwords and logins) and screenloggers (screen shot of the victim). Our antivirus audits if the analyzed file tries to:
-	detect in which part of the victim's screen there was an update;
-	identify the screen update region by copying it to a particular region;
-	capture AVI movies and videos from web cameras and other video hardware; 
-	capture information on electronic voting, specifically from the company Optical Vote-Trakker;
-	copy an array of keyboard key states. Such strategy is typical of keyloggers
-	monitor user's Internet activity and private information;
-	collect online bank passwords and other confidential information and to send the data to invader creator;
-	access a computer from remote locations, stealing passwords, Internet banking and personal data; 
-	create a BHO (Browser Helper Object) which is executed automatically every time when the web browser is started. It fits to emphasize that BHOs are not impeded by personal firewalls because they are identified as part of the browser. In a distorted way, BHOs are often used by adware and spyware in order to record keyboard and mouse entries
-	locate passwords stored on a computer.
######	Features related to Anti-forensic Digital which are techniques of removal, occultation and subversion of evidences with the goal of reducing the consequences of the results of forensic analyzes. Our antivirus investigates if the file tries to:
-	Suspend its own execution until a certain timeout interval has elapsed. A typical malware strategy that maintains itself inactive until the end of commercial antivirus quarantine;
-	Disable the victim's defense mechanisms, including Firewall and Antivirus;
-	disable automatic Windows updates;
-	detect if the own file is being scanned by an debugger of the Operating System;   
-	retrieve information about the first and next process found in an Operating System snapshot. Such strategy is typical of malwares that aim to corrupt backups and restore points of the Operating System;
-	hide one file in another. This strategy is named, technically, steganography which aims to hide malware in a benign program in the Task Manager;
-	disguise its own name in the Task Manager;
-	make use of libraries associated with Hackers Encyclopedia 2002;
-	Create a ZeroAcess cyber-attack type through firmware updates of hardware devices (eg, hard drive controlled).
######	Features related to the creation of GUI (Graphical User Interface) of the suspicious program. Our antivirus audits if the suspect file tries to: 
-	create a GUI at runtime; 
-	use DirectX which allows multimedia applications to draw 2D graphics; 
-	create a module that contains bitmap compression and decompression routines used for Microsoft Video for Windows;
-	create 3D graphics related to utilitarian functions used by OpenGL; 
-	detect shapes through computer vision and digital image processing;
-	access functionalities in order to create and to manage screen windows and more basic controls such as buttons and scrollbars, receive mouse and keyboard input, and other functionalities associated with the Windows GUI. This includes widgets like status bars, progress bars, toolbars, and guides; 
######	Features related to the illicit forensic of the RAM (main memory) of the local system. Our antivirus investigates if the suspicious application tries to:
-	access information in specific regions of main memory;
-	read data from an area of memory occupied by a specific process;
-	write data to a memory area in a specific process;
-	reserve, confirm or alter the status of a page region in the virtual address space of a process.
######	Features related to network traffic. It is checked if the suspect file tries to:
-	query DNS servers;
-	send request to an HTTP server; 
-	monitor information of the headers of computer data packets associated with an HTTP request;
-	send an ICMP IPv4 echo request; 
-	send an SNMP request used to monitor LAN equipment;
-	terminate the Internet connection;
-	create an FTP or HTTP session at runtime; 
-	fragment a URL at runtime; 
-	query a server in order to determine the amount of traffic data available; 
-	identify the connection state of the local system in relation to the Internet; 
-	initialize the use of an application of the WinINet functions (Windows API for creating and using the application using the Internet); 
-	read data from network packets made from previous local system requests (typical behavior of sniffers); 
-	overwrite data in a local system network packet; 
-	manage local and remote network systems; 
-	create a network socket on the local system. In a conventional application, the server sends data to the client (s). In an opposite way, in malware, the victim sends the data (images, digits) to the server. Therefore, malware can create sockets on the local system waiting (listen) for a remote malicious computer to request a connection and, then, receive the victim's private information;
-	receive data of a socket. Typical strategy of backdoors when the victim starts receiving remote commands; 
-	send data to a socket. Typical strategies of spywares which, after capturing innermost information, they send them to a malicious remote computer; 
######	Features related to utility applications programs. Our created antivirus checks if the suspicious file tries to:
-	reproduce videos/audios through Windows Media Player; 
-	change the shortcut icon and Internet default settings exhibited in the Explorer toolbar address bar; 
-	alter the Wordpad configurations;
-	alter the configurations of sockets, specifically, managed by Internet Explorer; 
-	alter Outlook Express configurations and to access the victim’s  e-mail list; 
-	access information linked to the Microsof Office; 
-	alter the configurations of the Adobe System’s suite;
-	change the system's disk cleanup configurations; 
-	alter the settings of native digital electronic games and others linked to companies Tycoon and Electronic Arts;
-	change Google Inc updates settings; 
-	use Visual Basic. Such strategy is typical of macro viruses that are intended to infect applications that support macro language such as web browsers, Microsoft Office, and Adobe Systems.
-	alter the access settings to Wikipedia.


