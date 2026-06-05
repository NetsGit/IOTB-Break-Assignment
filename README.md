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

(3)

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

PRODUCT THINKING:
