# 🛠️ Docker (Container) und Virtuelle Maschinen 

Dieses Projekt enthält Dateien und Informationen zu den folgenden Themen:

## 📦 Docker
- Docker ist eine Open-Source-Laufzeit, die Container bereitstellt.
- Container bieten eine isolierte Umgebung für Anwendungen, die den Kernel des Host-Betriebssystems teilen.
- Vorteile:
  - Leichtgewichtige Virtualisierung.
  - Portabilität und schnelle Bereitstellung.
- Einschränkungen:
  - Teilt den Kernel mit dem Host, was Sicherheitsrisiken birgt.

## 🖥️ Virtuelle Maschinen (VMs)
- Virtuelle Maschinen emulieren vollständige Computerumgebungen mit eigenem Betriebssystem und Kernel.
- Vorteile:
  - Vollständige Isolierung vom Host-System.
  - Ideal für sicherheitskritische Anwendungen.
- Nachteile:
  - Ressourcenschwerer und langsamer als Docker.

## 🛡️ Container und Sicherheit
- Container bieten Prozess- und Dateisystem-Isolierung.
- Virtuelle Festplatten allein bieten keinen Schutz, müssen in einer VM oder einem Container verwendet werden.
- Sicherheitsmaßnahmen:
  - Netzwerkisolierung (`--network none` in Docker).
  - Ressourcenbegrenzung durch cgroups.

## 🔄 Benutzer(wechsel) in Windows
- Der Benutzerwechsel (Switch User) ermöglicht es, zwischen Benutzerkonten zu wechseln, ohne die Sitzung zu beenden.
- Ähnlichkeiten mit Docker:
  - Abgetrennter Bereich und unterschiedliche Zugriffsrechte.
- Unterschiede:
  - Keine starke Isolierung wie bei Containern.
 
    
## 📂 Dateien im Projekt
- `containerVsVM.md`: Genaue betrachtung Unterschied von Container und Virtuele Maschinen. Sowie Docker spezifisches.
- `security_DockerandVF.md`: Zeigt scurity von Docker genauer und den Unterschied zu virtuellen Festplatten(VF for VM).
- `VM vs VF.md`: VM Vorteile on top zu virtuellen Festplatten (VF)
- `usegit.md`: Zeigt wieso hier .md files verwendet werden und wie sie anpassbar sind.
  
- `containers.json`: Beispiel für Container-Konfigurationen.
- `Dockerfile`: Beispiel für die Erstellung eines Docker-Containers.

    
## 📜 Lizenz
Dieses Projekt steht unter der [MIT-Lizenz](./LICENCE).
