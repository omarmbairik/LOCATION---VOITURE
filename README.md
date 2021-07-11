# LOCATION---VOITURE
LOCATION DE VOITURE : est une application desktop qui faciliter la gestion de location des voiture pour l’administrateur et sauvegarder les donnée important.
Code: C# , Ado.net , SQL Server , CrystalRepport



---------------------------------------------- Guide d'utilisateur ----------------------------------------------


1 - : Les accompagnements doivent être installés (All the Way to the Sun.otf,CRforVS13SP30_0-10010309.EXE)

2 - : Ajouter la Base de donnee (Location de voitures2.sql)

3 - : Modifier la Chaine de Connexion sur la class "AdoNet.cs" -- public static SqlConnection con = new SqlConnection("Votre cnx)
      + sur les rapport (Contrat.rpt,Facture.rpt,Recu.rpt)

4 - : Modifier mail d'application pour envoyeé les informations du compte oubliées 
	-- MailMessage msg = new MailMessage("votre mail d'application"....)
	--  NetworkCredential cre = new NetworkCredential("votre mail d'application", "mot de passe d'e-mail");

