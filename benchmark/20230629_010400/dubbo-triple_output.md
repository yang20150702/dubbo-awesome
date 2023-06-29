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
# Warmup Iteration   1: 2.517 ops/ms
# Warmup Iteration   2: 5.834 ops/ms
# Warmup Iteration   3: 9.047 ops/ms
Iteration   1: 9.699 ops/ms
Iteration   2: 9.417 ops/ms
Iteration   3: 10.237 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.785 ±(99.9%) 7.601 ops/ms [Average]
  (min, avg, max) = (9.417, 9.785, 10.237), stdev = 0.417
  CI (99.9%): [2.183, 17.386] (assumes normal distribution)


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
# Warmup Iteration   1: 3.381 ops/ms
# Warmup Iteration   2: 9.166 ops/ms
# Warmup Iteration   3: 10.129 ops/ms
Iteration   1: 10.100 ops/ms
Iteration   2: 10.442 ops/ms
Iteration   3: 9.985 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.176 ±(99.9%) 4.333 ops/ms [Average]
  (min, avg, max) = (9.985, 10.176, 10.442), stdev = 0.238
  CI (99.9%): [5.842, 14.509] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.414 ops/ms
# Warmup Iteration   2: 8.727 ops/ms
# Warmup Iteration   3: 9.594 ops/ms
Iteration   1: 9.946 ops/ms
Iteration   2: 10.110 ops/ms
Iteration   3: 10.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.059 ±(99.9%) 1.803 ops/ms [Average]
  (min, avg, max) = (9.946, 10.059, 10.123), stdev = 0.099
  CI (99.9%): [8.257, 11.862] (assumes normal distribution)


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
# Warmup Iteration   1: 3.051 ops/ms
# Warmup Iteration   2: 7.246 ops/ms
# Warmup Iteration   3: 8.136 ops/ms
Iteration   1: 8.505 ops/ms
Iteration   2: 8.521 ops/ms
Iteration   3: 8.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.520 ±(99.9%) 0.261 ops/ms [Average]
  (min, avg, max) = (8.505, 8.520, 8.533), stdev = 0.014
  CI (99.9%): [8.259, 8.780] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.372 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.008 ms/op
Iteration   1: 3.333 ±(99.9%) 0.006 ms/op
Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
Iteration   3: 3.167 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.216 ±(99.9%) 1.870 ms/op [Average]
  (min, avg, max) = (3.147, 3.216, 3.333), stdev = 0.102
  CI (99.9%): [1.346, 5.085] (assumes normal distribution)


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
# Warmup Iteration   1: 7.604 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.287 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.004 ms/op
Iteration   1: 3.061 ±(99.9%) 0.003 ms/op
Iteration   2: 3.188 ±(99.9%) 0.004 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 1.903 ms/op [Average]
  (min, avg, max) = (2.981, 3.077, 3.188), stdev = 0.104
  CI (99.9%): [1.173, 4.980] (assumes normal distribution)


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
# Warmup Iteration   1: 8.195 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.541 ±(99.9%) 0.002 ms/op
Iteration   1: 3.199 ±(99.9%) 0.004 ms/op
Iteration   2: 3.155 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.162 ±(99.9%) 0.635 ms/op [Average]
  (min, avg, max) = (3.131, 3.162, 3.199), stdev = 0.035
  CI (99.9%): [2.527, 3.797] (assumes normal distribution)


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
# Warmup Iteration   1: 8.907 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.777 ±(99.9%) 0.009 ms/op
Iteration   1: 3.711 ±(99.9%) 0.011 ms/op
Iteration   2: 3.747 ±(99.9%) 0.011 ms/op
Iteration   3: 3.784 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (3.711, 3.748, 3.784), stdev = 0.036
  CI (99.9%): [3.083, 4.412] (assumes normal distribution)


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
# Warmup Iteration   1: 8.719 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 3.863 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.331 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  10.928 ms/op
                 createUser·p0.9999: 22.676 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   2: 3.297 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  10.631 ms/op
                 createUser·p0.9999: 22.816 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   3: 3.287 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  17.990 ms/op
                 createUser·p0.9999: 24.562 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294156
  mean =      3.263 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16169 
    [ 2.500,  5.000) = 273540 
    [ 5.000,  7.500) = 3694 
    [ 7.500, 10.000) = 297 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 131 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     17.072 ms/op
     p(99.9900) =     22.695 ms/op
     p(99.9990) =     30.386 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.557 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.386 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.051 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  10.732 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.335 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.497 ms/op
                 existUser·p0.9999: 21.529 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  12.370 ms/op
                 existUser·p0.9999: 21.744 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301231
  mean =      3.184 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19569 
    [ 2.500,  5.000) = 274578 
    [ 5.000,  7.500) = 6255 
    [ 7.500, 10.000) = 471 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.944 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     12.206 ms/op
     p(99.9900) =     21.328 ms/op
     p(99.9990) =     22.249 ms/op
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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.521 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.437 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.363 ±(99.9%) 0.011 ms/op
Iteration   1: 3.237 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   4.415 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  11.354 ms/op
                 getUser·p0.9999: 22.204 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.400 ms/op
                 getUser·p0.95:   3.518 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  19.441 ms/op
                 getUser·p0.9999: 22.343 ms/op
                 getUser·p1.00:   22.938 ms/op

Iteration   3: 3.271 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.149 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.038 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  16.663 ms/op
                 getUser·p0.9999: 27.901 ms/op
                 getUser·p1.00:   28.246 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297844
  mean =      3.220 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3248 
    [ 2.500,  5.000) = 287062 
    [ 5.000,  7.500) = 6207 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      6.640 ms/op
     p(99.9000) =     17.995 ms/op
     p(99.9900) =     26.875 ms/op
     p(99.9990) =     28.084 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.410 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.391 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  15.581 ms/op
                 listUser·p0.9999: 21.250 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 3.848 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.142 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.203 ms/op
                 listUser·p0.9999: 21.793 ms/op
                 listUser·p1.00:   24.478 ms/op

Iteration   3: 3.687 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.055 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  14.390 ms/op
                 listUser·p0.9999: 23.735 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252223
  mean =      3.804 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 245151 
    [ 5.000,  7.500) = 4784 
    [ 7.500, 10.000) = 1508 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     15.348 ms/op
     p(99.9900) =     21.802 ms/op
     p(99.9990) =     23.838 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.785 ± 7.601  ops/ms
ClientPb.existUser                       thrpt       3  10.176 ± 4.333  ops/ms
ClientPb.getUser                         thrpt       3  10.059 ± 1.803  ops/ms
ClientPb.listUser                        thrpt       3   8.520 ± 0.261  ops/ms
ClientPb.createUser                       avgt       3   3.216 ± 1.870   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 1.903   ms/op
ClientPb.getUser                          avgt       3   3.162 ± 0.635   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 0.665   ms/op
ClientPb.createUser                     sample  294156   3.263 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.049           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.965           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.072           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.695           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.671           ms/op
ClientPb.existUser                      sample  301231   3.184 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.743           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.547           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.944           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.661           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.206           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.328           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.577           ms/op
ClientPb.getUser                        sample  297844   3.220 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.149           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.494           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.826           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.640           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.995           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.875           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.246           ms/op
ClientPb.listUser                       sample  252223   3.804 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.391           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.104           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.350           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.184           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.348           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.802           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.478           ms/op
