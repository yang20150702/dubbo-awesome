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
# Warmup Iteration   1: 3.942 ops/ms
# Warmup Iteration   2: 11.649 ops/ms
# Warmup Iteration   3: 11.787 ops/ms
Iteration   1: 12.377 ops/ms
Iteration   2: 11.970 ops/ms
Iteration   3: 11.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.097 ±(99.9%) 4.437 ops/ms [Average]
  (min, avg, max) = (11.943, 12.097, 12.377), stdev = 0.243
  CI (99.9%): [7.660, 16.534] (assumes normal distribution)


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
# Warmup Iteration   1: 7.263 ops/ms
# Warmup Iteration   2: 12.682 ops/ms
# Warmup Iteration   3: 12.698 ops/ms
Iteration   1: 12.649 ops/ms
Iteration   2: 12.817 ops/ms
Iteration   3: 12.748 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.738 ±(99.9%) 1.539 ops/ms [Average]
  (min, avg, max) = (12.649, 12.738, 12.817), stdev = 0.084
  CI (99.9%): [11.199, 14.277] (assumes normal distribution)


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
# Warmup Iteration   1: 6.994 ops/ms
# Warmup Iteration   2: 11.843 ops/ms
# Warmup Iteration   3: 12.493 ops/ms
Iteration   1: 12.459 ops/ms
Iteration   2: 12.531 ops/ms
Iteration   3: 12.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.434 ±(99.9%) 2.047 ops/ms [Average]
  (min, avg, max) = (12.311, 12.434, 12.531), stdev = 0.112
  CI (99.9%): [10.387, 14.480] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.084 ops/ms
# Warmup Iteration   2: 10.126 ops/ms
# Warmup Iteration   3: 9.995 ops/ms
Iteration   1: 10.194 ops/ms
Iteration   2: 10.180 ops/ms
Iteration   3: 10.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.240 ±(99.9%) 1.689 ops/ms [Average]
  (min, avg, max) = (10.180, 10.240, 10.347), stdev = 0.093
  CI (99.9%): [8.551, 11.929] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.680 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.628 ±(99.9%) 0.005 ms/op
Iteration   1: 2.620 ±(99.9%) 0.004 ms/op
Iteration   2: 2.631 ±(99.9%) 0.004 ms/op
Iteration   3: 2.592 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.614 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (2.592, 2.614, 2.631), stdev = 0.020
  CI (99.9%): [2.246, 2.982] (assumes normal distribution)


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.557 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.003 ms/op
Iteration   1: 2.559 ±(99.9%) 0.004 ms/op
Iteration   2: 2.563 ±(99.9%) 0.004 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.551 ±(99.9%) 0.316 ms/op [Average]
  (min, avg, max) = (2.531, 2.551, 2.563), stdev = 0.017
  CI (99.9%): [2.235, 2.867] (assumes normal distribution)


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
# Warmup Iteration   1: 4.133 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.592 ±(99.9%) 0.005 ms/op
Iteration   1: 2.578 ±(99.9%) 0.004 ms/op
Iteration   2: 2.590 ±(99.9%) 0.004 ms/op
Iteration   3: 2.619 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.596 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (2.578, 2.596, 2.619), stdev = 0.021
  CI (99.9%): [2.217, 2.974] (assumes normal distribution)


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
# Warmup Iteration   1: 5.246 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.005 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
Iteration   3: 3.047 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.046 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (3.038, 3.046, 3.053), stdev = 0.008
  CI (99.9%): [2.905, 3.187] (assumes normal distribution)


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
# Warmup Iteration   1: 4.407 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 2.681 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.563 ±(99.9%) 0.006 ms/op
Iteration   1: 2.592 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.671 ms/op
                 createUser·p0.90:   3.133 ms/op
                 createUser·p0.95:   3.265 ms/op
                 createUser·p0.99:   4.063 ms/op
                 createUser·p0.999:  12.151 ms/op
                 createUser·p0.9999: 14.380 ms/op
                 createUser·p1.00:   14.959 ms/op

Iteration   2: 2.574 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   2.675 ms/op
                 createUser·p0.90:   3.109 ms/op
                 createUser·p0.95:   3.232 ms/op
                 createUser·p0.99:   4.112 ms/op
                 createUser·p0.999:  10.089 ms/op
                 createUser·p0.9999: 13.559 ms/op
                 createUser·p1.00:   14.303 ms/op

Iteration   3: 2.558 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   2.650 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.709 ms/op
                 createUser·p0.999:  8.880 ms/op
                 createUser·p0.9999: 12.821 ms/op
                 createUser·p1.00:   12.976 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 372502
  mean =      2.575 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 30 
    [ 1.250,  2.500) = 176580 
    [ 2.500,  3.750) = 190771 
    [ 3.750,  5.000) = 4064 
    [ 5.000,  6.250) = 578 
    [ 6.250,  7.500) = 72 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      2.666 ms/op
     p(90.0000) =      3.113 ms/op
     p(95.0000) =      3.232 ms/op
     p(99.0000) =      3.944 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     14.139 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.908 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.499 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.985 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.666 ms/op
                 existUser·p0.999:  6.478 ms/op
                 existUser·p0.9999: 13.665 ms/op
                 existUser·p1.00:   14.254 ms/op

Iteration   2: 2.486 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.838 ms/op
                 existUser·p0.999:  7.303 ms/op
                 existUser·p0.9999: 13.124 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.925 ms/op
                 existUser·p0.50:   2.572 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  5.926 ms/op
                 existUser·p0.9999: 11.520 ms/op
                 existUser·p1.00:   12.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 386748
  mean =      2.480 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 38 
    [ 1.250,  2.500) = 189540 
    [ 2.500,  3.750) = 192643 
    [ 3.750,  5.000) = 3509 
    [ 5.000,  6.250) = 649 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 79 
    [10.000, 11.250) = 69 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.863 ms/op
     p(99.9000) =      6.103 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.123 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.534 ±(99.9%) 0.006 ms/op
Iteration   1: 2.534 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.978 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   3.936 ms/op
                 getUser·p0.999:  12.629 ms/op
                 getUser·p0.9999: 14.490 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 2.524 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.633 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.895 ms/op
                 getUser·p0.999:  9.967 ms/op
                 getUser·p0.9999: 13.326 ms/op
                 getUser·p1.00:   13.795 ms/op

Iteration   3: 2.528 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.972 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.076 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.080 ms/op
                 getUser·p0.999:  8.790 ms/op
                 getUser·p0.9999: 11.534 ms/op
                 getUser·p1.00:   11.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379296
  mean =      2.528 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 186215 
    [ 2.500,  3.750) = 187937 
    [ 3.750,  5.000) = 3637 
    [ 5.000,  6.250) = 963 
    [ 6.250,  7.500) = 78 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 84 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 129 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      3.953 ms/op
     p(99.9000) =      9.259 ms/op
     p(99.9900) =     13.995 ms/op
     p(99.9990) =     14.615 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


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
# Warmup Iteration   1: 5.214 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.167 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.009 ms/op
Iteration   1: 3.094 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.961 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   5.972 ms/op
                 listUser·p0.999:  10.125 ms/op
                 listUser·p0.9999: 11.589 ms/op
                 listUser·p1.00:   12.141 ms/op

Iteration   2: 3.087 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.910 ms/op
                 listUser·p0.50:   3.019 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.898 ms/op
                 listUser·p0.999:  10.531 ms/op
                 listUser·p0.9999: 11.977 ms/op
                 listUser·p1.00:   12.780 ms/op

Iteration   3: 3.075 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   4.018 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   5.816 ms/op
                 listUser·p0.999:  10.209 ms/op
                 listUser·p0.9999: 13.262 ms/op
                 listUser·p1.00:   14.221 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 310838
  mean =      3.086 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 84516 
    [ 2.500,  3.750) = 180710 
    [ 3.750,  5.000) = 36092 
    [ 5.000,  6.250) = 7431 
    [ 6.250,  7.500) = 1231 
    [ 7.500,  8.750) = 235 
    [ 8.750, 10.000) = 186 
    [10.000, 11.250) = 197 
    [11.250, 12.500) = 119 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     10.191 ms/op
     p(99.9900) =     12.467 ms/op
     p(99.9990) =     14.111 ms/op
     p(99.9999) =     14.221 ms/op
    p(100.0000) =     14.221 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.097 ± 4.437  ops/ms
ClientPb.existUser                       thrpt       3  12.738 ± 1.539  ops/ms
ClientPb.getUser                         thrpt       3  12.434 ± 2.047  ops/ms
ClientPb.listUser                        thrpt       3  10.240 ± 1.689  ops/ms
ClientPb.createUser                       avgt       3   2.614 ± 0.368   ms/op
ClientPb.existUser                        avgt       3   2.551 ± 0.316   ms/op
ClientPb.getUser                          avgt       3   2.596 ± 0.378   ms/op
ClientPb.listUser                         avgt       3   3.046 ± 0.141   ms/op
ClientPb.createUser                     sample  372502   2.575 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.885           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.666           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.995           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.139           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.959           ms/op
ClientPb.existUser                      sample  386748   2.480 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.925           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.552           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.863           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.103           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.254           ms/op
ClientPb.getUser                        sample  379296   2.528 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.633           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.552           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.259           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.995           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.696           ms/op
ClientPb.listUser                       sample  310838   3.086 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.771           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.015           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.035           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.467           ms/op
ClientPb.listUser:listUser·p1.00        sample          14.221           ms/op
