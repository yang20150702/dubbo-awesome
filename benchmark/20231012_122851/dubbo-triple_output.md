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
# Warmup Iteration   1: 1.970 ops/ms
# Warmup Iteration   2: 4.711 ops/ms
# Warmup Iteration   3: 8.846 ops/ms
Iteration   1: 9.130 ops/ms
Iteration   2: 9.269 ops/ms
Iteration   3: 9.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.282 ±(99.9%) 2.905 ops/ms [Average]
  (min, avg, max) = (9.130, 9.282, 9.448), stdev = 0.159
  CI (99.9%): [6.377, 12.187] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.171 ops/ms
# Warmup Iteration   2: 8.505 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.622 ops/ms
Iteration   2: 9.543 ops/ms
Iteration   3: 9.473 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.546 ±(99.9%) 1.355 ops/ms [Average]
  (min, avg, max) = (9.473, 9.546, 9.622), stdev = 0.074
  CI (99.9%): [8.191, 10.901] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.031 ops/ms
# Warmup Iteration   2: 8.701 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.334 ops/ms
Iteration   2: 9.449 ops/ms
Iteration   3: 9.392 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.392 ±(99.9%) 1.043 ops/ms [Average]
  (min, avg, max) = (9.334, 9.392, 9.449), stdev = 0.057
  CI (99.9%): [8.349, 10.435] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.439 ops/ms
# Warmup Iteration   2: 7.041 ops/ms
# Warmup Iteration   3: 7.559 ops/ms
Iteration   1: 7.788 ops/ms
Iteration   2: 7.454 ops/ms
Iteration   3: 7.738 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.660 ±(99.9%) 3.280 ops/ms [Average]
  (min, avg, max) = (7.454, 7.660, 7.788), stdev = 0.180
  CI (99.9%): [4.380, 10.940] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 8.749 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.740 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.005 ms/op
Iteration   1: 3.622 ±(99.9%) 0.004 ms/op
Iteration   2: 3.456 ±(99.9%) 0.009 ms/op
Iteration   3: 3.507 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.528 ±(99.9%) 1.552 ms/op [Average]
  (min, avg, max) = (3.456, 3.528, 3.622), stdev = 0.085
  CI (99.9%): [1.976, 5.081] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 8.903 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.003 ms/op
Iteration   1: 3.336 ±(99.9%) 0.003 ms/op
Iteration   2: 3.343 ±(99.9%) 0.003 ms/op
Iteration   3: 3.364 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.347 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (3.336, 3.347, 3.364), stdev = 0.014
  CI (99.9%): [3.083, 3.612] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.582 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.784 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.004 ms/op
Iteration   1: 3.469 ±(99.9%) 0.003 ms/op
Iteration   2: 3.431 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.460 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (3.431, 3.460, 3.481), stdev = 0.026
  CI (99.9%): [2.982, 3.939] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 12.025 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.006 ms/op
Iteration   1: 4.161 ±(99.9%) 0.006 ms/op
Iteration   2: 4.233 ±(99.9%) 0.009 ms/op
Iteration   3: 4.147 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.180 ±(99.9%) 0.839 ms/op [Average]
  (min, avg, max) = (4.147, 4.180, 4.233), stdev = 0.046
  CI (99.9%): [3.341, 5.019] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 9.682 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.658 ±(99.9%) 0.011 ms/op
Iteration   1: 3.620 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.364 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.432 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  11.489 ms/op
                 createUser·p0.9999: 27.044 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   2: 3.516 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.534 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.366 ms/op
                 createUser·p0.99:   7.078 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 26.470 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 3.487 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.387 ms/op
                 createUser·p0.90:   3.899 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.890 ms/op
                 createUser·p0.999:  20.522 ms/op
                 createUser·p0.9999: 26.990 ms/op
                 createUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 271096
  mean =      3.540 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2639 
    [ 2.500,  5.000) = 261827 
    [ 5.000,  7.500) = 5223 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.234 ms/op
     p(99.9000) =     16.463 ms/op
     p(99.9900) =     26.702 ms/op
     p(99.9990) =     27.694 ms/op
     p(99.9999) =     28.148 ms/op
    p(100.0000) =     28.148 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 8.374 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.576 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.348 ±(99.9%) 0.008 ms/op
Iteration   1: 3.320 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.212 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.666 ms/op
                 existUser·p0.95:   3.879 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  17.906 ms/op
                 existUser·p0.9999: 21.180 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 3.343 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.277 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  20.081 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.321 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.382 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   6.013 ms/op
                 existUser·p0.999:  9.695 ms/op
                 existUser·p0.9999: 25.911 ms/op
                 existUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288328
  mean =      3.328 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7449 
    [ 2.500,  5.000) = 276192 
    [ 5.000,  7.500) = 3475 
    [ 7.500, 10.000) = 570 
    [10.000, 12.500) = 307 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.212 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.800 ms/op
     p(99.9999) =     27.492 ms/op
    p(100.0000) =     27.492 ms/op


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
# Warmup Iteration   1: 8.887 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.009 ms/op
Iteration   1: 3.640 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.490 ms/op
                 getUser·p0.90:   4.092 ms/op
                 getUser·p0.95:   4.620 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  20.681 ms/op
                 getUser·p0.9999: 23.403 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   2: 3.452 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.315 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.006 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  21.843 ms/op
                 getUser·p0.9999: 26.384 ms/op
                 getUser·p1.00:   27.066 ms/op

Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.219 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.030 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  19.728 ms/op
                 getUser·p0.9999: 28.335 ms/op
                 getUser·p1.00:   29.000 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273588
  mean =      3.508 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4105 
    [ 2.500,  5.000) = 263462 
    [ 5.000,  7.500) = 4824 
    [ 7.500, 10.000) = 514 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 76 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.192 ms/op
     p(99.0000) =      6.096 ms/op
     p(99.9000) =     20.480 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     28.919 ms/op
     p(99.9999) =     29.000 ms/op
    p(100.0000) =     29.000 ms/op


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
# Warmup Iteration   1: 10.530 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.405 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.245 ±(99.9%) 0.013 ms/op
Iteration   1: 4.162 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.227 ms/op
                 listUser·p0.50:   3.953 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.194 ms/op
                 listUser·p0.99:   7.867 ms/op
                 listUser·p0.999:  22.487 ms/op
                 listUser·p0.9999: 26.026 ms/op
                 listUser·p1.00:   26.640 ms/op

Iteration   2: 4.082 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.825 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  16.045 ms/op
                 listUser·p0.9999: 18.142 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 4.052 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.515 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 20.680 ms/op
                 listUser·p1.00:   21.955 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 234071
  mean =      4.098 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 224813 
    [ 5.000,  7.500) = 6969 
    [ 7.500, 10.000) = 1407 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 245 
    [15.000, 17.500) = 235 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.227 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.422 ms/op
     p(99.9000) =     16.203 ms/op
     p(99.9900) =     24.877 ms/op
     p(99.9990) =     26.541 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.282 ± 2.905  ops/ms
ClientPb.existUser                       thrpt       3   9.546 ± 1.355  ops/ms
ClientPb.getUser                         thrpt       3   9.392 ± 1.043  ops/ms
ClientPb.listUser                        thrpt       3   7.660 ± 3.280  ops/ms
ClientPb.createUser                       avgt       3   3.528 ± 1.552   ms/op
ClientPb.existUser                        avgt       3   3.347 ± 0.265   ms/op
ClientPb.getUser                          avgt       3   3.460 ± 0.479   ms/op
ClientPb.listUser                         avgt       3   4.180 ± 0.839   ms/op
ClientPb.createUser                     sample  271096   3.540 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.288           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.391           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.234           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.463           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.702           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.148           ms/op
ClientPb.existUser                      sample  288328   3.328 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.212           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.891           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.860           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.492           ms/op
ClientPb.getUser                        sample  273588   3.508 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.219           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.387           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.192           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.096           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.480           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.460           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.000           ms/op
ClientPb.listUser                       sample  234071   4.098 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.227           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.422           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.203           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.877           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.640           ms/op
