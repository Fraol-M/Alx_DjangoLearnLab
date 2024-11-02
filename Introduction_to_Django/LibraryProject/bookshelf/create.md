# Create Operation

## Command
To create a `Book` instance, run:

```python
from your_app_name.models import Book
book = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
print(book)
