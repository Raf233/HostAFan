# HostAFan

Snippets of code from one of my main projects.

Location component that is resuable to provide the ability to render a Google map, with limitations to prevent giving out too much private info to the user, in other aspects of the project. Also allows the insertion of new locations to the database by presenting a form with validation through Formik and Yup that the user or admin can fill out and submit.


The Fan Dashboard component displays the main hub for users to visit and see information from the rest of the website tailored to their interests and location based on their profiles.

There are different sections to the dashboard, therefore each one was separated into their own components to organize code and to make it easier to return to and make changes if needed. The sections are grouped by related data and/or the area that each subsection is located on the page.

The SingleEvent and SingleReservation files are mapper components to map data passed to them into HTML ListItems to be displayed on a scrollable list in a section.

The ReservationDetails component displays the user with a more detailed page of a reservation they currently have and allows them the ability to cancel it from this page if desired.
