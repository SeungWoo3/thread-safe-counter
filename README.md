# thread-safe-counter

#### - Computer Architecture and Real-Time Operating system
#### - Project #2 (Thread-Safety by Semaphore)
#### - OS environment : Ubuntu Linux 18.04

## * Compare Performance (mutex vs semaphore)

### - Mutex

### - Semaphore

## * result
####  Mutex is faster than semaphore

## * analysis
####  In general, it is known that semaphore is much faster than mutex. That's because semaphore allows entering a critical section simultaneously. But in this case, there is only one resource. This is the reason mutex's execution is faster.
