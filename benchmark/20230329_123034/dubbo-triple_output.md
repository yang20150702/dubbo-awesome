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
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 5.363 ops/ms
# Warmup Iteration   3: 8.760 ops/ms
Iteration   1: 9.062 ops/ms
Iteration   2: 9.246 ops/ms
Iteration   3: 9.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.268 ±(99.9%) 3.973 ops/ms [Average]
  (min, avg, max) = (9.062, 9.268, 9.496), stdev = 0.218
  CI (99.9%): [5.296, 13.241] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.053 ops/ms
# Warmup Iteration   2: 9.278 ops/ms
# Warmup Iteration   3: 9.992 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 9.894 ops/ms
Iteration   3: 9.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.153 ±(99.9%) 6.781 ops/ms [Average]
  (min, avg, max) = (9.894, 10.153, 10.579), stdev = 0.372
  CI (99.9%): [3.373, 16.934] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.466 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 9.099 ops/ms
Iteration   1: 9.848 ops/ms
Iteration   2: 10.149 ops/ms
Iteration   3: 9.831 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.942 ±(99.9%) 3.261 ops/ms [Average]
  (min, avg, max) = (9.831, 9.942, 10.149), stdev = 0.179
  CI (99.9%): [6.682, 13.203] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.638 ops/ms
# Warmup Iteration   2: 7.691 ops/ms
# Warmup Iteration   3: 8.557 ops/ms
Iteration   1: 8.327 ops/ms
Iteration   2: 8.471 ops/ms
Iteration   3: 8.300 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.366 ±(99.9%) 1.672 ops/ms [Average]
  (min, avg, max) = (8.300, 8.366, 8.471), stdev = 0.092
  CI (99.9%): [6.694, 10.038] (assumes normal distribution)


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
# Warmup Iteration   1: 8.330 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.518 ±(99.9%) 0.002 ms/op
Iteration   1: 3.247 ±(99.9%) 0.004 ms/op
Iteration   2: 3.206 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.209 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.176, 3.209, 3.247), stdev = 0.036
  CI (99.9%): [2.551, 3.868] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.775 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.003 ms/op
Iteration   1: 3.029 ±(99.9%) 0.005 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 3.013 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.034 ±(99.9%) 0.447 ms/op [Average]
  (min, avg, max) = (3.013, 3.034, 3.061), stdev = 0.025
  CI (99.9%): [2.587, 3.482] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.939 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.003 ms/op
Iteration   1: 3.281 ±(99.9%) 0.002 ms/op
Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
Iteration   3: 3.375 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.305 ±(99.9%) 1.129 ms/op [Average]
  (min, avg, max) = (3.258, 3.305, 3.375), stdev = 0.062
  CI (99.9%): [2.175, 4.434] (assumes normal distribution)


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
# Warmup Iteration   1: 9.488 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.180 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.948 ±(99.9%) 0.007 ms/op
Iteration   1: 3.778 ±(99.9%) 0.004 ms/op
Iteration   2: 3.790 ±(99.9%) 0.007 ms/op
Iteration   3: 3.650 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.739 ±(99.9%) 1.416 ms/op [Average]
  (min, avg, max) = (3.650, 3.739, 3.790), stdev = 0.078
  CI (99.9%): [2.323, 5.155] (assumes normal distribution)


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
# Warmup Iteration   1: 7.957 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.008 ms/op
Iteration   1: 3.272 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  9.360 ms/op
                 createUser·p0.9999: 20.677 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.238 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  20.860 ms/op
                 createUser·p0.9999: 28.184 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 3.146 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  14.385 ms/op
                 createUser·p0.9999: 19.355 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 298128
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8233 
    [ 2.500,  5.000) = 284110 
    [ 5.000,  7.500) = 4955 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 23 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     26.067 ms/op
     p(99.9990) =     29.001 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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
# Warmup Iteration   1: 7.694 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.333 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
Iteration   1: 3.066 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.722 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   5.323 ms/op
                 existUser·p0.999:  11.535 ms/op
                 existUser·p0.9999: 23.078 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   2: 3.109 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.280 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  13.779 ms/op
                 existUser·p0.9999: 26.798 ms/op
                 existUser·p1.00:   27.394 ms/op

Iteration   3: 3.165 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  13.238 ms/op
                 existUser·p0.9999: 20.804 ms/op
                 existUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308298
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16919 
    [ 2.500,  5.000) = 286187 
    [ 5.000,  7.500) = 4483 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 80 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     23.369 ms/op
     p(99.9990) =     27.227 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 9.261 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.336 ±(99.9%) 0.011 ms/op
Iteration   1: 3.212 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.497 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 27.625 ms/op
                 getUser·p1.00:   29.098 ms/op

Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.327 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.363 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  19.562 ms/op
                 getUser·p0.9999: 22.255 ms/op
                 getUser·p1.00:   22.675 ms/op

Iteration   3: 3.188 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  12.299 ms/op
                 getUser·p0.9999: 21.363 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302979
  mean =      3.166 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11309 
    [ 2.500,  5.000) = 286562 
    [ 5.000,  7.500) = 4251 
    [ 7.500, 10.000) = 403 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     15.041 ms/op
     p(99.9900) =     25.177 ms/op
     p(99.9990) =     28.145 ms/op
     p(99.9999) =     29.098 ms/op
    p(100.0000) =     29.098 ms/op


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
# Warmup Iteration   1: 8.838 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 4.064 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.011 ms/op
Iteration   1: 3.797 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.346 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  15.364 ms/op
                 listUser·p0.9999: 21.351 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.750 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.753 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 16.082 ms/op
                 listUser·p1.00:   16.712 ms/op

Iteration   3: 3.785 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.567 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254022
  mean =      3.777 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 246724 
    [ 5.000,  7.500) = 5260 
    [ 7.500, 10.000) = 1320 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.567 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     20.873 ms/op
     p(99.9990) =     21.840 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.268 ± 3.973  ops/ms
ClientPb.existUser                       thrpt       3  10.153 ± 6.781  ops/ms
ClientPb.getUser                         thrpt       3   9.942 ± 3.261  ops/ms
ClientPb.listUser                        thrpt       3   8.366 ± 1.672  ops/ms
ClientPb.createUser                       avgt       3   3.209 ± 0.658   ms/op
ClientPb.existUser                        avgt       3   3.034 ± 0.447   ms/op
ClientPb.getUser                          avgt       3   3.305 ± 1.129   ms/op
ClientPb.listUser                         avgt       3   3.739 ± 1.416   ms/op
ClientPb.createUser                     sample  298128   3.218 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.660           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.662           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.961           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.942           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.067           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  308298   3.113 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.280           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.322           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.464           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.238           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.394           ms/op
ClientPb.getUser                        sample  302979   3.166 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.821           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.080           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.453           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.686           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.480           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.041           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.098           ms/op
ClientPb.listUser                       sample  254022   3.777 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.567           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.100           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.947           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.873           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
