# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ops/ms
# Warmup Iteration   2: 11.760 ops/ms
# Warmup Iteration   3: 12.222 ops/ms
Iteration   1: 12.416 ops/ms
Iteration   2: 12.575 ops/ms
Iteration   3: 12.552 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.514 ±(99.9%) 1.566 ops/ms [Average]
  (min, avg, max) = (12.416, 12.514, 12.575), stdev = 0.086
  CI (99.9%): [10.948, 14.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.270 ops/ms
# Warmup Iteration   2: 13.239 ops/ms
# Warmup Iteration   3: 13.285 ops/ms
Iteration   1: 12.990 ops/ms
Iteration   2: 13.268 ops/ms
Iteration   3: 13.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.135 ±(99.9%) 2.542 ops/ms [Average]
  (min, avg, max) = (12.990, 13.135, 13.268), stdev = 0.139
  CI (99.9%): [10.593, 15.676] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.612 ops/ms
# Warmup Iteration   2: 12.541 ops/ms
# Warmup Iteration   3: 12.637 ops/ms
Iteration   1: 12.760 ops/ms
Iteration   2: 12.791 ops/ms
Iteration   3: 13.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.876 ±(99.9%) 3.204 ops/ms [Average]
  (min, avg, max) = (12.760, 12.876, 13.078), stdev = 0.176
  CI (99.9%): [9.672, 16.081] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.541 ops/ms
# Warmup Iteration   2: 10.325 ops/ms
# Warmup Iteration   3: 10.309 ops/ms
Iteration   1: 10.352 ops/ms
Iteration   2: 10.430 ops/ms
Iteration   3: 10.489 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.424 ±(99.9%) 1.256 ops/ms [Average]
  (min, avg, max) = (10.352, 10.424, 10.489), stdev = 0.069
  CI (99.9%): [9.168, 11.680] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.004 ms/op
Iteration   1: 2.524 ±(99.9%) 0.003 ms/op
Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
Iteration   3: 2.467 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.523 ms/op [Average]
  (min, avg, max) = (2.467, 2.496, 2.524), stdev = 0.029
  CI (99.9%): [1.973, 3.020] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.414 ±(99.9%) 0.004 ms/op
Iteration   2: 2.399 ±(99.9%) 0.003 ms/op
Iteration   3: 2.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.417 ±(99.9%) 0.342 ms/op [Average]
  (min, avg, max) = (2.399, 2.417, 2.437), stdev = 0.019
  CI (99.9%): [2.075, 2.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.010 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.004 ms/op
Iteration   1: 2.506 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.003 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.491, 2.499, 2.506), stdev = 0.008
  CI (99.9%): [2.360, 2.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.004 ms/op
Iteration   1: 3.032 ±(99.9%) 0.006 ms/op
Iteration   2: 3.028 ±(99.9%) 0.006 ms/op
Iteration   3: 3.020 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.026 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (3.020, 3.026, 3.032), stdev = 0.006
  CI (99.9%): [2.917, 3.136] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.042 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.519 ±(99.9%) 0.006 ms/op
Iteration   1: 2.460 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   2.519 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.109 ms/op
                 createUser·p0.99:   3.723 ms/op
                 createUser·p0.999:  7.080 ms/op
                 createUser·p0.9999: 14.025 ms/op
                 createUser·p1.00:   14.893 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.006 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.764 ms/op
                 createUser·p0.999:  6.650 ms/op
                 createUser·p0.9999: 11.783 ms/op
                 createUser·p1.00:   12.009 ms/op

Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.556 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  9.166 ms/op
                 createUser·p0.9999: 10.760 ms/op
                 createUser·p1.00:   11.354 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385803
  mean =      2.486 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 186912 
    [ 2.500,  3.750) = 193987 
    [ 3.750,  5.000) = 3876 
    [ 5.000,  6.250) = 461 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 99 
    [10.000, 11.250) = 145 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 73 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.891 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     13.353 ms/op
     p(99.9990) =     14.448 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.741 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.455 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.671 ms/op
                 existUser·p0.999:  7.108 ms/op
                 existUser·p0.9999: 14.482 ms/op
                 existUser·p1.00:   14.696 ms/op

Iteration   2: 2.451 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.979 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.616 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 12.369 ms/op
                 existUser·p1.00:   13.353 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.490 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.846 ms/op
                 existUser·p0.999:  7.817 ms/op
                 existUser·p0.9999: 13.631 ms/op
                 existUser·p1.00:   14.467 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392108
  mean =      2.446 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 195171 
    [ 2.500,  3.750) = 193143 
    [ 3.750,  5.000) = 2835 
    [ 5.000,  6.250) = 443 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 81 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.970 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      7.810 ms/op
     p(99.9900) =     13.763 ms/op
     p(99.9990) =     14.571 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.060 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.546 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.005 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.756 ms/op
                 getUser·p0.999:  7.243 ms/op
                 getUser·p0.9999: 13.717 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.513 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.871 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.026 ms/op
                 getUser·p0.999:  9.073 ms/op
                 getUser·p0.9999: 15.111 ms/op
                 getUser·p1.00:   16.056 ms/op

Iteration   3: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.039 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  7.310 ms/op
                 getUser·p0.9999: 10.227 ms/op
                 getUser·p1.00:   10.551 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384221
  mean =      2.496 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 189401 
    [ 2.500,  3.750) = 189918 
    [ 3.750,  5.000) = 3830 
    [ 5.000,  6.250) = 542 
    [ 6.250,  7.500) = 75 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 56 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.883 ms/op
     p(99.9000) =      7.264 ms/op
     p(99.9900) =     13.887 ms/op
     p(99.9990) =     15.968 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.724 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.000 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.969 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.509 ms/op
                 listUser·p0.9999: 10.612 ms/op
                 listUser·p1.00:   11.289 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.723 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  9.241 ms/op
                 listUser·p0.9999: 10.979 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.652 ms/op
                 listUser·p0.999:  10.338 ms/op
                 listUser·p0.9999: 12.819 ms/op
                 listUser·p1.00:   14.303 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318879
  mean =      3.008 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 135 
    [ 1.250,  2.500) = 94127 
    [ 2.500,  3.750) = 183635 
    [ 3.750,  5.000) = 32773 
    [ 5.000,  6.250) = 6722 
    [ 6.250,  7.500) = 828 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 238 
    [10.000, 11.250) = 174 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =      9.519 ms/op
     p(99.9900) =     11.897 ms/op
     p(99.9990) =     13.186 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.514 ± 1.566  ops/ms
ClientPb.existUser                       thrpt       3  13.135 ± 2.542  ops/ms
ClientPb.getUser                         thrpt       3  12.876 ± 3.204  ops/ms
ClientPb.listUser                        thrpt       3  10.424 ± 1.256  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.523   ms/op
ClientPb.existUser                        avgt       3   2.417 ± 0.342   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.139   ms/op
ClientPb.listUser                         avgt       3   3.026 ± 0.110   ms/op
ClientPb.createUser                     sample  385803   2.486 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.556           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.556           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.353           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.893           ms/op
ClientPb.existUser                      sample  392108   2.446 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.810           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.763           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.696           ms/op
ClientPb.getUser                        sample  384221   2.496 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.754           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.264           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.887           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.056           ms/op
ClientPb.listUser                       sample  318879   3.008 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.723           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.519           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.897           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.303           ms/op
