A new user form (UserNew) was created at postorius/forms.py where all the forms are defined. This form contains the essay, gender, and location fields. Form validation has been enforced; all three fields must receive user input or will prompt the user to fill in missing information.

In postorius/views/user.py, changes were made so that data on each user could be retrieved and displayed to the administrator. The user_new method was modified to accept new parameters.

Also, the user_index function was redefined from what it was previously, since the previous function was not correctly displaying information.

Several template files were added or modified. These include user_index.html, user_new.html, user_summary.html, and user_confirm_delete.html. All were changed in order to display the new information that the user contains -- its full personality.
