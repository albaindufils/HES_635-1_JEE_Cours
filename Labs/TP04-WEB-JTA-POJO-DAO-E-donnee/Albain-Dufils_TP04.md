# TP04: Transactions at the service layer
## Questions
- The service layer, and in particular the method transfer of the class Bank
- The method saveOrUpdate2 of the class AccountDAO
- The class ch.hevs.dao.util.ConnexionManager

## Response
This saveOrUpdate2 throw an exception to proof that the transaction is necessary in case the transfer has a problem. 
We case see that no transaction has been done du to the "non-commit" in by the transaction. 
We can use this to validate a money transfer and to control that the data are right.
The connexionManager is a Singleton. We want only one instance of the DB connexion.
