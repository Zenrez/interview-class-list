## FE Take-home: Class List UI

### Goal

For this assignment, you are working with a fitness studio to display a list of their hot new classes!

They already have an API endpoint available for use: https://zenrez-interview.herokuapp.com/classes.

You will build a single page to display the classes in that list. For each class returned by the above endpoint, please show the following information:

* The class name
* The instructor name
* The start and end time
* The price
* The preview image

The studio would like each class to be displayed in a format similar to the following:

![Class row mock](images/class_row.png)

### Additional features

The studio has other ideas on how to improve their website. If they have more of your time, their next top requests would be:

* Showing a loading spinner while the classes are being fetched.
* Allow the user to click into a class. Clicking a class should allow them to view a page with a larger image and the full description.
* Break the list into separate pages, with three classes showing per page.
* Allow the user to book a class. Each class should have a button that makes a PUT request to https://zenrez-interview.herokuapp.com/book-class. The Content-Type should be `application/json`, and the request _body_ should include a `classId` parameter. Update the UI when the class is successfully booked. Check out `classId: 6` for an example error response.

### Guidelines

* Please use JavaScript, but feel free to use any frameworks/libraries/build tools you prefer.
* This is just a single page for now, but the studio intends to build upon this project in the future. Keep this in mind when choosing how to structure your code base.
* Share the code with us by sharing a Github repository or zipping the entire repo and emailing it to us.
* Have a demo page available, either published on the web or pre-built locally into a file.
* Please spend no more than ~4 hours working on the assignment. Try to find a consecutive block of time to work on it if you can.
* Think about what kind of user experience would be delightful to you.

Good luck and have fun! ✨ Please reach out to us if you have any questions.
