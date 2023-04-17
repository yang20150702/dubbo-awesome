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
# Warmup Iteration   1: 2.170 ops/ms
# Warmup Iteration   2: 4.637 ops/ms
# Warmup Iteration   3: 8.831 ops/ms
Iteration   1: 9.260 ops/ms
Iteration   2: 9.439 ops/ms
Iteration   3: 9.586 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.428 ±(99.9%) 2.974 ops/ms [Average]
  (min, avg, max) = (9.260, 9.428, 9.586), stdev = 0.163
  CI (99.9%): [6.454, 12.402] (assumes normal distribution)


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
# Warmup Iteration   1: 2.965 ops/ms
# Warmup Iteration   2: 8.488 ops/ms
# Warmup Iteration   3: 9.461 ops/ms
Iteration   1: 9.678 ops/ms
Iteration   2: 9.452 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.590 ±(99.9%) 2.200 ops/ms [Average]
  (min, avg, max) = (9.452, 9.590, 9.678), stdev = 0.121
  CI (99.9%): [7.390, 11.789] (assumes normal distribution)


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
# Warmup Iteration   1: 2.987 ops/ms
# Warmup Iteration   2: 8.302 ops/ms
# Warmup Iteration   3: 9.059 ops/ms
Iteration   1: 9.107 ops/ms
Iteration   2: 9.220 ops/ms
Iteration   3: 9.543 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.290 ±(99.9%) 4.132 ops/ms [Average]
  (min, avg, max) = (9.107, 9.290, 9.543), stdev = 0.226
  CI (99.9%): [5.158, 13.421] (assumes normal distribution)


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
# Warmup Iteration   1: 2.803 ops/ms
# Warmup Iteration   2: 7.373 ops/ms
# Warmup Iteration   3: 7.849 ops/ms
Iteration   1: 7.931 ops/ms
Iteration   2: 7.953 ops/ms
Iteration   3: 8.164 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.016 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (7.931, 8.016, 8.164), stdev = 0.129
  CI (99.9%): [5.669, 10.362] (assumes normal distribution)


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
# Warmup Iteration   1: 9.457 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.605 ±(99.9%) 0.005 ms/op
Iteration   1: 3.484 ±(99.9%) 0.006 ms/op
Iteration   2: 3.470 ±(99.9%) 0.006 ms/op
Iteration   3: 3.423 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.459 ±(99.9%) 0.581 ms/op [Average]
  (min, avg, max) = (3.423, 3.459, 3.484), stdev = 0.032
  CI (99.9%): [2.878, 4.040] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.163 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.346 ±(99.9%) 0.003 ms/op
Iteration   1: 3.310 ±(99.9%) 0.007 ms/op
Iteration   2: 3.383 ±(99.9%) 0.009 ms/op
Iteration   3: 3.327 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.340 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (3.310, 3.340, 3.383), stdev = 0.038
  CI (99.9%): [2.640, 4.040] (assumes normal distribution)


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
# Warmup Iteration   1: 10.455 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.007 ms/op
Iteration   1: 3.533 ±(99.9%) 0.006 ms/op
Iteration   2: 3.293 ±(99.9%) 0.011 ms/op
Iteration   3: 3.518 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.448 ±(99.9%) 2.446 ms/op [Average]
  (min, avg, max) = (3.293, 3.448, 3.533), stdev = 0.134
  CI (99.9%): [1.002, 5.893] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.685 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.777 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.134 ±(99.9%) 0.010 ms/op
Iteration   1: 4.105 ±(99.9%) 0.007 ms/op
Iteration   2: 3.959 ±(99.9%) 0.011 ms/op
Iteration   3: 4.024 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.029 ±(99.9%) 1.340 ms/op [Average]
  (min, avg, max) = (3.959, 4.029, 4.105), stdev = 0.073
  CI (99.9%): [2.690, 5.369] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.081 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.941 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.011 ms/op
Iteration   1: 3.469 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.561 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   4.125 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  21.365 ms/op
                 createUser·p0.9999: 23.415 ms/op
                 createUser·p1.00:   24.445 ms/op

Iteration   2: 3.358 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.669 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.928 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  22.807 ms/op
                 createUser·p0.9999: 27.279 ms/op
                 createUser·p1.00:   30.278 ms/op

Iteration   3: 3.552 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.437 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   6.488 ms/op
                 createUser·p0.999:  20.049 ms/op
                 createUser·p0.9999: 25.821 ms/op
                 createUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277314
  mean =      3.458 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10351 
    [ 2.500,  5.000) = 259660 
    [ 5.000,  7.500) = 6195 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 129 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.561 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     20.142 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     28.046 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.137 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.476 ±(99.9%) 0.009 ms/op
Iteration   1: 3.261 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   5.738 ms/op
                 existUser·p0.999:  11.403 ms/op
                 existUser·p0.9999: 21.889 ms/op
                 existUser·p1.00:   22.217 ms/op

Iteration   2: 3.413 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.278 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   4.035 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.006 ms/op
                 existUser·p0.999:  11.408 ms/op
                 existUser·p0.9999: 24.040 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   3: 3.437 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.293 ms/op
                 existUser·p0.90:   3.924 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   6.676 ms/op
                 existUser·p0.999:  23.003 ms/op
                 existUser·p0.9999: 26.981 ms/op
                 existUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284834
  mean =      3.368 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11265 
    [ 2.500,  5.000) = 266186 
    [ 5.000,  7.500) = 6052 
    [ 7.500, 10.000) = 906 
    [10.000, 12.500) = 154 
    [12.500, 15.000) = 15 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.278 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     11.865 ms/op
     p(99.9900) =     25.379 ms/op
     p(99.9990) =     27.185 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 8.871 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.011 ms/op
Iteration   1: 3.392 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.581 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  20.818 ms/op
                 getUser·p0.9999: 23.771 ms/op
                 getUser·p1.00:   24.740 ms/op

Iteration   2: 3.444 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.966 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.947 ms/op
                 getUser·p0.999:  23.069 ms/op
                 getUser·p0.9999: 33.545 ms/op
                 getUser·p1.00:   34.079 ms/op

Iteration   3: 3.523 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   7.135 ms/op
                 getUser·p0.999:  19.291 ms/op
                 getUser·p0.9999: 28.077 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277948
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1905 
    [ 2.500,  5.000) = 266551 
    [ 5.000,  7.500) = 8182 
    [ 7.500, 10.000) = 789 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.781 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.898 ms/op
     p(99.9000) =     19.600 ms/op
     p(99.9900) =     31.831 ms/op
     p(99.9990) =     33.962 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 9.882 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.415 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.013 ms/op
Iteration   1: 3.910 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.367 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.084 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 24.668 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 4.033 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.458 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  16.599 ms/op
                 listUser·p0.9999: 26.706 ms/op
                 listUser·p1.00:   34.275 ms/op

Iteration   3: 3.968 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  15.548 ms/op
                 listUser·p0.9999: 23.198 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241802
  mean =      3.970 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 232927 
    [ 5.000,  7.500) = 7382 
    [ 7.500, 10.000) = 822 
    [10.000, 12.500) = 192 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.930 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     24.969 ms/op
     p(99.9990) =     33.669 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.428 ± 2.974  ops/ms
ClientPb.existUser                       thrpt       3   9.590 ± 2.200  ops/ms
ClientPb.getUser                         thrpt       3   9.290 ± 4.132  ops/ms
ClientPb.listUser                        thrpt       3   8.016 ± 2.346  ops/ms
ClientPb.createUser                       avgt       3   3.459 ± 0.581   ms/op
ClientPb.existUser                        avgt       3   3.340 ± 0.700   ms/op
ClientPb.getUser                          avgt       3   3.448 ± 2.446   ms/op
ClientPb.listUser                         avgt       3   4.029 ± 1.340   ms/op
ClientPb.createUser                     sample  277314   3.458 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.561           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.351           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.957           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.142           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.116           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.278           ms/op
ClientPb.existUser                      sample  284834   3.368 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.278           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.366           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.865           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.379           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.508           ms/op
ClientPb.getUser                        sample  277948   3.452 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.966           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.281           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.600           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.831           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.079           ms/op
ClientPb.listUser                       sample  241802   3.970 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.367           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.710           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.930           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.367           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.969           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.275           ms/op
