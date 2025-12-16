# springboot-resilience4j

Alternate to hytrix
Resilience4j features and modules
-Circuit Breakers (Fault tolerance)
- Rate Limmiter (Block too frequent requests)
-Time Limiter (set a time limit when calling remote operation)
- Retry mechanism (Automaticlly retry a failed remote operation)
- Bulkhead (Avois toomany concurrent request)
- Cache(Store results of costly remote operations)

can check the status closed- open - hallf open  in the actuator metrics
