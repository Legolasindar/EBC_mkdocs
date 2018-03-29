Protocol operatiu de comunicació «POC»
======================================

Aquí tens un resum del nostre POC organitzat per categories. És un protocol d'ús obligat dintre del grup.

Protocols
#########

Infanteria
----------

.. list-table::
   :widths: 600
   :header-rows: 0

   * - **Bàsics**
     
.. list-table::
   :widths: 15, 100
   :header-rows: 0
   
   * - **Establir primera comunicació entre unitats**
     - **Receptor + Emissor** / El receptor respon amb la mateixa formula.
   
       * *Alfa 1-1 aquí Delta 2-1*
       * *Delta 2-1 aquí Alfa 11*
       
   * - **Comunicació entre unitats**
     - **Receptor + Emissor + Missatge**
   
       * *Alfa 1-1 aquí Delta 2-1, enemic al sud de la vostra posició, a 500 metres.*

   * - **Alertar de contactes (genèric)**
     - **Identitat + Orientació + Distància + Informació addicional**
   
       * *Contactes enemics a l'Est a 700 metres, a la dreta del poble.*

   * - **Salt i cobertura**
     - **Cobrint / Saltant / Últim**
   
       * Unitat de foc "*Cobrint!*", unitat de maniobra "*Saltant!*", en arribar a posició "*Cobrint!*".
       * L'últim a saltar en arribar a la posició indica "*Últim!*".

   * - **Llançament de granades**
     - **Tipus + va!**
   
       * *Fragmentadora va!, Cegadora va!*
       
   * - **Postura**
     - **Perfil + baix/alt** | Baix de genolls, alt dempeus
   
       * *Perfil baix!*

.. list-table::
   :header-rows: 0

   * - **Antitanc**
     
.. list-table::
   :widths: 30, 100
   :header-rows: 0
       
   * - **Disparar un antitanc**
     - **Tipus + 6 lliures + foc (opcional)**
   
       * *AT4!, 6 lliures?*
       * **Confirmació:** *6 lliures!, disparant* (opcional)
       * **Negació:** *Negatiu! o Espera!*
       
.. list-table::
   :header-rows: 0

   * - **Llançagranades**
     
.. list-table::
   :widths: 30, 100
   :header-rows: 0

   * - **Ordre de foc inicial**
     - **Alerta + Direcció + Distància + Descripció + Mètode de foc**
   
       * *Granader, frontal, 300, des del búnquer 100 a la dreta, tropes al clar, foc ràpid i de cerca.*
 
   * - **Ordre de foc posterior**
     - **Desviació lateral + desviació longitudinal**
   
       * *Dreta 100, augmenta cinc zero.*
 
   * - **Disparant llançagranades**
     - **Tipus d'arma**
   
       * *M320!*

.. list-table::
   :header-rows: 0

   * - **CQB**
     
.. list-table::
   :widths: 30, 100
   :header-rows: 0
 
   * - **Indicar tipus d'agrupació**
     - **Tipus (Agrupació o agrupació partida) + porta + costat** | Aquí només s'indica el mètode d'agrupació, no cap a on s'entra.
   
       * *Agrupats porta esquerra.*
 
   * - **Indicar tipus d'entrada**
     - **Tipus d'entrada (direcció del primer gir)** | L'entrada en creu només és possible amb agrupació partida
   
       * *Porta dreta!*
       * **(Confirmació)** | Indicar que tothom està llest.
       * *4! 3! 2! 1!*
 
   * - **Llançament de granada**
     - **Ordenar tipus** | S'ha de confirmar que està llesta i indicar el llançament.
   
       * *Cegadora.*
       * *Cegadora llesta.*
       * *Espera, espera, llança!*
 
   * - **Entrant**
     - **Ordre + confirmació del primer** | Si es fa servir granada no cal aquesta seqüència, quan explota s'entra directament.
   
       * *Entreu!*
       * *Entrant!* (només el 1)

   * - **Confirmació de neteja**
     - **Ultim costat + primer costat + líder** | En el supòsit que el primer costat sigui el dret.
   
       * *Esquerra neta!*
       * *Dreta neta!*
       * *Habitació neta!*

   * - **Seqüència de recarrega**
     - **Avís + cobertura + acció + preparat**
   
       * *Recarrega!*
       * *Cobrint!*
       * *Recarregant...*
       * *Llest!*
       
Blindats
----------

.. list-table::
   :header-rows: 0

   * - **Maniobrant**
     
.. list-table::
   :widths: 30, 100
   :header-rows: 0
       
   * - **Orientar un tripulant**
     - **Tripulant + Orienta + Direcció o referència**
   
       * *Conductor orienta 3-5-0 graus.*
       * *Conductor orienta artiller.*
       * *Artiller orienta esquerra.*

   * - **Movent el vehicle**
     - **Conductor + direcció + velocitat i/o quantitat**
   
       * *Conductor avança lent.*
       * *Conductor retrocedeix 10 metres.*
 
   * - **Emmascarar només el casc**
     - **Tripulant + Casc baix + Orientació (opcional)**
   
       * *Conductor casc baix esquerra.*
 
   * - **Emmascarar tot el vehicle**
     - **Tripulant + torreta baixa**
   
       * *Conductor torreta baixa.*
 
.. list-table::
   :header-rows: 0
   
   * - **Combat**
   
.. list-table::
   :widths: 30, 100
   :header-rows: 0
 
   * - **Disparant l'arma principal**
     - **Tripulant + foc** | L'ordre la dóna el comandant sempre. L'artiller sempre ha d'avisar del foc.
   
       * *Artiller foc!*
       * *Disparant!*
 
   * - **Correcció del foc**
     - **Error vertical + horitzontal + correcció (opcional)** | S'indica primer l'error, i després si cal la correcció.
   
       * *Alt / llarg.*
       * *Curt / baix, afegeix 100.*
 
   * - **Confirmació d'impacte**
     - **Confirmació simple**
   
       * Impacte!
 
   * - **Recarregant l'arma principal**
     - **Recarrega + confirmació** | Sempre després de cada tret.
   
       * *Recarregant!*
       * *Llest!*

   * - **Ordre d'emergència per desplegar fum**
     - **Ordre per duplicat** | L'ordre la donen el conductor o l'artiller, ja que és el comandant qui ho desplega.
   
       * *FUM! FUM!*

Brevity Code
############

Paraules clau per la comunicació, valid per totes les unitats.

.. list-table::
   :widths: 30, 100
   :header-rows: 0

   * - **Actual**
     - Parla el líder de la unitat, no cap altre soldat.  
   * - **A totes les estacions**
     - Comunicar-te amb tothom.
   * - **Canvi**
     - Has acabat la teva transmissió i esperes resposta (la resposta és obligatòria ).
   * - **Fora**
     - Has acabat la comunicació i no esperes resposta. 
   * - **Rebut**
     - Comunicació compresa.
   * - **Ho faré**
     - De l'anglès Wilco «Will complay», vol dir que compliràs l'ordre.
   * - **Afirmatiu**
     - Sí
   * - **Negatiu**
     - No
   * - **Urgent**
     - El missatge té preferència sobre els altres.
   * - **Repeteix**
     - Repeteix l'última transmissió totalment o parcialment.
   * - **Correcció**
     - En un error de comunicació, després del mot es diu la informació restant correcta.
   * - **Prova de ràdio**
     - Confirmació de qualitat de les comunicacions.
   * - **Alt i clar**
     - Comunicació perfecte.
   * - **X sobre X**
     - Qualitat de ràdio, per exemple una qualitat mitja seria 3 sobre 5.
   * - **Tallo Tallo**
     - Interromps la comunicació actual i envies un missatge nou (urgent) a una altra estació.
   * - **Silenci (3 cops)**
     - Ordre a totes les estacions d'interrompre les comunicacions.
   * - **Fi de silenci**
     - Es poden reemprendre comunicacions. Indicat per la estació líder de la malla.
   * - **Contactes**
     - Visual d'objectius. Segons alineació es poden determinar com enemics, amics, civils.
