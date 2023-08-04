# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.247 ops/ms
# Warmup Iteration   2: 5.658 ops/ms
# Warmup Iteration   3: 8.502 ops/ms
Iteration   1: 9.376 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.363 ±(99.9%) 1.866 ops/ms [Average]
  (min, avg, max) = (9.255, 9.363, 9.458), stdev = 0.102
  CI (99.9%): [7.497, 11.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.085 ops/ms
# Warmup Iteration   2: 8.420 ops/ms
# Warmup Iteration   3: 9.394 ops/ms
Iteration   1: 9.350 ops/ms
Iteration   2: 9.361 ops/ms
Iteration   3: 9.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.493 ±(99.9%) 4.344 ops/ms [Average]
  (min, avg, max) = (9.350, 9.493, 9.768), stdev = 0.238
  CI (99.9%): [5.149, 13.838] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.464 ops/ms
# Warmup Iteration   2: 8.678 ops/ms
# Warmup Iteration   3: 8.780 ops/ms
Iteration   1: 9.242 ops/ms
Iteration   2: 9.465 ops/ms
Iteration   3: 9.166 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.291 ±(99.9%) 2.828 ops/ms [Average]
  (min, avg, max) = (9.166, 9.291, 9.465), stdev = 0.155
  CI (99.9%): [6.463, 12.119] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.786 ops/ms
# Warmup Iteration   2: 6.998 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.698 ops/ms
Iteration   2: 7.848 ops/ms
Iteration   3: 7.917 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.821 ±(99.9%) 2.038 ops/ms [Average]
  (min, avg, max) = (7.698, 7.821, 7.917), stdev = 0.112
  CI (99.9%): [5.783, 9.860] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.322 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.006 ms/op
Iteration   1: 3.639 ±(99.9%) 0.007 ms/op
Iteration   2: 3.532 ±(99.9%) 0.003 ms/op
Iteration   3: 3.362 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.511 ±(99.9%) 2.540 ms/op [Average]
  (min, avg, max) = (3.362, 3.511, 3.639), stdev = 0.139
  CI (99.9%): [0.971, 6.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 8.731 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.007 ms/op
Iteration   1: 3.375 ±(99.9%) 0.010 ms/op
Iteration   2: 3.331 ±(99.9%) 0.007 ms/op
Iteration   3: 3.374 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.360 ±(99.9%) 0.454 ms/op [Average]
  (min, avg, max) = (3.331, 3.360, 3.375), stdev = 0.025
  CI (99.9%): [2.906, 3.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 8.504 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.720 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.004 ms/op
Iteration   1: 3.585 ±(99.9%) 0.005 ms/op
Iteration   2: 3.490 ±(99.9%) 0.006 ms/op
Iteration   3: 3.529 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.535 ±(99.9%) 0.873 ms/op [Average]
  (min, avg, max) = (3.490, 3.535, 3.585), stdev = 0.048
  CI (99.9%): [2.662, 4.407] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 10.273 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.380 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.156 ±(99.9%) 0.007 ms/op
Iteration   1: 4.099 ±(99.9%) 0.008 ms/op
Iteration   2: 4.046 ±(99.9%) 0.008 ms/op
Iteration   3: 4.148 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.098 ±(99.9%) 0.929 ms/op [Average]
  (min, avg, max) = (4.046, 4.098, 4.148), stdev = 0.051
  CI (99.9%): [3.169, 5.027] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.604 ±(99.9%) 0.012 ms/op
Iteration   1: 3.544 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.593 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   4.141 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  20.070 ms/op
                 createUser·p0.9999: 22.412 ms/op
                 createUser·p1.00:   24.281 ms/op

Iteration   2: 3.533 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.415 ms/op
                 createUser·p0.99:   6.382 ms/op
                 createUser·p0.999:  22.118 ms/op
                 createUser·p0.9999: 47.835 ms/op
                 createUser·p1.00:   48.234 ms/op

Iteration   3: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.918 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  18.486 ms/op
                 createUser·p0.9999: 27.955 ms/op
                 createUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272862
  mean =      3.515 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 265789 
    [ 5.000, 10.000) = 6605 
    [10.000, 15.000) = 170 
    [15.000, 20.000) = 36 
    [20.000, 25.000) = 166 
    [25.000, 30.000) = 64 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.043 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     19.321 ms/op
     p(99.9900) =     46.999 ms/op
     p(99.9990) =     48.121 ms/op
     p(99.9999) =     48.234 ms/op
    p(100.0000) =     48.234 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.400 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.584 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
Iteration   1: 3.461 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.065 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  20.349 ms/op
                 existUser·p0.9999: 22.668 ms/op
                 existUser·p1.00:   23.233 ms/op

Iteration   2: 3.463 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  22.011 ms/op
                 existUser·p0.9999: 25.569 ms/op
                 existUser·p1.00:   26.313 ms/op

Iteration   3: 3.464 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   7.537 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 27.182 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277012
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12550 
    [ 2.500,  5.000) = 253881 
    [ 5.000,  7.500) = 8563 
    [ 7.500, 10.000) = 1373 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     26.486 ms/op
     p(99.9990) =     27.497 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 8.465 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 3.665 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.010 ms/op
Iteration   1: 3.443 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   6.644 ms/op
                 getUser·p0.999:  20.385 ms/op
                 getUser·p0.9999: 24.434 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.614 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.845 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   7.691 ms/op
                 getUser·p0.999:  13.664 ms/op
                 getUser·p0.9999: 25.788 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.420 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.454 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.889 ms/op
                 getUser·p0.999:  19.351 ms/op
                 getUser·p0.9999: 34.449 ms/op
                 getUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274845
  mean =      3.490 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13043 
    [ 2.500,  5.000) = 252281 
    [ 5.000,  7.500) = 7425 
    [ 7.500, 10.000) = 1439 
    [10.000, 12.500) = 352 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.454 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     15.209 ms/op
     p(99.9900) =     31.671 ms/op
     p(99.9990) =     34.849 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.678 ±(99.9%) 0.147 ms/op
# Warmup Iteration   2: 4.945 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.154 ±(99.9%) 0.013 ms/op
Iteration   1: 4.139 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   8.323 ms/op
                 listUser·p0.999:  20.578 ms/op
                 listUser·p0.9999: 23.569 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   2: 4.072 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.884 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  15.062 ms/op
                 listUser·p0.9999: 15.794 ms/op
                 listUser·p1.00:   16.089 ms/op

Iteration   3: 4.120 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   8.135 ms/op
                 listUser·p0.999:  14.932 ms/op
                 listUser·p0.9999: 18.210 ms/op
                 listUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233668
  mean =      4.110 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 223011 
    [ 5.000,  7.500) = 7318 
    [ 7.500, 10.000) = 2279 
    [10.000, 12.500) = 466 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.884 ms/op
     p(50.0000) =      3.944 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      8.241 ms/op
     p(99.9000) =     15.663 ms/op
     p(99.9900) =     22.488 ms/op
     p(99.9990) =     23.702 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.363 ± 1.866  ops/ms
ClientPb.existUser                       thrpt       3   9.493 ± 4.344  ops/ms
ClientPb.getUser                         thrpt       3   9.291 ± 2.828  ops/ms
ClientPb.listUser                        thrpt       3   7.821 ± 2.038  ops/ms
ClientPb.createUser                       avgt       3   3.511 ± 2.540   ms/op
ClientPb.existUser                        avgt       3   3.360 ± 0.454   ms/op
ClientPb.getUser                          avgt       3   3.535 ± 0.873   ms/op
ClientPb.listUser                         avgt       3   4.098 ± 0.929   ms/op
ClientPb.createUser                     sample  272862   3.515 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.918           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.412           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.136           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.321           ms/op
ClientPb.createUser:createUser·p0.9999  sample          46.999           ms/op
ClientPb.createUser:createUser·p1.00    sample          48.234           ms/op
ClientPb.existUser                      sample  277012   3.462 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.065           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.743           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.758           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.763           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.486           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.606           ms/op
ClientPb.getUser                        sample  274845   3.490 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.454           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.209           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.062           ms/op
ClientPb.listUser                       sample  233668   4.110 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.884           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.944           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.663           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.488           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.035           ms/op
