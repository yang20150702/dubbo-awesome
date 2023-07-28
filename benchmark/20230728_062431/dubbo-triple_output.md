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
# Warmup Iteration   1: 2.679 ops/ms
# Warmup Iteration   2: 6.717 ops/ms
# Warmup Iteration   3: 8.796 ops/ms
Iteration   1: 9.736 ops/ms
Iteration   2: 9.677 ops/ms
Iteration   3: 10.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.881 ±(99.9%) 5.543 ops/ms [Average]
  (min, avg, max) = (9.677, 9.881, 10.230), stdev = 0.304
  CI (99.9%): [4.338, 15.424] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.815 ops/ms
# Warmup Iteration   2: 9.249 ops/ms
# Warmup Iteration   3: 10.300 ops/ms
Iteration   1: 10.179 ops/ms
Iteration   2: 10.331 ops/ms
Iteration   3: 10.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.206 ±(99.9%) 2.077 ops/ms [Average]
  (min, avg, max) = (10.108, 10.206, 10.331), stdev = 0.114
  CI (99.9%): [8.129, 12.283] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.402 ops/ms
# Warmup Iteration   2: 8.820 ops/ms
# Warmup Iteration   3: 9.364 ops/ms
Iteration   1: 9.760 ops/ms
Iteration   2: 10.139 ops/ms
Iteration   3: 10.257 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.052 ±(99.9%) 4.741 ops/ms [Average]
  (min, avg, max) = (9.760, 10.052, 10.257), stdev = 0.260
  CI (99.9%): [5.311, 14.792] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.196 ops/ms
# Warmup Iteration   2: 7.470 ops/ms
# Warmup Iteration   3: 8.397 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.541 ops/ms
Iteration   3: 8.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.494 ±(99.9%) 2.281 ops/ms [Average]
  (min, avg, max) = (8.352, 8.494, 8.588), stdev = 0.125
  CI (99.9%): [6.213, 10.775] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.361 ±(99.9%) 0.006 ms/op
Iteration   1: 3.145 ±(99.9%) 0.002 ms/op
Iteration   2: 3.340 ±(99.9%) 0.006 ms/op
Iteration   3: 3.077 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.187 ±(99.9%) 2.488 ms/op [Average]
  (min, avg, max) = (3.077, 3.187, 3.340), stdev = 0.136
  CI (99.9%): [0.699, 5.675] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.717 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.217 ±(99.9%) 0.005 ms/op
Iteration   1: 3.081 ±(99.9%) 0.005 ms/op
Iteration   2: 3.315 ±(99.9%) 0.001 ms/op
Iteration   3: 3.154 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.183 ±(99.9%) 2.191 ms/op [Average]
  (min, avg, max) = (3.081, 3.183, 3.315), stdev = 0.120
  CI (99.9%): [0.993, 5.374] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.377 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.635 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.332 ±(99.9%) 0.003 ms/op
Iteration   1: 3.280 ±(99.9%) 0.010 ms/op
Iteration   2: 3.135 ±(99.9%) 0.006 ms/op
Iteration   3: 3.123 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.179 ±(99.9%) 1.597 ms/op [Average]
  (min, avg, max) = (3.123, 3.179, 3.280), stdev = 0.088
  CI (99.9%): [1.583, 4.776] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.122 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.007 ms/op
Iteration   1: 3.782 ±(99.9%) 0.009 ms/op
Iteration   2: 3.784 ±(99.9%) 0.002 ms/op
Iteration   3: 3.746 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.771 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.746, 3.771, 3.784), stdev = 0.021
  CI (99.9%): [3.388, 4.153] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.176 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.327 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   3.207 ms/op
                 createUser·p0.90:   3.990 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.639 ms/op
                 createUser·p0.999:  18.909 ms/op
                 createUser·p0.9999: 29.026 ms/op
                 createUser·p1.00:   29.622 ms/op

Iteration   2: 3.266 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.714 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  11.283 ms/op
                 createUser·p0.9999: 22.217 ms/op
                 createUser·p1.00:   22.577 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.212 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   4.191 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 26.706 ms/op
                 createUser·p1.00:   28.082 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 292789
  mean =      3.276 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18401 
    [ 2.500,  5.000) = 267446 
    [ 5.000,  7.500) = 6084 
    [ 7.500, 10.000) = 462 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 140 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.714 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     27.751 ms/op
     p(99.9990) =     29.622 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.398 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.118 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.554 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 18.612 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   2: 3.065 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.597 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.038 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 32.904 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 3.253 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   5.284 ms/op
                 existUser·p0.999:  12.021 ms/op
                 existUser·p0.9999: 21.660 ms/op
                 existUser·p1.00:   23.167 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 305968
  mean =      3.135 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18096 
    [ 2.500,  5.000) = 283884 
    [ 5.000,  7.500) = 3177 
    [ 7.500, 10.000) = 343 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      5.308 ms/op
     p(99.9000) =     12.108 ms/op
     p(99.9900) =     31.707 ms/op
     p(99.9990) =     33.437 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.984 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.342 ±(99.9%) 0.010 ms/op
Iteration   1: 3.191 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.707 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  12.896 ms/op
                 getUser·p0.9999: 26.410 ms/op
                 getUser·p1.00:   27.034 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.298 ms/op
                 getUser·p0.50:   3.105 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   5.390 ms/op
                 getUser·p0.999:  9.863 ms/op
                 getUser·p0.9999: 22.840 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   3: 3.288 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   4.129 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  14.999 ms/op
                 getUser·p0.9999: 21.766 ms/op
                 getUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297425
  mean =      3.228 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12595 
    [ 2.500,  5.000) = 278398 
    [ 5.000,  7.500) = 5546 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 172 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.851 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.926 ms/op
     p(99.9900) =     24.340 ms/op
     p(99.9990) =     26.936 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.448 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.010 ms/op
Iteration   1: 3.718 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.048 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.740 ms/op
                 listUser·p0.999:  16.775 ms/op
                 listUser·p0.9999: 19.522 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 3.745 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.678 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.252 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.100 ms/op
                 listUser·p0.9999: 17.039 ms/op
                 listUser·p1.00:   17.334 ms/op

Iteration   3: 3.737 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.858 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  12.510 ms/op
                 listUser·p0.9999: 16.677 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257120
  mean =      3.733 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63 
    [ 2.500,  5.000) = 250548 
    [ 5.000,  7.500) = 4825 
    [ 7.500, 10.000) = 947 
    [10.000, 12.500) = 329 
    [12.500, 15.000) = 229 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.800 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     13.761 ms/op
     p(99.9900) =     18.360 ms/op
     p(99.9990) =     20.429 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.881 ± 5.543  ops/ms
ClientPb.existUser                       thrpt       3  10.206 ± 2.077  ops/ms
ClientPb.getUser                         thrpt       3  10.052 ± 4.741  ops/ms
ClientPb.listUser                        thrpt       3   8.494 ± 2.281  ops/ms
ClientPb.createUser                       avgt       3   3.187 ± 2.488   ms/op
ClientPb.existUser                        avgt       3   3.183 ± 2.191   ms/op
ClientPb.getUser                          avgt       3   3.179 ± 1.597   ms/op
ClientPb.listUser                         avgt       3   3.771 ± 0.382   ms/op
ClientPb.createUser                     sample  292789   3.276 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.714           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.276           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.710           ms/op
ClientPb.createUser:createUser·p0.999   sample          11.256           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.751           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.622           ms/op
ClientPb.existUser                      sample  305968   3.135 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.169           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.084           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.715           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.308           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.108           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.707           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  297425   3.228 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.851           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.138           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.908           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.926           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.340           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  257120   3.733 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.800           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.014           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.791           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.761           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.360           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.546           ms/op
