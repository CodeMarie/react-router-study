[<img src="assets/images/su-logo.png" alt="Skills Union Logo" height="80px" />](https://www.skillsunion.com/)

# React Router: Study

Use [DuckDuckGo](https://duckduckgo.com/) or your preferred search engine along with the provided resources to research and answer the [questions below](#questions).

## Required Reading

- [History API](https://medium.com/young-coder/a-simple-introduction-to-the-history-api-in-javascript-85b879d3d87e)
- [HashRouter vs BrowserRouter in React](https://stackoverflow.com/questions/51974369/what-is-the-difference-between-hashrouter-and-browserrouter-in-react)
- [Static and Dynamic Routing](https://blog.bitsrc.io/dynamic-vs-static-routing-in-react-49730baaf3e9)
- [How `<Switch>` works](https://reactrouter.com/web/api/Switch)

## Questions

1. How does browsing history works?

   ```
   A history API allows for back and forward navigation. It allows you to Bookmark state of where you are using the pushState() method and onPopState event counterpart. The pushState()method allos you to add a new item into the history list for the current page. It takes three arguments, data, the page title and the new version of the URL. The onPopState helps to deal with the browser history list when the user returns to the browser. The onPopState event is triggered after every history navigation, it provides your code with the state information you stored earlier with pushState().
   ```

1. What problem does SPA face with the back button?

   ```
   A page may not be loaded into the history list which is when onPopState() can help as it is triggered after every history navigation and this includes history.back(), as well as when the user clicks the browser navigation buttons. For issues with reload, changing the URL can help. You can use the History API to modify the URL, note if the URL is changed but not used for a web app you can get an error that breaks when the user refreshes it (with an ugly 404 error)or similar error. 
   ```

1. What is the difference between `<HashRouter>` and `<BrowserRouter>`

   ```
   HashRouter uses a hash symbol in the URL, from this point in the URL all subsequent URL path content is ignored in the server request. It is seen with snaller client side applications where the use of hashes foesnt effect the server requests. 

   The Browser Router does add the hash to the URL it is more commonly found on larger applications with larger backend requirements. 
   ```

1. What is the difference between routing with `<Switch>` and without?

   ```
   Switch will render the first child of redirect or route that matches its location. 
   Using switch will render a route exclusively. This differs to just using route which for every <Route> matches the location renders inclusively.
   ```

### Response Guidelines

Please follow these guidelines as you answers these questions:

- Cite any relevant sources consulted during your research
- Do not reply using direct quotes from the source material
- Provide an answer using your own words and voice
