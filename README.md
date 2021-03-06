<h6>Ben Hasselgren</h6>
<h1> Interactive Frontend Development Milestone Project  </h1>
<a href="https://benhasselgren.github.io/ifd-milestone-project-pages/" target="_blank"> Click here to view website</a>
<h3>Quick Tutorial</h3>
<ol>
    <li>First enter select a country from the dropdown menu. Notice how the map zooms in over that country</li>
    <li>Now type a country in the correct field. Notice how the cities generated are restricted within that country</li>
    <li>Now toggle the radio buttons to change the places you are searching for within that city</li>
    <li>To revert everything, press reset</li>
</ol>
<h3>Purpose</h3>
<p>
    The purpose of this project is to create a website that allows users
    to search for holiday locations by being able to see what hotels, tourist attractions and resteraunt/bars
    there are to visit in different cities. The website makes use of the google maps api to search for all the differnt places on the map.
    The results of the users map quesries should be presented in a readable and user-friendly way/
</p>

<h3>Functionality/Technologies</h3>
<p>
    This website has lots of functionality. One functioniality is that it's resposnive. It has responsive elements
    such as the map and filter sections that adapt to make the website more user-friendly on mobile and desktop devices.
    The map also has functionality as it allows the user to see clearly all the locations of what they have searched. They can also 
    zoom in and out with the map, click on markers to view information about places. The filter section allows the user to manipulate the 
    map to zoom in on cities, countries and change what markers they want to see.
</p>

<p>   
    There is some different technologies used in this project. Bootstrap was used for the structure of the web pages(html).
    Using Boostraps classes, tables and grids were made to give the website a nice layout with a responsive design. Google fonts were also 
    applied in the header to give font a Roboto or Exo font-family. Google maps api was used to manipulate and design an attractive map that 
    shows all the locations of places that the user has searched for. I used google maps api tutorials and used code from there originally. This code 
    showed me hot to zoom in to places on events forced by the user. It also showed me to how to take information of discovered
    places and then add that to html elements to display to the user.I then added to this code to make it more suited tothe brief and allow searching so be more interactive
    and alow the user to query cities in more detail.Then after I was happy with the functionality of the map search I realised
    the code was made with only javascript. I linked a jquery file and started to neaten things up by changing lots of 
    javascript to jquery. I did however find this hard as I realised a lot of the google maps api code relied on javacript
    so I was unable to fully change all my code.
</p>

<h3>Testing</h3>
<p>
    This website was tested using Chrome development tools. The website was created on a design made
    by wireframe diagrams using Balsamiq. It was important to make sure the final version looked like the designs so
    Chrome development tools were used to test out all the features and see if they responded correctly and looked 
    right. Once mistakes/changes were made with Chrome, the code was copied to the actual code to fix the issue permanently.
</p>
<p>
    I also did some manual tests. Here are a couple examples
</p>
<table>
    <tr>
        <th>Test</th>
        <th>Input</th>
        <th>Expected output</th>
        <th>Output</th>
        <th>Pass?</th>
    </tr>
    <tr>
        <td>Testing to see if the correct country comes up when selected country</td>
        <td>Canada</td>
        <td>Cities that are in Canada</td>
        <td>Cities that are in Canada</td>
        <td>Yes</td>
    </tr>
    <tr>
        <td>Testing to see if a the city field is reset when clicked on reset button</td>
        <td>Click on reset button</td>
        <td>all cities should shown now</td>
        <td>all cities shown</td>
        <td>Yes</td>
    </tr>
</table>
<h3>Deployment</h3>
<p>
    This website was deployed to github pages. It was very easy to set up as the website has been put in a github repository from the start so all that had to be done was activate github pages and point the source to the master branch. 
</p>