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
# Warmup Iteration   1: 4.705 ops/ms
# Warmup Iteration   2: 11.998 ops/ms
# Warmup Iteration   3: 12.213 ops/ms
Iteration   1: 12.484 ops/ms
Iteration   2: 12.543 ops/ms
Iteration   3: 12.503 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.510 ±(99.9%) 0.542 ops/ms [Average]
  (min, avg, max) = (12.484, 12.510, 12.543), stdev = 0.030
  CI (99.9%): [11.968, 13.052] (assumes normal distribution)


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
# Warmup Iteration   1: 8.048 ops/ms
# Warmup Iteration   2: 12.994 ops/ms
# Warmup Iteration   3: 13.041 ops/ms
Iteration   1: 13.056 ops/ms
Iteration   2: 13.113 ops/ms
Iteration   3: 13.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.092 ±(99.9%) 0.567 ops/ms [Average]
  (min, avg, max) = (13.056, 13.092, 13.113), stdev = 0.031
  CI (99.9%): [12.524, 13.659] (assumes normal distribution)


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
# Warmup Iteration   1: 7.557 ops/ms
# Warmup Iteration   2: 12.573 ops/ms
# Warmup Iteration   3: 12.681 ops/ms
Iteration   1: 12.758 ops/ms
Iteration   2: 12.796 ops/ms
Iteration   3: 12.787 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.780 ±(99.9%) 0.361 ops/ms [Average]
  (min, avg, max) = (12.758, 12.780, 12.796), stdev = 0.020
  CI (99.9%): [12.420, 13.141] (assumes normal distribution)


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
# Warmup Iteration   1: 6.624 ops/ms
# Warmup Iteration   2: 10.369 ops/ms
# Warmup Iteration   3: 10.550 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.747 ops/ms
Iteration   3: 10.681 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.715 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (10.681, 10.715, 10.747), stdev = 0.033
  CI (99.9%): [10.119, 11.312] (assumes normal distribution)


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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.004 ms/op
Iteration   1: 2.545 ±(99.9%) 0.005 ms/op
Iteration   2: 2.492 ±(99.9%) 0.004 ms/op
Iteration   3: 2.508 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.515 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (2.492, 2.515, 2.545), stdev = 0.027
  CI (99.9%): [2.015, 3.015] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.467 ±(99.9%) 0.003 ms/op
Iteration   1: 2.474 ±(99.9%) 0.005 ms/op
Iteration   2: 2.496 ±(99.9%) 0.004 ms/op
Iteration   3: 2.500 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.490 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (2.474, 2.490, 2.500), stdev = 0.014
  CI (99.9%): [2.232, 2.748] (assumes normal distribution)


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.612 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.517 ±(99.9%) 0.004 ms/op
Iteration   1: 2.503 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.004 ms/op
Iteration   3: 2.519 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.514 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.503, 2.514, 2.521), stdev = 0.010
  CI (99.9%): [2.336, 2.693] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.644 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.005 ms/op
Iteration   1: 3.018 ±(99.9%) 0.006 ms/op
Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
Iteration   3: 3.024 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.362 ms/op [Average]
  (min, avg, max) = (2.987, 3.009, 3.024), stdev = 0.020
  CI (99.9%): [2.648, 3.371] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.619 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.506 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.047 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  12.118 ms/op
                 createUser·p0.9999: 13.898 ms/op
                 createUser·p1.00:   14.320 ms/op

Iteration   2: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.662 ms/op
                 createUser·p0.999:  7.675 ms/op
                 createUser·p0.9999: 13.267 ms/op
                 createUser·p1.00:   13.730 ms/op

Iteration   3: 2.508 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.883 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  8.431 ms/op
                 createUser·p0.9999: 12.018 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383023
  mean =      2.503 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 40 
    [ 1.250,  2.500) = 185289 
    [ 2.500,  3.750) = 193670 
    [ 3.750,  5.000) = 3162 
    [ 5.000,  6.250) = 426 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 43 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 116 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      2.568 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      8.437 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.260 ms/op
     p(99.9999) =     14.320 ms/op
    p(100.0000) =     14.320 ms/op


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
# Warmup Iteration   1: 3.750 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.507 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.698 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  6.373 ms/op
                 existUser·p0.9999: 14.172 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.053 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  7.555 ms/op
                 existUser·p0.9999: 18.935 ms/op
                 existUser·p1.00:   19.792 ms/op

Iteration   3: 2.433 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.842 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.629 ms/op
                 existUser·p0.999:  5.675 ms/op
                 existUser·p0.9999: 11.827 ms/op
                 existUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 394153
  mean =      2.433 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 61 
    [ 1.250,  2.500) = 199398 
    [ 2.500,  3.750) = 191552 
    [ 3.750,  5.000) = 2414 
    [ 5.000,  6.250) = 338 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 111 
    [12.500, 13.750) = 100 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      2.474 ms/op
     p(90.0000) =      2.957 ms/op
     p(95.0000) =      3.068 ms/op
     p(99.0000) =      3.610 ms/op
     p(99.9000) =      6.167 ms/op
     p(99.9900) =     14.250 ms/op
     p(99.9990) =     19.377 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.893 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.592 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.006 ms/op
Iteration   1: 2.459 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.869 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.092 ms/op
                 getUser·p0.99:   3.592 ms/op
                 getUser·p0.999:  7.594 ms/op
                 getUser·p0.9999: 13.795 ms/op
                 getUser·p1.00:   14.483 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   4.139 ms/op
                 getUser·p0.999:  6.169 ms/op
                 getUser·p0.9999: 12.848 ms/op
                 getUser·p1.00:   13.124 ms/op

Iteration   3: 2.473 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.001 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.727 ms/op
                 getUser·p0.999:  6.410 ms/op
                 getUser·p0.9999: 14.074 ms/op
                 getUser·p1.00:   15.073 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 387712
  mean =      2.474 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 71 
    [ 1.250,  2.500) = 194115 
    [ 2.500,  3.750) = 189487 
    [ 3.750,  5.000) = 2982 
    [ 5.000,  6.250) = 645 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 54 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      6.537 ms/op
     p(99.9900) =     13.550 ms/op
     p(99.9990) =     14.520 ms/op
     p(99.9999) =     15.073 ms/op
    p(100.0000) =     15.073 ms/op


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
# Warmup Iteration   1: 4.779 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.009 ms/op
Iteration   1: 3.037 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.662 ms/op
                 listUser·p0.9999: 13.410 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   2: 3.004 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.863 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 13.523 ms/op
                 listUser·p1.00:   14.107 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.859 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.164 ms/op
                 listUser·p0.9999: 11.687 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317337
  mean =      3.022 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 90561 
    [ 2.500,  3.750) = 186834 
    [ 3.750,  5.000) = 32459 
    [ 5.000,  6.250) = 5910 
    [ 6.250,  7.500) = 771 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 243 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 72 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     13.275 ms/op
     p(99.9990) =     14.101 ms/op
     p(99.9999) =     14.385 ms/op
    p(100.0000) =     14.385 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.510 ± 0.542  ops/ms
ClientPb.existUser                       thrpt       3  13.092 ± 0.567  ops/ms
ClientPb.getUser                         thrpt       3  12.780 ± 0.361  ops/ms
ClientPb.listUser                        thrpt       3  10.715 ± 0.597  ops/ms
ClientPb.createUser                       avgt       3   2.515 ± 0.500   ms/op
ClientPb.existUser                        avgt       3   2.490 ± 0.258   ms/op
ClientPb.getUser                          avgt       3   2.514 ± 0.178   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.362   ms/op
ClientPb.createUser                     sample  383023   2.503 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.883           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.568           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.437           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.435           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.320           ms/op
ClientPb.existUser                      sample  394153   2.433 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.698           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.474           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.957           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.068           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.610           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.167           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.250           ms/op
ClientPb.existUser:existUser·p1.00      sample          19.792           ms/op
ClientPb.getUser                        sample  387712   2.474 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.869           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.537           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.073           ms/op
ClientPb.listUser                       sample  317337   3.022 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.802           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.957           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.903           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.652           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.275           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.385           ms/op
