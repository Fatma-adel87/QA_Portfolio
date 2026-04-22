“}
# Login Test Cases - SauceDemo

## TC01 - Valid Login

Steps:
1. Open the website
2. Enter valid username (standard_user)
3. Enter valid password (secret_sauce)
4. Click on Login button

Expected Result:
User should be redirected to the products page

---

## TC02 - Invalid Password

Steps:
1. Enter valid username
2. Enter invalid password
3. Click Login

Expected Result:
Error message should be displayed saying "Username and password do not match"

---

## TC03 - Empty Fields

Steps:
1. Leave username empty
2. Leave password empty
3. Click Login

Expected Result:
Validation message should appe
