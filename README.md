# epicode-esercizio5

Usa il file allegato come punto di partenza.

NON aggiungere nessuna classe o id agli elementi HTML!

Usa classi già esistenti, o scrivi selettori e pseudo classi per selezionare gli elementi HTML necessari.

Il punto di partenza dovrebbe apparire così:

Es. 1) Muovi i riquadri verso sinistra orizzontalmente, applicando la proprietà css display:inline-block. Dovresti ottenere il seguente risultato:

Es. 2) Scrivi UN selettore CSS per cambiare il bordo dei riquadri la cui positione è pari.
( :nth-child() ). Dovresti ottenere il seguente risultato:

Es. 3) Scrivi UN selettore CSS per colorare di verde il colore delle lettere B e D nei riquadri di posizione dispari. ( :nth-child() ). Dovresti ottenere il seguente risultato:

Es. 4) Scrivi UN selettore CSS per colorare di blu l’ultima lettera (D) del secondo riquadro ( :last-of-type ). Dovresti ottenere il seguente risultato:

Es. 5) Scrivi UN selettore CSS per colorare di giallo tutte le lettere eccetto l’ultima (D) del sesto riquadro. ( :not( :last-of-type) ). Dovresti ottenere il seguente risultato:

Gli esercizi seguenti richiederanno il posizionamento CSS degli elementi!
position:relative ← genitore (div);
position:absolute ← figlio (span)

Es. 6) Scrivi un selettore CSS per cambiare la posizione della lettera A in tutti i riquadri. Dovresti ottenere il seguente risultato:

Es. 7) Scrivi un selettore CSS per cambiare la posizione della lettera B in tutti i riquadri. Dovresti ottenere il seguente risultato:

Es. 8) Scrivi un selettore CSS per cambiare la posizione della lettera D nell’ultimo riquadro. Dovresti ottenere il seguente risultato:

Es. 9) Scrivi un selettore CSS per cambiare la posizione della lettera D nel primo riquadro. Dovresti ottenere il seguente risultato:

Es. 10) Rimuovi gli spazi bianchi tra i riquadri. (sono il risultato di default di position:inline-block)

Il trucco è applicare
.container {
font-size:0;
}

che fornirà il seguente risultato:

Ma dove sono sparite tutte le lettere?? Purtroppo è normale siano scomparse, visto che abbiamo impostato la dimensione del font all’interno di .container a 0.

Come si risolve?

Applicando font-size al div dentro .container, tutti gli span al suo interno erediteranno la font-size del div e non più dal .container:

.container div {
font-size:1rem;
}

//esercizio 2//
Il tuo compito e creare una scacchiera.

IMPORTANTE! Completa prima gli esercizi, seguendo le indicazioni una per una, e poi prova a completare anche questo progetto.

Indicazioni:
Quando il puntatore scorre sopra una qualsiasi cella, il colore della cella dovrebbe diventare rosso.
La scacchiera deve essere posizionata al centro della pagina.

