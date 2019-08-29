<style>
  /* Style the Image Used to Trigger the Modal */
#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (Image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption {
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform:scale(0)}
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
</style>

<script>
  // Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}
  </script>

## Multi Media UI Assignment

### Tools

For this assignment I used Adobe Illustrator for the wireframes and Photoshop for the mock-ups.

The reason why I used Illustrator for the wireframes is because of how it manages its objects. Every shape placed on the page can be moved and resized separately even when they're on the same layer. Since Illustrator is a vector-based software the elements never lost any quality. This was useful for making the wireframes as I was moving and changing the elements on the page frequently.


### Sketches

before I started making the wireframes I downloaded 7 homework/task manager apps so that I could keep my app consistent
- Study Planner
- Dreamie Planner
- Remember the Milk
- Any.do
- Planner Pro
- School Planner
- MyLifeOrganized: To-Do List

After testing those apps I started making some basic sketches of the layout and the UI elements.

<img src="imgs/multimedia/sketches/Scan1.jpg" alt="image" width="200">
<img src="imgs/multimedia/sketches/Scan2.jpg" alt="image" width="200">

### Wireframes

<img src="imgs/multimedia/wireframes/Wireframe-Homework.jpg" alt="image" id="myImg" width="200">

<!-- The Modal -->
<div id="myModal" class="modal">

  <!-- The Close Button -->
  <span class="close">&times;</span>

  <!-- Modal Content (The Image) -->
  <img class="modal-content" id="img01">

  <!-- Modal Caption (Image Text) -->
  <div id="caption"></div>
</div>

<img src="imgs/multimedia/wireframes/Wireframe-Menu.jpg" alt="image" width="200">
<img src="imgs/multimedia/wireframes/Wireframe-AddHomework.jpg" alt="image" width="200">
<img src="imgs/multimedia/wireframes/Wireframe-Projects.jpg" alt="image" width="200">
<img src="imgs/multimedia/wireframes/Wireframe-ProjectItems.jpg" alt="image" width="200">
<img src="imgs/multimedia/wireframes/Wireframe-Calander.jpg" alt="image" width="200">

### Mockups

<img src="imgs/multimedia/mockups/Mockup-Homework.jpg" alt="image" width="200">
<img src="imgs/multimedia/mockups/Mockup-Menu.jpg" alt="image" width="200">
<img src="imgs/multimedia/mockups/Mockup-AddHomework.jpg" alt="image" width="200">
<img src="imgs/multimedia/mockups/Mockup-Projects.jpg" alt="image" width="200">
<img src="imgs/multimedia/mockups/Mockup-ProjectItems.jpg" alt="image" width="200">
<img src="imgs/multimedia/mockups/Mockup-Calander.jpg" alt="image" width="200">

### Design Decisions

My intention with this app was to have a fast, easy and efficient way of viewing, completing and adding tasks to the app. Because of this the mock-up’s I have created are very minimalistic in order to keep the users focus on the listed items. I experimented with using gradients and images however they added too much noise to the screen (becoming too distracting and making it too hard to understand at a quick glance).

The coloured bars too the side of each list item represent what subject the homework is for (when adding a subject to the app you pick a colour for it). This adds a quick way to identify what subject the class is for without writing it under the date. The colours also make the page more visually interesting, because of this I could keep the rest of the app in greyscale (so that it always matches the colour of the subject and doesn’t take too much attention away from the homework which is the most important part of the app).

However, I didn’t add these bars to the project’s items. This was because a project will most likely be for one subject. Having a single colour bar down the side of the page for all items didn’t look very appealing. So instead I changed the colour of the header. So, the design I had didn’t have any colour, however that made the page very boring to look at and didn’t provide an easy way to identify what subject the project was for. Because of this I changed the colour of the header.

I’ve kept my app very consistent with other similar apps and software
-	All of my icons are blocky versions of already existing icons
-	The menu button is located in the top right
-	The add button is in the bottom right (some of the apps i tested had the add button in the bottom center, however because of Fitts law I decided to add mine to the right. I found having the button in the middle to be annoying to try to tap)
- checkboxes are located on the left of a task
- icons to edit tasks are on the right
