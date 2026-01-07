# Detection and Analysis of Web Authentication Attacks in a DMZ Environment

## Overview
Questo progetto simula un’attività tipica di un Security Operations Center (SOC) di livello 1, focalizzata sulla detection e analisi di attività malevole dirette verso un sistema esposto in DMZ.

L’obiettivo non è la prevenzione dell’attacco, ma l’analisi post-evento tramite log centralizzati e la corretta classificazione degli eventi di sicurezza.

## Scenario
L’ambiente è composto da:
- Web Server Linux in DMZ (SSH e HTTP esposti)
- Host Windows interno (attività legittima / baseline)
- SIEM centralizzato (Splunk)
- Firewall perimetrale

## Attack Simulation
Lo scenario include:
- Network reconnaissance tramite Nmap
- Brute force HTTP tramite Hydra
- Tentativi di autenticazione legittimi da host interno
- Correlazione degli eventi tramite SIEM

## Project Structure
- `scenario/` – descrizione completa dello scenario e della topologia
- `reports/` – report SOC (SAL-1 style)
- `screenshots/` – evidenze a supporto dell’analisi

## Tools Used
- Splunk (SIEM)
- Splunk Universal Forwarder
- Nginx
- Hydra
- Nmap

## Skills Demonstrated
- Log analysis
- Event correlation
- SOC Level 1 triage
- False Positive vs True Positive classification
- MITRE ATT&CK mapping


