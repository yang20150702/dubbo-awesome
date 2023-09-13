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
# Warmup Iteration   1: 2.312 ops/ms
# Warmup Iteration   2: 5.502 ops/ms
# Warmup Iteration   3: 8.837 ops/ms
Iteration   1: 9.353 ops/ms
Iteration   2: 9.250 ops/ms
Iteration   3: 9.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.382 ±(99.9%) 2.700 ops/ms [Average]
  (min, avg, max) = (9.250, 9.382, 9.542), stdev = 0.148
  CI (99.9%): [6.682, 12.081] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 8.281 ops/ms
# Warmup Iteration   3: 9.331 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.764 ±(99.9%) 3.216 ops/ms [Average]
  (min, avg, max) = (9.621, 9.764, 9.961), stdev = 0.176
  CI (99.9%): [6.548, 12.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 8.542 ops/ms
# Warmup Iteration   3: 8.932 ops/ms
Iteration   1: 9.162 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.403 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.325 ±(99.9%) 2.573 ops/ms [Average]
  (min, avg, max) = (9.162, 9.325, 9.410), stdev = 0.141
  CI (99.9%): [6.752, 11.898] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.729 ops/ms
# Warmup Iteration   2: 7.217 ops/ms
# Warmup Iteration   3: 7.688 ops/ms
Iteration   1: 8.015 ops/ms
Iteration   2: 8.022 ops/ms
Iteration   3: 8.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.107 ±(99.9%) 2.783 ops/ms [Average]
  (min, avg, max) = (8.015, 8.107, 8.283), stdev = 0.153
  CI (99.9%): [5.323, 10.890] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 10.315 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.179 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.006 ms/op
Iteration   1: 3.605 ±(99.9%) 0.005 ms/op
Iteration   2: 3.489 ±(99.9%) 0.002 ms/op
Iteration   3: 3.504 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.533 ±(99.9%) 1.148 ms/op [Average]
  (min, avg, max) = (3.489, 3.533, 3.605), stdev = 0.063
  CI (99.9%): [2.385, 4.681] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 7.543 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.480 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
Iteration   1: 3.364 ±(99.9%) 0.008 ms/op
Iteration   2: 3.297 ±(99.9%) 0.004 ms/op
Iteration   3: 3.326 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 0.614 ms/op [Average]
  (min, avg, max) = (3.297, 3.329, 3.364), stdev = 0.034
  CI (99.9%): [2.715, 3.943] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 8.496 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.479 ±(99.9%) 0.009 ms/op
Iteration   1: 3.409 ±(99.9%) 0.005 ms/op
Iteration   2: 3.552 ±(99.9%) 0.003 ms/op
Iteration   3: 3.445 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.469 ±(99.9%) 1.363 ms/op [Average]
  (min, avg, max) = (3.409, 3.469, 3.552), stdev = 0.075
  CI (99.9%): [2.105, 4.832] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 10.085 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.475 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.118 ±(99.9%) 0.006 ms/op
Iteration   1: 4.041 ±(99.9%) 0.010 ms/op
Iteration   2: 4.093 ±(99.9%) 0.004 ms/op
Iteration   3: 3.923 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.019 ±(99.9%) 1.591 ms/op [Average]
  (min, avg, max) = (3.923, 4.019, 4.093), stdev = 0.087
  CI (99.9%): [2.427, 5.610] (assumes normal distribution)


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
# Warmup Iteration   1: 9.413 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.830 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.575 ±(99.9%) 0.010 ms/op
Iteration   1: 3.470 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.294 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   6.248 ms/op
                 createUser·p0.999:  19.653 ms/op
                 createUser·p0.9999: 23.079 ms/op
                 createUser·p1.00:   24.543 ms/op

Iteration   2: 3.555 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   3.408 ms/op
                 createUser·p0.90:   4.170 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  21.529 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   28.836 ms/op

Iteration   3: 3.477 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.522 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.250 ms/op
                 createUser·p0.999:  21.201 ms/op
                 createUser·p0.9999: 35.483 ms/op
                 createUser·p1.00:   36.504 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274319
  mean =      3.500 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7059 
    [ 2.500,  5.000) = 259697 
    [ 5.000,  7.500) = 6126 
    [ 7.500, 10.000) = 838 
    [10.000, 12.500) = 184 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 168 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.010 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     28.738 ms/op
     p(99.9990) =     36.389 ms/op
     p(99.9999) =     36.504 ms/op
    p(100.0000) =     36.504 ms/op


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
# Warmup Iteration   1: 8.490 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.568 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.387 ±(99.9%) 0.009 ms/op
Iteration   1: 3.400 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.895 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.726 ms/op
                 existUser·p0.999:  17.623 ms/op
                 existUser·p0.9999: 20.008 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.318 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   6.049 ms/op
                 existUser·p0.999:  17.475 ms/op
                 existUser·p0.9999: 22.941 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   3: 3.376 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.325 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  11.586 ms/op
                 existUser·p0.9999: 25.480 ms/op
                 existUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285115
  mean =      3.364 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7896 
    [ 2.500,  5.000) = 268476 
    [ 5.000,  7.500) = 7312 
    [ 7.500, 10.000) = 1014 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.300 ms/op
     p(99.9000) =     13.681 ms/op
     p(99.9900) =     24.019 ms/op
     p(99.9990) =     26.388 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


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
# Warmup Iteration   1: 9.063 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
Iteration   1: 3.423 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.310 ms/op
                 getUser·p0.90:   3.920 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.339 ms/op
                 getUser·p0.999:  11.682 ms/op
                 getUser·p0.9999: 27.468 ms/op
                 getUser·p1.00:   28.705 ms/op

Iteration   2: 3.542 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.485 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.873 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  21.816 ms/op
                 getUser·p0.9999: 24.904 ms/op
                 getUser·p1.00:   25.952 ms/op

Iteration   3: 3.446 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.532 ms/op
                 getUser·p0.50:   3.326 ms/op
                 getUser·p0.90:   3.916 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  19.929 ms/op
                 getUser·p0.9999: 26.435 ms/op
                 getUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276449
  mean =      3.470 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12093 
    [ 2.500,  5.000) = 253743 
    [ 5.000,  7.500) = 9027 
    [ 7.500, 10.000) = 1050 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 98 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.936 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     17.465 ms/op
     p(99.9900) =     26.509 ms/op
     p(99.9990) =     28.647 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 10.508 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.013 ms/op
Iteration   1: 4.212 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.424 ms/op
                 listUser·p0.999:  19.530 ms/op
                 listUser·p0.9999: 23.947 ms/op
                 listUser·p1.00:   24.740 ms/op

Iteration   2: 4.090 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 16.524 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   3: 3.953 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.408 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.922 ms/op
                 listUser·p0.999:  14.598 ms/op
                 listUser·p0.9999: 22.377 ms/op
                 listUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235073
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 69 
    [ 2.500,  5.000) = 222645 
    [ 5.000,  7.500) = 8687 
    [ 7.500, 10.000) = 2739 
    [10.000, 12.500) = 408 
    [12.500, 15.000) = 232 
    [15.000, 17.500) = 132 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     15.860 ms/op
     p(99.9900) =     22.593 ms/op
     p(99.9990) =     24.717 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.382 ± 2.700  ops/ms
ClientPb.existUser                       thrpt       3   9.764 ± 3.216  ops/ms
ClientPb.getUser                         thrpt       3   9.325 ± 2.573  ops/ms
ClientPb.listUser                        thrpt       3   8.107 ± 2.783  ops/ms
ClientPb.createUser                       avgt       3   3.533 ± 1.148   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 0.614   ms/op
ClientPb.getUser                          avgt       3   3.469 ± 1.363   ms/op
ClientPb.listUser                         avgt       3   4.019 ± 1.591   ms/op
ClientPb.createUser                     sample  274319   3.500 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.585           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.010           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.906           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.738           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.504           ms/op
ClientPb.existUser                      sample  285115   3.364 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.797           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.219           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.300           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.681           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.019           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.001           ms/op
ClientPb.getUser                        sample  276449   3.470 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.485           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.538           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.799           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.465           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.509           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.705           ms/op
ClientPb.listUser                       sample  235073   4.083 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.094           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.514           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.104           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.192           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.860           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.593           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.740           ms/op
