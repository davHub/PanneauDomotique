Le panneau gère les réception de messages de la forme suivante :
  
  // Faire transiter un message
  1) SCROLL:T:V:YY:Mon message à afficher     
        -> T : taille (1,2 ou 4 octets) 
        -> V : vitesse (Vmax=0 - Vmin=9 )
        -> YY : Position horizontal de du message
        
  // Réaliser une action prédéfinie
  2) ACTION:Nom de l'action
  
  // Ecrire quelquechose de taille 1 octet quelquepart
  3) PHRASE:XX:YY:Ma message 
        -> XX : Coordonnées horizontales
        -> YY : Coordonnées horizontales
