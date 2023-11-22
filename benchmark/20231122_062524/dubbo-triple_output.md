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
# Warmup Iteration   1: 4.327 ops/ms
# Warmup Iteration   2: 11.599 ops/ms
# Warmup Iteration   3: 12.249 ops/ms
Iteration   1: 12.336 ops/ms
Iteration   2: 12.557 ops/ms
Iteration   3: 12.618 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.504 ±(99.9%) 2.708 ops/ms [Average]
  (min, avg, max) = (12.336, 12.504, 12.618), stdev = 0.148
  CI (99.9%): [9.796, 15.211] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.863 ops/ms
# Warmup Iteration   2: 12.616 ops/ms
# Warmup Iteration   3: 12.739 ops/ms
Iteration   1: 12.801 ops/ms
Iteration   2: 12.894 ops/ms
Iteration   3: 12.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.834 ±(99.9%) 0.948 ops/ms [Average]
  (min, avg, max) = (12.801, 12.834, 12.894), stdev = 0.052
  CI (99.9%): [11.886, 13.782] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.594 ops/ms
# Warmup Iteration   2: 12.479 ops/ms
# Warmup Iteration   3: 12.421 ops/ms
Iteration   1: 12.759 ops/ms
Iteration   2: 12.758 ops/ms
Iteration   3: 12.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.740 ±(99.9%) 0.576 ops/ms [Average]
  (min, avg, max) = (12.704, 12.740, 12.759), stdev = 0.032
  CI (99.9%): [12.165, 13.316] (assumes normal distribution)


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
# Warmup Iteration   1: 6.362 ops/ms
# Warmup Iteration   2: 10.362 ops/ms
# Warmup Iteration   3: 10.433 ops/ms
Iteration   1: 10.565 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.730 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.609 ±(99.9%) 1.932 ops/ms [Average]
  (min, avg, max) = (10.533, 10.609, 10.730), stdev = 0.106
  CI (99.9%): [8.678, 12.541] (assumes normal distribution)


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
# Warmup Iteration   1: 4.048 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.656 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.572 ±(99.9%) 0.005 ms/op
Iteration   1: 2.574 ±(99.9%) 0.004 ms/op
Iteration   2: 2.645 ±(99.9%) 0.003 ms/op
Iteration   3: 2.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.599 ±(99.9%) 0.730 ms/op [Average]
  (min, avg, max) = (2.574, 2.599, 2.645), stdev = 0.040
  CI (99.9%): [1.869, 3.329] (assumes normal distribution)


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
# Warmup Iteration   1: 3.833 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.003 ms/op
Iteration   1: 2.519 ±(99.9%) 0.004 ms/op
Iteration   2: 2.495 ±(99.9%) 0.004 ms/op
Iteration   3: 2.503 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.506 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.495, 2.506, 2.519), stdev = 0.012
  CI (99.9%): [2.283, 2.728] (assumes normal distribution)


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
# Warmup Iteration   1: 3.961 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.609 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.003 ms/op
Iteration   1: 2.566 ±(99.9%) 0.006 ms/op
Iteration   2: 2.537 ±(99.9%) 0.006 ms/op
Iteration   3: 2.552 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.551 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.537, 2.551, 2.566), stdev = 0.014
  CI (99.9%): [2.289, 2.814] (assumes normal distribution)


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
# Warmup Iteration   1: 4.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.004 ms/op
Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
Iteration   3: 3.014 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.020 ±(99.9%) 0.198 ms/op [Average]
  (min, avg, max) = (3.014, 3.020, 3.033), stdev = 0.011
  CI (99.9%): [2.822, 3.218] (assumes normal distribution)


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.562 ±(99.9%) 0.006 ms/op
Iteration   1: 2.522 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.023 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.858 ms/op
                 createUser·p0.999:  11.518 ms/op
                 createUser·p0.9999: 14.265 ms/op
                 createUser·p1.00:   14.451 ms/op

Iteration   2: 2.509 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.645 ms/op
                 createUser·p0.999:  10.447 ms/op
                 createUser·p0.9999: 14.090 ms/op
                 createUser·p1.00:   14.287 ms/op

Iteration   3: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  8.485 ms/op
                 createUser·p0.9999: 10.846 ms/op
                 createUser·p1.00:   11.780 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380761
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 182552 
    [ 2.500,  3.750) = 193436 
    [ 3.750,  5.000) = 3731 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 112 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.052 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      8.511 ms/op
     p(99.9900) =     14.008 ms/op
     p(99.9990) =     14.385 ms/op
     p(99.9999) =     14.451 ms/op
    p(100.0000) =     14.451 ms/op


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
# Warmup Iteration   1: 3.816 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.583 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
Iteration   1: 2.528 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.597 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.187 ms/op
                 existUser·p0.99:   3.724 ms/op
                 existUser·p0.999:  12.124 ms/op
                 existUser·p0.9999: 14.145 ms/op
                 existUser·p1.00:   14.942 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.069 ms/op
                 existUser·p0.50:   2.564 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.719 ms/op
                 existUser·p0.999:  5.764 ms/op
                 existUser·p0.9999: 11.996 ms/op
                 existUser·p1.00:   12.403 ms/op

Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.038 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.813 ms/op
                 existUser·p0.999:  9.114 ms/op
                 existUser·p0.9999: 13.909 ms/op
                 existUser·p1.00:   14.434 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382528
  mean =      2.507 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 185969 
    [ 2.500,  3.750) = 192707 
    [ 3.750,  5.000) = 2890 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 102 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.748 ms/op
     p(99.9000) =      6.896 ms/op
     p(99.9900) =     13.566 ms/op
     p(99.9990) =     14.866 ms/op
     p(99.9999) =     14.942 ms/op
    p(100.0000) =     14.942 ms/op


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
# Warmup Iteration   1: 3.938 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.608 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.553 ±(99.9%) 0.006 ms/op
Iteration   1: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.540 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.170 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  12.016 ms/op
                 getUser·p0.9999: 14.369 ms/op
                 getUser·p1.00:   15.155 ms/op

Iteration   2: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   2.572 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.228 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 15.061 ms/op
                 getUser·p1.00:   15.647 ms/op

Iteration   3: 2.551 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.035 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.101 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.752 ms/op
                 getUser·p0.999:  9.503 ms/op
                 getUser·p0.9999: 11.008 ms/op
                 getUser·p1.00:   12.321 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378494
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 184541 
    [ 2.500,  3.750) = 187365 
    [ 3.750,  5.000) = 4875 
    [ 5.000,  6.250) = 1113 
    [ 6.250,  7.500) = 113 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      9.503 ms/op
     p(99.9900) =     14.355 ms/op
     p(99.9990) =     15.284 ms/op
     p(99.9999) =     15.647 ms/op
    p(100.0000) =     15.647 ms/op


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
# Warmup Iteration   1: 4.724 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.573 ms/op
                 listUser·p0.999:  9.111 ms/op
                 listUser·p0.9999: 11.213 ms/op
                 listUser·p1.00:   11.485 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.748 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.847 ms/op
                 listUser·p0.9999: 11.641 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   3: 3.033 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.820 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.306 ms/op
                 listUser·p0.9999: 11.960 ms/op
                 listUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317802
  mean =      3.018 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 92006 
    [ 2.500,  3.750) = 185109 
    [ 3.750,  5.000) = 33238 
    [ 5.000,  6.250) = 5999 
    [ 6.250,  7.500) = 640 
    [ 7.500,  8.750) = 231 
    [ 8.750, 10.000) = 224 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.636 ms/op
     p(99.9990) =     12.819 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.504 ± 2.708  ops/ms
ClientPb.existUser                       thrpt       3  12.834 ± 0.948  ops/ms
ClientPb.getUser                         thrpt       3  12.740 ± 0.576  ops/ms
ClientPb.listUser                        thrpt       3  10.609 ± 1.932  ops/ms
ClientPb.createUser                       avgt       3   2.599 ± 0.730   ms/op
ClientPb.existUser                        avgt       3   2.506 ± 0.223   ms/op
ClientPb.getUser                          avgt       3   2.551 ± 0.263   ms/op
ClientPb.listUser                         avgt       3   3.020 ± 0.198   ms/op
ClientPb.createUser                     sample  380761   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.052           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.511           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.008           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.451           ms/op
ClientPb.existUser                      sample  382528   2.507 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.028           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.748           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.896           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.566           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.942           ms/op
ClientPb.getUser                        sample  378494   2.534 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.902           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.560           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.503           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.355           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.647           ms/op
ClientPb.listUser                       sample  317802   3.018 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.748           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.920           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.636           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
