# Byu Status Alerts Templates

Questa cartella contiene i template JSON per il sistema "Interfonico" di Byu.

## Come attivare un alert
Per attivare un alert, copia il contenuto del file `status.json` della cartella desiderata e incollalo nel file `status.json` alla radice (root) del repository.

### Cartelle disponibili:
- `maintenance/`: Alert per manutenzione programmata (Arancione).
- `update/`: Alert per nuova versione disponibile (Viola).
- `critical/`: Alert per errori critici o blocchi WAF (Rosso).
- `news/`: Alert per novità generiche o consigli (Viola).

**Nota:** Ricordati di cambiare l' `id` nel file alla radice se vuoi che l'alert riappaia agli utenti che lo avevano precedentemente chiuso.
