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
# Warmup Iteration   1: 1.117 ops/ms
# Warmup Iteration   2: 2.616 ops/ms
# Warmup Iteration   3: 5.260 ops/ms
Iteration   1: 5.794 ops/ms
Iteration   2: 6.023 ops/ms
Iteration   3: 5.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.914 ±(99.9%) 2.093 ops/ms [Average]
  (min, avg, max) = (5.794, 5.914, 6.023), stdev = 0.115
  CI (99.9%): [3.821, 8.007] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.762 ops/ms
# Warmup Iteration   2: 4.963 ops/ms
# Warmup Iteration   3: 6.210 ops/ms
Iteration   1: 6.322 ops/ms
Iteration   2: 6.169 ops/ms
Iteration   3: 6.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.190 ±(99.9%) 2.229 ops/ms [Average]
  (min, avg, max) = (6.080, 6.190, 6.322), stdev = 0.122
  CI (99.9%): [3.961, 8.420] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 5.310 ops/ms
# Warmup Iteration   3: 5.914 ops/ms
Iteration   1: 6.093 ops/ms
Iteration   2: 5.978 ops/ms
Iteration   3: 5.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.013 ±(99.9%) 1.275 ops/ms [Average]
  (min, avg, max) = (5.968, 6.013, 6.093), stdev = 0.070
  CI (99.9%): [4.737, 7.288] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.602 ops/ms
# Warmup Iteration   2: 4.472 ops/ms
# Warmup Iteration   3: 4.962 ops/ms
Iteration   1: 4.810 ops/ms
Iteration   2: 5.076 ops/ms
Iteration   3: 4.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.954 ±(99.9%) 2.459 ops/ms [Average]
  (min, avg, max) = (4.810, 4.954, 5.076), stdev = 0.135
  CI (99.9%): [2.496, 7.413] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 18.083 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.206 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.655 ±(99.9%) 0.008 ms/op
Iteration   1: 5.631 ±(99.9%) 0.011 ms/op
Iteration   2: 5.533 ±(99.9%) 0.010 ms/op
Iteration   3: 5.429 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.531 ±(99.9%) 1.846 ms/op [Average]
  (min, avg, max) = (5.429, 5.531, 5.631), stdev = 0.101
  CI (99.9%): [3.685, 7.377] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 17.826 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 6.141 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.206 ±(99.9%) 0.012 ms/op
Iteration   1: 5.091 ±(99.9%) 0.015 ms/op
Iteration   2: 5.108 ±(99.9%) 0.019 ms/op
Iteration   3: 4.997 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.065 ±(99.9%) 1.097 ms/op [Average]
  (min, avg, max) = (4.997, 5.065, 5.108), stdev = 0.060
  CI (99.9%): [3.969, 6.162] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.367 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.416 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.439 ±(99.9%) 0.011 ms/op
Iteration   1: 5.224 ±(99.9%) 0.018 ms/op
Iteration   2: 5.464 ±(99.9%) 0.008 ms/op
Iteration   3: 5.428 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.372 ±(99.9%) 2.364 ms/op [Average]
  (min, avg, max) = (5.224, 5.372, 5.464), stdev = 0.130
  CI (99.9%): [3.008, 7.736] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.193 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 7.698 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.431 ±(99.9%) 0.019 ms/op
Iteration   1: 6.416 ±(99.9%) 0.014 ms/op
Iteration   2: 6.365 ±(99.9%) 0.017 ms/op
Iteration   3: 6.195 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.326 ±(99.9%) 2.112 ms/op [Average]
  (min, avg, max) = (6.195, 6.326, 6.416), stdev = 0.116
  CI (99.9%): [4.214, 8.438] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 18.601 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 7.519 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.944 ±(99.9%) 0.026 ms/op
Iteration   1: 5.404 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.161 ms/op
                 createUser·p0.90:   6.537 ms/op
                 createUser·p0.95:   7.365 ms/op
                 createUser·p0.99:   10.142 ms/op
                 createUser·p0.999:  24.733 ms/op
                 createUser·p0.9999: 28.443 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   2: 5.851 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.351 ms/op
                 createUser·p0.50:   5.456 ms/op
                 createUser·p0.90:   7.799 ms/op
                 createUser·p0.95:   8.339 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  15.041 ms/op
                 createUser·p0.9999: 30.889 ms/op
                 createUser·p1.00:   31.588 ms/op

Iteration   3: 5.219 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.821 ms/op
                 createUser·p0.50:   4.973 ms/op
                 createUser·p0.90:   6.300 ms/op
                 createUser·p0.95:   6.935 ms/op
                 createUser·p0.99:   9.159 ms/op
                 createUser·p0.999:  26.935 ms/op
                 createUser·p0.9999: 30.134 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175126
  mean =      5.479 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 66128 
    [ 5.000,  7.500) = 97975 
    [ 7.500, 10.000) = 9239 
    [10.000, 12.500) = 1130 
    [12.500, 15.000) = 358 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.027 ms/op
     p(99.9000) =     18.579 ms/op
     p(99.9900) =     30.096 ms/op
     p(99.9990) =     31.776 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.217 ±(99.9%) 0.242 ms/op
# Warmup Iteration   2: 5.856 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.520 ±(99.9%) 0.022 ms/op
Iteration   1: 5.414 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   5.161 ms/op
                 existUser·p0.90:   6.373 ms/op
                 existUser·p0.95:   7.381 ms/op
                 existUser·p0.99:   10.191 ms/op
                 existUser·p0.999:  24.131 ms/op
                 existUser·p0.9999: 32.345 ms/op
                 existUser·p1.00:   32.604 ms/op

Iteration   2: 5.063 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.019 ms/op
                 existUser·p0.50:   4.882 ms/op
                 existUser·p0.90:   5.693 ms/op
                 existUser·p0.95:   6.177 ms/op
                 existUser·p0.99:   8.995 ms/op
                 existUser·p0.999:  25.133 ms/op
                 existUser·p0.9999: 28.895 ms/op
                 existUser·p1.00:   29.262 ms/op

Iteration   3: 5.296 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.511 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.308 ms/op
                 existUser·p0.95:   7.037 ms/op
                 existUser·p0.99:   9.306 ms/op
                 existUser·p0.999:  14.727 ms/op
                 existUser·p0.9999: 28.341 ms/op
                 existUser·p1.00:   30.933 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 182765
  mean =      5.254 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 85448 
    [ 5.000,  7.500) = 91164 
    [ 7.500, 10.000) = 4648 
    [10.000, 12.500) = 954 
    [12.500, 15.000) = 237 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.683 ms/op
     p(50.0000) =      5.038 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.914 ms/op
     p(99.0000) =      9.667 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     30.310 ms/op
     p(99.9990) =     32.577 ms/op
     p(99.9999) =     32.604 ms/op
    p(100.0000) =     32.604 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.247 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.005 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.698 ±(99.9%) 0.019 ms/op
Iteration   1: 5.581 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.548 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   6.595 ms/op
                 getUser·p0.95:   8.045 ms/op
                 getUser·p0.99:   11.092 ms/op
                 getUser·p0.999:  25.230 ms/op
                 getUser·p0.9999: 37.814 ms/op
                 getUser·p1.00:   39.649 ms/op

Iteration   2: 5.406 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.634 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   9.372 ms/op
                 getUser·p0.999:  25.156 ms/op
                 getUser·p0.9999: 30.093 ms/op
                 getUser·p1.00:   32.506 ms/op

Iteration   3: 5.284 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   5.104 ms/op
                 getUser·p0.90:   5.915 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   9.093 ms/op
                 getUser·p0.999:  27.540 ms/op
                 getUser·p0.9999: 42.234 ms/op
                 getUser·p1.00:   42.664 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176901
  mean =      5.421 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 62896 
    [ 5.000, 10.000) = 112120 
    [10.000, 15.000) = 1504 
    [15.000, 20.000) = 182 
    [20.000, 25.000) = 13 
    [25.000, 30.000) = 106 
    [30.000, 35.000) = 23 
    [35.000, 40.000) = 35 
    [40.000, 45.000) = 22 

  Percentiles, ms/op:
      p(0.0000) =      2.150 ms/op
     p(50.0000) =      5.169 ms/op
     p(90.0000) =      6.308 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     25.313 ms/op
     p(99.9900) =     41.177 ms/op
     p(99.9990) =     42.664 ms/op
     p(99.9999) =     42.664 ms/op
    p(100.0000) =     42.664 ms/op


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
# Warmup Iteration   1: 17.193 ±(99.9%) 0.310 ms/op
# Warmup Iteration   2: 7.598 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.205 ±(99.9%) 0.021 ms/op
Iteration   1: 6.486 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   2.736 ms/op
                 listUser·p0.50:   5.915 ms/op
                 listUser·p0.90:   8.135 ms/op
                 listUser·p0.95:   8.847 ms/op
                 listUser·p0.99:   11.780 ms/op
                 listUser·p0.999:  29.318 ms/op
                 listUser·p0.9999: 34.097 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 6.375 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.250 ms/op
                 listUser·p0.95:   7.946 ms/op
                 listUser·p0.99:   11.059 ms/op
                 listUser·p0.999:  29.420 ms/op
                 listUser·p0.9999: 31.812 ms/op
                 listUser·p1.00:   33.817 ms/op

Iteration   3: 6.497 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   6.218 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.520 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  22.273 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148748
  mean =      6.453 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 3944 
    [ 5.000,  7.500) = 125615 
    [ 7.500, 10.000) = 16105 
    [10.000, 12.500) = 2150 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 115 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 98 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      6.119 ms/op
     p(90.0000) =      7.766 ms/op
     p(95.0000) =      8.552 ms/op
     p(99.0000) =     11.289 ms/op
     p(99.9000) =     28.148 ms/op
     p(99.9900) =     33.407 ms/op
     p(99.9990) =     35.095 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.914 ± 2.093  ops/ms
ClientPb.existUser                       thrpt       3   6.190 ± 2.229  ops/ms
ClientPb.getUser                         thrpt       3   6.013 ± 1.275  ops/ms
ClientPb.listUser                        thrpt       3   4.954 ± 2.459  ops/ms
ClientPb.createUser                       avgt       3   5.531 ± 1.846   ms/op
ClientPb.existUser                        avgt       3   5.065 ± 1.097   ms/op
ClientPb.getUser                          avgt       3   5.372 ± 2.364   ms/op
ClientPb.listUser                         avgt       3   6.326 ± 2.112   ms/op
ClientPb.createUser                     sample  175126   5.479 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.821           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.947           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.027           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.579           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.096           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  182765   5.254 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.683           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.128           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.914           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.667           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.072           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.310           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.604           ms/op
ClientPb.getUser                        sample  176901   5.421 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.150           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.169           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.313           ms/op
ClientPb.getUser:getUser·p0.9999        sample          41.177           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.664           ms/op
ClientPb.listUser                       sample  148748   6.453 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.421           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.119           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.766           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.552           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.289           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.148           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.407           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
