# CRUD Operations on Book model

## Create
```python
book = Book.objects.create(title="1984", author="George Orwell", publication_year=1949)
# Expected output: <Book: 1984>
