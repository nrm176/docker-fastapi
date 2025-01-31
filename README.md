### structure
```plaintext
fastapi-docker/
│── app/
│   ├── main.py  <-- Contains FastAPI instance
│── Dockerfile
│── requirements.txt
│── docker-compose.yml
```

### dockerfile
```aiignore
CMD ["uvicorn", "app.main:app", "--host", "0.0.0.0", "--port", "8200"]

```