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
# Warmup Iteration   1: 1.972 ops/ms
# Warmup Iteration   2: 5.025 ops/ms
# Warmup Iteration   3: 8.651 ops/ms
Iteration   1: 9.006 ops/ms
Iteration   2: 9.101 ops/ms
Iteration   3: 9.114 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.074 ±(99.9%) 1.081 ops/ms [Average]
  (min, avg, max) = (9.006, 9.074, 9.114), stdev = 0.059
  CI (99.9%): [7.993, 10.154] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 8.277 ops/ms
# Warmup Iteration   3: 9.327 ops/ms
Iteration   1: 9.126 ops/ms
Iteration   2: 9.284 ops/ms
Iteration   3: 9.430 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.280 ±(99.9%) 2.771 ops/ms [Average]
  (min, avg, max) = (9.126, 9.280, 9.430), stdev = 0.152
  CI (99.9%): [6.509, 12.051] (assumes normal distribution)


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
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 8.109 ops/ms
# Warmup Iteration   3: 9.306 ops/ms
Iteration   1: 8.835 ops/ms
Iteration   2: 8.990 ops/ms
Iteration   3: 9.192 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.006 ±(99.9%) 3.273 ops/ms [Average]
  (min, avg, max) = (8.835, 9.006, 9.192), stdev = 0.179
  CI (99.9%): [5.732, 12.279] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.650 ops/ms
# Warmup Iteration   2: 6.609 ops/ms
# Warmup Iteration   3: 7.546 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 8.124 ops/ms
Iteration   3: 7.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.910 ±(99.9%) 3.405 ops/ms [Average]
  (min, avg, max) = (7.784, 7.910, 8.124), stdev = 0.187
  CI (99.9%): [4.504, 11.315] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.478 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.846 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.703 ±(99.9%) 0.004 ms/op
Iteration   1: 3.595 ±(99.9%) 0.005 ms/op
Iteration   2: 3.455 ±(99.9%) 0.008 ms/op
Iteration   3: 3.549 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.533 ±(99.9%) 1.295 ms/op [Average]
  (min, avg, max) = (3.455, 3.533, 3.595), stdev = 0.071
  CI (99.9%): [2.238, 4.828] (assumes normal distribution)


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
# Warmup Iteration   1: 10.117 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.006 ms/op
Iteration   1: 3.352 ±(99.9%) 0.004 ms/op
Iteration   2: 3.337 ±(99.9%) 0.003 ms/op
Iteration   3: 3.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.385 ±(99.9%) 1.284 ms/op [Average]
  (min, avg, max) = (3.337, 3.385, 3.465), stdev = 0.070
  CI (99.9%): [2.100, 4.669] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 11.036 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.562 ±(99.9%) 0.006 ms/op
Iteration   1: 3.647 ±(99.9%) 0.005 ms/op
Iteration   2: 3.456 ±(99.9%) 0.006 ms/op
Iteration   3: 3.475 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.526 ±(99.9%) 1.926 ms/op [Average]
  (min, avg, max) = (3.456, 3.526, 3.647), stdev = 0.106
  CI (99.9%): [1.600, 5.452] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.645 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.327 ±(99.9%) 0.010 ms/op
Iteration   1: 4.333 ±(99.9%) 0.006 ms/op
Iteration   2: 4.153 ±(99.9%) 0.008 ms/op
Iteration   3: 4.136 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.208 ±(99.9%) 1.990 ms/op [Average]
  (min, avg, max) = (4.136, 4.208, 4.333), stdev = 0.109
  CI (99.9%): [2.217, 6.198] (assumes normal distribution)


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
# Warmup Iteration   1: 11.171 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.016 ms/op
Iteration   1: 3.543 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.776 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.727 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  24.059 ms/op
                 createUser·p0.9999: 27.098 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.526 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   3.998 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  22.999 ms/op
                 createUser·p0.9999: 27.298 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   3: 3.418 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   6.074 ms/op
                 createUser·p0.999:  21.147 ms/op
                 createUser·p0.9999: 35.127 ms/op
                 createUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274515
  mean =      3.495 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7271 
    [ 2.500,  5.000) = 258259 
    [ 5.000,  7.500) = 7258 
    [ 7.500, 10.000) = 1016 
    [10.000, 12.500) = 268 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.346 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     21.758 ms/op
     p(99.9900) =     33.853 ms/op
     p(99.9990) =     35.423 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 10.288 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.910 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.010 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   5.702 ms/op
                 existUser·p0.999:  20.546 ms/op
                 existUser·p0.9999: 23.414 ms/op
                 existUser·p1.00:   24.379 ms/op

Iteration   2: 3.438 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.815 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.903 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  12.617 ms/op
                 existUser·p0.9999: 24.642 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.470 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.563 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.834 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.627 ms/op
                 existUser·p0.999:  26.112 ms/op
                 existUser·p0.9999: 48.559 ms/op
                 existUser·p1.00:   50.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 279195
  mean =      3.438 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 271173 
    [ 5.000, 10.000) = 7487 
    [10.000, 15.000) = 274 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 159 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 16 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     13.579 ms/op
     p(99.9900) =     43.844 ms/op
     p(99.9990) =     49.862 ms/op
     p(99.9999) =     50.135 ms/op
    p(100.0000) =     50.135 ms/op


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
# Warmup Iteration   1: 8.989 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.912 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.595 ±(99.9%) 0.013 ms/op
Iteration   1: 3.504 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.739 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   7.160 ms/op
                 getUser·p0.999:  22.741 ms/op
                 getUser·p0.9999: 27.683 ms/op
                 getUser·p1.00:   28.738 ms/op

Iteration   2: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.829 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.166 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.275 ms/op
                 getUser·p0.999:  25.054 ms/op
                 getUser·p0.9999: 28.078 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 3.538 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.432 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  12.134 ms/op
                 getUser·p0.9999: 30.866 ms/op
                 getUser·p1.00:   31.293 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272047
  mean =      3.526 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7886 
    [ 2.500,  5.000) = 253313 
    [ 5.000,  7.500) = 9001 
    [ 7.500, 10.000) = 1206 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 139 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.432 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      4.018 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     12.893 ms/op
     p(99.9900) =     28.580 ms/op
     p(99.9990) =     31.130 ms/op
     p(99.9999) =     31.293 ms/op
    p(100.0000) =     31.293 ms/op


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
# Warmup Iteration   1: 11.862 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.670 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.016 ms/op
Iteration   1: 4.313 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.860 ms/op
                 listUser·p0.50:   4.026 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.929 ms/op
                 listUser·p0.999:  23.273 ms/op
                 listUser·p0.9999: 28.082 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 4.214 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.265 ms/op
                 listUser·p0.50:   4.043 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.880 ms/op
                 listUser·p0.999:  15.500 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.973 ms/op

Iteration   3: 4.127 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.963 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 20.234 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 227714
  mean =      4.216 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 213514 
    [ 5.000,  7.500) = 10307 
    [ 7.500, 10.000) = 2612 
    [10.000, 12.500) = 751 
    [12.500, 15.000) = 114 
    [15.000, 17.500) = 219 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     16.843 ms/op
     p(99.9900) =     26.582 ms/op
     p(99.9990) =     28.672 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.074 ± 1.081  ops/ms
ClientPb.existUser                       thrpt       3   9.280 ± 2.771  ops/ms
ClientPb.getUser                         thrpt       3   9.006 ± 3.273  ops/ms
ClientPb.listUser                        thrpt       3   7.910 ± 3.405  ops/ms
ClientPb.createUser                       avgt       3   3.533 ± 1.295   ms/op
ClientPb.existUser                        avgt       3   3.385 ± 1.284   ms/op
ClientPb.getUser                          avgt       3   3.526 ± 1.926   ms/op
ClientPb.listUser                         avgt       3   4.208 ± 1.990   ms/op
ClientPb.createUser                     sample  274515   3.495 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.346           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.932           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.758           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.853           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.717           ms/op
ClientPb.existUser                      sample  279195   3.438 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.338           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          43.844           ms/op
ClientPb.existUser:existUser·p1.00      sample          50.135           ms/op
ClientPb.getUser                        sample  272047   3.526 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.432           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.018           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.955           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.893           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.580           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.293           ms/op
ClientPb.listUser                       sample  227714   4.216 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.843           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.582           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.901           ms/op
