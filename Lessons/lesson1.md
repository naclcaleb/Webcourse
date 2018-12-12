# Lesson 1 - Structure of a Web Application
### What is a web application? 
A web application or web app is a client–server computer program in which the client (including the user interface and client-side logic) runs in a web browser.

But what does that mean?

![Figure 1.1](/resources/WebAppStructure.png)

As shown in Figure 1.1, a web app is composed of two main parts: a __frontend__ and a __backend__.
The frontend is a set of computer programs that run on the user's computer (the __client__ computer), while the backend is a different set of computer programs that run on a more powerful __server__ computer.

So this definition is really just saying that a web application is a big set of computer programs, separated into a frontend and a backend, that is viewed in your web browser (and I extend this definition to include mobile apps).

### The Frontend
Simply put, the frontend is everything you *see* when you look at a website, or open a mobile app. 
For example, go to [Google.com](https://www.google.com). Take a look around. You might see some text, some images, and a big search box in the middle. All these components are drawn on your screen by the frontend code. 

#### Frontend languages
The Frontend can be either a website or a mobile app (or both), as shown in Figure 1.1.
The main three languages for building a website are HTML, CSS, and JavaScript (JS). HTML defines content, CSS defines how that content should look, and JavaScript adds interactivity to the page.

A mobile app frontend has more options. Here are some of them:
Swift, Java, Kotlin, JavaScript, and, more recently, Dart.

### The Backend
The backend is a bit harder to conceptualize than the frontend. Go back to [Google](https://www.google.com). Look around again. As I said before, all this is drawn by the frontend code. But the frontend code isn't able to provide all of that information on its own. When you visited that site, your computer asked the backend server for the frontend code. The frontend code then asked the server for some information, such as whether the user is logged in, and where their profile picture is located. These are things that *only the backend knows*. In this way, the frontend and backend work together to present all the information the user needs.

#### Parts of the backend
The backend can be further divided into two primary parts: the database and the intermedium.
