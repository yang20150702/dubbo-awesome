# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.104 ops/ms
# Warmup Iteration   2: 12.374 ops/ms
# Warmup Iteration   3: 12.244 ops/ms
Iteration   1: 12.507 ops/ms
Iteration   2: 12.541 ops/ms
Iteration   3: 12.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.530 ±(99.9%) 0.363 ops/ms [Average]
  (min, avg, max) = (12.507, 12.530, 12.542), stdev = 0.020
  CI (99.9%): [12.166, 12.893] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.064 ops/ms
# Warmup Iteration   2: 12.839 ops/ms
# Warmup Iteration   3: 13.000 ops/ms
Iteration   1: 12.834 ops/ms
Iteration   2: 13.014 ops/ms
Iteration   3: 12.753 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.867 ±(99.9%) 2.441 ops/ms [Average]
  (min, avg, max) = (12.753, 12.867, 13.014), stdev = 0.134
  CI (99.9%): [10.426, 15.308] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.012 ops/ms
# Warmup Iteration   2: 12.414 ops/ms
# Warmup Iteration   3: 12.602 ops/ms
Iteration   1: 12.619 ops/ms
Iteration   2: 12.549 ops/ms
Iteration   3: 12.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.567 ±(99.9%) 0.832 ops/ms [Average]
  (min, avg, max) = (12.533, 12.567, 12.619), stdev = 0.046
  CI (99.9%): [11.735, 13.398] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.561 ops/ms
# Warmup Iteration   2: 10.506 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.558 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.568 ±(99.9%) 0.462 ops/ms [Average]
  (min, avg, max) = (10.549, 10.568, 10.597), stdev = 0.025
  CI (99.9%): [10.107, 11.030] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.669 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.582 ±(99.9%) 0.003 ms/op
Iteration   1: 2.618 ±(99.9%) 0.004 ms/op
Iteration   2: 2.549 ±(99.9%) 0.004 ms/op
Iteration   3: 2.547 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.571 ±(99.9%) 0.732 ms/op [Average]
  (min, avg, max) = (2.547, 2.571, 2.618), stdev = 0.040
  CI (99.9%): [1.839, 3.304] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.498 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.003 ms/op
Iteration   1: 2.477 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
Iteration   3: 2.469 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.474 ±(99.9%) 0.083 ms/op [Average]
  (min, avg, max) = (2.469, 2.474, 2.477), stdev = 0.005
  CI (99.9%): [2.391, 2.557] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.966 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.599 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.501 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.481 ±(99.9%) 0.306 ms/op [Average]
  (min, avg, max) = (2.470, 2.481, 2.501), stdev = 0.017
  CI (99.9%): [2.176, 2.787] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.709 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.005 ms/op
Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
Iteration   3: 3.037 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.044 ±(99.9%) 0.171 ms/op [Average]
  (min, avg, max) = (3.037, 3.044, 3.055), stdev = 0.009
  CI (99.9%): [2.873, 3.215] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.215 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.710 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.191 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.398 ms/op
                 createUser·p0.9999: 13.819 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.604 ms/op
                 createUser·p0.999:  9.255 ms/op
                 createUser·p0.9999: 11.786 ms/op
                 createUser·p1.00:   12.730 ms/op

Iteration   3: 2.568 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.512 ms/op
                 createUser·p0.50:   2.638 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.240 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  9.241 ms/op
                 createUser·p0.9999: 10.546 ms/op
                 createUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376346
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180269 
    [ 2.500,  3.750) = 191920 
    [ 3.750,  5.000) = 3170 
    [ 5.000,  6.250) = 474 
    [ 6.250,  7.500) = 24 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.512 ms/op
     p(50.0000) =      2.613 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      9.257 ms/op
     p(99.9900) =     13.097 ms/op
     p(99.9990) =     14.045 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   2.527 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.056 ms/op
                 existUser·p0.99:   3.391 ms/op
                 existUser·p0.999:  5.842 ms/op
                 existUser·p0.9999: 13.423 ms/op
                 existUser·p1.00:   13.992 ms/op

Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.465 ms/op
                 existUser·p0.999:  7.912 ms/op
                 existUser·p0.9999: 12.302 ms/op
                 existUser·p1.00:   12.517 ms/op

Iteration   3: 2.463 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.033 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  7.157 ms/op
                 existUser·p0.9999: 15.335 ms/op
                 existUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390893
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 194512 
    [ 2.500,  3.750) = 193968 
    [ 3.750,  5.000) = 1763 
    [ 5.000,  6.250) = 181 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.836 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      2.978 ms/op
     p(95.0000) =      3.072 ms/op
     p(99.0000) =      3.465 ms/op
     p(99.9000) =      7.390 ms/op
     p(99.9900) =     13.792 ms/op
     p(99.9990) =     15.423 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.870 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.569 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.495 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  10.674 ms/op
                 getUser·p0.9999: 13.182 ms/op
                 getUser·p1.00:   13.779 ms/op

Iteration   2: 2.501 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  8.595 ms/op
                 getUser·p0.9999: 12.177 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  6.573 ms/op
                 getUser·p0.9999: 12.128 ms/op
                 getUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383602
  mean =      2.500 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 189808 
    [ 2.500,  3.750) = 187731 
    [ 3.750,  5.000) = 4787 
    [ 5.000,  6.250) = 815 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.187 ms/op
     p(99.0000) =      4.071 ms/op
     p(99.9000) =      6.653 ms/op
     p(99.9900) =     12.861 ms/op
     p(99.9990) =     13.637 ms/op
     p(99.9999) =     13.779 ms/op
    p(100.0000) =     13.779 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.588 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.015 ±(99.9%) 0.009 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.833 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.208 ms/op
                 listUser·p0.9999: 11.706 ms/op
                 listUser·p1.00:   12.665 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.388 ms/op
                 listUser·p0.9999: 12.378 ms/op
                 listUser·p1.00:   13.877 ms/op

Iteration   3: 3.041 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.842 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.175 ms/op
                 listUser·p0.9999: 12.026 ms/op
                 listUser·p1.00:   12.452 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316478
  mean =      3.030 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 108 
    [ 1.250,  2.500) = 86372 
    [ 2.500,  3.750) = 191478 
    [ 3.750,  5.000) = 31476 
    [ 5.000,  6.250) = 5873 
    [ 6.250,  7.500) = 522 
    [ 7.500,  8.750) = 244 
    [ 8.750, 10.000) = 174 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.216 ms/op
     p(99.9900) =     11.982 ms/op
     p(99.9990) =     13.542 ms/op
     p(99.9999) =     13.877 ms/op
    p(100.0000) =     13.877 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.530 ± 0.363  ops/ms
ClientPb.existUser                       thrpt       3  12.867 ± 2.441  ops/ms
ClientPb.getUser                         thrpt       3  12.567 ± 0.832  ops/ms
ClientPb.listUser                        thrpt       3  10.568 ± 0.462  ops/ms
ClientPb.createUser                       avgt       3   2.571 ± 0.732   ms/op
ClientPb.existUser                        avgt       3   2.474 ± 0.083   ms/op
ClientPb.getUser                          avgt       3   2.481 ± 0.306   ms/op
ClientPb.listUser                         avgt       3   3.044 ± 0.171   ms/op
ClientPb.createUser                     sample  376346   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.512           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.613           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.257           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  390893   2.454 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.836           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.511           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.978           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.072           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.465           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.390           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.792           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.630           ms/op
ClientPb.getUser                        sample  383602   2.500 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.527           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.187           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.071           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.653           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.861           ms/op
ClientPb.getUser:getUser·p1.00          sample          13.779           ms/op
ClientPb.listUser                       sample  316478   3.030 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.833           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.216           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.982           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.877           ms/op
