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
# Warmup Iteration   1: 2.187 ops/ms
# Warmup Iteration   2: 5.943 ops/ms
# Warmup Iteration   3: 8.616 ops/ms
Iteration   1: 9.303 ops/ms
Iteration   2: 9.109 ops/ms
Iteration   3: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.171 ±(99.9%) 2.082 ops/ms [Average]
  (min, avg, max) = (9.102, 9.171, 9.303), stdev = 0.114
  CI (99.9%): [7.089, 11.254] (assumes normal distribution)


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
# Warmup Iteration   1: 3.076 ops/ms
# Warmup Iteration   2: 8.496 ops/ms
# Warmup Iteration   3: 9.597 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.652 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.527 ±(99.9%) 2.454 ops/ms [Average]
  (min, avg, max) = (9.385, 9.527, 9.652), stdev = 0.135
  CI (99.9%): [7.073, 11.982] (assumes normal distribution)


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
# Warmup Iteration   1: 3.259 ops/ms
# Warmup Iteration   2: 8.633 ops/ms
# Warmup Iteration   3: 9.200 ops/ms
Iteration   1: 9.249 ops/ms
Iteration   2: 9.294 ops/ms
Iteration   3: 9.251 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.265 ±(99.9%) 0.463 ops/ms [Average]
  (min, avg, max) = (9.249, 9.265, 9.294), stdev = 0.025
  CI (99.9%): [8.802, 9.727] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 2.767 ops/ms
# Warmup Iteration   2: 6.847 ops/ms
# Warmup Iteration   3: 7.775 ops/ms
Iteration   1: 7.777 ops/ms
Iteration   2: 7.812 ops/ms
Iteration   3: 7.922 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.837 ±(99.9%) 1.382 ops/ms [Average]
  (min, avg, max) = (7.777, 7.837, 7.922), stdev = 0.076
  CI (99.9%): [6.456, 9.219] (assumes normal distribution)


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
# Warmup Iteration   1: 10.449 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.005 ms/op
Iteration   1: 3.565 ±(99.9%) 0.007 ms/op
Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
Iteration   3: 3.424 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.517 ±(99.9%) 1.459 ms/op [Average]
  (min, avg, max) = (3.424, 3.517, 3.565), stdev = 0.080
  CI (99.9%): [2.058, 4.976] (assumes normal distribution)


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
# Warmup Iteration   1: 8.518 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.003 ms/op
Iteration   1: 3.333 ±(99.9%) 0.006 ms/op
Iteration   2: 3.294 ±(99.9%) 0.004 ms/op
Iteration   3: 3.344 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.324 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (3.294, 3.324, 3.344), stdev = 0.026
  CI (99.9%): [2.842, 3.805] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.912 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.660 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.005 ms/op
Iteration   1: 3.538 ±(99.9%) 0.004 ms/op
Iteration   2: 3.486 ±(99.9%) 0.005 ms/op
Iteration   3: 3.430 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.485 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.430, 3.485, 3.538), stdev = 0.054
  CI (99.9%): [2.501, 4.469] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.076 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.403 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.316 ±(99.9%) 0.006 ms/op
Iteration   1: 4.173 ±(99.9%) 0.010 ms/op
Iteration   2: 4.116 ±(99.9%) 0.006 ms/op
Iteration   3: 4.095 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.128 ±(99.9%) 0.734 ms/op [Average]
  (min, avg, max) = (4.095, 4.128, 4.173), stdev = 0.040
  CI (99.9%): [3.394, 4.862] (assumes normal distribution)


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
# Warmup Iteration   1: 9.192 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.009 ms/op
Iteration   1: 3.557 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.210 ms/op
                 createUser·p0.50:   3.457 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.342 ms/op
                 createUser·p0.99:   5.740 ms/op
                 createUser·p0.999:  18.614 ms/op
                 createUser·p0.9999: 20.611 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.380 ms/op
                 createUser·p0.50:   3.351 ms/op
                 createUser·p0.90:   4.157 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   5.521 ms/op
                 createUser·p0.999:  19.213 ms/op
                 createUser·p0.9999: 24.669 ms/op
                 createUser·p1.00:   25.330 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.579 ms/op
                 createUser·p0.999:  19.826 ms/op
                 createUser·p0.9999: 25.985 ms/op
                 createUser·p1.00:   27.165 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273595
  mean =      3.509 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4325 
    [ 2.500,  5.000) = 264728 
    [ 5.000,  7.500) = 3710 
    [ 7.500, 10.000) = 314 
    [10.000, 12.500) = 155 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.210 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.096 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      5.612 ms/op
     p(99.9000) =     18.822 ms/op
     p(99.9900) =     25.023 ms/op
     p(99.9990) =     26.851 ms/op
     p(99.9999) =     27.165 ms/op
    p(100.0000) =     27.165 ms/op


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
# Warmup Iteration   1: 8.054 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.008 ms/op
Iteration   1: 3.384 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.454 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.047 ms/op
                 existUser·p0.99:   5.269 ms/op
                 existUser·p0.999:  17.746 ms/op
                 existUser·p0.9999: 27.587 ms/op
                 existUser·p1.00:   28.410 ms/op

Iteration   2: 3.367 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.493 ms/op
                 existUser·p0.50:   3.310 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  19.286 ms/op
                 existUser·p0.9999: 25.756 ms/op
                 existUser·p1.00:   26.345 ms/op

Iteration   3: 3.453 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.946 ms/op
                 existUser·p0.50:   3.334 ms/op
                 existUser·p0.90:   3.944 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.046 ms/op
                 existUser·p0.999:  13.292 ms/op
                 existUser·p0.9999: 24.371 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282179
  mean =      3.401 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12560 
    [ 2.500,  5.000) = 264957 
    [ 5.000,  7.500) = 3854 
    [ 7.500, 10.000) = 304 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      0.946 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.145 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     13.655 ms/op
     p(99.9900) =     26.076 ms/op
     p(99.9990) =     28.015 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.587 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.805 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.699 ±(99.9%) 0.010 ms/op
Iteration   1: 3.541 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.961 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.292 ms/op
                 getUser·p0.999:  15.822 ms/op
                 getUser·p0.9999: 18.380 ms/op
                 getUser·p1.00:   19.694 ms/op

Iteration   2: 3.514 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.383 ms/op
                 getUser·p0.90:   3.981 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  12.552 ms/op
                 getUser·p0.9999: 19.497 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 3.508 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.538 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   5.513 ms/op
                 getUser·p0.999:  19.618 ms/op
                 getUser·p0.9999: 23.746 ms/op
                 getUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272343
  mean =      3.521 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2772 
    [ 2.500,  5.000) = 264031 
    [ 5.000,  7.500) = 3993 
    [ 7.500, 10.000) = 881 
    [10.000, 12.500) = 339 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.400 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.136 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     22.569 ms/op
     p(99.9990) =     24.379 ms/op
     p(99.9999) =     25.362 ms/op
    p(100.0000) =     25.362 ms/op


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
# Warmup Iteration   1: 10.073 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.013 ms/op
Iteration   1: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.708 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.678 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  19.125 ms/op
                 listUser·p0.9999: 24.220 ms/op
                 listUser·p1.00:   24.838 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.011 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  16.140 ms/op
                 listUser·p0.9999: 18.820 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.056 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   4.719 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 16.450 ms/op
                 listUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237087
  mean =      4.046 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 229636 
    [ 5.000,  7.500) = 5574 
    [ 7.500, 10.000) = 883 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 221 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.708 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.743 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     15.727 ms/op
     p(99.9900) =     23.078 ms/op
     p(99.9990) =     24.736 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.171 ± 2.082  ops/ms
ClientPb.existUser                       thrpt       3   9.527 ± 2.454  ops/ms
ClientPb.getUser                         thrpt       3   9.265 ± 0.463  ops/ms
ClientPb.listUser                        thrpt       3   7.837 ± 1.382  ops/ms
ClientPb.createUser                       avgt       3   3.517 ± 1.459   ms/op
ClientPb.existUser                        avgt       3   3.324 ± 0.482   ms/op
ClientPb.getUser                          avgt       3   3.485 ± 0.984   ms/op
ClientPb.listUser                         avgt       3   4.128 ± 0.734   ms/op
ClientPb.createUser                     sample  273595   3.509 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.210           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.371           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.096           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.342           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.612           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.822           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.023           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.165           ms/op
ClientPb.existUser                      sample  282179   3.401 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.946           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.145           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.652           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.655           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.076           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.410           ms/op
ClientPb.getUser                        sample  272343   3.521 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.442           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.400           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.136           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.811           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.569           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.362           ms/op
ClientPb.listUser                       sample  237087   4.046 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.743           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.727           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.078           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.838           ms/op
