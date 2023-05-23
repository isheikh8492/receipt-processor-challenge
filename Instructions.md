# Receipt Processor Service

## Steps to Run the Application

1. Clone this repository to your local machine:

```
git clone https://github.com/isheikh8492/receipt-processor-challenge.git
```
2. Navigate to the project directory:

```
cd receipt-processor-challenge
```
3. Build the Docker image. This might take a few minutes.

```
docker build -t receipt_api .
```

4. After the Docker image has built successfully, run the Docker container:

```
docker run -p 8080:8080 receipt_api
```


This will start the application, and it will be accessible at http://localhost:8080.
