# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 6.078 ops/ms
# Warmup Iteration   3: 8.266 ops/ms
Iteration   1: 9.625 ops/ms
Iteration   2: 9.314 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.592 ±(99.9%) 4.796 ops/ms [Average]
  (min, avg, max) = (9.314, 9.592, 9.837), stdev = 0.263
  CI (99.9%): [4.796, 14.388] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ops/ms
# Warmup Iteration   2: 8.931 ops/ms
# Warmup Iteration   3: 9.133 ops/ms
Iteration   1: 9.904 ops/ms
Iteration   2: 9.635 ops/ms
Iteration   3: 9.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.765 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (9.635, 9.765, 9.904), stdev = 0.135
  CI (99.9%): [7.306, 12.224] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.945 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.528 ops/ms
Iteration   2: 9.577 ops/ms
Iteration   3: 9.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.489 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (9.361, 9.489, 9.577), stdev = 0.113
  CI (99.9%): [7.424, 11.553] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.922 ops/ms
# Warmup Iteration   2: 7.425 ops/ms
# Warmup Iteration   3: 7.928 ops/ms
Iteration   1: 8.207 ops/ms
Iteration   2: 8.169 ops/ms
Iteration   3: 8.483 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.286 ±(99.9%) 3.132 ops/ms [Average]
  (min, avg, max) = (8.169, 8.286, 8.483), stdev = 0.172
  CI (99.9%): [5.154, 11.418] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.636 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.779 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.528 ±(99.9%) 0.006 ms/op
Iteration   1: 3.527 ±(99.9%) 0.008 ms/op
Iteration   2: 3.438 ±(99.9%) 0.009 ms/op
Iteration   3: 3.292 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.419 ±(99.9%) 2.165 ms/op [Average]
  (min, avg, max) = (3.292, 3.419, 3.527), stdev = 0.119
  CI (99.9%): [1.253, 5.584] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.579 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.605 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.003 ms/op
Iteration   1: 3.268 ±(99.9%) 0.006 ms/op
Iteration   2: 3.241 ±(99.9%) 0.011 ms/op
Iteration   3: 3.203 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.237 ±(99.9%) 0.596 ms/op [Average]
  (min, avg, max) = (3.203, 3.237, 3.268), stdev = 0.033
  CI (99.9%): [2.641, 3.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.600 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.524 ±(99.9%) 0.006 ms/op
Iteration   1: 3.503 ±(99.9%) 0.006 ms/op
Iteration   2: 3.461 ±(99.9%) 0.005 ms/op
Iteration   3: 3.335 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 1.594 ms/op [Average]
  (min, avg, max) = (3.335, 3.433, 3.503), stdev = 0.087
  CI (99.9%): [1.839, 5.027] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 9.659 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.999 ±(99.9%) 0.008 ms/op
Iteration   1: 3.951 ±(99.9%) 0.011 ms/op
Iteration   2: 4.011 ±(99.9%) 0.006 ms/op
Iteration   3: 4.064 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.009 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (3.951, 4.009, 4.064), stdev = 0.057
  CI (99.9%): [2.976, 5.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.380 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.011 ms/op
Iteration   1: 3.484 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  18.910 ms/op
                 createUser·p0.9999: 23.718 ms/op
                 createUser·p1.00:   24.347 ms/op

Iteration   2: 3.467 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.327 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.051 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.751 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 27.518 ms/op
                 createUser·p1.00:   28.115 ms/op

Iteration   3: 3.500 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  19.464 ms/op
                 createUser·p0.9999: 25.443 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275509
  mean =      3.484 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14986 
    [ 2.500,  5.000) = 253568 
    [ 5.000,  7.500) = 6100 
    [ 7.500, 10.000) = 437 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.071 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     26.080 ms/op
     p(99.9990) =     27.853 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.703 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.394 ±(99.9%) 0.008 ms/op
Iteration   1: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.628 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.464 ms/op
                 existUser·p0.999:  19.912 ms/op
                 existUser·p0.9999: 22.160 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.222 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.724 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.392 ms/op
                 existUser·p0.999:  12.595 ms/op
                 existUser·p0.9999: 24.101 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.395 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.863 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 28.041 ms/op
                 existUser·p1.00:   30.343 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287752
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11445 
    [ 2.500,  5.000) = 269357 
    [ 5.000,  7.500) = 5680 
    [ 7.500, 10.000) = 641 
    [10.000, 12.500) = 305 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 32 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.335 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     13.722 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     28.487 ms/op
     p(99.9999) =     30.343 ms/op
    p(100.0000) =     30.343 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.983 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.643 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.383 ±(99.9%) 0.010 ms/op
Iteration   1: 3.459 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.460 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   5.177 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  19.645 ms/op
                 getUser·p0.9999: 24.650 ms/op
                 getUser·p1.00:   26.182 ms/op

Iteration   2: 3.385 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.389 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   5.702 ms/op
                 getUser·p0.999:  19.497 ms/op
                 getUser·p0.9999: 22.431 ms/op
                 getUser·p1.00:   22.839 ms/op

Iteration   3: 3.341 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.232 ms/op
                 getUser·p0.90:   3.760 ms/op
                 getUser·p0.95:   4.157 ms/op
                 getUser·p0.99:   6.029 ms/op
                 getUser·p0.999:  9.896 ms/op
                 getUser·p0.9999: 23.589 ms/op
                 getUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282641
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4282 
    [ 2.500,  5.000) = 269263 
    [ 5.000,  7.500) = 7835 
    [ 7.500, 10.000) = 779 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 133 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.389 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     18.809 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     25.465 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.007 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.013 ms/op
Iteration   1: 3.945 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  21.201 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 3.940 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.754 ms/op
                 listUser·p0.99:   7.995 ms/op
                 listUser·p0.999:  17.727 ms/op
                 listUser·p0.9999: 32.768 ms/op
                 listUser·p1.00:   33.686 ms/op

Iteration   3: 4.015 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.782 ms/op
                 listUser·p0.999:  15.231 ms/op
                 listUser·p0.9999: 20.907 ms/op
                 listUser·p1.00:   21.168 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241812
  mean =      3.966 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 232373 
    [ 5.000,  7.500) = 6738 
    [ 7.500, 10.000) = 1773 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 268 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.768 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     17.766 ms/op
     p(99.9900) =     28.584 ms/op
     p(99.9990) =     33.391 ms/op
     p(99.9999) =     33.686 ms/op
    p(100.0000) =     33.686 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.592 ± 4.796  ops/ms
ClientPb.existUser                       thrpt       3   9.765 ± 2.459  ops/ms
ClientPb.getUser                         thrpt       3   9.489 ± 2.064  ops/ms
ClientPb.listUser                        thrpt       3   8.286 ± 3.132  ops/ms
ClientPb.createUser                       avgt       3   3.419 ± 2.165   ms/op
ClientPb.existUser                        avgt       3   3.237 ± 0.596   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 1.594   ms/op
ClientPb.listUser                         avgt       3   4.009 ± 1.033   ms/op
ClientPb.createUser                     sample  275509   3.484 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.595           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.080           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.115           ms/op
ClientPb.existUser                      sample  287752   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.335           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.898           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.722           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.509           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.343           ms/op
ClientPb.getUser                        sample  282641   3.394 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.389           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.719           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.809           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.626           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.182           ms/op
ClientPb.listUser                       sample  241812   3.966 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.313           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.756           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.768           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.766           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.584           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.686           ms/op
