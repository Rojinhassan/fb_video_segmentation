# CNN

## Challanges/ Probleme:
Es können verschiedene Probleme/challanges auftretten:
- Wenn wir uns auf das Video chatten konzentrieren, kann es passieren, dass unser CNN nicht eingenerelles fg/bg estimation durchführt, sonder einfach generell den Menschen im Video als Forground setzt. Die Frage ist, wollen wir ein allgemeines CNN, dass auf verschiedene scenarios anwendbar ist, oder eines, dass nur auf das Video chatten spezialisiert ist. Denn diese Art von Overfitting könnte man auch zum Vorteil nutzen.


## Fragen:
1. Wie schaffe ich es, dass die vergangenen informationen in mein CNN mitverarbeitet werden?
  - Man muss irgendiwe das alte Bild zum neuen in relation setzen. Die Frage ist, lassen wir das von unser CNN diese relation von _ganz selbst bestimmen_ oder fürgen wir sowas wie eine Color Error Funktopn manuel ein?

2. Machen wir eine art Hybried CNN oder eine reine CNN?

3. 3nd-to-end
  - Was ist das?
  - Warum ist das so wichtig?
  -


## Ideen:
- **Collor Error Funktion** *(Zu Frage 1)*: Die die veränderung der Farben oder Grauenstufe der einzelnen Pixel vom Vergangenen Bild fg zum neuen berechneten fg misst.
  - Vorraussetzung: Wir gehen davon aus, dass unser zu betrachtender Vorground stehts im Bild ist. Was aber in eienr Video Call nicht immer der Fall ist
