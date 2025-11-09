A Java bug detection tool developed on top of Facebook Infer.

TACAS25:
Install using Infer's instruction. 
Disable/Enable casting error detection: 
comment/uncomment line 1252 in infer/src/pulse/PulseModelsJava.ml 
run a maven program cd to the top directory and using: sudo infer --pulse-only -- mvn clean compile
run a gradle program cd to the top directory and using: sudo infer --pulse-only -- ./gradlew build
