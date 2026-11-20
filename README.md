# Il Secret Santa di Casa Navarra

Il Babbo Natale segreto senza app: chi organizza scrive i nomi e preme Sorteggia, poi manda a ognuno il suo link su WhatsApp. Chi lo riceve apre la busta e scopre a chi fa il regalo.

Tutto sta in un solo file, `index.html`. Non c'è un server e non serve un account: i nomi viaggiano solo dentro i link (dopo il `#`, che il browser non manda a nessun server).

## Come pubblicarlo

Serve un indirizzo `https://` pubblico, così i link funzionano sul telefono di tutti.

**Netlify Drop (il più semplice)**
1. Apri https://app.netlify.com/drop
2. Trascina dentro la cartella `SecretSantaCasaNavarra`.
3. Netlify ti dà un indirizzo tipo `https://nome-a-caso.netlify.app`: quello è il sito.

**GitHub Pages**
1. Crea un repository e caricaci `index.html`.
2. Settings, Pages, scegli il ramo principale e la cartella `/ (root)`.
3. Dopo un minuto il sito è su `https://<utente>.github.io/<repository>/`.

## Da sapere

- I link sono offuscati, non cifrati: chi conosce il codice può decodificarli. L'app però non mostra mai chi ha pescato chi.
- Se rifai il sorteggio, i link vecchi restano validi ma non corrispondono più: rimandali tutti.
- I caratteri (Alegreya e Parisienne) arrivano da Google Fonts; senza rete si usano Palatino/Georgia e un corsivo di sistema.
