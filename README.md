# Modelagem e Controle de Célula de Manufatura Automatizada

## 1. Contexto do Sistema
Este projeto visa a modelagem e a síntese de um supervisor para uma célula de manufatura automatizada, operando sob o paradigma de Sistemas a Eventos Discretos (SED). O sistema é caracterizado pelo compartilhamento de recursos críticos e restrições de capacidade que, sem o devido controle lógico, levam a estados de bloqueio (deadlock) e violação de especificações de segurança.

O objetivo fundamental da planta é transformar matéria-prima em produtos acabados através de estações de processamento paralelo, utilizando um robô manipulador para o transporte até uma zona de armazenamento temporário com capacidade finita.

## 2. Arquitetura da Planta

O sistema é composto por 4 subsistemas principais que interagem de forma síncrona:

### Máquinas 1 e 2

### Robô de Transporte

### Armazenamento Intermediário
