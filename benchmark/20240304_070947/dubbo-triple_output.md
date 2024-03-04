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
# Warmup Iteration   1: 4.708 ops/ms
# Warmup Iteration   2: 12.647 ops/ms
# Warmup Iteration   3: 12.774 ops/ms
Iteration   1: 13.043 ops/ms
Iteration   2: 12.989 ops/ms
Iteration   3: 13.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.019 ±(99.9%) 0.500 ops/ms [Average]
  (min, avg, max) = (12.989, 13.019, 13.043), stdev = 0.027
  CI (99.9%): [12.520, 13.519] (assumes normal distribution)


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
# Warmup Iteration   1: 8.660 ops/ms
# Warmup Iteration   2: 13.469 ops/ms
# Warmup Iteration   3: 13.443 ops/ms
Iteration   1: 13.555 ops/ms
Iteration   2: 13.562 ops/ms
Iteration   3: 13.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.491 ±(99.9%) 2.121 ops/ms [Average]
  (min, avg, max) = (13.357, 13.491, 13.562), stdev = 0.116
  CI (99.9%): [11.370, 15.612] (assumes normal distribution)


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
# Warmup Iteration   1: 7.793 ops/ms
# Warmup Iteration   2: 12.682 ops/ms
# Warmup Iteration   3: 12.738 ops/ms
Iteration   1: 12.815 ops/ms
Iteration   2: 12.899 ops/ms
Iteration   3: 12.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.826 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (12.764, 12.826, 12.899), stdev = 0.068
  CI (99.9%): [11.590, 14.062] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.695 ops/ms
# Warmup Iteration   2: 10.455 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.561 ops/ms
Iteration   2: 10.591 ops/ms
Iteration   3: 10.535 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.562 ±(99.9%) 0.504 ops/ms [Average]
  (min, avg, max) = (10.535, 10.562, 10.591), stdev = 0.028
  CI (99.9%): [10.059, 11.066] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.990 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.003 ms/op
Iteration   1: 2.496 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
Iteration   3: 2.483 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.496 ±(99.9%) 0.224 ms/op [Average]
  (min, avg, max) = (2.483, 2.496, 2.508), stdev = 0.012
  CI (99.9%): [2.272, 2.720] (assumes normal distribution)


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
# Warmup Iteration   1: 3.455 ±(99.9%) 0.007 ms/op
# Warmup Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.430 ±(99.9%) 0.004 ms/op
Iteration   1: 2.394 ±(99.9%) 0.003 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.410 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.407 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.394, 2.407, 2.418), stdev = 0.012
  CI (99.9%): [2.185, 2.630] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 4.062 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.422 ±(99.9%) 0.004 ms/op
Iteration   1: 2.456 ±(99.9%) 0.005 ms/op
Iteration   2: 2.433 ±(99.9%) 0.004 ms/op
Iteration   3: 2.433 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.441 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.433, 2.441, 2.456), stdev = 0.013
  CI (99.9%): [2.202, 2.680] (assumes normal distribution)


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
# Warmup Iteration   1: 4.645 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.991 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.005 ms/op
Iteration   1: 2.967 ±(99.9%) 0.006 ms/op
Iteration   2: 2.954 ±(99.9%) 0.006 ms/op
Iteration   3: 2.957 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.960 ±(99.9%) 0.117 ms/op [Average]
  (min, avg, max) = (2.954, 2.960, 2.967), stdev = 0.006
  CI (99.9%): [2.842, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 4.200 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.479 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   2.998 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.609 ms/op
                 createUser·p0.999:  9.503 ms/op
                 createUser·p0.9999: 13.895 ms/op
                 createUser·p1.00:   14.696 ms/op

Iteration   2: 2.469 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.113 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  5.555 ms/op
                 createUser·p0.9999: 12.354 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.919 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.854 ms/op
                 createUser·p0.999:  7.643 ms/op
                 createUser·p0.9999: 9.832 ms/op
                 createUser·p1.00:   10.142 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387549
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 189194 
    [ 2.500,  3.750) = 194968 
    [ 3.750,  5.000) = 2586 
    [ 5.000,  6.250) = 285 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 75 
    [ 8.750, 10.000) = 111 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.678 ms/op
     p(99.9000) =      8.083 ms/op
     p(99.9900) =     13.357 ms/op
     p(99.9990) =     14.209 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 3.706 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.459 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
Iteration   1: 2.399 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.953 ms/op
                 existUser·p0.50:   2.421 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.708 ms/op
                 existUser·p0.9999: 14.238 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   2: 2.444 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.961 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   4.424 ms/op
                 existUser·p0.999:  7.497 ms/op
                 existUser·p0.9999: 12.942 ms/op
                 existUser·p1.00:   13.386 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   2.474 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.064 ms/op
                 existUser·p0.99:   3.621 ms/op
                 existUser·p0.999:  8.064 ms/op
                 existUser·p0.9999: 10.557 ms/op
                 existUser·p1.00:   11.223 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395662
  mean =      2.424 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 202425 
    [ 2.500,  3.750) = 188924 
    [ 3.750,  5.000) = 3245 
    [ 5.000,  6.250) = 491 
    [ 6.250,  7.500) = 95 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 48 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      2.458 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.809 ms/op
     p(99.9000) =      7.512 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.435 ms/op
     p(99.9999) =     14.516 ms/op
    p(100.0000) =     14.516 ms/op


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
# Warmup Iteration   1: 3.699 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.517 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
Iteration   1: 2.444 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   2.449 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.695 ms/op
                 getUser·p0.999:  6.075 ms/op
                 getUser·p0.9999: 14.481 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.456 ms/op
                 getUser·p0.9999: 13.444 ms/op
                 getUser·p1.00:   14.320 ms/op

Iteration   3: 2.435 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.945 ms/op
                 getUser·p0.50:   2.454 ms/op
                 getUser·p0.90:   2.978 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.711 ms/op
                 getUser·p0.999:  5.326 ms/op
                 getUser·p0.9999: 11.404 ms/op
                 getUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390404
  mean =      2.457 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 120 
    [ 1.250,  2.500) = 198741 
    [ 2.500,  3.750) = 186214 
    [ 3.750,  5.000) = 4154 
    [ 5.000,  6.250) = 740 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 21 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =      8.169 ms/op
     p(99.9900) =     13.958 ms/op
     p(99.9990) =     14.768 ms/op
     p(99.9999) =     15.008 ms/op
    p(100.0000) =     15.008 ms/op


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
# Warmup Iteration   1: 4.709 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.008 ms/op
Iteration   1: 2.919 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   2.859 ms/op
                 listUser·p0.90:   3.756 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   5.415 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 13.223 ms/op
                 listUser·p1.00:   14.828 ms/op

Iteration   2: 2.981 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.795 ms/op
                 listUser·p0.50:   2.908 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.449 ms/op
                 listUser·p0.9999: 11.605 ms/op
                 listUser·p1.00:   13.091 ms/op

Iteration   3: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.763 ms/op
                 listUser·p0.50:   2.896 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.372 ms/op
                 listUser·p0.9999: 10.849 ms/op
                 listUser·p1.00:   12.108 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325164
  mean =      2.950 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 185 
    [ 1.250,  2.500) = 103662 
    [ 2.500,  3.750) = 185438 
    [ 3.750,  5.000) = 29137 
    [ 5.000,  6.250) = 5666 
    [ 6.250,  7.500) = 439 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 260 
    [10.000, 11.250) = 114 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     12.550 ms/op
     p(99.9990) =     14.725 ms/op
     p(99.9999) =     14.828 ms/op
    p(100.0000) =     14.828 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.019 ± 0.500  ops/ms
ClientPb.existUser                       thrpt       3  13.491 ± 2.121  ops/ms
ClientPb.getUser                         thrpt       3  12.826 ± 1.236  ops/ms
ClientPb.listUser                        thrpt       3  10.562 ± 0.504  ops/ms
ClientPb.createUser                       avgt       3   2.496 ± 0.224   ms/op
ClientPb.existUser                        avgt       3   2.407 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.441 ± 0.239   ms/op
ClientPb.listUser                         avgt       3   2.960 ± 0.117   ms/op
ClientPb.createUser                     sample  387549   2.475 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.919           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.544           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.678           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.083           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.357           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.696           ms/op
ClientPb.existUser                      sample  395662   2.424 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.506           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.458           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.512           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.516           ms/op
ClientPb.getUser                        sample  390404   2.457 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.649           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.470           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.169           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.958           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.008           ms/op
ClientPb.listUser                       sample  325164   2.950 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.763           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.888           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.817           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.550           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.828           ms/op
