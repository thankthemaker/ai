# Artificial Intelligence
ThankTheMaker Artificial Intelligence Github pages

## Reinforcement Learning am Beispiel des Spiels "Snake"

Im Rahmen eines Schul-Workshops haben wir am Beispiel des Spiels "Snake" demonstriert und erkläutert, wie eine Maschine selbstständig lernen kann. Ähnlich wie ein Baby oder Kleinkind, lernt die Maschine durch Ausprobieren und entsprechende Rückmeldung, ob ein Zug gut, schlecht oder neutral war.

<img src="https://cloud.githubusercontent.com/assets/2750531/24808769/cc825424-1bc5-11e7-816f-7320f7bda2cf.gif" width="300px"><img src="https://cloud.githubusercontent.com/assets/2750531/24810302/9e4d6e86-1bca-11e7-869b-fc282cd600bb.gif" width="300px">

Der Source-Code findet sich in folgendem Github-Repository [snake-ai-reinforcement](https://github.com/thankthemaker/snake-ai-reinforcement)

In dem Spiel wird ein Deep-Q-Network verwendet um ohne Modell und "Feature Engeneering" ein Spiel zu erlernen. Die Basis besteht  aus mehreren CNN (convolutional neural network), die durch das wiederholte Ausprobieren trainiert werden. Nach jedem Zug eines Spiels wird eine Belohnungsfunktion ausgeführt, die den Computer eine Rückmeldung über die Güte des Zugs gibt, d.h. ob dieser gut, schlecht oder neutral war. 

*Großer Dank geht an [Yuriy Guts](https://github.com/YuriyGuts), von dem das original Beispiel stammt.*

