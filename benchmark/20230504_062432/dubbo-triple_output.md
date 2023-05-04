# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.125 ops/ms
# Warmup Iteration   2: 5.598 ops/ms
# Warmup Iteration   3: 8.601 ops/ms
Iteration   1: 9.162 ops/ms
Iteration   2: 9.616 ops/ms
Iteration   3: 9.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 5.036 ops/ms [Average]
  (min, avg, max) = (9.117, 9.299, 9.616), stdev = 0.276
  CI (99.9%): [4.263, 14.335] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.025 ops/ms
# Warmup Iteration   2: 8.966 ops/ms
# Warmup Iteration   3: 9.302 ops/ms
Iteration   1: 9.565 ops/ms
Iteration   2: 9.214 ops/ms
Iteration   3: 10.083 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.621 ±(99.9%) 7.974 ops/ms [Average]
  (min, avg, max) = (9.214, 9.621, 10.083), stdev = 0.437
  CI (99.9%): [1.646, 17.595] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.350 ops/ms
# Warmup Iteration   2: 7.655 ops/ms
# Warmup Iteration   3: 9.449 ops/ms
Iteration   1: 9.533 ops/ms
Iteration   2: 9.737 ops/ms
Iteration   3: 9.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.609 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (9.533, 9.609, 9.737), stdev = 0.111
  CI (99.9%): [7.576, 11.642] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 7.465 ops/ms
# Warmup Iteration   3: 8.047 ops/ms
Iteration   1: 7.821 ops/ms
Iteration   2: 7.897 ops/ms
Iteration   3: 8.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.991 ±(99.9%) 4.253 ops/ms [Average]
  (min, avg, max) = (7.821, 7.991, 8.257), stdev = 0.233
  CI (99.9%): [3.738, 12.245] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.761 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.007 ms/op
Iteration   1: 3.282 ±(99.9%) 0.017 ms/op
Iteration   2: 3.382 ±(99.9%) 0.011 ms/op
Iteration   3: 3.313 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.326 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.282, 3.326, 3.382), stdev = 0.051
  CI (99.9%): [2.398, 4.253] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.485 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.006 ms/op
Iteration   1: 3.218 ±(99.9%) 0.010 ms/op
Iteration   2: 3.352 ±(99.9%) 0.005 ms/op
Iteration   3: 3.363 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.311 ±(99.9%) 1.482 ms/op [Average]
  (min, avg, max) = (3.218, 3.311, 3.363), stdev = 0.081
  CI (99.9%): [1.830, 4.793] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.776 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.005 ms/op
Iteration   1: 3.377 ±(99.9%) 0.008 ms/op
Iteration   2: 3.485 ±(99.9%) 0.007 ms/op
Iteration   3: 3.490 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 1.164 ms/op [Average]
  (min, avg, max) = (3.377, 3.451, 3.490), stdev = 0.064
  CI (99.9%): [2.287, 4.615] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.053 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.974 ±(99.9%) 0.008 ms/op
Iteration   1: 3.970 ±(99.9%) 0.012 ms/op
Iteration   2: 3.957 ±(99.9%) 0.007 ms/op
Iteration   3: 3.959 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.962 ±(99.9%) 0.124 ms/op [Average]
  (min, avg, max) = (3.957, 3.962, 3.970), stdev = 0.007
  CI (99.9%): [3.838, 4.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.083 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.010 ms/op
Iteration   1: 3.428 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.843 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.092 ms/op
                 createUser·p0.999:  20.120 ms/op
                 createUser·p0.9999: 22.566 ms/op
                 createUser·p1.00:   22.774 ms/op

Iteration   2: 3.446 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.575 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  21.022 ms/op
                 createUser·p0.9999: 30.020 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 3.526 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.343 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   4.076 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  18.055 ms/op
                 createUser·p0.9999: 30.561 ms/op
                 createUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276877
  mean =      3.466 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5184 
    [ 2.500,  5.000) = 265120 
    [ 5.000,  7.500) = 5300 
    [ 7.500, 10.000) = 722 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.343 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     19.042 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     30.981 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.439 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.471 ±(99.9%) 0.010 ms/op
Iteration   1: 3.236 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  16.681 ms/op
                 existUser·p0.9999: 23.669 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.225 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  14.402 ms/op
                 existUser·p0.9999: 25.723 ms/op
                 existUser·p1.00:   28.738 ms/op

Iteration   3: 3.424 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   4.166 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  18.330 ms/op
                 existUser·p0.9999: 23.844 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291482
  mean =      3.292 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17956 
    [ 2.500,  5.000) = 268251 
    [ 5.000,  7.500) = 3951 
    [ 7.500, 10.000) = 640 
    [10.000, 12.500) = 273 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 126 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     25.030 ms/op
     p(99.9990) =     28.708 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.459 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.720 ±(99.9%) 0.012 ms/op
Iteration   1: 3.545 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.832 ms/op
                 getUser·p0.999:  20.384 ms/op
                 getUser·p0.9999: 32.373 ms/op
                 getUser·p1.00:   33.161 ms/op

Iteration   2: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  22.075 ms/op
                 getUser·p0.9999: 25.674 ms/op
                 getUser·p1.00:   26.870 ms/op

Iteration   3: 3.692 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.469 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.880 ms/op
                 getUser·p0.999:  21.501 ms/op
                 getUser·p0.9999: 40.326 ms/op
                 getUser·p1.00:   40.960 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271896
  mean =      3.530 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 262309 
    [ 5.000, 10.000) = 9090 
    [10.000, 15.000) = 199 
    [15.000, 20.000) = 16 
    [20.000, 25.000) = 192 
    [25.000, 30.000) = 28 
    [30.000, 35.000) = 30 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.379 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     20.709 ms/op
     p(99.9900) =     39.755 ms/op
     p(99.9990) =     40.894 ms/op
     p(99.9999) =     40.960 ms/op
    p(100.0000) =     40.960 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.357 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.014 ms/op
Iteration   1: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  17.890 ms/op
                 listUser·p0.9999: 22.662 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.951 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.200 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.776 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.796 ms/op
                 listUser·p0.9999: 20.840 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 3.991 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.216 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.299 ms/op
                 listUser·p0.999:  14.960 ms/op
                 listUser·p0.9999: 23.691 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243239
  mean =      3.948 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 233637 
    [ 5.000,  7.500) = 7649 
    [ 7.500, 10.000) = 1177 
    [10.000, 12.500) = 254 
    [12.500, 15.000) = 201 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.892 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.126 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 5.036  ops/ms
ClientPb.existUser                       thrpt       3   9.621 ± 7.974  ops/ms
ClientPb.getUser                         thrpt       3   9.609 ± 2.033  ops/ms
ClientPb.listUser                        thrpt       3   7.991 ± 4.253  ops/ms
ClientPb.createUser                       avgt       3   3.326 ± 0.928   ms/op
ClientPb.existUser                        avgt       3   3.311 ± 1.482   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 1.164   ms/op
ClientPb.listUser                         avgt       3   3.962 ± 0.124   ms/op
ClientPb.createUser                     sample  276877   3.466 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.343           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.944           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.042           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.917           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.162           ms/op
ClientPb.existUser                      sample  291482   3.292 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.296           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.211           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.663           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.030           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.738           ms/op
ClientPb.getUser                        sample  271896   3.530 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.149           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.727           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.709           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.755           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.960           ms/op
ClientPb.listUser                       sample  243239   3.948 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.403           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.777           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.465           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.892           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.610           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.183           ms/op
