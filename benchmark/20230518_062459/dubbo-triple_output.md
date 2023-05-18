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
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 3.624 ops/ms
# Warmup Iteration   3: 7.162 ops/ms
Iteration   1: 7.313 ops/ms
Iteration   2: 8.191 ops/ms
Iteration   3: 7.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.702 ±(99.9%) 8.162 ops/ms [Average]
  (min, avg, max) = (7.313, 7.702, 8.191), stdev = 0.447
  CI (99.9%): [≈ 0, 15.864] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 6.514 ops/ms
# Warmup Iteration   3: 7.918 ops/ms
Iteration   1: 8.201 ops/ms
Iteration   2: 8.225 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.166 ±(99.9%) 1.508 ops/ms [Average]
  (min, avg, max) = (8.071, 8.166, 8.225), stdev = 0.083
  CI (99.9%): [6.658, 9.674] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.346 ops/ms
# Warmup Iteration   2: 6.981 ops/ms
# Warmup Iteration   3: 7.279 ops/ms
Iteration   1: 7.593 ops/ms
Iteration   2: 7.700 ops/ms
Iteration   3: 7.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.699 ±(99.9%) 1.913 ops/ms [Average]
  (min, avg, max) = (7.593, 7.699, 7.803), stdev = 0.105
  CI (99.9%): [5.785, 9.612] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.109 ops/ms
# Warmup Iteration   2: 5.745 ops/ms
# Warmup Iteration   3: 6.357 ops/ms
Iteration   1: 6.831 ops/ms
Iteration   2: 6.765 ops/ms
Iteration   3: 6.741 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.779 ±(99.9%) 0.855 ops/ms [Average]
  (min, avg, max) = (6.741, 6.779, 6.831), stdev = 0.047
  CI (99.9%): [5.924, 7.634] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 13.515 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 5.125 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.015 ms/op
Iteration   1: 4.059 ±(99.9%) 0.011 ms/op
Iteration   2: 3.924 ±(99.9%) 0.011 ms/op
Iteration   3: 3.934 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.972 ±(99.9%) 1.381 ms/op [Average]
  (min, avg, max) = (3.924, 3.972, 4.059), stdev = 0.076
  CI (99.9%): [2.591, 5.354] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 11.892 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.010 ms/op
Iteration   1: 4.048 ±(99.9%) 0.005 ms/op
Iteration   2: 4.013 ±(99.9%) 0.005 ms/op
Iteration   3: 3.689 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.917 ±(99.9%) 3.608 ms/op [Average]
  (min, avg, max) = (3.689, 3.917, 4.048), stdev = 0.198
  CI (99.9%): [0.308, 7.525] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.212 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.009 ms/op
Iteration   1: 4.258 ±(99.9%) 0.005 ms/op
Iteration   2: 3.952 ±(99.9%) 0.010 ms/op
Iteration   3: 3.790 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.000 ±(99.9%) 4.336 ms/op [Average]
  (min, avg, max) = (3.790, 4.000, 4.258), stdev = 0.238
  CI (99.9%): [≈ 0, 8.336] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.357 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.761 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.908 ±(99.9%) 0.008 ms/op
Iteration   1: 4.603 ±(99.9%) 0.016 ms/op
Iteration   2: 4.865 ±(99.9%) 0.009 ms/op
Iteration   3: 4.714 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.727 ±(99.9%) 2.401 ms/op [Average]
  (min, avg, max) = (4.603, 4.727, 4.865), stdev = 0.132
  CI (99.9%): [2.326, 7.128] (assumes normal distribution)


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
# Warmup Iteration   1: 13.091 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 5.766 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.027 ms/op
Iteration   1: 4.017 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.962 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.349 ms/op
                 createUser·p0.99:   7.414 ms/op
                 createUser·p0.999:  17.020 ms/op
                 createUser·p0.9999: 26.809 ms/op
                 createUser·p1.00:   27.656 ms/op

Iteration   2: 4.147 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.475 ms/op
                 createUser·p0.50:   3.895 ms/op
                 createUser·p0.90:   5.095 ms/op
                 createUser·p0.95:   6.054 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  25.398 ms/op
                 createUser·p0.9999: 35.080 ms/op
                 createUser·p1.00:   36.307 ms/op

Iteration   3: 4.020 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.982 ms/op
                 createUser·p0.50:   3.838 ms/op
                 createUser·p0.90:   4.571 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   7.053 ms/op
                 createUser·p0.999:  27.507 ms/op
                 createUser·p0.9999: 34.412 ms/op
                 createUser·p1.00:   35.062 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236390
  mean =      4.060 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 441 
    [ 2.500,  5.000) = 218883 
    [ 5.000,  7.500) = 14548 
    [ 7.500, 10.000) = 1731 
    [10.000, 12.500) = 433 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 52 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.497 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     24.760 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     35.765 ms/op
     p(99.9999) =     36.307 ms/op
    p(100.0000) =     36.307 ms/op


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
# Warmup Iteration   1: 11.756 ±(99.9%) 0.160 ms/op
# Warmup Iteration   2: 4.480 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.012 ms/op
Iteration   1: 3.757 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.892 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  10.155 ms/op
                 existUser·p0.9999: 24.314 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.656 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.274 ms/op
                 existUser·p0.50:   3.568 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   6.578 ms/op
                 existUser·p0.999:  22.413 ms/op
                 existUser·p0.9999: 24.158 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   3: 3.766 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.678 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.653 ms/op
                 existUser·p0.99:   7.231 ms/op
                 existUser·p0.999:  17.138 ms/op
                 existUser·p0.9999: 30.345 ms/op
                 existUser·p1.00:   31.621 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 257499
  mean =      3.726 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1227 
    [ 2.500,  5.000) = 247020 
    [ 5.000,  7.500) = 7748 
    [ 7.500, 10.000) = 992 
    [10.000, 12.500) = 123 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 137 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.678 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     16.048 ms/op
     p(99.9900) =     29.082 ms/op
     p(99.9990) =     31.142 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


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
# Warmup Iteration   1: 13.837 ±(99.9%) 0.228 ms/op
# Warmup Iteration   2: 4.836 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.209 ±(99.9%) 0.014 ms/op
Iteration   1: 3.980 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.051 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.145 ms/op
                 getUser·p0.99:   7.266 ms/op
                 getUser·p0.999:  24.827 ms/op
                 getUser·p0.9999: 27.583 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 3.951 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   6.676 ms/op
                 getUser·p0.999:  14.385 ms/op
                 getUser·p0.9999: 28.797 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 3.955 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.017 ms/op
                 getUser·p0.50:   3.826 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.382 ms/op
                 getUser·p0.999:  28.062 ms/op
                 getUser·p0.9999: 32.523 ms/op
                 getUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 242133
  mean =      3.962 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 131 
    [ 2.500,  5.000) = 230923 
    [ 5.000,  7.500) = 9559 
    [ 7.500, 10.000) = 930 
    [10.000, 12.500) = 223 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 94 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.051 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     24.788 ms/op
     p(99.9900) =     31.123 ms/op
     p(99.9990) =     32.951 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


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
# Warmup Iteration   1: 14.307 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.785 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.031 ±(99.9%) 0.020 ms/op
Iteration   1: 4.907 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.560 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   10.248 ms/op
                 listUser·p0.999:  28.148 ms/op
                 listUser·p0.9999: 32.239 ms/op
                 listUser·p1.00:   34.865 ms/op

Iteration   2: 4.833 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.966 ms/op
                 listUser·p0.50:   4.522 ms/op
                 listUser·p0.90:   5.743 ms/op
                 listUser·p0.95:   6.283 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  19.391 ms/op
                 listUser·p0.9999: 27.222 ms/op
                 listUser·p1.00:   28.672 ms/op

Iteration   3: 4.684 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.028 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.128 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   8.290 ms/op
                 listUser·p0.999:  18.735 ms/op
                 listUser·p0.9999: 24.589 ms/op
                 listUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199642
  mean =      4.807 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 154657 
    [ 5.000,  7.500) = 40497 
    [ 7.500, 10.000) = 3165 
    [10.000, 12.500) = 646 
    [12.500, 15.000) = 209 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 67 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.966 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.144 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     21.159 ms/op
     p(99.9900) =     29.917 ms/op
     p(99.9990) =     34.735 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.702 ± 8.162  ops/ms
ClientPb.existUser                       thrpt       3   8.166 ± 1.508  ops/ms
ClientPb.getUser                         thrpt       3   7.699 ± 1.913  ops/ms
ClientPb.listUser                        thrpt       3   6.779 ± 0.855  ops/ms
ClientPb.createUser                       avgt       3   3.972 ± 1.381   ms/op
ClientPb.existUser                        avgt       3   3.917 ± 3.608   ms/op
ClientPb.getUser                          avgt       3   4.000 ± 4.336   ms/op
ClientPb.listUser                         avgt       3   4.727 ± 2.401   ms/op
ClientPb.createUser                     sample  236390   4.060 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.475           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.735           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.619           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.760           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.537           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.307           ms/op
ClientPb.existUser                      sample  257499   3.726 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.678           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.633           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.112           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.644           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.048           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.082           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.621           ms/op
ClientPb.getUser                        sample  242133   3.962 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.051           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.465           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.783           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.788           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.123           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.965           ms/op
ClientPb.listUser                       sample  199642   4.807 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.966           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.547           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.159           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.917           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.865           ms/op
