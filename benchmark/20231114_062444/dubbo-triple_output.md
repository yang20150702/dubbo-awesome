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
# Warmup Iteration   1: 5.047 ops/ms
# Warmup Iteration   2: 11.974 ops/ms
# Warmup Iteration   3: 12.214 ops/ms
Iteration   1: 12.326 ops/ms
Iteration   2: 12.388 ops/ms
Iteration   3: 12.538 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.418 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (12.326, 12.418, 12.538), stdev = 0.109
  CI (99.9%): [10.432, 14.404] (assumes normal distribution)


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
# Warmup Iteration   1: 7.323 ops/ms
# Warmup Iteration   2: 12.689 ops/ms
# Warmup Iteration   3: 12.727 ops/ms
Iteration   1: 12.752 ops/ms
Iteration   2: 12.732 ops/ms
Iteration   3: 12.825 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.770 ±(99.9%) 0.890 ops/ms [Average]
  (min, avg, max) = (12.732, 12.770, 12.825), stdev = 0.049
  CI (99.9%): [11.880, 13.659] (assumes normal distribution)


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
# Warmup Iteration   1: 8.058 ops/ms
# Warmup Iteration   2: 12.329 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.547 ops/ms
Iteration   2: 12.712 ops/ms
Iteration   3: 12.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.561 ±(99.9%) 2.630 ops/ms [Average]
  (min, avg, max) = (12.425, 12.561, 12.712), stdev = 0.144
  CI (99.9%): [9.931, 15.192] (assumes normal distribution)


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
# Warmup Iteration   1: 6.760 ops/ms
# Warmup Iteration   2: 10.237 ops/ms
# Warmup Iteration   3: 10.369 ops/ms
Iteration   1: 10.362 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.438 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (10.362, 10.438, 10.494), stdev = 0.068
  CI (99.9%): [9.194, 11.683] (assumes normal distribution)


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
# Warmup Iteration   1: 4.119 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.640 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.004 ms/op
Iteration   1: 2.551 ±(99.9%) 0.004 ms/op
Iteration   2: 2.593 ±(99.9%) 0.004 ms/op
Iteration   3: 2.558 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.567 ±(99.9%) 0.408 ms/op [Average]
  (min, avg, max) = (2.551, 2.567, 2.593), stdev = 0.022
  CI (99.9%): [2.159, 2.975] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.484 ±(99.9%) 0.004 ms/op
Iteration   1: 2.460 ±(99.9%) 0.004 ms/op
Iteration   2: 2.459 ±(99.9%) 0.004 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.373 ms/op [Average]
  (min, avg, max) = (2.459, 2.471, 2.495), stdev = 0.020
  CI (99.9%): [2.098, 2.844] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.808 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.579 ±(99.9%) 0.004 ms/op
Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
Iteration   3: 2.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.554 ±(99.9%) 0.600 ms/op [Average]
  (min, avg, max) = (2.517, 2.554, 2.579), stdev = 0.033
  CI (99.9%): [1.953, 3.154] (assumes normal distribution)


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
# Warmup Iteration   1: 4.965 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
Iteration   3: 3.064 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.067 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (3.053, 3.067, 3.083), stdev = 0.015
  CI (99.9%): [2.788, 3.346] (assumes normal distribution)


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
# Warmup Iteration   1: 4.219 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.674 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.548 ±(99.9%) 0.006 ms/op
Iteration   1: 2.525 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.025 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.907 ms/op
                 createUser·p0.999:  11.853 ms/op
                 createUser·p0.9999: 14.014 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   3.564 ms/op
                 createUser·p0.999:  10.441 ms/op
                 createUser·p0.9999: 14.234 ms/op
                 createUser·p1.00:   15.483 ms/op

Iteration   3: 2.547 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  8.126 ms/op
                 createUser·p0.9999: 10.238 ms/op
                 createUser·p1.00:   10.797 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 379661
  mean =      2.527 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 31 
    [ 1.250,  2.500) = 181309 
    [ 2.500,  3.750) = 193926 
    [ 3.750,  5.000) = 3526 
    [ 5.000,  6.250) = 435 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 97 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      8.268 ms/op
     p(99.9900) =     13.992 ms/op
     p(99.9990) =     15.119 ms/op
     p(99.9999) =     15.483 ms/op
    p(100.0000) =     15.483 ms/op


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
# Warmup Iteration   1: 3.814 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.475 ±(99.9%) 0.005 ms/op
Iteration   1: 2.485 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.519 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.207 ms/op
                 existUser·p0.99:   4.105 ms/op
                 existUser·p0.999:  7.912 ms/op
                 existUser·p0.9999: 13.978 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.843 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.978 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  9.119 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.007 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  5.947 ms/op
                 existUser·p0.9999: 10.797 ms/op
                 existUser·p1.00:   11.043 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 387984
  mean =      2.472 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 190924 
    [ 2.500,  3.750) = 192429 
    [ 3.750,  5.000) = 3626 
    [ 5.000,  6.250) = 562 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 61 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 76 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.531 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      6.177 ms/op
     p(99.9900) =     14.802 ms/op
     p(99.9990) =     17.944 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.554 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.920 ms/op
                 getUser·p0.50:   2.576 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  12.091 ms/op
                 getUser·p0.9999: 14.250 ms/op
                 getUser·p1.00:   15.106 ms/op

Iteration   2: 2.554 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.886 ms/op
                 getUser·p0.50:   2.593 ms/op
                 getUser·p0.90:   3.113 ms/op
                 getUser·p0.95:   3.260 ms/op
                 getUser·p0.99:   4.116 ms/op
                 getUser·p0.999:  9.437 ms/op
                 getUser·p0.9999: 12.796 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.586 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   2.617 ms/op
                 getUser·p0.90:   3.150 ms/op
                 getUser·p0.95:   3.330 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  9.421 ms/op
                 getUser·p0.9999: 14.232 ms/op
                 getUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 374977
  mean =      2.558 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 59 
    [ 1.250,  2.500) = 180544 
    [ 2.500,  3.750) = 187647 
    [ 3.750,  5.000) = 4731 
    [ 5.000,  6.250) = 1537 
    [ 6.250,  7.500) = 67 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 94 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 122 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.260 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      9.421 ms/op
     p(99.9900) =     14.156 ms/op
     p(99.9990) =     14.995 ms/op
     p(99.9999) =     15.106 ms/op
    p(100.0000) =     15.106 ms/op


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
# Warmup Iteration   1: 4.763 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.122 ±(99.9%) 0.009 ms/op
Iteration   1: 3.088 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.838 ms/op
                 listUser·p0.50:   3.031 ms/op
                 listUser·p0.90:   3.981 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.710 ms/op
                 listUser·p0.999:  10.002 ms/op
                 listUser·p0.9999: 13.308 ms/op
                 listUser·p1.00:   14.287 ms/op

Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.027 ms/op
                 listUser·p0.90:   3.998 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.749 ms/op
                 listUser·p0.9999: 11.168 ms/op
                 listUser·p1.00:   11.878 ms/op

Iteration   3: 3.094 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.039 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.718 ms/op
                 listUser·p0.999:  10.169 ms/op
                 listUser·p0.9999: 12.485 ms/op
                 listUser·p1.00:   13.730 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310308
  mean =      3.091 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 78908 
    [ 2.500,  3.750) = 186389 
    [ 3.750,  5.000) = 36786 
    [ 5.000,  6.250) = 6567 
    [ 6.250,  7.500) = 894 
    [ 7.500,  8.750) = 198 
    [ 8.750, 10.000) = 158 
    [10.000, 11.250) = 187 
    [11.250, 12.500) = 86 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     12.533 ms/op
     p(99.9990) =     13.926 ms/op
     p(99.9999) =     14.287 ms/op
    p(100.0000) =     14.287 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.418 ± 1.986  ops/ms
ClientPb.existUser                       thrpt       3  12.770 ± 0.890  ops/ms
ClientPb.getUser                         thrpt       3  12.561 ± 2.630  ops/ms
ClientPb.listUser                        thrpt       3  10.438 ± 1.245  ops/ms
ClientPb.createUser                       avgt       3   2.567 ± 0.408   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.373   ms/op
ClientPb.getUser                          avgt       3   2.554 ± 0.600   ms/op
ClientPb.listUser                         avgt       3   3.067 ± 0.279   ms/op
ClientPb.createUser                     sample  379661   2.527 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.947           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.842           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.268           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.992           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.483           ms/op
ClientPb.existUser                      sample  387984   2.472 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.843           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.531           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.177           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.802           ms/op
ClientPb.existUser:existUser·p1.00      sample          18.219           ms/op
ClientPb.getUser                        sample  374977   2.558 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.873           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.597           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.260           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.421           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.156           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.106           ms/op
ClientPb.listUser                       sample  310308   3.091 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.838           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.035           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.990           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.961           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.533           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.287           ms/op
