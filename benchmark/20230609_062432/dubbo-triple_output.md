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
# Warmup Iteration   1: 2.684 ops/ms
# Warmup Iteration   2: 6.713 ops/ms
# Warmup Iteration   3: 9.492 ops/ms
Iteration   1: 9.390 ops/ms
Iteration   2: 9.896 ops/ms
Iteration   3: 10.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.781 ±(99.9%) 6.341 ops/ms [Average]
  (min, avg, max) = (9.390, 9.781, 10.056), stdev = 0.348
  CI (99.9%): [3.440, 16.121] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.765 ops/ms
# Warmup Iteration   2: 9.318 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.339 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.535 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (10.339, 10.535, 10.755), stdev = 0.209
  CI (99.9%): [6.725, 14.344] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.701 ops/ms
# Warmup Iteration   2: 8.661 ops/ms
# Warmup Iteration   3: 9.600 ops/ms
Iteration   1: 9.646 ops/ms
Iteration   2: 10.090 ops/ms
Iteration   3: 10.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.937 ±(99.9%) 4.607 ops/ms [Average]
  (min, avg, max) = (9.646, 9.937, 10.090), stdev = 0.253
  CI (99.9%): [5.330, 14.545] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.158 ops/ms
# Warmup Iteration   2: 7.848 ops/ms
# Warmup Iteration   3: 8.302 ops/ms
Iteration   1: 8.686 ops/ms
Iteration   2: 8.498 ops/ms
Iteration   3: 8.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.615 ±(99.9%) 1.861 ops/ms [Average]
  (min, avg, max) = (8.498, 8.615, 8.686), stdev = 0.102
  CI (99.9%): [6.753, 10.476] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.056 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.481 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.318 ±(99.9%) 0.003 ms/op
Iteration   1: 3.185 ±(99.9%) 0.010 ms/op
Iteration   2: 3.128 ±(99.9%) 0.005 ms/op
Iteration   3: 3.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.132 ±(99.9%) 0.928 ms/op [Average]
  (min, avg, max) = (3.084, 3.132, 3.185), stdev = 0.051
  CI (99.9%): [2.205, 4.060] (assumes normal distribution)


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
# Warmup Iteration   1: 6.797 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 3.081 ±(99.9%) 0.003 ms/op
Iteration   2: 3.132 ±(99.9%) 0.001 ms/op
Iteration   3: 3.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.089 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.053, 3.089, 3.132), stdev = 0.040
  CI (99.9%): [2.361, 3.817] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.257 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.417 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.003 ms/op
Iteration   1: 3.138 ±(99.9%) 0.007 ms/op
Iteration   2: 3.129 ±(99.9%) 0.003 ms/op
Iteration   3: 3.241 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.169 ±(99.9%) 1.136 ms/op [Average]
  (min, avg, max) = (3.129, 3.169, 3.241), stdev = 0.062
  CI (99.9%): [2.033, 4.305] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.367 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.004 ms/op
Iteration   1: 3.688 ±(99.9%) 0.007 ms/op
Iteration   2: 3.757 ±(99.9%) 0.007 ms/op
Iteration   3: 3.781 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.688, 3.742, 3.781), stdev = 0.048
  CI (99.9%): [2.858, 4.626] (assumes normal distribution)


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
# Warmup Iteration   1: 8.187 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
Iteration   1: 3.182 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.857 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.580 ms/op
                 createUser·p0.99:   5.284 ms/op
                 createUser·p0.999:  13.926 ms/op
                 createUser·p0.9999: 26.082 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 3.218 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.540 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  13.310 ms/op
                 createUser·p0.9999: 26.643 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   3: 3.279 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  14.828 ms/op
                 createUser·p0.9999: 21.250 ms/op
                 createUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297348
  mean =      3.226 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25919 
    [ 2.500,  5.000) = 265819 
    [ 5.000,  7.500) = 4673 
    [ 7.500, 10.000) = 404 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.187 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     14.723 ms/op
     p(99.9900) =     26.133 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.525 ms/op
    p(100.0000) =     27.525 ms/op


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
# Warmup Iteration   1: 7.410 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.376 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.095 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   5.382 ms/op
                 existUser·p0.999:  13.736 ms/op
                 existUser·p0.9999: 20.010 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.081 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.199 ms/op
                 existUser·p0.95:   3.285 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  12.621 ms/op
                 existUser·p0.9999: 21.929 ms/op
                 existUser·p1.00:   22.577 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  14.729 ms/op
                 existUser·p0.9999: 20.017 ms/op
                 existUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308457
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28763 
    [ 2.500,  5.000) = 274533 
    [ 5.000,  7.500) = 4362 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.273 ms/op
     p(95.0000) =      3.518 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 8.497 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.377 ±(99.9%) 0.010 ms/op
Iteration   1: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.962 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.420 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  12.452 ms/op
                 getUser·p0.9999: 20.209 ms/op
                 getUser·p1.00:   20.939 ms/op

Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  10.057 ms/op
                 getUser·p0.9999: 23.399 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.259 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.169 ms/op
                 getUser·p0.999:  11.663 ms/op
                 getUser·p0.9999: 20.838 ms/op
                 getUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299145
  mean =      3.207 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13419 
    [ 2.500,  5.000) = 277637 
    [ 5.000,  7.500) = 7051 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 160 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 136 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     23.760 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 8.550 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.857 ±(99.9%) 0.013 ms/op
Iteration   1: 3.740 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   7.192 ms/op
                 listUser·p0.999:  15.573 ms/op
                 listUser·p0.9999: 18.820 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   2: 3.803 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 19.005 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   3: 3.738 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 18.055 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255319
  mean =      3.760 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 82 
    [ 2.500,  3.750) = 192157 
    [ 3.750,  5.000) = 54091 
    [ 5.000,  6.250) = 3486 
    [ 6.250,  7.500) = 3413 
    [ 7.500,  8.750) = 1046 
    [ 8.750, 10.000) = 328 
    [10.000, 11.250) = 160 
    [11.250, 12.500) = 77 
    [12.500, 13.750) = 241 
    [13.750, 15.000) = 86 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 99 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.670 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     18.711 ms/op
     p(99.9990) =     19.512 ms/op
     p(99.9999) =     19.595 ms/op
    p(100.0000) =     19.595 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.781 ± 6.341  ops/ms
ClientPb.existUser                       thrpt       3  10.535 ± 3.810  ops/ms
ClientPb.getUser                         thrpt       3   9.937 ± 4.607  ops/ms
ClientPb.listUser                        thrpt       3   8.615 ± 1.861  ops/ms
ClientPb.createUser                       avgt       3   3.132 ± 0.928   ms/op
ClientPb.existUser                        avgt       3   3.089 ± 0.728   ms/op
ClientPb.getUser                          avgt       3   3.169 ± 1.136   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 0.884   ms/op
ClientPb.createUser                     sample  297348   3.226 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.857           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.187           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.596           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.723           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.133           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.525           ms/op
ClientPb.existUser                      sample  308457   3.110 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.117           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.273           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.518           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.041           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.332           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.577           ms/op
ClientPb.getUser                        sample  299145   3.207 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.962           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.354           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.347           ms/op
ClientPb.listUser                       sample  255319   3.760 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.143           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.670           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.059           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.566           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.711           ms/op
ClientPb.listUser:listUser·p1.00        sample          19.595           ms/op
