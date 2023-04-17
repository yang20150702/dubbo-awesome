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
# Warmup Iteration   1: 2.549 ops/ms
# Warmup Iteration   2: 6.075 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 10.202 ops/ms
Iteration   3: 9.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.904 ±(99.9%) 6.103 ops/ms [Average]
  (min, avg, max) = (9.542, 9.904, 10.202), stdev = 0.335
  CI (99.9%): [3.801, 16.008] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.437 ops/ms
# Warmup Iteration   2: 9.384 ops/ms
# Warmup Iteration   3: 9.997 ops/ms
Iteration   1: 10.534 ops/ms
Iteration   2: 10.529 ops/ms
Iteration   3: 10.408 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.490 ±(99.9%) 1.306 ops/ms [Average]
  (min, avg, max) = (10.408, 10.490, 10.534), stdev = 0.072
  CI (99.9%): [9.184, 11.796] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.336 ops/ms
# Warmup Iteration   2: 9.388 ops/ms
# Warmup Iteration   3: 9.757 ops/ms
Iteration   1: 10.067 ops/ms
Iteration   2: 10.397 ops/ms
Iteration   3: 9.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.088 ±(99.9%) 5.454 ops/ms [Average]
  (min, avg, max) = (9.800, 10.088, 10.397), stdev = 0.299
  CI (99.9%): [4.634, 15.543] (assumes normal distribution)


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
# Warmup Iteration   1: 3.233 ops/ms
# Warmup Iteration   2: 7.161 ops/ms
# Warmup Iteration   3: 8.533 ops/ms
Iteration   1: 8.518 ops/ms
Iteration   2: 8.398 ops/ms
Iteration   3: 8.617 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.511 ±(99.9%) 1.997 ops/ms [Average]
  (min, avg, max) = (8.398, 8.511, 8.617), stdev = 0.109
  CI (99.9%): [6.514, 10.507] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.231 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.510 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.005 ms/op
Iteration   1: 3.176 ±(99.9%) 0.002 ms/op
Iteration   2: 3.122 ±(99.9%) 0.006 ms/op
Iteration   3: 3.200 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.166 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.122, 3.166, 3.200), stdev = 0.040
  CI (99.9%): [2.438, 3.895] (assumes normal distribution)


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
# Warmup Iteration   1: 7.294 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.102 ±(99.9%) 0.002 ms/op
Iteration   1: 2.958 ±(99.9%) 0.006 ms/op
Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
Iteration   3: 3.004 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.006 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (2.958, 3.006, 3.056), stdev = 0.049
  CI (99.9%): [2.112, 3.900] (assumes normal distribution)


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
# Warmup Iteration   1: 7.580 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.638 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.005 ms/op
Iteration   1: 3.176 ±(99.9%) 0.003 ms/op
Iteration   2: 3.236 ±(99.9%) 0.008 ms/op
Iteration   3: 3.289 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.234 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.176, 3.234, 3.289), stdev = 0.056
  CI (99.9%): [2.203, 4.264] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.686 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.279 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.862 ±(99.9%) 0.004 ms/op
Iteration   1: 3.747 ±(99.9%) 0.009 ms/op
Iteration   2: 3.856 ±(99.9%) 0.007 ms/op
Iteration   3: 3.838 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.813 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (3.747, 3.813, 3.856), stdev = 0.059
  CI (99.9%): [2.746, 4.881] (assumes normal distribution)


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
# Warmup Iteration   1: 8.889 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.811 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.009 ms/op
Iteration   1: 3.119 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.384 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   5.127 ms/op
                 createUser·p0.999:  9.265 ms/op
                 createUser·p0.9999: 21.258 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.136 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.893 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.330 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   26.018 ms/op

Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.708 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  10.076 ms/op
                 createUser·p0.9999: 19.005 ms/op
                 createUser·p1.00:   19.694 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304707
  mean =      3.148 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26258 
    [ 2.500,  5.000) = 273437 
    [ 5.000,  7.500) = 4363 
    [ 7.500, 10.000) = 315 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 128 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.893 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      5.341 ms/op
     p(99.9000) =     14.701 ms/op
     p(99.9900) =     23.747 ms/op
     p(99.9990) =     25.490 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 6.757 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
Iteration   1: 3.036 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.223 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.710 ms/op
                 existUser·p0.999:  10.177 ms/op
                 existUser·p0.9999: 24.749 ms/op
                 existUser·p1.00:   25.854 ms/op

Iteration   2: 3.093 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  13.828 ms/op
                 existUser·p0.9999: 21.780 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.083 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   4.528 ms/op
                 existUser·p0.999:  11.621 ms/op
                 existUser·p0.9999: 19.812 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312539
  mean =      3.070 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19250 
    [ 2.500,  5.000) = 289018 
    [ 5.000,  7.500) = 3444 
    [ 7.500, 10.000) = 291 
    [10.000, 12.500) = 162 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.285 ms/op
     p(95.0000) =      3.486 ms/op
     p(99.0000) =      5.276 ms/op
     p(99.9000) =     13.484 ms/op
     p(99.9900) =     22.683 ms/op
     p(99.9990) =     25.690 ms/op
     p(99.9999) =     25.854 ms/op
    p(100.0000) =     25.854 ms/op


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
# Warmup Iteration   1: 7.819 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.458 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.010 ms/op
Iteration   1: 3.291 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.063 ms/op
                 getUser·p0.99:   6.615 ms/op
                 getUser·p0.999:  17.433 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.120 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.387 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   5.319 ms/op
                 getUser·p0.999:  9.823 ms/op
                 getUser·p0.9999: 21.529 ms/op
                 getUser·p1.00:   23.429 ms/op

Iteration   3: 3.229 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.499 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   5.972 ms/op
                 getUser·p0.999:  12.959 ms/op
                 getUser·p0.9999: 23.460 ms/op
                 getUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298661
  mean =      3.212 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13360 
    [ 2.500,  5.000) = 279167 
    [ 5.000,  7.500) = 5151 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.595 ms/op
     p(95.0000) =      3.973 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     17.182 ms/op
     p(99.9900) =     22.680 ms/op
     p(99.9990) =     23.959 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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
# Warmup Iteration   1: 8.467 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
Iteration   1: 4.012 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.716 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.497 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.221 ms/op
                 listUser·p0.9999: 21.235 ms/op
                 listUser·p1.00:   22.643 ms/op

Iteration   2: 3.771 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.923 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 14.918 ms/op
                 listUser·p1.00:   15.335 ms/op

Iteration   3: 3.763 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.569 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.980 ms/op
                 listUser·p0.999:  16.336 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249413
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 137 
    [ 2.500,  5.000) = 237662 
    [ 5.000,  7.500) = 9289 
    [ 7.500, 10.000) = 1600 
    [10.000, 12.500) = 294 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      3.686 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.549 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     21.808 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.904 ± 6.103  ops/ms
ClientPb.existUser                       thrpt       3  10.490 ± 1.306  ops/ms
ClientPb.getUser                         thrpt       3  10.088 ± 5.454  ops/ms
ClientPb.listUser                        thrpt       3   8.511 ± 1.997  ops/ms
ClientPb.createUser                       avgt       3   3.166 ± 0.729   ms/op
ClientPb.existUser                        avgt       3   3.006 ± 0.894   ms/op
ClientPb.getUser                          avgt       3   3.234 ± 1.031   ms/op
ClientPb.listUser                         avgt       3   3.813 ± 1.068   ms/op
ClientPb.createUser                     sample  304707   3.148 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.893           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.478           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.760           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.701           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.747           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.018           ms/op
ClientPb.existUser                      sample  312539   3.070 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.285           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.276           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.484           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.683           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.854           ms/op
ClientPb.getUser                        sample  298661   3.212 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.499           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.595           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.939           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.182           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.680           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.297           ms/op
ClientPb.listUser                       sample  249413   3.845 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.569           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.686           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.211           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.549           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.643           ms/op
