# Ansible Playbooks

Dieses Repository enthält Ansible-Playbooks zur Automatisierung von Serverkonfigurationen und -management. Die Playbooks sind so strukturiert, dass sie einfach verwendet und angepasst werden können, um verschiedene Aufgaben zu erfüllen.

## Inhaltsverzeichnis

- [Voraussetzungen](#voraussetzungen)
- [Installation](#installation)
- [Verwendung](#verwendung)
- [Playbooks](#playbooks)

## Voraussetzungen

- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) muss auf deinem System installiert sein.
- Ein Zugriff auf die Zielserver über SSH mit den entsprechenden Berechtigungen.

## Installation

1. Klone das Repository:

   ```bash
   git clone https://github.com/ARoloo/ansible-library.git
   cd ansible-library
   ```

2. Stelle sicher, dass alle Abhängigkeiten installiert sind, falls vorhanden.

## Verwendung

Um ein Playbook auszuführen, verwende den folgende Befehl:

```bash
ansible-playbook -i inventory setip.yaml
```

Ersetze setup.yml durch den Namen des Playbooks, das du ausführen möchtest, und inventory durch den Pfad zu deiner Inventardatei.

## Playbooks
