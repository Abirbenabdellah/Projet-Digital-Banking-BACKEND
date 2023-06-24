<h2>Partie Backend</h2>
<h3>-Architecture Backend de l'application</h3>
<li>Couche DAO : Contient les interfaces JPA Repository basées sur Spring Data</li>
<img src="images/i1.png">
<li>Entités JPA: Customer, BankAccount, Saving Account, CurrentAccount, AccountOperation </li>
<img src="images/i2.png">
<li>DTOS </li>
<img src="images/i3.png">
<li>Couche service</li>
<img src="images/i4.png">
<li>RestController</li>
<img src="images/i5.png">
<li>Les exceptions : BalanceNotException, BankAccountNotFoundException, CustomerNotFoundException</li>
<img src="images/i6.png">
<h3>-Couche service, web</h3>
<h4>BankAccountService & BankAccountServiceImpl</h4>
<img src="images/i7.png">
<img src="images/i9.png">    <img src="images/i10.png">
<h4>Couche web</h4>
<li>CustomerRestController</li>
<img src="images/i11.png">
<li>BankAccountRestApi</li>
<img src="images/i12.png">
<h4>Test de la couche web (Swagger UI)</h4>
<img src="images/i13.png">
<li>Ajouter un client</li>
<img src="images/i16.png">
<li>La liste des clients</li>
<img src="images/i14.png">
<li>Rechercher un client par son Id</li>
<img src="images/i15.png">
<li>La listes des comptes</li>
<img src="images/i17.png">
<li>La listes des operations d'un compte</li>
<img src="images/i19.png">
