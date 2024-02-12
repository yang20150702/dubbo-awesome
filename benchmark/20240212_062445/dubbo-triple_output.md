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
# Warmup Iteration   1: 5.243 ops/ms
# Warmup Iteration   2: 12.198 ops/ms
# Warmup Iteration   3: 12.486 ops/ms
Iteration   1: 12.602 ops/ms
Iteration   2: 12.746 ops/ms
Iteration   3: 12.778 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.708 ±(99.9%) 1.711 ops/ms [Average]
  (min, avg, max) = (12.602, 12.708, 12.778), stdev = 0.094
  CI (99.9%): [10.997, 14.420] (assumes normal distribution)


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
# Warmup Iteration   1: 8.550 ops/ms
# Warmup Iteration   2: 13.129 ops/ms
# Warmup Iteration   3: 13.159 ops/ms
Iteration   1: 13.218 ops/ms
Iteration   2: 13.305 ops/ms
Iteration   3: 13.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.257 ±(99.9%) 0.813 ops/ms [Average]
  (min, avg, max) = (13.218, 13.257, 13.305), stdev = 0.045
  CI (99.9%): [12.444, 14.069] (assumes normal distribution)


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
# Warmup Iteration   1: 7.635 ops/ms
# Warmup Iteration   2: 12.377 ops/ms
# Warmup Iteration   3: 12.899 ops/ms
Iteration   1: 12.803 ops/ms
Iteration   2: 12.882 ops/ms
Iteration   3: 12.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.841 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (12.803, 12.841, 12.882), stdev = 0.040
  CI (99.9%): [12.119, 13.563] (assumes normal distribution)


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
# Warmup Iteration   1: 6.865 ops/ms
# Warmup Iteration   2: 10.522 ops/ms
# Warmup Iteration   3: 10.660 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.693 ±(99.9%) 0.648 ops/ms [Average]
  (min, avg, max) = (10.664, 10.693, 10.733), stdev = 0.036
  CI (99.9%): [10.044, 11.341] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.500 ±(99.9%) 0.004 ms/op
Iteration   2: 2.509 ±(99.9%) 0.004 ms/op
Iteration   3: 2.533 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.514 ±(99.9%) 0.305 ms/op [Average]
  (min, avg, max) = (2.500, 2.514, 2.533), stdev = 0.017
  CI (99.9%): [2.210, 2.819] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.704 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.462 ±(99.9%) 0.003 ms/op
Iteration   3: 2.477 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.471 ±(99.9%) 0.144 ms/op [Average]
  (min, avg, max) = (2.462, 2.471, 2.477), stdev = 0.008
  CI (99.9%): [2.327, 2.615] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.543 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.003 ms/op
Iteration   1: 2.487 ±(99.9%) 0.004 ms/op
Iteration   2: 2.483 ±(99.9%) 0.004 ms/op
Iteration   3: 2.498 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.490 ±(99.9%) 0.136 ms/op [Average]
  (min, avg, max) = (2.483, 2.490, 2.498), stdev = 0.007
  CI (99.9%): [2.354, 2.625] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.492 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.005 ms/op
Iteration   1: 2.965 ±(99.9%) 0.006 ms/op
Iteration   2: 2.981 ±(99.9%) 0.005 ms/op
Iteration   3: 2.959 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.968 ±(99.9%) 0.208 ms/op [Average]
  (min, avg, max) = (2.959, 2.968, 2.981), stdev = 0.011
  CI (99.9%): [2.761, 3.176] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.470 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.547 ±(99.9%) 0.006 ms/op
Iteration   1: 2.550 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.622 ms/op
                 createUser·p0.50:   2.580 ms/op
                 createUser·p0.90:   3.101 ms/op
                 createUser·p0.95:   3.219 ms/op
                 createUser·p0.99:   3.834 ms/op
                 createUser·p0.999:  11.953 ms/op
                 createUser·p0.9999: 13.910 ms/op
                 createUser·p1.00:   14.254 ms/op

Iteration   2: 2.530 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.597 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.584 ms/op
                 createUser·p0.999:  9.683 ms/op
                 createUser·p0.9999: 12.105 ms/op
                 createUser·p1.00:   12.452 ms/op

Iteration   3: 2.560 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.019 ms/op
                 createUser·p0.50:   2.630 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.215 ms/op
                 createUser·p0.99:   3.811 ms/op
                 createUser·p0.999:  8.263 ms/op
                 createUser·p0.9999: 12.897 ms/op
                 createUser·p1.00:   13.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376633
  mean =      2.547 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 181765 
    [ 2.500,  3.750) = 191122 
    [ 3.750,  5.000) = 2963 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 12 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 91 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.092 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.744 ms/op
     p(99.9000) =      8.640 ms/op
     p(99.9900) =     13.615 ms/op
     p(99.9990) =     14.008 ms/op
     p(99.9999) =     14.254 ms/op
    p(100.0000) =     14.254 ms/op


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
# Warmup Iteration   1: 3.751 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.005 ms/op
Iteration   1: 2.496 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.019 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.129 ms/op
                 existUser·p0.99:   3.572 ms/op
                 existUser·p0.999:  5.094 ms/op
                 existUser·p0.9999: 14.708 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 2.502 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.914 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   3.052 ms/op
                 existUser·p0.95:   3.158 ms/op
                 existUser·p0.99:   3.596 ms/op
                 existUser·p0.999:  8.917 ms/op
                 existUser·p0.9999: 13.009 ms/op
                 existUser·p1.00:   13.222 ms/op

Iteration   3: 2.520 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.851 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.060 ms/op
                 existUser·p0.95:   3.199 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.733 ms/op
                 existUser·p0.9999: 13.800 ms/op
                 existUser·p1.00:   14.352 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 382741
  mean =      2.506 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 185258 
    [ 2.500,  3.750) = 193739 
    [ 3.750,  5.000) = 3064 
    [ 5.000,  6.250) = 267 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      2.580 ms/op
     p(90.0000) =      3.043 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.727 ms/op
     p(99.9000) =      5.833 ms/op
     p(99.9900) =     13.676 ms/op
     p(99.9990) =     15.412 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


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
# Warmup Iteration   1: 3.888 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.601 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.565 ±(99.9%) 0.006 ms/op
Iteration   1: 2.516 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.515 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.781 ms/op
                 getUser·p0.999:  11.892 ms/op
                 getUser·p0.9999: 14.111 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.990 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.052 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   14.909 ms/op

Iteration   3: 2.529 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.987 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.084 ms/op
                 getUser·p0.95:   3.224 ms/op
                 getUser·p0.99:   3.933 ms/op
                 getUser·p0.999:  8.708 ms/op
                 getUser·p0.9999: 10.574 ms/op
                 getUser·p1.00:   11.502 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380067
  mean =      2.523 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 56 
    [ 1.250,  2.500) = 187475 
    [ 2.500,  3.750) = 187494 
    [ 3.750,  5.000) = 4035 
    [ 5.000,  6.250) = 589 
    [ 6.250,  7.500) = 33 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 77 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 6 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.898 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.068 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     13.631 ms/op
     p(99.9990) =     15.306 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 2.985 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   5.669 ms/op
                 listUser·p0.999:  9.028 ms/op
                 listUser·p0.9999: 11.249 ms/op
                 listUser·p1.00:   12.632 ms/op

Iteration   2: 2.945 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.938 ms/op
                 listUser·p0.50:   2.888 ms/op
                 listUser·p0.90:   3.760 ms/op
                 listUser·p0.95:   4.211 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.142 ms/op
                 listUser·p0.9999: 12.087 ms/op
                 listUser·p1.00:   12.730 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.858 ms/op
                 listUser·p0.95:   4.317 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.449 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323000
  mean =      2.970 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 144 
    [ 1.250,  2.500) = 99482 
    [ 2.500,  3.750) = 187043 
    [ 3.750,  5.000) = 29585 
    [ 5.000,  6.250) = 5387 
    [ 6.250,  7.500) = 662 
    [ 7.500,  8.750) = 270 
    [ 8.750, 10.000) = 261 
    [10.000, 11.250) = 137 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =      9.191 ms/op
     p(99.9900) =     11.185 ms/op
     p(99.9990) =     12.632 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.708 ± 1.711  ops/ms
ClientPb.existUser                       thrpt       3  13.257 ± 0.813  ops/ms
ClientPb.getUser                         thrpt       3  12.841 ± 0.722  ops/ms
ClientPb.listUser                        thrpt       3  10.693 ± 0.648  ops/ms
ClientPb.createUser                       avgt       3   2.514 ± 0.305   ms/op
ClientPb.existUser                        avgt       3   2.471 ± 0.144   ms/op
ClientPb.getUser                          avgt       3   2.490 ± 0.136   ms/op
ClientPb.listUser                         avgt       3   2.968 ± 0.208   ms/op
ClientPb.createUser                     sample  376633   2.547 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.622           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.092           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.744           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.640           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.615           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.254           ms/op
ClientPb.existUser                      sample  382741   2.506 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.851           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.580           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.833           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.676           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.532           ms/op
ClientPb.getUser                        sample  380067   2.523 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.535           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.068           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.195           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.765           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.631           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.434           ms/op
ClientPb.listUser                       sample  323000   2.970 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.857           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.530           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.191           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.185           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.730           ms/op
