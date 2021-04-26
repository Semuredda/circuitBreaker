# circuitBreaker
In the initial package there are two microservices that shows how to use Hysterix for circuit breaker pattern.
The bookStore (circuit-breaker-bookservice) exposes a GET endpoint which will return a String.
The reading (circuit-breaker-reading) will consume the bookstore service via restTemplate and uses Hysterix for circuit breaker pattern for fallback.
The full example of this circuit braker can be found here: https://spring.io/guides/gs/circuit-breaker/#initial
