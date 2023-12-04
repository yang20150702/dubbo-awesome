# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.495 ops/ms
# Warmup Iteration   2: 12.079 ops/ms
# Warmup Iteration   3: 12.410 ops/ms
Iteration   1: 12.675 ops/ms
Iteration   2: 12.668 ops/ms
Iteration   3: 12.708 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.683 ±(99.9%) 0.385 ops/ms [Average]
  (min, avg, max) = (12.668, 12.683, 12.708), stdev = 0.021
  CI (99.9%): [12.299, 13.068] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.497 ops/ms
# Warmup Iteration   2: 12.647 ops/ms
# Warmup Iteration   3: 12.941 ops/ms
Iteration   1: 13.031 ops/ms
Iteration   2: 13.046 ops/ms
Iteration   3: 12.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.023 ±(99.9%) 0.520 ops/ms [Average]
  (min, avg, max) = (12.991, 13.023, 13.046), stdev = 0.028
  CI (99.9%): [12.503, 13.543] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.595 ops/ms
# Warmup Iteration   2: 12.273 ops/ms
# Warmup Iteration   3: 12.612 ops/ms
Iteration   1: 12.528 ops/ms
Iteration   2: 12.534 ops/ms
Iteration   3: 12.504 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.522 ±(99.9%) 0.291 ops/ms [Average]
  (min, avg, max) = (12.504, 12.522, 12.534), stdev = 0.016
  CI (99.9%): [12.231, 12.813] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.754 ops/ms
# Warmup Iteration   2: 10.415 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.575 ops/ms
Iteration   2: 10.600 ops/ms
Iteration   3: 10.589 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.588 ±(99.9%) 0.224 ops/ms [Average]
  (min, avg, max) = (10.575, 10.588, 10.600), stdev = 0.012
  CI (99.9%): [10.364, 10.812] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.093 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.538 ±(99.9%) 0.004 ms/op
Iteration   1: 2.541 ±(99.9%) 0.004 ms/op
Iteration   2: 2.548 ±(99.9%) 0.004 ms/op
Iteration   3: 2.557 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.548 ±(99.9%) 0.145 ms/op [Average]
  (min, avg, max) = (2.541, 2.548, 2.557), stdev = 0.008
  CI (99.9%): [2.403, 2.694] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.505 ±(99.9%) 0.004 ms/op
Iteration   2: 2.491 ±(99.9%) 0.003 ms/op
Iteration   3: 2.495 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.497 ±(99.9%) 0.135 ms/op [Average]
  (min, avg, max) = (2.491, 2.497, 2.505), stdev = 0.007
  CI (99.9%): [2.362, 2.632] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.841 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.544 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.530 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.494 ±(99.9%) 0.005 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.491 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (2.470, 2.491, 2.510), stdev = 0.020
  CI (99.9%): [2.119, 2.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.562 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.004 ms/op
Iteration   3: 3.051 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.042 ±(99.9%) 0.148 ms/op [Average]
  (min, avg, max) = (3.037, 3.042, 3.051), stdev = 0.008
  CI (99.9%): [2.894, 3.190] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.100 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.661 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.549 ±(99.9%) 0.006 ms/op
Iteration   1: 2.545 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.097 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.509 ms/op
                 createUser·p0.9999: 13.991 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.039 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.772 ms/op
                 createUser·p0.999:  10.281 ms/op
                 createUser·p0.9999: 12.919 ms/op
                 createUser·p1.00:   14.123 ms/op

Iteration   3: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.117 ms/op
                 createUser·p0.95:   3.281 ms/op
                 createUser·p0.99:   4.265 ms/op
                 createUser·p0.999:  8.735 ms/op
                 createUser·p0.9999: 10.855 ms/op
                 createUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377981
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 41 
    [ 1.250,  2.500) = 180834 
    [ 2.500,  3.750) = 191563 
    [ 3.750,  5.000) = 4482 
    [ 5.000,  6.250) = 602 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 66 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 107 
    [12.500, 13.750) = 96 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.211 ms/op
     p(99.0000) =      3.973 ms/op
     p(99.9000) =      8.766 ms/op
     p(99.9900) =     13.307 ms/op
     p(99.9990) =     14.653 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.618 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.552 ms/op
                 existUser·p0.90:   3.015 ms/op
                 existUser·p0.95:   3.133 ms/op
                 existUser·p0.99:   3.670 ms/op
                 existUser·p0.999:  7.475 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   13.943 ms/op

Iteration   2: 2.461 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.984 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.235 ms/op
                 existUser·p0.9999: 12.927 ms/op
                 existUser·p1.00:   14.008 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.752 ms/op
                 existUser·p0.50:   2.535 ms/op
                 existUser·p0.90:   2.949 ms/op
                 existUser·p0.95:   3.060 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  8.771 ms/op
                 existUser·p0.9999: 11.682 ms/op
                 existUser·p1.00:   13.844 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390455
  mean =      2.456 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 191302 
    [ 2.500,  3.750) = 195908 
    [ 3.750,  5.000) = 2471 
    [ 5.000,  6.250) = 312 
    [ 6.250,  7.500) = 36 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 142 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.637 ms/op
     p(99.9000) =      7.534 ms/op
     p(99.9900) =     12.959 ms/op
     p(99.9990) =     13.785 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.556 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.006 ms/op
Iteration   1: 2.519 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.864 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.211 ms/op
                 getUser·p0.99:   3.736 ms/op
                 getUser·p0.999:  10.670 ms/op
                 getUser·p0.9999: 13.910 ms/op
                 getUser·p1.00:   14.074 ms/op

Iteration   2: 2.522 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   2.564 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.912 ms/op
                 getUser·p0.999:  8.917 ms/op
                 getUser·p0.9999: 12.113 ms/op
                 getUser·p1.00:   13.271 ms/op

Iteration   3: 2.538 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   2.580 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.248 ms/op
                 getUser·p0.99:   4.489 ms/op
                 getUser·p0.999:  8.291 ms/op
                 getUser·p0.9999: 12.193 ms/op
                 getUser·p1.00:   13.255 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 379609
  mean =      2.526 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 76 
    [ 1.250,  2.500) = 185308 
    [ 2.500,  3.750) = 188658 
    [ 3.750,  5.000) = 4128 
    [ 5.000,  6.250) = 1015 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 98 
    [11.250, 12.500) = 124 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 20 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.864 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.076 ms/op
     p(95.0000) =      3.215 ms/op
     p(99.0000) =      4.022 ms/op
     p(99.9000) =      8.350 ms/op
     p(99.9900) =     13.124 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.620 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.086 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.009 ms/op
Iteration   1: 3.040 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.866 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.947 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.751 ms/op
                 listUser·p0.999:  10.057 ms/op
                 listUser·p0.9999: 13.090 ms/op
                 listUser·p1.00:   13.844 ms/op

Iteration   2: 3.013 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.846 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.439 ms/op
                 listUser·p0.999:  9.224 ms/op
                 listUser·p0.9999: 11.033 ms/op
                 listUser·p1.00:   11.682 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.956 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   5.685 ms/op
                 listUser·p0.999:  10.272 ms/op
                 listUser·p0.9999: 11.960 ms/op
                 listUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316317
  mean =      3.032 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 113 
    [ 1.250,  2.500) = 88470 
    [ 2.500,  3.750) = 187594 
    [ 3.750,  5.000) = 32557 
    [ 5.000,  6.250) = 6170 
    [ 6.250,  7.500) = 702 
    [ 7.500,  8.750) = 202 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 203 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.866 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =      9.896 ms/op
     p(99.9900) =     12.169 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.844 ms/op
    p(100.0000) =     13.844 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.683 ± 0.385  ops/ms
ClientPb.existUser                       thrpt       3  13.023 ± 0.520  ops/ms
ClientPb.getUser                         thrpt       3  12.522 ± 0.291  ops/ms
ClientPb.listUser                        thrpt       3  10.588 ± 0.224  ops/ms
ClientPb.createUser                       avgt       3   2.548 ± 0.145   ms/op
ClientPb.existUser                        avgt       3   2.497 ± 0.135   ms/op
ClientPb.getUser                          avgt       3   2.491 ± 0.372   ms/op
ClientPb.listUser                         avgt       3   3.042 ± 0.148   ms/op
ClientPb.createUser                     sample  377981   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.908           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.211           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.766           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.307           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.811           ms/op
ClientPb.existUser                      sample  390455   2.456 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.660           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.959           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.008           ms/op
ClientPb.getUser                        sample  379609   2.526 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.864           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.076           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.215           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.022           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.350           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.124           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.074           ms/op
ClientPb.listUser                       sample  316317   3.032 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.866           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.912           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.628           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.896           ms/op
ClientPb.listUser:listUser·p0.9999      sample          12.169           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.844           ms/op
