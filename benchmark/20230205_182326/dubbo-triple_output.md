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
# Warmup Iteration   1: 2.004 ops/ms
# Warmup Iteration   2: 5.852 ops/ms
# Warmup Iteration   3: 8.845 ops/ms
Iteration   1: 9.422 ops/ms
Iteration   2: 9.388 ops/ms
Iteration   3: 9.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.469 ±(99.9%) 2.035 ops/ms [Average]
  (min, avg, max) = (9.388, 9.469, 9.596), stdev = 0.112
  CI (99.9%): [7.434, 11.503] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.257 ops/ms
# Warmup Iteration   2: 8.901 ops/ms
# Warmup Iteration   3: 9.735 ops/ms
Iteration   1: 10.258 ops/ms
Iteration   2: 10.185 ops/ms
Iteration   3: 9.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.137 ±(99.9%) 2.767 ops/ms [Average]
  (min, avg, max) = (9.967, 10.137, 10.258), stdev = 0.152
  CI (99.9%): [7.369, 12.904] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.696 ops/ms
# Warmup Iteration   2: 8.516 ops/ms
# Warmup Iteration   3: 8.900 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.373 ops/ms
Iteration   3: 9.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.527 ±(99.9%) 2.850 ops/ms [Average]
  (min, avg, max) = (9.373, 9.527, 9.685), stdev = 0.156
  CI (99.9%): [6.677, 12.376] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.522 ops/ms
# Warmup Iteration   2: 7.176 ops/ms
# Warmup Iteration   3: 7.788 ops/ms
Iteration   1: 8.060 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 8.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.936 ±(99.9%) 3.263 ops/ms [Average]
  (min, avg, max) = (7.731, 7.936, 8.060), stdev = 0.179
  CI (99.9%): [4.674, 11.199] (assumes normal distribution)


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
# Warmup Iteration   1: 10.189 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.654 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.006 ms/op
Iteration   1: 3.383 ±(99.9%) 0.010 ms/op
Iteration   2: 3.366 ±(99.9%) 0.009 ms/op
Iteration   3: 3.467 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.405 ±(99.9%) 0.989 ms/op [Average]
  (min, avg, max) = (3.366, 3.405, 3.467), stdev = 0.054
  CI (99.9%): [2.416, 4.394] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.982 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.578 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.213 ±(99.9%) 0.007 ms/op
Iteration   1: 3.205 ±(99.9%) 0.009 ms/op
Iteration   2: 3.331 ±(99.9%) 0.002 ms/op
Iteration   3: 3.194 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.243 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (3.194, 3.243, 3.331), stdev = 0.076
  CI (99.9%): [1.857, 4.629] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.881 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.008 ms/op
Iteration   1: 3.418 ±(99.9%) 0.005 ms/op
Iteration   2: 3.258 ±(99.9%) 0.010 ms/op
Iteration   3: 3.420 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.365 ±(99.9%) 1.698 ms/op [Average]
  (min, avg, max) = (3.258, 3.365, 3.420), stdev = 0.093
  CI (99.9%): [1.667, 5.063] (assumes normal distribution)


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
# Warmup Iteration   1: 10.873 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.047 ±(99.9%) 0.010 ms/op
Iteration   1: 3.992 ±(99.9%) 0.006 ms/op
Iteration   2: 3.929 ±(99.9%) 0.010 ms/op
Iteration   3: 3.958 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.960 ±(99.9%) 0.582 ms/op [Average]
  (min, avg, max) = (3.929, 3.960, 3.992), stdev = 0.032
  CI (99.9%): [3.377, 4.542] (assumes normal distribution)


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
# Warmup Iteration   1: 9.672 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.908 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
Iteration   1: 3.320 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   5.464 ms/op
                 createUser·p0.999:  17.549 ms/op
                 createUser·p0.9999: 22.110 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.403 ms/op
                 createUser·p0.9999: 28.264 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.336 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.305 ms/op
                 createUser·p0.999:  14.306 ms/op
                 createUser·p0.9999: 23.596 ms/op
                 createUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286582
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8051 
    [ 2.500,  5.000) = 274217 
    [ 5.000,  7.500) = 3651 
    [ 7.500, 10.000) = 279 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     14.381 ms/op
     p(99.9900) =     27.274 ms/op
     p(99.9990) =     28.403 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


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
# Warmup Iteration   1: 8.283 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
Iteration   1: 3.258 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.645 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.652 ms/op
                 existUser·p0.999:  11.354 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.626 ms/op

Iteration   2: 3.234 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  10.256 ms/op
                 existUser·p0.9999: 29.102 ms/op
                 existUser·p1.00:   29.852 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.624 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.981 ms/op
                 existUser·p0.9999: 24.879 ms/op
                 existUser·p1.00:   25.788 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 296711
  mean =      3.232 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12584 
    [ 2.500,  5.000) = 278867 
    [ 5.000,  7.500) = 4572 
    [ 7.500, 10.000) = 357 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      1.624 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     11.039 ms/op
     p(99.9900) =     27.513 ms/op
     p(99.9990) =     29.754 ms/op
     p(99.9999) =     29.852 ms/op
    p(100.0000) =     29.852 ms/op


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
# Warmup Iteration   1: 9.134 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.764 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.663 ±(99.9%) 0.012 ms/op
Iteration   1: 3.469 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.311 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  20.960 ms/op
                 getUser·p0.9999: 29.557 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   2: 3.555 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.178 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  21.135 ms/op
                 getUser·p0.9999: 25.068 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.711 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.107 ms/op
                 getUser·p0.999:  22.690 ms/op
                 getUser·p0.9999: 26.019 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277027
  mean =      3.463 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8423 
    [ 2.500,  5.000) = 260152 
    [ 5.000,  7.500) = 7566 
    [ 7.500, 10.000) = 538 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     21.037 ms/op
     p(99.9900) =     29.206 ms/op
     p(99.9990) =     29.823 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 9.668 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.215 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.013 ms/op
Iteration   1: 3.990 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.553 ms/op
                 listUser·p0.999:  18.635 ms/op
                 listUser·p0.9999: 25.559 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.725 ms/op
                 listUser·p0.999:  14.385 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.969 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.153 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242193
  mean =      3.964 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 235699 
    [ 5.000,  7.500) = 4377 
    [ 7.500, 10.000) = 1281 
    [10.000, 12.500) = 308 
    [12.500, 15.000) = 269 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      2.171 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     15.149 ms/op
     p(99.9900) =     24.405 ms/op
     p(99.9990) =     26.047 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.469 ± 2.035  ops/ms
ClientPb.existUser                       thrpt       3  10.137 ± 2.767  ops/ms
ClientPb.getUser                         thrpt       3   9.527 ± 2.850  ops/ms
ClientPb.listUser                        thrpt       3   7.936 ± 3.263  ops/ms
ClientPb.createUser                       avgt       3   3.405 ± 0.989   ms/op
ClientPb.existUser                        avgt       3   3.243 ± 1.386   ms/op
ClientPb.getUser                          avgt       3   3.365 ± 1.698   ms/op
ClientPb.listUser                         avgt       3   3.960 ± 0.582   ms/op
ClientPb.createUser                     sample  286582   3.349 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.336           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.381           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.274           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.327           ms/op
ClientPb.existUser                      sample  296711   3.232 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.624           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.539           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.497           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.039           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.513           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.852           ms/op
ClientPb.getUser                        sample  277027   3.463 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.145           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.334           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.506           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.037           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.206           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  242193   3.964 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.171           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.111           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.149           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.405           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
