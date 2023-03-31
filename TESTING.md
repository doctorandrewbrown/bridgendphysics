## **Bugs**


* Text overflow was encountered with the h1 and h2 headings in the hero section, when initial testing for small devices. This was due to the above elements not being placed in their own columns. Placing the h1, h2 elements (and cta button) in their own columns allowed responsivity. Solving this bug demonstrated the importance of following bootstrap format to get built-in responsiveness.


* The initial web-page layout used a single bootstrap container-fluid for the whole page. This caused an issue with the contact section which was required to be full-width. The bug was that bootstrap applied unwanted right and left margins. The bug was solved by enclosing the contact section in it's own container-fluid. 

* The rendered site showed streching of some images. This was solved by targeting the css rule object-fit:cover to the relevant img tags.


## **Testing**

Testing was conducted throughout development. Incremental changes were tested by opening the partly complete site in the chrome browser and "eye-balling" results. Incremental changes were initially tested for responsiveness via chrome inspector dev tools. The chrome inspector was also used to identify layout problems and testing small style changes before amending code. 

Performance testing of the deployed site was via Google Lighthouse. This identified dependencies that were affecting load times. One such dependency was a minified fontawsome.css file I had initially included in my local directory. This
was replaced by using a modern fontawsome kit approach instead, bringing a small improvement in load speed.
Lighthouse testing also flagged large image sizes slowing load time.

HTML and CSS checking used respectively, validator.w3.org and jigsaw.w3.org.

The HTML test tool flagged two instaces of the h1 element in my code where one is recommended for a single article (ie the web page). This was corrected in the final code. A missing DOCTYPE tag was also flagged and this was added to comply with current practice.

Browser testing was conducted in Chrome and Firefox. Responsivity was tested for a range of device sizes ie small, medium and large in both browsers. For testing small and medium devices, the iPhone SE and the iPad mini were selected. Large device testing was via a physical laptop.


