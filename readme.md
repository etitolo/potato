Hello,

To fire this up locally in a browser, please use the following URL:
http://localhost:8000/app/#/potato

Preview is here: http://etitolo.github.io/potato/

This is my first attempt at Angular. Here's a list of things that I know don't work:

* The detail view does not display any data. I couldn't find any sensible data to use for the photo ID. The only fields that have the photo ID were "link" and "description." Both would require a RegEx pattern to scrape the data from the field. I didn't do it because it felt like a hack and I wasn't sure how to do it in Angular.
* The Flickr API spits out malformed data and CORS isn't set up properly server-side. To get around this issue, I downloaded the JSON, removed the malformed data, and saved it to a file locally. You might want to modify the coding exercise to use data from something like https://randomuser.me/.
* I was given 3 wireframes. The two that worked together were the photo list and photo detail. I couldn't figure out how the post list fit into the application.
