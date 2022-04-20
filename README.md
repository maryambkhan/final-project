# final-project

## Team

- Maha
- Maryam

## ABK Photos

- Photography Website

### Tasks

- Mockup [maryam--maha]
- Wireframe [maha]
- Taskflow [maryam]
- User story [maryam]
- Flow Chart [maha]
- Lean Canvas [maryam]
- Landing Page [maha]
    - Nav-bar
- About Page [maryam]
   - Article
- Gallery Page [maha,maryam]
   - Images
- Contact Page [maryam]
   - Form

### Plan

- Landing Page
  - HeroSection Image
  - Nav-Bar 
  - Footer 
- About Page
  - Nav-bar 
  - Image
  - Article
  - Footer
- Contact Page
  - Nav-bar
  - Image
  - Form 
  - Footer
- Gallery
  - Nav-bar
  - Images
    - Instagram API/Storyblok Api/Strapy API
  - Footer

### Journel Entries

- We are done with all the documentation for final project.
- I created Nuxt2 project and added google image and tailwindcss.
- Then just to make sure everything is working i added nav-bar component but i could not see it. First thing i did was check
  nuxtconfig and make sure everything was okay.
- Created a rough structure of navigation bar
- Next i an going make this nav-bar mobile version.
- Followed a youtube video for mobile nav-bar it was reall good and i got it done the way i wanted yay!.
- I have started working on about page added navbar footer and content so far so good.
- I tweaked the design a little i  did not like the other one but last decision is clients.
- I have started working on contact page added form and did some design have to do somer design and then next is adding funcnailty to it.
- So i just made form backend work and tested it via sending it to myself working good. But i did not liked the 
  result you get at the end i wanted it to be something nice so i tried some other site and it did not worked so i went back to formspree.
- I have been working on strapi api for gallery page  i liked it. I can see why and when we need this. 
- I created a new nuxt2 project to learn strapi on. I did not wanted to messup our final project. I found a realy great video which i followed
   i set up everything  and then i ran into problem 
- We solved everything as group and i think it was really great working in group.
- After setup we had to fetch the image we could not figured it out then asked for help from tony and he helped us
       `<img :src="`http://localhost:1337${gallery.attributes.image.data.attributes.url}`" :alt="gallery"/>`


### Problems

- I just had this silly problem where i was not able to see nav-bar on html page. All of sudden idea struck me if
  inspect the page and see if it is rendring on page or not. Well it was and then i went back to VS and saw nav-bar
  color was white.
- Strapi Issue--> which was becouse that video was old and they changed few things like i had to do this `localhost:1337/api/menus`
   to get the data.
- And i after that i was having problem fetching it on html page becouse i was missing something ` httpEndpoint: 'http://localhost:1337/graphql'`.
- [problem](https://stackoverflow.com/questions/56448815/eperm-operation-not-permitted-error-when-building-nuxt-app)

### Resurces

- [Nuxt2](https://nuxtjs.org/docs/get-started/installation)
- [Tailwindcss](https://tailwindcss.com/docs/guides/nuxtjs)
- [Google Image](https://image.nuxtjs.org/getting-started/installation)
- [Font Awesome icons](https://stackoverflow.com/questions/67866467/how-to-add-font-awesome-to-vue-and-nuxt-js-project)
- [Font Awesome solids and brands](https://levelup.gitconnected.com/nuxt-js-and-fontawesome-a-simple-walk-through-78f35605d841)
- [Adam Wathan](https://www.youtube.com/watch?v=ZT5vwF6Ooig)
- [Debbie o'Brien](https://www.youtube.com/watch?v=Rj1qYm5zctE&t=2441s)
- [nuxt module](https://github.com/nuxt-community/apollo-module)
- [strapi](https://docs.strapi.io/developer-docs/latest/developer-resources/database-apis-reference/graphql-api.html#pagination-by-page)

### Attributions

- [Adrieana Blazin](https://blazinphoto.com/)
