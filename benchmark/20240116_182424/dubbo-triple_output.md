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
# Warmup Iteration   1: 4.721 ops/ms
# Warmup Iteration   2: 11.680 ops/ms
# Warmup Iteration   3: 12.241 ops/ms
Iteration   1: 12.511 ops/ms
Iteration   2: 12.204 ops/ms
Iteration   3: 12.374 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.363 ±(99.9%) 2.806 ops/ms [Average]
  (min, avg, max) = (12.204, 12.363, 12.511), stdev = 0.154
  CI (99.9%): [9.557, 15.169] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.036 ops/ms
# Warmup Iteration   2: 12.851 ops/ms
# Warmup Iteration   3: 13.012 ops/ms
Iteration   1: 12.983 ops/ms
Iteration   2: 13.066 ops/ms
Iteration   3: 12.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.961 ±(99.9%) 2.138 ops/ms [Average]
  (min, avg, max) = (12.834, 12.961, 13.066), stdev = 0.117
  CI (99.9%): [10.823, 15.099] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.731 ops/ms
# Warmup Iteration   2: 12.633 ops/ms
# Warmup Iteration   3: 12.763 ops/ms
Iteration   1: 12.853 ops/ms
Iteration   2: 13.009 ops/ms
Iteration   3: 12.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.824 ±(99.9%) 3.648 ops/ms [Average]
  (min, avg, max) = (12.612, 12.824, 13.009), stdev = 0.200
  CI (99.9%): [9.176, 16.472] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.749 ops/ms
# Warmup Iteration   2: 10.439 ops/ms
# Warmup Iteration   3: 10.719 ops/ms
Iteration   1: 10.794 ops/ms
Iteration   2: 10.785 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.778 ±(99.9%) 0.374 ops/ms [Average]
  (min, avg, max) = (10.755, 10.778, 10.794), stdev = 0.021
  CI (99.9%): [10.404, 11.152] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.070 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.557 ±(99.9%) 0.004 ms/op
Iteration   1: 2.569 ±(99.9%) 0.004 ms/op
Iteration   2: 2.602 ±(99.9%) 0.004 ms/op
Iteration   3: 2.609 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.593 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.569, 2.593, 2.609), stdev = 0.021
  CI (99.9%): [2.212, 2.974] (assumes normal distribution)


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
# Warmup Iteration   1: 3.829 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.004 ms/op
Iteration   1: 2.464 ±(99.9%) 0.004 ms/op
Iteration   2: 2.451 ±(99.9%) 0.003 ms/op
Iteration   3: 2.461 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.458 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.451, 2.458, 2.464), stdev = 0.007
  CI (99.9%): [2.340, 2.577] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.565 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.493 ±(99.9%) 0.004 ms/op
Iteration   1: 2.469 ±(99.9%) 0.004 ms/op
Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
Iteration   3: 2.487 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.493 ±(99.9%) 0.510 ms/op [Average]
  (min, avg, max) = (2.469, 2.493, 2.524), stdev = 0.028
  CI (99.9%): [1.983, 3.003] (assumes normal distribution)


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
# Warmup Iteration   1: 4.609 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.021 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
Iteration   2: 2.997 ±(99.9%) 0.005 ms/op
Iteration   3: 3.006 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.998 ±(99.9%) 0.119 ms/op [Average]
  (min, avg, max) = (2.993, 2.998, 3.006), stdev = 0.007
  CI (99.9%): [2.879, 3.118] (assumes normal distribution)


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
# Warmup Iteration   1: 4.153 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.666 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.532 ±(99.9%) 0.005 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.841 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   4.009 ms/op
                 createUser·p0.999:  11.033 ms/op
                 createUser·p0.9999: 13.999 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.536 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  9.466 ms/op
                 createUser·p0.9999: 12.350 ms/op
                 createUser·p1.00:   13.042 ms/op

Iteration   3: 2.562 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.029 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.228 ms/op
                 createUser·p0.99:   3.863 ms/op
                 createUser·p0.999:  8.970 ms/op
                 createUser·p0.9999: 10.519 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376505
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 181307 
    [ 2.500,  3.750) = 190795 
    [ 3.750,  5.000) = 3286 
    [ 5.000,  6.250) = 559 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      2.597 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      3.834 ms/op
     p(99.9000) =      9.052 ms/op
     p(99.9900) =     13.320 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.536 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.489 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.981 ms/op
                 existUser·p0.50:   2.503 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  9.195 ms/op
                 existUser·p0.9999: 20.447 ms/op
                 existUser·p1.00:   21.168 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.467 ms/op
                 existUser·p0.999:  5.968 ms/op
                 existUser·p0.9999: 12.731 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   3: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.014 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.101 ms/op
                 existUser·p0.99:   3.510 ms/op
                 existUser·p0.999:  5.399 ms/op
                 existUser·p0.9999: 15.237 ms/op
                 existUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388314
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 193910 
    [ 2.500,  5.000) = 193766 
    [ 5.000,  7.500) = 284 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.580 ms/op
     p(99.9000) =      5.724 ms/op
     p(99.9900) =     15.418 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.551 ±(99.9%) 0.005 ms/op
Iteration   1: 2.547 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.240 ms/op
                 getUser·p0.99:   3.887 ms/op
                 getUser·p0.999:  11.575 ms/op
                 getUser·p0.9999: 15.581 ms/op
                 getUser·p1.00:   16.564 ms/op

Iteration   2: 2.551 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.740 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.109 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  9.546 ms/op
                 getUser·p0.9999: 12.131 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   3: 2.548 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.926 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.105 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  5.685 ms/op
                 getUser·p0.9999: 12.820 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 376357
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 183469 
    [ 2.500,  3.750) = 188086 
    [ 3.750,  5.000) = 3883 
    [ 5.000,  6.250) = 468 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.572 ms/op
     p(90.0000) =      3.105 ms/op
     p(95.0000) =      3.228 ms/op
     p(99.0000) =      3.895 ms/op
     p(99.9000) =      6.275 ms/op
     p(99.9900) =     13.064 ms/op
     p(99.9990) =     16.339 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 4.759 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.009 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.929 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.875 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 11.420 ms/op
                 listUser·p1.00:   13.173 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.949 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.692 ms/op
                 listUser·p1.00:   11.321 ms/op

Iteration   3: 2.973 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.770 ms/op
                 listUser·p0.50:   2.912 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.546 ms/op
                 listUser·p0.999:  8.674 ms/op
                 listUser·p0.9999: 13.660 ms/op
                 listUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321358
  mean =      2.985 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 98691 
    [ 2.500,  3.750) = 184355 
    [ 3.750,  5.000) = 30952 
    [ 5.000,  6.250) = 5902 
    [ 6.250,  7.500) = 674 
    [ 7.500,  8.750) = 226 
    [ 8.750, 10.000) = 294 
    [10.000, 11.250) = 110 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.770 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.579 ms/op
     p(99.9000) =      9.218 ms/op
     p(99.9900) =     11.420 ms/op
     p(99.9990) =     13.850 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.363 ± 2.806  ops/ms
ClientPb.existUser                       thrpt       3  12.961 ± 2.138  ops/ms
ClientPb.getUser                         thrpt       3  12.824 ± 3.648  ops/ms
ClientPb.listUser                        thrpt       3  10.778 ± 0.374  ops/ms
ClientPb.createUser                       avgt       3   2.593 ± 0.381   ms/op
ClientPb.existUser                        avgt       3   2.458 ± 0.119   ms/op
ClientPb.getUser                          avgt       3   2.493 ± 0.510   ms/op
ClientPb.listUser                         avgt       3   2.998 ± 0.119   ms/op
ClientPb.createUser                     sample  376505   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.837           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.597           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.215           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.320           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  388314   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.724           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.418           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.168           ms/op
ClientPb.getUser                        sample  376357   2.548 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.635           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.572           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.228           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.895           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.275           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.064           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.564           ms/op
ClientPb.listUser                       sample  321358   2.985 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.770           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.218           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.420           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.926           ms/op
