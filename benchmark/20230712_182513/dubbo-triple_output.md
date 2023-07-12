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
# Warmup Iteration   1: 2.477 ops/ms
# Warmup Iteration   2: 6.034 ops/ms
# Warmup Iteration   3: 9.184 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.894 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.746 ±(99.9%) 2.443 ops/ms [Average]
  (min, avg, max) = (9.634, 9.746, 9.894), stdev = 0.134
  CI (99.9%): [7.303, 12.189] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.790 ops/ms
# Warmup Iteration   2: 9.407 ops/ms
# Warmup Iteration   3: 10.345 ops/ms
Iteration   1: 10.579 ops/ms
Iteration   2: 10.597 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.569 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (10.533, 10.569, 10.597), stdev = 0.033
  CI (99.9%): [9.966, 11.172] (assumes normal distribution)


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
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 8.899 ops/ms
# Warmup Iteration   3: 9.634 ops/ms
Iteration   1: 9.957 ops/ms
Iteration   2: 10.394 ops/ms
Iteration   3: 10.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.152 ±(99.9%) 4.059 ops/ms [Average]
  (min, avg, max) = (9.957, 10.152, 10.394), stdev = 0.222
  CI (99.9%): [6.092, 14.211] (assumes normal distribution)


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
# Warmup Iteration   1: 3.706 ops/ms
# Warmup Iteration   2: 7.815 ops/ms
# Warmup Iteration   3: 8.004 ops/ms
Iteration   1: 8.290 ops/ms
Iteration   2: 8.495 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.329 ±(99.9%) 2.739 ops/ms [Average]
  (min, avg, max) = (8.203, 8.329, 8.495), stdev = 0.150
  CI (99.9%): [5.590, 11.068] (assumes normal distribution)


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
# Warmup Iteration   1: 7.678 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.326 ±(99.9%) 0.004 ms/op
Iteration   1: 3.187 ±(99.9%) 0.004 ms/op
Iteration   2: 3.243 ±(99.9%) 0.008 ms/op
Iteration   3: 3.240 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.223 ±(99.9%) 0.569 ms/op [Average]
  (min, avg, max) = (3.187, 3.223, 3.243), stdev = 0.031
  CI (99.9%): [2.654, 3.792] (assumes normal distribution)


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
# Warmup Iteration   1: 8.002 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.436 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.002 ms/op
Iteration   1: 3.087 ±(99.9%) 0.009 ms/op
Iteration   2: 3.118 ±(99.9%) 0.003 ms/op
Iteration   3: 3.072 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.092 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.072, 3.092, 3.118), stdev = 0.023
  CI (99.9%): [2.667, 3.518] (assumes normal distribution)


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
# Warmup Iteration   1: 8.746 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.004 ms/op
Iteration   1: 3.307 ±(99.9%) 0.002 ms/op
Iteration   2: 3.169 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.214 ±(99.9%) 1.464 ms/op [Average]
  (min, avg, max) = (3.167, 3.214, 3.307), stdev = 0.080
  CI (99.9%): [1.750, 4.679] (assumes normal distribution)


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
# Warmup Iteration   1: 9.709 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.892 ±(99.9%) 0.003 ms/op
Iteration   1: 3.827 ±(99.9%) 0.008 ms/op
Iteration   2: 3.746 ±(99.9%) 0.009 ms/op
Iteration   3: 3.839 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.804 ±(99.9%) 0.922 ms/op [Average]
  (min, avg, max) = (3.746, 3.804, 3.839), stdev = 0.051
  CI (99.9%): [2.882, 4.726] (assumes normal distribution)


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
# Warmup Iteration   1: 8.671 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
Iteration   1: 3.233 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.165 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  14.852 ms/op
                 createUser·p0.9999: 22.155 ms/op
                 createUser·p1.00:   23.265 ms/op

Iteration   2: 3.290 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.580 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.223 ms/op
                 createUser·p0.9999: 20.751 ms/op
                 createUser·p1.00:   21.135 ms/op

Iteration   3: 3.252 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.462 ms/op
                 createUser·p0.50:   3.174 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  15.115 ms/op
                 createUser·p0.9999: 23.658 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294521
  mean =      3.258 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13611 
    [ 2.500,  5.000) = 274499 
    [ 5.000,  7.500) = 5332 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     22.202 ms/op
     p(99.9990) =     23.993 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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
# Warmup Iteration   1: 8.398 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.132 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.391 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  9.454 ms/op
                 existUser·p0.9999: 21.295 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.260 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.690 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  13.833 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   24.445 ms/op

Iteration   3: 3.113 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.026 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   6.169 ms/op
                 existUser·p0.999:  13.812 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   25.821 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302106
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15576 
    [ 2.500,  5.000) = 280576 
    [ 5.000,  7.500) = 4888 
    [ 7.500, 10.000) = 584 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     13.317 ms/op
     p(99.9900) =     23.107 ms/op
     p(99.9990) =     24.739 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


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
# Warmup Iteration   1: 8.286 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.011 ms/op
Iteration   1: 3.260 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.539 ms/op
                 getUser·p0.999:  14.407 ms/op
                 getUser·p0.9999: 25.172 ms/op
                 getUser·p1.00:   29.622 ms/op

Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   5.743 ms/op
                 getUser·p0.999:  20.185 ms/op
                 getUser·p0.9999: 29.360 ms/op
                 getUser·p1.00:   29.786 ms/op

Iteration   3: 3.265 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.125 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  15.254 ms/op
                 getUser·p0.9999: 20.553 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295629
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7610 
    [ 2.500,  5.000) = 281091 
    [ 5.000,  7.500) = 5783 
    [ 7.500, 10.000) = 654 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     17.379 ms/op
     p(99.9900) =     28.060 ms/op
     p(99.9990) =     29.691 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 9.066 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.013 ms/op
Iteration   1: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.067 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.609 ms/op
                 listUser·p0.9999: 21.346 ms/op
                 listUser·p1.00:   23.298 ms/op

Iteration   2: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   7.491 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 18.208 ms/op
                 listUser·p1.00:   19.431 ms/op

Iteration   3: 3.862 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  13.058 ms/op
                 listUser·p0.9999: 14.322 ms/op
                 listUser·p1.00:   14.795 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251286
  mean =      3.815 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74 
    [ 2.500,  5.000) = 243685 
    [ 5.000,  7.500) = 5633 
    [ 7.500, 10.000) = 1130 
    [10.000, 12.500) = 304 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.333 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     14.189 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     22.738 ms/op
     p(99.9999) =     23.298 ms/op
    p(100.0000) =     23.298 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.746 ± 2.443  ops/ms
ClientPb.existUser                       thrpt       3  10.569 ± 0.603  ops/ms
ClientPb.getUser                         thrpt       3  10.152 ± 4.059  ops/ms
ClientPb.listUser                        thrpt       3   8.329 ± 2.739  ops/ms
ClientPb.createUser                       avgt       3   3.223 ± 0.569   ms/op
ClientPb.existUser                        avgt       3   3.092 ± 0.425   ms/op
ClientPb.getUser                          avgt       3   3.214 ± 1.464   ms/op
ClientPb.listUser                         avgt       3   3.804 ± 0.922   ms/op
ClientPb.createUser                     sample  294521   3.258 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.580           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.106           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.202           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.150           ms/op
ClientPb.existUser                      sample  302106   3.176 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.849           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.097           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.469           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.879           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.317           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.107           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.821           ms/op
ClientPb.getUser                        sample  295629   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.113           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.592           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.379           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.060           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.786           ms/op
ClientPb.listUser                       sample  251286   3.815 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.333           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.189           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.087           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.298           ms/op
