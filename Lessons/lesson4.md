# Lesson 4 - Review
Since HTML and CSS are such important parts of frontend web development, we're going to spend a little bit more time with them. For this lesson, we'll be going through some examples in order to really get this down. You may not have finished the HTML/CSS course on KhanAcademy, but that's okay for now. Just keep watching it, and we'll try to make sure we don't cover too much new ground here.

So, to start out, here's our first example:

### [Example 1](https://www.khanacademy.org/computer-programming/teaching-material-1/5373785929056256)

<details>
  <summary>For the Teachers</summary>
  <p>Feel free to play around a little bit with the program at the link. It helps keep the students engaged, to have interactive results like that.</p>  
</details>

Now, here's the problem. That webpage is okay, but it doesn't look very special right now. What are some things we can do to make it better? (HINT: You'll need to use both HTML _and_ CSS for this one)

<details>
  <summary>Expand to view the answer</summary>
  <p>There are a lot of things that could make this page better, but a few that I had in mind were:<br>
    <ol>
      <li>Turn the list of points into an order list! Remember, this requires the <code>ol</code> and <code>li</code> tags.</li>
      <li>Let's try changing the color of the header! Change it to whatever color you like, as long as there's enough contrast to read the text!</li>
      <li>Pro tip: A lot of the time, it's best to stay away from using colors that are perfectly white or perfectly black. It often looks better to offset them just a little bit. In code, this means taking something like <code>rgb(255,255,255)</code> and changing it to <code>rgb(253,253,253)</code> for white, or taking <code>rgb(0,0,0)</code> and changing it to <code>rgb(2,2,2)</code> for black.</li>
      <li>Finally, let's add a background for the paragraph content. Again use a color with enough contrast to read the text!</li>
    </ol>
  </p>
</details>

Great! You completed the first example! Hopefully you learned something new from that, or at least gained some exerience.
Now we're going to target a more specific skill. Let's say you have the following code:

```
<!DOCTYPE html>
<html>
  <head>
    <title>My Webpage</title>
    <meta charset='utf-8'>
    
    <style>
      ____ {
        background:red;
      }
      ____ {
        color:green;
      }
    </style>
  </head>
  <body>
    <p>
      <ol>
        <li>List item 1</li>
        <li>List item 2</li>
        <h1>
          Paragraph after the line items
        </h1>
      </ol>
    </p>
  </body>
</html>
```

The question here is, how should you fill in the blanks so that the entire ordered list has a red background, and only the `h1` inside the ordered list is colored green?

<details>
  <summary>Expand to view the answer</summary>
  <p>
    The first blank should be replaced with <code>ol</code>, and the second should be replaced with <code>h1</code>.
  </p>
</details>

That one was trickier, but probably not too difficult. If you keep practicing, your CSS will be great in no time!

Now, you should try making your own creation with HTML and CSS for a little bit! Go to [KhanAcademy](https://khanacademy.org/computer-programming/new/webpage) to play with some code!

## Ending Notes
This was a shorter lesson. The most important thing is that you keep practicing your HTML/CSS, and keep up with the KhanAcademy course. 
However, pretty soon, after we learn JavaScript, it'll be time to start making your own web app frontend!
It's a good idea to start thinking about what you want to build right now, so you'll be ready then.

Happy Coding!

