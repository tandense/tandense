<form action="https://mapaycard.com/epay/" method="POST">
  <input type="hidden" name="c" value="MTEwMjM0MDk">
  <input type="hidden" name="paycard-amount" value="10000"> <!-- Changez au montant de votre produit -->
  <input type="hidden" name="paycard-description" value="Vente de produit"> <!-- Changez à la description de la vente ( pas obligatoire ) -->

  <!-- Inclure le callback URL où redigirer automatiquement après le paiement -->
  
  <!-- Un appel POST sera fait au callback URL avec toutes les données -->
  <!-- <input type="hidden" name="paycard-callback-url" value="https://www.tandense.com/checkout_ID_transaction_thanking"> -->

  <!-- Faire la redirection en GET au lieu de POST -->
  <!-- NB: Cette méthode est moins sécurisée que le POST. -->
  <!-- <input type="hidden" name="paycard-redirect-with-get" value="on"> -->
  
  <!-- Desactivez l'auto redirection en changeant la valeur de paycard-auto-redirect -->
  <!-- <input type="hidden" name="paycard-auto-redirect" value="off"> -->

  <!-- Inclure les données que vous aimerez recevoir au callback -->
  <!-- ex : <input type="hidden" name="order_id" value="abc001"> -->
  
  <input type="image" src="https://mapaycard.com/static/images/paywithpaycard-cc.png" border="0" alt="Payez avec PayCard"></input>
</form>
