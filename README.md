## Welcome to A No Storyboard iOS app

This app shows how to create an iOS app that consumes json data from an external url and displays that in a UITableView. The app doesn't use a storyboard and instead constructs it's entire UI in Swift code.

### Some properties of it

It has the following properties 

- it uses NSURLSession to query the external url
- uses JSONDecoder to parse data into native Swift objects
- lazy loads image for a feed item
- dynamically adjusts the height of each row displaying the feed based on feed item length
- bypasses ATS
- reads a local json file for the feed when no internet access

### A more beginner friendly example to create iOS UI in code
This project is a little overwhelming for new comers and I fully understand that, hence I have written a more beginner friendly tutorial for creating iOS UI in code [here check it out](https://mydaytodo.com/ios-app-no-storyboard-how-to/).


### Support or Contact
Find it useful? For more useful info, checkout my [blog](https://mydaytodo.com/blog) and if you'd like to support me, you can try one of my [apps](https://mydaytodo.com/apps)
