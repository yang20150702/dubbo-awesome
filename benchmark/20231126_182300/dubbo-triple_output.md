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
# Warmup Iteration   1: 4.934 ops/ms
# Warmup Iteration   2: 12.253 ops/ms
# Warmup Iteration   3: 12.523 ops/ms
Iteration   1: 12.723 ops/ms
Iteration   2: 12.695 ops/ms
Iteration   3: 12.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.739 ±(99.9%) 0.988 ops/ms [Average]
  (min, avg, max) = (12.695, 12.739, 12.800), stdev = 0.054
  CI (99.9%): [11.752, 13.727] (assumes normal distribution)


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
# Warmup Iteration   1: 8.185 ops/ms
# Warmup Iteration   2: 12.985 ops/ms
# Warmup Iteration   3: 13.033 ops/ms
Iteration   1: 12.981 ops/ms
Iteration   2: 13.018 ops/ms
Iteration   3: 13.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.027 ±(99.9%) 0.937 ops/ms [Average]
  (min, avg, max) = (12.981, 13.027, 13.083), stdev = 0.051
  CI (99.9%): [12.090, 13.965] (assumes normal distribution)


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
# Warmup Iteration   1: 7.718 ops/ms
# Warmup Iteration   2: 12.597 ops/ms
# Warmup Iteration   3: 12.764 ops/ms
Iteration   1: 12.844 ops/ms
Iteration   2: 12.916 ops/ms
Iteration   3: 12.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.901 ±(99.9%) 0.923 ops/ms [Average]
  (min, avg, max) = (12.844, 12.901, 12.942), stdev = 0.051
  CI (99.9%): [11.978, 13.823] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.576 ops/ms
# Warmup Iteration   2: 10.605 ops/ms
# Warmup Iteration   3: 10.582 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.646 ops/ms
Iteration   3: 10.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.566 ±(99.9%) 1.886 ops/ms [Average]
  (min, avg, max) = (10.449, 10.566, 10.646), stdev = 0.103
  CI (99.9%): [8.680, 12.453] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.252 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.654 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
Iteration   1: 2.563 ±(99.9%) 0.004 ms/op
Iteration   2: 2.571 ±(99.9%) 0.004 ms/op
Iteration   3: 2.564 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.566 ±(99.9%) 0.082 ms/op [Average]
  (min, avg, max) = (2.563, 2.566, 2.571), stdev = 0.005
  CI (99.9%): [2.484, 2.649] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.780 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.454 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.428 ±(99.9%) 0.004 ms/op
Iteration   2: 2.432 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.439 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.428, 2.439, 2.459), stdev = 0.017
  CI (99.9%): [2.134, 2.744] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.984 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.551 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.502 ±(99.9%) 0.004 ms/op
Iteration   2: 2.470 ±(99.9%) 0.004 ms/op
Iteration   3: 2.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.484 ±(99.9%) 0.295 ms/op [Average]
  (min, avg, max) = (2.470, 2.484, 2.502), stdev = 0.016
  CI (99.9%): [2.189, 2.779] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.774 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.995 ±(99.9%) 0.005 ms/op
Iteration   1: 3.013 ±(99.9%) 0.005 ms/op
Iteration   2: 3.001 ±(99.9%) 0.004 ms/op
Iteration   3: 2.992 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.002 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (2.992, 3.002, 3.013), stdev = 0.011
  CI (99.9%): [2.803, 3.201] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.189 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.677 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 13.681 ms/op
                 createUser·p1.00:   14.795 ms/op

Iteration   2: 2.566 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.252 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  10.149 ms/op
                 createUser·p0.9999: 12.173 ms/op
                 createUser·p1.00:   12.419 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.970 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   3.957 ms/op
                 createUser·p0.999:  8.841 ms/op
                 createUser·p0.9999: 13.442 ms/op
                 createUser·p1.00:   13.697 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375744
  mean =      2.553 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 180509 
    [ 2.500,  3.750) = 190122 
    [ 3.750,  5.000) = 4048 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 82 
    [ 7.500,  8.750) = 71 
    [ 8.750, 10.000) = 104 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 125 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.970 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.240 ms/op
     p(99.0000) =      3.926 ms/op
     p(99.9000) =      9.585 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.151 ms/op
     p(99.9999) =     14.795 ms/op
    p(100.0000) =     14.795 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.484 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.005 ms/op
Iteration   1: 2.482 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.727 ms/op
                 existUser·p0.999:  8.478 ms/op
                 existUser·p0.9999: 18.718 ms/op
                 existUser·p1.00:   19.464 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.121 ms/op
                 existUser·p0.99:   3.482 ms/op
                 existUser·p0.999:  8.300 ms/op
                 existUser·p0.9999: 12.665 ms/op
                 existUser·p1.00:   13.697 ms/op

Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   2.576 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   4.053 ms/op
                 existUser·p0.999:  6.556 ms/op
                 existUser·p0.9999: 11.111 ms/op
                 existUser·p1.00:   11.600 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384994
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 32 
    [ 1.250,  2.500) = 187679 
    [ 2.500,  3.750) = 193285 
    [ 3.750,  5.000) = 2876 
    [ 5.000,  6.250) = 643 
    [ 6.250,  7.500) = 121 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 103 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 36 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.888 ms/op
     p(50.0000) =      2.576 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      7.053 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     19.277 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.627 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.533 ±(99.9%) 0.006 ms/op
Iteration   1: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.809 ms/op
                 getUser·p0.999:  11.518 ms/op
                 getUser·p0.9999: 13.815 ms/op
                 getUser·p1.00:   14.582 ms/op

Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  8.812 ms/op
                 getUser·p0.9999: 14.289 ms/op
                 getUser·p1.00:   14.778 ms/op

Iteration   3: 2.569 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.121 ms/op
                 getUser·p0.95:   3.305 ms/op
                 getUser·p0.99:   5.005 ms/op
                 getUser·p0.999:  9.299 ms/op
                 getUser·p0.9999: 13.002 ms/op
                 getUser·p1.00:   13.468 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 377633
  mean =      2.540 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 184306 
    [ 2.500,  3.750) = 186397 
    [ 3.750,  5.000) = 4958 
    [ 5.000,  6.250) = 1378 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 108 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.244 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      9.181 ms/op
     p(99.9900) =     13.783 ms/op
     p(99.9990) =     14.600 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.656 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.009 ms/op
Iteration   1: 3.002 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.634 ms/op
                 listUser·p0.9999: 12.082 ms/op
                 listUser·p1.00:   12.976 ms/op

Iteration   2: 3.008 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.603 ms/op
                 listUser·p0.999:  9.760 ms/op
                 listUser·p0.9999: 11.125 ms/op
                 listUser·p1.00:   12.042 ms/op

Iteration   3: 3.023 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.816 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  10.043 ms/op
                 listUser·p0.9999: 12.018 ms/op
                 listUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318545
  mean =      3.011 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 92553 
    [ 2.500,  3.750) = 186749 
    [ 3.750,  5.000) = 31602 
    [ 5.000,  6.250) = 6100 
    [ 6.250,  7.500) = 689 
    [ 7.500,  8.750) = 167 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 216 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.838 ms/op
     p(99.9900) =     11.881 ms/op
     p(99.9990) =     12.866 ms/op
     p(99.9999) =     12.976 ms/op
    p(100.0000) =     12.976 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.739 ± 0.988  ops/ms
ClientPb.existUser                       thrpt       3  13.027 ± 0.937  ops/ms
ClientPb.getUser                         thrpt       3  12.901 ± 0.923  ops/ms
ClientPb.listUser                        thrpt       3  10.566 ± 1.886  ops/ms
ClientPb.createUser                       avgt       3   2.566 ± 0.082   ms/op
ClientPb.existUser                        avgt       3   2.439 ± 0.305   ms/op
ClientPb.getUser                          avgt       3   2.484 ± 0.295   ms/op
ClientPb.listUser                         avgt       3   3.002 ± 0.199   ms/op
ClientPb.createUser                     sample  375744   2.553 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.970           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.240           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.926           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.585           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.550           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.795           ms/op
ClientPb.existUser                      sample  384994   2.491 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.888           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.576           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.023           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.464           ms/op
ClientPb.getUser                        sample  377633   2.540 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.088           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.181           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.783           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.778           ms/op
ClientPb.listUser                       sample  318545   3.011 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.743           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.838           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.881           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.976           ms/op
