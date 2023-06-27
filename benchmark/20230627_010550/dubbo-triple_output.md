# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.629 ops/ms
# Warmup Iteration   2: 3.877 ops/ms
# Warmup Iteration   3: 7.146 ops/ms
Iteration   1: 7.505 ops/ms
Iteration   2: 8.006 ops/ms
Iteration   3: 7.817 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.776 ±(99.9%) 4.611 ops/ms [Average]
  (min, avg, max) = (7.505, 7.776, 8.006), stdev = 0.253
  CI (99.9%): [3.165, 12.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.140 ops/ms
# Warmup Iteration   2: 6.738 ops/ms
# Warmup Iteration   3: 7.933 ops/ms
Iteration   1: 8.081 ops/ms
Iteration   2: 8.382 ops/ms
Iteration   3: 8.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.205 ±(99.9%) 2.863 ops/ms [Average]
  (min, avg, max) = (8.081, 8.205, 8.382), stdev = 0.157
  CI (99.9%): [5.342, 11.068] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.299 ops/ms
# Warmup Iteration   2: 6.064 ops/ms
# Warmup Iteration   3: 7.861 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.258 ops/ms
Iteration   3: 8.002 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.096 ±(99.9%) 2.570 ops/ms [Average]
  (min, avg, max) = (8.002, 8.096, 8.258), stdev = 0.141
  CI (99.9%): [5.526, 10.666] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.084 ops/ms
# Warmup Iteration   2: 5.661 ops/ms
# Warmup Iteration   3: 6.743 ops/ms
Iteration   1: 6.773 ops/ms
Iteration   2: 6.557 ops/ms
Iteration   3: 7.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.802 ±(99.9%) 4.770 ops/ms [Average]
  (min, avg, max) = (6.557, 6.802, 7.077), stdev = 0.261
  CI (99.9%): [2.033, 11.572] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 13.464 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.966 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.233 ±(99.9%) 0.004 ms/op
Iteration   1: 3.843 ±(99.9%) 0.013 ms/op
Iteration   2: 4.001 ±(99.9%) 0.011 ms/op
Iteration   3: 4.198 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.014 ±(99.9%) 3.245 ms/op [Average]
  (min, avg, max) = (3.843, 4.014, 4.198), stdev = 0.178
  CI (99.9%): [0.769, 7.259] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 11.713 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.011 ±(99.9%) 0.004 ms/op
Iteration   1: 3.923 ±(99.9%) 0.011 ms/op
Iteration   2: 4.014 ±(99.9%) 0.007 ms/op
Iteration   3: 3.930 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.955 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (3.923, 3.955, 4.014), stdev = 0.051
  CI (99.9%): [3.031, 4.879] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 11.902 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.302 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.238 ±(99.9%) 0.008 ms/op
Iteration   1: 3.939 ±(99.9%) 0.006 ms/op
Iteration   2: 3.958 ±(99.9%) 0.006 ms/op
Iteration   3: 4.129 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.009 ±(99.9%) 1.914 ms/op [Average]
  (min, avg, max) = (3.939, 4.009, 4.129), stdev = 0.105
  CI (99.9%): [2.095, 5.923] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 14.044 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.493 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.008 ms/op
Iteration   1: 4.651 ±(99.9%) 0.014 ms/op
Iteration   2: 4.675 ±(99.9%) 0.010 ms/op
Iteration   3: 4.751 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.692 ±(99.9%) 0.949 ms/op [Average]
  (min, avg, max) = (4.651, 4.692, 4.751), stdev = 0.052
  CI (99.9%): [3.743, 5.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.174 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.818 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.439 ±(99.9%) 0.018 ms/op
Iteration   1: 4.074 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.587 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   4.702 ms/op
                 createUser·p0.95:   5.300 ms/op
                 createUser·p0.99:   8.290 ms/op
                 createUser·p0.999:  24.612 ms/op
                 createUser·p0.9999: 33.630 ms/op
                 createUser·p1.00:   34.210 ms/op

Iteration   2: 3.859 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   2.066 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  12.458 ms/op
                 createUser·p0.9999: 27.876 ms/op
                 createUser·p1.00:   28.738 ms/op

Iteration   3: 3.842 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   2.021 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.716 ms/op
                 createUser·p0.999:  29.629 ms/op
                 createUser·p0.9999: 32.058 ms/op
                 createUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 244663
  mean =      3.922 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 127 
    [ 2.500,  5.000) = 235609 
    [ 5.000,  7.500) = 6828 
    [ 7.500, 10.000) = 1426 
    [10.000, 12.500) = 315 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 55 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 93 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.587 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.784 ms/op
     p(99.0000) =      7.122 ms/op
     p(99.9000) =     23.975 ms/op
     p(99.9900) =     32.065 ms/op
     p(99.9990) =     35.780 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 10.618 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.234 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.012 ms/op
Iteration   1: 3.831 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.736 ms/op
                 existUser·p0.90:   4.252 ms/op
                 existUser·p0.95:   4.768 ms/op
                 existUser·p0.99:   6.721 ms/op
                 existUser·p0.999:  23.757 ms/op
                 existUser·p0.9999: 26.015 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   2: 3.791 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.662 ms/op
                 existUser·p0.90:   4.145 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   7.160 ms/op
                 existUser·p0.999:  14.879 ms/op
                 existUser·p0.9999: 26.907 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.872 ms/op
                 existUser·p0.50:   3.723 ms/op
                 existUser·p0.90:   4.186 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   6.701 ms/op
                 existUser·p0.999:  27.685 ms/op
                 existUser·p0.9999: 30.579 ms/op
                 existUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 251875
  mean =      3.809 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 339 
    [ 2.500,  5.000) = 242344 
    [ 5.000,  7.500) = 7700 
    [ 7.500, 10.000) = 747 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.194 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     23.212 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     31.440 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.818 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 5.046 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.213 ±(99.9%) 0.013 ms/op
Iteration   1: 4.260 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.942 ms/op
                 getUser·p0.50:   4.002 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  21.658 ms/op
                 getUser·p0.9999: 23.806 ms/op
                 getUser·p1.00:   24.019 ms/op

Iteration   2: 4.159 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   3.977 ms/op
                 getUser·p0.90:   4.792 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.662 ms/op
                 getUser·p0.999:  17.367 ms/op
                 getUser·p0.9999: 26.804 ms/op
                 getUser·p1.00:   27.230 ms/op

Iteration   3: 4.053 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.038 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  19.825 ms/op
                 getUser·p0.9999: 27.857 ms/op
                 getUser·p1.00:   28.672 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230722
  mean =      4.156 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 92 
    [ 2.500,  5.000) = 212540 
    [ 5.000,  7.500) = 15270 
    [ 7.500, 10.000) = 1893 
    [10.000, 12.500) = 531 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.317 ms/op
     p(50.0000) =      3.985 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.431 ms/op
     p(99.0000) =      7.971 ms/op
     p(99.9000) =     21.079 ms/op
     p(99.9900) =     27.228 ms/op
     p(99.9990) =     28.128 ms/op
     p(99.9999) =     28.672 ms/op
    p(100.0000) =     28.672 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 15.272 ±(99.9%) 0.201 ms/op
# Warmup Iteration   2: 6.400 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.840 ±(99.9%) 0.017 ms/op
Iteration   1: 4.941 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.808 ms/op
                 listUser·p0.95:   7.594 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  26.608 ms/op
                 listUser·p0.9999: 29.093 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   2: 4.691 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   8.782 ms/op
                 listUser·p0.999:  18.737 ms/op
                 listUser·p0.9999: 23.932 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 4.848 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.931 ms/op
                 listUser·p0.50:   4.669 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.125 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  18.316 ms/op
                 listUser·p0.9999: 23.377 ms/op
                 listUser·p1.00:   24.117 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198891
  mean =      4.825 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 165548 
    [ 5.000,  7.500) = 25698 
    [ 7.500, 10.000) = 6037 
    [10.000, 12.500) = 880 
    [12.500, 15.000) = 194 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.765 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.513 ms/op
     p(99.0000) =      9.404 ms/op
     p(99.9000) =     22.777 ms/op
     p(99.9900) =     27.907 ms/op
     p(99.9990) =     30.148 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.776 ± 4.611  ops/ms
ClientPb.existUser                       thrpt       3   8.205 ± 2.863  ops/ms
ClientPb.getUser                         thrpt       3   8.096 ± 2.570  ops/ms
ClientPb.listUser                        thrpt       3   6.802 ± 4.770  ops/ms
ClientPb.createUser                       avgt       3   4.014 ± 3.245   ms/op
ClientPb.existUser                        avgt       3   3.955 ± 0.924   ms/op
ClientPb.getUser                          avgt       3   4.009 ± 1.914   ms/op
ClientPb.listUser                         avgt       3   4.692 ± 0.949   ms/op
ClientPb.createUser                     sample  244663   3.922 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.587           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.383           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.784           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.122           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.975           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.065           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.438           ms/op
ClientPb.existUser                      sample  251875   3.809 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.711           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.194           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.669           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.791           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.212           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.557           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.211           ms/op
ClientPb.getUser                        sample  230722   4.156 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.317           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.985           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.841           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.431           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.971           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.079           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.228           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.672           ms/op
ClientPb.listUser                       sample  198891   4.825 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.765           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.349           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.513           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.907           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.278           ms/op
