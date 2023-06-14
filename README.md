# Moodle Plugin: Hide Correctly Answered Questions

## Description
This Moodle plugin allows teachers to hide questions that have been correctly answered in previous attempts. This can be useful in preventing students from seeing the correct answers and encourages them to attempt the questions again.

### Version

Plugin version: 1.0

Released on: 14 JUNE 2023

Authors: https://lmsace.com, LMSACE Dev Team

### Git Repository

Private Git Repository

Git URL: https://github.com/your-username/moodle-hide-correct-questions
### Installation steps using ZIP file.

1. Clone the HideCorrect Git repository to a location of your choice on your computer.
2. Rename the cloned folder to "hidecorrect" and compress it into a ZIP file.
3. Log in to Moodle as a Site Administrator.
4. Go to '*Site Administration*' -> '*Plugins*' -> '*Upload Plugin*', On here upload the plugin zip '**hidecorrect.zip**'.
5.  Go to ‘Site administration’ -> ‘Notifications’ , here on ‘Plugins check’ page you will see the '*Hide Correct Questions on New Attempt*' '*Quiz / Access rules*' plugin in listing.
6. Click the “Upgrade Moodle database now” button displayed on bottom of the page.
> You will get success message once the plugin installed successfully.
7. By clicking “Continue” button on success page. you will redirect to the admin notification page.

### Installation steps using Git.

1. Clone hidecorrect plugin Git repository into the folder '*mod / quiz / accessrule*'.
2. Rename the folder name into '**hidecorrect**'.
3. Go to ‘Site administration’ -> ‘Notifications’ , here on ‘Plugins check’ page you will see the '*Hide Correct Questions on New Attempt*' '*Quiz / Access rules*' plugin in listing.
4. Click the “Upgrade Moodle database now” button displayed on bottom of the page.
> You will get success message once the plugin installed successfully.
5. By clicking “Continue” button on success page. You will redirect to the admin notification page.

## Configuration
To configure the plugin settings, follow these steps:

1. Log in to your Moodle site as a '*course administrator*' or '*teacher*'.
2. Navigate to the course where the quiz is located.
3. Turn editing on.
4. Click on the quiz activity to access its settings.
5. In the quiz settings page, locate the '**Question behavior**' section and '*click on*' it.
6. Look for the '**Each attempt builds on the last**' setting and '*enable*' it. This setting allows each attempt to build on the previous one, retaining the user's previous responses and providing a cumulative learning experience.
7. Next, scroll down to the '**Extra restrictions on attempts**' section.
8. From the dropdown menu, select the option that says '**Hide the correct answered question in new attempt**'. This setting '*hides the questions that were answered correctly in the previous attempt*'.
9. Save the quiz settings to apply the changes.
With these settings enabled, when a learner attempts the quiz again, the questions will be hidden, allowing them to reflect on their previous attempt and make improvements without directly seeing the correct answers.
>Note: It's important to communicate these settings to your learners so they understand the behavior of the quiz and the purpose behind hiding the questions on subsequent attempts.

## Contributing
Contributions to this Moodle plugin are welcome. If you encounter any issues or have suggestions for improvement, please submit them through the [GitHub repository](https://github.com/your-username/moodle-hide-correct-questions/issues).

## License
This Moodle plugin is licensed under the [MIT License](LICENSE).

## Support
For support or assistance, please contact the plugin author or submit an issue through the [GitHub repository](https://github.com/lmsace/moodle-hide-correct-questions/issues).

## About
This plugin was developed by [LMSACE](https://lmsace.com/). For more information, please visit our website or contact us directly.