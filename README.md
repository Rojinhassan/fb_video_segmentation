# Masterarbeit


## Mein Plan:
1. *Basis Strucktur:* Ein EIGENSTÄNDIGES funktionierendes CNN/RNN architektur bauen, dass forground and backround video segmentation Prozess bewältigt.
  --> Ich glaub das ist sehr wichitig, denn wir wollen ja die performanc unseres Algorithmues maximieren, dafür müssen wir ganz genau wissen, was, wo und wie passiert! Wir müssen alle Einflussfaktoen voll unter kontrolle haben um es bei Bedarf optimieren können zu können.
2. *Verfeinerung:*  Auf der Basis kann man dann weitere Tweaks anwenden und damit rumspielen um den Prozess effizienter zu gestalten.
3. *Forschung:* Gegebenfalls andere gute Ideen von papern einbauen: z.b.: Optical-flow, tracking
4. *Eigene Ideen:* Eigene Ideen umsetzen.


---
## Toutor


### To-Do Toutor:
- [x] GutHub Repo
- [x] .md Text mit einem Plan
- [ ] Fragen

### Fragen am Toutor:
+ Welche Datenstrucktur und GPU packeses ich verwenden will
  --> Hat er preferencen? Wiel ich kann mich anpassen.
+ Tipps wie ich mein GitHub Repo ordentlich struckturieren könnte?
+ Tipps, wie cih mein Code Ordentlich struckturieren könnte?
+ Tensorflow or pytorch?
+ Kann ich erstmal eine normale fb segmentation CNN/RNN bauen und es dann später in dem eigendlichen video segmentation CNN/RNN einbauen?
+ Optical flow? tracking?
+ **Ich Frage ist:** *Ansatz_1:* Gehen wir einen etwas komplizierten Weg wie es in PRrMVOS versuchen wurde oder *Ansatz_2:* Gehen wir mit einer komplet neue Idee and die Sache ran?*
  - Mit beides ist eine Verbesserung zu erreichen.
  - Der zweite Ansatz ist riskanter aber dafür würde dieser bei einem Erfolg signifikant bessere Ergebnisse liefern.

#### DAVIS:
+ Was ist ein python wrapper?
+ Soll ich mit dem Datenset von DAVIS mit den angegebenen Programschnittstellen arbeiten und dehren hilfs tools benutzen oder soll ich einfach dehren Datenset nehmen und mir selber was aufbauen
    - Vorteil: Wäre eine sehr gute Übung
    - Eventueller Nachteil: Die Freage ist, ob ich mir damit wirklich Arbeit erspare, denn ich muss mich ja in den ganzen Skrioten und techniken derer einarbeiten. Was sagst du? Erspart man sich generell arbeit damit?
    - Eventueller Nachteil: Vielleicht muss ich auch die Implimentiereung durchführen um später unser Ergebniss mit den Methoden anderer zu vergelichen!?
    - Eventueller Nachteil: Verliere an performance boost?
