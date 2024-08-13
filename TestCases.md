1. Login with correct credentials

Description
Check if the login works when user enters the correct credentials.



Steps to reproduce:


1.Open your browser


2.Search for eMag.ro


3.Add correct user/pass


4.Click "Login" button


Expected Results:

User should be able to login and will be redirected to his profile page.



Test data:

Username: andrei@mail.ro

Password: 12345

Pre-conditions 

User should have a valid account

--------------------------------------------------------------------------

2. Login with wrong credentials

Description
Check if the login works when user enters the wrong credentials.



Steps to reproduce

1.Open your browser

2.Search for eMag.ro

3.Add the wrong user/password

4.Click "Login" buton



Expected results:

User should not be to login and to receive the message "Invalid Email".



Test data:

User: aaaa@

Pass: 123s

--------------------------------------------------------------------------------

3. Login with no credentials

Description
Check if the login works when user enters no credentials.



Steps to reproduce

1.Open your browser

2.Search for eMag.ro

3.Left the username and passwor field blank

4.Click "Login" buton



Expected results:

User should not be to login and to receive the message "Mandatory Field".


4. A search must bring a list with your searched results

Description
If you search for an item it should rezult the item that you searched for.



Steps to reproduce:

1.Open your browser

2.Search for eMag.ro

3.Click on Login buton

4.Fill field with username and password

5.Log in into your account

6.Check for the searchbar

7.Search for the item you want



Expected results:

The result of the search should be a list with similar products



Test data :

Username: andrei@mail.ro

Password: 12345

cafea


5. Autocomplete of a searched input -after 3 characters

Description
A search can autocomplete if you enter only some words and not the full word.



Steps to reproduce:

1.Open your browser

2.Search for eMag.ro

3.Click on the Login buton

4.Enter your username and password

5.Click on Login buton

6.Check for the searchbar

7.Enter the first 3 letters of the name of the item


Expected results:

The item name should be autocompleted



Test data :

Username: andrei@mail.ro

Password: 12345

caf


6. A search with random characters cannot give errors

Description
If you search for an item and you enter random characters it should not give you errors.



Steps to reproduce:

1.Open your browser

2.Search for eMag.ro

3.Click on the Login buton

4.Enter your username and password

5.Click on the Login buton

6.Check for the searchbar

7.Enter some random characters



Expected results:

The result of the search should be some random items



Test data :

Username: radu@mail.ro

Password: 12345

xyzzzaass
