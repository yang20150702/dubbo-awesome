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
# Warmup Iteration   1: 2.368 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 8.477 ops/ms
Iteration   1: 9.146 ops/ms
Iteration   2: 9.203 ops/ms
Iteration   3: 9.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.260 ±(99.9%) 2.752 ops/ms [Average]
  (min, avg, max) = (9.146, 9.260, 9.431), stdev = 0.151
  CI (99.9%): [6.508, 12.013] (assumes normal distribution)


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
# Warmup Iteration   1: 2.870 ops/ms
# Warmup Iteration   2: 8.506 ops/ms
# Warmup Iteration   3: 9.399 ops/ms
Iteration   1: 9.744 ops/ms
Iteration   2: 9.747 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.678 ±(99.9%) 2.135 ops/ms [Average]
  (min, avg, max) = (9.543, 9.678, 9.747), stdev = 0.117
  CI (99.9%): [7.543, 11.813] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.973 ops/ms
# Warmup Iteration   2: 8.962 ops/ms
# Warmup Iteration   3: 9.382 ops/ms
Iteration   1: 9.618 ops/ms
Iteration   2: 9.602 ops/ms
Iteration   3: 9.590 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.603 ±(99.9%) 0.255 ops/ms [Average]
  (min, avg, max) = (9.590, 9.603, 9.618), stdev = 0.014
  CI (99.9%): [9.349, 9.858] (assumes normal distribution)


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
# Warmup Iteration   1: 3.033 ops/ms
# Warmup Iteration   2: 7.606 ops/ms
# Warmup Iteration   3: 8.022 ops/ms
Iteration   1: 7.847 ops/ms
Iteration   2: 7.998 ops/ms
Iteration   3: 8.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.052 ±(99.9%) 4.298 ops/ms [Average]
  (min, avg, max) = (7.847, 8.052, 8.309), stdev = 0.236
  CI (99.9%): [3.754, 12.349] (assumes normal distribution)


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
# Warmup Iteration   1: 9.740 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.833 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.004 ms/op
Iteration   1: 3.406 ±(99.9%) 0.011 ms/op
Iteration   2: 3.415 ±(99.9%) 0.009 ms/op
Iteration   3: 3.450 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.423 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (3.406, 3.423, 3.450), stdev = 0.023
  CI (99.9%): [3.003, 3.844] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 9.119 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.563 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.288 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.010 ms/op
Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
Iteration   3: 3.182 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.200 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.182, 3.200, 3.231), stdev = 0.027
  CI (99.9%): [2.713, 3.687] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.470 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.564 ±(99.9%) 0.006 ms/op
Iteration   1: 3.354 ±(99.9%) 0.006 ms/op
Iteration   2: 3.386 ±(99.9%) 0.005 ms/op
Iteration   3: 3.496 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.412 ±(99.9%) 1.354 ms/op [Average]
  (min, avg, max) = (3.354, 3.412, 3.496), stdev = 0.074
  CI (99.9%): [2.058, 4.766] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.400 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.493 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.011 ms/op
Iteration   1: 3.944 ±(99.9%) 0.012 ms/op
Iteration   2: 4.001 ±(99.9%) 0.014 ms/op
Iteration   3: 3.906 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.950 ±(99.9%) 0.865 ms/op [Average]
  (min, avg, max) = (3.906, 3.950, 4.001), stdev = 0.047
  CI (99.9%): [3.085, 4.815] (assumes normal distribution)


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
# Warmup Iteration   1: 8.619 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 3.854 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
Iteration   1: 3.438 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.248 ms/op
                 createUser·p0.90:   4.399 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  21.612 ms/op
                 createUser·p0.9999: 26.532 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   2: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.987 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   6.383 ms/op
                 createUser·p0.999:  21.801 ms/op
                 createUser·p0.9999: 24.469 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.341 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  17.826 ms/op
                 createUser·p0.9999: 23.360 ms/op
                 createUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279712
  mean =      3.430 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11210 
    [ 2.500,  5.000) = 261854 
    [ 5.000,  7.500) = 5725 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 135 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.341 ms/op
     p(50.0000) =      3.334 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.563 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     25.922 ms/op
     p(99.9990) =     26.877 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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
# Warmup Iteration   1: 8.193 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.008 ms/op
Iteration   1: 3.364 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  10.027 ms/op
                 existUser·p0.9999: 24.920 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   5.324 ms/op
                 existUser·p0.999:  19.195 ms/op
                 existUser·p0.9999: 23.828 ms/op
                 existUser·p1.00:   24.183 ms/op

Iteration   3: 3.299 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  18.844 ms/op
                 existUser·p0.9999: 25.368 ms/op
                 existUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291028
  mean =      3.295 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11046 
    [ 2.500,  5.000) = 274148 
    [ 5.000,  7.500) = 4752 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 125 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     16.760 ms/op
     p(99.9900) =     24.838 ms/op
     p(99.9990) =     26.485 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 8.035 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
Iteration   1: 3.356 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   4.002 ms/op
                 getUser·p0.99:   6.283 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 21.362 ms/op
                 getUser·p1.00:   22.774 ms/op

Iteration   2: 3.305 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  17.654 ms/op
                 getUser·p0.9999: 34.800 ms/op
                 getUser·p1.00:   36.307 ms/op

Iteration   3: 3.521 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.241 ms/op
                 getUser·p0.50:   3.285 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   5.120 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  23.101 ms/op
                 getUser·p0.9999: 55.575 ms/op
                 getUser·p1.00:   55.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282928
  mean =      3.391 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 273837 
    [ 5.000, 10.000) = 8590 
    [10.000, 15.000) = 162 
    [15.000, 20.000) = 73 
    [20.000, 25.000) = 166 
    [25.000, 30.000) = 38 
    [30.000, 35.000) = 24 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.202 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     19.471 ms/op
     p(99.9900) =     54.723 ms/op
     p(99.9990) =     55.640 ms/op
     p(99.9999) =     55.706 ms/op
    p(100.0000) =     55.706 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.534 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.021 ±(99.9%) 0.012 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.550 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   7.841 ms/op
                 listUser·p0.999:  20.967 ms/op
                 listUser·p0.9999: 25.157 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 3.984 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.523 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 16.268 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.912 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  15.215 ms/op
                 listUser·p0.9999: 16.253 ms/op
                 listUser·p1.00:   16.286 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240250
  mean =      3.993 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 42 
    [ 2.500,  5.000) = 231968 
    [ 5.000,  7.500) = 5837 
    [ 7.500, 10.000) = 1543 
    [10.000, 12.500) = 326 
    [12.500, 15.000) = 198 
    [15.000, 17.500) = 189 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.698 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     23.363 ms/op
     p(99.9990) =     25.316 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.260 ± 2.752  ops/ms
ClientPb.existUser                       thrpt       3   9.678 ± 2.135  ops/ms
ClientPb.getUser                         thrpt       3   9.603 ± 0.255  ops/ms
ClientPb.listUser                        thrpt       3   8.052 ± 4.298  ops/ms
ClientPb.createUser                       avgt       3   3.423 ± 0.421   ms/op
ClientPb.existUser                        avgt       3   3.200 ± 0.487   ms/op
ClientPb.getUser                          avgt       3   3.412 ± 1.354   ms/op
ClientPb.listUser                         avgt       3   3.950 ± 0.865   ms/op
ClientPb.createUser                     sample  279712   3.430 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.341           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.334           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.563           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.922           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.034           ms/op
ClientPb.existUser                      sample  291028   3.295 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.195           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.693           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.760           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.838           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.804           ms/op
ClientPb.getUser                        sample  282928   3.391 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.202           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.242           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.471           ms/op
ClientPb.getUser:getUser·p0.9999        sample          54.723           ms/op
ClientPb.getUser:getUser·p1.00          sample          55.706           ms/op
ClientPb.listUser                       sample  240250   3.993 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.550           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.858           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.698           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.363           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.411           ms/op
