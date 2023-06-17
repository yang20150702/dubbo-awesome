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
# Warmup Iteration   1: 2.305 ops/ms
# Warmup Iteration   2: 6.036 ops/ms
# Warmup Iteration   3: 8.006 ops/ms
Iteration   1: 9.231 ops/ms
Iteration   2: 9.504 ops/ms
Iteration   3: 9.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.267 ±(99.9%) 4.038 ops/ms [Average]
  (min, avg, max) = (9.066, 9.267, 9.504), stdev = 0.221
  CI (99.9%): [5.229, 13.306] (assumes normal distribution)


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
# Warmup Iteration   1: 3.364 ops/ms
# Warmup Iteration   2: 9.040 ops/ms
# Warmup Iteration   3: 9.115 ops/ms
Iteration   1: 9.491 ops/ms
Iteration   2: 9.243 ops/ms
Iteration   3: 9.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.376 ±(99.9%) 2.285 ops/ms [Average]
  (min, avg, max) = (9.243, 9.376, 9.491), stdev = 0.125
  CI (99.9%): [7.091, 11.661] (assumes normal distribution)


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
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 8.627 ops/ms
# Warmup Iteration   3: 9.475 ops/ms
Iteration   1: 9.126 ops/ms
Iteration   2: 9.575 ops/ms
Iteration   3: 9.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.308 ±(99.9%) 4.303 ops/ms [Average]
  (min, avg, max) = (9.126, 9.308, 9.575), stdev = 0.236
  CI (99.9%): [5.005, 13.612] (assumes normal distribution)


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
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 6.997 ops/ms
# Warmup Iteration   3: 7.737 ops/ms
Iteration   1: 8.001 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.003 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.009 ±(99.9%) 0.215 ops/ms [Average]
  (min, avg, max) = (8.001, 8.009, 8.022), stdev = 0.012
  CI (99.9%): [7.793, 8.224] (assumes normal distribution)


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
# Warmup Iteration   1: 10.141 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.633 ±(99.9%) 0.004 ms/op
Iteration   1: 3.483 ±(99.9%) 0.006 ms/op
Iteration   2: 3.469 ±(99.9%) 0.004 ms/op
Iteration   3: 3.372 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.441 ±(99.9%) 1.105 ms/op [Average]
  (min, avg, max) = (3.372, 3.441, 3.483), stdev = 0.061
  CI (99.9%): [2.336, 4.546] (assumes normal distribution)


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
# Warmup Iteration   1: 8.692 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.287 ±(99.9%) 0.005 ms/op
Iteration   1: 3.292 ±(99.9%) 0.006 ms/op
Iteration   2: 3.284 ±(99.9%) 0.005 ms/op
Iteration   3: 3.270 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.282 ±(99.9%) 0.205 ms/op [Average]
  (min, avg, max) = (3.270, 3.282, 3.292), stdev = 0.011
  CI (99.9%): [3.077, 3.487] (assumes normal distribution)


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
# Warmup Iteration   1: 9.852 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.003 ms/op
Iteration   1: 3.425 ±(99.9%) 0.004 ms/op
Iteration   2: 3.493 ±(99.9%) 0.007 ms/op
Iteration   3: 3.416 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.445 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (3.416, 3.445, 3.493), stdev = 0.042
  CI (99.9%): [2.674, 4.216] (assumes normal distribution)


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
# Warmup Iteration   1: 10.845 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.542 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.219 ±(99.9%) 0.005 ms/op
Iteration   1: 4.075 ±(99.9%) 0.009 ms/op
Iteration   2: 3.991 ±(99.9%) 0.011 ms/op
Iteration   3: 3.979 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.015 ±(99.9%) 0.959 ms/op [Average]
  (min, avg, max) = (3.979, 4.015, 4.075), stdev = 0.053
  CI (99.9%): [3.056, 4.974] (assumes normal distribution)


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
# Warmup Iteration   1: 10.727 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.762 ±(99.9%) 0.013 ms/op
Iteration   1: 3.351 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.952 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  21.299 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.756 ms/op

Iteration   2: 3.373 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.149 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   5.718 ms/op
                 createUser·p0.999:  21.486 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   27.066 ms/op

Iteration   3: 3.430 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.693 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 25.254 ms/op
                 createUser·p1.00:   25.985 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283327
  mean =      3.384 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13281 
    [ 2.500,  5.000) = 264621 
    [ 5.000,  7.500) = 4602 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 48 

  Percentiles, ms/op:
      p(0.0000) =      1.149 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     19.814 ms/op
     p(99.9900) =     25.199 ms/op
     p(99.9990) =     27.006 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 8.315 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.009 ms/op
Iteration   1: 3.280 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.483 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  12.549 ms/op
                 existUser·p0.9999: 22.528 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   2: 3.323 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.417 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  19.253 ms/op
                 existUser·p0.9999: 27.623 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.403 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.698 ms/op
                 existUser·p0.50:   3.248 ms/op
                 existUser·p0.90:   4.121 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 25.219 ms/op
                 existUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287628
  mean =      3.335 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10294 
    [ 2.500,  5.000) = 271237 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 633 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     26.255 ms/op
     p(99.9990) =     27.808 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 9.914 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.840 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.457 ±(99.9%) 0.010 ms/op
Iteration   1: 3.607 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.391 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.784 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  19.367 ms/op
                 getUser·p0.9999: 26.956 ms/op
                 getUser·p1.00:   27.754 ms/op

Iteration   2: 3.349 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.907 ms/op
                 getUser·p0.999:  21.547 ms/op
                 getUser·p0.9999: 24.525 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.479 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  17.634 ms/op
                 getUser·p0.9999: 24.296 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275986
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11612 
    [ 2.500,  5.000) = 256461 
    [ 5.000,  7.500) = 6727 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     25.192 ms/op
     p(99.9990) =     27.672 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 10.800 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.636 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
Iteration   1: 4.188 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.815 ms/op
                 listUser·p0.999:  20.809 ms/op
                 listUser·p0.9999: 23.912 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 3.904 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.614 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.189 ms/op
                 listUser·p0.9999: 14.972 ms/op
                 listUser·p1.00:   15.106 ms/op

Iteration   3: 3.904 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   6.994 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 19.137 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240026
  mean =      3.994 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47 
    [ 2.500,  5.000) = 231601 
    [ 5.000,  7.500) = 6339 
    [ 7.500, 10.000) = 1366 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 235 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.614 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.193 ms/op
     p(99.9000) =     15.368 ms/op
     p(99.9900) =     23.068 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.267 ± 4.038  ops/ms
ClientPb.existUser                       thrpt       3   9.376 ± 2.285  ops/ms
ClientPb.getUser                         thrpt       3   9.308 ± 4.303  ops/ms
ClientPb.listUser                        thrpt       3   8.009 ± 0.215  ops/ms
ClientPb.createUser                       avgt       3   3.441 ± 1.105   ms/op
ClientPb.existUser                        avgt       3   3.282 ± 0.205   ms/op
ClientPb.getUser                          avgt       3   3.445 ± 0.771   ms/op
ClientPb.listUser                         avgt       3   4.015 ± 0.959   ms/op
ClientPb.createUser                     sample  283327   3.384 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.149           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.100           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.814           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.199           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.066           ms/op
ClientPb.existUser                      sample  287628   3.335 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.417           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.207           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.809           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.337           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.255           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.049           ms/op
ClientPb.getUser                        sample  275986   3.475 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.014           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.579           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.185           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.891           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.192           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  240026   3.994 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.614           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.867           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.399           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.193           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.368           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.068           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
