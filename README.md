This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

To open the project, open Command Prompt on your local machine, and run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser. (This should open automatically once npm start has finished running)

## Project Overview
### Main Page (Library)
The website you will be using is a book tracking website. The main page is where you can view all books in your library. The books are organized according to assignment to one of three possible "shelves". 
- "Currently Reading" 
- "Want to Read" 
- "Read". 

To move a book from shelf to shelf, select the arrow selector in the right bottom corner of the book, and pick the shelf you want to assign that book to. 

### Search Page
You can also search for books to add to your library. To reach the search page, click on the green plus sign at the right bottom corner of the page. Then simply type in a search term you wish to filter the books by. The backend API uses a fixed set of cached search results and is limited to a particular set of search terms, which can be found in [SEARCH_TERMS.md](https://github.com/udacity/reactnd-project-myreads-starter/blob/master/SEARCH_TERMS.md). That list of terms are the only terms that will work with the backend. 

Once you've found a book you want to add to your library, simply select the green arrow on the bottom right hand corner of each book to assign it to a shelf in your library. If a book is already assigned to a shelf in your library, it will highlight the shelf it is assigned to in the selector by default. 

To return to the Library, click the arrow directly to the left of the search bar. 

### Contributing
This project was created with React. The [Create React App](https://github.com/facebook/create-react-app) was used to build the project with the Udacity provided [starter code](https://github.com/udacity/reactnd-project-myreads-starter).

For help to scale and understand the project, the following walk-through was used:<br> https://www.youtube.com/watch?v=i6L2jLHV9j8

Due to the scale of the project, there is contributing help from the patient and kind-hearted Udacity coaches. 

