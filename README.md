# [twister](https://github.com/ShepherdJerred/twister)
Android app similar to Twitter with a mock backend

### Known bugs
* Twist searching not implemented

### Extra credit
* Image caching

### Contributions
Noah Kinslow (0%)

Jerred Shepherd (50%)
* App icon
* DataFetcher
* User login
    * LoginActivity, LoginFragment
    * Show error message if API returns error
* Twist List
    * ListActivity, ListFragment
    * Recycler view
    * Relative time
    * Click to show details
    * Action Bar
        * Add twist
        * Search twists
        * Logout (overflow)
        * About (overflow)
* Add Twist
    * AddTwistActivity, AddTwistFragment
    * Disable posting if textbox doesn't have one non-whitespace character or
      more than 150 characters
    * Posting returns it to list activity
    * Add twist to SQLite DB
* User Details activity
    * DetailActivity, DetailFragment
    * Recycler view
* Database/cache
    * TwisterDatabase, TwisterDatabaseHelper
* Image caching (Extra credit)
