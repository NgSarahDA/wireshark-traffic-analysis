# wireshark-traffic-analysis
Analyse du trafic réseau général avec Wireshark
# Analyse de Trafic Réseau avec Wireshark

## Description
Ce projet vise à capturer et analyser le trafic réseau général d'une machine 
pour comprendre comment fonctionnent les protocoles réseau et identifier 
les différents types de flux de données circulant sur le réseau.

## Objectifs
- Comprendre le fonctionnement du trafic réseau en conditions réelles
- Identifier et analyser les protocoles réseau principaux (TCP/IP, UDP, DNS, HTTP)
- Développer des compétences pratiques en capture et analyse de trafic
- Apprendre à utiliser Wireshark comme outil d'analyse réseau

## Outils utilisés
- **Wireshark** : Capture et analyse de trafic réseau
- **Système d'exploitation** : [Windows]

## Méthodologie
1. Lancement de Wireshark sur l'interface réseau principale
2. Capture du trafic réseau pendant [durée : 20 sec]
3. Filtrage et analyse des paquets capturés
4. Identification des protocoles et des flux principaux
5. Documentation des findings clés

## Résultats & Findings
**Durée de capture**: 20.04 secondes
**Interface réseau**: Wi-Fi
**Nombre de paquets**: 461
**Protocole identifiés**:
- TCP
- HTTP
L'analyse des paquets montre un trafic de paquets essentiellement constitué de paquets TCP sur IPv4.
Les échanges sont principalement une communication locale entre des applications.
Un service HTTP est accessible sur le port TCP  19575.
Les échange comprennent plusieurs ouvertures et fermetures de connexions TCP.

## Screenshots
[screenshots de Wireshark]<img width="1917" height="1020" alt="Capture d&#39;écran 2026-10-03 155531" src="https://github.com/user-attachments/assets/89757b9d-c78f-499e-9071-0282ce9f160e" />


## Conclusion
cette analyse m'a permis d'apprendre à utiliser Wireshark pour capturer et analyser le trafic réseau. En cybersécurité, cet outil est utile pour détecter les activités suspectes, identifier les failles et renforcer la sécurité des réseaux.
