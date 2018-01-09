# shinylogin
An example shiny app with user/password authentication

## What

This is a minimal shiny app which exhibits how unique users/passwords can be used.

## Why  

Because sometimes (a) you only want some people to access your shiny app, and/or (b) a user's identity is important to the app's functionality.

## Extending use  

In this example, the `users` object (which contains users' names and passwords) is a simple dataframe, created in the `app.R` script. To the extent that creating data in-code can be unwieldy, one might consider using a spreadsheet file (such as a `.csv`), an external package (such as `gsheets`) or a database for storing the `users` object. 

## Caveats  

This is a minimal viable example. The table of usernames and passwords is expected to exist in memory as an unhashed dataframe. For app's with substantial security needs, more complex solutions should be considered.

## Who

This app was built by [Databrew](http://databrew.cc). Feel free to copy, modify, use, etc. in whatever form you'd like.