# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.462 ops/ms
# Warmup Iteration   2: 6.040 ops/ms
# Warmup Iteration   3: 9.030 ops/ms
Iteration   1: 10.173 ops/ms
Iteration   2: 9.995 ops/ms
Iteration   3: 10.367 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  10.178 ±(99.9%) 3.396 ops/ms [Average]
  (min, avg, max) = (9.995, 10.178, 10.367), stdev = 0.186
  CI (99.9%): [6.782, 13.574] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.367 ops/ms
# Warmup Iteration   2: 9.744 ops/ms
# Warmup Iteration   3: 9.874 ops/ms
Iteration   1: 10.516 ops/ms
Iteration   2: 10.701 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.459 ±(99.9%) 5.008 ops/ms [Average]
  (min, avg, max) = (10.161, 10.459, 10.701), stdev = 0.274
  CI (99.9%): [5.451, 15.467] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.634 ops/ms
# Warmup Iteration   2: 8.755 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 9.993 ops/ms
Iteration   2: 9.802 ops/ms
Iteration   3: 9.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.906 ±(99.9%) 1.766 ops/ms [Average]
  (min, avg, max) = (9.802, 9.906, 9.993), stdev = 0.097
  CI (99.9%): [8.140, 11.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ops/ms
# Warmup Iteration   2: 7.942 ops/ms
# Warmup Iteration   3: 8.362 ops/ms
Iteration   1: 8.655 ops/ms
Iteration   2: 8.520 ops/ms
Iteration   3: 8.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.594 ±(99.9%) 1.245 ops/ms [Average]
  (min, avg, max) = (8.520, 8.594, 8.655), stdev = 0.068
  CI (99.9%): [7.349, 9.839] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.869 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.354 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.199 ±(99.9%) 0.005 ms/op
Iteration   1: 3.114 ±(99.9%) 0.005 ms/op
Iteration   2: 3.186 ±(99.9%) 0.006 ms/op
Iteration   3: 3.112 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.137 ±(99.9%) 0.774 ms/op [Average]
  (min, avg, max) = (3.112, 3.137, 3.186), stdev = 0.042
  CI (99.9%): [2.363, 3.912] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.818 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.137 ±(99.9%) 0.008 ms/op
Iteration   1: 3.126 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.004 ms/op
Iteration   3: 2.966 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.051 ±(99.9%) 1.466 ms/op [Average]
  (min, avg, max) = (2.966, 3.051, 3.126), stdev = 0.080
  CI (99.9%): [1.585, 4.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.229 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.351 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.003 ms/op
Iteration   2: 3.044 ±(99.9%) 0.007 ms/op
Iteration   3: 3.216 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.126 ±(99.9%) 1.575 ms/op [Average]
  (min, avg, max) = (3.044, 3.126, 3.216), stdev = 0.086
  CI (99.9%): [1.551, 4.702] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.597 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.913 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.722 ±(99.9%) 0.006 ms/op
Iteration   1: 3.635 ±(99.9%) 0.004 ms/op
Iteration   2: 3.819 ±(99.9%) 0.005 ms/op
Iteration   3: 3.663 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.706 ±(99.9%) 1.807 ms/op [Average]
  (min, avg, max) = (3.635, 3.706, 3.819), stdev = 0.099
  CI (99.9%): [1.899, 5.513] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.970 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.088 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  9.392 ms/op
                 createUser·p0.9999: 19.497 ms/op
                 createUser·p1.00:   19.923 ms/op

Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   2.986 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   5.202 ms/op
                 createUser·p0.999:  11.820 ms/op
                 createUser·p0.9999: 29.254 ms/op
                 createUser·p1.00:   30.147 ms/op

Iteration   3: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.923 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  16.810 ms/op
                 createUser·p0.9999: 19.923 ms/op
                 createUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306928
  mean =      3.128 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16024 
    [ 2.500,  5.000) = 286561 
    [ 5.000,  7.500) = 3514 
    [ 7.500, 10.000) = 368 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 197 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.923 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.490 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     16.238 ms/op
     p(99.9900) =     28.254 ms/op
     p(99.9990) =     29.980 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.303 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.009 ms/op
Iteration   1: 3.231 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.022 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.715 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 19.585 ms/op
                 existUser·p1.00:   21.266 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.171 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   5.202 ms/op
                 existUser·p0.999:  11.780 ms/op
                 existUser·p0.9999: 22.269 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.033 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.239 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.240 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  9.745 ms/op
                 existUser·p0.9999: 23.921 ms/op
                 existUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308374
  mean =      3.109 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18788 
    [ 2.500,  5.000) = 283846 
    [ 5.000,  7.500) = 5035 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.022 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     11.471 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.478 ms/op
     p(99.9999) =     24.510 ms/op
    p(100.0000) =     24.510 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.902 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.264 ±(99.9%) 0.008 ms/op
Iteration   1: 3.159 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.135 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  17.465 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.546 ms/op

Iteration   2: 3.356 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.977 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   4.035 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  17.172 ms/op
                 getUser·p0.9999: 27.034 ms/op
                 getUser·p1.00:   29.327 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  15.337 ms/op
                 getUser·p0.9999: 23.112 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293510
  mean =      3.269 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12500 
    [ 2.500,  5.000) = 275242 
    [ 5.000,  7.500) = 4499 
    [ 7.500, 10.000) = 690 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     16.924 ms/op
     p(99.9900) =     25.274 ms/op
     p(99.9990) =     27.403 ms/op
     p(99.9999) =     29.327 ms/op
    p(100.0000) =     29.327 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.619 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.841 ±(99.9%) 0.012 ms/op
Iteration   1: 3.763 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.653 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.026 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  18.960 ms/op
                 listUser·p0.9999: 21.479 ms/op
                 listUser·p1.00:   23.200 ms/op

Iteration   2: 3.821 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.066 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  12.763 ms/op
                 listUser·p0.9999: 15.106 ms/op
                 listUser·p1.00:   15.254 ms/op

Iteration   3: 3.760 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.665 ms/op
                 listUser·p0.9999: 15.385 ms/op
                 listUser·p1.00:   16.089 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253795
  mean =      3.781 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 70 
    [ 2.500,  5.000) = 245939 
    [ 5.000,  7.500) = 5649 
    [ 7.500, 10.000) = 1402 
    [10.000, 12.500) = 301 
    [12.500, 15.000) = 301 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.653 ms/op
     p(50.0000) =      3.682 ms/op
     p(90.0000) =      4.088 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      7.217 ms/op
     p(99.9000) =     13.373 ms/op
     p(99.9900) =     20.762 ms/op
     p(99.9990) =     21.884 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  10.178 ± 3.396  ops/ms
ClientPb.existUser                       thrpt       3  10.459 ± 5.008  ops/ms
ClientPb.getUser                         thrpt       3   9.906 ± 1.766  ops/ms
ClientPb.listUser                        thrpt       3   8.594 ± 1.245  ops/ms
ClientPb.createUser                       avgt       3   3.137 ± 0.774   ms/op
ClientPb.existUser                        avgt       3   3.051 ± 1.466   ms/op
ClientPb.getUser                          avgt       3   3.126 ± 1.575   ms/op
ClientPb.listUser                         avgt       3   3.706 ± 1.807   ms/op
ClientPb.createUser                     sample  306928   3.128 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.923           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.043           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.490           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.238           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.254           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.147           ms/op
ClientPb.existUser                      sample  308374   3.109 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.022           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.043           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.473           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.813           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.471           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.036           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.510           ms/op
ClientPb.getUser                        sample  293510   3.269 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.977           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.940           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.308           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.924           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.274           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.327           ms/op
ClientPb.listUser                       sample  253795   3.781 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.653           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.682           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.088           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.217           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.373           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.762           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.200           ms/op
