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
# Warmup Iteration   1: 2.232 ops/ms
# Warmup Iteration   2: 6.027 ops/ms
# Warmup Iteration   3: 8.402 ops/ms
Iteration   1: 8.863 ops/ms
Iteration   2: 9.273 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.094 ±(99.9%) 3.824 ops/ms [Average]
  (min, avg, max) = (8.863, 9.094, 9.273), stdev = 0.210
  CI (99.9%): [5.270, 12.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.322 ops/ms
# Warmup Iteration   2: 8.828 ops/ms
# Warmup Iteration   3: 9.644 ops/ms
Iteration   1: 9.542 ops/ms
Iteration   2: 9.622 ops/ms
Iteration   3: 9.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.588 ±(99.9%) 0.750 ops/ms [Average]
  (min, avg, max) = (9.542, 9.588, 9.622), stdev = 0.041
  CI (99.9%): [8.838, 10.338] (assumes normal distribution)


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
# Warmup Iteration   1: 2.843 ops/ms
# Warmup Iteration   2: 8.379 ops/ms
# Warmup Iteration   3: 9.186 ops/ms
Iteration   1: 8.915 ops/ms
Iteration   2: 9.131 ops/ms
Iteration   3: 9.284 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.110 ±(99.9%) 3.385 ops/ms [Average]
  (min, avg, max) = (8.915, 9.110, 9.284), stdev = 0.186
  CI (99.9%): [5.724, 12.495] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.899 ops/ms
# Warmup Iteration   2: 7.172 ops/ms
# Warmup Iteration   3: 7.603 ops/ms
Iteration   1: 7.709 ops/ms
Iteration   2: 7.961 ops/ms
Iteration   3: 7.707 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.792 ±(99.9%) 2.661 ops/ms [Average]
  (min, avg, max) = (7.707, 7.792, 7.961), stdev = 0.146
  CI (99.9%): [5.131, 10.453] (assumes normal distribution)


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
# Warmup Iteration   1: 10.218 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.005 ms/op
Iteration   1: 3.482 ±(99.9%) 0.004 ms/op
Iteration   2: 3.324 ±(99.9%) 0.009 ms/op
Iteration   3: 3.493 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.433 ±(99.9%) 1.723 ms/op [Average]
  (min, avg, max) = (3.324, 3.433, 3.493), stdev = 0.094
  CI (99.9%): [1.710, 5.156] (assumes normal distribution)


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
# Warmup Iteration   1: 9.190 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.406 ±(99.9%) 0.003 ms/op
Iteration   1: 3.373 ±(99.9%) 0.006 ms/op
Iteration   2: 3.351 ±(99.9%) 0.004 ms/op
Iteration   3: 3.341 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.355 ±(99.9%) 0.293 ms/op [Average]
  (min, avg, max) = (3.341, 3.355, 3.373), stdev = 0.016
  CI (99.9%): [3.062, 3.648] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.537 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.003 ms/op
Iteration   1: 3.454 ±(99.9%) 0.004 ms/op
Iteration   2: 3.429 ±(99.9%) 0.004 ms/op
Iteration   3: 3.457 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.447 ±(99.9%) 0.277 ms/op [Average]
  (min, avg, max) = (3.429, 3.447, 3.457), stdev = 0.015
  CI (99.9%): [3.169, 3.724] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 11.236 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.005 ms/op
Iteration   1: 4.133 ±(99.9%) 0.008 ms/op
Iteration   2: 4.087 ±(99.9%) 0.007 ms/op
Iteration   3: 4.100 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.107 ±(99.9%) 0.439 ms/op [Average]
  (min, avg, max) = (4.087, 4.107, 4.133), stdev = 0.024
  CI (99.9%): [3.668, 4.545] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.919 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.536 ±(99.9%) 0.011 ms/op
Iteration   1: 3.475 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.546 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.944 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  22.251 ms/op
                 createUser·p0.9999: 25.402 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.765 ms/op
                 createUser·p0.50:   3.359 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  22.511 ms/op
                 createUser·p0.9999: 27.342 ms/op
                 createUser·p1.00:   28.869 ms/op

Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.396 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.882 ms/op
                 createUser·p0.999:  20.295 ms/op
                 createUser·p0.9999: 25.756 ms/op
                 createUser·p1.00:   28.115 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 275612
  mean =      3.479 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4577 
    [ 2.500,  5.000) = 265430 
    [ 5.000,  7.500) = 4333 
    [ 7.500, 10.000) = 770 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 56 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 169 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     20.755 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     28.407 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.139 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.007 ms/op
Iteration   1: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.440 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.775 ms/op
                 existUser·p0.999:  17.385 ms/op
                 existUser·p0.9999: 23.951 ms/op
                 existUser·p1.00:   25.100 ms/op

Iteration   2: 3.312 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.516 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  16.408 ms/op
                 existUser·p0.9999: 26.532 ms/op
                 existUser·p1.00:   27.197 ms/op

Iteration   3: 3.336 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.540 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.600 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   6.735 ms/op
                 existUser·p0.999:  18.481 ms/op
                 existUser·p0.9999: 25.403 ms/op
                 existUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289260
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12580 
    [ 2.500,  5.000) = 270930 
    [ 5.000,  7.500) = 4510 
    [ 7.500, 10.000) = 612 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 112 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 52 

  Percentiles, ms/op:
      p(0.0000) =      1.440 ms/op
     p(50.0000) =      3.252 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     25.365 ms/op
     p(99.9990) =     27.070 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.637 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.470 ±(99.9%) 0.009 ms/op
Iteration   1: 3.440 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.165 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  17.528 ms/op
                 getUser·p0.9999: 20.142 ms/op
                 getUser·p1.00:   22.348 ms/op

Iteration   2: 3.422 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.785 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  10.789 ms/op
                 getUser·p0.9999: 22.092 ms/op
                 getUser·p1.00:   22.741 ms/op

Iteration   3: 3.630 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   5.054 ms/op
                 getUser·p0.99:   7.217 ms/op
                 getUser·p0.999:  20.349 ms/op
                 getUser·p0.9999: 23.658 ms/op
                 getUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 274702
  mean =      3.495 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3180 
    [ 2.500,  5.000) = 262987 
    [ 5.000,  7.500) = 7080 
    [ 7.500, 10.000) = 670 
    [10.000, 12.500) = 436 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.243 ms/op
     p(99.9900) =     22.839 ms/op
     p(99.9990) =     24.789 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


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
# Warmup Iteration   1: 10.177 ±(99.9%) 0.151 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.108 ±(99.9%) 0.012 ms/op
Iteration   1: 4.221 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.171 ms/op
                 listUser·p0.50:   4.121 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  16.924 ms/op
                 listUser·p0.9999: 22.788 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   2: 4.153 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   3.994 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.373 ms/op
                 listUser·p0.999:  15.910 ms/op
                 listUser·p0.9999: 17.760 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   3: 4.103 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.187 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.093 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 17.924 ms/op
                 listUser·p1.00:   18.612 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 230618
  mean =      4.158 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 221053 
    [ 5.000,  7.500) = 7412 
    [ 7.500, 10.000) = 1142 
    [10.000, 12.500) = 323 
    [12.500, 15.000) = 342 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.921 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     15.473 ms/op
     p(99.9900) =     22.411 ms/op
     p(99.9990) =     23.304 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.094 ± 3.824  ops/ms
ClientPb.existUser                       thrpt       3   9.588 ± 0.750  ops/ms
ClientPb.getUser                         thrpt       3   9.110 ± 3.385  ops/ms
ClientPb.listUser                        thrpt       3   7.792 ± 2.661  ops/ms
ClientPb.createUser                       avgt       3   3.433 ± 1.723   ms/op
ClientPb.existUser                        avgt       3   3.355 ± 0.293   ms/op
ClientPb.getUser                          avgt       3   3.447 ± 0.277   ms/op
ClientPb.listUser                         avgt       3   4.107 ± 0.439   ms/op
ClientPb.createUser                     sample  275612   3.479 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.255           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.227           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.906           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.755           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.869           ms/op
ClientPb.existUser                      sample  289260   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.440           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.252           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.592           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.956           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.236           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.365           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.197           ms/op
ClientPb.getUser                        sample  274702   3.495 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.910           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.644           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.243           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.839           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.494           ms/op
ClientPb.listUser                       sample  230618   4.158 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.921           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.047           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.858           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.340           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.473           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.411           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.593           ms/op
