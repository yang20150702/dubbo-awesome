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
# Warmup Iteration   1: 5.408 ops/ms
# Warmup Iteration   2: 12.112 ops/ms
# Warmup Iteration   3: 12.231 ops/ms
Iteration   1: 12.505 ops/ms
Iteration   2: 12.533 ops/ms
Iteration   3: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.556 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (12.505, 12.556, 12.631), stdev = 0.067
  CI (99.9%): [11.342, 13.771] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.100 ops/ms
# Warmup Iteration   2: 13.237 ops/ms
# Warmup Iteration   3: 13.090 ops/ms
Iteration   1: 13.046 ops/ms
Iteration   2: 13.188 ops/ms
Iteration   3: 13.238 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.157 ±(99.9%) 1.821 ops/ms [Average]
  (min, avg, max) = (13.046, 13.157, 13.238), stdev = 0.100
  CI (99.9%): [11.337, 14.978] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.793 ops/ms
# Warmup Iteration   2: 12.570 ops/ms
# Warmup Iteration   3: 12.877 ops/ms
Iteration   1: 13.025 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 13.018 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.990 ±(99.9%) 0.999 ops/ms [Average]
  (min, avg, max) = (12.927, 12.990, 13.025), stdev = 0.055
  CI (99.9%): [11.990, 13.989] (assumes normal distribution)


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
# Warmup Iteration   1: 6.797 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.427 ops/ms
Iteration   1: 10.542 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.470 ±(99.9%) 1.524 ops/ms [Average]
  (min, avg, max) = (10.378, 10.470, 10.542), stdev = 0.084
  CI (99.9%): [8.946, 11.994] (assumes normal distribution)


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
# Warmup Iteration   1: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.542 ±(99.9%) 0.003 ms/op
Iteration   1: 2.512 ±(99.9%) 0.004 ms/op
Iteration   2: 2.532 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.527 ±(99.9%) 0.234 ms/op [Average]
  (min, avg, max) = (2.512, 2.527, 2.537), stdev = 0.013
  CI (99.9%): [2.293, 2.761] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.626 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.444 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.473 ±(99.9%) 0.003 ms/op
Iteration   1: 2.468 ±(99.9%) 0.004 ms/op
Iteration   2: 2.449 ±(99.9%) 0.004 ms/op
Iteration   3: 2.454 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.457 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.449, 2.457, 2.468), stdev = 0.010
  CI (99.9%): [2.271, 2.643] (assumes normal distribution)


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
# Warmup Iteration   1: 3.991 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.542 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.003 ms/op
Iteration   2: 2.528 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.513 ±(99.9%) 0.254 ms/op [Average]
  (min, avg, max) = (2.500, 2.513, 2.528), stdev = 0.014
  CI (99.9%): [2.259, 2.767] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.876 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.081 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 3.024 ±(99.9%) 0.004 ms/op
Iteration   3: 3.055 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.036 ±(99.9%) 0.309 ms/op [Average]
  (min, avg, max) = (3.024, 3.036, 3.055), stdev = 0.017
  CI (99.9%): [2.727, 3.344] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.650 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.006 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  12.133 ms/op
                 createUser·p0.9999: 17.465 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.596 ms/op
                 createUser·p0.999:  9.185 ms/op
                 createUser·p0.9999: 12.517 ms/op
                 createUser·p1.00:   13.369 ms/op

Iteration   3: 2.559 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.019 ms/op
                 createUser·p0.999:  8.552 ms/op
                 createUser·p0.9999: 10.421 ms/op
                 createUser·p1.00:   12.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377720
  mean =      2.539 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 182232 
    [ 2.500,  3.750) = 191367 
    [ 3.750,  5.000) = 3266 
    [ 5.000,  6.250) = 348 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 101 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      8.573 ms/op
     p(99.9900) =     13.646 ms/op
     p(99.9990) =     17.604 ms/op
     p(99.9999) =     17.727 ms/op
    p(100.0000) =     17.727 ms/op


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
# Warmup Iteration   1: 3.648 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.449 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
Iteration   1: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.031 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.432 ms/op
                 existUser·p0.999:  8.320 ms/op
                 existUser·p0.9999: 14.088 ms/op
                 existUser·p1.00:   14.647 ms/op

Iteration   2: 2.437 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.049 ms/op
                 existUser·p0.50:   2.568 ms/op
                 existUser·p0.90:   2.941 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.332 ms/op
                 existUser·p0.999:  6.605 ms/op
                 existUser·p0.9999: 13.353 ms/op
                 existUser·p1.00:   13.779 ms/op

Iteration   3: 2.452 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 12.790 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 392880
  mean =      2.441 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 195814 
    [ 2.500,  3.750) = 193989 
    [ 3.750,  5.000) = 2202 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.338 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.647 ms/op
    p(100.0000) =     14.647 ms/op


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
# Warmup Iteration   1: 4.321 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.584 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.889 ms/op
                 getUser·p0.999:  10.863 ms/op
                 getUser·p0.9999: 14.285 ms/op
                 getUser·p1.00:   15.041 ms/op

Iteration   2: 2.561 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.277 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  10.362 ms/op
                 getUser·p0.9999: 14.329 ms/op
                 getUser·p1.00:   15.237 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   2.519 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.998 ms/op
                 getUser·p0.999:  8.686 ms/op
                 getUser·p0.9999: 13.821 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379693
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 96 
    [ 1.250,  2.500) = 186425 
    [ 2.500,  3.750) = 187005 
    [ 3.750,  5.000) = 5091 
    [ 5.000,  6.250) = 600 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 22 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 101 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      4.076 ms/op
     p(99.9000) =      8.862 ms/op
     p(99.9900) =     14.221 ms/op
     p(99.9990) =     15.014 ms/op
     p(99.9999) =     15.237 ms/op
    p(100.0000) =     15.237 ms/op


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
# Warmup Iteration   1: 4.548 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.009 ms/op
Iteration   1: 3.050 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.674 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.675 ms/op
                 listUser·p0.999:  8.785 ms/op
                 listUser·p0.9999: 11.215 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   2: 3.049 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.676 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.748 ms/op
                 listUser·p0.9999: 11.192 ms/op
                 listUser·p1.00:   11.469 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.809 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.871 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.365 ms/op
                 listUser·p0.9999: 10.760 ms/op
                 listUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315094
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 161 
    [ 1.250,  2.500) = 85477 
    [ 2.500,  3.750) = 187812 
    [ 3.750,  5.000) = 34437 
    [ 5.000,  6.250) = 5904 
    [ 6.250,  7.500) = 635 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 254 
    [10.000, 11.250) = 170 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =      9.241 ms/op
     p(99.9900) =     11.116 ms/op
     p(99.9990) =     11.580 ms/op
     p(99.9999) =     11.928 ms/op
    p(100.0000) =     11.928 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.556 ± 1.215  ops/ms
ClientPb.existUser                       thrpt       3  13.157 ± 1.821  ops/ms
ClientPb.getUser                         thrpt       3  12.990 ± 0.999  ops/ms
ClientPb.listUser                        thrpt       3  10.470 ± 1.524  ops/ms
ClientPb.createUser                       avgt       3   2.527 ± 0.234   ms/op
ClientPb.existUser                        avgt       3   2.457 ± 0.186   ms/op
ClientPb.getUser                          avgt       3   2.513 ± 0.254   ms/op
ClientPb.listUser                         avgt       3   3.036 ± 0.309   ms/op
ClientPb.createUser                     sample  377720   2.539 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.771           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.573           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.646           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.727           ms/op
ClientPb.existUser                      sample  392880   2.441 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.865           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.507           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.338           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.320           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.647           ms/op
ClientPb.getUser                        sample  379693   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.854           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.224           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.076           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.862           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.221           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.237           ms/op
ClientPb.listUser                       sample  315094   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.674           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.982           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.612           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.241           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.116           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.928           ms/op
