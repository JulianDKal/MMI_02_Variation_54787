Bearbeiter: Julian Kalkmann
## Breath Easy Studie mit Mobilgeräten
In der Studie geht es um frühzeitiges Erkennen von Atemwegserkrankungen mit den multimodalen Sensoren von Smartphones und Smartwatches. Die Sensoren der Geräte erkennen dabei verschiedene sogenannte “Biomarker”, darunter z.B. das Verhältnis zwischen Ein- und Ausatmung. Dafür wurden Untersuchungen mit insgesamt 228 verschiedenen Patienten durchgeführt. Das entwickelte Modell soll sowohl chronische Atemwegserkrankungen (z.B. Asthma, COPD) als auch infektiöse Atemwegserkrankungen (z.B. COVID-19) feststellen können, da die Biomarker die selben sind. Die Atemfrequenz sowie Ein/Ausatmungsrate kann z.B. durch die gyroskopische/motosensorische Funktionen, also Bewegungssensoren des Smartphones gemessen werden. Die Herzschlagrate sowie Herzfrequenzvariabilität wird durch optische Sensoren, durch sogenannte _Photoplethysmographie_ bestimmt. Das Paper schlägt dabei zwei Modelle vor: Einmal nur mit dem Smartphone und einmal mit Smartphone und Smartwatch in Kombination, wobei bei letzterem noch bestimmte Messungen zwischen beiden Geräten verglichen werden können, was zur akkurateren Einschätzung der Biomarker führt. Die Studie kommt zu dem Schluss, dass der Einsatz von multimodalen Sensoren in Mobilgeräten eine kostensparende, unaufwendige sowie annähernd akkurate Alternative zu klinischen Erkennungsmöglichkeiten bieten kann.

![BreathEasy Bilder](img/Pasted_image.png)
## Multimodales Kontaktloses Erkennungssystem (von Atemwegserkrankungen)
Das Paper beschreibt ein tragbares, multimodales Sensorsystem zur Überwachung der Atemfunktion. Es kombiniert _piezoelektrische Schallsensoren_ zur Erfassung von Lungengeräuschen und _ECG-Sensoren_ zur Messung der Herzaktivität, um Atemmuster und Symptome wie flaches Atmen und Husten zu analysieren. Durch die Fusion von Lungengeräusch- und ECG-Signalen wird eine genauere Überwachung ermöglicht. Das System nutzt mathematische Methoden wie die Berechnung der Fläche unter der Kurve (AUC) und Signalverarbeitungstechniken, um verschiedene Atemvolumina und Abweichungen in den Atemmustern zu identifizieren. Ziel ist es, eine präzise und kontinuierliche Überwachung der Atemgesundheit zu ermöglichen und so die Früherkennung und Diagnose von Atemwegserkrankungen zu unterstützen.

## Erweiterung und Variation

|                                  | **Rahman et al., 2020**                                           | **Moon et al., 2023**                                |
| -------------------------------- | ----------------------------------------------------------------- | ---------------------------------------------------- |
| **Herzaktivität messen**         | _Photoplethysmographie,_ also optische Sensoren                   | ECG-Sensoren, also elektrische Sensoren              |
| **Atemfrequenz- und funktion**   | motosensorische Funktionen des Mobilgeräts, also Bewegungsmessung | _piezoelektrische Schallsensoren_, also Akkustik     |
| ***Sauerstoffgehalt (im Atem)*** | *Atmen in das Mobilgerät*                                         | *Passives Atmen, Aufnahme über das Erkennungssystem* |

![Neues Care Modell](img/SecondPaper_Illustration.png)
## Literaturverzeichnis
\[Rahman et al., 2020\] Md Mahbubur Rahman, Mohsin Yusuf Ahmed, Tousif Ahmed, Bashima Islam, Viswam Nathan, Korosh Vatanparvar, Ebrahim Nemati, Daniel McCaffrey, Jilong Kuang, and Jun Alex Gao. 2020. BreathEasy: Assessing Respiratory Diseases Using Mobile Multimodal Sensors. In Proceedings of the 2020 International Conference on Multimodal Interaction (ICMI '20). Association for Computing Machinery, New York, NY, USA, 41–49. https://doi.org/10.1145/3382507.3418852

\[Moon et al., 2023\] Moon, K.S.; Lee, S.Q. A Wearable Multimodal Wireless Sensing System for Respiratory Monitoring and Analysis. Sensors 2023, 23, 6790. https://doi.org/10.3390/s23156790



 
