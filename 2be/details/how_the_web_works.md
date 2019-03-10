## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
 
 There is a hidden `.` at the end of this web address(`domain name`), which is the ROOT of the Internet Name Space.
 From here, your operating system checks to see if it has the IP address associated with this domain name on the computer or  in its `cache`. If it does not, it uses the `RNS`(Resolving Name Server) to check a series of places, which in order include the `Root Name Server`, `Top Level Domain` servers, and `Authoritative Name Server`. These are connected to the `Domain Registrar` where domain names are registered with their corresponding IP address. 
 
 Once the `RNS` has this info, it stores it in cash, gives it to the operatins system, which gives it to the browser, which makes the connection to the corresponding server via the internet.

1.  What does HTTP stand for?

 Hypertext Transfer Protocol

1. 	What protocol does the World Wide Web use?

 Protocols are a set method for exchanging information over the internet. Most commonly you will see `HTTP` or `HTTPS` in use over the internet.

1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?

 Internet Protocol

1. 	What does DNS stand for?

  ~~* A. Domain Name System~~
  ~~* B. Digital Number System~~
  ~~* C. Domain Number System~~
  * D. Domain Name Service
  ~~* E. Digital Name Service~~
  
1. 	How are text domain names matched to their respective numeric IP addresses.

 Using a `Root Name Server` which goes through a series of steps to find the respective IP address registered to the domain name.

1. 	What is the client?

  ~~* A. A purchaser~~
  ~~* B. Internet shopping customer (Consumer)~~
  ~~* C. The software which requests information from a server (browser)~~
  ~~* D. The server to which a particular computer sends data~~
  * E. The computer which the IP address belongs to
  
1. 	What does URL stand for?

 Uniform Resource Locator - the web address of an online resource.

1. 	What are protocols

 ~~* A. The standardisation of IP addressess~~
 ~~* B. The DNS standard method for data transfer~~
 ~~* C.	The standardised network address system~~
 * D.	The standardised method for transferring data or documents over a network
 ~~* E.	The standardised method for prioratising data or document storage over a network~~
 
1. What does DNS stand for?

 Domain Name System

1. what is the `www` portion of a url?

 Stood for `World Wide Web`. Some old systems may still require this in a url, but generally it is not needed.

1. What is The markup language used for all web documents?

 `HTML` - Hypertext Markup Language

1. What is the organization that monitors web technologies?

  W3C (World Wide Web Consortium)

1. What is the Protocol for transferring web documents on the Internet?

 `HTTP` - Hypertext Transfer Protocol

1. What matches the domain names with numeric IP addresses?

 A `Resolving Name Server` - which goes through a series of steps. Ultimately a domain name is registered at the `Domain Registrar`




