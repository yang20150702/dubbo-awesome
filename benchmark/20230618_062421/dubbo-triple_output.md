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
# Warmup Iteration   1: 1.471 ops/ms
# Warmup Iteration   2: 3.417 ops/ms
# Warmup Iteration   3: 6.811 ops/ms
Iteration   1: 7.229 ops/ms
Iteration   2: 7.514 ops/ms
Iteration   3: 7.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.462 ±(99.9%) 3.858 ops/ms [Average]
  (min, avg, max) = (7.229, 7.462, 7.642), stdev = 0.211
  CI (99.9%): [3.604, 11.320] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 6.099 ops/ms
# Warmup Iteration   3: 7.936 ops/ms
Iteration   1: 7.804 ops/ms
Iteration   2: 8.079 ops/ms
Iteration   3: 8.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.989 ±(99.9%) 2.925 ops/ms [Average]
  (min, avg, max) = (7.804, 7.989, 8.084), stdev = 0.160
  CI (99.9%): [5.065, 10.914] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.150 ops/ms
# Warmup Iteration   2: 5.838 ops/ms
# Warmup Iteration   3: 7.442 ops/ms
Iteration   1: 7.252 ops/ms
Iteration   2: 7.594 ops/ms
Iteration   3: 7.501 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.449 ±(99.9%) 3.219 ops/ms [Average]
  (min, avg, max) = (7.252, 7.449, 7.594), stdev = 0.176
  CI (99.9%): [4.230, 10.669] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.994 ops/ms
# Warmup Iteration   2: 5.218 ops/ms
# Warmup Iteration   3: 6.285 ops/ms
Iteration   1: 6.389 ops/ms
Iteration   2: 6.581 ops/ms
Iteration   3: 6.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.470 ±(99.9%) 1.817 ops/ms [Average]
  (min, avg, max) = (6.389, 6.470, 6.581), stdev = 0.100
  CI (99.9%): [4.654, 8.287] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.189 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.948 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.445 ±(99.9%) 0.011 ms/op
Iteration   1: 4.269 ±(99.9%) 0.006 ms/op
Iteration   2: 4.156 ±(99.9%) 0.007 ms/op
Iteration   3: 4.136 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.187 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (4.136, 4.187, 4.269), stdev = 0.072
  CI (99.9%): [2.880, 5.494] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 13.151 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.535 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.007 ms/op
Iteration   1: 4.018 ±(99.9%) 0.007 ms/op
Iteration   2: 4.014 ±(99.9%) 0.007 ms/op
Iteration   3: 4.013 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.015 ±(99.9%) 0.046 ms/op [Average]
  (min, avg, max) = (4.013, 4.015, 4.018), stdev = 0.003
  CI (99.9%): [3.969, 4.061] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.646 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.334 ±(99.9%) 0.005 ms/op
Iteration   1: 4.295 ±(99.9%) 0.007 ms/op
Iteration   2: 4.069 ±(99.9%) 0.006 ms/op
Iteration   3: 4.243 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.202 ±(99.9%) 2.159 ms/op [Average]
  (min, avg, max) = (4.069, 4.202, 4.295), stdev = 0.118
  CI (99.9%): [2.043, 6.362] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.494 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.951 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.012 ms/op
Iteration   1: 4.813 ±(99.9%) 0.010 ms/op
Iteration   2: 4.765 ±(99.9%) 0.009 ms/op
Iteration   3: 4.940 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.839 ±(99.9%) 1.651 ms/op [Average]
  (min, avg, max) = (4.765, 4.839, 4.940), stdev = 0.091
  CI (99.9%): [3.188, 6.491] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.608 ±(99.9%) 0.231 ms/op
# Warmup Iteration   2: 5.438 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.462 ±(99.9%) 0.016 ms/op
Iteration   1: 4.084 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   3.965 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.367 ms/op
                 createUser·p0.99:   7.537 ms/op
                 createUser·p0.999:  21.208 ms/op
                 createUser·p0.9999: 25.723 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   2: 4.099 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.950 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.760 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   6.843 ms/op
                 createUser·p0.999:  11.239 ms/op
                 createUser·p0.9999: 42.349 ms/op
                 createUser·p1.00:   45.416 ms/op

Iteration   3: 4.102 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.167 ms/op
                 createUser·p0.999:  25.037 ms/op
                 createUser·p0.9999: 31.890 ms/op
                 createUser·p1.00:   33.817 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234302
  mean =      4.095 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 218616 
    [ 5.000, 10.000) = 15094 
    [10.000, 15.000) = 302 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 148 
    [25.000, 30.000) = 74 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 4 
    [40.000, 45.000) = 27 

  Percentiles, ms/op:
      p(0.0000) =      1.075 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.267 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     21.814 ms/op
     p(99.9900) =     40.670 ms/op
     p(99.9990) =     43.340 ms/op
     p(99.9999) =     45.416 ms/op
    p(100.0000) =     45.416 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 11.490 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.015 ms/op
Iteration   1: 3.848 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.255 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.030 ms/op
                 existUser·p0.95:   4.252 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  23.720 ms/op
                 existUser·p0.9999: 26.469 ms/op
                 existUser·p1.00:   27.853 ms/op

Iteration   2: 3.950 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.013 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   5.143 ms/op
                 existUser·p0.99:   7.726 ms/op
                 existUser·p0.999:  13.464 ms/op
                 existUser·p0.9999: 27.951 ms/op
                 existUser·p1.00:   29.032 ms/op

Iteration   3: 4.098 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.972 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   8.069 ms/op
                 existUser·p0.999:  17.367 ms/op
                 existUser·p0.9999: 33.037 ms/op
                 existUser·p1.00:   34.996 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242048
  mean =      3.963 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 226 
    [ 2.500,  5.000) = 229591 
    [ 5.000,  7.500) = 9943 
    [ 7.500, 10.000) = 1466 
    [10.000, 12.500) = 393 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.255 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     31.647 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     34.996 ms/op
    p(100.0000) =     34.996 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 13.565 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.786 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.356 ±(99.9%) 0.017 ms/op
Iteration   1: 4.162 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.281 ms/op
                 getUser·p0.50:   3.949 ms/op
                 getUser·p0.90:   4.801 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   8.536 ms/op
                 getUser·p0.999:  15.794 ms/op
                 getUser·p0.9999: 25.395 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 4.146 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.550 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.691 ms/op
                 getUser·p0.999:  25.650 ms/op
                 getUser·p0.9999: 29.360 ms/op
                 getUser·p1.00:   29.819 ms/op

Iteration   3: 4.066 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.167 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.669 ms/op
                 getUser·p0.95:   5.317 ms/op
                 getUser·p0.99:   7.504 ms/op
                 getUser·p0.999:  13.671 ms/op
                 getUser·p0.9999: 32.974 ms/op
                 getUser·p1.00:   33.522 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 232746
  mean =      4.124 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 216384 
    [ 5.000,  7.500) = 12950 
    [ 7.500, 10.000) = 2691 
    [10.000, 12.500) = 296 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 80 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.550 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.439 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     20.988 ms/op
     p(99.9900) =     32.324 ms/op
     p(99.9990) =     33.305 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


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
# Warmup Iteration   1: 16.706 ±(99.9%) 0.239 ms/op
# Warmup Iteration   2: 5.877 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.009 ±(99.9%) 0.018 ms/op
Iteration   1: 4.829 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.946 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   9.126 ms/op
                 listUser·p0.999:  25.210 ms/op
                 listUser·p0.9999: 29.042 ms/op
                 listUser·p1.00:   31.883 ms/op

Iteration   2: 5.118 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.393 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   6.341 ms/op
                 listUser·p0.95:   7.676 ms/op
                 listUser·p0.99:   11.346 ms/op
                 listUser·p0.999:  19.795 ms/op
                 listUser·p0.9999: 24.568 ms/op
                 listUser·p1.00:   26.149 ms/op

Iteration   3: 4.754 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.892 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   9.552 ms/op
                 listUser·p0.999:  17.917 ms/op
                 listUser·p0.9999: 21.987 ms/op
                 listUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196000
  mean =      4.896 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 154929 
    [ 5.000,  7.500) = 33649 
    [ 7.500, 10.000) = 5551 
    [10.000, 12.500) = 1123 
    [12.500, 15.000) = 329 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 54 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.636 ms/op
     p(95.0000) =      6.939 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     20.873 ms/op
     p(99.9900) =     27.800 ms/op
     p(99.9990) =     31.034 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.462 ± 3.858  ops/ms
ClientPb.existUser                       thrpt       3   7.989 ± 2.925  ops/ms
ClientPb.getUser                         thrpt       3   7.449 ± 3.219  ops/ms
ClientPb.listUser                        thrpt       3   6.470 ± 1.817  ops/ms
ClientPb.createUser                       avgt       3   4.187 ± 1.307   ms/op
ClientPb.existUser                        avgt       3   4.015 ± 0.046   ms/op
ClientPb.getUser                          avgt       3   4.202 ± 2.159   ms/op
ClientPb.listUser                         avgt       3   4.839 ± 1.651   ms/op
ClientPb.createUser                     sample  234302   4.095 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.075           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.814           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.670           ms/op
ClientPb.createUser:createUser·p1.00    sample          45.416           ms/op
ClientPb.existUser                      sample  242048   3.963 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.255           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.838           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.375           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.138           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.647           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.996           ms/op
ClientPb.getUser                        sample  232746   4.124 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.550           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.953           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.439           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.069           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.988           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.324           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.522           ms/op
ClientPb.listUser                       sample  196000   4.896 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.393           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.939           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.880           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.873           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.800           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.883           ms/op
