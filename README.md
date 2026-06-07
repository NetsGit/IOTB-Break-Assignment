                                                         Class 01 (The 2026 Web Ecosystem)
THEORY:
(1)
        HTML
          |
       DOM TREE
          |
      RENDER TREE
          |
        LAYOUT
          |
        PAINT

HTML ---> DOM TREE ---> RENDER TREE ---> LAYOUT ---> PAINT

Understanding how the web browser takes in HTML to give a visual display on the screen matters as a developer because in every HTML contains Elements which serves as a building block for HTML pages, Where the brower goes through the html in a tree like structure to easily understand the html elements, then the DOM (Document Object Model) is fixed up with CSS (cascading style sheet), which sytles the element, allowing the browser to understand  both the content and the look, in general all element has position and sizing and the browser calculates this as a layout where we have the CSS box model which consist of four part (content, padding, border, and margin). at the final part this is where the web page becomes visible to the web user.

(2)
QUIC is impoetajt no because it’s the modern protocol used by the HTTP/3 and is built on UDP unlike the earlier days where we had HTTP/1 and HTTP/2, where they make use of TCP which is slower and a delay in process of a data disrupts other data eg. A slow internet connection or switching of internet. This is where QUIC comes in because it take out disadvantages of the previously used TCP, Especially where information needs to arrive early.

(3) https://registration.waecdirect.org/# After my inspection, i noticed the site relies on generic containers, which may make navigation less clear for assistive technologies, while also inspecting, i observed there was a link that had no action and on click never redirected and the while i tab, i didnt notice anything over there, like the focus didnt move through the link.

PRODUCT THINKING:
(1)
Basically semantic HTML are very important when it comes more traffic / SEO, because it gives direction and that is what, firstly looking at the <article> tag, it directs the search engine to the content, letting it know a presence of the content, while the <header> tag gives lnformation like the page title or blog tile, which bring out the chef name when users are in need of services. Then the  <main> tag contains the general content of the chef, eg blog posts, then the <aside> can be a side bar where you can find popular post / content of the chef or related articles. When semantic html is used, it tells the search engine, it’s well structured / optimized.

(2)
Firstly edge computing enables data to travel shorter distance, by bringing server closer to the user, so In real time, edge computing help multi playing game by enabling low latency, better synchronization for each user to experience same actions at the shortest time possible, reduced lag, which bring activeness not a player repeating multiple actions at the same time, all for a smoother gaming experience.

ENGINEERING BEST PRACTICE:
(1)
I disagree and you can’t use div everywhere, and those are the advantages of having semantic tags / elements. In terms of accessing, excessive using of div which just acts as a generic container and would be a disadvantage to screen users, because they won’t know which area is which, be it navigation or going to a particular content, eg the main content. On the part of seo, the search engine is confused because it doesn’t give a specific direction and which lead to bad crawling and poor index and lastly for maintainability and developer collaboration, div everywhere means the code is hard to maintain with no purpose of each section that also leads to poor collaboration and less understanding of layout, increasing the product finish time.


                                                Class 02 (Typography & Information Hierarchy)
THEORY:
(1)
Basically <em> mean emphasis and the <i> italics, the emphasis stress more on the important of a word or group of words eg, the assignment should be submitted before 8:00am Saturday, the empasis can be used on before 8:00am Saturday to stress on the important and lastly <i> is just to create a difference and styling from other text and doesn’t mean it’s necessarily important.

(2)
<nav>, <main>, <button>, while these are commonly used, screen readers treat them differently or rather specially because it also give direction where a screen reader knows, <nav> is a navigation to navigate between area of a website without going through the entire page or website and the <main> area signifies the main content area to screen readers enabling them to not repeat action and go straight to the main content and lastly, <button> signifies a clickable element that carries out an action and its interactive and can be activated with keyboard keys also.

(3)
So while semantic html first, Arial label is where it’s only needed, eg. 
<button aria-label="Search">
</button>, at this instance, it describes the button. When to fix html instead would be when using <div>:
 <div aria-label="Submit Form"> Submit </div>, here the aria label doesn’t make it an actual button instead - <button> Submit </button>, it’s recognized as a button immediately.

ACCESSIBILITY REFLECTION:
(1)
https://www.nairaland.com/
I pressed Tab multiple times and i was able to move through the navigation menu, major links and the website in general. The order generally followed the visual layout of the page.
The email field when you want to register had a visible label above the input, the focus was good on the button which points out they are clickable for search, submit and even the links / text click through to another page.

PRODUCT THINKING:

                                                Class 03 (Modern Assets & Linking)
THEORY:
(1)
Working with that is going to be an issue, because firstly 5mb is too much and it increases page load time and also affect seo which is important for every website, while I was a blogger far back as 2021c I would usually make use of webp images since it’s a modern format of image, include lazy loading and always use cdn to enable speed (eg. Cloudflare). While PNG has its advantages, converting to a modern image format and resizing with an image resizer to reduce visible image quality drop, because sometimes, image resizing is necessary when the size is required, eg. uploading a profile picture, or even for artist that distributes songs.

(2)
Just like explained in class, while every image tag has a source (src), the srcset is like specifying different width for different screen size and when a browser is been accessed on various devices, the srcset enables the browser to display the needed imagine to the required screen size. For a mobile users it’s important because eg, if a mobile screen needs 480px and large image is been displayed eg. 1200, firstly it breaks the website layout, reducing responsiveness and also increasing the page load speed and bad user experience increases the bounce rate, as user enter they leave, leading bad ranking, because engine perceives it as a bad website and leads to bad seo.

(3)
Both rel="noopener" and target="_blank" controls how a page / tab works and this is very important, the function of target="_blank" is to create a background / new tab but is just like when you enter a house and you leave your door open while rel="noopener" opens a new tab but keeps the door close, all these is important for security reason, now imagine when you click on ads and it opens a new tab, imagine your back down is opened and hackers make use of that to steal your data. So it’s best to make use of rel="noopener" to close the door behind you.

Engineering THINKING:
(1)
50 images is like you are working with a gallery, more like you are spamming images, so we need to work on the images by applying modern assets, because if not users or the website will experience slow load, bad experience and finally it might just lag, considering networks also, a using a modern image format is required and creating fallbacks, while I have never used Avif personally it’s the best, then fall back to webp and then jpg or png as the last fall back then srcset for screen selection, since there are lots of images and mobile users should be considered then applying lazy load and cdn is good, while using Wordpress then, there are plugin that automatically resize images enables, that would also reduce load time and increase page speed. Because imagine when you have a poor connection and you have to wait forever for image to load.

                                                Class 04 (Modern Forms & User Experience)
THEORY:
(1)
What happens with the user experience flow is that, is that for client-side-only validation, the validation is being done via the client side alone, meaning when there is an error like, .com isn’t included or @ isn’t included, it shows that it isn’t an email and that way, it’s rejected, this is good for the server because it reduced request been made to the server and also prevent page load but not fully secure then for the Server-side-only?, it makes it more secure but user spend more time waiting before getting an error message. Need both is removing the disadvantages, getting a better user experience and security.

(2)
Autocomplete, enable suggestion before typing what you wanna type, I have experienced this with browser or even when you wanna fill a form, name, email and sometimes browsers save up to bring it up later as autocomplete, this help remove typing error and saves time. 

Working with common values, 

1.Email: (autocomplete="email") you can use it during login form or registration forms 

2.⁠Street address: (autocomplete="street-address") to easily fill out address be it for shipping or delivery 

3.⁠Current password: (autocomplete="current-password") most time one mightnt even know their current password but that helps the user to Autocomplete it 

4.Name: (autocomplete="name") while filing forms of first name and last name fields

5.Telephone: (autocomplete="tel") to fill up forms of phone number field

PRODUCT THINKING:
(1)
How to handle it gracefully is by applying progress saving, I remember when I was filling an application form then, I mistakenly refresh and I was like, I can’t imagine filling again, to my surprised it was saved, so that is a good feature a form should have, save progress automatically. Then for validation strategy and error messaging would be validating each step, making sure that user don’t skip steps by letting by letting user know it’s required and for the error messaging it’s letting user know their progress has been saved due to maybe internet connection or refresh and they can continue from where they stopped, although I didn’t experience that during the job application then.

(2)
In simple terms native <select> should be used when with simple list that has to do with simple pick / select because it’s faster to build and and easy to understand eg. When selecting gender (Male or Female) on the other hand when you need a complex list, where you need to select more than one option or even search in the list, eg search for a particular country where you have a lot of country listed, it’s best to use the custom drop down.

ENGINEERING PRACTICE:
(1)
When working with an accessible password input one should focus on including a password field with a visible label, a show or hide password toggle, a password strength meter, and a requirements checklist.

The password field should indicate the password label, a toggle Show and Hide button should be next to the field so users can verify what they have typed as most website mostly show and eye which indicate a see through, The button should be keyboard accessible and include an ARIA label.
As the user types or increase the input the password strength meter should get update as the user increases the password value or character and the meter displays indication such as Weak, Medium, or Strong. For screen reader users, the strength status should be announced.
A requirements checklist should be displayed below the field and update in real time:

(===) At least 8 characters
(===) Contains uppercase letter
x Contains number
x Contains symbol

As the password improves, the checklist in particular show which requirements have been met by the user.


                                        Class 05 (The CSS Engine — Box Model & Specificity)

THEORY:
(1)
+----------------------+
|       Margin         |
|  +----------------+  |
|  |    Border      |  |
|  | +------------+ |  |
|  | |  Padding   | |  |
|  | | +--------+ | |  |
|  | | |Content | | |  |
|  | | +--------+ | |  |
|  | +------------+ |  |
|  +----------------+  |
+----------------------+

if we have two adjacent divs both with the margin-bottom: 20px and margin-top: 30px, the space between them will still be 30px, for example, when we play cards there is a type of game play where the lowest number wins, but for css, the highest number wins, logically one will think, if you add both, it ends up with minus 20px from the 30px to have 10px but since the highest number wins, a margin of 30px is given in between.

(2)
Based on CSS specificity hierarchy, the selector that will win from these three: .header nav ul li a / nav a.active / .nav-links a, .header nav ul li a, will win, because its more specific, while they all have a class selector in common, .header nav ul li a, was more specific with 4 element. Saying From .header > go to nav > go to ul > go to li > go to a. So if we have 1 point for each element .header nav ul li a has .header plus 4 point, then the rest have 2 / 1 point.

(3)
Firstly a cascade is a steep, often small waterfall or a series of small falls, now applying that to css, means where there is multiple css rule targeting the same element the browser picks which one to apply by cascade where where the last to come is the first to pick. 
Eg. p {
  color: blue;
}
p {
  color: red;
}

Where cascade is understood means lesser and cleaner code.

.b-paragraph {
color: green;
}

ENGINEERING THINKING:
(1)
From the given problem box sizing is a solution like giving boundary to your code, I remember when working with a class project and I kept having breaks, so while by default there is an actual sizing of content box but when that happens if we have. 
Width = 200px
Padding = 10px, the total width becomes 210px and that is a problem but now that is where specifying border-box comes in. So if we are using a global fix we will have something like 
* {
  box-sizing: border-box;
}
It’s like caging the content within a certain box.

(2)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Test</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body>
    <div class="w-[200px] p-[30px] border-[5px] border-black box-content">
  Content Box
</div>

<div class="w-[200px] p-[30px] border-[5px] border-black box-border mt-4">
  Border Box
</div>
</body>
</html> 
From the tailwind css above, on check the container with the border box remains 200px while the one with the content box increased because other values are added to the content and playing around i was able to know that for the border box to be on the same width with the content box it needs to be 270px width.

                                                        Class 06 (Flexbox Mastery)
THEORY:
(1)
Now let’s imagine we have runners who wanna start a race, the starting lane where they are start from is the flex basis. Then if we are done with the race and then we have 3 race winners, 1,2,3 who are to be given medals. They are all standing on a flex basis, to give 1st a medal he take a step forward that is flex grow (by 1) then moving back to his position is flex shrink (by 1).

(2)
Align-items: stretch won’t work when the parent container is already defined and you and you wanna stretch it, it won’t work when the height is set already because there is noting to stretch eg. 

<div class="flex h-[200px] items-stretch">
  <div class="h-[50px]">Hello</div>
</div>

Because the div container for the child will remains 50px instead of stretching to 200px.

ENGINEERING THINKING:
(1)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Class 6</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>

<body>
    <header class="flex items-center py-4 px-8">
    <div class="flex-1">
        <a href="/" class="font-bold text-xl">
            Logo
        </a>
    </div>
    <nav class="flex justify-center">
        <ul class="flex gap-8">
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Blog</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <div class="flex-1 flex justify-end ml-2">
        <button class="px-6 py-2 border rounded-full">
            Sign In
        </button>
    </div>
</header>
    <main class="px-8 py-10">
        <h1 class="text-4xl font-bold">
            ⚙️ Engineering Thinking
        </h1>
    </main>
</body>
</html>
from the tailwind code above, i started with putting the header inside the  body as a best practice and been semantic, proceeded to putting the logo in a div container, which the div contain was flex by one to take up any space left and then created a nav class to include 5 nav items, with a flex of justify centered to keep it centered  between the logo and the button for the sign in, then gave a gap of 8 between each element within the nav, proceeded to setting the flex box to justify end to place the sign in to the end of the header container and flex by 1 to also take up space left so that way both left and right are covered by the flex by 1 and the nav is perfectly in the middle.
(2)

                                                    Class 07 (CSS Grid & Layout Complexity)
THEORY:
(1)
Firstly Flexbox is one direction and then grid is two direction, meaning flexbox works either row or column but grid works both row and column, so grid is more flexible when working.
Scenario 1: A Chess layout, Scenario 2: A Magazine website, Scenario 3: photo gallery.
When it comes to all these scenarios, flexbox is messy and grid has more control over both the roles and the columns.

(2)
grid-template-areas works by assigning names to section instead of getting confused, because named areas are easy to understand. I remember when working with bento grid for desktop view, I was so confused, with the rows and columns, where by I had issues assigning but now I have a clearer view of how grid-template-areas could have made it easier by naming each section of the grid.

ENGINEERING THINKING:
(1)
(2)


                                               Class 08 (Tailwind CSS Fundamentals)
THEORY:
(1)
The “utility-first" philosophy, is all about having your class within your HTML element, why the Tailwind's creator chose the utility classes over semantic/component-based classes, is because the traditional semantic/component-based classes involves creating class, switching to css file, styling your html element there. 
That traditional method takes time and the “utility-first" philosophy eradicates that, the utility classes enables faster development and remove stress of thinking about class names back to back.

(2)
JIT (Just-In-Time) compiler help tailwind css to work with just what you have in your project, the class you are working in the html element while everything else is ignored. This leads to faster development and small css file which result in faster loading.

PRODCUT THINKING:
(1)
I remember when a course mate of mine will complain about tailwind and says vanilla is better and my usual response is.
Technology is all about evolving, newer things or process will be created and with tailwind CSS everything is made easier, there is consistency in values, no more inventing of different names.
It’s easy to maintainable, you don’t need to be switching tabs, going far from home. It’s also very readable because you can easily spot why you are looking for eg. p-20. All the switching of tabs, reduced performance and tailwind saves you all that stress and time waste.

ENGINEERING THINKING:
(1)


                                            Class 09 (Advanced Tailwind & Responsive Design)
THEORY:
(1)
The break point system is more like saying when a screen attains a certain size, display this. Because imagine working on a grid in row and column, when it reach a mobile screen, it can’t be displayed as row and column but just column.
Eg. <div class="text-sm xl:text-lg">

(2)
In tailwind arbitrary values are custom values, so let’s say width = 123px but tailwind values are w-28, w-32, you can make use of w-[123px], so it’s best used for unique spacing or when a value you need is off.

ENGINEERING  BEST PRACTICE:
(1)
Let: scope - block, hoisting - technically hoisted, reassignment - allowed 
Const: scope - block, hoisting - technically hoisted, reassignment - not allowed 
Var: scope - function scoped, hoisting - hoisted, reassignment - allowed 
So basically let and var can be reassigned, while const and let can only be seen and accessed while used between { }, let and constant are technically hoisted before they need to be defined before they can be accessed, unlike var.

(2)
Technically, these are hoisted, but they are not initialized. Trying to access them before the actual line of declaration throws a ReferenceError. This uninitialized period is known as the Temporal Dead Zone (TDZ).
Temporal Dead Zone is when you are trying to access a let or const variables before declarations, that is why we need to declare first if not, we will get a reference error and Temporal Dead Zone  exists to prevent bugs without Temporal Dead Zone, you won’t get a hold of mistakes early.