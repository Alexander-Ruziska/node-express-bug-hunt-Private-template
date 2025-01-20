# Node & Express Bug Hunt!

**READ ALL INSTRUCTIONS BEFORE STARTING**

There are 10 bugs in total, can you find them all? There are hints throughout (???), you should only need to make minor modifcations to 10 lines of code.

**Don't race through the files looking for the issues!** They should all have a console log or error that help you identify them. Read the console so that you know what error will cause each bug. The last one is tricky since it doesn't throw any errors. Document the error, line number and your fix in this README for each of the bugs.

## Setup
```
npm install
npm start
```

> NOTE: A couple of bugs prevent the server from starting.

## Error List

TODO: Add the error here followed by the line of code you fixed.

1. // ??? Look here for files
app.use(express.static('server/public'));

2. // Use 5001 for localhost development
const port = process.env.PORT || 5001;

3. // ??? List of quotes
let quoteList = [];

4. // ??? GET request returns information
router.get('/', (req, res) => {

5. // ??? POST request save user input
quoteList.push(quoteToAdd);

6. // PUT request update information
module.exports = router;

7.  url: '/quotes}' to  url: '/quotes'

8. // ???
 getQuotes();
 
9. <!-- ??? Our JavaScript file -->
axios and script swapped places.
10. 



### Bug 0

`ReferenceError: app is not defined`

Fixed `quote.router.js` line 28: switch `app` to `router`. _This is the solution to the first bug._

### Bug 1

...

## Extra Practice (Optional)

Complete the JS debugging exercises at:

- https://education.launchcode.org/intro-to-professional-web-dev/chapters/errors-and-debugging/exercises.html
