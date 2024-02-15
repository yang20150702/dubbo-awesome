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
# Warmup Iteration   1: 5.248 ops/ms
# Warmup Iteration   2: 11.867 ops/ms
# Warmup Iteration   3: 12.260 ops/ms
Iteration   1: 12.434 ops/ms
Iteration   2: 12.513 ops/ms
Iteration   3: 12.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.490 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (12.434, 12.490, 12.522), stdev = 0.049
  CI (99.9%): [11.602, 13.377] (assumes normal distribution)


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
# Warmup Iteration   1: 8.500 ops/ms
# Warmup Iteration   2: 12.886 ops/ms
# Warmup Iteration   3: 12.963 ops/ms
Iteration   1: 12.927 ops/ms
Iteration   2: 13.349 ops/ms
Iteration   3: 13.067 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.114 ±(99.9%) 3.926 ops/ms [Average]
  (min, avg, max) = (12.927, 13.114, 13.349), stdev = 0.215
  CI (99.9%): [9.189, 17.040] (assumes normal distribution)


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
# Warmup Iteration   1: 7.801 ops/ms
# Warmup Iteration   2: 12.552 ops/ms
# Warmup Iteration   3: 12.887 ops/ms
Iteration   1: 12.965 ops/ms
Iteration   2: 12.916 ops/ms
Iteration   3: 12.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.897 ±(99.9%) 1.438 ops/ms [Average]
  (min, avg, max) = (12.810, 12.897, 12.965), stdev = 0.079
  CI (99.9%): [11.459, 14.335] (assumes normal distribution)


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
# Warmup Iteration   1: 6.658 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.483 ops/ms
Iteration   2: 10.474 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.497 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (10.474, 10.497, 10.533), stdev = 0.032
  CI (99.9%): [9.921, 11.072] (assumes normal distribution)


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
# Warmup Iteration   1: 3.870 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.568 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.004 ms/op
Iteration   1: 2.546 ±(99.9%) 0.004 ms/op
Iteration   2: 2.520 ±(99.9%) 0.003 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.534 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.520, 2.534, 2.546), stdev = 0.013
  CI (99.9%): [2.290, 2.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.497 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.460 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
Iteration   2: 2.456 ±(99.9%) 0.005 ms/op
Iteration   3: 2.432 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.443 ±(99.9%) 0.225 ms/op [Average]
  (min, avg, max) = (2.432, 2.443, 2.456), stdev = 0.012
  CI (99.9%): [2.218, 2.669] (assumes normal distribution)


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.508 ±(99.9%) 0.004 ms/op
Iteration   1: 2.507 ±(99.9%) 0.004 ms/op
Iteration   2: 2.492 ±(99.9%) 0.005 ms/op
Iteration   3: 2.497 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.492, 2.499, 2.507), stdev = 0.008
  CI (99.9%): [2.360, 2.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.005 ms/op
Iteration   1: 3.051 ±(99.9%) 0.004 ms/op
Iteration   2: 3.052 ±(99.9%) 0.006 ms/op
Iteration   3: 3.046 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.050 ±(99.9%) 0.051 ms/op [Average]
  (min, avg, max) = (3.046, 3.050, 3.052), stdev = 0.003
  CI (99.9%): [2.999, 3.100] (assumes normal distribution)


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
# Warmup Iteration   1: 4.203 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.584 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   2.613 ms/op
                 createUser·p0.90:   3.092 ms/op
                 createUser·p0.95:   3.195 ms/op
                 createUser·p0.99:   3.682 ms/op
                 createUser·p0.999:  11.266 ms/op
                 createUser·p0.9999: 13.253 ms/op
                 createUser·p1.00:   14.057 ms/op

Iteration   2: 2.554 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.224 ms/op
                 createUser·p0.99:   3.658 ms/op
                 createUser·p0.999:  9.454 ms/op
                 createUser·p0.9999: 12.443 ms/op
                 createUser·p1.00:   13.648 ms/op

Iteration   3: 2.550 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.501 ms/op
                 createUser·p0.50:   2.666 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.736 ms/op
                 createUser·p0.999:  9.322 ms/op
                 createUser·p0.9999: 14.852 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 375898
  mean =      2.551 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 47 
    [ 1.250,  2.500) = 179359 
    [ 2.500,  3.750) = 193156 
    [ 3.750,  5.000) = 2520 
    [ 5.000,  6.250) = 282 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 50 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 104 
    [11.250, 12.500) = 112 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.621 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.199 ms/op
     p(99.0000) =      3.686 ms/op
     p(99.9000) =      9.355 ms/op
     p(99.9900) =     13.638 ms/op
     p(99.9990) =     15.933 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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
# Warmup Iteration   1: 3.696 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.672 ms/op
                 existUser·p0.50:   2.417 ms/op
                 existUser·p0.90:   2.974 ms/op
                 existUser·p0.95:   3.088 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.214 ms/op
                 existUser·p0.9999: 16.363 ms/op
                 existUser·p1.00:   17.302 ms/op

Iteration   2: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.437 ms/op
                 existUser·p0.999:  7.190 ms/op
                 existUser·p0.9999: 13.581 ms/op
                 existUser·p1.00:   14.189 ms/op

Iteration   3: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   2.494 ms/op
                 existUser·p0.90:   3.023 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.115 ms/op
                 existUser·p0.9999: 11.946 ms/op
                 existUser·p1.00:   12.812 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 391359
  mean =      2.450 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 200353 
    [ 2.500,  3.750) = 188038 
    [ 3.750,  5.000) = 1989 
    [ 5.000,  6.250) = 420 
    [ 6.250,  7.500) = 87 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 102 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.672 ms/op
     p(50.0000) =      2.454 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.105 ms/op
     p(99.0000) =      3.576 ms/op
     p(99.9000) =      7.760 ms/op
     p(99.9900) =     14.085 ms/op
     p(99.9990) =     17.045 ms/op
     p(99.9999) =     17.302 ms/op
    p(100.0000) =     17.302 ms/op


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
# Warmup Iteration   1: 3.823 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.725 ms/op
                 getUser·p0.50:   2.486 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.768 ms/op
                 getUser·p0.999:  9.351 ms/op
                 getUser·p0.9999: 13.206 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 2.512 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.056 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.043 ms/op
                 getUser·p0.999:  5.980 ms/op
                 getUser·p0.9999: 12.354 ms/op
                 getUser·p1.00:   12.927 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.947 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   3.740 ms/op
                 getUser·p0.999:  7.323 ms/op
                 getUser·p0.9999: 11.375 ms/op
                 getUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384135
  mean =      2.497 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 191600 
    [ 2.500,  3.750) = 188005 
    [ 3.750,  5.000) = 3584 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 78 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.838 ms/op
     p(99.9000) =      6.062 ms/op
     p(99.9900) =     12.953 ms/op
     p(99.9990) =     13.706 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


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
# Warmup Iteration   1: 4.572 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.118 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.009 ms/op
Iteration   1: 3.039 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.435 ms/op
                 listUser·p0.9999: 12.394 ms/op
                 listUser·p1.00:   13.697 ms/op

Iteration   2: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 11.756 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   3: 3.027 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  9.814 ms/op
                 listUser·p0.9999: 12.262 ms/op
                 listUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315431
  mean =      3.040 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 85122 
    [ 2.500,  3.750) = 189040 
    [ 3.750,  5.000) = 34175 
    [ 5.000,  6.250) = 5771 
    [ 6.250,  7.500) = 560 
    [ 7.500,  8.750) = 170 
    [ 8.750, 10.000) = 267 
    [10.000, 11.250) = 131 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =      9.570 ms/op
     p(99.9900) =     12.099 ms/op
     p(99.9990) =     13.200 ms/op
     p(99.9999) =     13.697 ms/op
    p(100.0000) =     13.697 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.490 ± 0.888  ops/ms
ClientPb.existUser                       thrpt       3  13.114 ± 3.926  ops/ms
ClientPb.getUser                         thrpt       3  12.897 ± 1.438  ops/ms
ClientPb.listUser                        thrpt       3  10.497 ± 0.575  ops/ms
ClientPb.createUser                       avgt       3   2.534 ± 0.244   ms/op
ClientPb.existUser                        avgt       3   2.443 ± 0.225   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.139   ms/op
ClientPb.listUser                         avgt       3   3.050 ± 0.051   ms/op
ClientPb.createUser                     sample  375898   2.551 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.501           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.621           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.686           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.355           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.638           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.302           ms/op
ClientPb.existUser                      sample  391359   2.450 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.672           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.454           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.576           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.760           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.085           ms/op
ClientPb.existUser:existUser·p1.00      sample          17.302           ms/op
ClientPb.getUser                        sample  384135   2.497 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.725           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.043           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.838           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.062           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.953           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.123           ms/op
ClientPb.listUser                       sample  315431   3.040 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.903           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.978           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.570           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.099           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.697           ms/op
