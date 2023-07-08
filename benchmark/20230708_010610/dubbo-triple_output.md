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
# Warmup Iteration   1: 2.521 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 9.338 ops/ms
Iteration   1: 10.161 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 9.965 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.071 ±(99.9%) 1.802 ops/ms [Average]
  (min, avg, max) = (9.965, 10.071, 10.161), stdev = 0.099
  CI (99.9%): [8.269, 11.873] (assumes normal distribution)


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
# Warmup Iteration   1: 3.626 ops/ms
# Warmup Iteration   2: 9.293 ops/ms
# Warmup Iteration   3: 10.165 ops/ms
Iteration   1: 10.014 ops/ms
Iteration   2: 9.958 ops/ms
Iteration   3: 10.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.213 ±(99.9%) 7.198 ops/ms [Average]
  (min, avg, max) = (9.958, 10.213, 10.668), stdev = 0.395
  CI (99.9%): [3.015, 17.411] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ops/ms
# Warmup Iteration   2: 9.037 ops/ms
# Warmup Iteration   3: 9.814 ops/ms
Iteration   1: 10.270 ops/ms
Iteration   2: 10.347 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.223 ±(99.9%) 2.781 ops/ms [Average]
  (min, avg, max) = (10.053, 10.223, 10.347), stdev = 0.152
  CI (99.9%): [7.443, 13.004] (assumes normal distribution)


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
# Warmup Iteration   1: 3.272 ops/ms
# Warmup Iteration   2: 7.815 ops/ms
# Warmup Iteration   3: 8.166 ops/ms
Iteration   1: 8.752 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.472 ±(99.9%) 5.300 ops/ms [Average]
  (min, avg, max) = (8.172, 8.472, 8.752), stdev = 0.291
  CI (99.9%): [3.171, 13.772] (assumes normal distribution)


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
# Warmup Iteration   1: 7.581 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.443 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.212 ±(99.9%) 0.004 ms/op
Iteration   1: 3.307 ±(99.9%) 0.006 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.277 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.225 ±(99.9%) 2.140 ms/op [Average]
  (min, avg, max) = (3.091, 3.225, 3.307), stdev = 0.117
  CI (99.9%): [1.085, 5.366] (assumes normal distribution)


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
# Warmup Iteration   1: 7.103 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.005 ms/op
Iteration   1: 3.025 ±(99.9%) 0.004 ms/op
Iteration   2: 3.075 ±(99.9%) 0.005 ms/op
Iteration   3: 3.094 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.065 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.025, 3.065, 3.094), stdev = 0.035
  CI (99.9%): [2.422, 3.708] (assumes normal distribution)


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
# Warmup Iteration   1: 8.108 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.005 ms/op
Iteration   1: 3.330 ±(99.9%) 0.005 ms/op
Iteration   2: 3.125 ±(99.9%) 0.009 ms/op
Iteration   3: 3.095 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.183 ±(99.9%) 2.335 ms/op [Average]
  (min, avg, max) = (3.095, 3.183, 3.330), stdev = 0.128
  CI (99.9%): [0.848, 5.518] (assumes normal distribution)


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
# Warmup Iteration   1: 9.900 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.733 ±(99.9%) 0.004 ms/op
Iteration   1: 3.729 ±(99.9%) 0.010 ms/op
Iteration   2: 3.719 ±(99.9%) 0.006 ms/op
Iteration   3: 3.663 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.704 ±(99.9%) 0.650 ms/op [Average]
  (min, avg, max) = (3.663, 3.704, 3.729), stdev = 0.036
  CI (99.9%): [3.054, 4.353] (assumes normal distribution)


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
# Warmup Iteration   1: 8.541 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.659 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.009 ms/op
Iteration   1: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.481 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.903 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  13.615 ms/op
                 createUser·p0.9999: 21.026 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  9.890 ms/op
                 createUser·p0.9999: 22.605 ms/op
                 createUser·p1.00:   23.200 ms/op

Iteration   3: 3.096 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.613 ms/op
                 createUser·p0.99:   4.841 ms/op
                 createUser·p0.999:  14.156 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 304099
  mean =      3.153 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22685 
    [ 2.500,  5.000) = 277818 
    [ 5.000,  7.500) = 2818 
    [ 7.500, 10.000) = 378 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 111 
    [20.000, 22.500) = 113 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      5.292 ms/op
     p(99.9000) =     14.023 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     22.902 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 6.707 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.009 ms/op
Iteration   1: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.178 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  9.214 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.137 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.044 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.664 ms/op
                 existUser·p0.999:  8.456 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   24.609 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.208 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.408 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  9.831 ms/op
                 existUser·p0.9999: 23.337 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312246
  mean =      3.072 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20891 
    [ 2.500,  5.000) = 286836 
    [ 5.000,  7.500) = 3820 
    [ 7.500, 10.000) = 410 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 155 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.044 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.355 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      9.269 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     24.601 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 7.175 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
Iteration   1: 3.305 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.792 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  20.065 ms/op
                 getUser·p0.9999: 22.617 ms/op
                 getUser·p1.00:   23.593 ms/op

Iteration   2: 3.202 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.625 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  9.979 ms/op
                 getUser·p0.9999: 23.298 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.232 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.521 ms/op
                 getUser·p0.999:  12.354 ms/op
                 getUser·p0.9999: 20.815 ms/op
                 getUser·p1.00:   21.463 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295824
  mean =      3.246 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12138 
    [ 2.500,  5.000) = 275034 
    [ 5.000,  7.500) = 7692 
    [ 7.500, 10.000) = 497 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.218 ms/op
     p(99.9000) =     17.007 ms/op
     p(99.9900) =     22.525 ms/op
     p(99.9990) =     23.734 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 8.448 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.895 ±(99.9%) 0.012 ms/op
Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   7.070 ms/op
                 listUser·p0.999:  16.073 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   2: 3.854 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.003 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.218 ms/op
                 listUser·p0.99:   6.842 ms/op
                 listUser·p0.999:  12.993 ms/op
                 listUser·p0.9999: 14.369 ms/op
                 listUser·p1.00:   14.762 ms/op

Iteration   3: 3.902 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.430 ms/op
                 listUser·p0.999:  12.928 ms/op
                 listUser·p0.9999: 16.712 ms/op
                 listUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248121
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 237474 
    [ 5.000,  7.500) = 8748 
    [ 7.500, 10.000) = 1216 
    [10.000, 12.500) = 230 
    [12.500, 15.000) = 241 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.287 ms/op
     p(99.9900) =     25.461 ms/op
     p(99.9990) =     26.824 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.071 ± 1.802  ops/ms
ClientPb.existUser                       thrpt       3  10.213 ± 7.198  ops/ms
ClientPb.getUser                         thrpt       3  10.223 ± 2.781  ops/ms
ClientPb.listUser                        thrpt       3   8.472 ± 5.300  ops/ms
ClientPb.createUser                       avgt       3   3.225 ± 2.140   ms/op
ClientPb.existUser                        avgt       3   3.065 ± 0.643   ms/op
ClientPb.getUser                          avgt       3   3.183 ± 2.335   ms/op
ClientPb.listUser                         avgt       3   3.704 ± 0.650   ms/op
ClientPb.createUser                     sample  304099   3.153 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.981           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.129           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.424           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.748           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.023           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.823           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.200           ms/op
ClientPb.existUser                      sample  312246   3.072 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.044           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.355           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.267           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.269           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.101           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  295824   3.246 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.129           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.641           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.268           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.218           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.007           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.525           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.953           ms/op
ClientPb.listUser                       sample  248121   3.868 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.953           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.752           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.293           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.287           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.461           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.034           ms/op
