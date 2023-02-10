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
# Warmup Iteration   1: 2.052 ops/ms
# Warmup Iteration   2: 5.694 ops/ms
# Warmup Iteration   3: 8.867 ops/ms
Iteration   1: 9.217 ops/ms
Iteration   2: 9.508 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.304 ±(99.9%) 3.236 ops/ms [Average]
  (min, avg, max) = (9.186, 9.304, 9.508), stdev = 0.177
  CI (99.9%): [6.068, 12.539] (assumes normal distribution)


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
# Warmup Iteration   1: 3.066 ops/ms
# Warmup Iteration   2: 8.895 ops/ms
# Warmup Iteration   3: 9.504 ops/ms
Iteration   1: 9.537 ops/ms
Iteration   2: 9.462 ops/ms
Iteration   3: 9.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.571 ±(99.9%) 2.375 ops/ms [Average]
  (min, avg, max) = (9.462, 9.571, 9.715), stdev = 0.130
  CI (99.9%): [7.197, 11.946] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.902 ops/ms
# Warmup Iteration   2: 8.038 ops/ms
# Warmup Iteration   3: 9.369 ops/ms
Iteration   1: 9.010 ops/ms
Iteration   2: 9.475 ops/ms
Iteration   3: 9.346 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.277 ±(99.9%) 4.384 ops/ms [Average]
  (min, avg, max) = (9.010, 9.277, 9.475), stdev = 0.240
  CI (99.9%): [4.893, 13.660] (assumes normal distribution)


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
# Warmup Iteration   1: 2.758 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 8.091 ops/ms
Iteration   2: 7.972 ops/ms
Iteration   3: 7.986 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.016 ±(99.9%) 1.184 ops/ms [Average]
  (min, avg, max) = (7.972, 8.016, 8.091), stdev = 0.065
  CI (99.9%): [6.832, 9.200] (assumes normal distribution)


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
# Warmup Iteration   1: 8.226 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.700 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.011 ms/op
Iteration   1: 3.477 ±(99.9%) 0.005 ms/op
Iteration   2: 3.305 ±(99.9%) 0.010 ms/op
Iteration   3: 3.408 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.305, 3.397, 3.477), stdev = 0.087
  CI (99.9%): [1.818, 4.975] (assumes normal distribution)


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
# Warmup Iteration   1: 9.316 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.004 ms/op
Iteration   1: 3.185 ±(99.9%) 0.008 ms/op
Iteration   2: 3.110 ±(99.9%) 0.010 ms/op
Iteration   3: 3.219 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.172 ±(99.9%) 1.014 ms/op [Average]
  (min, avg, max) = (3.110, 3.172, 3.219), stdev = 0.056
  CI (99.9%): [2.158, 4.185] (assumes normal distribution)


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
# Warmup Iteration   1: 10.031 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.655 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.574 ±(99.9%) 0.008 ms/op
Iteration   1: 3.419 ±(99.9%) 0.009 ms/op
Iteration   2: 3.426 ±(99.9%) 0.004 ms/op
Iteration   3: 3.353 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.399 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (3.353, 3.399, 3.426), stdev = 0.041
  CI (99.9%): [2.658, 4.141] (assumes normal distribution)


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
# Warmup Iteration   1: 11.202 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.060 ±(99.9%) 0.008 ms/op
Iteration   1: 4.024 ±(99.9%) 0.008 ms/op
Iteration   2: 3.829 ±(99.9%) 0.013 ms/op
Iteration   3: 3.817 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.890 ±(99.9%) 2.117 ms/op [Average]
  (min, avg, max) = (3.817, 3.890, 4.024), stdev = 0.116
  CI (99.9%): [1.773, 6.007] (assumes normal distribution)


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
# Warmup Iteration   1: 11.069 ±(99.9%) 0.146 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.013 ms/op
Iteration   1: 3.604 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.492 ms/op
                 createUser·p0.999:  14.603 ms/op
                 createUser·p0.9999: 38.535 ms/op
                 createUser·p1.00:   42.467 ms/op

Iteration   2: 3.428 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.030 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.865 ms/op
                 createUser·p0.999:  24.331 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   33.423 ms/op

Iteration   3: 3.381 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.221 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.685 ms/op
                 createUser·p0.999:  19.735 ms/op
                 createUser·p0.9999: 59.310 ms/op
                 createUser·p1.00:   61.473 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277040
  mean =      3.468 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 267648 
    [ 5.000, 10.000) = 8913 
    [10.000, 15.000) = 178 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 84 
    [25.000, 30.000) = 78 
    [30.000, 35.000) = 21 
    [35.000, 40.000) = 30 
    [40.000, 45.000) = 2 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 5 
    [55.000, 60.000) = 21 
    [60.000, 65.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      4.035 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     16.659 ms/op
     p(99.9900) =     55.249 ms/op
     p(99.9990) =     60.817 ms/op
     p(99.9999) =     61.473 ms/op
    p(100.0000) =     61.473 ms/op


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
# Warmup Iteration   1: 8.934 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.610 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.329 ±(99.9%) 0.008 ms/op
Iteration   1: 3.163 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  8.175 ms/op
                 existUser·p0.9999: 22.177 ms/op
                 existUser·p1.00:   22.675 ms/op

Iteration   2: 3.291 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.662 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   5.243 ms/op
                 existUser·p0.999:  10.885 ms/op
                 existUser·p0.9999: 29.824 ms/op
                 existUser·p1.00:   30.409 ms/op

Iteration   3: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.448 ms/op
                 existUser·p0.50:   3.265 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.133 ms/op
                 existUser·p0.99:   6.029 ms/op
                 existUser·p0.999:  16.223 ms/op
                 existUser·p0.9999: 23.344 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294236
  mean =      3.260 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19660 
    [ 2.500,  5.000) = 270162 
    [ 5.000,  7.500) = 3649 
    [ 7.500, 10.000) = 419 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     10.875 ms/op
     p(99.9900) =     26.781 ms/op
     p(99.9990) =     30.278 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 8.757 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.012 ms/op
Iteration   1: 3.416 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.703 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  20.147 ms/op
                 getUser·p0.9999: 22.663 ms/op
                 getUser·p1.00:   23.298 ms/op

Iteration   2: 3.420 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.370 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.834 ms/op
                 getUser·p0.95:   4.162 ms/op
                 getUser·p0.99:   6.020 ms/op
                 getUser·p0.999:  22.476 ms/op
                 getUser·p0.9999: 28.594 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 3.546 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.577 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.751 ms/op
                 getUser·p0.99:   7.193 ms/op
                 getUser·p0.999:  12.976 ms/op
                 getUser·p0.9999: 25.327 ms/op
                 getUser·p1.00:   26.051 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277721
  mean =      3.460 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4450 
    [ 2.500,  5.000) = 264541 
    [ 5.000,  7.500) = 7292 
    [ 7.500, 10.000) = 840 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.582 ms/op
     p(99.9900) =     27.312 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 10.418 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.484 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
Iteration   1: 3.862 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.837 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.196 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   6.283 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 25.148 ms/op
                 listUser·p1.00:   26.411 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   8.028 ms/op
                 listUser·p0.999:  16.302 ms/op
                 listUser·p0.9999: 20.480 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.952 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.181 ms/op
                 listUser·p0.9999: 17.429 ms/op
                 listUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243425
  mean =      3.940 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 236475 
    [ 5.000,  7.500) = 4619 
    [ 7.500, 10.000) = 1535 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 259 
    [15.000, 17.500) = 183 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.837 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.538 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     16.269 ms/op
     p(99.9900) =     23.931 ms/op
     p(99.9990) =     25.760 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.304 ± 3.236  ops/ms
ClientPb.existUser                       thrpt       3   9.571 ± 2.375  ops/ms
ClientPb.getUser                         thrpt       3   9.277 ± 4.384  ops/ms
ClientPb.listUser                        thrpt       3   8.016 ± 1.184  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 1.579   ms/op
ClientPb.existUser                        avgt       3   3.172 ± 1.014   ms/op
ClientPb.getUser                          avgt       3   3.399 ± 0.742   ms/op
ClientPb.listUser                         avgt       3   3.890 ± 2.117   ms/op
ClientPb.createUser                     sample  277040   3.468 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.465           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.659           ms/op
ClientPb.createUser:createUser·p0.9999  sample          55.249           ms/op
ClientPb.createUser:createUser·p1.00    sample          61.473           ms/op
ClientPb.existUser                      sample  294236   3.260 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.143           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.494           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.636           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.875           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.781           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  277721   3.460 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.370           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.582           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.312           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.360           ms/op
ClientPb.listUser                       sample  243425   3.940 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.837           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.785           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.365           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.269           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.931           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.411           ms/op
