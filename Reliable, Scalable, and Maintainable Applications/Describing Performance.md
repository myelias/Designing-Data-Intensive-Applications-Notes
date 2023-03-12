**_Throughput_** - the number of records we can process per second or the total time
it takes to run a job on a dataset of a certain size.

p95, p99, and p999 are the response thresholds at which 95%, 99%, or 99.9% of
requests are faster than a particular threshold.

When several backend calls are needed to serve a request, it takes just a single
slow backend request to slow down the entire end-user request. Ex:

<img width="439" alt="image" src="https://user-images.githubusercontent.com/72317416/224521448-373119bb-7c77-4b2a-ac8b-9e933af1815e.png">


Scaling up (_vertical scaling_) describes moving to a more powerful machine while
scaling out (_horizontal scaling_) describes distributing the loud across multiple
smaller machines

Some systems are **_elastic_**, which menus they can automatically add computing
resources when they detect a load increase.
