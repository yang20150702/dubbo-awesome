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
# Warmup Iteration   1: 2.145 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 8.511 ops/ms
Iteration   1: 9.079 ops/ms
Iteration   2: 9.180 ops/ms
Iteration   3: 9.213 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.157 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (9.079, 9.157, 9.213), stdev = 0.070
  CI (99.9%): [7.876, 10.438] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.967 ops/ms
# Warmup Iteration   2: 8.611 ops/ms
# Warmup Iteration   3: 9.429 ops/ms
Iteration   1: 9.983 ops/ms
Iteration   2: 10.005 ops/ms
Iteration   3: 9.978 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.989 ±(99.9%) 0.257 ops/ms [Average]
  (min, avg, max) = (9.978, 9.989, 10.005), stdev = 0.014
  CI (99.9%): [9.731, 10.246] (assumes normal distribution)


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
# Warmup Iteration   1: 2.678 ops/ms
# Warmup Iteration   2: 8.629 ops/ms
# Warmup Iteration   3: 9.038 ops/ms
Iteration   1: 9.547 ops/ms
Iteration   2: 9.295 ops/ms
Iteration   3: 9.758 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.533 ±(99.9%) 4.223 ops/ms [Average]
  (min, avg, max) = (9.295, 9.533, 9.758), stdev = 0.231
  CI (99.9%): [5.310, 13.756] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.442 ops/ms
# Warmup Iteration   2: 7.095 ops/ms
# Warmup Iteration   3: 7.769 ops/ms
Iteration   1: 7.924 ops/ms
Iteration   2: 8.187 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.989 ±(99.9%) 3.194 ops/ms [Average]
  (min, avg, max) = (7.856, 7.989, 8.187), stdev = 0.175
  CI (99.9%): [4.795, 11.183] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.903 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.800 ±(99.9%) 0.005 ms/op
Iteration   1: 3.491 ±(99.9%) 0.004 ms/op
Iteration   2: 3.527 ±(99.9%) 0.010 ms/op
Iteration   3: 3.346 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 1.749 ms/op [Average]
  (min, avg, max) = (3.346, 3.455, 3.527), stdev = 0.096
  CI (99.9%): [1.706, 5.204] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 9.976 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.626 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.417 ±(99.9%) 0.009 ms/op
Iteration   1: 3.294 ±(99.9%) 0.006 ms/op
Iteration   2: 3.260 ±(99.9%) 0.005 ms/op
Iteration   3: 3.307 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.287 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (3.260, 3.287, 3.307), stdev = 0.024
  CI (99.9%): [2.841, 3.732] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.723 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.478 ±(99.9%) 0.004 ms/op
Iteration   1: 3.421 ±(99.9%) 0.006 ms/op
Iteration   2: 3.441 ±(99.9%) 0.005 ms/op
Iteration   3: 3.446 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.436 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (3.421, 3.436, 3.446), stdev = 0.013
  CI (99.9%): [3.194, 3.679] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 12.375 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.579 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.176 ±(99.9%) 0.007 ms/op
Iteration   1: 4.030 ±(99.9%) 0.011 ms/op
Iteration   2: 4.036 ±(99.9%) 0.012 ms/op
Iteration   3: 4.000 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.022 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (4.000, 4.022, 4.036), stdev = 0.019
  CI (99.9%): [3.667, 4.376] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.897 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.451 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.009 ms/op
Iteration   1: 3.448 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.355 ms/op
                 createUser·p0.90:   3.897 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  18.927 ms/op
                 createUser·p0.9999: 25.713 ms/op
                 createUser·p1.00:   26.673 ms/op

Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.600 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  9.781 ms/op
                 createUser·p0.9999: 21.974 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.456 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.219 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 23.887 ms/op
                 createUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282447
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16422 
    [ 2.500,  5.000) = 260546 
    [ 5.000,  7.500) = 4546 
    [ 7.500, 10.000) = 521 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 154 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.764 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =     18.335 ms/op
     p(99.9900) =     24.371 ms/op
     p(99.9990) =     26.451 ms/op
     p(99.9999) =     26.673 ms/op
    p(100.0000) =     26.673 ms/op


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
# Warmup Iteration   1: 8.472 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.741 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.008 ms/op
Iteration   1: 3.272 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.758 ms/op
                 existUser·p0.999:  9.440 ms/op
                 existUser·p0.9999: 22.067 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   2: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.782 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  11.567 ms/op
                 existUser·p0.9999: 24.584 ms/op
                 existUser·p1.00:   25.559 ms/op

Iteration   3: 3.461 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.526 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   6.270 ms/op
                 existUser·p0.999:  17.627 ms/op
                 existUser·p0.9999: 25.900 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287505
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8462 
    [ 2.500,  5.000) = 273377 
    [ 5.000,  7.500) = 4730 
    [ 7.500, 10.000) = 508 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     13.533 ms/op
     p(99.9900) =     25.117 ms/op
     p(99.9990) =     26.382 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.393 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.515 ±(99.9%) 0.010 ms/op
Iteration   1: 3.544 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.264 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.067 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  16.922 ms/op
                 getUser·p0.9999: 24.638 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   2: 3.509 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.159 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.055 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  10.970 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   21.463 ms/op

Iteration   3: 3.474 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.330 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   4.030 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  21.183 ms/op
                 getUser·p0.9999: 28.508 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273929
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12131 
    [ 2.500,  5.000) = 252162 
    [ 5.000,  7.500) = 8194 
    [ 7.500, 10.000) = 1029 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     14.928 ms/op
     p(99.9900) =     27.776 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 11.560 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.306 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.200 ±(99.9%) 0.015 ms/op
Iteration   1: 4.053 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.413 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  20.513 ms/op
                 listUser·p0.9999: 24.953 ms/op
                 listUser·p1.00:   25.821 ms/op

Iteration   2: 4.035 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   8.052 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 22.512 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   3: 3.915 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 17.498 ms/op
                 listUser·p1.00:   17.727 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239911
  mean =      4.000 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 232196 
    [ 5.000,  7.500) = 5516 
    [ 7.500, 10.000) = 1175 
    [10.000, 12.500) = 421 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.413 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     16.517 ms/op
     p(99.9900) =     23.790 ms/op
     p(99.9990) =     26.857 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.157 ± 1.281  ops/ms
ClientPb.existUser                       thrpt       3   9.989 ± 0.257  ops/ms
ClientPb.getUser                         thrpt       3   9.533 ± 4.223  ops/ms
ClientPb.listUser                        thrpt       3   7.989 ± 3.194  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 1.749   ms/op
ClientPb.existUser                        avgt       3   3.287 ± 0.446   ms/op
ClientPb.getUser                          avgt       3   3.436 ± 0.242   ms/op
ClientPb.listUser                         avgt       3   4.022 ± 0.354   ms/op
ClientPb.createUser                     sample  282447   3.398 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.219           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.145           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.784           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.335           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.371           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.673           ms/op
ClientPb.existUser                      sample  287505   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.641           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.953           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.533           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.117           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.509           ms/op
ClientPb.getUser                        sample  273929   3.509 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.330           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.371           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.928           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.776           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  239911   4.000 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.413           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.517           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.790           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
