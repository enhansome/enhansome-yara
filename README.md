# Awesome yara with stars

<p align="center">
  <img height="128" src="./awesome-yara.png"  alt="Awesome YARA" title="Awesome YARA">
</p>

<h1 align="center">Awesome YARA</h1>

A curated list of awesome YARA rules, tools, and resources. Inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 318,021 | 🐛 16 | 🌐 Python | 📅 2026-09-01 and [awesome-php](https://github.com/ziadoz/awesome-php) ⭐ 32,675 | 🐛 85 | 📅 2026-07-13.

> YARA is an ancronym for: YARA: Another Recursive Ancronym, or Yet Another Ridiculous Acronym. Pick your choice.
>
> \-- *[Victor M. Alvarez (@plusvic)](https://twitter.com/plusvic/status/778983467627479040)*

[YARA](https://virustotal.github.io/yara/), the "pattern matching swiss knife for malware researchers (and everyone else)" is developed by [@plusvic](https://github.com/plusvic/) and [@VirusTotal](https://github.com/VirusTotal). View it on [GitHub](https://github.com/virustotal/yara) ⭐ 9,847 | 🐛 170 | 🌐 C | 📅 2026-08-25.

### Contents

* [100 Days of YARA (#100DaysofYARA)](#100-days-of-yara-100daysofyara)
* [Guides](#guides)
* [Rules](#rules)
* [Tools](#tools)
* [Services](#services)
* [Syntax Highlighters](#syntax-highlighters)
* [People](#people)
* [Videos and Talks](#videos-and-talks)
* [Related Awesome Lists](#related-awesome-lists)
* [Contributing](#contributing)
  * [Contributors](#contributors)

### Legend

* :eyes: - Actively maintained, a repository worth watching.
* :gem: - Novel, interesting, educational, or otherwise stand-out content.
* :sparkles: - Added more recently, shiny new toys.
* :trophy: - The biggest collection award, awarded to a single repo.

## 100 Days of YARA (#100DaysofYARA)

An annual YARA challenge started by [Greg Lesnewich](https://twitter.com/greglesnewich) in 2022, inspired by #100DaysOfCode and taking place in the first 100 days of the year. The goal is to contribute daily to the YARA community through rule creation, source code contributions, or generally teaching/help your colleagues. Other key contributors include [Wesley Shields](https://twitter.com/wxs) and [Steve Miller](https://twitter.com/stvemillertime). For a list of all participants in the first two years of the challenge, see our [Twitter List](https://twitter.com/i/lists/1648861278901764096).

Rule collections from prior years of the challenge: [100 Days of YARA](https://github.com/100DaysofYARA)

## Guides

* [Yara Performance Guidelines](https://github.com/Neo23x0/YARA-Performance-Guidelines) ⭐ 174 | 🐛 0 | 📅 2025-02-11
* [YARA-Style-Guide](https://github.com/Neo23x0/YARA-Style-Guide) ⭐ 78 | 🐛 2 | 📅 2024-02-17

## Rules

* [YaraRules Project Official Repo](https://github.com/Yara-Rules/rules) ⭐ 4,882 | 🐛 27 | 🌐 YARA | 📅 2024-04-17 :eyes:
  * Large collection of rules constantly updated by the community.
* [CAPE Rules](https://github.com/kevoreilly/CAPEv2/tree/master/data/yara) ⭐ 3,463 | 🐛 63 | 🌐 Python | 📅 2026-09-02 :eyes:
  * Rules from various authors bundled with the Config And Payload Extraction Cuckoo Sandbox extension (see next section).
* [Florian Roth Rules](https://github.com/Neo23x0/signature-base/tree/master/yara) ⭐ 3,018 | 🐛 14 | 🌐 YARA | 📅 2026-08-31 :eyes: :gem:
  * Florian Roth's signature base is a frequently updated collection of IOCs and YARA rules that cover a wide range of threats. There are dozens of rules which are actively maintained. Watch the repository to see rules evolve over time to address false positives / negatives.
* [FireEye](https://github.com/fireeye/red_team_tool_countermeasures) ⚠️ Archived
  * FireEye Red Team countermeasures detection
* [Didier Stevens Rules](https://github.com/DidierStevens/DidierStevensSuite) ⭐ 2,529 | 🐛 13 | 🌐 Python | 📅 2026-07-30 :gem:
  * Collection of rules from Didier Stevens, author of a suite of tools for inspecting OLE/RTF/PDF. Didier's rules are worth scrutinizing and are generally written purposed towards hunting. New rules are frequently announced through the [NVISO Labs Blog](https://blog.nviso.eu/).
* [ESET IOCs](https://github.com/eset/malware-ioc/) ⭐ 1,982 | 🐛 0 | 🌐 YARA | 📅 2026-06-25 :eyes:
  * Collection of YARA and Snort rules from IOCs collected by ESET researchers. There's about a dozen YARA Rules to glean from in this repo, search for file extension .yar. This repository is seemingly updated on a roughly monthly interval. New IOCs are often mentioned on the [ESET WeLiveSecurity Blog](https://www.welivesecurity.com/).
* [Elastic Security YARA Rules](https://github.com/elastic/protections-artifacts/tree/main/yara) ⭐ 1,486 | 🐛 6 | 🌐 YARA | 📅 2026-09-02
  * Elastic Security provides signature-based YARA rules within the Elastic Endpoint product. These rules are used to detect and prevent emerging threats within Linux, Windows, and macOS systems. Our repository holds over 1,000 YARA rules that are used every day to stop a wide range of threats including: Trojans, ransomware, cryptominers, attack penetration frameworks, and more.
* [BinaryAlert YARA Rules](https://github.com/airbnb/binaryalert/tree/master/rules/public) ⭐ 1,455 | 🐛 43 | 🌐 Python | 📅 2023-12-12
  * A couple dozen rules written and released by AirBnB as part of their BinaryAlert tool (see next section). Detection for hack tools, malware, and ransomware across Linux, Window, and OS X. This is a new and active project.
* [ReversingLabs YARA Rules](https://github.com/reversinglabs/reversinglabs-yara-rules) ⭐ 937 | 🐛 2 | 🌐 YARA | 📅 2025-11-03 :sparkles: :eyes:
  * A collection of yara rules published by ReversingLabs which covers exploits, infostealers, ransomware, trojans, and viruses.
* [McAfee Advanced Threat Research Yara-Rules](https://github.com/advanced-threat-research/Yara-Rules) ⭐ 626 | 🐛 0 | 🌐 YARA | 📅 2025-03-18
  * Repository of YARA rules made by McAfee ATR Teams.
* [Google Cloud Threat Intelligence(GCTI) Rules](https://github.com/chronicle/GCTI) ⚠️ Archived
  * Rules to detect CobaltStrike framework and Sliver implant.
* [AlienVault Labs Rules](https://github.com/AlienVault-Labs/AlienVaultLabs/tree/master/malware_analysis) ⭐ 524 | 🐛 4 | 🌐 Python | 📅 2021-12-22
  * Collection of tools, signatures, and rules from the researchers at [AlienVault Labs](https://cybersecurity.att.com/blogs/labs-research). Search the repo for .yar and .yara extensions to find about two dozen rules ranging from APT detection to generic sandbox / VM detection. Last updated in January of 2016.
* [NCC Group Rules](https://github.com/nccgroup/Cyber-Defence/tree/master/Signatures/yara) ⭐ 474 | 🐛 0 | 🌐 Python | 📅 2021-12-12 :eyes:
  * A handful of YARA rules released by NCC Group's Cyber Defence team.
* [bartblaze YARA rules](https://github.com/bartblaze/Yara-rules) ⭐ 390 | 🐛 1 | 🌐 YARA | 📅 2026-01-28 :eyes:
  * Collection of personal YARA rules
* [InQuest Rules](https://github.com/InQuest/yara-rules) ⭐ 390 | 🐛 2 | 🌐 Python | 📅 2022-05-11 :eyes:
  * YARA rules published by InQuest researchers mostly geared towards threat hunting on Virus Total. Rules are updated as new samples are collected and novel pivots are discovered. The [InQuest Blog](http://blog.inquest.net) will often discuss new findings.
* [Icewater Rules](https://github.com/SupportIntelligence/Icewater) ⭐ 389 | 🐛 3 | 🌐 YARA | 📅 2019-06-01
  * Repository of automatically generated YARA rules from Icewater.io. This repository is updated rapidly with newly generated signatures that mostly match on file size range and partial content hashes.
* [Volexity - Threat-Intel](https://github.com/volexity/threat-intel) ⭐ 370 | 🐛 0 | 🌐 Python | 📅 2026-07-17 :sparkles: :gem:
  * This repository contains IoCs related to Volexity public threat intelligence blog posts.
* [mikesxrs YARA Rules Collection](https://github.com/mikesxrs/Open-Source-YARA-rules) ⭐ 368 | 🐛 1 | 🌐 YARA | 📅 2024-04-17 :eyes:
  * Large collection of open source rules aggregated from a variety of sources, including blogs and other more ephemeral sources. Over 100 categories, 1500 files, 4000 rules, and 20Mb. If you're going to pull down a single repo to play with, this is the one.
* [StrangeRealIntel's Daily IOCs](https://github.com/StrangerealIntel/DailyIOC) ⭐ 318 | 🐛 6 | 🌐 YARA | 📅 2023-12-12 :gem: :sparkles: :eyes:
  * Regularly updated YARA rules covering a variety of fresh threats.
* [FSF Rules](https://github.com/EmersonElectricCo/fsf/tree/master/fsf-server/yara) ⭐ 294 | 🐛 17 | 🌐 Python | 📅 2021-09-15
  * Mostly filetype detection rules, from the EmersonElectricCo FSF project (see next section).
* [Ditekshen Rules](https://github.com/ditekshen/detection) ⭐ 257 | 🐛 2 | 🌐 YARA | 📅 2024-11-01
  * A set of interrelated network and host detection rules with the aim of improving detection and hunting visibility and context.
* [SpiderLabs Rules](https://github.com/SpiderLabs/malware-analysis/tree/master/Yara) ⭐ 256 | 🐛 1 | 🌐 Ruby | 📅 2016-07-29
  * Repository of tools and scripts related to malware analysis from the researchers at SpiderLabs. There's only three YARA rules here and the last update was back in 2015, but worth exploring.
* [t4d's PhishingKit-Yara-Rules](https://github.com/t4d/PhishingKit-Yara-Rules) ⭐ 240 | 🐛 0 | 🌐 YARA | 📅 2026-07-19
  * This repository, dedicated to Phishing Kits zip files YARA rules, is based on zip raw format analysis to find directories and files names, you don't need yara-extend there.
* [HydraDragonAntivirus](https://github.com/HydraDragonAntivirus/HydraDragonAntivirus) ⭐ 238 | 🐛 0 | 🌐 YARA | 📅 2026-09-02 :trophy:
  * World's largest open source YARA collection with no duplicates, no invalid ones and only few files. Also it contains ClamAV + YARA-X or YARA + Machine Learning + IDS canner and signatures and SUBLIME + CAPA + SIGMA signatures. Finally it has so big malware collection.
* [Rastrea2r](https://github.com/rastrea2r/rastrea2r) ⭐ 238 | 🐛 8 | 🌐 Python | 📅 2021-08-01
  * Triage suspect systems and hunt for Indicators of Compromise (IOCs) across thousands of endpoints in minutes.
* [Sophos AI YaraML Rules](https://github.com/inv-ds-research/yaraml_rules) ⭐ 216 | 🐛 4 | 🌐 Python | 📅 2023-07-06
  * A repository of Yara rules created automatically as translations of machine learning models. Each directory will have a rule and accompanying metadata: hashes of files used in training, and an accuracy diagram (a ROC curve).
* [ThreatHunting-Keywords-yara-rules](https://github.com/mthcht/ThreatHunting-Keywords-yara-rules) ⭐ 166 | 🐛 1 | 🌐 YARA | 📅 2025-05-11
  * Yara rules for Threat Hunting sessions
* [Malpedia Auto Generated Rules Repo](https://github.com/malpedia/signator-rules) ⭐ 150 | 🐛 1 | 🌐 YARA | 📅 2026-05-18 :sparkles:
  * Repository to simplify access to and synchronization of Malpedia's automatically generated, code-based YARA rules.
* [Citizen Lab Malware Signatures](https://github.com/citizenlab/malware-signatures) ⭐ 145 | 🐛 1 | 🌐 VimL | 📅 2016-11-17
  * YARA signatures developed by Citizen Lab. Dozens of signatures covering a variety of malware families. The also inclde a syntax file for Vim. Last update was in November of 2016.
* [YARA-FORENSICS](https://github.com/Xumeiquer/yara-forensics) ⭐ 143 | 🐛 1 | 🌐 YARA | 📅 2020-09-08
  * Collection of file type identifying rules.
* [Intezer Rules](https://github.com/intezer/yara-rules) ⭐ 131 | 🐛 0 | 🌐 YARA | 📅 2025-02-02 :sparkles:
  * YARA rules published by Intezer Labs.
* [QuickSand Lite Rules](https://github.com/tylabs/quicksand_lite) ⭐ 127 | 🐛 0 | 🌐 C | 📅 2023-09-23
  * This repo contains a C framework and standalone tool for malware analysis, along with several useful YARA rules developed for use with the project.
* [yara4pentesters](https://github.com/DiabloHorn/yara4pentesters) ⭐ 127 | 🐛 0 | 📅 2018-01-31
  * Rules to identify files containing juicy information like usernames, passwords etc.
* [Telekom Security Malare Analysis Repository](https://github.com/telekom-security/malware_analysis) ⭐ 122 | 🐛 2 | 🌐 Python | 📅 2026-03-04
  * This repository comprises scripts, signatures, and additional IOCs of our blog posts at the telekom.com blog.
* [Rapid7-Labs](https://github.com/rapid7/Rapid7-Labs/) ⭐ 114 | 🐛 0 | 🌐 Shell | 📅 2026-08-19
  * This repository contains a curated collection of Sigma & Yara rules and Indicators of Compromise (IOCs) shared by Rapid7 Labs.
* [lw-yara](https://github.com/Hestat/lw-yara) ⭐ 108 | 🐛 0 | 🌐 YARA | 📅 2021-03-04
  * Ruleset for scanning Linux servers for shells, spamming, phishing and other webserver baddies.
* [GoDaddy ProcFilter Rules](https://github.com/godaddy/yara-rules) ⚠️ Archived
  * A couple dozen rules written and released by GoDaddy for use with ProcFilter (see next section). Example rules include detection for packers, mimikatz, and specific malware.
* [x64dbg Signatures](https://github.com/x64dbg/yarasigs) ⭐ 87 | 🐛 0 | 🌐 YARA | 📅 2019-05-23 :gem:
  * Collection of interesting packer, compiler, and crypto identification signatures.
* [McAfee Advanced Threat Research IOCs](https://github.com/advanced-threat-research/IOCs) ⭐ 83 | 🐛 1 | 🌐 HTML | 📅 2021-08-04
  * IOCs, including YARA rules, to accompany McAfee ATR's blog and other public posts.
* [BinSequencer](https://github.com/karttoon/binsequencer) ⭐ 79 | 🐛 1 | 🌐 Python | 📅 2022-01-02
  * Find a common pattern of bytes within a set of samples and generate a YARA rule from the identified pattern.
* [Delivr.to Detections](https://github.com/delivr-to/detections) ⭐ 75 | 🐛 1 | 🌐 YARA | 📅 2025-08-10
  * This repo serves as a home for detection content developed by the delivr.to team.
* [Frank Boldewin's Rules](https://github.com/fboldewin/YARA-rules) ⭐ 68 | 🐛 1 | 🌐 YARA | 📅 2023-03-25
  * A collection of YARA Rules from [@r3c0nst](https://twitter.com/@r3c0nst).
* [MalGamy's YARA\_Rules](https://github.com/MalGamy/YARA_Rules) ⭐ 65 | 🐛 2 | 🌐 YARA | 📅 2023-01-27
  * A small repository which contains some stealer rules.
* [Tenable Rules](https://github.com/tenable/yara-rules) ⭐ 60 | 🐛 0 | 🌐 YARA | 📅 2022-11-29
  * Small collection from Tenable Network Security.
* [kevthehermit Rules](https://github.com/kevthehermit/YaraRules) ⭐ 52 | 🐛 0 | 📅 2016-02-07
  * Dozens of rules from the personal collection of Kevin Breen. This repository hasn't been updated since February of 2016.
* [Burp YARA Rules](https://github.com/codewatchorg/Burp-Yara-Rules) ⭐ 49 | 🐛 0 | 🌐 YARA | 📅 2022-01-26
  * Collection of YARA rules intended to be used with the Burp Proxy through the Yara-Scanner extension. These rules focus mostly on non-exe malware typically delivered over HTTP including HTML, Java, Flash, Office, PDF, etc. Last updated in June of 2016.
* [Deadbits Rules](https://github.com/deadbits/yara-rules) ⚠️ Archived :eyes:
  * A collection of YARA rules made public by [Adam Swanda](https://www.deadbits.org/), Splunk's Principal Threat Intel. Analyst, from his own recent malware research.
* [ConventionEngine Rules](https://github.com/stvemillertime/ConventionEngine) ⭐ 37 | 🐛 2 | 🌐 YARA | 📅 2023-03-15 :sparkles:
  * A collection of Yara rules looking for PEs with PDB paths that have unique, unusual, or overtly malicious-looking keywords, terms, or other features.
* [anyrun rules](https://github.com/anyrun/YARA) ⭐ 31 | 🐛 0 | 🌐 YARA | 📅 2025-11-01
  * Public YARA rules
* [jeFF0Falltrades Rules](https://github.com/jeFF0Falltrades/YARA-Signatures) ⭐ 30 | 🐛 0 | 🌐 YARA | 📅 2024-09-20 :sparkles:
  * A collection of YARA signatures for various malware families.
* [Malice.IO YARA Plugin Rules](https://github.com/malice-plugins/yara/tree/master/rules) ⚠️ Archived :eyes:
  * Collection of topical from a variety of sources for the YARA component of the Malice.IO framework.
* [YAIDS](https://github.com/wrayjustin/yaids) ⭐ 26 | 🐛 4 | 🌐 C | 📅 2022-10-20 :gem: :sparkles:
  * YAIDS is a Multi-Threaded Intrusion Detection System using Yara. YAIDS supports all valid Yara rules (including modules) and any PCAP compatible data stream (Network, USB, Bluetooth, etc.).
* [Yara-Unprotect](https://github.com/fr0gger/Yara-Unprotect) ⭐ 26 | 🐛 1 | 🌐 YARA | 📅 2020-11-19
  * Rules created for the Unprotect Project for detecting malware evasion techniques.
  - [Unprotect Project](https://unprotect.it/detection-rules/)
    * Detection Rule List.
* [Filescan.io Rules](https://github.com/filescanio/fsYara) ⭐ 22 | 🐛 0 | 🌐 YARA | 📅 2026-08-31 ✨
  * A collection of curated YARA rules used as part of the Filescan.io service.
* [h3x2b Rules](https://github.com/h3x2b/yara-rules) ⭐ 22 | 🐛 0 | 🌐 YARA | 📅 2025-09-09 :gem:
  * Collection of signatures from h3x2b which stand out in that they are generic and can be used to assist in reverse engineering. There are YARA rules for identifying crypto routines, highly entropic sections (certificate discovery for example), discovering injection / hooking functionality, and more.
* [imp0rtp3's Rules](https://github.com/imp0rtp3/yara-rules) ⭐ 20 | 🐛 0 | 🌐 YARA | 📅 2021-11-26
  * A small repository which contains some browser based rules.
* [CyStack Stealer Fingerprints](https://github.com/cystack/stealer-fingerprints) ⭐ 19 | 🐛 0 | 🌐 YARA | 📅 2026-06-09 :sparkles:
  * YARA rules and field-signature fingerprints for 30+ infostealer log families including RedLine, Vidar, Lumma and StealC. Each family folder contains a rules.yar, a sanitized sample, and fingerprint metadata (banner strings, field keys).
* [CDI Rules](https://github.com/CyberDefenses/CDI_yara) ⭐ 18 | 🐛 2 | 📅 2023-09-10
  * Collection of YARA rules released by [CyberDefenses](https://cyberdefenses.com/blog/) for public use. Built from information in intelligence profiles, dossiers and file work.
* [VectraThreatLab Rules](https://github.com/VectraThreatLab/reyara) ⭐ 18 | 🐛 0 | 📅 2015-12-09
  * YARA rules for identifying anti-RE malware techniques.
* [Securitymagic's YARA Rules](https://github.com/securitymagic/yara) ⭐ 17 | 🐛 2 | 🌐 YARA | 📅 2026-06-26
  * YARA rules for a variety of threats.
* [Public YARA Rules](https://github.com/jipegit/yara-rules-public) ⭐ 11 | 🐛 0 | 🌐 YARA | 📅 2019-04-29
  * Repository of Public YARA Rules.
* [f0wl yara\_rules](https://github.com/f0wl/yara_rules) ⭐ 10 | 🐛 0 | 🌐 YARA | 📅 2022-03-03
  * A collection of Yara rules from <https://dissectingmalwa.re/> blog posts.
* [TjadaNel Rules](https://github.com/tjnel/yara_repo) ⭐ 9 | 🐛 0 | 🌐 YARA | 📅 2019-05-13
  * Small collection of malware rules.
* [Operation Epic Fury Rules](https://github.com/paolocostanzo/operation-epic-fury-rules) ⭐ 0 | 🐛 0 | 🌐 YARA | 📅 2026-03-16 :sparkles:
  * YARA + Sigma detection rules for Operation Epic Fury (Iranian-linked dual-platform campaign, 2026). Covers LotAccessUI.EXE (trojanized AppEx VPN Windows RAT with RDTSC anti-VM evasion, T1497.003) and fake RedAlert Android spyware (com.red.alertx + com.net.alerts with Pushy.me C2). Includes secondary C2 (167.160.187.43) with 0/94 VirusTotal detections at publication. TLP:WHITE, MIT license.
* [Apple OSX](https://gist.github.com/pedramamini/c586a151a978f971b70412ca4485c491)
  * Apple has \~40 YARA signatures for detecting malware on OSX. The file, XProtect.yara, is available locally at /System/Library/CoreServices/XProtect.bundle/Contents/Resources/.
* [Fidelis Rules](https://github.com/fideliscyber/indicators/tree/master/yararules)
  * You can find a half dozen YARA rules in Fidelis Cyber's IOC repository. They update this repository on a roughly quarterly interval. Complete blog content is also available in this repository.
* [Florian Roth's IDDQD Rule](https://gist.github.com/Neo23x0/f1bb645a4f715cb499150c5a14d82b44)
  * A proof-of-concept rule that shows how easy it actually is to detect red teamer and threat group tools and code.
* [Loginsoft Rules](https://research.loginsoft.com/yara-rules/)
  * Yara Rules for Detecting Malicious Documents targeting Microsoft Office format.
* [ndaal\_YARA\_passwords\_default](https://gitlab.com/ndaal_open_source/ndaal_yara_passwords_default)
  * YARA rules includes default credentials of at least 1043 organizations which are hashed with different hash permutations such as base64, md5, sha512, etc.
* [ndaal\_YARA\_passwords\_weak](https://gitlab.com/ndaal_open_source/ndaal_yara_passwords_weak)
  * YARA rules includes hashed passwords of the top weak passwords. The passwords are hashed in a respective rule according to the following permutations such as base64, md5, sha512, etc.
* [Malpedia Auto Generated Rules](https://malpedia.caad.fkie.fraunhofer.de/api/get/yara/auto/zip) :sparkles:
  * A zip file that contains all automatically generated, code-based rules created using Malpedia's YARA-Signator
* [YARA Forge](https://yarahq.github.io/) :gem: :sparkles: :eyes:
  * YARA Forge specializes in delivering high-quality YARA rule packages for immediate integration into security platforms.

## Tools

* [MISP Threat Sharing](https://github.com/MISP/MISP) ⭐ 6,498 | 🐛 2,912 | 🌐 PHP | 📅 2026-09-02
  * Threat intelligence platform including indicators, threat intelligence, malware samples and binaries. Includes support for sharing, generating, and validating YARA signatures.
* [CAPE: Config And Payload Extraction](https://github.com/kevoreilly/CAPEv2) ⭐ 3,463 | 🐛 63 | 🌐 Python | 📅 2026-09-02 :eyes:
  * Extension of Cuckoo specifically designed to extract payloads and configuration from malware. CAPE can detect a number of malware techniques or behaviours, as well as specific malware families, from its initial run on a sample. This detection then triggers a second run with a specific package, in order to extract the malware payload and possibly its configuration, for further analysis.
* [APKiD](https://github.com/rednaga/APKiD) ⭐ 2,568 | 🐛 84 | 🌐 YARA | 📅 2026-07-27
  * Android Application Identifier for Packers, Protectors, Obfuscators and Oddities - PEiD for Android
* [Yeti](https://github.com/yeti-platform/yeti) ⭐ 2,022 | 🐛 52 | 🌐 Python | 📅 2026-09-02
  * Platform meant to organize observables, indicators of compromise, TTPs, and knowledge on threats in a single, unified repository.
* [yarGen](https://github.com/Neo23x0/yarGen) ⭐ 1,812 | 🐛 14 | 🌐 Python | 📅 2026-01-10
  * YARA rule generator for finding related samples and hunting.
* [findcrypt-yara](https://github.com/polymorf/findcrypt-yara) ⭐ 1,739 | 🐛 10 | 🌐 Python | 📅 2024-11-19 and [FindYara](https://github.com/OALabs/FindYara) ⭐ 184 | 🐛 6 | 🌐 Python | 📅 2024-01-30
  * IDA pro plugins to scan your binary with YARA rules to find crypto constants (and more).
* [AirBnB BinaryAlert](https://github.com/airbnb/binaryalert) ⭐ 1,455 | 🐛 43 | 🌐 Python | 📅 2023-12-12
  * Open-source serverless AWS pipeline where any file uploaded to an S3 bucket is immediately scanned with a configurable set of YARA rules.
* [YaraHunter](https://github.com/deepfence/YaraHunter) ⭐ 1,320 | 🐛 6 | 🌐 Go | 📅 2026-03-07
  * Malware scanner for cloud-native, as part of CI/CD and at Runtime
* [PasteHunter](https://github.com/kevthehermit/PasteHunter) ⭐ 1,138 | 🐛 21 | 🌐 Python | 📅 2026-01-10
  * Scan pastebin.com with YARA rules.
* [Strelka](https://github.com/target/strelka) ⭐ 1,001 | 🐛 14 | 🌐 Python | 📅 2026-08-29
  * Detection-Oriented File Analysis System built on Python3, ZeroMQ, and YARA, primarily used for threat detection/hunting and intelligence gathering.
* [ThreatIngestor](https://github.com/InQuest/ThreatIngestor/) ⭐ 926 | 🐛 15 | 🌐 Python | 📅 2026-05-26
  * Automatically extract and aggregate IOCs including YARA rules from many sources.
* [Laika BOSS](https://github.com/lmco/laikaboss) ⭐ 753 | 🐛 26 | 🌐 Python | 📅 2024-12-16
  * [Whitepaper](https://github.com/lmco/laikaboss/blob/master/LaikaBOSS_Whitepaper.pdf) ⭐ 753 | 🐛 26 | 🌐 Python | 📅 2024-12-16
  * Object scanner and intrusion detection system that strives to achieve the following goals: Scalable, Flexible, Verbose.
* [KLara](https://github.com/KasperskyLab/klara) ⭐ 728 | 🐛 10 | 🌐 PHP | 📅 2024-07-24
  * Distributed system written in Python, allows researchers to scan one or more YARA rules over collections with samples.
* [bincapz](https://github.com/chainguard-dev/bincapz) ⭐ 675 | 🐛 10 | 🌐 Go | 📅 2026-09-02
  * Enumerates program capabilities and malicious behaviors using fragment analysis..
* [MITRE MultiScanner](https://github.com/mitre/multiscanner) ⭐ 621 | 🐛 39 | 🌐 Python | 📅 2019-10-08
  * File analysis framework that assists the user in evaluating a set of files by automatically running a suite of tools for the user and aggregating the output.
* [iocextract](https://github.com/InQuest/python-iocextract) ⭐ 584 | 🐛 2 | 🌐 Python | 📅 2024-08-28
  * Advanced Indicator of Compromise (IOC) extractor, with YARA rule extraction.
* [MalConfScan](https://github.com/JPCERTCC/MalConfScan) ⭐ 498 | 🐛 4 | 🌐 Python | 📅 2023-12-22
  * MalConfScan is a Volatility plugin extracts configuration data of known malware. This tool searches for malware in memory images and dumps configuration data. In addition, this tool has a function to list strings to which malicious code refers.
* [Rustinel](https://github.com/Karib0u/rustinel) ⭐ 464 | 🐛 61 | 🌐 Rust | 📅 2026-09-01
  * Open-source endpoint detection engine for Windows and Linux that scans executables with YARA on process creation and combines results with Sigma and IOC detections.
* [mquery](https://github.com/CERT-Polska/mquery) ⭐ 443 | 🐛 26 | 🌐 Python | 📅 2026-02-03
  * Web frontend for running blazingly fast YARA queries on large datasets.
* [GoDaddy ProcFilter](https://github.com/godaddy/procfilter) ⚠️ Archived :gem:
  * ProcFilter is a process filtering system for Windows with built-in YARA integration. YARA rules can be instrumented with custom meta tags that tailor its response to rule matches. It runs as a Windows service and is integrated with Microsoft's ETW API, making results viewable in the Windows Event Log. Installation, activation, and removal can be done dynamically and does not require a reboot.
* [SwishDbgExt](https://github.com/comaeio/SwishDbgExt) ⭐ 399 | 🐛 2 | 🌐 C++ | 📅 2018-12-11
  * Microsoft WinDbg extension which includes the ability to use YARA rules to hunt processes in memory.
* [yarAnalyzer](https://github.com/Neo23x0/yarAnalyzer) ⭐ 397 | 🐛 2 | 🌐 Python | 📅 2023-02-19
  * YARA rule set coverage analyzer.
* [stoQ](https://github.com/PUNCH-Cyber/stoq) ⭐ 392 | 🐛 4 | 🌐 Python | 📅 2022-06-27
  * Modular and highly customizable framework for the creation of data sets from multiple disparate data sources.
* [go-yara](https://github.com/hillu/go-yara) ⭐ 389 | 🐛 7 | 🌐 Go | 📅 2025-07-01
  * Go bindings for YARA.
* [Polichombr](https://github.com/ANSSI-FR/polichombr) ⚠️ Archived
  * Collaborative malware analysis framework with YARA rule matching and other features.
* [YaraGenerator](https://github.com/Xen0ph0n/YaraGenerator) ⭐ 332 | 🐛 3 | 🌐 Python | 📅 2016-02-02
  * Quick, simple, and effective yara rule creation to isolate malware families and other malicious objects of interest.
* [yextend](https://github.com/BayshoreNetworks/yextend) ⭐ 324 | 🐛 11 | 🌐 C++ | 📅 2022-05-09
  * YARA integrated software to handle archive file data.
* [yaya](https://github.com/EFForg/yaya) ⭐ 305 | 🐛 9 | 🌐 Go | 📅 2023-12-27
  * Automatically curate open source yara rules and run scans.
* [Fnord](https://github.com/Neo23x0/Fnord) ⭐ 303 | 🐛 1 | 🌐 Shell | 📅 2022-02-12
  * Pattern extractor for obfuscated code.
* [Emerson File Scanning Framework (FSF)](https://github.com/EmersonElectricCo/fsf) ⭐ 294 | 🐛 17 | 🌐 Python | 📅 2021-09-15
  * Modular, recursive file scanning solution.
* [Vxsig](https://github.com/google/vxsig) ⭐ 288 | 🐛 5 | 🌐 C++ | 📅 2026-05-04 :sparkles:
  * Automatically generate AV byte signatures from sets of similar binaries.
* [Arya- The Reverse YARA](https://github.com/claroty/arya) ⭐ 261 | 🐛 1 | 🌐 Python | 📅 2022-12-27
  * Arya is a unique tool that produces pseudo-malicious files meant to trigger YARA rules. You can think of it like a reverse YARA because it does exactly the opposite - it creates files that matches your rules.
* [Fastfinder](https://github.com/codeyourweb/fastfinder) ⭐ 261 | 🐛 0 | 🌐 Go | 📅 2026-01-24
  * Fast customisable cross-platform suspicious file finder. Designed for incident response. Supports md5/sha1/sha256 hashs, litteral/wildcard strings, regular expressions and YARA rules. Can easily be packed to be deployed on any windows / linux host.
* [Hyara](https://github.com/hyuunnn/Hyara) ⭐ 248 | 🐛 9 | 🌐 Python | 📅 2024-10-18
  * IDA Pro, Cutter, and BinaryNinja plugin that provides easy creation of YARA rules for ASCII & hex strings between a given start and end address.
* [Sysmon EDR](https://github.com/ion-storm/sysmon-edr) ⭐ 228 | 🐛 1 | 🌐 PowerShell | 📅 2021-05-01 :sparkles:
  * YARA scanning, process killing, network blocking, and more.
* [mkYARA](https://github.com/fox-it/mkYARA) ⭐ 219 | 🐛 10 | 🌐 Python | 📅 2021-10-07
  * Generate YARA rules based on binary code.
* [halogen](https://github.com/target/halogen) ⚠️ Archived
  * Halogen is a tool to automate the creation of yara rules against image files embedded within a malicious document.
* [YaraGuardian](https://github.com/PUNCH-Cyber/YaraGuardian) ⭐ 196 | 🐛 9 | 🌐 Python | 📅 2018-07-28
  * Django web interface for managing YARA rules.
* [plyara](https://github.com/plyara/plyara) ⭐ 195 | 🐛 17 | 🌐 Python | 📅 2025-02-06
  * Parse YARA rules with Python.
* [spyre](https://github.com/spyre-project/spyre) ⭐ 181 | 🐛 13 | 🌐 Go | 📅 2026-03-17
  * Simple, self-contained YARA-based file IOC scanner.
* [yara-signator](https://github.com/fxb-cocacoding/yara-signator) ⭐ 168 | 🐛 5 | 🌐 Java | 📅 2022-09-08 :sparkles:
  * Automatic YARA rule generation for Malpedia
* [yabin](https://github.com/AlienVault-OTX/yabin) ⭐ 165 | 🐛 4 | 🌐 Python | 📅 2022-09-11
  * Creates YARA signatures from executable code within malware.
* [yaralyzer](https://github.com/michelcrypt4d4mus/yaralyzer) ⭐ 153 | 🐛 1 | 🌐 Python | 📅 2026-02-01
  * Visually inspect and force decode YARA and regex matches found in both binary and text data. With Colors.
* [CrowdStrike Feed Management System](https://github.com/CrowdStrike/CrowdFMS) ⚠️ Archived
  * Framework for automating collection and processing of samples from VirusTotal, and executing commands based on YARA rule matches.
* [yaramod](https://github.com/avast/yaramod) ⭐ 128 | 🐛 36 | 🌐 C++ | 📅 2026-07-23
  * A library that provides parsing of YARA rules into AST and a C++ programming interface to build new YARA rulesets.
* [CCCS-Yara](https://github.com/CybercentreCanada/CCCS-Yara) ⭐ 118 | 🐛 5 | 🌐 Python | 📅 2026-09-01
  * YARA rule metadata specification and validation utility.
* [yara-endpoint](https://github.com/Yara-Rules/yara-endpoint) ⭐ 110 | 🐛 5 | 🌐 Go | 📅 2018-03-13
  * Tool useful for incident response as well as anti-malware enpoint based on YARA signatures.
* [yaraPCAP](https://github.com/kevthehermit/YaraPcap) ⭐ 108 | 🐛 1 | 🌐 Python | 📅 2013-07-29
  * YARA scanner For IMAP feeds and saved streams.
* [InQuest ThreatKB](https://github.com/InQuest/ThreatKB) ⭐ 104 | 🐛 42 | 🌐 JavaScript | 📅 2026-08-12
  * Knowledge base workflow management for YARA rules and C2 artifacts (IP, DNS, SSL).
* [yarasafe](https://github.com/lucamassarelli/yarasafe) ⭐ 100 | 🐛 1 | 🌐 C | 📅 2020-02-25
  * Automatic generation of function signature using machine learning.
* [VTCodeSimilarity-YaraGen](https://github.com/arieljt/VTCodeSimilarity-YaraGen) ⭐ 98 | 🐛 0 | 🌐 Python | 📅 2020-10-07 :gem: :sparkles:
  * Yara rule generator using VirusTotal code similarity feature `code-similar-to:` written by [@arieljt](https://twitter.com/arieljt).
* [YARI](https://github.com/avast/yari) ⭐ 90 | 🐛 13 | 🌐 Rust | 📅 2025-09-10
  * Interactive debugger for the YARA language written in Rust.
* [yara-parser](https://github.com/Northern-Lights/yara-parser) ⭐ 86 | 🐛 1 | 🌐 Go | 📅 2026-05-05
  * Tools for parsing rulesets using the exact grammar as YARA. Written in Go.
* [yara-rust](https://github.com/Hugal31/yara-rust) ⭐ 81 | 🐛 17 | 🌐 Rust | 📅 2026-06-10
  * Rust bindings for VirusTotal/Yara
* [AutoYara](https://github.com/NeuromorphicComputationResearchProgram/AutoYara) ⭐ 78 | 🐛 3 | 🌐 Java | 📅 2025-10-08
  * Automated Yara Rule generation using Biclustering
* [factual-rules-generator](https://github.com/CIRCL/factual-rules-generator) ⭐ 75 | 🐛 1 | 🌐 Python | 📅 2022-01-18
  * Factual-rules-generator is an open source project which aims to generate YARA rules about installed software from a running operating system.
* [YLS](https://github.com/avast/yls) ⭐ 74 | 🐛 26 | 🌐 Python | 📅 2026-02-03
  * Language server for YARA to intergrate with e.g. vscode or vim. Offers code completion, function documentation, code formatting, debugging, ...
* [yara\_tools](https://github.com/matonis/yara_tools) ⭐ 73 | 🐛 7 | 🌐 Python | 📅 2019-01-12
  * Python bindings to author YARA rules using natural Python conventions.
* [Yaramanager](https://github.com/3c7/yaramanager) ⚠️ Archived ([PyPI](https://pypi.org/project/yaramanager/))
  * Command line tool to manage and organize your Yara ruleset.
* [YaYaGen](https://github.com/jimmy-sonny/YaYaGen) ⭐ 65 | 🐛 1 | 🌐 Python | 📅 2018-10-09
  * YARA rule generator for Android malware.
* [malwatch](https://github.com/defended-net/malwatch) ⭐ 64 | 🐛 0 | 🌐 Go | 📅 2026-07-25
  * Fast and lightweight malware scanner written in go that is ideal for Linux based web server environments. Currently used with some of the internet's largest deployments.
* [yaraZeekAlert](https://github.com/SCILabsMX/yaraZeekAlert) ⭐ 62 | 🐛 2 | 🌐 Python | 📅 2023-12-16 :sparkles:
  * Scans files with YARA rules and send email alerts which include network context of the file transfer and attaches the suspicious file if it is less than 10 MB.
* [FARA](https://github.com/bartblaze/FARA) ⭐ 61 | 🐛 0 | 🌐 YARA | 📅 2025-07-23
  * FARA, or Faux YARA, is a simple repository that contains a set of purposefully erroneous Yara rules. It is meant as a training vehicle for new security analysts, those that are new to Yara and even Yara veterans that want to keep their rule writing (and debugging) sharp.
* [libyara.NET](https://github.com/microsoft/libyara.NET) ⭐ 60 | 🐛 6 | 🌐 C++ | 📅 2026-01-08
  * .NET wrapper for libyara built in C++ CLI used to easily incorporate yara into .NET projects
* [Yara Python ICAP Server](https://github.com/RamadhanAmizudin/python-icap-yara) ⭐ 58 | 🐛 0 | 🌐 Python | 📅 2024-12-19
  * ICAP server with YARA scanner.
* [YaraManager](https://github.com/kevthehermit/YaraManager) ⚠️ Archived
  * Web based manager for YARA rules.
* [static\_file\_analysis](https://github.com/lprat/static_file_analysis) ⭐ 51 | 🐛 1 | 🌐 YARA | 📅 2023-09-06
  * Analyze deeply embedded files (doc, pdf, exe, ...) with clamscan and YARA.
* [Yobi](https://github.com/imp0rtp3/Yobi) ⭐ 50 | 🐛 0 | 🌐 JavaScript | 📅 2021-09-05 :sparkles:
  * Yobi is a basic firefox extension which allows to run public or private YARA rules on all scripts and pages rendered by the browser.
* [Yara-Scanner](https://github.com/PolitoInc/Yara-Scanner) ⭐ 48 | 🐛 3 | 🌐 Python | 📅 2016-06-30
  * Python-based extension that integrates a YARA scanner into Burp Suite.
* [OCYara](https://github.com/bandrel/OCyara) ⭐ 42 | 🐛 3 | 🌐 Python | 📅 2018-10-30
  * Performs OCR on image files and scans them for matches to YARA rules.
* [YaraSharp](https://github.com/stellarbear/YaraSharp) ⭐ 42 | 🐛 4 | 🌐 C | 📅 2022-02-07
  * C# wrapper around the Yara pattern matching library
* [Yara-Validator](https://github.com/CIRCL/yara-validator) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2020-09-05
  * Validates YARA rules and tries to repair the broken ones.
* [base64\_substring](https://github.com/DissectMalware/base64_substring) ⭐ 40 | 🐛 1 | 🌐 Python | 📅 2018-07-13
  * Generate YARA rules to match terms against base64-encoded data.
* [dnYara](https://github.com/airbus-cert/dnYara) ⭐ 39 | 🐛 6 | 🌐 C# | 📅 2023-06-30
  * A multi-platform .NET wrapper library for the native YARA library.
* [yaradbg-frontend](https://github.com/DissectMalware/yaradbg-frontend) ⭐ 38 | 🐛 0 | 🌐 JavaScript | 📅 2024-01-24 :eyes:
  * YaraDbg is a free web-based Yara debugger to help security analysts to write hunting or detection rules with less effort and more confidence.
* [Yara Malware Quick menu scanner](https://github.com/techbliss/Yara_Mailware_Quick_menu_scanner) ⭐ 38 | 🐛 0 | 📅 2016-03-26
  * Adds the awsome YARA pattern scanner to Windows right click menus.
* [YaraGen](https://github.com/mrexodia/YaraGen) ⭐ 37 | 🐛 0 | 🌐 C | 📅 2017-09-02 and [yara\_fn](https://github.com/williballenthin/idawilli/tree/master/scripts/yara_fn) ⭐ 198 | 🐛 13 | 🌐 Python | 📅 2026-08-28
  * Plugins for x64dbg and IDAPython, respectively, that generate YARA rules from function blocks.
* [YaraStation](https://github.com/NumLocK15/yarastation) ⭐ 36 | 🐛 1 | 🌐 JavaScript | 📅 2022-02-01
  * Yara station is a managment portal designed to facilitate the use of Loki scanner.
* [clara](https://github.com/abhinavbom/clara) ⭐ 34 | 🐛 17 | 🌐 Python | 📅 2026-01-14 :sparkles:
  * Serverless, real-time, ClamAV+Yara scanning for your S3 Buckets.
* [VirusTotalTools](https://github.com/silascutler/VirusTotalTools) ⭐ 34 | 🐛 0 | 🌐 Python | 📅 2018-03-02
  * Tools for checking samples against Virus Total, including VT\_RuleMGR, for managing threat hunting YARA rules.
* [ELAT](https://github.com/reed1713/ELAT) ⭐ 31 | 🐛 0 | 🌐 Python | 📅 2016-09-27
  * Event Log Analysis Tool that creates/uses YARA rules for Windows event log analysis.
* [PwC Cyber Threat Operations rtfsig](https://github.com/PwCUK-CTO/rtfsig) ⭐ 29 | 🐛 0 | 🌐 Rich Text Format | 📅 2026-01-05
  * This tool is designed to make it easy to signature potentially unique parts of RTF files.
* [yarg](https://github.com/immortalp0ny/yarg) ⭐ 29 | 🐛 0 | 🌐 Python | 📅 2025-06-06
  * IDAPython plugin for gerenating YARA rules from x86/x86-64 code.
* [Fadavvi YARA collection script](https://github.com/Fadavvi/Yara-Repo) ⭐ 28 | 🐛 0 | 🌐 Shell | 📅 2023-08-26
* [ida-yara-processor](https://github.com/bnbdr/ida-yara-processor) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2019-01-22
  * IDA processor for compiled YARA rules.
* [yaraMail](https://github.com/kevthehermit/yaraMail) ⭐ 28 | 🐛 2 | 🌐 Python | 📅 2019-11-05
  * YARA scanner for IMAP feeds and saved streams.
* [Yarasilly2](https://github.com/YARA-Silly-Silly/yarasilly2) ⭐ 28 | 🐛 45 | 🌐 Python | 📅 2026-07-10
  * A Semi automatic handy tool to generate YARA rules from sample virus files ( WIP ) for Malware Analyst, inspired by DIFF function of VirusTotal Premium Account.
* [yaradbg-backend](https://github.com/DissectMalware/yaradbg-backend) ⭐ 25 | 🐛 0 | 🌐 Python | 📅 2024-01-08 :gem:
  * YaraDbg is a free web-based Yara debugger to help security analysts to write hunting or detection rules with less effort and more confidence.
* [yarascanner](https://github.com/jheise/yarascanner) ⭐ 25 | 🐛 2 | 🌐 Go | 📅 2017-07-06
  * Golang-based web service to scan files with YARA rules.
* [ida\_yara](https://github.com/alexander-hanel/ida_yara) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2018-09-04
  * Scan data within an IDB using YARA.
* [Cloudina Security Hawk](https://github.com/cloudina/hawk) ⭐ 22 | 🐛 5 | 🌐 Go | 📅 2024-09-01 :sparkles:
* [yaml2yara](https://github.com/nccgroup/yaml2yara) ⭐ 22 | 🐛 0 | 🌐 HTML | 📅 2020-02-03
  * Generate bulk YARA rules from YAML input.
* [Audit Node Modules With YARA Rules](https://github.com/rpgeeganage/audit-node-modules-with-yara) ⭐ 20 | 🐛 0 | 🌐 YARA | 📅 2021-03-24
  * Run a given set of YARA rules against the given node\_module folder
* [ExchangeFilter](https://github.com/k-sec-tools/ExchangeFilter) ⭐ 19 | 🐛 0 | 🌐 C# | 📅 2021-08-25
  * MS Exchange transport agent uses YARA to detect malware in email messages.
* [Yara Scanner](https://github.com/ace-ecosystem/yara_scanner) ⭐ 19 | 🐛 2 | 🌐 Python | 📅 2022-12-08
  * A wrapper around the yara-python project the providing multiple capabilities.
* [alterix](https://github.com/mtnmunuklu/alterix) ⭐ 17 | 🐛 1 | 🌐 Go | 📅 2025-01-26
  * Converts Yara rules to the query language of CRYPTTECH's SIEM
* [plast](https://github.com/sk4la/plast) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2020-07-20
  * Threat hunting tool for detecting and processing IOCs using YARA under the hood.
* [a-ray-grass](https://github.com/hashlookup/a-ray-grass) ⭐ 14 | 🐛 1 | 🌐 C | 📅 2022-08-19
  * YARA module that provides support for bloom filters in yara. In the context of [hashlookup.io](https://hashlookup.io/), it allows to quickly discard known files before any further analysis.
* [node-yara](https://github.com/nospaceships/node-yara) ⭐ 14 | 🐛 3 | 🌐 C++ | 📅 2021-05-19
  * YARA support for Node.js.
* [statiStrings](https://github.com/Sh3llyR/statiStrings) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2021-07-24
  * Strings statistics calculator for YARA rules.
* [malscan](https://github.com/usualsuspect/malscan) ⭐ 13 | 🐛 0 | 🌐 C | 📅 2018-05-15
  * Scan process memory for YARA matches and execute Python scripts if a match is found.
* [YARA-sort](https://github.com/horsicq/YARA-sort) ⭐ 13 | 🐛 0 | 🌐 YARA | 📅 2026-08-31
  * Aggregate files into collections basd on YARA rules. [blog](https://n10info.blogspot.com/2019/10/nfd-sort.html)
* [yara\_zip\_module](https://github.com/stoerchl/yara_zip_module) ⭐ 13 | 🐛 1 | 🌐 C | 📅 2022-10-21
  * Search for strings inside a zip file.
* [IDA\_scripts](https://github.com/swackhamer/IDA_scripts) ⭐ 12 | 🐛 1 | 🌐 Python | 📅 2017-11-02
  * IDA Python scripts for generating YARA sigs from executable opcodes (.NET included).
* [AIDebug](https://github.com/anpa1200/AIDebug) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2026-08-13
  * AI-assisted malware reverse-engineering debugger that emits analyst-review YARA candidates, ATT\&CK mappings, IOCs, JSON, and HTML reports.
* [yara-ocaml](https://github.com/XVilka/yara-ocaml) ⚠️ Archived
  * OCaml bindings for YARA
* [yara-procdump-python](https://github.com/google/yara-procdump-python) ⚠️ Archived
  * Python extension to wrap the YARA process memory access API.
* [yaraScanParser](https://github.com/Sh3llyR/yaraScanParser) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2021-04-25
  * Parsing tool for [Yara Scan Service](https://riskmitigation.ch/yara-scan/)'s JSON output file.
* [shotgunyara](https://github.com/darienhuss/shotgunyara) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2022-08-29
  * Given a string, create 255 xor encoded versions of that string as a YARA rule.
* [yaraparser](https://github.com/BitsOfBinary/yaraparser) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2020-07-12
  * Python 3 tool to parse Yara rules.
* [decompressingyara](https://github.com/rjzak/decompressingyara) ⭐ 7 | 🐛 0 | 🌐 Go | 📅 2023-04-24
  * For when your malware samples are stored compressed, but you still want to run rules against them.
* [yara-java](https://github.com/subreption/yara-java) ⭐ 7 | 🐛 2 | 🌐 Java | 📅 2024-10-11
  * Java bindings for YARA (Subreption fork, maintained as of 2024, [old bindings](https://github.com/p8a/yara-java) ⭐ 28 | 🐛 6 | 🌐 Java | 📅 2024-06-05).
* [androguard-yara](https://github.com/MindMac/androguard-yara) ⭐ 6 | 🐛 0 | 🌐 C | 📅 2015-09-25
  * Androguard module for Yara.
* [GhidraYara](https://github.com/subreption/ghidra_yara) ⭐ 5 | 🐛 0 | 🌐 YARA | 📅 2024-10-11
  \- A Ghidra extension providing direct integration of YARA through an analyzer, as well as rule generation from code listings and management in the Ghidra UI. Supports an extensive library of cryptographic constants, CRC tables, etc.
* [ocaml-yara](https://github.com/elastic/ocaml-yara) ⚠️ Archived
  * OCaml bindings to libyara
* [yaraVT](https://github.com/deadbits/yaraVT) ⚠️ Archived
  * Scan files with Yara and send rule matches to VirusTotal reports as comments.
* [YMCA](https://github.com/m0n4/YARA-Matches-Correspondance-Array) ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2022-02-06
  * Displays a table of matches between YARA rules and a collection of samples.
* [java2yara](https://github.com/fxb-cocacoding/java2yara) ⭐ 3 | 🐛 2 | 🌐 Java | 📅 2022-05-20
  * A minimal library to generate YARA rules from JAVA
* [YaraFileCheckerLib](https://github.com/k-sec-tools/YaraFileCheckerLib) ⭐ 2 | 🐛 0 | 🌐 YARA | 📅 2022-02-07
  * .Net Library designed to make it easier to check potentially malicious files and archives using YARA and make a decision about their harmfulness based on the weights of the detected rules.
* [nullsec-yara](https://github.com/bad-antics/nullsec-yara) ⭐ 1 | 🐛 0 | 🌐 Clojure | 📅 2026-02-27
  * YARA rule development toolkit with rule generation, optimization, and testing capabilities.
  * Multi Cloud antivirus scanning API based on CLAMAV and YARA for AWS S3, AZURE Blob Storage, GCP Cloud Storage.
* [CSE-CST AssemblyLine](https://bitbucket.org/cse-assemblyline/alsvc_yara)
  * The Canadian Communications Security Establishment (CSE) open sourced [AssemblyLine](https://cyber.gc.ca/en/assemblyline), a platform for analyzing malicious files. The component linked here provides an interface to YARA.
* [Fibratus](https://www.fibratus.io)
  * A modern tool for Windows kernel exploration and observability with a focus on security and [support for YARA](https://www.fibratus.io/#/filters/functions?id=yara-functions).
* [Invoke-Yara](https://github.com/secabstraction/Yara)
  * Powershell scripts to run YARA on remote machines.
* [Malcat](https://malcat.fr)
  * Hexadecimal editor, disassembler and decompiler for malware analysis. Embeds both a YARA scanner and rule editor for easy in-app rule creation. Free and paid versions are available.
* [Manalyzer Yara Validator](https://yaravalidator.manalyzer.org/)
  * Compile your rules on all yara versions online to detect compatibility issues!
* [ndaal YARA ruleset checker](https://gitlab.com/ndaal_open_source/ndaal_yara_nyc)
  * ndaal YARA ruleset checker, Open Source
* Nextron Systems OSS and Commercial Tools (Florian Roth: @Neo23x0)
  * [Loki](https://github.com/Neo23x0/Loki) ⭐ 3,787 | 🐛 18 | 🌐 Python | 📅 2026-01-12 IOC and YARA rule scanner implemented in Python. Open source and free.
  * [THOR Lite](https://www.nextron-systems.com/thor-lite/) IOC and YARA rule scanner implemented in Go. Closed source, free, but registration required.
* [osquery](https://osquery.readthedocs.io/en/stable/deployment/yara/)
  * YARA-based scanning with osquery.
* [UXProtect](https://digitasecurity.com/uxprotect/)
  * The missing UI to Apple's built-in XProtect YARA signatures. Enumerate signatures, scan files, and more.
* [YARA-CI](https://yara-ci.cloud.virustotal.com/) :sparkles:
  * YARA-CI helps you to keep your YARA rules in good shape. It can be integrated into any GitHub
* [yaramail](https://seanthegeek.github.io/yaramail/)
  * A YARA scanner designed for phishing triage automation. Categorizes emails email authentication, attachments, and normalized body content.
* [Yara Toolkit](https://yaratoolkit.securitybreak.io/)
  * This is the Yara editor. You can write your own Yara rules or copy paste one to edit it.

## Services

* [Hybrid Analysis YARA Search](https://www.hybrid-analysis.com/yara-search)
  * YARA search / hunting from CrowdStrike / Hybrid Analysis, powered by Falcon MalQuery.
* [InQuest Labs](https://labs.inquest.net) :sparkles: :gem:
  * See the YARA section for helper routines to convert regular expressions to match on base64 encoded strings, conver strings to sequences of uint() lookups, and more.
* [Koodous](https://koodous.com/)
  * Collaborative platform for APK analysis, with community YARA rule repository and large APK sample dataset.
* [MalShare](https://malshare.com/)
  * Free malware repository providing researchers access to samples, malicous feeds, and YARA results.
* [MalwareConfig](https://malwareconfig.com/)
  * Extract IOCs from Remote Access Trojans.
* [YaraEditor (Web)](https://www.adlice.com/download/yaraeditorweb/)
  * All-in-one website to create and manage YARA rules.
* [YARAify](https://yaraify.abuse.ch/):sparkles:
  * YARAify is a project from abuse.ch that allows anyone to scan suspicious files such as malware samples or process dumps against a large repository of YARA rules.
* [Yara Scan Service](https://riskmitigation.ch/yara-scan/)
  * A simple service to test your Yara rules against a large set of malicious and identified files.

## Syntax Highlighters

* Notepad++: [userDefinedLanguages](https://github.com/notepad-plus-plus/userDefinedLanguages/blob/master/udl-list.md) ⭐ 815 | 🐛 0 | 🌐 Python | 📅 2026-08-24
* Visual Studio Code: [vscode-yara](https://github.com/infosec-intern/vscode-yara) ⭐ 62 | 🐛 13 | 🌐 TypeScript | 📅 2024-01-10
* Atom: [language-yara](https://github.com/blacktop/language-yara) ⚠️ Archived
* Sublime Text: [YaraSyntax](https://github.com/nyx0/YaraSyntax/) ⭐ 19 | 🐛 0 | 🌐 YARA | 📅 2025-11-30
* Vim: [vim-yara](https://github.com/yaunj/vim-yara) ⭐ 14 | 🐛 0 | 🌐 Vim script | 📅 2021-02-18, [vim-syntax-yara](https://github.com/s3rvac/vim-syntax-yara) ⭐ 31 | 🐛 0 | 🌐 Vim Script | 📅 2026-04-19
* Emacs: [yara-mode](https://github.com/binjo/yara-mode) ⭐ 7 | 🐛 0 | 🌐 Emacs Lisp | 📅 2026-07-02
* GTK-based editors, like gedit and xed: [GtkSourceView-YARA](https://github.com/wesinator/GtkSourceView-YARA) ⚠️ Archived

## People

We're aggregating the Twitter handles for anyone involved with the projects on this page into a single list: [awesome-yara Twitter list](https://twitter.com/InQuest/lists/awesome-yara). Do let us know if anyone is missing.

## Videos and Talks

* [Finding Evil with YARA](https://www.youtube.com/watch?v=mQ-mqxOfopk)
* [SAS2018: Finding aliens, star weapons and ponies with YARA](https://www.youtube.com/watch?v=fbidgtOXvc0)
* [Costin Raiu - Combining code similarity with Yara to find goodies](https://www.youtube.com/watch?v=DQXpdEvyasc)
* [YARA Rule Processing Sessions - Florian Roth](https://www.youtube.com/playlist?list=PL8OlALxRcWsSEPtN6AujulTHVc9HZMwso)
* [Upping the APT hunting game: learn the best YARA practices from Kaspersky](https://securelist.com/yara-webinar-follow-up/96505/)
* [Star-Gazing | Using a Full Galaxy of YARA Methods to Pursue an Apex Actor | By Greg Lesnewich](https://www.youtube.com/watch?v=aaV7UieJ_l4)
* [Lightweight Binary Similarity - YARA Using PE Features for Quick Wins](https://github.com/g-les/YARA-PE-Features) ⭐ 4 | 🐛 0 | 📅 2021-10-07
* [DEF CON 26 - Andrea Marcelli - Looking for the perfect signature an automatic YARA rules](https://www.youtube.com/watch?v=Dz0C55Azn1Y)

## Related Awesome Lists

* [HackwithGithub](https://github.com/Hack-with-Github/Awesome-Hacking) ⭐ 119,551 | 🐛 40 | 📅 2026-07-26
* [OSINT](https://github.com/jivoi/awesome-osint) ⭐ 29,106 | 🐛 16 | 📅 2026-08-25
* [Pentesting](https://github.com/enaqx/awesome-pentest) ⭐ 27,099 | 🐛 109 | 📅 2026-07-25
* [Hacking](https://github.com/carpedm20/awesome-hacking) ⭐ 16,995 | 🐛 70 | 📅 2024-06-02
* [Security](https://github.com/sbilly/awesome-security) ⭐ 14,822 | 🐛 321 | 📅 2026-01-11
* [Static Analysis](https://github.com/analysis-tools-dev/static-analysis) ⭐ 14,758 | 🐛 12 | 🌐 Rust | 📅 2026-08-30
* [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis) ⭐ 14,178 | 🐛 25 | 📅 2024-06-07
* [Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) ⭐ 10,589 | 🐛 118 | 📅 2026-05-31
* [Honeypots](https://github.com/paralax/awesome-honeypots) ⭐ 10,542 | 🐛 24 | 🌐 Python | 📅 2026-06-01
* [Incident-Response](https://github.com/meirwah/awesome-incident-response) ⭐ 9,369 | 🐛 77 | 📅 2026-07-15
* [ML for Cyber Security](https://github.com/jivoi/awesome-ml-for-cybersecurity) ⭐ 9,347 | 🐛 29 | 📅 2024-08-19
* [Crawler](https://github.com/BruceDone/awesome-crawler) ⭐ 7,303 | 🐛 41 | 📅 2024-06-16
* [Infosec](https://github.com/onlurking/awesome-infosec) ⭐ 5,735 | 🐛 17 | 📅 2026-08-28
* [Forensics](https://github.com/Cugu/awesome-forensics) ⭐ 5,172 | 🐛 10 | 📅 2026-08-23
* [Threat Detection](https://github.com/0x4D31/awesome-threat-detection) ⭐ 4,717 | 🐛 53 | 📅 2026-01-05
* [Reversing](https://github.com/tylerha97/awesome-reversing) ⭐ 4,518 | 🐛 18 | 📅 2023-08-19
* [CVE PoC](https://github.com/qazbnm456/awesome-cve-poc) ⭐ 3,530 | 🐛 2 | 📅 2022-01-04
* [PCAP Tools](https://github.com/caesar0301/awesome-pcaptools) ⭐ 3,418 | 🐛 14 | 📅 2025-09-03
* [IOCs](https://github.com/sroberts/awesome-iocs) ⭐ 999 | 🐛 7 | 🌐 Shell | 📅 2026-08-29

## Contributing

This list is maintained by [InQuest](https://inquest.net/). Feel free to let us
know about anything we're missing!

See [CONTRIBUTING.md](CONTRIBUTING.md).

### Contributors

[![awesome-yara contributors](https://contrib.rocks/image?repo=inquest/awesome-yara\&max=100)](https://github.com/inquest/awesome-yara/graphs/contributors) ⭐ 4,268 | 🐛 2 | 📅 2026-06-15

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-02._
