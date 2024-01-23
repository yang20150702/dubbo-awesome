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
# Warmup Iteration   1: 5.348 ops/ms
# Warmup Iteration   2: 12.132 ops/ms
# Warmup Iteration   3: 12.534 ops/ms
Iteration   1: 12.653 ops/ms
Iteration   2: 12.920 ops/ms
Iteration   3: 12.790 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.788 ±(99.9%) 2.434 ops/ms [Average]
  (min, avg, max) = (12.653, 12.788, 12.920), stdev = 0.133
  CI (99.9%): [10.354, 15.222] (assumes normal distribution)


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
# Warmup Iteration   1: 8.437 ops/ms
# Warmup Iteration   2: 12.958 ops/ms
# Warmup Iteration   3: 12.977 ops/ms
Iteration   1: 12.915 ops/ms
Iteration   2: 13.046 ops/ms
Iteration   3: 12.921 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.960 ±(99.9%) 1.351 ops/ms [Average]
  (min, avg, max) = (12.915, 12.960, 13.046), stdev = 0.074
  CI (99.9%): [11.610, 14.311] (assumes normal distribution)


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
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.469 ops/ms
# Warmup Iteration   3: 12.769 ops/ms
Iteration   1: 12.909 ops/ms
Iteration   2: 13.029 ops/ms
Iteration   3: 12.833 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.924 ±(99.9%) 1.802 ops/ms [Average]
  (min, avg, max) = (12.833, 12.924, 13.029), stdev = 0.099
  CI (99.9%): [11.122, 14.726] (assumes normal distribution)


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
# Warmup Iteration   1: 6.717 ops/ms
# Warmup Iteration   2: 10.532 ops/ms
# Warmup Iteration   3: 10.558 ops/ms
Iteration   1: 10.699 ops/ms
Iteration   2: 10.736 ops/ms
Iteration   3: 10.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.707 ±(99.9%) 0.473 ops/ms [Average]
  (min, avg, max) = (10.686, 10.707, 10.736), stdev = 0.026
  CI (99.9%): [10.235, 11.180] (assumes normal distribution)


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
# Warmup Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.515 ±(99.9%) 0.003 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.521 ±(99.9%) 0.003 ms/op
Iteration   3: 2.510 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.526 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.510, 2.526, 2.547), stdev = 0.019
  CI (99.9%): [2.185, 2.867] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.775 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.004 ms/op
Iteration   1: 2.463 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.479 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.463, 2.479, 2.497), stdev = 0.017
  CI (99.9%): [2.167, 2.790] (assumes normal distribution)


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
# Warmup Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.537 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
Iteration   1: 2.480 ±(99.9%) 0.004 ms/op
Iteration   2: 2.490 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.492 ±(99.9%) 0.231 ms/op [Average]
  (min, avg, max) = (2.480, 2.492, 2.505), stdev = 0.013
  CI (99.9%): [2.261, 2.722] (assumes normal distribution)


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
# Warmup Iteration   1: 4.633 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.022 ±(99.9%) 0.005 ms/op
Iteration   2: 3.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.012 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.012 ±(99.9%) 0.180 ms/op [Average]
  (min, avg, max) = (3.002, 3.012, 3.022), stdev = 0.010
  CI (99.9%): [2.832, 3.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.260 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.636 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.533 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.088 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   3.711 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 13.599 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.817 ms/op
                 createUser·p0.999:  8.991 ms/op
                 createUser·p0.9999: 12.681 ms/op
                 createUser·p1.00:   13.926 ms/op

Iteration   3: 2.558 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.256 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  8.458 ms/op
                 createUser·p0.9999: 17.826 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378388
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 181807 
    [ 2.500,  3.750) = 191641 
    [ 3.750,  5.000) = 3892 
    [ 5.000,  6.250) = 529 
    [ 6.250,  7.500) = 56 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 101 
    [10.000, 11.250) = 87 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.912 ms/op
     p(99.9000) =      8.699 ms/op
     p(99.9900) =     13.681 ms/op
     p(99.9990) =     17.964 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.705 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.509 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.494 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.174 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.128 ms/op
                 existUser·p0.99:   3.874 ms/op
                 existUser·p0.999:  10.459 ms/op
                 existUser·p0.9999: 16.777 ms/op
                 existUser·p1.00:   17.596 ms/op

Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.621 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  5.387 ms/op
                 existUser·p0.9999: 13.539 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.009 ms/op
                 existUser·p0.50:   2.593 ms/op
                 existUser·p0.90:   3.076 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.568 ms/op
                 existUser·p0.9999: 12.435 ms/op
                 existUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382454
  mean =      2.508 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 185001 
    [ 2.500,  3.750) = 192321 
    [ 3.750,  5.000) = 3832 
    [ 5.000,  6.250) = 857 
    [ 6.250,  7.500) = 52 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.031 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.998 ms/op
     p(99.9000) =      6.453 ms/op
     p(99.9900) =     15.946 ms/op
     p(99.9990) =     17.097 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.907 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.593 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.511 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.031 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.699 ms/op
                 getUser·p0.999:  11.375 ms/op
                 getUser·p0.9999: 13.599 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.564 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.980 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.117 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  10.065 ms/op
                 getUser·p0.9999: 13.231 ms/op
                 getUser·p1.00:   13.926 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.064 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.723 ms/op
                 getUser·p0.999:  7.926 ms/op
                 getUser·p0.9999: 12.132 ms/op
                 getUser·p1.00:   12.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379548
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 186322 
    [ 2.500,  3.750) = 187885 
    [ 3.750,  5.000) = 3970 
    [ 5.000,  6.250) = 817 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 126 
    [12.500, 13.750) = 119 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.994 ms/op
     p(99.9000) =      8.609 ms/op
     p(99.9900) =     13.223 ms/op
     p(99.9990) =     14.100 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.634 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.100 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.008 ms/op
Iteration   1: 3.021 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.923 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.867 ms/op
                 listUser·p0.9999: 10.280 ms/op
                 listUser·p1.00:   11.076 ms/op

Iteration   2: 3.028 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.055 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.116 ms/op
                 listUser·p0.9999: 11.551 ms/op
                 listUser·p1.00:   11.944 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   2.941 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.438 ms/op
                 listUser·p0.999:  9.159 ms/op
                 listUser·p0.9999: 11.015 ms/op
                 listUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 318248
  mean =      3.014 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 111 
    [ 1.250,  2.500) = 89836 
    [ 2.500,  3.750) = 189705 
    [ 3.750,  5.000) = 31936 
    [ 5.000,  6.250) = 5349 
    [ 6.250,  7.500) = 646 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 269 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     11.259 ms/op
     p(99.9990) =     11.831 ms/op
     p(99.9999) =     11.944 ms/op
    p(100.0000) =     11.944 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.788 ± 2.434  ops/ms
ClientPb.existUser                       thrpt       3  12.960 ± 1.351  ops/ms
ClientPb.getUser                         thrpt       3  12.924 ± 1.802  ops/ms
ClientPb.listUser                        thrpt       3  10.707 ± 0.473  ops/ms
ClientPb.createUser                       avgt       3   2.526 ± 0.341   ms/op
ClientPb.existUser                        avgt       3   2.479 ± 0.312   ms/op
ClientPb.getUser                          avgt       3   2.492 ± 0.231   ms/op
ClientPb.listUser                         avgt       3   3.012 ± 0.180   ms/op
ClientPb.createUser                     sample  378388   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.817           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.912           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.699           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.681           ms/op
ClientPb.createUser:createUser·p1.00    sample          17.990           ms/op
ClientPb.existUser                      sample  382454   2.508 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.824           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.593           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.031           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.453           ms/op
ClientPb.existUser:existUser·p0.9999    sample          15.946           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.596           ms/op
ClientPb.getUser                        sample  379548   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.804           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.548           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.609           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.223           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  318248   3.014 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.923           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.953           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.060           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.259           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.944           ms/op
