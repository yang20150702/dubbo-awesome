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
# Warmup Iteration   1: 1.855 ops/ms
# Warmup Iteration   2: 4.988 ops/ms
# Warmup Iteration   3: 8.546 ops/ms
Iteration   1: 9.062 ops/ms
Iteration   2: 9.081 ops/ms
Iteration   3: 9.101 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.081 ±(99.9%) 0.357 ops/ms [Average]
  (min, avg, max) = (9.062, 9.081, 9.101), stdev = 0.020
  CI (99.9%): [8.724, 9.439] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.703 ops/ms
# Warmup Iteration   2: 8.735 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 9.793 ops/ms
Iteration   2: 9.578 ops/ms
Iteration   3: 9.137 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.503 ±(99.9%) 6.099 ops/ms [Average]
  (min, avg, max) = (9.137, 9.503, 9.793), stdev = 0.334
  CI (99.9%): [3.404, 15.601] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.583 ops/ms
# Warmup Iteration   2: 8.120 ops/ms
# Warmup Iteration   3: 8.820 ops/ms
Iteration   1: 9.725 ops/ms
Iteration   2: 9.485 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.593 ±(99.9%) 2.223 ops/ms [Average]
  (min, avg, max) = (9.485, 9.593, 9.725), stdev = 0.122
  CI (99.9%): [7.370, 11.815] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.738 ops/ms
# Warmup Iteration   2: 7.066 ops/ms
# Warmup Iteration   3: 8.252 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 7.737 ops/ms
Iteration   3: 8.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.004 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (7.737, 8.004, 8.139), stdev = 0.231
  CI (99.9%): [3.784, 12.224] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.906 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.776 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.573 ±(99.9%) 0.004 ms/op
Iteration   1: 3.425 ±(99.9%) 0.004 ms/op
Iteration   2: 3.391 ±(99.9%) 0.007 ms/op
Iteration   3: 3.350 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.389 ±(99.9%) 0.684 ms/op [Average]
  (min, avg, max) = (3.350, 3.389, 3.425), stdev = 0.037
  CI (99.9%): [2.705, 4.073] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 9.686 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.410 ±(99.9%) 0.005 ms/op
Iteration   1: 3.274 ±(99.9%) 0.009 ms/op
Iteration   2: 3.284 ±(99.9%) 0.013 ms/op
Iteration   3: 3.342 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.300 ±(99.9%) 0.672 ms/op [Average]
  (min, avg, max) = (3.274, 3.300, 3.342), stdev = 0.037
  CI (99.9%): [2.628, 3.972] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 10.881 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.851 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.005 ms/op
Iteration   1: 3.385 ±(99.9%) 0.006 ms/op
Iteration   2: 3.496 ±(99.9%) 0.006 ms/op
Iteration   3: 3.776 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.552 ±(99.9%) 3.679 ms/op [Average]
  (min, avg, max) = (3.385, 3.552, 3.776), stdev = 0.202
  CI (99.9%): [≈ 0, 7.232] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.976 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.010 ms/op
Iteration   1: 4.085 ±(99.9%) 0.011 ms/op
Iteration   2: 3.999 ±(99.9%) 0.015 ms/op
Iteration   3: 4.119 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.068 ±(99.9%) 1.121 ms/op [Average]
  (min, avg, max) = (3.999, 4.068, 4.119), stdev = 0.061
  CI (99.9%): [2.947, 5.189] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.639 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.773 ±(99.9%) 0.013 ms/op
Iteration   1: 3.634 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   4.260 ms/op
                 createUser·p0.95:   4.661 ms/op
                 createUser·p0.99:   5.939 ms/op
                 createUser·p0.999:  21.134 ms/op
                 createUser·p0.9999: 26.843 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   2: 3.617 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.659 ms/op
                 createUser·p0.50:   3.441 ms/op
                 createUser·p0.90:   4.276 ms/op
                 createUser·p0.95:   4.882 ms/op
                 createUser·p0.99:   6.349 ms/op
                 createUser·p0.999:  22.893 ms/op
                 createUser·p0.9999: 26.367 ms/op
                 createUser·p1.00:   28.148 ms/op

Iteration   3: 3.535 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.677 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  25.673 ms/op
                 createUser·p0.9999: 33.948 ms/op
                 createUser·p1.00:   34.734 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 266912
  mean =      3.595 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8070 
    [ 2.500,  5.000) = 248602 
    [ 5.000,  7.500) = 8996 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 24 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      6.291 ms/op
     p(99.9000) =     21.368 ms/op
     p(99.9900) =     32.428 ms/op
     p(99.9990) =     34.559 ms/op
     p(99.9999) =     34.734 ms/op
    p(100.0000) =     34.734 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.431 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.679 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.009 ms/op
Iteration   1: 3.406 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.817 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  19.464 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   23.560 ms/op

Iteration   2: 3.395 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.380 ms/op
                 existUser·p0.50:   3.244 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.344 ms/op
                 existUser·p0.99:   6.062 ms/op
                 existUser·p0.999:  20.925 ms/op
                 existUser·p0.9999: 24.253 ms/op
                 existUser·p1.00:   27.525 ms/op

Iteration   3: 3.394 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.655 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  20.868 ms/op
                 existUser·p0.9999: 27.656 ms/op
                 existUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282362
  mean =      3.398 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8204 
    [ 2.500,  5.000) = 268848 
    [ 5.000,  7.500) = 4451 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     19.747 ms/op
     p(99.9900) =     26.519 ms/op
     p(99.9990) =     27.924 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


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
# Warmup Iteration   1: 8.364 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.560 ±(99.9%) 0.011 ms/op
Iteration   1: 3.513 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.396 ms/op
                 getUser·p0.90:   4.096 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   6.152 ms/op
                 getUser·p0.999:  14.925 ms/op
                 getUser·p0.9999: 23.884 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   2: 3.452 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.468 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  21.253 ms/op
                 getUser·p0.9999: 30.695 ms/op
                 getUser·p1.00:   31.916 ms/op

Iteration   3: 3.563 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.088 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.627 ms/op
                 getUser·p0.999:  19.787 ms/op
                 getUser·p0.9999: 27.886 ms/op
                 getUser·p1.00:   28.803 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273493
  mean =      3.509 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9930 
    [ 2.500,  5.000) = 256242 
    [ 5.000,  7.500) = 5879 
    [ 7.500, 10.000) = 974 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.346 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     15.630 ms/op
     p(99.9900) =     28.661 ms/op
     p(99.9990) =     31.049 ms/op
     p(99.9999) =     31.916 ms/op
    p(100.0000) =     31.916 ms/op


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
# Warmup Iteration   1: 12.043 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.536 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.014 ms/op
Iteration   1: 4.138 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   7.560 ms/op
                 listUser·p0.999:  19.811 ms/op
                 listUser·p0.9999: 29.730 ms/op
                 listUser·p1.00:   30.048 ms/op

Iteration   2: 4.059 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.552 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.224 ms/op
                 listUser·p0.9999: 21.827 ms/op
                 listUser·p1.00:   21.889 ms/op

Iteration   3: 4.035 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.490 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.102 ms/op
                 listUser·p0.999:  15.298 ms/op
                 listUser·p0.9999: 19.630 ms/op
                 listUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235298
  mean =      4.077 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 225102 
    [ 5.000,  7.500) = 8055 
    [ 7.500, 10.000) = 1323 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 211 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.299 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     28.556 ms/op
     p(99.9990) =     30.015 ms/op
     p(99.9999) =     30.048 ms/op
    p(100.0000) =     30.048 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.081 ± 0.357  ops/ms
ClientPb.existUser                       thrpt       3   9.503 ± 6.099  ops/ms
ClientPb.getUser                         thrpt       3   9.593 ± 2.223  ops/ms
ClientPb.listUser                        thrpt       3   8.004 ± 4.220  ops/ms
ClientPb.createUser                       avgt       3   3.389 ± 0.684   ms/op
ClientPb.existUser                        avgt       3   3.300 ± 0.672   ms/op
ClientPb.getUser                          avgt       3   3.552 ± 3.679   ms/op
ClientPb.listUser                         avgt       3   4.068 ± 1.121   ms/op
ClientPb.createUser                     sample  266912   3.595 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.678           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.291           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.368           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.428           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.734           ms/op
ClientPb.existUser                      sample  282362   3.398 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.368           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.849           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.747           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.519           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.984           ms/op
ClientPb.getUser                        sample  273493   3.509 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.346           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.977           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.630           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.661           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.916           ms/op
ClientPb.listUser                       sample  235298   4.077 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.299           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.450           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.556           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.048           ms/op
