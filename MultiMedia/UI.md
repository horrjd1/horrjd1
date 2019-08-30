<style>
  table{
  border: none;
  }
  td{
  padding: 0px;
  margin: 0px;
  border: none;
  text-align: center;
  }
  tr{
    border: none;
  }
  h3{
  padding: 0px;
  margin: 0px;
  }
  </style>

# Multi Media UI Assignment

For this assignment I decide to design the UI for a homework manager mobile app.

## Tools

For this assignment I used Adobe Illustrator for the wireframes and Photoshop for the mock-ups.

The reason why I used Illustrator for the wireframes is because of how it manages its objects. Every shape placed on the page can be moved and resized separately even when they're on the same layer. Since Illustrator is a vector-based software the elements never lost any quality. This was useful for making the wireframes as I was moving and changing the elements on the page frequently. 

The reason I used Photoshop for the mock-ups was because it provides a lot more freedom and control for adding images and effects to the mock-ups. I also didn’t need my shapes to be vectors anymore since I was working with the wireframes as a guideline and therefor knew the size that every element was going to be on the screen. When making the mock-ups I made sure to use plenty of layers for each of the elements so that my work was as ‘non-destructive’ as possible (I could easily change certain parts of each element and go back to old ones if necessary.

I made the wireframes and the mock-ups to be a resolution of 750 x 1334. I did this because that is the resolution of the iPhone 6 which is the bestselling and most used touchscreen phone. I exported all of my images in the .jpg format. I did this because jpgs are a lossy format (meaning that it gets compressed). This will make them load faster on the web page I’m deploying them on. Also they are just wireframes and mock-ups so it doesn’t matter if some of the quality is lost (unlike if it was a promotional).


## Sketches

Before I started making the wireframes I downloaded 7 homework/task manager apps so that I could get a general idea of the features and the layout that all of them have in common. The ones I tested were:
- Study Planner
- Dreamie Planner
- Remember the Milk
- Any.do
- Planner Pro
- School Planner
- MyLifeOrganized: To-Do List

After using these apps I noticed how not many of them did projects (checkboxes with sub items) and didn’t display overdue items (these items would just disappear from the agenda screen and can only be viewed from the calendar). Because of this I wanted to include overdue items and a projects screen in my design. At this point I also decided that my target audience would be students, this means that they should have an understanding of how mobile apps work, therefor I could use icons for filtering/sorting instead of having them typed out. After using those apps as a bases I started making some basic sketches of the layout and the UI elements (the images are clickable).


<a href="imgs/multimedia/sketches/Scan1.jpg">
<img src="imgs/multimedia/sketches/Scan1.jpg" alt="image" width="300"/>
 </a>
 <a href="imgs/multimedia/sketches/Scan2.jpg">
<img src="imgs/multimedia/sketches/Scan2.jpg" alt="image" width="300"/>
 </a>

## Wireframes
All images are clickable.

<table>
  <tr>
    <td>
      <h3>Agenda</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-Homework.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-Homework.jpg" alt="image" width="200" />
        </a>
    </td>
    <td>
      <h3>Menu</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-Menu.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-Menu.jpg" alt="image" width="200"/>
        </a>
    </td>
    <td>
      <h3>Add Homework</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-AddHomework.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-AddHomework.jpg" alt="image" width="200"/>
        </a>
    </td>
  </tr>
  
  <tr>
    <td>
      <h3>Projects</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-Projects.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-Projects.jpg" alt="image" width="200"/>
        </a>
    </td>
    <td>
      <h3>Project Items</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-ProjectItems.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-ProjectItems.jpg" alt="image" width="200"/>
        </a>
    </td>
    <td>
      <h3>Calander</h3>
        <a href="imgs/multimedia/wireframes/Wireframe-Calander.jpg">
          <img src="imgs/multimedia/wireframes/Wireframe-Calander.jpg" alt="image" width="200"/>
        </a>
    </td>
  </tr>
</table>

## Mockups
All images are clickable.

<table>
  <tr>
    <td>
      <h3>Agenda</h3>
        <a href="imgs/multimedia/mockups/Mockup-Homework.jpg">
          <img src="imgs/multimedia/mockups/Mockup-Homework.jpg" alt="image" width="200"/>
        </a>
    </td>
    <td>
      <h3>Menu</h3>
        <a href="imgs/multimedia/mockups/Mockup-Menu.jpg">
          <img src="imgs/multimedia/mockups/Mockup-Menu.jpg" alt="image" width="200">
        </a>
    </td>
    <td>
      <h3>Add Homework</h3>
        <a href="imgs/multimedia/mockups/Mockup-AddHomework.jpg">
          <img src="imgs/multimedia/mockups/Mockup-AddHomework.jpg" alt="image" width="200">
        </a>
    </td>
  </tr>
  
  <tr>
    <td>
      <h3>Projects</h3>
        <a href="imgs/multimedia/mockups/Mockup-Projects.jpg">
          <img src="imgs/multimedia/mockups/Mockup-Projects.jpg" alt="image" width="200">
        </a>
    </td>
    <td>
      <h3>Project Items</h3>
        <a href="imgs/multimedia/mockups/Mockup-ProjectItems.jpg">
          <img src="imgs/multimedia/mockups/Mockup-ProjectItems.jpg" alt="image" width="200">
        </a>
    </td>
    <td>
      <h3>Calander</h3>
        <a href="imgs/multimedia/mockups/Mockup-Calander.jpg">
          <img src="imgs/multimedia/mockups/Mockup-Calander.jpg" alt="image" width="200">
      </a>
    </td>
  </tr>
</table>

## Design Decisions

My intention with this app was to have a fast, easy and efficient way of viewing, completing and adding tasks to the app. Because of this the mock-up’s I have created are very minimalistic in order to keep the users focus on the listed items. I experimented with using gradients and images however they added too much noise to the screen (becoming too distracting and making it too hard to understand at a quick glance).

The coloured bars to the side of each list item represent what subject the homework is for (when adding a subject to the app you pick a colour for it). This adds a quick way to identify what subject the class is for without writing it under the date. The colours also make the page more visually interesting, because of this I could keep the rest of the app in greyscale, so that it always matches the colour of the subjects and doesn’t take too much attention away from the homework, which is the most important part of the app.

However, I didn’t add these bars to the project’s items. This was because a project will most likely be for one subject. Having a single colour bar down the side of the page for all items didn’t look very appealing. Once I deleted them the page didn’t have any colour, making the page very boring to look at and didn’t provide an easy way to identify what subject the project was for. I tried adding colour in various places (like creating a new subtitle with a coloured background and changing the colour of the items themselves), however the least jarring way to do this was to change the colour of the header.

I’ve kept my app very consistent with other similar apps and software
-	All of my icons are blocky versions of already existing icons
-	The menu button is located in the top right
-	The add button is in the bottom right (some of the apps I tested had the add button in the bottom centre, however because of Fitts law I decided to add mine to the right. I found having the button in the middle was annoying to try to tap)
- Checkboxes are located on the left of a task
- Icons to edit tasks are on the right

When I started I tried to keep Fitts law in mind (that if the user is right handed and holding the phone with one hand, then their thumb will be around the bottom right). Because of this I considered placing menu items (icons and homework/exams) at the bottom, however I valued consistency with other mobile apps and homework management apps more than having the most used buttons close to the users thumb. 

I also have two different add buttons, the plus symbol and the ‘ADD’ button on the 'Add Homework' screen. I used the plus symbol to represent wanting to add a new item to the list, and used the 'ADD' button to represent submitting the filled entries and adding them as an item to the list. I ended up making the ‘ADD’ button because I felt like the plus symbols meaning wouldn’t come across as a submit button if it were placed on the 'Add Homework' screen (the plus symbol has always been used to add an item to the list and symbols don’t often get used as submit buttons). I also didn’t use the 'ADD' button on any of the other screens because it took up too much space.

On the menu screen I decide to put a dark overlay over the screen in the background. I did this to separate the menu from the rest of the page and too keep the users focus on the menu. It also indicates to the user that if they tap in that area then the menu would minimize.
