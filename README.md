
# Social Network Activity Monitor

## Your Mission
A client needs a robust and scalable solution to monitor social network activities in real-time. The client is interested in the following social networks:

Twitter (https://takehome.io/twitter)
Facebook (https://takehome.io/facebook)
Instagram (https://takehome.io/instagram)

## Requirements:
Microservices Architecture: Implement a microservices architecture using .NET Core. Each social network should have its own microservice.
Asynchronous Communication: Use asynchronous communication between microservices (e.g., HTTP requests).

Resilience and Fault Tolerance: Implement resilience and fault tolerance using Polly or a similar library to handle unpredictable delays and errors from the social networks.
API Gateway: Implement an API Gateway to aggregate responses from the microservices.

Caching: Implement caching to store responses temporarily to reduce load on the social networks.
Logging and Monitoring: Implement logging and monitoring to track the performance and health of the microservices.
Security: Ensure secure communication between microservices and the API Gateway.

## Task:
Microservices: Create three microservices for Twitter, Facebook, and Instagram. Each microservice should:

Fetch data from the respective social network.
Handle random delays and errors gracefully.
Expose an endpoint to return the fetched data.
API Gateway: Create an API Gateway that:

Aggregates responses from the three microservices.
Exposes a single endpoint to return the aggregated data in the format:

Caching: Implement caching in the API Gateway to store responses for a configurable duration.

Resilience: Use Polly or a similar library to implement retry policies, circuit breakers, and fallback mechanisms.

Logging and Monitoring: Implement logging and monitoring using a tool like Serilog.

Security: Ensure secure communication between microservices and the API Gateway using HTTPS and JWT authentication.

## Instructions:
Clone the provided repository.
Implement the solution as described above.
Push your changes to the repository regularly.
Provide documentation on how to run and test the solution locally.
Ensure your code is clean, well-documented, and follows best practices.
