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

# How will blockchain benefit my application?

_Blockchain, at its core, is a technology that innovates on how we transfer value._ So, if your application exchanges value in some way, blockchain may be a candidate technology to bring your application to the next level. 

But before jumping in, it is important to understand specifically how it might benefit your application so that you can design a system that targets those benefits and doesn’t add unnecessary complexity to other parts of your application. This usually maps to thinking about which components to put “on-chain” versus “off-chain”.

Below are some of the characteristics of blockchains that make them attractive technologies for value-based applications. 


<center>
![Blockchain properties](../../imgs/blockchain-properties.png)
</center>

Not all of these may be important to your application or some may be more important than others, so a good first question to ask is: 

> “Which of these characteristics is an important property for my use case?” 

If you choose at least one, then ask:
 
> “Is that property lacking or insufficient in my current application design?” 

If the answer to the second question is “yes” to any or all of the properties you chose, then you’re in the right place.

For example, sending a payment across borders through a bank often takes days and is expensive since there are many intermediaries who are involved to ensure that the value is transferred securely. High **costs** and overall poor **efficiency** are the characteristics that stand out in this scenario and that blockchain could improve. That’s not to say that the other characteristics aren’t important. For example, we don’t want lower costs at the expense of security, but if security mattered alone we might say that the current process is good enough (assuming you trust the bank who is making the transfer). In this scenario, blockchain improves deficiencies in the system without making a tradeoff elsewhere.

# Alice and Bob's auction

Meet Alice and Bob. Alice is a talented artist, looking to grow her fanbase and her value as an artist. Bob is a developer and Alice’s good friend. He wants to help her out. 

<center>
![Meet Alice and Bob](../../imgs/basics-alicebob-1.png){: width='500px' }
</center>

Alice usually sells her artwork through personal connections and sometimes by advertising on social media. One of her digital art pieces sells for $100, on average, using her current sale techniques. She thinks she could make a lot more if she were able to scale and reach a wider audience. Alice considers the important properties for her use case:

1. **Efficiency** - Alice spends lots of time trying to find a buyer and ultimately doesn’t reach a wide enough audience.
2. **Trust/Transparency** - Alice wants to reach a wider audience, but she is still building her reputation and needs a way for both herself and potential buyers to know that they aren’t getting scammed.
3. **Cost** - The best option for scaling now is to use an e-commerce site, but she knows she’ll have to give up a good chunk of what she makes on fees (minimum 5% and up to 15-20%). 

We named 4 properties of blockchain that could help Alice and her use case. Alice and Bob brainstorm together considering Alice’s main goals and the properties she wants to optimize for. They come up with the following idea:

They plan to tokenize Alice’s artwork as an NFT on the blockchain. This gives them an entry point into the blockchain ecosystem and the ability to program what they want to do next. Then, they will build an auction dApp on the blockchain that will allow Alice to sell her artwork for a price set by the market. The auction will be programmed on the blockchain for everyone to see and independently verify. Alice can guarantee to her buyers that they will not be scammed and vice versa without needing to be personally acquainted (trust/transparency). Since they are removing the need for a third-party to guarantee trade, they can substantially cut down fees and Alice can make more money (low cost). Alice can focus on advertising her work to as broad of an audience as she wants through her social media accounts or elsewhere without needing to meet individually and build trust with potential buyers (efficiency).

Now that we know the basics of blockchain. Let’s learn more about the Algorand blockchain.

