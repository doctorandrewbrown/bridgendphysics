# **Bridgend Physics and Maths Website**  
https://doctorandrewbrown.github.io/bridgendphysics/

This website has been developed for a fictional A level and GCSE physics and maths private tutor service. 


## UX Design

UX design was guided by the "five planes of UX" methodology. The five planes as they relate to the current project are detailed below.  

### Strategy

This project is considered worthwhile because an unmet demand for local private tutoring in physics and maths has been identified by the site-owner. Demand for such a service has been established by interviewing potential clients and researching competition in the targeted market. Site users are envisaged to be those seeking local in-person tuition in a given geographical location. This website will allow site users to find and contact a suitable local tutor (i.e. the site-owner) in order to arrange the tuition they need. The site is intended to provide value to both users and the site owner. Value is provided to users by assisting them to meet their tutoring needs, and to the site owner in terms of the business opportunity created by connecting with clients. 

To realize the above strategy, a custom personal website was chosen instead of relying solely on social media for instance, as a website gives more flexibility and scope for branding the new service. A website can also be optimized for local SEO and building authority in the business niche by providing relevant content via a blog and articles. The website must be responsive to cater for the range of user devices that will be available to the intended users, especially mobile. 

### Scope

The scope for this project was restricted to what was needed for a MVP and is determined by considering tasks and information needed to serve the project strategy. 

#### Tasks  

Users need to:


* Contact site owner

#### Information

Users need to:

* Find details of tutors qualifications
* Find details of subjects covered 
* View social proof of service ie. user testimonials
* Find details of features of the service

Blogging functionality is not included in the scope at this (MVP) stage but could easily be added in future. Article pages (HTML) could easily be added to the MVP at a future date. In this way, the current MVP provides immediate value and potential for future extensibility to serve the business strategy. 


### Structure

Given the limited amount of content required to build the MVP, a single page website structure broken into sections was considered appropriate. Navigation between sections is via a sticky navbar at the top of the page.

Page sections

* Navigation

* Header with CTA - This is a banner section announcing the business title and a tagline summing up the essentials of the service. This section also includes a CTA button linking to the contact form. 
* Testimonials - Social proof in the form of testimonials from happy clients was considered to be crucial content for this type of business. Therefore this section was placed near the page top.
* About - This section gives information on the qualifications and experience of the site-owner, geographical area covered and subjects offered 
* Key features - one-to-one, online, hybrid. This section uses the design convention of icons to highlight features. 
* Contact details information.This section doubles as the footer
  
### Skeleton



### Surface

## **Bugs**

Bugs encountered are detailed in this section.

* Text overflow was encountered with the h1 and h2 headings in the hero section, when initial testing for small devices. This was due to the above elements not being placed in their own columns. Placing the h1, h2 elements (and cta button) in their own columns allowed responsivity. Solving this bug demonstrated the importance of following bootstrap format to get built-in responsiveness.

## **Testing**

Testing was conducted throughout development. Incremental changes were tested by opening the partly complete site in the chrome browser and "eye-balling" results. Incremental changes were initially tested for responsiveness via chrome dev tools. The chrome inspector was also used to identify layout problems and testing small style changes before amending code. 

Performance testing of the deployed site was via Google Lighthouse. This identified dependencies that were affecting load times. One such dependency was a minified fontawsome.css file I had initially included in my local directory. This
was replaced by using a modern fontawsome kit approach instead, bringing a small improvement in load speed.

HTML and CSS checking used respectively, validator.w3.org and jigsaw.w3.org.

The HTML test tool flagged two instaces of the h1 element in my code where one is recommended for a single article ie the web page. This was corrected in the final code. A missing DOCTYPE tag was also flagged and this was added to comply with current practice.


## **Deployment**

Deployment was via github-pages at https://doctorandrewbrown.github.io/bridgendphysics/

## **Credits**

Pexels for images.