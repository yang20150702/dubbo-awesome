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
# Warmup Iteration   1: 2.405 ops/ms
# Warmup Iteration   2: 5.873 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 9.955 ops/ms
Iteration   2: 9.735 ops/ms
Iteration   3: 9.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.768 ±(99.9%) 3.146 ops/ms [Average]
  (min, avg, max) = (9.615, 9.768, 9.955), stdev = 0.172
  CI (99.9%): [6.623, 12.914] (assumes normal distribution)


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
# Warmup Iteration   1: 3.181 ops/ms
# Warmup Iteration   2: 9.472 ops/ms
# Warmup Iteration   3: 9.960 ops/ms
Iteration   1: 9.710 ops/ms
Iteration   2: 9.556 ops/ms
Iteration   3: 9.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.753 ±(99.9%) 4.043 ops/ms [Average]
  (min, avg, max) = (9.556, 9.753, 9.993), stdev = 0.222
  CI (99.9%): [5.710, 13.796] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.711 ops/ms
# Warmup Iteration   2: 8.601 ops/ms
# Warmup Iteration   3: 9.247 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.524 ops/ms
Iteration   3: 9.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.385 ±(99.9%) 2.356 ops/ms [Average]
  (min, avg, max) = (9.269, 9.385, 9.524), stdev = 0.129
  CI (99.9%): [7.029, 11.741] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.512 ops/ms
# Warmup Iteration   2: 6.491 ops/ms
# Warmup Iteration   3: 7.924 ops/ms
Iteration   1: 8.179 ops/ms
Iteration   2: 7.732 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.961 ±(99.9%) 4.081 ops/ms [Average]
  (min, avg, max) = (7.732, 7.961, 8.179), stdev = 0.224
  CI (99.9%): [3.880, 12.041] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.908 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.005 ms/op
Iteration   1: 3.502 ±(99.9%) 0.006 ms/op
Iteration   2: 3.446 ±(99.9%) 0.004 ms/op
Iteration   3: 3.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.412, 3.453, 3.502), stdev = 0.045
  CI (99.9%): [2.632, 4.274] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.803 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.490 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.372 ±(99.9%) 0.003 ms/op
Iteration   1: 3.323 ±(99.9%) 0.003 ms/op
Iteration   2: 3.346 ±(99.9%) 0.005 ms/op
Iteration   3: 3.307 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.325 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.307, 3.325, 3.346), stdev = 0.019
  CI (99.9%): [2.971, 3.680] (assumes normal distribution)


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
# Warmup Iteration   1: 9.430 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.558 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.003 ms/op
Iteration   1: 3.426 ±(99.9%) 0.003 ms/op
Iteration   2: 3.408 ±(99.9%) 0.005 ms/op
Iteration   3: 3.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.428 ±(99.9%) 0.402 ms/op [Average]
  (min, avg, max) = (3.408, 3.428, 3.451), stdev = 0.022
  CI (99.9%): [3.026, 3.830] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.295 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.661 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.052 ±(99.9%) 0.006 ms/op
Iteration   1: 4.085 ±(99.9%) 0.005 ms/op
Iteration   2: 4.180 ±(99.9%) 0.006 ms/op
Iteration   3: 4.042 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.102 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (4.042, 4.102, 4.180), stdev = 0.071
  CI (99.9%): [2.815, 5.389] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.831 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.794 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.011 ms/op
Iteration   1: 3.411 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   7.348 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 24.400 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.386 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.141 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.141 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  20.982 ms/op
                 createUser·p0.9999: 23.724 ms/op
                 createUser·p1.00:   24.084 ms/op

Iteration   3: 3.398 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.268 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  18.153 ms/op
                 createUser·p0.9999: 25.321 ms/op
                 createUser·p1.00:   25.723 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282269
  mean =      3.398 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10424 
    [ 2.500,  5.000) = 263282 
    [ 5.000,  7.500) = 7061 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 138 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     18.407 ms/op
     p(99.9900) =     24.437 ms/op
     p(99.9990) =     25.630 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


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
# Warmup Iteration   1: 9.435 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.510 ±(99.9%) 0.011 ms/op
Iteration   1: 3.290 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.366 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.112 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  10.728 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.322 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  20.120 ms/op
                 existUser·p0.9999: 30.573 ms/op
                 existUser·p1.00:   31.883 ms/op

Iteration   3: 3.385 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  17.302 ms/op
                 existUser·p0.9999: 24.236 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287983
  mean =      3.332 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14873 
    [ 2.500,  5.000) = 266051 
    [ 5.000,  7.500) = 5575 
    [ 7.500, 10.000) = 912 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 7 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     18.843 ms/op
     p(99.9900) =     24.754 ms/op
     p(99.9990) =     31.425 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


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
# Warmup Iteration   1: 8.330 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.519 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.010 ms/op
Iteration   1: 3.294 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.186 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.358 ms/op
                 getUser·p0.99:   6.835 ms/op
                 getUser·p0.999:  17.725 ms/op
                 getUser·p0.9999: 20.480 ms/op
                 getUser·p1.00:   20.840 ms/op

Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  15.614 ms/op
                 getUser·p0.9999: 21.802 ms/op
                 getUser·p1.00:   22.184 ms/op

Iteration   3: 3.353 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.008 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   4.317 ms/op
                 getUser·p0.99:   6.996 ms/op
                 getUser·p0.999:  17.092 ms/op
                 getUser·p0.9999: 22.327 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290721
  mean =      3.300 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11022 
    [ 2.500,  5.000) = 269452 
    [ 5.000,  7.500) = 8735 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 139 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.008 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     21.463 ms/op
     p(99.9990) =     22.682 ms/op
     p(99.9999) =     22.905 ms/op
    p(100.0000) =     22.905 ms/op


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
# Warmup Iteration   1: 9.843 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.171 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.011 ms/op
Iteration   1: 3.832 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  16.032 ms/op
                 listUser·p0.9999: 22.353 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.888 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.563 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.320 ms/op
                 listUser·p0.9999: 20.531 ms/op
                 listUser·p1.00:   28.115 ms/op

Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.831 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   7.242 ms/op
                 listUser·p0.999:  13.775 ms/op
                 listUser·p0.9999: 15.286 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248992
  mean =      3.855 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 85 
    [ 2.500,  5.000) = 240490 
    [ 5.000,  7.500) = 5875 
    [ 7.500, 10.000) = 1538 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 472 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.563 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.528 ms/op
     p(99.9000) =     14.123 ms/op
     p(99.9900) =     21.892 ms/op
     p(99.9990) =     26.428 ms/op
     p(99.9999) =     28.115 ms/op
    p(100.0000) =     28.115 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.768 ± 3.146  ops/ms
ClientPb.existUser                       thrpt       3   9.753 ± 4.043  ops/ms
ClientPb.getUser                         thrpt       3   9.385 ± 2.356  ops/ms
ClientPb.listUser                        thrpt       3   7.961 ± 4.081  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 0.821   ms/op
ClientPb.existUser                        avgt       3   3.325 ± 0.355   ms/op
ClientPb.getUser                          avgt       3   3.428 ± 0.402   ms/op
ClientPb.listUser                         avgt       3   4.102 ± 1.287   ms/op
ClientPb.createUser                     sample  282269   3.398 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.141           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.865           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.407           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.437           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.723           ms/op
ClientPb.existUser                      sample  287983   3.332 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.799           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.843           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.754           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.883           ms/op
ClientPb.getUser                        sample  290721   3.300 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.008           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.162           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.662           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.652           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.105           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.463           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.905           ms/op
ClientPb.listUser                       sample  248992   3.855 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.563           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.123           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.892           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.115           ms/op
