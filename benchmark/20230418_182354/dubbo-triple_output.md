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
# Warmup Iteration   1: 2.315 ops/ms
# Warmup Iteration   2: 5.767 ops/ms
# Warmup Iteration   3: 8.815 ops/ms
Iteration   1: 9.269 ops/ms
Iteration   2: 9.897 ops/ms
Iteration   3: 9.877 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.681 ±(99.9%) 6.510 ops/ms [Average]
  (min, avg, max) = (9.269, 9.681, 9.897), stdev = 0.357
  CI (99.9%): [3.171, 16.191] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 8.880 ops/ms
# Warmup Iteration   3: 10.196 ops/ms
Iteration   1: 10.096 ops/ms
Iteration   2: 10.333 ops/ms
Iteration   3: 10.065 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.165 ±(99.9%) 2.681 ops/ms [Average]
  (min, avg, max) = (10.065, 10.165, 10.333), stdev = 0.147
  CI (99.9%): [7.484, 12.845] (assumes normal distribution)


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
# Warmup Iteration   1: 3.538 ops/ms
# Warmup Iteration   2: 8.851 ops/ms
# Warmup Iteration   3: 9.334 ops/ms
Iteration   1: 9.956 ops/ms
Iteration   2: 10.058 ops/ms
Iteration   3: 9.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.984 ±(99.9%) 1.185 ops/ms [Average]
  (min, avg, max) = (9.938, 9.984, 10.058), stdev = 0.065
  CI (99.9%): [8.799, 11.169] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.039 ops/ms
# Warmup Iteration   2: 7.346 ops/ms
# Warmup Iteration   3: 8.353 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 8.126 ops/ms
Iteration   3: 8.570 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.227 ±(99.9%) 5.556 ops/ms [Average]
  (min, avg, max) = (7.987, 8.227, 8.570), stdev = 0.305
  CI (99.9%): [2.672, 13.783] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.799 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.007 ms/op
Iteration   1: 3.198 ±(99.9%) 0.006 ms/op
Iteration   2: 3.197 ±(99.9%) 0.004 ms/op
Iteration   3: 3.225 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.207 ±(99.9%) 0.289 ms/op [Average]
  (min, avg, max) = (3.197, 3.207, 3.225), stdev = 0.016
  CI (99.9%): [2.918, 3.496] (assumes normal distribution)


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
# Warmup Iteration   1: 7.775 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.419 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.004 ms/op
Iteration   1: 3.271 ±(99.9%) 0.006 ms/op
Iteration   2: 3.224 ±(99.9%) 0.003 ms/op
Iteration   3: 3.100 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.198 ±(99.9%) 1.615 ms/op [Average]
  (min, avg, max) = (3.100, 3.198, 3.271), stdev = 0.089
  CI (99.9%): [1.583, 4.813] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.833 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.606 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.277 ±(99.9%) 0.004 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
Iteration   3: 3.197 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.216 ±(99.9%) 0.489 ms/op [Average]
  (min, avg, max) = (3.197, 3.216, 3.247), stdev = 0.027
  CI (99.9%): [2.727, 3.705] (assumes normal distribution)


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
# Warmup Iteration   1: 9.206 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.006 ms/op
Iteration   1: 3.732 ±(99.9%) 0.010 ms/op
Iteration   2: 3.898 ±(99.9%) 0.004 ms/op
Iteration   3: 3.752 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.794 ±(99.9%) 1.661 ms/op [Average]
  (min, avg, max) = (3.732, 3.794, 3.898), stdev = 0.091
  CI (99.9%): [2.133, 5.455] (assumes normal distribution)


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
# Warmup Iteration   1: 8.833 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.761 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.203 ±(99.9%) 0.008 ms/op
Iteration   1: 3.243 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.264 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.650 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.694 ms/op
                 createUser·p0.9999: 25.977 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   2: 3.250 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.358 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  10.562 ms/op
                 createUser·p0.9999: 22.315 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.251 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  14.005 ms/op
                 createUser·p0.9999: 23.134 ms/op
                 createUser·p1.00:   24.773 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 295320
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18108 
    [ 2.500,  5.000) = 271421 
    [ 5.000,  7.500) = 4888 
    [ 7.500, 10.000) = 492 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 117 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.264 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.957 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     17.215 ms/op
     p(99.9900) =     24.705 ms/op
     p(99.9990) =     26.484 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.545 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.473 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.191 ±(99.9%) 0.007 ms/op
Iteration   1: 3.265 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.266 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  10.716 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   21.561 ms/op

Iteration   2: 3.183 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.524 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.506 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  12.762 ms/op
                 existUser·p0.9999: 22.853 ms/op
                 existUser·p1.00:   24.117 ms/op

Iteration   3: 3.156 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.642 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.637 ms/op
                 existUser·p0.99:   5.333 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 22.348 ms/op
                 existUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299785
  mean =      3.201 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17982 
    [ 2.500,  5.000) = 276653 
    [ 5.000,  7.500) = 4357 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.266 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.415 ms/op
     p(99.9000) =     12.521 ms/op
     p(99.9900) =     22.282 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


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
# Warmup Iteration   1: 7.979 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.011 ms/op
Iteration   1: 3.345 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.087 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.750 ms/op
                 getUser·p0.999:  19.310 ms/op
                 getUser·p0.9999: 22.362 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   2: 3.411 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.965 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  20.227 ms/op
                 getUser·p0.9999: 22.868 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   3: 3.249 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.600 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 22.386 ms/op
                 getUser·p1.00:   22.970 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287894
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15930 
    [ 2.500,  5.000) = 261701 
    [ 5.000,  7.500) = 9052 
    [ 7.500, 10.000) = 785 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 190 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.087 ms/op
     p(50.0000) =      3.207 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     14.356 ms/op
     p(99.9900) =     22.551 ms/op
     p(99.9990) =     23.273 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


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
# Warmup Iteration   1: 11.219 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.011 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.939 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.125 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  15.499 ms/op
                 listUser·p0.9999: 22.999 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 3.923 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.847 ms/op
                 listUser·p0.99:   8.102 ms/op
                 listUser·p0.999:  14.889 ms/op
                 listUser·p0.9999: 20.737 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   3: 3.813 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.585 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.325 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  13.622 ms/op
                 listUser·p0.9999: 15.041 ms/op
                 listUser·p1.00:   15.237 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249118
  mean =      3.850 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58 
    [ 2.500,  5.000) = 240569 
    [ 5.000,  7.500) = 5754 
    [ 7.500, 10.000) = 1913 
    [10.000, 12.500) = 345 
    [12.500, 15.000) = 274 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     14.269 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     23.842 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.681 ± 6.510  ops/ms
ClientPb.existUser                       thrpt       3  10.165 ± 2.681  ops/ms
ClientPb.getUser                         thrpt       3   9.984 ± 1.185  ops/ms
ClientPb.listUser                        thrpt       3   8.227 ± 5.556  ops/ms
ClientPb.createUser                       avgt       3   3.207 ± 0.289   ms/op
ClientPb.existUser                        avgt       3   3.198 ± 1.615   ms/op
ClientPb.getUser                          avgt       3   3.216 ± 0.489   ms/op
ClientPb.listUser                         avgt       3   3.794 ± 1.661   ms/op
ClientPb.createUser                     sample  295320   3.248 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.174           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.617           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.669           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.215           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.705           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.706           ms/op
ClientPb.existUser                      sample  299785   3.201 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.266           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.535           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.415           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.521           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.282           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.117           ms/op
ClientPb.getUser                        sample  287894   3.333 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.207           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.317           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.373           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.356           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.551           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.495           ms/op
ClientPb.listUser                       sample  249118   3.850 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.585           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.347           ms/op
