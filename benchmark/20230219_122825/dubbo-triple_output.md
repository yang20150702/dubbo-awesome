# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.388 ops/ms
# Warmup Iteration   2: 6.268 ops/ms
# Warmup Iteration   3: 9.125 ops/ms
Iteration   1: 10.174 ops/ms
Iteration   2: 9.395 ops/ms
Iteration   3: 10.043 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.871 ±(99.9%) 7.605 ops/ms [Average]
  (min, avg, max) = (9.395, 9.871, 10.174), stdev = 0.417
  CI (99.9%): [2.265, 17.476] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.255 ops/ms
# Warmup Iteration   2: 9.591 ops/ms
# Warmup Iteration   3: 9.418 ops/ms
Iteration   1: 10.430 ops/ms
Iteration   2: 10.353 ops/ms
Iteration   3: 10.409 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.397 ±(99.9%) 0.726 ops/ms [Average]
  (min, avg, max) = (10.353, 10.397, 10.430), stdev = 0.040
  CI (99.9%): [9.671, 11.123] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.596 ops/ms
# Warmup Iteration   2: 8.988 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 9.971 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 9.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.048 ±(99.9%) 2.589 ops/ms [Average]
  (min, avg, max) = (9.961, 10.048, 10.211), stdev = 0.142
  CI (99.9%): [7.458, 12.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.540 ops/ms
# Warmup Iteration   2: 8.044 ops/ms
# Warmup Iteration   3: 8.479 ops/ms
Iteration   1: 8.283 ops/ms
Iteration   2: 8.630 ops/ms
Iteration   3: 8.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.518 ±(99.9%) 3.701 ops/ms [Average]
  (min, avg, max) = (8.283, 8.518, 8.639), stdev = 0.203
  CI (99.9%): [4.817, 12.218] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.334 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.427 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.279 ±(99.9%) 0.002 ms/op
Iteration   1: 3.149 ±(99.9%) 0.007 ms/op
Iteration   2: 3.170 ±(99.9%) 0.005 ms/op
Iteration   3: 3.053 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.124 ±(99.9%) 1.135 ms/op [Average]
  (min, avg, max) = (3.053, 3.124, 3.170), stdev = 0.062
  CI (99.9%): [1.989, 4.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.422 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.320 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.162 ±(99.9%) 0.002 ms/op
Iteration   1: 3.161 ±(99.9%) 0.004 ms/op
Iteration   2: 3.046 ±(99.9%) 0.007 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.069 ±(99.9%) 1.498 ms/op [Average]
  (min, avg, max) = (3.002, 3.069, 3.161), stdev = 0.082
  CI (99.9%): [1.572, 4.567] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.272 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.422 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.367 ±(99.9%) 0.003 ms/op
Iteration   1: 3.221 ±(99.9%) 0.004 ms/op
Iteration   2: 3.227 ±(99.9%) 0.006 ms/op
Iteration   3: 3.198 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.215 ±(99.9%) 0.272 ms/op [Average]
  (min, avg, max) = (3.198, 3.215, 3.227), stdev = 0.015
  CI (99.9%): [2.944, 3.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.553 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.829 ±(99.9%) 0.006 ms/op
Iteration   1: 3.777 ±(99.9%) 0.005 ms/op
Iteration   2: 3.658 ±(99.9%) 0.008 ms/op
Iteration   3: 3.700 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.712 ±(99.9%) 1.102 ms/op [Average]
  (min, avg, max) = (3.658, 3.712, 3.777), stdev = 0.060
  CI (99.9%): [2.610, 4.814] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.305 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.711 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.295 ±(99.9%) 0.009 ms/op
Iteration   1: 3.177 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  11.911 ms/op
                 createUser·p0.9999: 19.626 ms/op
                 createUser·p1.00:   20.349 ms/op

Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.567 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.731 ms/op
                 createUser·p0.99:   4.767 ms/op
                 createUser·p0.999:  8.978 ms/op
                 createUser·p0.9999: 23.849 ms/op
                 createUser·p1.00:   25.133 ms/op

Iteration   3: 3.185 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.399 ms/op
                 createUser·p0.999:  15.663 ms/op
                 createUser·p0.9999: 22.053 ms/op
                 createUser·p1.00:   22.544 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303088
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15853 
    [ 2.500,  5.000) = 282573 
    [ 5.000,  7.500) = 3544 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 183 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      5.448 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.278 ms/op
     p(99.9999) =     25.133 ms/op
    p(100.0000) =     25.133 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.469 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.319 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.170 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 20.685 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.026 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.158 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  9.974 ms/op
                 existUser·p0.9999: 21.294 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   3: 3.019 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.145 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  14.853 ms/op
                 existUser·p0.9999: 21.444 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 317421
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29080 
    [ 2.500,  5.000) = 284715 
    [ 5.000,  7.500) = 2956 
    [ 7.500, 10.000) = 236 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 141 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.976 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.215 ms/op
     p(95.0000) =      3.473 ms/op
     p(99.0000) =      5.079 ms/op
     p(99.9000) =     14.420 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     22.657 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.122 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.439 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.428 ±(99.9%) 0.011 ms/op
Iteration   1: 3.115 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   5.890 ms/op
                 getUser·p0.999:  14.221 ms/op
                 getUser·p0.9999: 20.387 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.423 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  19.792 ms/op
                 getUser·p0.9999: 23.290 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   3: 3.169 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.141 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  12.554 ms/op
                 getUser·p0.9999: 18.962 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 305924
  mean =      3.136 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8642 
    [ 2.500,  5.000) = 290886 
    [ 5.000,  7.500) = 5362 
    [ 7.500, 10.000) = 631 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 126 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.141 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.441 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      5.718 ms/op
     p(99.9000) =     15.831 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.531 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.567 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.819 ±(99.9%) 0.011 ms/op
Iteration   1: 3.710 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.035 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  14.578 ms/op
                 listUser·p0.9999: 18.793 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 3.713 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   6.732 ms/op
                 listUser·p0.999:  13.255 ms/op
                 listUser·p0.9999: 16.803 ms/op
                 listUser·p1.00:   17.433 ms/op

Iteration   3: 3.772 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.236 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.260 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.338 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 15.836 ms/op
                 listUser·p1.00:   15.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257058
  mean =      3.731 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 251004 
    [ 5.000,  7.500) = 4698 
    [ 7.500, 10.000) = 734 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 334 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.159 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.137 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      6.554 ms/op
     p(99.9000) =     13.648 ms/op
     p(99.9900) =     17.897 ms/op
     p(99.9990) =     19.099 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.871 ± 7.605  ops/ms
ClientPb.existUser                       thrpt       3  10.397 ± 0.726  ops/ms
ClientPb.getUser                         thrpt       3  10.048 ± 2.589  ops/ms
ClientPb.listUser                        thrpt       3   8.518 ± 3.701  ops/ms
ClientPb.createUser                       avgt       3   3.124 ± 1.135   ms/op
ClientPb.existUser                        avgt       3   3.069 ± 1.498   ms/op
ClientPb.getUser                          avgt       3   3.215 ± 0.272   ms/op
ClientPb.listUser                         avgt       3   3.712 ± 1.102   ms/op
ClientPb.createUser                     sample  303088   3.165 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.446           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.514           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.448           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.090           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.839           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.133           ms/op
ClientPb.existUser                      sample  317421   3.023 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.976           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.019           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.079           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.234           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.872           ms/op
ClientPb.getUser                        sample  305924   3.136 ± 0.004   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.141           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.011           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.441           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.707           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.718           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.831           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.805           ms/op
ClientPb.listUser                       sample  257058   3.731 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.159           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.137           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.554           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.648           ms/op
ClientPb.listUser:listUser·p0.9999      sample          17.897           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.724           ms/op
