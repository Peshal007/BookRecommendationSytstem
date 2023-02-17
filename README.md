Book-Recommendation-System
A Book Recommendation System which recommends the users a selection of books based on their interests. It also has a separate page for the list of all books.
1. Data Cleaning and Pre-Processing
The dataset consists of three tables; Books, Users, and Ratings. Data from all three tables are cleaned and preprocessed separately.


2. Algorithms Implemented:
2.1 Popularity Based Recommendation :
Popular in the Whole Collection
We have sorted the dataset according to the total ratings each of the books have received in non-increasing order and then recommended top 50 books.

2.2 Content Based Recommendation
This system recommends books by calculating similarities in Book Titles. For this, TF-IDF feature vectors were created for unigrams and bigrams of Book-Titles; only those books' data has been considered which are having at least 50 ratings.

3. Libraries Used:
ipython-notebook - Python Text Editor
sklearn - Machine learning library
numpy, scipy- number python library
pandas - data handling library
4. Frontend
HTML, CSS & Javascript was used for the frontend of the application.
