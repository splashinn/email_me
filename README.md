# Email Me!

Email Me! is a simple Rails application demoing the use of Action Mailer.

## What does it do?
It sends an email welcoming the user to the site upon account creation.

### Instructions for use:
- Fork and Clone this repository to your local machine.
- `cd` to the directory and run `bundle install` to install dependencies.
- Run `rake db:create db:migrate` to create/migrate database (which is PG by default)
- You will need to edit `app/mailers/application_mailer.rb` and replace the default from with the email you want to use to send from
- You will also need to edit `config/environments/development.rb`, replacing `your-email@example.com`, `<username>` and `<password>` with the email and password you are using to send from. (Make sure you do not commit these! Encrypting the password is outside the scope of this demo.)
-
