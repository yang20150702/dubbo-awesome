# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.482 ops/ms
# Warmup Iteration   2: 11.488 ops/ms
# Warmup Iteration   3: 12.258 ops/ms
Iteration   1: 12.499 ops/ms
Iteration   2: 12.822 ops/ms
Iteration   3: 12.737 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.686 ±(99.9%) 3.060 ops/ms [Average]
  (min, avg, max) = (12.499, 12.686, 12.822), stdev = 0.168
  CI (99.9%): [9.626, 15.745] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.305 ops/ms
# Warmup Iteration   2: 12.682 ops/ms
# Warmup Iteration   3: 12.773 ops/ms
Iteration   1: 12.804 ops/ms
Iteration   2: 12.776 ops/ms
Iteration   3: 12.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.742 ±(99.9%) 1.550 ops/ms [Average]
  (min, avg, max) = (12.645, 12.742, 12.804), stdev = 0.085
  CI (99.9%): [11.191, 14.292] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.750 ops/ms
# Warmup Iteration   2: 12.761 ops/ms
# Warmup Iteration   3: 12.746 ops/ms
Iteration   1: 12.856 ops/ms
Iteration   2: 12.852 ops/ms
Iteration   3: 12.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.871 ±(99.9%) 0.530 ops/ms [Average]
  (min, avg, max) = (12.852, 12.871, 12.904), stdev = 0.029
  CI (99.9%): [12.341, 13.401] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.684 ops/ms
# Warmup Iteration   2: 10.473 ops/ms
# Warmup Iteration   3: 10.611 ops/ms
Iteration   1: 10.632 ops/ms
Iteration   2: 10.725 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.686 ±(99.9%) 0.873 ops/ms [Average]
  (min, avg, max) = (10.632, 10.686, 10.725), stdev = 0.048
  CI (99.9%): [9.813, 11.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.969 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.514 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.003 ms/op
Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
Iteration   3: 2.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.522 ±(99.9%) 0.194 ms/op [Average]
  (min, avg, max) = (2.510, 2.522, 2.530), stdev = 0.011
  CI (99.9%): [2.328, 2.716] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.541 ±(99.9%) 0.008 ms/op
# Warmup Iteration   2: 2.497 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.451 ±(99.9%) 0.003 ms/op
Iteration   1: 2.442 ±(99.9%) 0.005 ms/op
Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
Iteration   3: 2.457 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.444 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.435, 2.444, 2.457), stdev = 0.011
  CI (99.9%): [2.236, 2.653] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.751 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.541 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.501 ±(99.9%) 0.004 ms/op
Iteration   1: 2.489 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.505 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.499 ±(99.9%) 0.156 ms/op [Average]
  (min, avg, max) = (2.489, 2.499, 2.505), stdev = 0.009
  CI (99.9%): [2.343, 2.655] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.005 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
Iteration   3: 3.041 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.031 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.014, 3.031, 3.041), stdev = 0.015
  CI (99.9%): [2.756, 3.307] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.281 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.643 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.497 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.515 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  11.194 ms/op
                 createUser·p0.9999: 13.114 ms/op
                 createUser·p1.00:   13.910 ms/op

Iteration   2: 2.566 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.978 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.142 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  10.387 ms/op
                 createUser·p0.9999: 12.985 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 2.535 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.974 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.203 ms/op
                 createUser·p0.99:   3.781 ms/op
                 createUser·p0.999:  8.002 ms/op
                 createUser·p0.9999: 11.724 ms/op
                 createUser·p1.00:   12.993 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378611
  mean =      2.533 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 185148 
    [ 2.500,  3.750) = 189054 
    [ 3.750,  5.000) = 3524 
    [ 5.000,  6.250) = 387 
    [ 6.250,  7.500) = 58 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 71 
    [11.250, 12.500) = 151 
    [12.500, 13.750) = 69 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.097 ms/op
     p(95.0000) =      3.224 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =      8.339 ms/op
     p(99.9900) =     12.934 ms/op
     p(99.9990) =     13.844 ms/op
     p(99.9999) =     13.910 ms/op
    p(100.0000) =     13.910 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.660 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
Iteration   1: 2.467 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.785 ms/op
                 existUser·p0.999:  8.208 ms/op
                 existUser·p0.9999: 13.404 ms/op
                 existUser·p1.00:   13.926 ms/op

Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.018 ms/op
                 existUser·p0.50:   2.548 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.514 ms/op
                 existUser·p0.999:  5.545 ms/op
                 existUser·p0.9999: 14.412 ms/op
                 existUser·p1.00:   15.434 ms/op

Iteration   3: 2.438 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.055 ms/op
                 existUser·p0.50:   2.470 ms/op
                 existUser·p0.90:   2.966 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.551 ms/op
                 existUser·p0.999:  7.781 ms/op
                 existUser·p0.9999: 11.502 ms/op
                 existUser·p1.00:   11.928 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390061
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 64 
    [ 1.250,  2.500) = 195787 
    [ 2.500,  3.750) = 191137 
    [ 3.750,  5.000) = 2372 
    [ 5.000,  6.250) = 276 
    [ 6.250,  7.500) = 60 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 47 
    [10.000, 11.250) = 74 
    [11.250, 12.500) = 81 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.840 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.604 ms/op
     p(99.9000) =      6.733 ms/op
     p(99.9900) =     13.648 ms/op
     p(99.9990) =     14.952 ms/op
     p(99.9999) =     15.434 ms/op
    p(100.0000) =     15.434 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.567 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.006 ms/op
Iteration   1: 2.503 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.912 ms/op
                 getUser·p0.50:   2.531 ms/op
                 getUser·p0.90:   3.043 ms/op
                 getUser·p0.95:   3.203 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  11.433 ms/op
                 getUser·p0.9999: 13.533 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.867 ms/op
                 getUser·p0.999:  9.590 ms/op
                 getUser·p0.9999: 12.458 ms/op
                 getUser·p1.00:   13.484 ms/op

Iteration   3: 2.478 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.857 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.580 ms/op
                 getUser·p0.999:  7.204 ms/op
                 getUser·p0.9999: 11.356 ms/op
                 getUser·p1.00:   11.747 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 384844
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 191384 
    [ 2.500,  3.750) = 188397 
    [ 3.750,  5.000) = 3754 
    [ 5.000,  6.250) = 757 
    [ 6.250,  7.500) = 98 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 118 
    [11.250, 12.500) = 134 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.166 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =      7.817 ms/op
     p(99.9900) =     12.813 ms/op
     p(99.9990) =     13.833 ms/op
     p(99.9999) =     14.172 ms/op
    p(100.0000) =     14.172 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.641 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.984 ms/op
                 listUser·p0.50:   2.978 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.440 ms/op
                 listUser·p0.99:   5.530 ms/op
                 listUser·p0.999:  9.205 ms/op
                 listUser·p0.9999: 10.985 ms/op
                 listUser·p1.00:   11.551 ms/op

Iteration   2: 3.019 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.586 ms/op
                 listUser·p0.9999: 11.269 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 3.018 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.983 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.373 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.731 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316999
  mean =      3.026 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 91092 
    [ 2.500,  3.750) = 185341 
    [ 3.750,  5.000) = 32858 
    [ 5.000,  6.250) = 6263 
    [ 6.250,  7.500) = 661 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 317 
    [10.000, 11.250) = 123 
    [11.250, 12.500) = 23 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.948 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.415 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     11.059 ms/op
     p(99.9990) =     11.654 ms/op
     p(99.9999) =     11.731 ms/op
    p(100.0000) =     11.731 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.686 ± 3.060  ops/ms
ClientPb.existUser                       thrpt       3  12.742 ± 1.550  ops/ms
ClientPb.getUser                         thrpt       3  12.871 ± 0.530  ops/ms
ClientPb.listUser                        thrpt       3  10.686 ± 0.873  ops/ms
ClientPb.createUser                       avgt       3   2.522 ± 0.194   ms/op
ClientPb.existUser                        avgt       3   2.444 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.499 ± 0.156   ms/op
ClientPb.listUser                         avgt       3   3.031 ± 0.276   ms/op
ClientPb.createUser                     sample  378611   2.533 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.662           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.097           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.224           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.830           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.339           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.934           ms/op
ClientPb.createUser:createUser·p1.00    sample          13.910           ms/op
ClientPb.existUser                      sample  390061   2.459 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.840           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.490           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.604           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.733           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.648           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.434           ms/op
ClientPb.getUser                        sample  384844   2.492 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.786           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.035           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.932           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.817           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.813           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.172           ms/op
ClientPb.listUser                       sample  316999   3.026 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.948           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.916           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.415           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.587           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.059           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.731           ms/op
