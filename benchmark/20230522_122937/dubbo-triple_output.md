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
# Warmup Iteration   1: 1.649 ops/ms
# Warmup Iteration   2: 3.611 ops/ms
# Warmup Iteration   3: 7.156 ops/ms
Iteration   1: 7.649 ops/ms
Iteration   2: 8.392 ops/ms
Iteration   3: 8.290 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.110 ±(99.9%) 7.347 ops/ms [Average]
  (min, avg, max) = (7.649, 8.110, 8.392), stdev = 0.403
  CI (99.9%): [0.764, 15.457] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.236 ops/ms
# Warmup Iteration   2: 7.046 ops/ms
# Warmup Iteration   3: 8.561 ops/ms
Iteration   1: 8.787 ops/ms
Iteration   2: 8.788 ops/ms
Iteration   3: 8.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.857 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (8.787, 8.857, 8.995), stdev = 0.120
  CI (99.9%): [6.672, 11.041] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.484 ops/ms
# Warmup Iteration   2: 7.395 ops/ms
# Warmup Iteration   3: 8.095 ops/ms
Iteration   1: 8.263 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.420 ±(99.9%) 4.208 ops/ms [Average]
  (min, avg, max) = (8.263, 8.420, 8.685), stdev = 0.231
  CI (99.9%): [4.212, 12.628] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.229 ops/ms
# Warmup Iteration   2: 5.724 ops/ms
# Warmup Iteration   3: 7.293 ops/ms
Iteration   1: 7.225 ops/ms
Iteration   2: 7.144 ops/ms
Iteration   3: 7.024 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.131 ±(99.9%) 1.847 ops/ms [Average]
  (min, avg, max) = (7.024, 7.131, 7.225), stdev = 0.101
  CI (99.9%): [5.284, 8.978] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.557 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.806 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.005 ms/op
Iteration   1: 3.799 ±(99.9%) 0.007 ms/op
Iteration   2: 3.861 ±(99.9%) 0.011 ms/op
Iteration   3: 3.895 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.852 ±(99.9%) 0.880 ms/op [Average]
  (min, avg, max) = (3.799, 3.852, 3.895), stdev = 0.048
  CI (99.9%): [2.971, 4.732] (assumes normal distribution)


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
# Warmup Iteration   1: 11.958 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.783 ±(99.9%) 0.004 ms/op
Iteration   1: 3.701 ±(99.9%) 0.006 ms/op
Iteration   2: 3.703 ±(99.9%) 0.009 ms/op
Iteration   3: 3.549 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.651 ±(99.9%) 1.618 ms/op [Average]
  (min, avg, max) = (3.549, 3.651, 3.703), stdev = 0.089
  CI (99.9%): [2.034, 5.269] (assumes normal distribution)


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
# Warmup Iteration   1: 11.850 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.903 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.049 ±(99.9%) 0.006 ms/op
Iteration   1: 3.650 ±(99.9%) 0.008 ms/op
Iteration   2: 3.724 ±(99.9%) 0.008 ms/op
Iteration   3: 3.669 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.681 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.650, 3.681, 3.724), stdev = 0.038
  CI (99.9%): [2.980, 4.382] (assumes normal distribution)


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
# Warmup Iteration   1: 12.545 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.146 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.694 ±(99.9%) 0.008 ms/op
Iteration   1: 4.594 ±(99.9%) 0.016 ms/op
Iteration   2: 4.670 ±(99.9%) 0.009 ms/op
Iteration   3: 4.328 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.531 ±(99.9%) 3.274 ms/op [Average]
  (min, avg, max) = (4.328, 4.531, 4.670), stdev = 0.179
  CI (99.9%): [1.257, 7.804] (assumes normal distribution)


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
# Warmup Iteration   1: 10.659 ±(99.9%) 0.153 ms/op
# Warmup Iteration   2: 4.768 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.019 ms/op
Iteration   1: 3.931 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.526 ms/op
                 createUser·p0.50:   3.715 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.907 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  20.490 ms/op
                 createUser·p0.9999: 23.711 ms/op
                 createUser·p1.00:   24.478 ms/op

Iteration   2: 3.842 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.896 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   6.783 ms/op
                 createUser·p0.999:  10.500 ms/op
                 createUser·p0.9999: 25.887 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.834 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.839 ms/op
                 createUser·p0.50:   3.658 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  24.561 ms/op
                 createUser·p0.9999: 28.594 ms/op
                 createUser·p1.00:   29.360 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 248080
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 605 
    [ 2.500,  5.000) = 237875 
    [ 5.000,  7.500) = 7453 
    [ 7.500, 10.000) = 1474 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 95 
    [25.000, 27.500) = 75 

  Percentiles, ms/op:
      p(0.0000) =      1.526 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     19.855 ms/op
     p(99.9900) =     27.249 ms/op
     p(99.9990) =     29.068 ms/op
     p(99.9999) =     29.360 ms/op
    p(100.0000) =     29.360 ms/op


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
# Warmup Iteration   1: 11.012 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 4.126 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.013 ms/op
Iteration   1: 3.810 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.882 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.825 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 41.550 ms/op
                 existUser·p1.00:   41.746 ms/op

Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.692 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.604 ms/op
                 existUser·p0.95:   5.177 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  19.800 ms/op
                 existUser·p0.9999: 25.413 ms/op
                 existUser·p1.00:   26.542 ms/op

Iteration   3: 3.920 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.774 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.710 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  24.365 ms/op
                 existUser·p0.9999: 29.257 ms/op
                 existUser·p1.00:   29.852 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246123
  mean =      3.894 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 233239 
    [ 5.000, 10.000) = 12360 
    [10.000, 15.000) = 224 
    [15.000, 20.000) = 58 
    [20.000, 25.000) = 127 
    [25.000, 30.000) = 83 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.692 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     19.919 ms/op
     p(99.9900) =     39.911 ms/op
     p(99.9990) =     41.746 ms/op
     p(99.9999) =     41.746 ms/op
    p(100.0000) =     41.746 ms/op


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
# Warmup Iteration   1: 10.972 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.051 ±(99.9%) 0.015 ms/op
Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.066 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   8.487 ms/op
                 getUser·p0.999:  17.879 ms/op
                 getUser·p0.9999: 26.115 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 3.892 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.236 ms/op
                 getUser·p0.50:   3.781 ms/op
                 getUser·p0.90:   4.327 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  25.166 ms/op
                 getUser·p0.9999: 27.394 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.513 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.243 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   7.111 ms/op
                 getUser·p0.999:  13.030 ms/op
                 getUser·p0.9999: 32.931 ms/op
                 getUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 245095
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 235270 
    [ 5.000,  7.500) = 6781 
    [ 7.500, 10.000) = 2094 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 122 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.513 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.832 ms/op
     p(99.9000) =     17.426 ms/op
     p(99.9900) =     31.095 ms/op
     p(99.9990) =     33.961 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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
# Warmup Iteration   1: 13.587 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.161 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.745 ±(99.9%) 0.019 ms/op
Iteration   1: 4.622 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.046 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.079 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  25.903 ms/op
                 listUser·p0.9999: 34.215 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 4.497 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   4.399 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.267 ms/op
                 listUser·p0.99:   8.069 ms/op
                 listUser·p0.999:  17.760 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.642 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.642 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 26.509 ms/op
                 listUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 209352
  mean =      4.586 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 187664 
    [ 5.000,  7.500) = 17072 
    [ 7.500, 10.000) = 3789 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 112 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.046 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     19.190 ms/op
     p(99.9900) =     32.606 ms/op
     p(99.9990) =     35.062 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.110 ± 7.347  ops/ms
ClientPb.existUser                       thrpt       3   8.857 ± 2.184  ops/ms
ClientPb.getUser                         thrpt       3   8.420 ± 4.208  ops/ms
ClientPb.listUser                        thrpt       3   7.131 ± 1.847  ops/ms
ClientPb.createUser                       avgt       3   3.852 ± 0.880   ms/op
ClientPb.existUser                        avgt       3   3.651 ± 1.618   ms/op
ClientPb.getUser                          avgt       3   3.681 ± 0.701   ms/op
ClientPb.listUser                         avgt       3   4.531 ± 3.274   ms/op
ClientPb.createUser                     sample  248080   3.868 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.526           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.703           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.415           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.111           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.855           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.249           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.360           ms/op
ClientPb.existUser                      sample  246123   3.894 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.692           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.744           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.522           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.038           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.919           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.911           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.746           ms/op
ClientPb.getUser                        sample  245095   3.916 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.513           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.748           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.832           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.426           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.095           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.210           ms/op
ClientPb.listUser                       sample  209352   4.586 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.046           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.464           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.602           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.190           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.606           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.127           ms/op
