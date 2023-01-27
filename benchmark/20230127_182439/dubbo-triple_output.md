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
# Warmup Iteration   1: 2.595 ops/ms
# Warmup Iteration   2: 5.467 ops/ms
# Warmup Iteration   3: 9.222 ops/ms
Iteration   1: 9.618 ops/ms
Iteration   2: 9.643 ops/ms
Iteration   3: 9.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.700 ±(99.9%) 2.194 ops/ms [Average]
  (min, avg, max) = (9.618, 9.700, 9.838), stdev = 0.120
  CI (99.9%): [7.505, 11.894] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.307 ops/ms
# Warmup Iteration   2: 8.989 ops/ms
# Warmup Iteration   3: 10.366 ops/ms
Iteration   1: 10.746 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.609 ±(99.9%) 2.600 ops/ms [Average]
  (min, avg, max) = (10.461, 10.609, 10.746), stdev = 0.143
  CI (99.9%): [8.008, 13.209] (assumes normal distribution)


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
# Warmup Iteration   1: 3.359 ops/ms
# Warmup Iteration   2: 8.607 ops/ms
# Warmup Iteration   3: 9.925 ops/ms
Iteration   1: 10.018 ops/ms
Iteration   2: 10.264 ops/ms
Iteration   3: 9.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.078 ±(99.9%) 3.003 ops/ms [Average]
  (min, avg, max) = (9.952, 10.078, 10.264), stdev = 0.165
  CI (99.9%): [7.075, 13.081] (assumes normal distribution)


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
# Warmup Iteration   1: 3.583 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.422 ops/ms
Iteration   1: 8.611 ops/ms
Iteration   2: 8.413 ops/ms
Iteration   3: 8.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.452 ±(99.9%) 2.611 ops/ms [Average]
  (min, avg, max) = (8.333, 8.452, 8.611), stdev = 0.143
  CI (99.9%): [5.842, 11.063] (assumes normal distribution)


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
# Warmup Iteration   1: 8.356 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.442 ±(99.9%) 0.006 ms/op
Iteration   1: 3.227 ±(99.9%) 0.005 ms/op
Iteration   2: 3.339 ±(99.9%) 0.006 ms/op
Iteration   3: 3.170 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.245 ±(99.9%) 1.576 ms/op [Average]
  (min, avg, max) = (3.170, 3.245, 3.339), stdev = 0.086
  CI (99.9%): [1.670, 4.821] (assumes normal distribution)


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
# Warmup Iteration   1: 7.939 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.278 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.002 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
Iteration   3: 3.286 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.165 ±(99.9%) 2.184 ms/op [Average]
  (min, avg, max) = (3.047, 3.165, 3.286), stdev = 0.120
  CI (99.9%): [0.981, 5.349] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.346 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.003 ms/op
Iteration   1: 3.139 ±(99.9%) 0.004 ms/op
Iteration   2: 3.094 ±(99.9%) 0.004 ms/op
Iteration   3: 3.270 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (3.094, 3.168, 3.270), stdev = 0.091
  CI (99.9%): [1.503, 4.832] (assumes normal distribution)


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
# Warmup Iteration   1: 8.906 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.883 ±(99.9%) 0.004 ms/op
Iteration   1: 3.725 ±(99.9%) 0.008 ms/op
Iteration   2: 3.668 ±(99.9%) 0.008 ms/op
Iteration   3: 3.745 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.713 ±(99.9%) 0.725 ms/op [Average]
  (min, avg, max) = (3.668, 3.713, 3.745), stdev = 0.040
  CI (99.9%): [2.988, 4.437] (assumes normal distribution)


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
# Warmup Iteration   1: 8.359 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.254 ±(99.9%) 0.009 ms/op
Iteration   1: 3.190 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   4.293 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  11.449 ms/op
                 createUser·p0.9999: 21.495 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.348 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  16.391 ms/op
                 createUser·p0.9999: 21.137 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 3.183 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.761 ms/op
                 createUser·p0.9999: 19.462 ms/op
                 createUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300631
  mean =      3.191 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17937 
    [ 2.500,  5.000) = 276728 
    [ 5.000,  7.500) = 5126 
    [ 7.500, 10.000) = 406 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 167 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.021 ms/op
     p(99.9900) =     21.068 ms/op
     p(99.9990) =     22.085 ms/op
     p(99.9999) =     23.003 ms/op
    p(100.0000) =     23.003 ms/op


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
# Warmup Iteration   1: 7.018 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.247 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   5.210 ms/op
                 existUser·p0.999:  10.919 ms/op
                 existUser·p0.9999: 19.321 ms/op
                 existUser·p1.00:   20.382 ms/op

Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.075 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.719 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  13.560 ms/op
                 existUser·p0.9999: 34.732 ms/op
                 existUser·p1.00:   35.193 ms/op

Iteration   3: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.348 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  13.032 ms/op
                 existUser·p0.9999: 21.045 ms/op
                 existUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301367
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15843 
    [ 2.500,  5.000) = 278451 
    [ 5.000,  7.500) = 6356 
    [ 7.500, 10.000) = 362 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.000 ms/op
     p(99.0000) =      5.816 ms/op
     p(99.9000) =     13.138 ms/op
     p(99.9900) =     21.922 ms/op
     p(99.9990) =     34.995 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 7.687 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.220 ±(99.9%) 0.009 ms/op
Iteration   1: 3.244 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.003 ms/op
                 getUser·p0.999:  12.365 ms/op
                 getUser·p0.9999: 19.931 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   2: 3.230 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.245 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.100 ms/op
                 getUser·p0.99:   5.358 ms/op
                 getUser·p0.999:  9.451 ms/op
                 getUser·p0.9999: 22.315 ms/op
                 getUser·p1.00:   23.003 ms/op

Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   5.718 ms/op
                 getUser·p0.999:  9.362 ms/op
                 getUser·p0.9999: 22.896 ms/op
                 getUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299171
  mean =      3.208 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14897 
    [ 2.500,  5.000) = 277474 
    [ 5.000,  7.500) = 6019 
    [ 7.500, 10.000) = 478 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.991 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      4.125 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     12.024 ms/op
     p(99.9900) =     22.348 ms/op
     p(99.9990) =     23.134 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 8.653 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.080 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.754 ±(99.9%) 0.009 ms/op
Iteration   1: 3.686 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.064 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.694 ms/op
                 listUser·p0.999:  14.585 ms/op
                 listUser·p0.9999: 20.161 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   2: 3.687 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  12.260 ms/op
                 listUser·p0.9999: 17.345 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.731 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   3.854 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  13.582 ms/op
                 listUser·p0.9999: 20.822 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 259152
  mean =      3.701 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 253527 
    [ 5.000,  7.500) = 4097 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 282 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 101 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.384 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.243 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     19.664 ms/op
     p(99.9990) =     20.887 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.700 ± 2.194  ops/ms
ClientPb.existUser                       thrpt       3  10.609 ± 2.600  ops/ms
ClientPb.getUser                         thrpt       3  10.078 ± 3.003  ops/ms
ClientPb.listUser                        thrpt       3   8.452 ± 2.611  ops/ms
ClientPb.createUser                       avgt       3   3.245 ± 1.576   ms/op
ClientPb.existUser                        avgt       3   3.165 ± 2.184   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 1.665   ms/op
ClientPb.listUser                         avgt       3   3.713 ± 0.725   ms/op
ClientPb.createUser                     sample  300631   3.191 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.650           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.112           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.021           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.068           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.003           ms/op
ClientPb.existUser                      sample  301367   3.182 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.075           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.658           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.000           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.193           ms/op
ClientPb.getUser                        sample  299171   3.208 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.991           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.666           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.125           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.024           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.348           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.216           ms/op
ClientPb.listUser                       sample  259152   3.701 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.384           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.654           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.243           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.664           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.972           ms/op
