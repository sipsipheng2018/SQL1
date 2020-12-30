# SQL1
Exercise SQL :

Q Select all records from the Customers where the PostalCode column is NOT empty.
A WHERE PostalCode is null

Q Select all records where the value of the City column contains the letter "a".
A WHERE City LIKE '%a%'

Q Select all records where the value of the City column starts with letter "a" and ends with the letter "b".
A like 'a%b'

Q Select all records where the value of the City column does NOT start with the letter "a".
A where city not like 'a%'

Q Select all records where the second letter of the City is an "a".
A WHERE City LIKE '?a%'

Q Select all records where the first letter of the City is an "a" or a "c" or an "s".
A WHERE City LIKE '[acs]%'

Q Select all records where the first letter of the City starts with anything from an "a" to an "f".
A WHERE City LIKE '[a-f]%'

Q Select all records where the first letter of the City is NOT an "a" or a "c" or an "f".
A WHERE City LIKE '[^acf]%'

Q Use the IN operator to select all the records where Country is either "Norway" or "France".
A where Country  in ('Norway', 'France');

Q Use the IN operator to select all the records where Country is NOT "Norway" and NOT "France".
A where Country not in not ('Norway', 'France');

Q Use the BETWEEN operator to select all the records where the value of the Price column is between 10 and 20.
AProducts WHERE Price between 10 and 20

Q Use the BETWEEN operator to select all the records where the value of the Price column is NOT between 10 and 20.
A WHERE Price not between 10 and 20

Q Use the BETWEEN operator to select all the records where the value of the ProductName column is alphabetically between 'Geitost' and 'Pavlova'.
A  WHERE ProductName BETWEEN 'Geitost' and 'Pavlova'
