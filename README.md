# .github
Regole e template globali

## Esecuzione della pagina di associazione conti

1. Assicurati di avere clonato questo repository in locale.
2. Apri una shell nella cartella `.github` del progetto.
3. Avvia un piccolo server web statico, ad esempio con Python:
   ```bash
   python3 -m http.server 8000
   ```
4. Nel browser visita [http://localhost:8000/account-association.html](http://localhost:8000/account-association.html).
5. Carica i due file CSV o XLSX richiesti direttamente dall'interfaccia e verifica il risultato mostrato.

> In alternativa puoi aprire direttamente il file `account-association.html` nel browser facendo doppio clic, ma l'utilizzo di un server statico evita limitazioni di sicurezza su alcuni browser.
