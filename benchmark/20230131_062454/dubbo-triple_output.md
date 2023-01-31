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
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 4.546 ops/ms
# Warmup Iteration   3: 8.791 ops/ms
Iteration   1: 9.143 ops/ms
Iteration   2: 9.303 ops/ms
Iteration   3: 9.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.277 ±(99.9%) 2.256 ops/ms [Average]
  (min, avg, max) = (9.143, 9.277, 9.386), stdev = 0.124
  CI (99.9%): [7.021, 11.533] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.061 ops/ms
# Warmup Iteration   2: 8.508 ops/ms
# Warmup Iteration   3: 9.340 ops/ms
Iteration   1: 9.816 ops/ms
Iteration   2: 9.393 ops/ms
Iteration   3: 9.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.676 ±(99.9%) 4.482 ops/ms [Average]
  (min, avg, max) = (9.393, 9.676, 9.820), stdev = 0.246
  CI (99.9%): [5.194, 14.159] (assumes normal distribution)


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
# Warmup Iteration   1: 2.427 ops/ms
# Warmup Iteration   2: 7.427 ops/ms
# Warmup Iteration   3: 8.694 ops/ms
Iteration   1: 9.039 ops/ms
Iteration   2: 9.409 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.298 ±(99.9%) 4.122 ops/ms [Average]
  (min, avg, max) = (9.039, 9.298, 9.448), stdev = 0.226
  CI (99.9%): [5.177, 13.420] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.616 ops/ms
# Warmup Iteration   2: 7.032 ops/ms
# Warmup Iteration   3: 7.636 ops/ms
Iteration   1: 7.992 ops/ms
Iteration   2: 7.972 ops/ms
Iteration   3: 8.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.989 ±(99.9%) 0.281 ops/ms [Average]
  (min, avg, max) = (7.972, 7.989, 8.002), stdev = 0.015
  CI (99.9%): [7.708, 8.269] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.975 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.646 ±(99.9%) 0.003 ms/op
Iteration   1: 3.404 ±(99.9%) 0.011 ms/op
Iteration   2: 3.438 ±(99.9%) 0.010 ms/op
Iteration   3: 3.433 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.425 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (3.404, 3.425, 3.438), stdev = 0.018
  CI (99.9%): [3.093, 3.757] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 9.294 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.658 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.521 ±(99.9%) 0.008 ms/op
Iteration   1: 3.302 ±(99.9%) 0.007 ms/op
Iteration   2: 3.333 ±(99.9%) 0.006 ms/op
Iteration   3: 3.254 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.296 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (3.254, 3.296, 3.333), stdev = 0.040
  CI (99.9%): [2.563, 4.030] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.693 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.665 ±(99.9%) 0.008 ms/op
Iteration   1: 3.533 ±(99.9%) 0.007 ms/op
Iteration   2: 3.590 ±(99.9%) 0.007 ms/op
Iteration   3: 3.397 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.507 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.397, 3.507, 3.590), stdev = 0.099
  CI (99.9%): [1.702, 5.311] (assumes normal distribution)


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
# Warmup Iteration   1: 10.510 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.386 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.932 ±(99.9%) 0.013 ms/op
Iteration   2: 3.992 ±(99.9%) 0.011 ms/op
Iteration   3: 4.029 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.985 ±(99.9%) 0.893 ms/op [Average]
  (min, avg, max) = (3.932, 3.985, 4.029), stdev = 0.049
  CI (99.9%): [3.092, 4.877] (assumes normal distribution)


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
# Warmup Iteration   1: 8.914 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.009 ms/op
Iteration   1: 3.485 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  21.786 ms/op
                 createUser·p0.9999: 27.540 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   2: 3.579 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.133 ms/op
                 createUser·p0.50:   3.428 ms/op
                 createUser·p0.90:   4.162 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.775 ms/op
                 createUser·p0.999:  25.327 ms/op
                 createUser·p0.9999: 30.769 ms/op
                 createUser·p1.00:   31.130 ms/op

Iteration   3: 3.515 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.360 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.633 ms/op
                 createUser·p0.999:  20.164 ms/op
                 createUser·p0.9999: 27.165 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272310
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5690 
    [ 2.500,  5.000) = 259108 
    [ 5.000,  7.500) = 5873 
    [ 7.500, 10.000) = 1013 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.619 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     30.305 ms/op
     p(99.9990) =     31.040 ms/op
     p(99.9999) =     31.130 ms/op
    p(100.0000) =     31.130 ms/op


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
# Warmup Iteration   1: 10.256 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.302 ±(99.9%) 0.008 ms/op
Iteration   1: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.121 ms/op
                 existUser·p0.99:   6.431 ms/op
                 existUser·p0.999:  20.810 ms/op
                 existUser·p0.9999: 24.150 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   2: 3.329 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.491 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  22.424 ms/op
                 existUser·p0.9999: 26.837 ms/op
                 existUser·p1.00:   27.361 ms/op

Iteration   3: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.339 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  14.685 ms/op
                 existUser·p0.9999: 26.116 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 283543
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11202 
    [ 2.500,  5.000) = 265870 
    [ 5.000,  7.500) = 5583 
    [ 7.500, 10.000) = 473 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 153 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.301 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.149 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     26.072 ms/op
     p(99.9990) =     26.979 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


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
# Warmup Iteration   1: 9.173 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.804 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.013 ms/op
Iteration   1: 3.487 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.354 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.010 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  20.523 ms/op
                 getUser·p0.9999: 22.861 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 3.521 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.737 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.768 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  13.337 ms/op
                 getUser·p0.9999: 24.445 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   3: 3.483 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.337 ms/op
                 getUser·p0.50:   3.408 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  24.124 ms/op
                 getUser·p0.9999: 40.859 ms/op
                 getUser·p1.00:   42.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274434
  mean =      3.497 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 264613 
    [ 5.000, 10.000) = 9365 
    [10.000, 15.000) = 190 
    [15.000, 20.000) = 11 
    [20.000, 25.000) = 188 
    [25.000, 30.000) = 35 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 22 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.337 ms/op
     p(50.0000) =      3.396 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     13.337 ms/op
     p(99.9900) =     37.195 ms/op
     p(99.9990) =     42.518 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


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
# Warmup Iteration   1: 11.882 ±(99.9%) 0.164 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.207 ±(99.9%) 0.013 ms/op
Iteration   1: 4.227 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.999 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  23.628 ms/op
                 listUser·p0.9999: 27.525 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   2: 3.929 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.570 ms/op
                 listUser·p0.999:  16.417 ms/op
                 listUser·p0.9999: 17.596 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   3: 3.948 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.163 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  15.972 ms/op
                 listUser·p0.9999: 18.477 ms/op
                 listUser·p1.00:   20.840 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238143
  mean =      4.030 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 229732 
    [ 5.000,  7.500) = 5711 
    [ 7.500, 10.000) = 1694 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 49 

  Percentiles, ms/op:
      p(0.0000) =      1.999 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.702 ms/op
     p(99.0000) =      7.717 ms/op
     p(99.9000) =     16.936 ms/op
     p(99.9900) =     26.417 ms/op
     p(99.9990) =     27.959 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.277 ± 2.256  ops/ms
ClientPb.existUser                       thrpt       3   9.676 ± 4.482  ops/ms
ClientPb.getUser                         thrpt       3   9.298 ± 4.122  ops/ms
ClientPb.listUser                        thrpt       3   7.989 ± 0.281  ops/ms
ClientPb.createUser                       avgt       3   3.425 ± 0.332   ms/op
ClientPb.existUser                        avgt       3   3.296 ± 0.734   ms/op
ClientPb.getUser                          avgt       3   3.507 ± 1.805   ms/op
ClientPb.listUser                         avgt       3   3.985 ± 0.893   ms/op
ClientPb.createUser                     sample  272310   3.526 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.133           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.424           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.480           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.305           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.130           ms/op
ClientPb.existUser                      sample  283543   3.384 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.339           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.301           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.149           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.906           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.746           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.072           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  274434   3.497 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.337           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.396           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.337           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.195           ms/op
ClientPb.getUser:getUser·p1.00          sample          42.926           ms/op
ClientPb.listUser                       sample  238143   4.030 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.999           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.702           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.936           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.417           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.017           ms/op
