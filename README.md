# flask-ml-api
## Getting Started

### 1. API Implementation
- Open `app.py` and implement the required endpoints and logic
- Ensure your code follows PEP 8 style guidelines
- Add any necessary dependencies to `requirements.txt`

### 2. Building the Docker Image
```
docker build -t <image-name>:<version> .
```

### 3. Running the Container
```
docker run -p 50505:50505 <image-name>:<version>
```

### 4. Testing Your API
Use curl or any API testing tool to make requests to your endpoints. For example:
```
curl http://localhost:50505
```

## Evaluation Criteria
Your submission will be evaluated based on:
- Correctness of API implementation, including the ML inference endpoint
- Code quality, organization, and adherence to best practices
- Proper use of Docker
- API functionality and adherence to RESTful principles
- Error handling and input validation

## Bonus Features
While not required, implementing any of the following will be viewed favorably:
- JWT authentication
- Comprehensive logging
- API documentation (e.g., using Swagger/OpenAPI)
- Unit tests
- Data validation and sanitization
- Rate limiting
- Caching mechanisms

## Submission and Review Process
