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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 8.528 ops/ms
Iteration   1: 8.997 ops/ms
Iteration   2: 9.329 ops/ms
Iteration   3: 9.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.219 ±(99.9%) 3.513 ops/ms [Average]
  (min, avg, max) = (8.997, 9.219, 9.331), stdev = 0.193
  CI (99.9%): [5.706, 12.732] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.063 ops/ms
# Warmup Iteration   2: 8.853 ops/ms
# Warmup Iteration   3: 9.423 ops/ms
Iteration   1: 9.607 ops/ms
Iteration   2: 9.604 ops/ms
Iteration   3: 9.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.651 ±(99.9%) 1.449 ops/ms [Average]
  (min, avg, max) = (9.604, 9.651, 9.743), stdev = 0.079
  CI (99.9%): [8.203, 11.100] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.663 ops/ms
# Warmup Iteration   2: 8.276 ops/ms
# Warmup Iteration   3: 9.124 ops/ms
Iteration   1: 9.391 ops/ms
Iteration   2: 9.031 ops/ms
Iteration   3: 9.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.265 ±(99.9%) 3.705 ops/ms [Average]
  (min, avg, max) = (9.031, 9.265, 9.391), stdev = 0.203
  CI (99.9%): [5.560, 12.970] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 7.281 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.822 ops/ms
Iteration   2: 7.845 ops/ms
Iteration   3: 7.624 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.764 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (7.624, 7.764, 7.845), stdev = 0.121
  CI (99.9%): [5.548, 9.980] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.796 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.666 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.673 ±(99.9%) 0.004 ms/op
Iteration   1: 3.515 ±(99.9%) 0.003 ms/op
Iteration   2: 3.444 ±(99.9%) 0.005 ms/op
Iteration   3: 3.341 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 1.593 ms/op [Average]
  (min, avg, max) = (3.341, 3.433, 3.515), stdev = 0.087
  CI (99.9%): [1.840, 5.027] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.004 ms/op
Iteration   1: 3.331 ±(99.9%) 0.006 ms/op
Iteration   2: 3.256 ±(99.9%) 0.002 ms/op
Iteration   3: 3.271 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.286 ±(99.9%) 0.723 ms/op [Average]
  (min, avg, max) = (3.256, 3.286, 3.331), stdev = 0.040
  CI (99.9%): [2.563, 4.008] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.173 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.497 ±(99.9%) 0.005 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op
Iteration   2: 3.519 ±(99.9%) 0.002 ms/op
Iteration   3: 3.448 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.466 ±(99.9%) 0.845 ms/op [Average]
  (min, avg, max) = (3.432, 3.466, 3.519), stdev = 0.046
  CI (99.9%): [2.621, 4.311] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.386 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.009 ms/op
Iteration   1: 4.104 ±(99.9%) 0.006 ms/op
Iteration   2: 4.024 ±(99.9%) 0.005 ms/op
Iteration   3: 4.052 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.060 ±(99.9%) 0.736 ms/op [Average]
  (min, avg, max) = (4.024, 4.060, 4.104), stdev = 0.040
  CI (99.9%): [3.324, 4.796] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.824 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.533 ±(99.9%) 0.010 ms/op
Iteration   1: 3.451 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 22.839 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.465 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.816 ms/op
                 createUser·p0.999:  21.954 ms/op
                 createUser·p0.9999: 24.435 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   3: 3.457 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   3.404 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  18.431 ms/op
                 createUser·p0.9999: 25.878 ms/op
                 createUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276198
  mean =      3.474 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8267 
    [ 2.500,  5.000) = 263329 
    [ 5.000,  7.500) = 3600 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.775 ms/op
     p(99.9000) =     19.065 ms/op
     p(99.9900) =     24.883 ms/op
     p(99.9990) =     27.074 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.987 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.009 ms/op
Iteration   1: 3.379 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.319 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.157 ms/op
                 existUser·p0.99:   5.431 ms/op
                 existUser·p0.999:  18.248 ms/op
                 existUser·p0.9999: 20.336 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.321 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 21.657 ms/op
                 existUser·p1.00:   22.348 ms/op

Iteration   3: 3.371 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.537 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  22.171 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285865
  mean =      3.357 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9355 
    [ 2.500,  5.000) = 271141 
    [ 5.000,  7.500) = 4465 
    [ 7.500, 10.000) = 454 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.537 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     24.551 ms/op
     p(99.9990) =     26.364 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 11.012 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.505 ±(99.9%) 0.010 ms/op
Iteration   1: 3.588 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.018 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  20.054 ms/op
                 getUser·p0.9999: 22.347 ms/op
                 getUser·p1.00:   23.200 ms/op

Iteration   2: 3.430 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.329 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.850 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.285 ms/op
                 getUser·p0.999:  21.552 ms/op
                 getUser·p0.9999: 25.352 ms/op
                 getUser·p1.00:   28.082 ms/op

Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.632 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   3.977 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  18.999 ms/op
                 getUser·p0.9999: 25.545 ms/op
                 getUser·p1.00:   25.952 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274664
  mean =      3.493 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2400 
    [ 2.500,  5.000) = 263532 
    [ 5.000,  7.500) = 7486 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 147 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.974 ms/op
     p(99.9000) =     19.202 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.182 ms/op
     p(99.9999) =     28.082 ms/op
    p(100.0000) =     28.082 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 10.370 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.290 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.060 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.005 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  17.214 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 4.095 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.792 ms/op
                 listUser·p0.99:   7.775 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 18.874 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   3: 3.971 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  14.370 ms/op
                 listUser·p0.9999: 17.071 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237373
  mean =      4.042 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 228748 
    [ 5.000,  7.500) = 6591 
    [ 7.500, 10.000) = 1119 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 207 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.694 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     23.003 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.219 ± 3.513  ops/ms
ClientPb.existUser                       thrpt       3   9.651 ± 1.449  ops/ms
ClientPb.getUser                         thrpt       3   9.265 ± 3.705  ops/ms
ClientPb.listUser                        thrpt       3   7.764 ± 2.216  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 1.593   ms/op
ClientPb.existUser                        avgt       3   3.286 ± 0.723   ms/op
ClientPb.getUser                          avgt       3   3.466 ± 0.845   ms/op
ClientPb.listUser                         avgt       3   4.060 ± 0.736   ms/op
ClientPb.createUser                     sample  276198   3.474 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.766           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.445           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.775           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.065           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.883           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.132           ms/op
ClientPb.existUser                      sample  285865   3.357 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.537           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.067           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.551           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706           ms/op
ClientPb.getUser                        sample  274664   3.493 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.184           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.342           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.202           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.974           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.202           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.199           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.082           ms/op
ClientPb.listUser                       sample  237373   4.042 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.694           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.463           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.167           ms/op
