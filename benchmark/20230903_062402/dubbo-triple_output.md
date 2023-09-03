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
# Warmup Iteration   1: 1.600 ops/ms
# Warmup Iteration   2: 3.850 ops/ms
# Warmup Iteration   3: 7.230 ops/ms
Iteration   1: 7.211 ops/ms
Iteration   2: 7.659 ops/ms
Iteration   3: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.525 ±(99.9%) 4.987 ops/ms [Average]
  (min, avg, max) = (7.211, 7.525, 7.705), stdev = 0.273
  CI (99.9%): [2.539, 12.512] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.281 ops/ms
# Warmup Iteration   2: 6.297 ops/ms
# Warmup Iteration   3: 8.279 ops/ms
Iteration   1: 7.925 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.197 ±(99.9%) 6.237 ops/ms [Average]
  (min, avg, max) = (7.925, 8.197, 8.581), stdev = 0.342
  CI (99.9%): [1.960, 14.434] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.097 ops/ms
# Warmup Iteration   2: 7.013 ops/ms
# Warmup Iteration   3: 7.610 ops/ms
Iteration   1: 8.033 ops/ms
Iteration   2: 8.306 ops/ms
Iteration   3: 8.063 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.134 ±(99.9%) 2.730 ops/ms [Average]
  (min, avg, max) = (8.033, 8.134, 8.306), stdev = 0.150
  CI (99.9%): [5.405, 10.864] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.146 ops/ms
# Warmup Iteration   2: 5.632 ops/ms
# Warmup Iteration   3: 6.272 ops/ms
Iteration   1: 6.932 ops/ms
Iteration   2: 6.866 ops/ms
Iteration   3: 6.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.824 ±(99.9%) 2.431 ops/ms [Average]
  (min, avg, max) = (6.675, 6.824, 6.932), stdev = 0.133
  CI (99.9%): [4.394, 9.255] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.192 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.601 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.011 ms/op
Iteration   1: 3.833 ±(99.9%) 0.005 ms/op
Iteration   2: 4.002 ±(99.9%) 0.006 ms/op
Iteration   3: 3.851 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.895 ±(99.9%) 1.689 ms/op [Average]
  (min, avg, max) = (3.833, 3.895, 4.002), stdev = 0.093
  CI (99.9%): [2.206, 5.585] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.245 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 5.036 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.007 ms/op
Iteration   1: 3.802 ±(99.9%) 0.005 ms/op
Iteration   2: 3.835 ±(99.9%) 0.003 ms/op
Iteration   3: 3.758 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.798 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.758, 3.798, 3.835), stdev = 0.038
  CI (99.9%): [3.100, 4.496] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 12.396 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.006 ms/op
Iteration   1: 4.049 ±(99.9%) 0.009 ms/op
Iteration   2: 4.268 ±(99.9%) 0.007 ms/op
Iteration   3: 4.038 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.119 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (4.038, 4.119, 4.268), stdev = 0.130
  CI (99.9%): [1.751, 6.486] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.380 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 6.071 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.179 ±(99.9%) 0.007 ms/op
Iteration   1: 4.664 ±(99.9%) 0.015 ms/op
Iteration   2: 4.625 ±(99.9%) 0.012 ms/op
Iteration   3: 4.742 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.677 ±(99.9%) 1.093 ms/op [Average]
  (min, avg, max) = (4.625, 4.677, 4.742), stdev = 0.060
  CI (99.9%): [3.585, 5.770] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.844 ±(99.9%) 0.162 ms/op
# Warmup Iteration   2: 5.113 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.021 ms/op
Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.446 ms/op
                 createUser·p0.50:   3.867 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   8.234 ms/op
                 createUser·p0.999:  24.003 ms/op
                 createUser·p0.9999: 27.263 ms/op
                 createUser·p1.00:   27.525 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.917 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  25.297 ms/op
                 createUser·p0.9999: 29.544 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 4.015 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.801 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   8.077 ms/op
                 createUser·p0.999:  20.878 ms/op
                 createUser·p0.9999: 32.216 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239592
  mean =      4.007 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 353 
    [ 2.500,  5.000) = 226637 
    [ 5.000,  7.500) = 9541 
    [ 7.500, 10.000) = 2158 
    [10.000, 12.500) = 529 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.571 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     23.947 ms/op
     p(99.9900) =     31.425 ms/op
     p(99.9990) =     33.621 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.805 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.595 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.013 ms/op
Iteration   1: 3.942 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.492 ms/op
                 existUser·p0.95:   5.079 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  24.376 ms/op
                 existUser·p0.9999: 28.049 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   2: 4.119 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.887 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.502 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 28.549 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   3: 3.971 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.374 ms/op
                 existUser·p0.50:   3.871 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   6.937 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 34.075 ms/op
                 existUser·p1.00:   34.275 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 239293
  mean =      4.009 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 264 
    [ 2.500,  5.000) = 222186 
    [ 5.000,  7.500) = 14365 
    [ 7.500, 10.000) = 1816 
    [10.000, 12.500) = 340 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 57 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 35 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.374 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     13.711 ms/op
     p(99.9900) =     33.000 ms/op
     p(99.9990) =     34.275 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.625 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.779 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.014 ms/op
Iteration   1: 4.057 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.442 ms/op
                 getUser·p0.50:   3.846 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   5.816 ms/op
                 getUser·p0.99:   8.061 ms/op
                 getUser·p0.999:  23.560 ms/op
                 getUser·p0.9999: 29.222 ms/op
                 getUser·p1.00:   30.114 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.673 ms/op
                 getUser·p0.50:   3.867 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   7.258 ms/op
                 getUser·p0.999:  20.152 ms/op
                 getUser·p0.9999: 30.935 ms/op
                 getUser·p1.00:   31.654 ms/op

Iteration   3: 3.923 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   7.201 ms/op
                 getUser·p0.999:  26.243 ms/op
                 getUser·p0.9999: 29.491 ms/op
                 getUser·p1.00:   30.114 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 240115
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 54 
    [ 2.500,  5.000) = 228555 
    [ 5.000,  7.500) = 8992 
    [ 7.500, 10.000) = 1619 
    [10.000, 12.500) = 504 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 92 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.442 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.569 ms/op
     p(99.9000) =     23.520 ms/op
     p(99.9900) =     29.720 ms/op
     p(99.9990) =     31.293 ms/op
     p(99.9999) =     31.654 ms/op
    p(100.0000) =     31.654 ms/op


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
# Warmup Iteration   1: 15.282 ±(99.9%) 0.233 ms/op
# Warmup Iteration   2: 5.250 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.322 ±(99.9%) 0.023 ms/op
Iteration   1: 4.755 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.017 ms/op
                 listUser·p0.50:   4.514 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   9.372 ms/op
                 listUser·p0.999:  26.405 ms/op
                 listUser·p0.9999: 34.724 ms/op
                 listUser·p1.00:   36.438 ms/op

Iteration   2: 5.038 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   4.833 ms/op
                 listUser·p0.90:   5.489 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  18.298 ms/op
                 listUser·p0.9999: 23.134 ms/op
                 listUser·p1.00:   29.983 ms/op

Iteration   3: 4.884 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   2.429 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.644 ms/op
                 listUser·p0.95:   6.463 ms/op
                 listUser·p0.99:   9.899 ms/op
                 listUser·p0.999:  17.041 ms/op
                 listUser·p0.9999: 19.610 ms/op
                 listUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196271
  mean =      4.890 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 147277 
    [ 5.000,  7.500) = 42784 
    [ 7.500, 10.000) = 4435 
    [10.000, 12.500) = 908 
    [12.500, 15.000) = 383 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.017 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.497 ms/op
     p(95.0000) =      6.357 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     20.742 ms/op
     p(99.9900) =     32.891 ms/op
     p(99.9990) =     35.176 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.525 ± 4.987  ops/ms
ClientPb.existUser                       thrpt       3   8.197 ± 6.237  ops/ms
ClientPb.getUser                         thrpt       3   8.134 ± 2.730  ops/ms
ClientPb.listUser                        thrpt       3   6.824 ± 2.431  ops/ms
ClientPb.createUser                       avgt       3   3.895 ± 1.689   ms/op
ClientPb.existUser                        avgt       3   3.798 ± 0.698   ms/op
ClientPb.getUser                          avgt       3   4.119 ± 2.368   ms/op
ClientPb.listUser                         avgt       3   4.677 ± 1.093   ms/op
ClientPb.createUser                     sample  239592   4.007 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.446           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.809           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.571           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.054           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.930           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.947           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.425           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  239293   4.009 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.374           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.854           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.300           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.545           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.711           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.000           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.275           ms/op
ClientPb.getUser                        sample  240115   3.995 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.442           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.842           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.456           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.948           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.569           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.520           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.720           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.654           ms/op
ClientPb.listUser                       sample  196271   4.890 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.017           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.357           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.716           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.742           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.891           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.438           ms/op
