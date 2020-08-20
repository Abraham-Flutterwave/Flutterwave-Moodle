<p align="center">
    <img title="Flutterwave" height="200" src="https://flutterwave.com/images/logo-colored.svg" width="50%"/>
</p>

# Flutterwave Moodle Plugin

Enrolment in Moodle using Flutterwave payment gateway for paid courses.

This plugin helps admins and tutors use Flutterwave as the payment gateway to collect payment and enrol students for their paid courses. This plugin can be used for both development and production.

## Getting Started
These instructions will get you a copy of the plugin up and running on your local machine for development and production purposes.

### Prerequisites
What things you need to install the software and how to install them.

1. Moodle installation and setup
2. Administrator account setup

### Installing

1. Log in to your moodle site as an administrator.

2. Upload the zip package from Site Administration -> Plugins -> Install Plugins. Choose Plugin type 'Enrolment method (enrol)'. Upload the ZIP package, check the acknowledgement and install.

3. Go to Enrolments -> Manage enrol plugins -> Enable 'Flutterwave' from list by clicking on the eye symbol. You can also alter the plugin's base setting from the list.

4. Click 'Settings' which will lead to the settings page of the plugin.

5. Provide merchant credentials for Flutterwave. You will get all the information from your merchant account. Now select the checkboxes as per requirement. Please ensure to ensure to enter appropiate credentials given the mode (test or live).

6. Select any course from course listing page.

7. Go to Course Administration -> Users -> Enrolment Methods -> Add method 'Flutterwave' from the dropdown. Set 'Custom instance name', 'Enrol cost' etc and add the method.

This completes all the steps for the administrator's end. Now registered users can login to the Moodle site and view the course after a successful payment.

## Built Using 
- [PHP](https://www.php.net/)
- [Flutterwave Inline](https://developer.flutterwave.com/docs/flutterwave-inline)

## Contributors
Here you can browse the source, look at open issues and keep track of development.
