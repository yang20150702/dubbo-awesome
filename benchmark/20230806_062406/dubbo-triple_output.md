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
# Warmup Iteration   1: 0.930 ops/ms
# Warmup Iteration   2: 1.946 ops/ms
# Warmup Iteration   3: 4.565 ops/ms
Iteration   1: 5.042 ops/ms
Iteration   2: 5.411 ops/ms
Iteration   3: 5.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.332 ±(99.9%) 4.737 ops/ms [Average]
  (min, avg, max) = (5.042, 5.332, 5.542), stdev = 0.260
  CI (99.9%): [0.594, 10.069] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.473 ops/ms
# Warmup Iteration   2: 4.310 ops/ms
# Warmup Iteration   3: 5.580 ops/ms
Iteration   1: 5.686 ops/ms
Iteration   2: 5.786 ops/ms
Iteration   3: 5.687 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.720 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (5.686, 5.720, 5.786), stdev = 0.058
  CI (99.9%): [4.669, 6.770] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.259 ops/ms
# Warmup Iteration   2: 3.787 ops/ms
# Warmup Iteration   3: 5.200 ops/ms
Iteration   1: 5.296 ops/ms
Iteration   2: 5.532 ops/ms
Iteration   3: 5.459 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.429 ±(99.9%) 2.207 ops/ms [Average]
  (min, avg, max) = (5.296, 5.429, 5.532), stdev = 0.121
  CI (99.9%): [3.222, 7.636] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.407 ops/ms
# Warmup Iteration   2: 3.610 ops/ms
# Warmup Iteration   3: 4.145 ops/ms
Iteration   1: 4.504 ops/ms
Iteration   2: 4.684 ops/ms
Iteration   3: 4.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.567 ±(99.9%) 1.863 ops/ms [Average]
  (min, avg, max) = (4.504, 4.567, 4.684), stdev = 0.102
  CI (99.9%): [2.703, 6.430] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 21.196 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 8.325 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 6.407 ±(99.9%) 0.014 ms/op
Iteration   1: 6.358 ±(99.9%) 0.012 ms/op
Iteration   2: 6.076 ±(99.9%) 0.012 ms/op
Iteration   3: 6.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.149 ±(99.9%) 3.360 ms/op [Average]
  (min, avg, max) = (6.012, 6.149, 6.358), stdev = 0.184
  CI (99.9%): [2.788, 9.509] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 20.973 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.940 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.946 ±(99.9%) 0.007 ms/op
Iteration   1: 5.645 ±(99.9%) 0.012 ms/op
Iteration   2: 5.667 ±(99.9%) 0.009 ms/op
Iteration   3: 5.465 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.592 ±(99.9%) 2.017 ms/op [Average]
  (min, avg, max) = (5.465, 5.592, 5.667), stdev = 0.111
  CI (99.9%): [3.576, 7.609] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 21.489 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.713 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.919 ±(99.9%) 0.005 ms/op
Iteration   1: 5.798 ±(99.9%) 0.015 ms/op
Iteration   2: 5.738 ±(99.9%) 0.010 ms/op
Iteration   3: 5.667 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.735 ±(99.9%) 1.197 ms/op [Average]
  (min, avg, max) = (5.667, 5.735, 5.798), stdev = 0.066
  CI (99.9%): [4.538, 6.931] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 20.798 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 7.755 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.894 ±(99.9%) 0.014 ms/op
Iteration   1: 6.704 ±(99.9%) 0.011 ms/op
Iteration   2: 7.114 ±(99.9%) 0.015 ms/op
Iteration   3: 6.713 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.844 ±(99.9%) 4.268 ms/op [Average]
  (min, avg, max) = (6.704, 6.844, 7.114), stdev = 0.234
  CI (99.9%): [2.575, 11.112] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 19.441 ±(99.9%) 0.338 ms/op
# Warmup Iteration   2: 8.368 ±(99.9%) 0.073 ms/op
# Warmup Iteration   3: 6.319 ±(99.9%) 0.031 ms/op
Iteration   1: 5.888 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.691 ms/op
                 createUser·p0.50:   5.562 ms/op
                 createUser·p0.90:   7.307 ms/op
                 createUser·p0.95:   8.487 ms/op
                 createUser·p0.99:   11.583 ms/op
                 createUser·p0.999:  15.968 ms/op
                 createUser·p0.9999: 28.166 ms/op
                 createUser·p1.00:   28.705 ms/op

Iteration   2: 5.944 ±(99.9%) 0.027 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.530 ms/op
                 createUser·p0.90:   7.569 ms/op
                 createUser·p0.95:   8.569 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  35.127 ms/op
                 createUser·p0.9999: 46.899 ms/op
                 createUser·p1.00:   48.955 ms/op

Iteration   3: 5.787 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.376 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.438 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  30.540 ms/op
                 createUser·p0.9999: 34.472 ms/op
                 createUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 163426
  mean =      5.872 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 38032 
    [ 5.000, 10.000) = 121741 
    [10.000, 15.000) = 3315 
    [15.000, 20.000) = 177 
    [20.000, 25.000) = 1 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 69 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.505 ms/op
     p(90.0000) =      7.389 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     11.567 ms/op
     p(99.9000) =     18.795 ms/op
     p(99.9900) =     45.285 ms/op
     p(99.9990) =     48.706 ms/op
     p(99.9999) =     48.955 ms/op
    p(100.0000) =     48.955 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 18.699 ±(99.9%) 0.337 ms/op
# Warmup Iteration   2: 7.816 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.117 ±(99.9%) 0.027 ms/op
Iteration   1: 5.775 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.753 ms/op
                 existUser·p0.50:   5.439 ms/op
                 existUser·p0.90:   7.315 ms/op
                 existUser·p0.95:   8.765 ms/op
                 existUser·p0.99:   12.239 ms/op
                 existUser·p0.999:  25.646 ms/op
                 existUser·p0.9999: 30.358 ms/op
                 existUser·p1.00:   32.309 ms/op

Iteration   2: 5.804 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.703 ms/op
                 existUser·p0.50:   5.439 ms/op
                 existUser·p0.90:   7.422 ms/op
                 existUser·p0.95:   8.913 ms/op
                 existUser·p0.99:   12.510 ms/op
                 existUser·p0.999:  18.575 ms/op
                 existUser·p0.9999: 30.540 ms/op
                 existUser·p1.00:   32.014 ms/op

Iteration   3: 5.702 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   2.777 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.160 ms/op
                 existUser·p0.95:   8.364 ms/op
                 existUser·p0.99:   12.141 ms/op
                 existUser·p0.999:  30.996 ms/op
                 existUser·p0.9999: 33.305 ms/op
                 existUser·p1.00:   33.620 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 166583
  mean =      5.760 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 43952 
    [ 5.000,  7.500) = 107726 
    [ 7.500, 10.000) = 10471 
    [10.000, 12.500) = 2894 
    [12.500, 15.000) = 1008 
    [15.000, 17.500) = 192 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 41 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      5.407 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.716 ms/op
     p(99.0000) =     12.272 ms/op
     p(99.9000) =     24.964 ms/op
     p(99.9900) =     32.735 ms/op
     p(99.9990) =     33.511 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 20.491 ±(99.9%) 0.333 ms/op
# Warmup Iteration   2: 7.510 ±(99.9%) 0.057 ms/op
# Warmup Iteration   3: 6.050 ±(99.9%) 0.028 ms/op
Iteration   1: 6.390 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   3.117 ms/op
                 getUser·p0.50:   5.734 ms/op
                 getUser·p0.90:   9.191 ms/op
                 getUser·p0.95:   10.846 ms/op
                 getUser·p0.99:   14.347 ms/op
                 getUser·p0.999:  26.672 ms/op
                 getUser·p0.9999: 29.261 ms/op
                 getUser·p1.00:   30.048 ms/op

Iteration   2: 5.825 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   1.968 ms/op
                 getUser·p0.50:   5.505 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.389 ms/op
                 getUser·p0.99:   11.534 ms/op
                 getUser·p0.999:  28.972 ms/op
                 getUser·p0.9999: 34.377 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 6.077 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   5.628 ms/op
                 getUser·p0.90:   7.684 ms/op
                 getUser·p0.95:   9.159 ms/op
                 getUser·p0.99:   13.287 ms/op
                 getUser·p0.999:  30.186 ms/op
                 getUser·p0.9999: 33.396 ms/op
                 getUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 157480
  mean =      6.089 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 28722 
    [ 5.000,  7.500) = 109598 
    [ 7.500, 10.000) = 12709 
    [10.000, 12.500) = 4195 
    [12.500, 15.000) = 1495 
    [15.000, 17.500) = 394 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 64 
    [30.000, 32.500) = 70 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      5.612 ms/op
     p(90.0000) =      7.922 ms/op
     p(95.0000) =      9.568 ms/op
     p(99.0000) =     13.484 ms/op
     p(99.9000) =     27.787 ms/op
     p(99.9900) =     33.022 ms/op
     p(99.9990) =     34.864 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 22.619 ±(99.9%) 0.390 ms/op
# Warmup Iteration   2: 8.585 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 7.431 ±(99.9%) 0.042 ms/op
Iteration   1: 7.140 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   6.521 ms/op
                 listUser·p0.90:   9.601 ms/op
                 listUser·p0.95:   11.469 ms/op
                 listUser·p0.99:   15.188 ms/op
                 listUser·p0.999:  28.186 ms/op
                 listUser·p0.9999: 32.326 ms/op
                 listUser·p1.00:   33.391 ms/op

Iteration   2: 6.693 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.511 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   8.348 ms/op
                 listUser·p0.95:   10.322 ms/op
                 listUser·p0.99:   14.008 ms/op
                 listUser·p0.999:  28.255 ms/op
                 listUser·p0.9999: 39.337 ms/op
                 listUser·p1.00:   40.042 ms/op

Iteration   3: 6.827 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   6.365 ms/op
                 listUser·p0.90:   8.217 ms/op
                 listUser·p0.95:   10.043 ms/op
                 listUser·p0.99:   13.959 ms/op
                 listUser·p0.999:  30.507 ms/op
                 listUser·p0.9999: 36.844 ms/op
                 listUser·p1.00:   37.683 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 139353
  mean =      6.882 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2974 
    [ 5.000, 10.000) = 127226 
    [10.000, 15.000) = 8072 
    [15.000, 20.000) = 715 
    [20.000, 25.000) = 80 
    [25.000, 30.000) = 178 
    [30.000, 35.000) = 70 
    [35.000, 40.000) = 37 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      6.349 ms/op
     p(90.0000) =      8.700 ms/op
     p(95.0000) =     10.732 ms/op
     p(99.0000) =     14.483 ms/op
     p(99.9000) =     29.480 ms/op
     p(99.9900) =     37.552 ms/op
     p(99.9990) =     39.939 ms/op
     p(99.9999) =     40.042 ms/op
    p(100.0000) =     40.042 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.332 ± 4.737  ops/ms
ClientPb.existUser                       thrpt       3   5.720 ± 1.050  ops/ms
ClientPb.getUser                         thrpt       3   5.429 ± 2.207  ops/ms
ClientPb.listUser                        thrpt       3   4.567 ± 1.863  ops/ms
ClientPb.createUser                       avgt       3   6.149 ± 3.360   ms/op
ClientPb.existUser                        avgt       3   5.592 ± 2.017   ms/op
ClientPb.getUser                          avgt       3   5.735 ± 1.197   ms/op
ClientPb.listUser                         avgt       3   6.844 ± 4.268   ms/op
ClientPb.createUser                     sample  163426   5.872 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.505           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.389           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.503           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.567           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.795           ms/op
ClientPb.createUser:createUser·p0.9999  sample          45.285           ms/op
ClientPb.createUser:createUser·p1.00    sample          48.955           ms/op
ClientPb.existUser                      sample  166583   5.760 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.703           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.274           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.716           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.272           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.964           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.735           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.620           ms/op
ClientPb.getUser                        sample  157480   6.089 ± 0.016   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.968           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.612           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.922           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.568           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.484           ms/op
ClientPb.getUser:getUser·p0.999         sample          27.787           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.022           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  139353   6.882 ± 0.018   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.511           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.349           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.700           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.732           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.483           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.480           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.552           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.042           ms/op
