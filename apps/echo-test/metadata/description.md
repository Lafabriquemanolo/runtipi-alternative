Echo Test
À quoi sert cette application ?
Echo Test est une application de diagnostic minimaliste. Son unique but est de vérifier que votre App Store personnel est correctement lu et interprété par votre instance RunTipi.

Elle ne fait rien de complexe : elle lance simplement un micro-serveur qui "répond" un message de succès.

Comment interpréter le résultat ?
Si vous voyez cette application "Echo Test" dans votre App Store : Félicitations ! Cela signifie que la connexion entre votre RunTipi et votre dépôt GitHub fonctionne parfaitement. Si une autre application plus complexe (comme Framadate) n'apparaît pas, le problème vient spécifiquement de la configuration de cette autre application.

Si même cette application n'apparaît pas : Cela confirme qu'il y a un problème de communication entre votre serveur et GitHub. La cause la plus probable est un pare-feu (firewall) qui bloque la connexion, comme nous l'avons évoqué.
