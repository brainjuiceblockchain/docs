title: ¿Qué es blockchain? 

<center>
![Blockchain versus traditional database](../../imgs/basics-blockchain-vs-traditional.png){: style="width:500px" align=center }
</center>

Blockchain es un libro mayor público (o archivo) de transaciones de datos, distribuido entre un red de ordenadores (“nodos”). Todos estos nodos trabajan juntos, utilizando el mismo conjunto de software y reglas para verificar transacciones a añadir en el libro mayor cerrado. 

<center>
![Woman bids on blockchain](../../imgs/basics-woman-bid-blockchain.png){: style="width:500px" align=center }
<figcaption style="font-size:12px">Una mujer puja por un casa utilizando un software construido sobre un blockchain descentralizado.</figcaption>
</center>

Compara esto a un tradicional libro mayor de transacción de datos que puede estar en una sola base de datos configurado en unos pocos ordenadores donde sólo unas personas tienen acceso.

<center>
![Woman bids in traditional world](../../imgs/basics-woman-bid-traditional.png){: width='500px' }
<figcaption style="font-size:12px">Una mujer puja por una casa usando una agencia privado.</figcaption>
</center>

El “bloque”, parte de “Blockchain”, hace referencia a un conjunto de transacciones propuesto y validado por otros nodos y añadido finalmente al libro mayor.
La parte “cadena”, hace referencia al hecho de que cada bloque de la transacción contenga prueba de manipulaciones (Hash criptográfico) de lo que se haya modificado en el anterior bloque. Este patrón, de capturar los bloques de datos anteriores en el bloque actual, se hace desde el inicio del comienzo de la red (bloque origen) creando un verificable público y un registro seguro de todas las transacciones existentes. 

<center>
![Blockchain diagram](../../imgs/blockchain-diagram.png){: width='500px' }
</center>

En otras palabras, si se intenta modificar un solo registro en cualquier parte  de la historia de un blockchain, la modificación será detectado y rechazado por los nodos de la red. 

<center>
![Man attempts to change blockchain record, unsuccessfully](../../imgs/basics-immutable.png){: width='500px' }
<figcaption style="font-size:12px">Un usuario malicioso intenta cambiar un registro pasado de blockchain fracasadamente.</figcaption>
</center>

Compara esto con un libro mayor tradicional donde un cambio en la base de datos es confiado a un grupo limite que pueden ser fácilmente manipulado  a través de intentos maliciosos o simplemente por error. 

<center>
![Traditional bid error](../../imgs/basics-traditional-error.png){: width='500px' }
<figcaption style="font-size:12px">Ejemplo de cómo un sistema centralizado puede accidentalmente descalificar la participación de usuario.</figcaption>
</center>



Pero, ¿ cómo se puede añadir bloques a la cadena en primer lugar? Cada nodo ejecuta un software que les instruye de cómo verificar las transacciones y de añadir nuevos bloques a la cadena. Estas instrucciones se llaman en conjunto "Consensus protocol". La naturaleza de estas instrucciones son una de los principales factores característico de los diferentes blockchain.

# Cómo puede una applicación beneficiarse de Blockchain?
