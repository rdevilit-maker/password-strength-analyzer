void main(): The entry point of any Dart program.
print('Enter a password:'): Prompts the user to enter a password.
final password = stdin.readLineSync()!: Reads the password input from the user. The exclamation mark (!) is a null check operator, ensuring that the value read is not null.
final strength = getPasswordStrength(password): Calls the function getPasswordStrength with the entered password.
print('Password strength: $strength'): Displays the evaluated strength of the password.
