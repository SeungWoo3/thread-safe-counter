# thread-safe-counter

#### - Computer Architecture and Real-Time Operating system
#### - Project #2 (Thread-Safety by Semaphore)
#### - OS environment : Ubuntu Linux 18.04


## Compare Performance (semaphore vs mutex)
![hw2](https://user-images.githubusercontent.com/78201406/121796113-a9e97a00-cc51-11eb-9083-8911375b3848.png)
###  Semaphore (Left)
#### - real : 6.227s
#### - user : 2.903s
#### - sys : 6.421s
### Mutex (Right)
#### - real : 0.196s
#### - user : 0.297s
#### - sys : 0.076s




## result
####  Mutex is faster than semaphore.


## analysis
####  In general, it is known that semaphore is much faster than mutex. That's because semaphore allows entering a critical section simultaneously. But in this case, there is only one resource. This is the reason mutex's execution is faster.
