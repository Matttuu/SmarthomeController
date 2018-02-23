#Smarthome Controller
___

**Kunde:** Daniel Lyck

Kunden ønsker at lave sit hjem om til et smarthome, han ønsker følgende features:

    * Tænd og slukke fjernsyn ved at råbe "fisse".
    * Skrue varmen helt op for varmen, når kunden siger "Der er sku da ved at være lidt varmt herinde"
    * El-kedel tænder når kunde siger "Yum-yum"
    * Når der ligger mere end én i den, så skal den åbne kondom skuffen.
    * Telefon skal åbne justeat browser når kunden siger "Cremefraiche"
    
Kunden ønsker at modernisere sit hjem ved hjælp af enheder som tager imod stemmekommandoer samt måle enhed.
For eksempel så skal måle enheden måle vægten i sengen, og åbne kondom skuffen når vægten har oversteget en angivet 
grænse. 

### Design your classes

En klasse som indeholder en stemmeaktiverings metode som går igen i flere cases

El-kedel class, varme class, telefon class som alle nedarves fra stemmeaktiveringsmetoden, da samme funktion går igen.

En måle klasse, som måler vægt

En skuffe klasse som nedarves fra måle klasse.



