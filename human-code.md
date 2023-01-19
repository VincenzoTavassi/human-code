## HUMAN CODE

Scegliere cosa guardare su Netflix
Che barba, che noia, che noia, che barba!
Perché ci si mette sempre un’ora a scegliere cosa guardare la sera? Certo è difficile mettere d’accordo i gusti di tutti, poi dipende anche in base al tempo (o al sonno) che abbiamo. Delle volte si pensa di vedere quel bel film che ci hanno consigliato, mentre altre volte si viene risucchiati da quella serie tv che ci tiene incollati allo schermo. Che senso di vuoto quando poi finisce! 


## SCEGLIERE COSA GUARDARE SU NETFLIX

##### FILM PIU' VOTATO TRA 5 PERSONE

- APRI Lista_Film_Consigliati
- SFOGLIA Lista_Film_Consigliati
- RACCOGLI Votazioni(Film)
**FINCHE'** Film < 3 voti VAI AL PROSSIMO
DEFINISCI Lista_Film_Consigliati(*Film_Piu_Votato*)


### GUARDA NETFLIX

- Prendere il telecomando
- Accendere la TV 
- Visualizzare l'elenco di APP
    - **SE** l'app *Netflix* non è presente
    SCARICA *Netflix*
- ACCEDI a *Netflix*

- **SE** il *mio_tempo* > 1.5h **E** *sonno* non è vero
 APRI *Lista_Film_Consigliati*
 RIPRODUCI *Film_Consigliati(Film_Piu_Votato)*
 **ALTRIMENTI** Apri lista serie TV **O** documentari
   - **SE** è presente un *Documentario_Interessante*
    RIPRODUCI *Documentario_Interessante* 
    **ALTRIMENTI**
    - **SE** è presente una *Serie_NonTerminata*
RIPRODUCI *Serie_NonTerminata*
**ALTRIMENTI**
RIPRODUCI *Serie_Nuova*

- **FINCHE'** mio_tempo NON E' = 0 **E** *sonno* NON è vero
continua RIPRODUCI
- Prendi il telecomando
- Spegni TV
- Vai a dormire



 
