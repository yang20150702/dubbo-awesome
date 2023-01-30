# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 5.664 ops/ms
# Warmup Iteration   3: 9.289 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 9.442 ops/ms
Iteration   3: 9.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.757 ±(99.9%) 4.984 ops/ms [Average]
  (min, avg, max) = (9.442, 9.757, 9.923), stdev = 0.273
  CI (99.9%): [4.773, 14.741] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ops/ms
# Warmup Iteration   2: 9.199 ops/ms
# Warmup Iteration   3: 9.961 ops/ms
Iteration   1: 10.631 ops/ms
Iteration   2: 10.388 ops/ms
Iteration   3: 10.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.375 ±(99.9%) 4.785 ops/ms [Average]
  (min, avg, max) = (10.107, 10.375, 10.631), stdev = 0.262
  CI (99.9%): [5.590, 15.160] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.613 ops/ms
# Warmup Iteration   2: 9.482 ops/ms
# Warmup Iteration   3: 9.534 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 10.341 ops/ms
Iteration   3: 10.401 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.223 ±(99.9%) 4.718 ops/ms [Average]
  (min, avg, max) = (9.926, 10.223, 10.401), stdev = 0.259
  CI (99.9%): [5.505, 14.941] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.300 ops/ms
# Warmup Iteration   2: 7.955 ops/ms
# Warmup Iteration   3: 8.505 ops/ms
Iteration   1: 8.613 ops/ms
Iteration   2: 8.490 ops/ms
Iteration   3: 8.879 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.661 ±(99.9%) 3.620 ops/ms [Average]
  (min, avg, max) = (8.490, 8.661, 8.879), stdev = 0.198
  CI (99.9%): [5.041, 12.280] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.718 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.645 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.003 ms/op
Iteration   1: 3.145 ±(99.9%) 0.004 ms/op
Iteration   2: 3.123 ±(99.9%) 0.005 ms/op
Iteration   3: 3.286 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.185 ±(99.9%) 1.608 ms/op [Average]
  (min, avg, max) = (3.123, 3.185, 3.286), stdev = 0.088
  CI (99.9%): [1.577, 4.792] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.031 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.297 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.005 ms/op
Iteration   2: 3.073 ±(99.9%) 0.001 ms/op
Iteration   3: 2.996 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.041 ±(99.9%) 0.727 ms/op [Average]
  (min, avg, max) = (2.996, 3.041, 3.073), stdev = 0.040
  CI (99.9%): [2.313, 3.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.059 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.005 ms/op
Iteration   1: 3.207 ±(99.9%) 0.006 ms/op
Iteration   2: 3.051 ±(99.9%) 0.002 ms/op
Iteration   3: 3.254 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.171 ±(99.9%) 1.941 ms/op [Average]
  (min, avg, max) = (3.051, 3.171, 3.254), stdev = 0.106
  CI (99.9%): [1.230, 5.112] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.585 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.006 ms/op
Iteration   1: 3.656 ±(99.9%) 0.005 ms/op
Iteration   2: 3.768 ±(99.9%) 0.006 ms/op
Iteration   3: 3.627 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.684 ±(99.9%) 1.357 ms/op [Average]
  (min, avg, max) = (3.627, 3.684, 3.768), stdev = 0.074
  CI (99.9%): [2.327, 5.041] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.147 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.008 ms/op
Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.891 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.627 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  18.644 ms/op
                 createUser·p0.9999: 22.577 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.432 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.407 ms/op
                 createUser·p0.999:  17.536 ms/op
                 createUser·p0.9999: 24.478 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   5.336 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 28.470 ms/op
                 createUser·p1.00:   28.967 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 301386
  mean =      3.181 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10066 
    [ 2.500,  5.000) = 284313 
    [ 5.000,  7.500) = 6100 
    [ 7.500, 10.000) = 428 
    [10.000, 12.500) = 61 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     16.715 ms/op
     p(99.9900) =     26.754 ms/op
     p(99.9990) =     28.934 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.049 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.339 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.007 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.219 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.153 ms/op
                 existUser·p0.999:  10.371 ms/op
                 existUser·p0.9999: 21.035 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.064 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.911 ms/op
                 existUser·p0.9999: 20.728 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   3: 3.063 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.453 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  10.660 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 313814
  mean =      3.058 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18970 
    [ 2.500,  5.000) = 289849 
    [ 5.000,  7.500) = 4105 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.453 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     11.125 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.142 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.741 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.340 ±(99.9%) 0.010 ms/op
Iteration   1: 3.208 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  16.073 ms/op
                 getUser·p0.9999: 20.612 ms/op
                 getUser·p1.00:   20.972 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.449 ms/op
                 getUser·p0.95:   3.613 ms/op
                 getUser·p0.99:   5.480 ms/op
                 getUser·p0.999:  11.616 ms/op
                 getUser·p0.9999: 21.889 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.223 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   6.365 ms/op
                 getUser·p0.999:  9.961 ms/op
                 getUser·p0.9999: 24.740 ms/op
                 getUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298894
  mean =      3.210 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12559 
    [ 2.500,  5.000) = 279100 
    [ 5.000,  7.500) = 6212 
    [ 7.500, 10.000) = 611 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.329 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     16.056 ms/op
     p(99.9900) =     23.469 ms/op
     p(99.9990) =     25.205 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.875 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.021 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.010 ms/op
Iteration   1: 3.713 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.541 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  16.168 ms/op
                 listUser·p0.9999: 22.405 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   2: 3.685 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   3.535 ms/op
                 listUser·p0.90:   4.006 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.107 ms/op
                 listUser·p0.9999: 16.171 ms/op
                 listUser·p1.00:   16.253 ms/op

Iteration   3: 3.724 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.633 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  12.730 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 258849
  mean =      3.707 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 250545 
    [ 5.000,  7.500) = 6636 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 242 
    [12.500, 15.000) = 264 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.541 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.873 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     20.615 ms/op
     p(99.9990) =     24.262 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.757 ± 4.984  ops/ms
ClientPb.existUser                       thrpt       3  10.375 ± 4.785  ops/ms
ClientPb.getUser                         thrpt       3  10.223 ± 4.718  ops/ms
ClientPb.listUser                        thrpt       3   8.661 ± 3.620  ops/ms
ClientPb.createUser                       avgt       3   3.185 ± 1.608   ms/op
ClientPb.existUser                        avgt       3   3.041 ± 0.727   ms/op
ClientPb.getUser                          avgt       3   3.171 ± 1.941   ms/op
ClientPb.listUser                         avgt       3   3.684 ± 1.357   ms/op
ClientPb.createUser                     sample  301386   3.181 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.891           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.019           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.715           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.754           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.967           ms/op
ClientPb.existUser                      sample  313814   3.058 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.453           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.998           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.125           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.151           ms/op
ClientPb.getUser                        sample  298894   3.210 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.329           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.125           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.510           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.056           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.469           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.985           ms/op
ClientPb.listUser                       sample  258849   3.707 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.541           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.600           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.022           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.873           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.550           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.615           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.576           ms/op
