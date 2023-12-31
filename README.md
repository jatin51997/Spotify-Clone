# Spotify 2.0

1. Technologies Used:

    - Next.js 12
    - Tailwind CSS
    - Spotify API
    - NextAuth
    - Recoil

2. Project Overview:

    - It is a fully functional and responsive clone of Spotify with features like search, play, pause, and change songs.
    - It has a complete search functinality with data being fetched from Spotify API.
    - Added User authentication using NextAuth.js, which provides complete authentication for next.js
    - Implemented many concepts of react components, hooks, lifecycle methods, props, and added global state management using recoil.
    - Added a custom player with controls like play, pause, and adjust the volume of songs.

    - One Limitation of spotify API is that it only works for spotify users having premium memberships.

3. Project Screenshots:

- Large Screen View
![](project-screenshot1.png)

- Medium Screen View
![](project-screenshot3.png)

- Small Screen View
![](project-screenshot2.png)



4. Imp Links:

    - https://tailwindcss.com/docs/guides/nextjs

    - https://nextjs.org/

    - Read about dynamic "built-in" routing in next.js

    - In next.js, any file inside the pages folder is a website page.

    - In next.js any file inside the api folder is all the back-end code.

    - Read about "built-in" server in next.js
    
    - Image component in next.js
    
        - https://nextjs.org/docs/basic-features/image-optimization
        
        - https://nextjs.org/docs/api-reference/next/image
    
    - postion: fixed; in css  

        - https://developer.mozilla.org/en-US/docs/Web/CSS/position

    - z-index in css 

        - https://developer.mozilla.org/en-US/docs/Web/CSS/z-index
    
    - add icons using heroicons:

        - https://heroicons.com/

        - https://github.com/tailwindlabs/heroicons

    - add icons using React Icons

        - https://react-icons.github.io/react-icons/
    
    - Creating your own utility custom class in TailwindCSS

        1. create a folder named "styles" and add a file called "globals.css" to it

        2. import this globals.css file into the _app.js file

        3. create your utility classes in globals.css

    - Breakpoints in tailwindcss for adding responsiveness:

        - https://tailwindcss.com/docs/breakpoints

        - Always remember, default styling in tailwindcss is always mobile responsive first, and then breakpoints are added to make it 
        responsive for bigger screens. 💥💥💥💥💥
    
    - @tailwindcss/forms:

        - https://github.com/tailwindlabs/tailwindcss-forms
    
    - tailwind-scrollbar:

        - https://www.npmjs.com/package/tailwind-scrollbar
    
    - tailwind-scrollbar-hide:

        - https://www.npmjs.com/package/tailwind-scrollbar-hide
    
    - useState() hook in react:

        - https://reactjs.org/docs/hooks-state.html
    
    - custom google fonts:

        - https://fonts.google.com/

    - Making a grid using tailwindcss

    - NextAuth authentication:

        - https://next-auth.js.org/

        - Getting Started:

            - https://next-auth.js.org/getting-started/upgrade-v4

            - https://next-auth.js.org/getting-started/example

        - NextAuth authentication for spotify api:

            - https://next-auth.js.org/providers/spotify

        - We need authentication because we need an access token and also check if the access token has expired

        - If the access token has expired, then we need to refresh the expired access token with a valid refresh token.

        - Having a valid access token, authenticates the use login, without a valid access token the user cannot access the 
        website and it will always redirect that un-authenticated user to the login/signin page.

        - Once the user login/signup using their spotify account, the user is authenitcated and gets a valid access token.

    - What is .env.local file in react/next.js projects?

    - useSession() hook in NextAuth:

    - creating custom login/signin page in NextAuth:

        - https://next-auth.js.org/configuration/pages
    
    - What are callbacks in NextAuth:

        - https://next-auth.js.org/configuration/callbacks

        - JWT Callback:

            - https://next-auth.js.org/configuration/callbacks#jwt-callback
        
        - Session Callback:
            
            - https://next-auth.js.org/configuration/callbacks#session-callback
        
        - Refresh Access Token NextAuth: (💥💥💥💥💥)
            
            - https://next-auth.js.org/tutorials/refresh-token-rotation
        
    - useRouter() hook in next.js:

        - https://nextjs.org/docs/api-reference/next/router
    
    - useEffect() hook in react:

        - https://reactjs.org/docs/hooks-effect.html
    
   - react-loader-spinner:

        - https://github.com/mhnpd/react-loader-spinner

        - https://www.npmjs.com/package/react-loader-spinner

        - https://mhnpd.github.io/react-loader-spinner/

     - Group-hover in tailwind css   
    
        - https://tailwindcss.com/docs/hover-focus-and-other-states#group-hover

        - If you need to style a child element when hovering over a specific parent element, add the group class to the parent element and add the group-hover: prefix to the utility on the child element.
    
     - Recoil --> Global State Management

            - https://recoiljs.org/

            - Global state management using recoil.js

            - npm install recoil

            - https://recoiljs.org/docs/introduction/getting-started/

    - Recoil Atoms
            
            - https://recoiljs.org/docs/introduction/getting-started#atom
            
            - https://recoiljs.org/docs/basic-tutorial/atoms
    
    - Headless UI:

        - https://github.com/tailwindlabs/headlessui

        - https://github.com/tailwindlabs/headlessui/tree/main/packages/%40headlessui-react

        - https://headlessui.dev/
    
    - SignOut functionality in NextAuth:

        - https://next-auth.js.org/getting-started/client#signout
    
    - react-spotify-web-playback:

        - adding custom player to the spotify clone

        - https://github.com/gilbarbara/react-spotify-web-playback


