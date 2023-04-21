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
# Warmup Iteration   1: 2.171 ops/ms
# Warmup Iteration   2: 5.998 ops/ms
# Warmup Iteration   3: 8.694 ops/ms
Iteration   1: 9.193 ops/ms
Iteration   2: 9.329 ops/ms
Iteration   3: 9.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.324 ±(99.9%) 2.355 ops/ms [Average]
  (min, avg, max) = (9.193, 9.324, 9.451), stdev = 0.129
  CI (99.9%): [6.969, 11.679] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.068 ops/ms
# Warmup Iteration   2: 9.042 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.965 ops/ms
Iteration   2: 10.146 ops/ms
Iteration   3: 9.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.904 ±(99.9%) 5.050 ops/ms [Average]
  (min, avg, max) = (9.602, 9.904, 10.146), stdev = 0.277
  CI (99.9%): [4.854, 14.954] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.926 ops/ms
# Warmup Iteration   2: 8.363 ops/ms
# Warmup Iteration   3: 9.377 ops/ms
Iteration   1: 9.224 ops/ms
Iteration   2: 9.586 ops/ms
Iteration   3: 9.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.392 ±(99.9%) 3.328 ops/ms [Average]
  (min, avg, max) = (9.224, 9.392, 9.586), stdev = 0.182
  CI (99.9%): [6.064, 12.720] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.020 ops/ms
# Warmup Iteration   2: 7.421 ops/ms
# Warmup Iteration   3: 7.765 ops/ms
Iteration   1: 7.975 ops/ms
Iteration   2: 8.077 ops/ms
Iteration   3: 8.010 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.021 ±(99.9%) 0.945 ops/ms [Average]
  (min, avg, max) = (7.975, 8.021, 8.077), stdev = 0.052
  CI (99.9%): [7.076, 8.966] (assumes normal distribution)


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
# Warmup Iteration   1: 8.861 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.715 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.424 ±(99.9%) 0.008 ms/op
Iteration   1: 3.347 ±(99.9%) 0.009 ms/op
Iteration   2: 3.318 ±(99.9%) 0.014 ms/op
Iteration   3: 3.358 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.341 ±(99.9%) 0.375 ms/op [Average]
  (min, avg, max) = (3.318, 3.341, 3.358), stdev = 0.021
  CI (99.9%): [2.966, 3.716] (assumes normal distribution)


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
# Warmup Iteration   1: 8.992 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.467 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.451 ±(99.9%) 0.004 ms/op
Iteration   1: 3.306 ±(99.9%) 0.009 ms/op
Iteration   2: 3.186 ±(99.9%) 0.008 ms/op
Iteration   3: 3.325 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.273 ±(99.9%) 1.375 ms/op [Average]
  (min, avg, max) = (3.186, 3.273, 3.325), stdev = 0.075
  CI (99.9%): [1.897, 4.648] (assumes normal distribution)


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.006 ms/op
Iteration   1: 3.409 ±(99.9%) 0.003 ms/op
Iteration   2: 3.228 ±(99.9%) 0.007 ms/op
Iteration   3: 3.428 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.355 ±(99.9%) 2.015 ms/op [Average]
  (min, avg, max) = (3.228, 3.355, 3.428), stdev = 0.110
  CI (99.9%): [1.340, 5.369] (assumes normal distribution)


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
# Warmup Iteration   1: 11.148 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.327 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.005 ms/op
Iteration   1: 4.458 ±(99.9%) 0.011 ms/op
Iteration   2: 4.163 ±(99.9%) 0.012 ms/op
Iteration   3: 3.915 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.179 ±(99.9%) 4.960 ms/op [Average]
  (min, avg, max) = (3.915, 4.179, 4.458), stdev = 0.272
  CI (99.9%): [≈ 0, 9.139] (assumes normal distribution)


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
# Warmup Iteration   1: 8.894 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
Iteration   1: 3.274 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.288 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.514 ms/op
                 createUser·p0.99:   5.349 ms/op
                 createUser·p0.999:  11.212 ms/op
                 createUser·p0.9999: 22.290 ms/op
                 createUser·p1.00:   22.905 ms/op

Iteration   2: 3.420 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.282 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  21.689 ms/op
                 createUser·p0.9999: 25.777 ms/op
                 createUser·p1.00:   26.444 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.010 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.947 ms/op
                 createUser·p0.999:  17.539 ms/op
                 createUser·p0.9999: 24.396 ms/op
                 createUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286155
  mean =      3.353 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10153 
    [ 2.500,  5.000) = 271021 
    [ 5.000,  7.500) = 4165 
    [ 7.500, 10.000) = 383 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     17.669 ms/op
     p(99.9900) =     24.851 ms/op
     p(99.9990) =     26.270 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 8.112 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.010 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.225 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  10.863 ms/op
                 existUser·p0.9999: 25.731 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   2: 3.277 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   6.300 ms/op
                 existUser·p0.999:  15.448 ms/op
                 existUser·p0.9999: 24.910 ms/op
                 existUser·p1.00:   26.018 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.487 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  8.700 ms/op
                 existUser·p0.9999: 27.229 ms/op
                 existUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291509
  mean =      3.291 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13274 
    [ 2.500,  5.000) = 270963 
    [ 5.000,  7.500) = 6343 
    [ 7.500, 10.000) = 551 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 118 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.808 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     26.073 ms/op
     p(99.9990) =     27.462 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.208 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.674 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.495 ±(99.9%) 0.011 ms/op
Iteration   1: 3.424 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   6.930 ms/op
                 getUser·p0.999:  19.908 ms/op
                 getUser·p0.9999: 23.744 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.326 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.907 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  20.847 ms/op
                 getUser·p0.9999: 24.962 ms/op
                 getUser·p1.00:   25.461 ms/op

Iteration   3: 3.366 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.575 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  15.122 ms/op
                 getUser·p0.9999: 27.001 ms/op
                 getUser·p1.00:   27.591 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284571
  mean =      3.371 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9099 
    [ 2.500,  5.000) = 265674 
    [ 5.000,  7.500) = 8547 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.907 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.589 ms/op
     p(99.9000) =     15.155 ms/op
     p(99.9900) =     25.136 ms/op
     p(99.9990) =     27.460 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


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
# Warmup Iteration   1: 10.997 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.421 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
Iteration   1: 3.874 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.259 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 22.282 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   2: 3.948 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  15.532 ms/op
                 listUser·p0.9999: 24.160 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.567 ms/op
                 listUser·p0.9999: 17.816 ms/op
                 listUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246280
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 239770 
    [ 5.000,  7.500) = 4407 
    [ 7.500, 10.000) = 1314 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 270 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.559 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      7.137 ms/op
     p(99.9000) =     15.577 ms/op
     p(99.9900) =     22.765 ms/op
     p(99.9990) =     25.708 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.324 ± 2.355  ops/ms
ClientPb.existUser                       thrpt       3   9.904 ± 5.050  ops/ms
ClientPb.getUser                         thrpt       3   9.392 ± 3.328  ops/ms
ClientPb.listUser                        thrpt       3   8.021 ± 0.945  ops/ms
ClientPb.createUser                       avgt       3   3.341 ± 0.375   ms/op
ClientPb.existUser                        avgt       3   3.273 ± 1.375   ms/op
ClientPb.getUser                          avgt       3   3.355 ± 2.015   ms/op
ClientPb.listUser                         avgt       3   4.179 ± 4.960   ms/op
ClientPb.createUser                     sample  286155   3.353 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.010           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.256           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.772           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.121           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.669           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.851           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.444           ms/op
ClientPb.existUser                      sample  291509   3.291 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.629           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.808           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.452           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.073           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.525           ms/op
ClientPb.getUser                        sample  284571   3.371 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.907           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.752           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.589           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.155           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.136           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.591           ms/op
ClientPb.listUser                       sample  246280   3.892 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.559           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.736           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.137           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.577           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.765           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
