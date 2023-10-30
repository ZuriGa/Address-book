Describe: building the Address Book application with contact information and individual ID# for faster look up.

Test: It Should create a Contact function
Code: function Contact(firstName, lastName, phoneNumber);
Output: first name, last name, and phone number

Test: It should add a prototype method to call first and last name together. 
Code: Contact.prototype.fullName = function () / return this.firstName + " " + this.lastName;
Output: first and last name together

Test: It should store contact information to our address book.
Code: function AddressBook()
Output: empty string

Test: It should add new contact information to the AddressBook.
Code: AddressBook.prototype.addContact = function(contact)
Output: first and last name and phone number.

Test: It should assigned an ID to contacts once they are created.
Code: AddressBook.prototype.assignId = function() 
Output: Contact number. 1

Test: It should retrieve contact information by its Id property.
Code: AddressBook.prototype.findContact()
Output: Contact {firstName: , lastName: , phoneNumber: }

Test: It should delete a contact from our AddressBook.
Code: AddressBook.prototype.deleteContact = function(id)
Output: 