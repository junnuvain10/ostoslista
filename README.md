Yksinkertainen Ostoslista Web App, joka on toteutettu lähinnä puhelimella käytettäväksi omaan käyttöön.

## Käyttöohjeet

### Vaatimukset

- Node.js ja npm asennettuna

### Paikallisesti ajaminen

1. **Kloonaa tai lataa projekti**

   ```
   git clone https://github.com/junnuvain10/ostoslista.git
   cd ostoslista
   ```

2. **Asenna riippuvuudet**

   ```
   npm install
   ```

3. **Käynnistä kehityspalvelin**

   ```
   npm run dev
   ```

   Sovellus on nyt saatavilla osoitteessa `http://localhost:3000/`

4. **Tuotantoversion rakentaminen**

   ```
   npm run build
   ```

   Rakentaminen luo `dist` kansion, joka voidaan julkaista.

5. **Esikatselu tuotantoversio**
   ```
   npm run preview
   ```
