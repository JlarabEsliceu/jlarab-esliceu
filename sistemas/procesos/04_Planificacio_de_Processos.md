# Planificació de Processos

La planificació de processos és una part crucial de la gestió de sistemes microinformàtics i xarxes. Aquesta tasca és realitzada pel **planificador de processos**, una component essencial del sistema operatiu encarregada de decidir quin procés s'executarà a continuació. A continuació, es detallen alguns dels aspectes més importants de la planificació de processos:

## Objectius de la Planificació de Processos

1. **Rendiment**: Assegurar que el temps de CPU es utilitzi eficientment, maximitzant el rendiment del sistema.
2. **Equitat**: Proporcionar a tots els processos una oportunitat justa d'execució, evitant situacions d'inanició (starvation).
3. **Resposta Ràpida**: Minimitzar el temps d'espera dels usuaris i garantir una resposta ràpida a les sol·licituds.
4. **Priorització**: Assignar prioritats als processos segons la seva importància i urgència.

## Tipus de Planificació de Processos

### Planificació de Curt Terminis (CPU Scheduling)

La planificació de curt termini es centra en la selecció dels processos que s'executaran immediatament. El sistema operatiu ha de prendre decisions ràpides per garantir l'ús eficient de la CPU.

### Planificació de Mitjà i Llarg Terminis

La planificació de mitjà i llarg terminis s'enfoca en la gestió dels processos que no estan actualment en execució. Aquests processos poden estar a l'espera d'una entrada/sortida o ser traslladats a la memòria secundària.

### Preempció i No Preempció

- **Preempció**: El sistema operatiu pot interrompre l'execució d'un procés per donar prioritat a un altre. Això és comú en la planificació de curt termini.
- **No Preempció**: El procés en execució continua fins que finalitza o es bloqueja. Això és més freqüent en la planificació de mitjà i llarg terminis.


