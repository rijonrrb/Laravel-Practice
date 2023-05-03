## Customized Authentication System using Laravel

__𝙊𝙫𝙚𝙧𝙫𝙞𝙚𝙬:__ The purpose of this project is to develop a customized authentication system that provides a secure and user-friendly way for users to log in and register for a web application. The system will include features such as email verification, password reset, remember me, login with Google, and more.
- - - - -
## Features

- `Login page` The login page will include a form that allows the user to enter their email and password. The system will also include a "remember me" feature that allows the user to stay logged in for a specified period of time.
- `Registration page` The registration page will include a form that allows the user to enter their name, email, password, and other relevant details. The system will include validation for the registration form fields and will only allow registration with a verified email address.
- `Email verification` The system will integrate with an SMTP service to send an OTP using email after registration to verify the user's email address. The OTP submission page will allow the user to resend the OTP after 60 seconds. After successful OTP submission, the user will be redirected to the welcome page/home page.
- `Login with Google` The system will provide the option for the user to log in using their Google account.
- `Password reset` The system will include a "forgot password" feature that redirects the user to a new tab to verify their email address. If the email address is valid, the system will send a mail with a reset password link where the user can change their password.
- `Validation` The system will include validation for the registration form fields and reset password form fields to ensure the data entered by the user is valid and secure.
- `Logout` The home page/welcome page will include a logout button that allows the user to log out of the system.
- `Middleware` Middleware services will be used to verify that the user of the application is authenticated and to restrict access to certain pages.
- - - - -
## Demo




https://user-images.githubusercontent.com/109922200/235931063-5ba5a93f-2a13-45d3-8bf4-abb56ec03aa3.mp4




- - - - -
## Technology

- `Backend` Laravel PHP framework
- `Frontend` Livewire for real-time frontend development, HTML, CSS, Bootstrap, and JavaScript for the user interface
- `Database` MySQL for data storage

- - - - -
## Conclusion

This customized authentication system will provide a secure and user-friendly way for users to log in and register for a web application. The integration of email verification, password reset, and other features will enhance the security and usability of the system. The use of Laravel, HTML, CSS, Bootstrap, and JavaScript will ensure a high-performance system that is easily scalable and maintainable.

---
## Usage

This is not a package - it's a full Laravel project that you should use as a starter boilerplate, and then add your own custom functionality.

- Clone the repository with `git clone`
- Copy `.env.example` file to `.env` and edit database credentials there
- Run `composer install`
- Run `php artisan keygenerate`
- Run `php artisan migrate`
- Run `php artisan serve`
