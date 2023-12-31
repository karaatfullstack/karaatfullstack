## Hi there 👋

<!--
**karaatfullstack/karaatfullstack** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
- 🌱 I’m currently learning... how to make a github portfolio for my students
- 💬 Ask me about... how that's going
- ⚡ Fun fact:... I have a 14 year old chinchilla. He might be immortal.

---
## How to make a Github portfolio
1. Go to your Github page and click to create a new repo
2. Name that repo the same thing as your username (If your username is coolcode2000, name your repo that as well)
3. Once you've typed in the repo name, a message will appear:
<img width="650" alt="Github Readme" src="https://github.com/karaatfullstack/karaatfullstack/assets/116577743/1478056d-87ba-48de-b694-05471c52c76c">

4. Make sure to select PUBLIC as the type of repo, and to check the box that adds a README file
5. Create your repo and head back to your main profile page - you'll see the file appear at the top!
---
## How to make your page B-E-A-utiful

You can technically use CSS in most markdown files, but it's recommended you use actual markdown when you can. Here is a [basic style guide](https://www.markdownguide.org/basic-syntax/#overview) to get you started.

### #1 - Add images
  - You can simply drag and drop images from your computer to Github, and it will be saved in your assets folder. Dropping the image will create an img tag in your README, which will have 'width' and 'alt' attributes that you can update to resize and change.

### #2 - Add gifs:
  - The easiest way to do this is save the gif to your computer, then drag and drop it into the README file
  - The other way is by going to a site like giphy.com and choosing a gif. Once selected, choose the "Embed" option
  - Don't paste the entire div into your README - instead right click on the image and select "copy image address". Create an img tag and place that address in your 'src' attribute - the img element will display your gif, and will look amazing.
 <p align="center">
   <img width="350" alt="delightfully surprised" src="https://media4.giphy.com/media/3og0IPNcCRz8Tizbd6/giphy.gif?cid=ecf05e478lg12dq4ab01fvme5934hieky4l047ms89iy8fcv&ep=v1_gifs_search&rid=giphy.gif&ct=g"/>
 </p>

 - Remember that when you're taking images you check that they are free to use! If a site requires you to link back to it, you can do so with an HTML anchor tag
 - You can center and style items using HTML. To get the gif centered, I placed my img element into a paragraph:
```
<p align="center">
   <img src="myImage.jpg"/>
 </p>
```

### #3 - Add badges:

A badge is a logo image you can add to link other social media and portfolio sites.

The standard code:
```![Badge Name](https://img.shields.io/badge/BadgeName-hexColorforBackground)```

So, to make a LinkedIn badge, this is the code and result:

```![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2)```

![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2)

- [Here is the site](https://simpleicons.org/) with all the SVG icons

To make the badge link to a site, simply wrap it in an anchor tag, like so: 

```<a href="https://www.linkedin.com/yourLinkedIn"> ![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2) </a>```

And now it's clickable: <a href="https://www.linkedin.com/in/kara-cavanaugh/"> ![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2) </a>

### #4 - List technologies
Example of how this section can be styled: 
<h2> &#127881; Tools and Technologies &#127881;</h2>
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" width="60" height="60"/> &ensp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript" width="60" height="60"/> &ensp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="60" height="60"/> &ensp;
</p>

- [Devicon](https://devicon.dev/) has development-specific icons
- Here is a [list of HTML emojis](https://www.w3schools.com/charsets/ref_emoji.asp) that can be used as plain text

The code I used to create that section is here:
```
<h2> &#127881; Tools and Technologies &#127881;</h2>
<p align="left">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" width="60" height="60"/> &ensp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="javascript" width="60" height="60"/> &ensp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="java" width="60" height="60" /> &ensp;
</p>
```

- Some CSS can be added to change the size of the emojis, but Github doesn't allow all properties (like margin). To make spaces, I used an actual space character: `&ensp;`
