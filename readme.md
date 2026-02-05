# RiotHub Custom

**⚠️ PROJEKT EINGESTELLT / DISCONTINUED**

Dieses Repository enthält den Quellcode für einen Custom League of Legends Client. Die Entwicklung wurde eingestellt, da das Projektziel nicht mehr verfolgt wird.

Die Entscheidung, den Client nicht weiterzuentwickeln, basiert auf folgenden technischen und strukturellen Hürden:

1.  **Riot Vanguard & Anti-Cheat Kompatibilität**
    Mit der tiefen Integration von Vanguard (Kernel-Level Anti-Cheat) wird das Starten des Spiels über Drittanbieter-Clients zunehmend erschwert. Eine Umgehung des offiziellen Launchers stellt ein Sicherheitsrisiko dar und könnte fälschlicherweise als Manipulationsversuch erkannt werden.

2.  **Hoher Wartungsaufwand (Patch-Zyklen)**
    Riot Games aktualisiert den Client und die LCU-API (League Client Update) in sehr kurzen Abständen (ca. alle 2 Wochen). Da es keine offizielle Dokumentation für den Launcher-Prozess gibt, würde jedes Update des Spiels potenzielle Breaking Changes verursachen, die den Custom Client sofort unbrauchbar machen.

3.  **Terms of Service (ToS) & Account-Sicherheit**
    Die Nutzung von inoffiziellen Launchern bewegt sich in einer Grauzone. Um die Sicherheit der Nutzer-Accounts (Bans durch False-Positives) nicht zu gefährden, ist die Einstellung des Projekts die einzig verantwortungsvolle Entscheidung.

4.  **Backend-Abhängigkeit**
    Ein Custom Client benötigt eine permanente, serverseitige Infrastruktur, um mit den Riot-Servern Schritt zu halten. Der Aufwand, diese Infrastruktur sicher und aktuell zu halten, steht in keinem Verhältnis zum Nutzen gegenüber dem offiziellen Client.

## 📝 Fazit

Das Projekt war ein hervorragender "Proof of Concept", um die Architektur von Electron-Anwendungen und die Interaktion mit externen Prozessen via Node.js zu erlernen. Für den produktiven Einsatz ist dieser Ansatz jedoch aufgrund der geschlossenen Architektur des Spiels nicht nachhaltig.

---
*Created by [LukxsDE]*
