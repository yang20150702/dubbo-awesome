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
# Warmup Iteration   1: 4.984 ops/ms
# Warmup Iteration   2: 12.560 ops/ms
# Warmup Iteration   3: 13.036 ops/ms
Iteration   1: 13.218 ops/ms
Iteration   2: 13.369 ops/ms
Iteration   3: 13.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  13.261 ±(99.9%) 1.717 ops/ms [Average]
  (min, avg, max) = (13.196, 13.261, 13.369), stdev = 0.094
  CI (99.9%): [11.544, 14.978] (assumes normal distribution)


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
# Warmup Iteration   1: 8.478 ops/ms
# Warmup Iteration   2: 13.434 ops/ms
# Warmup Iteration   3: 14.095 ops/ms
Iteration   1: 13.922 ops/ms
Iteration   2: 13.682 ops/ms
Iteration   3: 13.566 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.723 ±(99.9%) 3.310 ops/ms [Average]
  (min, avg, max) = (13.566, 13.723, 13.922), stdev = 0.181
  CI (99.9%): [10.413, 17.033] (assumes normal distribution)


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
# Warmup Iteration   1: 8.130 ops/ms
# Warmup Iteration   2: 12.788 ops/ms
# Warmup Iteration   3: 12.975 ops/ms
Iteration   1: 13.132 ops/ms
Iteration   2: 13.167 ops/ms
Iteration   3: 13.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.148 ±(99.9%) 0.323 ops/ms [Average]
  (min, avg, max) = (13.132, 13.148, 13.167), stdev = 0.018
  CI (99.9%): [12.825, 13.471] (assumes normal distribution)


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
# Warmup Iteration   1: 6.567 ops/ms
# Warmup Iteration   2: 10.543 ops/ms
# Warmup Iteration   3: 10.635 ops/ms
Iteration   1: 10.602 ops/ms
Iteration   2: 10.547 ops/ms
Iteration   3: 10.578 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.576 ±(99.9%) 0.505 ops/ms [Average]
  (min, avg, max) = (10.547, 10.576, 10.602), stdev = 0.028
  CI (99.9%): [10.071, 11.081] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.743 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.468 ±(99.9%) 0.004 ms/op
Iteration   1: 2.481 ±(99.9%) 0.004 ms/op
Iteration   2: 2.461 ±(99.9%) 0.003 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.474 ±(99.9%) 0.202 ms/op [Average]
  (min, avg, max) = (2.461, 2.474, 2.481), stdev = 0.011
  CI (99.9%): [2.272, 2.676] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.522 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.390 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.413 ±(99.9%) 0.004 ms/op
Iteration   1: 2.402 ±(99.9%) 0.003 ms/op
Iteration   2: 2.394 ±(99.9%) 0.003 ms/op
Iteration   3: 2.394 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.397 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (2.394, 2.397, 2.402), stdev = 0.005
  CI (99.9%): [2.310, 2.484] (assumes normal distribution)


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.004 ms/op
Iteration   1: 2.433 ±(99.9%) 0.004 ms/op
Iteration   2: 2.467 ±(99.9%) 0.004 ms/op
Iteration   3: 2.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.449 ±(99.9%) 0.312 ms/op [Average]
  (min, avg, max) = (2.433, 2.449, 2.467), stdev = 0.017
  CI (99.9%): [2.137, 2.762] (assumes normal distribution)


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
# Warmup Iteration   1: 4.499 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
Iteration   1: 2.996 ±(99.9%) 0.007 ms/op
Iteration   2: 2.983 ±(99.9%) 0.006 ms/op
Iteration   3: 2.987 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.988 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (2.983, 2.988, 2.996), stdev = 0.007
  CI (99.9%): [2.864, 3.113] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.112 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.659 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.513 ±(99.9%) 0.006 ms/op
Iteration   1: 2.498 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.906 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.969 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 14.628 ms/op
                 createUser·p1.00:   14.991 ms/op

Iteration   2: 2.526 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.961 ms/op
                 createUser·p0.50:   2.601 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  9.388 ms/op
                 createUser·p0.9999: 12.643 ms/op
                 createUser·p1.00:   12.993 ms/op

Iteration   3: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.899 ms/op
                 createUser·p0.999:  7.859 ms/op
                 createUser·p0.9999: 10.732 ms/op
                 createUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380744
  mean =      2.519 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 36 
    [ 1.250,  2.500) = 182738 
    [ 2.500,  3.750) = 193440 
    [ 3.750,  5.000) = 3606 
    [ 5.000,  6.250) = 518 
    [ 6.250,  7.500) = 21 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 86 
    [11.250, 12.500) = 84 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      2.593 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      3.873 ms/op
     p(99.9000) =      7.918 ms/op
     p(99.9900) =     13.116 ms/op
     p(99.9990) =     14.847 ms/op
     p(99.9999) =     14.991 ms/op
    p(100.0000) =     14.991 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.633 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.391 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
Iteration   1: 2.390 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.833 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.892 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   4.108 ms/op
                 existUser·p0.999:  6.106 ms/op
                 existUser·p0.9999: 13.642 ms/op
                 existUser·p1.00:   14.057 ms/op

Iteration   2: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.949 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.916 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   3.559 ms/op
                 existUser·p0.999:  5.922 ms/op
                 existUser·p0.9999: 15.032 ms/op
                 existUser·p1.00:   16.056 ms/op

Iteration   3: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.876 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.740 ms/op
                 existUser·p0.999:  8.028 ms/op
                 existUser·p0.9999: 11.249 ms/op
                 existUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 399309
  mean =      2.401 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 204286 
    [ 2.500,  3.750) = 190719 
    [ 3.750,  5.000) = 3309 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 90 
    [10.000, 11.250) = 66 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 64 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      6.811 ms/op
     p(99.9900) =     13.878 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.006 ms/op
Iteration   1: 2.449 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.801 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  5.640 ms/op
                 getUser·p0.9999: 13.303 ms/op
                 getUser·p1.00:   13.648 ms/op

Iteration   2: 2.463 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.671 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.129 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  6.735 ms/op
                 getUser·p0.9999: 13.845 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.905 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.863 ms/op
                 getUser·p0.999:  7.766 ms/op
                 getUser·p0.9999: 11.058 ms/op
                 getUser·p1.00:   11.174 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390851
  mean =      2.454 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 101 
    [ 1.250,  2.500) = 196801 
    [ 2.500,  3.750) = 189171 
    [ 3.750,  5.000) = 3799 
    [ 5.000,  6.250) = 552 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 96 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 89 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =      7.008 ms/op
     p(99.9900) =     13.270 ms/op
     p(99.9990) =     14.618 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.524 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.034 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.008 ms/op
Iteration   1: 2.989 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  9.881 ms/op
                 listUser·p0.9999: 12.069 ms/op
                 listUser·p1.00:   12.534 ms/op

Iteration   2: 2.992 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.623 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.612 ms/op
                 listUser·p0.999:  9.683 ms/op
                 listUser·p0.9999: 12.102 ms/op
                 listUser·p1.00:   12.485 ms/op

Iteration   3: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.598 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.628 ms/op
                 listUser·p0.999:  9.568 ms/op
                 listUser·p0.9999: 11.115 ms/op
                 listUser·p1.00:   11.895 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319974
  mean =      2.998 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 174 
    [ 1.250,  2.500) = 97521 
    [ 2.500,  3.750) = 182409 
    [ 3.750,  5.000) = 31858 
    [ 5.000,  6.250) = 6609 
    [ 6.250,  7.500) = 732 
    [ 7.500,  8.750) = 165 
    [ 8.750, 10.000) = 253 
    [10.000, 11.250) = 179 
    [11.250, 12.500) = 71 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     11.878 ms/op
     p(99.9990) =     12.498 ms/op
     p(99.9999) =     12.534 ms/op
    p(100.0000) =     12.534 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  13.261 ± 1.717  ops/ms
ClientPb.existUser                       thrpt       3  13.723 ± 3.310  ops/ms
ClientPb.getUser                         thrpt       3  13.148 ± 0.323  ops/ms
ClientPb.listUser                        thrpt       3  10.576 ± 0.505  ops/ms
ClientPb.createUser                       avgt       3   2.474 ± 0.202   ms/op
ClientPb.existUser                        avgt       3   2.397 ± 0.087   ms/op
ClientPb.getUser                          avgt       3   2.449 ± 0.312   ms/op
ClientPb.listUser                         avgt       3   2.988 ± 0.124   ms/op
ClientPb.createUser                     sample  380744   2.519 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.906           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.593           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.056           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.873           ms/op
ClientPb.createUser:createUser·p0.999   sample           7.918           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.991           ms/op
ClientPb.existUser                      sample  399309   2.401 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.833           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.470           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.811           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.878           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.056           ms/op
ClientPb.getUser                        sample  390851   2.454 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.671           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.990           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.008           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.270           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  319974   2.998 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.598           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.929           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.908           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.683           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.878           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.534           ms/op
