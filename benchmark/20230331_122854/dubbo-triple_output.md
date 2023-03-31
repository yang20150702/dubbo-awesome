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
# Warmup Iteration   1: 2.420 ops/ms
# Warmup Iteration   2: 5.927 ops/ms
# Warmup Iteration   3: 8.664 ops/ms
Iteration   1: 9.464 ops/ms
Iteration   2: 9.480 ops/ms
Iteration   3: 9.056 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.334 ±(99.9%) 4.384 ops/ms [Average]
  (min, avg, max) = (9.056, 9.334, 9.480), stdev = 0.240
  CI (99.9%): [4.950, 13.717] (assumes normal distribution)


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
# Warmup Iteration   1: 2.610 ops/ms
# Warmup Iteration   2: 8.220 ops/ms
# Warmup Iteration   3: 8.845 ops/ms
Iteration   1: 9.642 ops/ms
Iteration   2: 9.636 ops/ms
Iteration   3: 9.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.571 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (9.436, 9.571, 9.642), stdev = 0.117
  CI (99.9%): [7.430, 11.712] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.691 ops/ms
# Warmup Iteration   2: 8.113 ops/ms
# Warmup Iteration   3: 8.623 ops/ms
Iteration   1: 9.208 ops/ms
Iteration   2: 9.071 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.282 ±(99.9%) 4.685 ops/ms [Average]
  (min, avg, max) = (9.071, 9.282, 9.568), stdev = 0.257
  CI (99.9%): [4.598, 13.967] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.860 ops/ms
# Warmup Iteration   2: 7.315 ops/ms
# Warmup Iteration   3: 7.930 ops/ms
Iteration   1: 7.946 ops/ms
Iteration   2: 7.859 ops/ms
Iteration   3: 8.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.010 ±(99.9%) 3.489 ops/ms [Average]
  (min, avg, max) = (7.859, 8.010, 8.225), stdev = 0.191
  CI (99.9%): [4.521, 11.499] (assumes normal distribution)


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
# Warmup Iteration   1: 11.164 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.594 ±(99.9%) 0.008 ms/op
Iteration   1: 3.438 ±(99.9%) 0.006 ms/op
Iteration   2: 3.525 ±(99.9%) 0.005 ms/op
Iteration   3: 3.367 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.443 ±(99.9%) 1.440 ms/op [Average]
  (min, avg, max) = (3.367, 3.443, 3.525), stdev = 0.079
  CI (99.9%): [2.003, 4.883] (assumes normal distribution)


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
# Warmup Iteration   1: 8.701 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.495 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.009 ms/op
Iteration   1: 3.406 ±(99.9%) 0.003 ms/op
Iteration   2: 3.401 ±(99.9%) 0.004 ms/op
Iteration   3: 3.418 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.409 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (3.401, 3.409, 3.418), stdev = 0.009
  CI (99.9%): [3.249, 3.568] (assumes normal distribution)


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
# Warmup Iteration   1: 10.419 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.003 ms/op
Iteration   1: 3.652 ±(99.9%) 0.007 ms/op
Iteration   2: 3.547 ±(99.9%) 0.008 ms/op
Iteration   3: 3.533 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.578 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.533, 3.578, 3.652), stdev = 0.065
  CI (99.9%): [2.390, 4.765] (assumes normal distribution)


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
# Warmup Iteration   1: 9.793 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.387 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.190 ±(99.9%) 0.005 ms/op
Iteration   1: 3.983 ±(99.9%) 0.009 ms/op
Iteration   2: 3.946 ±(99.9%) 0.012 ms/op
Iteration   3: 3.939 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.956 ±(99.9%) 0.433 ms/op [Average]
  (min, avg, max) = (3.939, 3.956, 3.983), stdev = 0.024
  CI (99.9%): [3.523, 4.389] (assumes normal distribution)


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
# Warmup Iteration   1: 11.218 ±(99.9%) 0.143 ms/op
# Warmup Iteration   2: 4.213 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.014 ms/op
Iteration   1: 3.426 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.624 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.235 ms/op
                 createUser·p0.99:   5.792 ms/op
                 createUser·p0.999:  19.222 ms/op
                 createUser·p0.9999: 24.936 ms/op
                 createUser·p1.00:   26.509 ms/op

Iteration   2: 3.441 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.460 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.928 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  21.662 ms/op
                 createUser·p0.9999: 24.720 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.489 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  21.968 ms/op
                 createUser·p0.9999: 29.062 ms/op
                 createUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277964
  mean =      3.452 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5139 
    [ 2.500,  5.000) = 266040 
    [ 5.000,  7.500) = 5803 
    [ 7.500, 10.000) = 541 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      5.751 ms/op
     p(99.9000) =     19.761 ms/op
     p(99.9900) =     27.270 ms/op
     p(99.9990) =     29.295 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 8.401 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.539 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.008 ms/op
Iteration   1: 3.259 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.450 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.998 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  8.815 ms/op
                 existUser·p0.9999: 23.448 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.264 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.133 ms/op
                 existUser·p0.50:   3.154 ms/op
                 existUser·p0.90:   3.564 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.538 ms/op
                 existUser·p0.999:  11.797 ms/op
                 existUser·p0.9999: 23.842 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.234 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.768 ms/op
                 existUser·p0.99:   5.669 ms/op
                 existUser·p0.999:  13.107 ms/op
                 existUser·p0.9999: 24.055 ms/op
                 existUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294984
  mean =      3.252 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8131 
    [ 2.500,  5.000) = 282494 
    [ 5.000,  7.500) = 3346 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 105 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     13.091 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     26.323 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 8.869 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.498 ±(99.9%) 0.010 ms/op
Iteration   1: 3.537 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.297 ms/op
                 getUser·p0.90:   4.265 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  19.024 ms/op
                 getUser·p0.9999: 28.901 ms/op
                 getUser·p1.00:   29.983 ms/op

Iteration   2: 3.426 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.973 ms/op
                 getUser·p0.95:   4.190 ms/op
                 getUser·p0.99:   5.677 ms/op
                 getUser·p0.999:  19.299 ms/op
                 getUser·p0.9999: 21.932 ms/op
                 getUser·p1.00:   22.479 ms/op

Iteration   3: 3.345 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   5.841 ms/op
                 getUser·p0.999:  15.548 ms/op
                 getUser·p0.9999: 24.547 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279331
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8009 
    [ 2.500,  5.000) = 262524 
    [ 5.000,  7.500) = 7801 
    [ 7.500, 10.000) = 568 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 137 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.133 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      6.414 ms/op
     p(99.9000) =     17.880 ms/op
     p(99.9900) =     27.853 ms/op
     p(99.9990) =     29.727 ms/op
     p(99.9999) =     29.983 ms/op
    p(100.0000) =     29.983 ms/op


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
# Warmup Iteration   1: 9.226 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.954 ±(99.9%) 0.012 ms/op
Iteration   1: 4.049 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.659 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.620 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 21.142 ms/op
                 listUser·p1.00:   21.627 ms/op

Iteration   2: 3.898 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.968 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  14.678 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 4.128 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.347 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   7.665 ms/op
                 listUser·p0.999:  13.657 ms/op
                 listUser·p0.9999: 23.298 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238550
  mean =      4.023 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53 
    [ 2.500,  5.000) = 227191 
    [ 5.000,  7.500) = 8996 
    [ 7.500, 10.000) = 1648 
    [10.000, 12.500) = 202 
    [12.500, 15.000) = 248 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.659 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     14.877 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.334 ± 4.384  ops/ms
ClientPb.existUser                       thrpt       3   9.571 ± 2.141  ops/ms
ClientPb.getUser                         thrpt       3   9.282 ± 4.685  ops/ms
ClientPb.listUser                        thrpt       3   8.010 ± 3.489  ops/ms
ClientPb.createUser                       avgt       3   3.443 ± 1.440   ms/op
ClientPb.existUser                        avgt       3   3.409 ± 0.159   ms/op
ClientPb.getUser                          avgt       3   3.578 ± 1.187   ms/op
ClientPb.listUser                         avgt       3   3.956 ± 0.433   ms/op
ClientPb.createUser                     sample  277964   3.452 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.936           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.322           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.916           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.391           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.751           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.761           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.270           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.655           ms/op
ClientPb.existUser                      sample  294984   3.252 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.133           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.154           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.846           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.091           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.691           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.475           ms/op
ClientPb.getUser                        sample  279331   3.434 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.133           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.383           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.880           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.853           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.983           ms/op
ClientPb.listUser                       sample  238550   4.023 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.659           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.838           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.877           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.053           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.364           ms/op
