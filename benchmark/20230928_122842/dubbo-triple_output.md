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
# Warmup Iteration   1: 2.467 ops/ms
# Warmup Iteration   2: 6.542 ops/ms
# Warmup Iteration   3: 9.078 ops/ms
Iteration   1: 9.869 ops/ms
Iteration   2: 9.768 ops/ms
Iteration   3: 9.798 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.812 ±(99.9%) 0.951 ops/ms [Average]
  (min, avg, max) = (9.768, 9.812, 9.869), stdev = 0.052
  CI (99.9%): [8.861, 10.763] (assumes normal distribution)


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
# Warmup Iteration   1: 3.757 ops/ms
# Warmup Iteration   2: 9.472 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.273 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.378 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.293 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (10.229, 10.293, 10.378), stdev = 0.077
  CI (99.9%): [8.893, 11.694] (assumes normal distribution)


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
# Warmup Iteration   1: 3.461 ops/ms
# Warmup Iteration   2: 8.847 ops/ms
# Warmup Iteration   3: 9.872 ops/ms
Iteration   1: 9.975 ops/ms
Iteration   2: 10.038 ops/ms
Iteration   3: 9.482 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.832 ±(99.9%) 5.559 ops/ms [Average]
  (min, avg, max) = (9.482, 9.832, 10.038), stdev = 0.305
  CI (99.9%): [4.273, 15.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.350 ops/ms
# Warmup Iteration   2: 7.632 ops/ms
# Warmup Iteration   3: 8.297 ops/ms
Iteration   1: 8.308 ops/ms
Iteration   2: 8.400 ops/ms
Iteration   3: 8.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.368 ±(99.9%) 0.958 ops/ms [Average]
  (min, avg, max) = (8.308, 8.368, 8.400), stdev = 0.052
  CI (99.9%): [7.410, 9.326] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.390 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.429 ±(99.9%) 0.005 ms/op
Iteration   1: 3.347 ±(99.9%) 0.005 ms/op
Iteration   2: 3.233 ±(99.9%) 0.006 ms/op
Iteration   3: 3.173 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.251 ±(99.9%) 1.613 ms/op [Average]
  (min, avg, max) = (3.173, 3.251, 3.347), stdev = 0.088
  CI (99.9%): [1.638, 4.864] (assumes normal distribution)


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
# Warmup Iteration   1: 7.013 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.005 ms/op
Iteration   1: 3.157 ±(99.9%) 0.005 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.169 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.153 ±(99.9%) 0.315 ms/op [Average]
  (min, avg, max) = (3.135, 3.153, 3.169), stdev = 0.017
  CI (99.9%): [2.839, 3.468] (assumes normal distribution)


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
# Warmup Iteration   1: 7.741 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.004 ms/op
Iteration   1: 3.226 ±(99.9%) 0.002 ms/op
Iteration   2: 3.191 ±(99.9%) 0.004 ms/op
Iteration   3: 3.209 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.208 ±(99.9%) 0.319 ms/op [Average]
  (min, avg, max) = (3.191, 3.208, 3.226), stdev = 0.018
  CI (99.9%): [2.889, 3.528] (assumes normal distribution)


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
# Warmup Iteration   1: 9.238 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.004 ms/op
Iteration   1: 3.939 ±(99.9%) 0.005 ms/op
Iteration   2: 3.869 ±(99.9%) 0.004 ms/op
Iteration   3: 3.803 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.871 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (3.803, 3.871, 3.939), stdev = 0.068
  CI (99.9%): [2.627, 5.114] (assumes normal distribution)


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
# Warmup Iteration   1: 8.168 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
Iteration   1: 3.302 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.479 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   5.186 ms/op
                 createUser·p0.999:  15.091 ms/op
                 createUser·p0.9999: 16.777 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   5.590 ms/op
                 createUser·p0.999:  15.743 ms/op
                 createUser·p0.9999: 19.737 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   3: 3.309 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.112 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.208 ms/op
                 createUser·p0.999:  16.356 ms/op
                 createUser·p0.9999: 21.529 ms/op
                 createUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 291984
  mean =      3.287 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18577 
    [ 2.500,  5.000) = 269656 
    [ 5.000,  7.500) = 2877 
    [ 7.500, 10.000) = 184 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 153 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     15.303 ms/op
     p(99.9900) =     20.506 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.853 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
Iteration   1: 3.215 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  14.669 ms/op
                 existUser·p0.9999: 19.071 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 3.153 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.217 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  16.312 ms/op
                 existUser·p0.9999: 20.148 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   3: 3.185 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  15.142 ms/op
                 existUser·p0.9999: 19.830 ms/op
                 existUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301254
  mean =      3.184 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22029 
    [ 2.500,  5.000) = 273714 
    [ 5.000,  7.500) = 4575 
    [ 7.500, 10.000) = 342 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.217 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     15.200 ms/op
     p(99.9900) =     19.554 ms/op
     p(99.9990) =     21.560 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 7.505 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.297 ±(99.9%) 0.009 ms/op
Iteration   1: 3.407 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  17.077 ms/op
                 getUser·p0.9999: 20.074 ms/op
                 getUser·p1.00:   21.004 ms/op

Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.047 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   5.186 ms/op
                 getUser·p0.999:  13.267 ms/op
                 getUser·p0.9999: 22.317 ms/op
                 getUser·p1.00:   22.708 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.108 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.056 ms/op
                 getUser·p0.99:   5.922 ms/op
                 getUser·p0.999:  18.846 ms/op
                 getUser·p0.9999: 23.396 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 289511
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13816 
    [ 2.500,  5.000) = 268080 
    [ 5.000,  7.500) = 6520 
    [ 7.500, 10.000) = 517 
    [10.000, 12.500) = 136 
    [12.500, 15.000) = 130 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 139 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.047 ms/op
     p(50.0000) =      3.219 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     22.610 ms/op
     p(99.9990) =     24.481 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 9.289 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.013 ms/op
Iteration   1: 3.776 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.379 ms/op
                 listUser·p0.9999: 19.171 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.702 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   6.332 ms/op
                 listUser·p0.999:  13.400 ms/op
                 listUser·p0.9999: 16.210 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.690 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.243 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  15.273 ms/op
                 listUser·p0.9999: 18.461 ms/op
                 listUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 254142
  mean =      3.773 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 248041 
    [ 5.000,  7.500) = 4796 
    [ 7.500, 10.000) = 509 
    [10.000, 12.500) = 303 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     14.074 ms/op
     p(99.9900) =     18.533 ms/op
     p(99.9990) =     20.308 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.812 ± 0.951  ops/ms
ClientPb.existUser                       thrpt       3  10.293 ± 1.400  ops/ms
ClientPb.getUser                         thrpt       3   9.832 ± 5.559  ops/ms
ClientPb.listUser                        thrpt       3   8.368 ± 0.958  ops/ms
ClientPb.createUser                       avgt       3   3.251 ± 1.613   ms/op
ClientPb.existUser                        avgt       3   3.153 ± 0.315   ms/op
ClientPb.getUser                          avgt       3   3.208 ± 0.319   ms/op
ClientPb.listUser                         avgt       3   3.871 ± 1.244   ms/op
ClientPb.createUser                     sample  291984   3.287 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.112           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.244           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.969           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.374           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.506           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.594           ms/op
ClientPb.existUser                      sample  301254   3.184 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.217           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.612           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.200           ms/op
ClientPb.existUser:existUser·p0.9999    sample          19.554           ms/op
ClientPb.existUser:existUser·p1.00      sample          21.692           ms/op
ClientPb.getUser                        sample  289511   3.315 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.047           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.051           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.046           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.170           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.610           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.543           ms/op
ClientPb.listUser                       sample  254142   3.773 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.690           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.108           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.660           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.074           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.533           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.414           ms/op
