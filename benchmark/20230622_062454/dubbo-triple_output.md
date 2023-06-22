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
# Warmup Iteration   1: 2.654 ops/ms
# Warmup Iteration   2: 7.055 ops/ms
# Warmup Iteration   3: 9.085 ops/ms
Iteration   1: 9.256 ops/ms
Iteration   2: 9.834 ops/ms
Iteration   3: 9.875 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.655 ±(99.9%) 6.307 ops/ms [Average]
  (min, avg, max) = (9.256, 9.655, 9.875), stdev = 0.346
  CI (99.9%): [3.348, 15.962] (assumes normal distribution)


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
# Warmup Iteration   1: 3.373 ops/ms
# Warmup Iteration   2: 9.005 ops/ms
# Warmup Iteration   3: 10.199 ops/ms
Iteration   1: 10.443 ops/ms
Iteration   2: 10.533 ops/ms
Iteration   3: 10.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.460 ±(99.9%) 1.210 ops/ms [Average]
  (min, avg, max) = (10.403, 10.460, 10.533), stdev = 0.066
  CI (99.9%): [9.249, 11.670] (assumes normal distribution)


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
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 8.534 ops/ms
# Warmup Iteration   3: 9.786 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.500 ops/ms
Iteration   3: 10.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.822 ±(99.9%) 7.177 ops/ms [Average]
  (min, avg, max) = (9.500, 9.822, 10.261), stdev = 0.393
  CI (99.9%): [2.645, 16.999] (assumes normal distribution)


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
# Warmup Iteration   1: 3.475 ops/ms
# Warmup Iteration   2: 7.813 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.480 ops/ms
Iteration   3: 8.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.332 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (8.256, 8.332, 8.480), stdev = 0.128
  CI (99.9%): [6.004, 10.661] (assumes normal distribution)


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.293 ±(99.9%) 0.003 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.272 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.240 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.222, 3.240, 3.272), stdev = 0.028
  CI (99.9%): [2.732, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 7.331 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.335 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
Iteration   1: 3.227 ±(99.9%) 0.007 ms/op
Iteration   2: 3.162 ±(99.9%) 0.002 ms/op
Iteration   3: 3.056 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.148 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.056, 3.148, 3.227), stdev = 0.086
  CI (99.9%): [1.576, 4.720] (assumes normal distribution)


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
# Warmup Iteration   1: 7.901 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.525 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.330 ±(99.9%) 0.003 ms/op
Iteration   1: 3.297 ±(99.9%) 0.004 ms/op
Iteration   2: 3.223 ±(99.9%) 0.005 ms/op
Iteration   3: 3.145 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.222 ±(99.9%) 1.389 ms/op [Average]
  (min, avg, max) = (3.145, 3.222, 3.297), stdev = 0.076
  CI (99.9%): [1.833, 4.611] (assumes normal distribution)


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
# Warmup Iteration   1: 8.811 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.217 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.009 ms/op
Iteration   1: 3.804 ±(99.9%) 0.005 ms/op
Iteration   2: 3.664 ±(99.9%) 0.011 ms/op
Iteration   3: 3.701 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.723 ±(99.9%) 1.321 ms/op [Average]
  (min, avg, max) = (3.664, 3.723, 3.804), stdev = 0.072
  CI (99.9%): [2.402, 5.044] (assumes normal distribution)


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
# Warmup Iteration   1: 8.128 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.613 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.256 ±(99.9%) 0.009 ms/op
Iteration   1: 3.326 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.649 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.265 ms/op
                 createUser·p0.99:   5.808 ms/op
                 createUser·p0.999:  18.308 ms/op
                 createUser·p0.9999: 26.940 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.238 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.940 ms/op
                 createUser·p0.99:   5.442 ms/op
                 createUser·p0.999:  15.237 ms/op
                 createUser·p0.9999: 25.538 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.734 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  16.409 ms/op
                 createUser·p0.9999: 21.873 ms/op
                 createUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292373
  mean =      3.281 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26341 
    [ 2.500,  5.000) = 259643 
    [ 5.000,  7.500) = 5560 
    [ 7.500, 10.000) = 423 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.513 ms/op
     p(99.9000) =     16.712 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.235 ms/op
     p(99.9999) =     27.394 ms/op
    p(100.0000) =     27.394 ms/op


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
# Warmup Iteration   1: 8.067 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.008 ms/op
Iteration   1: 3.186 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.969 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.510 ms/op
                 existUser·p0.95:   4.039 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.765 ms/op
                 existUser·p0.9999: 20.413 ms/op
                 existUser·p1.00:   21.103 ms/op

Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.448 ms/op
                 existUser·p0.999:  13.969 ms/op
                 existUser·p0.9999: 23.099 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.522 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.314 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.274 ms/op
                 existUser·p0.999:  8.990 ms/op
                 existUser·p0.9999: 19.817 ms/op
                 existUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308071
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23137 
    [ 2.500,  5.000) = 278724 
    [ 5.000,  7.500) = 5491 
    [ 7.500, 10.000) = 307 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.342 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.401 ms/op
     p(99.9000) =     12.878 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     23.585 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 8.073 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.215 ±(99.9%) 0.009 ms/op
Iteration   1: 3.219 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  9.623 ms/op
                 getUser·p0.9999: 23.331 ms/op
                 getUser·p1.00:   24.117 ms/op

Iteration   2: 3.233 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.813 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  16.847 ms/op
                 getUser·p0.9999: 25.999 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   3: 3.199 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   5.366 ms/op
                 getUser·p0.999:  10.602 ms/op
                 getUser·p0.9999: 20.874 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298191
  mean =      3.217 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6088 
    [ 2.500,  5.000) = 284370 
    [ 5.000,  7.500) = 6741 
    [ 7.500, 10.000) = 659 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     14.179 ms/op
     p(99.9900) =     24.269 ms/op
     p(99.9990) =     26.674 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


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
# Warmup Iteration   1: 9.383 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.716 ±(99.9%) 0.010 ms/op
Iteration   1: 3.755 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.542 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   3.957 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  14.664 ms/op
                 listUser·p0.9999: 18.969 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.660 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   3.924 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  13.828 ms/op
                 listUser·p0.9999: 15.197 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   3: 3.786 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.787 ms/op
                 listUser·p0.9999: 20.283 ms/op
                 listUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254116
  mean =      3.777 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 247615 
    [ 5.000,  7.500) = 4666 
    [ 7.500, 10.000) = 1054 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 293 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.313 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.655 ± 6.307  ops/ms
ClientPb.existUser                       thrpt       3  10.460 ± 1.210  ops/ms
ClientPb.getUser                         thrpt       3   9.822 ± 7.177  ops/ms
ClientPb.listUser                        thrpt       3   8.332 ± 2.328  ops/ms
ClientPb.createUser                       avgt       3   3.240 ± 0.508   ms/op
ClientPb.existUser                        avgt       3   3.148 ± 1.572   ms/op
ClientPb.getUser                          avgt       3   3.222 ± 1.389   ms/op
ClientPb.listUser                         avgt       3   3.723 ± 1.321   ms/op
ClientPb.createUser                     sample  292373   3.281 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.649           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.666           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.092           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.712           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.625           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.394           ms/op
ClientPb.existUser                      sample  308071   3.113 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.969           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.342           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.401           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.878           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.986           ms/op
ClientPb.getUser                        sample  298191   3.217 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.116           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.179           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.269           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.968           ms/op
ClientPb.listUser                       sample  254116   3.777 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.660           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.914           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.054           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.414           ms/op
