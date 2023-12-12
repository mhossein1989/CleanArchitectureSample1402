# My Code Sample 

I Have Done a  CRUD application with ASP NET that implements the below model:

Customer {
	Firstname
	Lastname
	DateOfBirth
	PhoneNumber
	Email
	BankAccountNumber
}

## Practices and patterns (Must):

- [TDD]
- [DDD]
- [BDD]
- [Clean architecture]
- [CQRS]

### Validations

- During Create; validated the phone number to be a valid *mobile* number only (using [Google LibPhoneNumber]

- A Valid email and a valid bank account number Is checked before submitting the form.

- Customers Is unique in database: By Firstname, Lastname and DateOfBirth.

- Email Is unique in the database.

- Stored the phone number in a database with minimized space storage

