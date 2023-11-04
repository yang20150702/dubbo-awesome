# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.832 ops/ms
# Warmup Iteration   2: 4.658 ops/ms
# Warmup Iteration   3: 7.881 ops/ms
Iteration   1: 8.063 ops/ms
Iteration   2: 8.455 ops/ms
Iteration   3: 8.761 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.426 ±(99.9%) 6.390 ops/ms [Average]
  (min, avg, max) = (8.063, 8.426, 8.761), stdev = 0.350
  CI (99.9%): [2.037, 14.816] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.086 ops/ms
# Warmup Iteration   2: 7.806 ops/ms
# Warmup Iteration   3: 8.764 ops/ms
Iteration   1: 8.582 ops/ms
Iteration   2: 8.726 ops/ms
Iteration   3: 8.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.667 ±(99.9%) 1.371 ops/ms [Average]
  (min, avg, max) = (8.582, 8.667, 8.726), stdev = 0.075
  CI (99.9%): [7.296, 10.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 7.418 ops/ms
# Warmup Iteration   3: 8.382 ops/ms
Iteration   1: 8.227 ops/ms
Iteration   2: 8.197 ops/ms
Iteration   3: 8.331 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.252 ±(99.9%) 1.281 ops/ms [Average]
  (min, avg, max) = (8.197, 8.252, 8.331), stdev = 0.070
  CI (99.9%): [6.971, 9.533] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.325 ops/ms
# Warmup Iteration   2: 6.292 ops/ms
# Warmup Iteration   3: 7.053 ops/ms
Iteration   1: 6.829 ops/ms
Iteration   2: 7.084 ops/ms
Iteration   3: 7.240 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.051 ±(99.9%) 3.783 ops/ms [Average]
  (min, avg, max) = (6.829, 7.051, 7.240), stdev = 0.207
  CI (99.9%): [3.268, 10.834] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.772 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.004 ms/op
Iteration   1: 4.021 ±(99.9%) 0.005 ms/op
Iteration   2: 3.901 ±(99.9%) 0.005 ms/op
Iteration   3: 3.717 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.880 ±(99.9%) 2.795 ms/op [Average]
  (min, avg, max) = (3.717, 3.880, 4.021), stdev = 0.153
  CI (99.9%): [1.085, 6.675] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 9.960 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.718 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.612 ±(99.9%) 0.004 ms/op
Iteration   1: 3.601 ±(99.9%) 0.006 ms/op
Iteration   2: 3.589 ±(99.9%) 0.003 ms/op
Iteration   3: 3.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.561 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.492, 3.561, 3.601), stdev = 0.060
  CI (99.9%): [2.471, 4.651] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.691 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.137 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.004 ms/op
Iteration   1: 3.682 ±(99.9%) 0.004 ms/op
Iteration   2: 3.639 ±(99.9%) 0.004 ms/op
Iteration   3: 3.568 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.630 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.568, 3.630, 3.682), stdev = 0.058
  CI (99.9%): [2.572, 4.688] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.183 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.514 ±(99.9%) 0.007 ms/op
Iteration   1: 4.477 ±(99.9%) 0.007 ms/op
Iteration   2: 4.534 ±(99.9%) 0.009 ms/op
Iteration   3: 4.556 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.522 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (4.477, 4.522, 4.556), stdev = 0.041
  CI (99.9%): [3.773, 5.272] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.432 ±(99.9%) 0.193 ms/op
# Warmup Iteration   2: 4.872 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.019 ms/op
Iteration   1: 3.679 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.497 ms/op
                 createUser·p0.50:   3.568 ms/op
                 createUser·p0.90:   4.211 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   7.228 ms/op
                 createUser·p0.999:  22.026 ms/op
                 createUser·p0.9999: 25.297 ms/op
                 createUser·p1.00:   25.625 ms/op

Iteration   2: 3.610 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.580 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  23.200 ms/op
                 createUser·p0.9999: 26.608 ms/op
                 createUser·p1.00:   27.427 ms/op

Iteration   3: 3.730 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.838 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.342 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   7.447 ms/op
                 createUser·p0.999:  24.052 ms/op
                 createUser·p0.9999: 27.394 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 261455
  mean =      3.672 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4556 
    [ 2.500,  5.000) = 249188 
    [ 5.000,  7.500) = 5914 
    [ 7.500, 10.000) = 1015 
    [10.000, 12.500) = 371 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 176 
    [25.000, 27.500) = 105 

  Percentiles, ms/op:
      p(0.0000) =      0.838 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.243 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     23.086 ms/op
     p(99.9900) =     26.996 ms/op
     p(99.9990) =     27.669 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 10.105 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 3.914 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.009 ms/op
Iteration   1: 3.519 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.432 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  17.973 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.680 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.579 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.702 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  15.811 ms/op
                 existUser·p0.9999: 24.180 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.624 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.153 ms/op
                 existUser·p0.95:   4.506 ms/op
                 existUser·p0.99:   6.160 ms/op
                 existUser·p0.999:  23.489 ms/op
                 existUser·p0.9999: 26.974 ms/op
                 existUser·p1.00:   27.361 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 265986
  mean =      3.607 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3498 
    [ 2.500,  5.000) = 255016 
    [ 5.000,  7.500) = 6024 
    [ 7.500, 10.000) = 715 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 42 

  Percentiles, ms/op:
      p(0.0000) =      1.030 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.166 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     27.252 ms/op
     p(99.9999) =     27.361 ms/op
    p(100.0000) =     27.361 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 10.551 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.909 ±(99.9%) 0.012 ms/op
Iteration   1: 3.777 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  21.725 ms/op
                 getUser·p0.9999: 24.936 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.753 ms/op
                 getUser·p0.50:   3.699 ms/op
                 getUser·p0.90:   4.334 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  14.533 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   26.378 ms/op

Iteration   3: 3.763 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.686 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  24.970 ms/op
                 getUser·p0.9999: 30.130 ms/op
                 getUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 254632
  mean =      3.768 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1477 
    [ 2.500,  5.000) = 245246 
    [ 5.000,  7.500) = 6829 
    [ 7.500, 10.000) = 529 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 167 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.538 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     21.225 ms/op
     p(99.9900) =     28.334 ms/op
     p(99.9990) =     30.650 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.888 ±(99.9%) 0.176 ms/op
# Warmup Iteration   2: 5.271 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.731 ±(99.9%) 0.013 ms/op
Iteration   1: 4.636 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.925 ms/op
                 listUser·p0.50:   4.465 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  22.575 ms/op
                 listUser·p0.9999: 25.709 ms/op
                 listUser·p1.00:   27.394 ms/op

Iteration   2: 4.686 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   7.999 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 24.331 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 4.609 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   8.258 ms/op
                 listUser·p0.999:  16.443 ms/op
                 listUser·p0.9999: 18.448 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 206682
  mean =      4.644 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 177148 
    [ 5.000,  7.500) = 26001 
    [ 7.500, 10.000) = 2601 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 245 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.405 ms/op
     p(50.0000) =      4.530 ms/op
     p(90.0000) =      5.120 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.274 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     24.893 ms/op
     p(99.9990) =     27.213 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.426 ± 6.390  ops/ms
ClientPb.existUser                       thrpt       3   8.667 ± 1.371  ops/ms
ClientPb.getUser                         thrpt       3   8.252 ± 1.281  ops/ms
ClientPb.listUser                        thrpt       3   7.051 ± 3.783  ops/ms
ClientPb.createUser                       avgt       3   3.880 ± 2.795   ms/op
ClientPb.existUser                        avgt       3   3.561 ± 1.090   ms/op
ClientPb.getUser                          avgt       3   3.630 ± 1.058   ms/op
ClientPb.listUser                         avgt       3   4.522 ± 0.750   ms/op
ClientPb.createUser                     sample  261455   3.672 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.838           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.588           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.243           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.726           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.086           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.996           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.722           ms/op
ClientPb.existUser                      sample  265986   3.607 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.030           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.166           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.538           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.455           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.876           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.361           ms/op
ClientPb.getUser                        sample  254632   3.768 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.538           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.690           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.455           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.225           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.334           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.704           ms/op
ClientPb.listUser                       sample  206682   4.644 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.405           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.120           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.439           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.481           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.893           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.394           ms/op
