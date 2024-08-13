# eMag Login and Search Functionality Test Cases

## 1. Login with Correct Credentials

**Description**: Check if the login works when the user enters the correct credentials.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Add correct user/pass.
4. Click "Login" button.

**Expected Results**: User should be able to login and will be redirected to his profile page.

**Test Data**:
- Username: andrei@mail.ro
- Password: 12345

**Pre-conditions**: User should have a valid account.

---

## 2. Login with Wrong Credentials

**Description**: Check if the login works when the user enters the wrong credentials.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Add the wrong user/password.
4. Click "Login" button.

**Expected Results**: User should not be able to login and to receive the message "Invalid Email".

**Test Data**:
- User: aaaa@
- Pass: 123s

---

## 3. Login with No Credentials

**Description**: Check if the login works when the user enters no credentials.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Leave the username and password field blank.
4. Click "Login" button.

**Expected Results**: User should not be able to login and to receive the message "Mandatory Field".

---

## 4. Search Functionality

**Description**: If you search for an item, it should result in the item that you searched for.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Click on Login button.
4. Fill field with username and password.
5. Log in into your account.
6. Check for the search bar.
7. Search for the item you want.

**Expected Results**: The result of the search should be a list with similar products.

**Test Data**:
- Username: andrei@mail.ro
- Password: 12345
- Search Query: cafea

---

## 5. Autocomplete of a Searched Input - After 3 Characters

**Description**: A search can autocomplete if you enter only some words and not the full word.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Click on the Login button.
4. Enter your username and password.
5. Click on Login button.
6. Check for the search bar.
7. Enter the first 3 letters of the name of the item.

**Expected Results**: The item name should be autocompleted.

**Test Data**:
- Username: andrei@mail.ro
- Password: 12345
- Partial Search: caf

---

## 6. Search with Random Characters Cannot Give Errors

**Description**: If you search for an item and you enter random characters, it should not give you errors.

**Steps to Reproduce**:
1. Open your browser.
2. Search for eMag.ro.
3. Click on the Login button.
4. Enter your username and password.
5. Click on the Login button.
6. Check for the search bar.
7. Enter some random characters.

**Expected Results**: The result of the search should be some random items.

**Test Data**:
- Username: radu@mail.ro
- Password: 12345
- Random Characters: xyzzzaass
