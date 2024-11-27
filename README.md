## CPNT-262-NextJs-Pokemon-Lab

### Bugs which are fixed

1. The links in layout.js are missing the href attribute.
   Fix: Update the navigation to correctly use the Next.js  Link component by adding the appropriate href attribute.

2. Incorrect API URL: The Pokémon list was failing due to an incorrect API URL.
   Infinite Loop in useEffect: The useEffect dependency was causing an infinite loop.
   Missing Error Handling: There was no error handling for failed API requests.

3. Update the href to use Next.js dynamic routing syntax as /pokemon/[id] instead of pokemon?id=1.

4. Add a navigation link to the Home page using the Next.js Link component on the About page.

5. Update the Pokémon link to use template literals with the id, add error handling for invalid IDs, and use the    correct property for Pokémon images.


### What you learned during the debugging process.

- Small issues, like incorrect parameters or missing error handling, can significantly affect functionality.

- Proper error handling is crucial for building resilient applications that can gracefully handle unexpected situations.

-  Ensuring that the correct data properties are accessed and used correctly is essential for maintaining accurate output and user experience.