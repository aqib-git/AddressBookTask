# AddressBookTask

Please read through the details of this task below, let me know if you have any questions.

You have to create an AddressBook Web Application. It should have the following features.

Features:

1. As a user, I should be to register & sign-in. (No need to develop your own because Laravel already has this builtin feature.)
2. As a user, I should create/update/delete and see a list of contacts.
3. Create & Update Forms should have validation.
4. As a user, I should be able to search for contacts.

Pages:

1. List of contacts page where the user can see a list of contacts. At the top of the list, there should be the Add Contact button. List page route will be `/contacts` (GET)
2. Create Contact page. Its route will be `/contacts/create` (POST)
3. Update the contacts page. Its route will be `/contacts/{id}` (PUT)
4. Search the contacts e.g `/contacts?q=Aqib` (GET)


Database:

Make sure you are using Laravel Migrations.

It should have only two tables `users` & `contacts` table. Every user can have its own set of contacts in the contacts table.

`contacts` table columns are first_name, last_name, email, phone, bio & user_id (Foreign  key to users table)

I don't care about how UI looks, so don't spend much time on that. I just want to see your logic.

Required Frameworks:

Laravel Framework.
