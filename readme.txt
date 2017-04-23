An atttempt at consuming a JSON Array of Objects by Alex Keillor

Note: I found this hard during school holidays to find a few hours to do this.

Copy the contents of the folder DTA/*.* to a directory on your machine.
the HTML wireframe should be working.  This prototype does not have server side processing or client side validations as yet.

Basic Wireframe is configured using:
* Bootstrap JS-min
* Bootstrap CSS-min and
* JQuery

I got hung up on the NULL array pointer in the JSON feed and simply ran out of time I could find. So the log isn't there as I liek having the basic  visuals for a site then hook in the logic - this way i can still do a showcase and has saved my bacon in the past.

So .. .the solution as it stand is a basic navigation for a web site:
* Header
* Left Nav
* Center Content for product feed - incomplete
* right Nav as shopping CART - not implemented

Got hung up on processing the JSON object array.  In essence how to handle nulls in the client using JavaScript and I simply ran out of time.

My strategy was to consume the service.  Implement a button that would load the selected item into a input box: Name, unit price, quantity, special quanitty and special quantity pricing. In the input box perform the function for totals for that item. Handle special quanities and prices and scenarios around that, then add the item to a shopping cart via javascript DOM.  

Finally refactor to use server side logic and AJAX.

Tidy up any other loose items.

Ran out of time ... i ahve kids on school holidays (NSW) and doing dancing/footy competitions, hence I struggled to find more than 2-3 hours for this.

Place holders are in the HTML for what I wanted to do - oh well.  