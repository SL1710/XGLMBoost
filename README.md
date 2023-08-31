# XGLMBoost

*XGLMBoost* ist der Versuch einer neuartigen Erweiterung für generalisierte lineare Modelle (GLM), die auf dem Konzept des Boosting basiert und vom XGBoost-Ansatz inspiriert ist. Diese Erweiterung zielt darauf ab, die Erklärbarkeit von GLMs durch die Kombination von Residuenanalyse und Boosting zu verbessern. Die Struktur basiert auf dem Projekt [pyLocalGLMnet](https://github.com/PK1706/pyLocalGLMnet) auf, welches eine Python-Implementierung des Richman/Wüthrich-Ansatzes zur Verfügung stellt.

Die Grundidee von XGLMBoost ist es, die Vorhersagegenauigkeit einer klassischen GLM durch die Integration von Boosting zu erhöhen und gleichzeitig die Interpretierbarkeit der Modellvorhersagen zu verbessern. Dies wird erreicht, indem die Residuen, d.h. die Unterschiede zwischen den beobachteten und den vorhergesagten Werten des GLM, als neues Trainingsziel für das Boosting behandelt werden. Dieser Ansatz ermöglicht eine gezielte Reduktion von Modellfehlern und gewährleistet gleichzeitig die Interpretierbarkeit der Modellvorhersagen.

## Projektdatei

Die Projektdatei befindet sich im Verzeichnis `src/XGLMBoost.ipynb`. Sie ist [hier](src/XGLMBoost.ipynb) zu finden.
