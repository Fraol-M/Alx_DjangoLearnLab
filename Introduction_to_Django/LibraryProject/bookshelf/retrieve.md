# Retrieve Operation

## Command
To retrieve the `Book` instance:

```python
retrieved_book = Book.objects.get(id=book.id)
print(retrieved_book.title, retrieved_book.author, retrieved_book.publication_year)
