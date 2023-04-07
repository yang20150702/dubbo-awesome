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
# Warmup Iteration   1: 1.735 ops/ms
# Warmup Iteration   2: 3.375 ops/ms
# Warmup Iteration   3: 6.677 ops/ms
Iteration   1: 7.274 ops/ms
Iteration   2: 8.179 ops/ms
Iteration   3: 7.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.792 ±(99.9%) 8.511 ops/ms [Average]
  (min, avg, max) = (7.274, 7.792, 8.179), stdev = 0.467
  CI (99.9%): [≈ 0, 16.303] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 6.374 ops/ms
# Warmup Iteration   3: 8.339 ops/ms
Iteration   1: 8.277 ops/ms
Iteration   2: 8.304 ops/ms
Iteration   3: 8.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.348 ±(99.9%) 1.822 ops/ms [Average]
  (min, avg, max) = (8.277, 8.348, 8.462), stdev = 0.100
  CI (99.9%): [6.525, 10.170] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 5.720 ops/ms
# Warmup Iteration   3: 7.576 ops/ms
Iteration   1: 8.036 ops/ms
Iteration   2: 8.203 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.103 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (8.036, 8.103, 8.203), stdev = 0.088
  CI (99.9%): [6.495, 9.711] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.357 ops/ms
# Warmup Iteration   2: 5.750 ops/ms
# Warmup Iteration   3: 6.441 ops/ms
Iteration   1: 6.636 ops/ms
Iteration   2: 6.517 ops/ms
Iteration   3: 6.852 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.668 ±(99.9%) 3.098 ops/ms [Average]
  (min, avg, max) = (6.517, 6.668, 6.852), stdev = 0.170
  CI (99.9%): [3.570, 9.766] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.580 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 5.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.340 ±(99.9%) 0.006 ms/op
Iteration   1: 4.100 ±(99.9%) 0.007 ms/op
Iteration   2: 3.890 ±(99.9%) 0.013 ms/op
Iteration   3: 3.980 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.990 ±(99.9%) 1.925 ms/op [Average]
  (min, avg, max) = (3.890, 3.990, 4.100), stdev = 0.106
  CI (99.9%): [2.065, 5.915] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 12.374 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.009 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
Iteration   2: 3.870 ±(99.9%) 0.006 ms/op
Iteration   3: 3.857 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.859 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (3.851, 3.859, 3.870), stdev = 0.010
  CI (99.9%): [3.682, 4.036] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 13.186 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.094 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.007 ms/op
Iteration   1: 4.136 ±(99.9%) 0.008 ms/op
Iteration   2: 4.081 ±(99.9%) 0.012 ms/op
Iteration   3: 4.063 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.093 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (4.063, 4.093, 4.136), stdev = 0.038
  CI (99.9%): [3.396, 4.791] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 15.762 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.328 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.762 ±(99.9%) 0.009 ms/op
Iteration   1: 4.557 ±(99.9%) 0.016 ms/op
Iteration   2: 4.747 ±(99.9%) 0.008 ms/op
Iteration   3: 4.756 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.687 ±(99.9%) 2.050 ms/op [Average]
  (min, avg, max) = (4.557, 4.687, 4.756), stdev = 0.112
  CI (99.9%): [2.637, 6.737] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.505 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 5.590 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.370 ±(99.9%) 0.019 ms/op
Iteration   1: 3.994 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.997 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.538 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  21.396 ms/op
                 createUser·p0.9999: 24.412 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.822 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   5.030 ms/op
                 createUser·p0.99:   7.471 ms/op
                 createUser·p0.999:  15.892 ms/op
                 createUser·p0.9999: 29.296 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.372 ms/op
                 createUser·p0.50:   3.817 ms/op
                 createUser·p0.90:   4.432 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.586 ms/op
                 createUser·p0.999:  25.068 ms/op
                 createUser·p0.9999: 27.942 ms/op
                 createUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241035
  mean =      3.981 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 255 
    [ 2.500,  5.000) = 228756 
    [ 5.000,  7.500) = 9710 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 206 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 40 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.372 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.997 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     21.396 ms/op
     p(99.9900) =     28.243 ms/op
     p(99.9990) =     30.401 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.253 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.334 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.014 ms/op
Iteration   1: 3.819 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.948 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   6.521 ms/op
                 existUser·p0.999:  10.638 ms/op
                 existUser·p0.9999: 30.069 ms/op
                 existUser·p1.00:   32.539 ms/op

Iteration   2: 3.855 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  10.322 ms/op
                 existUser·p0.9999: 27.092 ms/op
                 existUser·p1.00:   28.541 ms/op

Iteration   3: 3.839 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   3.658 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.858 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  26.169 ms/op
                 existUser·p0.9999: 30.452 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 250095
  mean =      3.838 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 306 
    [ 2.500,  5.000) = 240834 
    [ 5.000,  7.500) = 7136 
    [ 7.500, 10.000) = 1342 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 116 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     13.763 ms/op
     p(99.9900) =     29.819 ms/op
     p(99.9990) =     31.424 ms/op
     p(99.9999) =     32.539 ms/op
    p(100.0000) =     32.539 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.996 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 4.766 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.015 ms/op
Iteration   1: 4.274 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.790 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   5.382 ms/op
                 getUser·p0.95:   6.636 ms/op
                 getUser·p0.99:   8.831 ms/op
                 getUser·p0.999:  24.945 ms/op
                 getUser·p0.9999: 29.951 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   2: 4.117 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.638 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.530 ms/op
                 getUser·p0.99:   7.700 ms/op
                 getUser·p0.999:  13.065 ms/op
                 getUser·p0.9999: 31.865 ms/op
                 getUser·p1.00:   32.834 ms/op

Iteration   3: 3.962 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.142 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.005 ms/op
                 getUser·p0.999:  11.015 ms/op
                 getUser·p0.9999: 31.619 ms/op
                 getUser·p1.00:   32.539 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 233352
  mean =      4.114 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 217226 
    [ 5.000,  7.500) = 12445 
    [ 7.500, 10.000) = 2779 
    [10.000, 12.500) = 425 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 76 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.912 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     18.612 ms/op
     p(99.9900) =     31.610 ms/op
     p(99.9990) =     32.440 ms/op
     p(99.9999) =     32.834 ms/op
    p(100.0000) =     32.834 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.607 ±(99.9%) 0.219 ms/op
# Warmup Iteration   2: 5.621 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.890 ±(99.9%) 0.016 ms/op
Iteration   1: 4.710 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  26.328 ms/op
                 listUser·p0.9999: 28.451 ms/op
                 listUser·p1.00:   29.327 ms/op

Iteration   2: 4.788 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.218 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.121 ms/op
                 listUser·p0.9999: 30.252 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   3: 4.874 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.510 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   7.070 ms/op
                 listUser·p0.99:   9.322 ms/op
                 listUser·p0.999:  17.347 ms/op
                 listUser·p0.9999: 25.100 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200246
  mean =      4.790 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 163644 
    [ 5.000,  7.500) = 30105 
    [ 7.500, 10.000) = 5326 
    [10.000, 12.500) = 558 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      4.555 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      6.087 ms/op
     p(99.0000) =      8.889 ms/op
     p(99.9000) =     19.456 ms/op
     p(99.9900) =     28.736 ms/op
     p(99.9990) =     31.260 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.792 ± 8.511  ops/ms
ClientPb.existUser                       thrpt       3   8.348 ± 1.822  ops/ms
ClientPb.getUser                         thrpt       3   8.103 ± 1.608  ops/ms
ClientPb.listUser                        thrpt       3   6.668 ± 3.098  ops/ms
ClientPb.createUser                       avgt       3   3.990 ± 1.925   ms/op
ClientPb.existUser                        avgt       3   3.859 ± 0.177   ms/op
ClientPb.getUser                          avgt       3   4.093 ± 0.697   ms/op
ClientPb.listUser                         avgt       3   4.687 ± 2.050   ms/op
ClientPb.createUser                     sample  241035   3.981 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.372           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.813           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.522           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.422           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.396           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.243           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.540           ms/op
ClientPb.existUser                      sample  250095   3.838 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.678           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.243           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.819           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.539           ms/op
ClientPb.getUser                        sample  233352   4.114 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.638           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.912           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.167           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.612           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.834           ms/op
ClientPb.listUser                       sample  200246   4.790 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.510           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.555           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.087           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.889           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.456           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.736           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.621           ms/op
