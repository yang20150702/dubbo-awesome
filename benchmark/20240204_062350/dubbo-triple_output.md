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
# Warmup Iteration   1: 5.224 ops/ms
# Warmup Iteration   2: 12.075 ops/ms
# Warmup Iteration   3: 12.504 ops/ms
Iteration   1: 12.564 ops/ms
Iteration   2: 12.540 ops/ms
Iteration   3: 12.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.609 ±(99.9%) 1.820 ops/ms [Average]
  (min, avg, max) = (12.540, 12.609, 12.723), stdev = 0.100
  CI (99.9%): [10.789, 14.429] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.117 ops/ms
# Warmup Iteration   2: 12.889 ops/ms
# Warmup Iteration   3: 13.024 ops/ms
Iteration   1: 13.057 ops/ms
Iteration   2: 13.035 ops/ms
Iteration   3: 12.930 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.007 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (12.930, 13.007, 13.057), stdev = 0.068
  CI (99.9%): [11.771, 14.244] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.501 ops/ms
# Warmup Iteration   2: 12.727 ops/ms
# Warmup Iteration   3: 12.807 ops/ms
Iteration   1: 12.839 ops/ms
Iteration   2: 12.813 ops/ms
Iteration   3: 12.764 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.805 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (12.764, 12.805, 12.839), stdev = 0.038
  CI (99.9%): [12.117, 13.493] (assumes normal distribution)


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
# Warmup Iteration   1: 6.494 ops/ms
# Warmup Iteration   2: 10.506 ops/ms
# Warmup Iteration   3: 10.542 ops/ms
Iteration   1: 10.590 ops/ms
Iteration   2: 10.635 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.618 ±(99.9%) 0.438 ops/ms [Average]
  (min, avg, max) = (10.590, 10.618, 10.635), stdev = 0.024
  CI (99.9%): [10.180, 11.056] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.004 ms/op
Iteration   1: 2.558 ±(99.9%) 0.004 ms/op
Iteration   2: 2.567 ±(99.9%) 0.005 ms/op
Iteration   3: 2.525 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.550 ±(99.9%) 0.407 ms/op [Average]
  (min, avg, max) = (2.525, 2.550, 2.567), stdev = 0.022
  CI (99.9%): [2.143, 2.957] (assumes normal distribution)


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.413 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.439 ±(99.9%) 0.004 ms/op
Iteration   1: 2.445 ±(99.9%) 0.003 ms/op
Iteration   2: 2.437 ±(99.9%) 0.004 ms/op
Iteration   3: 2.422 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.435 ±(99.9%) 0.217 ms/op [Average]
  (min, avg, max) = (2.422, 2.435, 2.445), stdev = 0.012
  CI (99.9%): [2.218, 2.651] (assumes normal distribution)


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
# Warmup Iteration   1: 3.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.004 ms/op
Iteration   1: 2.522 ±(99.9%) 0.004 ms/op
Iteration   2: 2.489 ±(99.9%) 0.004 ms/op
Iteration   3: 2.484 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.379 ms/op [Average]
  (min, avg, max) = (2.484, 2.499, 2.522), stdev = 0.021
  CI (99.9%): [2.120, 2.877] (assumes normal distribution)


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
# Warmup Iteration   1: 4.542 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.005 ms/op
Iteration   1: 3.030 ±(99.9%) 0.004 ms/op
Iteration   2: 3.027 ±(99.9%) 0.005 ms/op
Iteration   3: 3.031 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.029 ±(99.9%) 0.042 ms/op [Average]
  (min, avg, max) = (3.027, 3.029, 3.031), stdev = 0.002
  CI (99.9%): [2.988, 3.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 2.610 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.539 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.617 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.617 ms/op
                 createUser·p0.999:  12.048 ms/op
                 createUser·p0.9999: 13.844 ms/op
                 createUser·p1.00:   14.615 ms/op

Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.934 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.248 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  10.131 ms/op
                 createUser·p0.9999: 12.446 ms/op
                 createUser·p1.00:   13.156 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.149 ms/op
                 createUser·p0.999:  8.589 ms/op
                 createUser·p0.9999: 12.313 ms/op
                 createUser·p1.00:   12.943 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376298
  mean =      2.548 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 180949 
    [ 2.500,  3.750) = 190158 
    [ 3.750,  5.000) = 4152 
    [ 5.000,  6.250) = 533 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 35 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 94 
    [12.500, 13.750) = 106 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      2.589 ms/op
     p(90.0000) =      3.101 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.928 ms/op
     p(99.9000) =      8.629 ms/op
     p(99.9900) =     13.474 ms/op
     p(99.9990) =     14.336 ms/op
     p(99.9999) =     14.615 ms/op
    p(100.0000) =     14.615 ms/op


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.518 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.502 ±(99.9%) 0.005 ms/op
Iteration   1: 2.508 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  11.863 ms/op
                 existUser·p0.9999: 13.914 ms/op
                 existUser·p1.00:   14.975 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.092 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.740 ms/op
                 existUser·p0.9999: 13.469 ms/op
                 existUser·p1.00:   14.336 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.669 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 12.632 ms/op
                 existUser·p1.00:   13.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384223
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 189351 
    [ 2.500,  3.750) = 191623 
    [ 3.750,  5.000) = 2343 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 76 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.138 ms/op
     p(99.0000) =      3.625 ms/op
     p(99.9000) =      6.534 ms/op
     p(99.9900) =     13.775 ms/op
     p(99.9990) =     14.664 ms/op
     p(99.9999) =     14.975 ms/op
    p(100.0000) =     14.975 ms/op


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.603 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.006 ms/op
Iteration   1: 2.497 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.796 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.146 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  10.611 ms/op
                 getUser·p0.9999: 15.519 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 2.523 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.004 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   3.752 ms/op
                 getUser·p0.999:  7.318 ms/op
                 getUser·p0.9999: 12.665 ms/op
                 getUser·p1.00:   13.206 ms/op

Iteration   3: 2.521 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   2.585 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.875 ms/op
                 getUser·p0.999:  8.634 ms/op
                 getUser·p0.9999: 11.993 ms/op
                 getUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 381600
  mean =      2.514 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 188366 
    [ 2.500,  3.750) = 189092 
    [ 3.750,  5.000) = 3154 
    [ 5.000,  6.250) = 438 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 29 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 72 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.789 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     13.468 ms/op
     p(99.9990) =     15.630 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.967 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.035 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.981 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.759 ms/op
                 listUser·p0.999:  8.847 ms/op
                 listUser·p0.9999: 10.288 ms/op
                 listUser·p1.00:   11.338 ms/op

Iteration   2: 3.025 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.887 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.693 ms/op
                 listUser·p0.999:  9.339 ms/op
                 listUser·p0.9999: 11.083 ms/op
                 listUser·p1.00:   11.895 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 11.075 ms/op
                 listUser·p1.00:   11.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 317037
  mean =      3.025 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 109 
    [ 1.250,  2.500) = 90117 
    [ 2.500,  3.750) = 187640 
    [ 3.750,  5.000) = 31587 
    [ 5.000,  6.250) = 6137 
    [ 6.250,  7.500) = 766 
    [ 7.500,  8.750) = 247 
    [ 8.750, 10.000) = 275 
    [10.000, 11.250) = 144 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.887 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.887 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =      9.306 ms/op
     p(99.9900) =     10.971 ms/op
     p(99.9990) =     11.695 ms/op
     p(99.9999) =     11.960 ms/op
    p(100.0000) =     11.960 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.609 ± 1.820  ops/ms
ClientPb.existUser                       thrpt       3  13.007 ± 1.236  ops/ms
ClientPb.getUser                         thrpt       3  12.805 ± 0.688  ops/ms
ClientPb.listUser                        thrpt       3  10.618 ± 0.438  ops/ms
ClientPb.createUser                       avgt       3   2.550 ± 0.407   ms/op
ClientPb.existUser                        avgt       3   2.435 ± 0.217   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.379   ms/op
ClientPb.listUser                         avgt       3   3.029 ± 0.042   ms/op
ClientPb.createUser                     sample  376298   2.548 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.653           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.589           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.101           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.629           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.474           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.615           ms/op
ClientPb.existUser                      sample  384223   2.497 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.928           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.775           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.975           ms/op
ClientPb.getUser                        sample  381600   2.514 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.759           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.060           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.789           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.373           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.468           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.663           ms/op
ClientPb.listUser                       sample  317037   3.025 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.887           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.887           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.661           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.306           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.971           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.960           ms/op
