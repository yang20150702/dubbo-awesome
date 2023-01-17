# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.592 ops/ms
# Warmup Iteration   2: 6.550 ops/ms
# Warmup Iteration   3: 9.077 ops/ms
Iteration   1: 9.980 ops/ms
Iteration   2: 9.757 ops/ms
Iteration   3: 9.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.896 ±(99.9%) 2.209 ops/ms [Average]
  (min, avg, max) = (9.757, 9.896, 9.980), stdev = 0.121
  CI (99.9%): [7.687, 12.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.390 ops/ms
# Warmup Iteration   2: 9.029 ops/ms
# Warmup Iteration   3: 10.155 ops/ms
Iteration   1: 10.261 ops/ms
Iteration   2: 10.586 ops/ms
Iteration   3: 10.159 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.335 ±(99.9%) 4.072 ops/ms [Average]
  (min, avg, max) = (10.159, 10.335, 10.586), stdev = 0.223
  CI (99.9%): [6.263, 14.408] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 3.852 ops/ms
# Warmup Iteration   2: 9.244 ops/ms
# Warmup Iteration   3: 9.708 ops/ms
Iteration   1: 10.009 ops/ms
Iteration   2: 9.418 ops/ms
Iteration   3: 9.683 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.704 ±(99.9%) 5.400 ops/ms [Average]
  (min, avg, max) = (9.418, 9.704, 10.009), stdev = 0.296
  CI (99.9%): [4.304, 15.103] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 3.258 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.548 ops/ms
Iteration   1: 8.717 ops/ms
Iteration   2: 8.487 ops/ms
Iteration   3: 8.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.533 ±(99.9%) 3.023 ops/ms [Average]
  (min, avg, max) = (8.395, 8.533, 8.717), stdev = 0.166
  CI (99.9%): [5.510, 11.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.195 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.571 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.008 ms/op
Iteration   2: 3.234 ±(99.9%) 0.004 ms/op
Iteration   3: 3.114 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.172 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (3.114, 3.172, 3.234), stdev = 0.060
  CI (99.9%): [2.074, 4.270] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.550 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.412 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.236 ±(99.9%) 0.005 ms/op
Iteration   2: 3.189 ±(99.9%) 0.004 ms/op
Iteration   3: 3.104 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.177 ±(99.9%) 1.224 ms/op [Average]
  (min, avg, max) = (3.104, 3.177, 3.236), stdev = 0.067
  CI (99.9%): [1.952, 4.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.085 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.453 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.261 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.004 ms/op
Iteration   2: 3.238 ±(99.9%) 0.005 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.200 ±(99.9%) 0.654 ms/op [Average]
  (min, avg, max) = (3.167, 3.200, 3.238), stdev = 0.036
  CI (99.9%): [2.546, 3.854] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.026 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.015 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.815 ±(99.9%) 0.008 ms/op
Iteration   1: 3.761 ±(99.9%) 0.007 ms/op
Iteration   2: 3.774 ±(99.9%) 0.006 ms/op
Iteration   3: 3.766 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.767 ±(99.9%) 0.118 ms/op [Average]
  (min, avg, max) = (3.761, 3.767, 3.774), stdev = 0.006
  CI (99.9%): [3.649, 3.885] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ±(99.9%) 0.099 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
Iteration   1: 3.141 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.530 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  18.094 ms/op
                 createUser·p0.9999: 19.530 ms/op
                 createUser·p1.00:   20.120 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   5.169 ms/op
                 createUser·p0.999:  9.271 ms/op
                 createUser·p0.9999: 22.231 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.096 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.248 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.713 ms/op
                 createUser·p0.9999: 18.765 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307904
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24715 
    [ 2.500,  5.000) = 279531 
    [ 5.000,  7.500) = 2989 
    [ 7.500, 10.000) = 333 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 218 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.289 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     21.170 ms/op
     p(99.9990) =     22.900 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.268 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.008 ms/op
Iteration   1: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  15.542 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.135 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   4.043 ms/op
                 existUser·p0.99:   5.439 ms/op
                 existUser·p0.999:  10.024 ms/op
                 existUser·p0.9999: 26.207 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.133 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   5.341 ms/op
                 existUser·p0.999:  11.178 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.675 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300478
  mean =      3.195 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18877 
    [ 2.500,  5.000) = 275242 
    [ 5.000,  7.500) = 5634 
    [ 7.500, 10.000) = 391 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.685 ms/op
     p(99.9000) =     11.420 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     26.476 ms/op
     p(99.9999) =     26.542 ms/op
    p(100.0000) =     26.542 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.563 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.526 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.009 ms/op
Iteration   1: 3.225 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.167 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  16.692 ms/op
                 getUser·p0.9999: 19.530 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.396 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.592 ms/op
                 getUser·p0.99:   5.308 ms/op
                 getUser·p0.999:  19.096 ms/op
                 getUser·p0.9999: 22.405 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.286 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.011 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  9.371 ms/op
                 getUser·p0.9999: 25.731 ms/op
                 getUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299264
  mean =      3.209 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7801 
    [ 2.500,  5.000) = 284289 
    [ 5.000,  7.500) = 6375 
    [ 7.500, 10.000) = 388 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 172 
    [20.000, 22.500) = 66 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.396 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     16.368 ms/op
     p(99.9900) =     24.936 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.214 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.011 ms/op
Iteration   1: 3.783 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.593 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  15.854 ms/op
                 listUser·p0.9999: 22.317 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   2: 3.658 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.785 ms/op
                 listUser·p0.95:   3.846 ms/op
                 listUser·p0.99:   6.111 ms/op
                 listUser·p0.999:  14.476 ms/op
                 listUser·p0.9999: 18.416 ms/op
                 listUser·p1.00:   18.448 ms/op

Iteration   3: 3.767 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.204 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.166 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  12.422 ms/op
                 listUser·p0.9999: 15.606 ms/op
                 listUser·p1.00:   15.679 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256967
  mean =      3.735 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 250322 
    [ 5.000,  7.500) = 5101 
    [ 7.500, 10.000) = 861 
    [10.000, 12.500) = 233 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.593 ms/op
     p(50.0000) =      3.666 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      6.562 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     20.261 ms/op
     p(99.9990) =     23.064 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.896 ± 2.209  ops/ms
ClientPb.existUser                       thrpt       3  10.335 ± 4.072  ops/ms
ClientPb.getUser                         thrpt       3   9.704 ± 5.400  ops/ms
ClientPb.listUser                        thrpt       3   8.533 ± 3.023  ops/ms
ClientPb.createUser                       avgt       3   3.172 ± 1.098   ms/op
ClientPb.existUser                        avgt       3   3.177 ± 1.224   ms/op
ClientPb.getUser                          avgt       3   3.200 ± 0.654   ms/op
ClientPb.listUser                         avgt       3   3.767 ± 0.118   ms/op
ClientPb.createUser                     sample  307904   3.115 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.808           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.289           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.592           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.317           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.451           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.170           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.626           ms/op
ClientPb.existUser                      sample  300478   3.195 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.660           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.129           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.071           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.685           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.420           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.231           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.542           ms/op
ClientPb.getUser                        sample  299264   3.209 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.396           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.523           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.871           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.368           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.936           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.116           ms/op
ClientPb.listUser                       sample  256967   3.735 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.593           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.666           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.562           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.516           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.261           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.331           ms/op
