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
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 6.733 ops/ms
# Warmup Iteration   3: 9.446 ops/ms
Iteration   1: 9.667 ops/ms
Iteration   2: 10.123 ops/ms
Iteration   3: 10.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.027 ±(99.9%) 5.905 ops/ms [Average]
  (min, avg, max) = (9.667, 10.027, 10.293), stdev = 0.324
  CI (99.9%): [4.122, 15.933] (assumes normal distribution)


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
# Warmup Iteration   1: 3.371 ops/ms
# Warmup Iteration   2: 9.607 ops/ms
# Warmup Iteration   3: 9.659 ops/ms
Iteration   1: 9.511 ops/ms
Iteration   2: 10.131 ops/ms
Iteration   3: 10.697 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.113 ±(99.9%) 10.825 ops/ms [Average]
  (min, avg, max) = (9.511, 10.113, 10.697), stdev = 0.593
  CI (99.9%): [≈ 0, 20.938] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ops/ms
# Warmup Iteration   2: 9.633 ops/ms
# Warmup Iteration   3: 9.554 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.344 ops/ms
Iteration   3: 10.235 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.178 ±(99.9%) 3.649 ops/ms [Average]
  (min, avg, max) = (9.956, 10.178, 10.344), stdev = 0.200
  CI (99.9%): [6.530, 13.827] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.539 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 8.390 ops/ms
Iteration   1: 8.723 ops/ms
Iteration   2: 8.638 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.663 ±(99.9%) 0.953 ops/ms [Average]
  (min, avg, max) = (8.628, 8.663, 8.723), stdev = 0.052
  CI (99.9%): [7.711, 9.616] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.113 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.614 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.244 ±(99.9%) 0.008 ms/op
Iteration   2: 3.149 ±(99.9%) 0.005 ms/op
Iteration   3: 3.202 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.198 ±(99.9%) 0.868 ms/op [Average]
  (min, avg, max) = (3.149, 3.198, 3.244), stdev = 0.048
  CI (99.9%): [2.330, 4.066] (assumes normal distribution)


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
# Warmup Iteration   1: 7.406 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.237 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.006 ms/op
Iteration   2: 3.040 ±(99.9%) 0.003 ms/op
Iteration   3: 3.049 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.039 ±(99.9%) 0.196 ms/op [Average]
  (min, avg, max) = (3.028, 3.039, 3.049), stdev = 0.011
  CI (99.9%): [2.843, 3.235] (assumes normal distribution)


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
# Warmup Iteration   1: 7.349 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.566 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.304 ±(99.9%) 0.007 ms/op
Iteration   1: 3.214 ±(99.9%) 0.006 ms/op
Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
Iteration   3: 3.161 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.183 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.161, 3.183, 3.214), stdev = 0.027
  CI (99.9%): [2.683, 3.683] (assumes normal distribution)


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
# Warmup Iteration   1: 8.433 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.962 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.006 ms/op
Iteration   1: 3.718 ±(99.9%) 0.006 ms/op
Iteration   2: 3.661 ±(99.9%) 0.010 ms/op
Iteration   3: 3.857 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.745 ±(99.9%) 1.841 ms/op [Average]
  (min, avg, max) = (3.661, 3.745, 3.857), stdev = 0.101
  CI (99.9%): [1.904, 5.587] (assumes normal distribution)


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
# Warmup Iteration   1: 7.678 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.708 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.275 ±(99.9%) 0.010 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  18.408 ms/op
                 createUser·p0.9999: 22.245 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.257 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.577 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.506 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.538 ms/op
                 createUser·p0.999:  17.564 ms/op
                 createUser·p0.9999: 25.068 ms/op
                 createUser·p1.00:   25.690 ms/op

Iteration   3: 3.297 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.317 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  13.631 ms/op
                 createUser·p0.9999: 18.950 ms/op
                 createUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296216
  mean =      3.236 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29283 
    [ 2.500,  5.000) = 260466 
    [ 5.000,  7.500) = 5564 
    [ 7.500, 10.000) = 456 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 74 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 51 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     14.758 ms/op
     p(99.9900) =     23.643 ms/op
     p(99.9990) =     25.469 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


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
# Warmup Iteration   1: 6.573 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 3.478 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.009 ms/op
Iteration   1: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.155 ms/op
                 existUser·p0.50:   3.101 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  12.108 ms/op
                 existUser·p0.9999: 19.780 ms/op
                 existUser·p1.00:   20.709 ms/op

Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.499 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   3.936 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  19.387 ms/op
                 existUser·p0.9999: 25.627 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.190 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.276 ms/op
                 existUser·p0.999:  11.154 ms/op
                 existUser·p0.9999: 21.297 ms/op
                 existUser·p1.00:   21.823 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 298248
  mean =      3.214 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19470 
    [ 2.500,  5.000) = 273936 
    [ 5.000,  7.500) = 4059 
    [ 7.500, 10.000) = 292 
    [10.000, 12.500) = 148 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     15.082 ms/op
     p(99.9900) =     24.751 ms/op
     p(99.9990) =     26.255 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 6.910 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.441 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.341 ±(99.9%) 0.010 ms/op
Iteration   1: 3.431 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   6.216 ms/op
                 getUser·p0.999:  18.696 ms/op
                 getUser·p0.9999: 20.568 ms/op
                 getUser·p1.00:   21.234 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 27.406 ms/op
                 getUser·p1.00:   28.213 ms/op

Iteration   3: 3.357 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.116 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.957 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  16.378 ms/op
                 getUser·p0.9999: 21.067 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 286648
  mean =      3.347 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17834 
    [ 2.500,  5.000) = 258491 
    [ 5.000,  7.500) = 9552 
    [ 7.500, 10.000) = 431 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     16.593 ms/op
     p(99.9900) =     25.516 ms/op
     p(99.9990) =     27.682 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


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
# Warmup Iteration   1: 10.628 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.872 ±(99.9%) 0.012 ms/op
Iteration   1: 3.817 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   3.621 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.692 ms/op
                 listUser·p0.999:  16.883 ms/op
                 listUser·p0.9999: 20.103 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 3.656 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.523 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.137 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 21.758 ms/op
                 listUser·p1.00:   21.791 ms/op

Iteration   3: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  13.773 ms/op
                 listUser·p0.9999: 18.336 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255610
  mean =      3.753 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 246965 
    [ 5.000,  7.500) = 6724 
    [ 7.500, 10.000) = 1093 
    [10.000, 12.500) = 199 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.448 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.980 ms/op
     p(99.9000) =     14.533 ms/op
     p(99.9900) =     19.835 ms/op
     p(99.9990) =     21.758 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score    Error   Units
ClientPb.createUser                      thrpt       3  10.027 ±  5.905  ops/ms
ClientPb.existUser                       thrpt       3  10.113 ± 10.825  ops/ms
ClientPb.getUser                         thrpt       3  10.178 ±  3.649  ops/ms
ClientPb.listUser                        thrpt       3   8.663 ±  0.953  ops/ms
ClientPb.createUser                       avgt       3   3.198 ±  0.868   ms/op
ClientPb.existUser                        avgt       3   3.039 ±  0.196   ms/op
ClientPb.getUser                          avgt       3   3.183 ±  0.500   ms/op
ClientPb.listUser                         avgt       3   3.745 ±  1.841   ms/op
ClientPb.createUser                     sample  296216   3.236 ±  0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.237            ms/op
ClientPb.createUser:createUser·p0.50    sample           3.199            ms/op
ClientPb.createUser:createUser·p0.90    sample           3.531            ms/op
ClientPb.createUser:createUser·p0.95    sample           3.990            ms/op
ClientPb.createUser:createUser·p0.99    sample           5.480            ms/op
ClientPb.createUser:createUser·p0.999   sample          14.758            ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.643            ms/op
ClientPb.createUser:createUser·p1.00    sample          28.672            ms/op
ClientPb.existUser                      sample  298248   3.214 ±  0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.155            ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138            ms/op
ClientPb.existUser:existUser·p0.90      sample           3.690            ms/op
ClientPb.existUser:existUser·p0.95      sample           4.092            ms/op
ClientPb.existUser:existUser·p0.99      sample           5.456            ms/op
ClientPb.existUser:existUser·p0.999     sample          15.082            ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.751            ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706            ms/op
ClientPb.getUser                        sample  286648   3.347 ±  0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.470            ms/op
ClientPb.getUser:getUser·p0.50          sample           3.248            ms/op
ClientPb.getUser:getUser·p0.90          sample           3.863            ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522            ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070            ms/op
ClientPb.getUser:getUser·p0.999         sample          16.593            ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.516            ms/op
ClientPb.getUser:getUser·p1.00          sample          28.213            ms/op
ClientPb.listUser                       sample  255610   3.753 ±  0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.448            ms/op
ClientPb.listUser:listUser·p0.50        sample           3.621            ms/op
ClientPb.listUser:listUser·p0.90        sample           4.116            ms/op
ClientPb.listUser:listUser·p0.95        sample           4.506            ms/op
ClientPb.listUser:listUser·p0.99        sample           6.980            ms/op
ClientPb.listUser:listUser·p0.999       sample          14.533            ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.835            ms/op
ClientPb.listUser:listUser·p1.00        sample          21.791            ms/op
