# human-code

## Traccia

//Fatti mandare dalla mamma a prendere il latte

Fare la spesa seguendo una lista:
Nel frigo si inizia a sentire l’eco, perciò è ora di fare rifornimenti!
Visto che dimentico sempre qualcosa, decido di appuntarmi tutto ciò che manca in una lista, così una volta al supermercato, girando tra gli scaffali, posso verificare di aver preso tutto e Ricky non rimane senza crocchette come l’ultima volta, povero! Devo ricordarmi di usare il coupon che scade a fine mese, per il resto dovrebbero bastarmi i contanti che ho in portafogli, sempre se non mi faccio prendere la mano con gli snack extra!

### Steps

// Ho fame

Apro il frigo:

    ? SE il frigo è pieno
        - Prendo qualcosa e mangio
    : ALTRIMENTI
        - Decido di andare a fare la spesa

Chiudo il frigo.

// Preparazione lista:

Prendo carta e penna

Decido cosa mi serve:

[crocchette per il cane, pane, latte, uova, caffè, birra]

Per ciascun item controllo la quantità:

        ? SE la quantità è sufficiente
            Continuo a controllare
        : ALTRIMENTI
            Inserisco l'item nella lista

Lascio carta e penna.

// Prima di uscire:

Controllo di avere il coupon:

        ? SE ho il coupon
            Va bene così
        : ALTRIMENTI
            Lo prendo

Controllo di avere le chiavi di casa:

        ? SE ho le chiavi di casa
            Va bene così
        : ALTRIMENTI
            Le prendo

Prendo il portafoglio:

        ? SE contanti maggiori o uguali a 50€
            Esco a fare la spesa
        : ALTRIMENTI
            Decido di passare al bancomat prima di andare al supermercato

// Arrivo al supermercato

Controllo tra le corsie i prodotti sugli scaffali:

        :FINCHE' non depenno tutti i prodotti

            ? SE trovo il prodotto che mi serve
                Lo prendo e lo depenno
            : ALTRIMENTI
                Vado avanti


Dopo aver preso i prodotti della lista, mi dirigo alla cassa:

            ? SE c'è una cassa libera
                La scelgo
            : ALTRIMENTI
                Scelgo quella con meno fila

Al momento del pagamento
                
            ? SE il totale meno il coupon è inferiore a 50 €
                Compro uno snack
            : ALTRIMENTI
                Pago e vado via