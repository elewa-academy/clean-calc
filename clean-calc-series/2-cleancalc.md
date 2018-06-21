# CLEANCALC v.2.* - Embedded in HTML  

For this step you will create a browser UI for your cleancalc object.   There are only two unbreakable rules:
* You cannot change your calculator object in any way from the last version.
* Only your event listeners can call the calc object, they will translate between the user and the calc object's logic.

If you do this correctly you will be able to copy paste anyone's cleancalc.js file into your /public folder without breaking your project.  This illustrates the distinction between logic & framework. The word for this is "separation of concerns".  One concern is doing math, the other is handling and cleaning user input.

Once you understand this principle it's not long before you're thinking of _dependency injection_, and _interfaces_.  

---

Your finished project will have:
* index.html
* /public
  * cleancalc.js
  * event-listeners.js