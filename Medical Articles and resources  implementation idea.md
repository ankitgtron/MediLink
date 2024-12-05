# Medical Articles and Resources Feature. 

# 1. Backend (Spring Boot):
## Entity:
Define an Article entity to represent articles in the database with fields:
- id (Unique identifier)
- title (Title of the article)
- content (Full content of the article)
- author (Author's name)
- specialty (Medical specialty of the article)
- publishedDate (Publication date)

## Repository:
Use JpaRepository to handle database operations.
- Add a custom method: List<Article> findBySpecialty(String specialty);

## Service Layer:
Implement the following methods in the service layer:
- addArticle(Article article) – To save a new article.
- getAllArticles() – To fetch all articles.
- getArticlesBySpecialty(String specialty) – To fetch articles filtered by medical specialty.

## Controller Layer:
Expose the following REST endpoints:
- POST /articles – Add a new article to the database.
- GET /articles – Fetch all articles.
- GET /articles?specialty=xyz – Fetch articles filtered by specialty.

# 2. Frontend:
## Articles Section:
- Create an Articles page to display all articles fetched from the backend.
- Add a filter dropdown to filter articles based on their medical specialty.

## UI:
- Display the article’s title, author, date, and a brief snippet of the content.
- Provide a "Read More" button/link for viewing the full article.

#3. Database Design:
- Create a database table named articles with the following fields:
- id (Primary Key)
- title (VARCHAR)
- content (TEXT)
- author (VARCHAR)
- specialty (VARCHAR)
- published_date (DATE)

## Example Workflow:
Backend Operations:
- Add an article using the POST /articles endpoint with data like:

- json

```
{
  "title": "Understanding Diabetes",
  "content": "Diabetes is a chronic condition...",
  "author": "Dr. John Doe",
  "specialty": "Endocrinology",
  "publishedDate": "2024-12-01"
}
```

- Fetch all articles using GET /articles.
- Filter articles by specialty using GET /articles?specialty=Endocrinology.

## Frontend Workflow:
- Display the list of articles in a table or grid view.
- Add a dropdown to filter articles by specialties like "Cardiology," "Neurology," etc.
- Show a preview of the article and a "Read More" button to expand the full content.
