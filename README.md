# JS2 week1

# Overview of the Content:
- HTML vs CSS vs JavaScript
- Client and servers
- Document Object Manuapluation(DOM)
- Event Listener
- Exercise!

  ## What is HTML, CSS and JavaScript
  - HTML is a markup language for creating instructions on the page, and it helps to structure your page with elements such as paragraphs and headings. It's like the skeleton and bare bones of a human body.

   - CSS is a design language used to improve the page's appearance. It's used for laying out the position of the element. It's like the humans' hair, skin and general physical attributes.

  - JavaScript is the programming language, responsible for the functionality of web pages. It's like eating or sleeping in humans.
 
![alt text](html_css_js.jpg "HTML and Css and JS roles")
## Client and Servers
The client is a computer that can receive information and display it in a coherent UI. Gather inputs and communicate them to the server.

The server is a remote computer that provides information or access to a specific service.

When you enter a URL into the browser web address, your browser sends a request to the server where the data is stored. when recieving the request back, your browser interpet the HTML, CSS and JS code and renders it into the web page.

![alt text](Api.png "Client and servers and API")

## Document Object Manuapluation(DOM)

You can work with Javascript with the <script> tag inside the HTML. There is two ways of doing it, with the regular tag <script> [JavaScript function]</script> or with <script  src= [javascript path]></script>

Placement of the external script tag is usually recommened to be in the head tag.

### DOM

How can JS understand which element to change in HTML?
You can access the element in HTML by Document Object Manupluation. It represent the document as object and nodes with Id and attributes. DOM have a tree structre.
These are the function mostly used for accessing element in HTML in JS:
- getElementById
- getElementsByTagName
- getElementsByClassName
- appendChild

## Event Listner

Matches event handler to a spcific element. You can add many events to a single element. The event needs to be from HTML dom events.

   


