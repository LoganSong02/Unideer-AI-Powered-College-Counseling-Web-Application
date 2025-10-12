# Unideer-AI-Powered-College-Counseling-Web-Application (unideer.cn)
- Developed a full-stack university application platform using Java, ReactJS, and MySQL, supporting school search, application tracking, and school list management.
- Designed relational schemas for entities like users and universities, and built backend microservices with Spring Boot and Maven.
- Implemented Spring Security with JWT authentication to enable secure, role-based access for both guests and registered users.
- Integrated OpenAI API and LangChain to generate personalized school recommendations from user preferences, and built a chatbot to assist with university research and application planning.
- Used RabbitMQ to decouple services and process school recommendations asynchronously, achieving 75+ QPS at peak load.
- Built a Redis-based rate limiter to monitor per-user API usage, reducing third-party throttling and boosting availability to 99.9%.
