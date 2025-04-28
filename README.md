RO:

   CIRCUITE ELECTRICE CU COMANDĂ ELECTRONICĂ


  Acest proiect reprezinta proiectul final pentru obtinerea atestarii de 
tehnician operator, thenica de calcul, realizat la finalizarea studiilor preuniversitare.

  Se prezinta o simpla implementare a unei automatizari rezidentiale, pentru circuite 
casnice de lumina si prize. Proiectul se imparte in doua parti distincte, aceea de eletrica
si aceea de automatizare. 

Partea electrica, se vizeaza un panou electric constituit din:
separatoare - pentru protectia la supratensiune; siguranta diferentiala RCBO pentru protectia
persoanelor la curenti reziduali; sigurante automate RCB pentru protectia la supracurent si scurt
circuit a circuitului; o priza de panou pentru alimentarea circuitului de comanda. 
Partea de comanda se constituie din o placa de relee, si o placuta de dezvoltare cu microcontroller
Arduino UNO. Placa de relee este conectata in configuratie "cap scara" cu fiecare din consumatorii 
din circuit. Placuta se conecteaza prin bluetooh la un telefon cu aplicatia specifica si detine 
configuratia prezentata in documentatie.

ENG:

   Electrical Circuits with Electronic Control 

   This project is the ,technical high-school, final project, for obtaining my operator technician, computation technics
certification in electronics and automations. It is presented as an implementation of a simple residential
automatization, for home circuits like for the room lights and the power sockets.

   The project is divided into 2 parts: intro the electrical circuit and the automation circuit. The electrical circuit is
composed out of several operating blocks that are interconnected. The main electrical panel ensures the protection
over the whole other part of the electrical system. It is composed out of a separator for protection against over
voltages; an RCBO (Residual Current Breaker with Over-Current) for protecting against the residual current that can
harm people; and several RCB (Miniature Circuit Breaker) for protecting against overcurrent and short circuit.

   The automation part is composed out of 3 blocks. The first ones being a series of switches, that connect in an "cap
scara" configuration with the relays contacts, so the user can operate the lights as usual without any automation. The
second bock is the relay board that is connected between the controller and the power circuits. It has the role of
making possible the "connection" between the controller and the electrical system. The last block is the controller,
witch is an Arduino UNO based circuit, that uses a Bluetooth module in order to connect to a smartphone. From a
certain configured android app the automation and the wireless control of the electrical circuits is possible.
