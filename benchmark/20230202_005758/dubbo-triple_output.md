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
# Warmup Iteration   1: 2.348 ops/ms
# Warmup Iteration   2: 5.906 ops/ms
# Warmup Iteration   3: 9.258 ops/ms
Iteration   1: 9.885 ops/ms
Iteration   2: 9.978 ops/ms
Iteration   3: 9.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.933 ±(99.9%) 0.845 ops/ms [Average]
  (min, avg, max) = (9.885, 9.933, 9.978), stdev = 0.046
  CI (99.9%): [9.088, 10.778] (assumes normal distribution)


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
# Warmup Iteration   1: 3.182 ops/ms
# Warmup Iteration   2: 9.026 ops/ms
# Warmup Iteration   3: 10.020 ops/ms
Iteration   1: 10.250 ops/ms
Iteration   2: 10.527 ops/ms
Iteration   3: 10.348 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.375 ±(99.9%) 2.559 ops/ms [Average]
  (min, avg, max) = (10.250, 10.375, 10.527), stdev = 0.140
  CI (99.9%): [7.816, 12.935] (assumes normal distribution)


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
# Warmup Iteration   1: 2.917 ops/ms
# Warmup Iteration   2: 8.770 ops/ms
# Warmup Iteration   3: 9.440 ops/ms
Iteration   1: 10.134 ops/ms
Iteration   2: 9.462 ops/ms
Iteration   3: 9.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.816 ±(99.9%) 6.159 ops/ms [Average]
  (min, avg, max) = (9.462, 9.816, 10.134), stdev = 0.338
  CI (99.9%): [3.657, 15.975] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.208 ops/ms
# Warmup Iteration   2: 7.949 ops/ms
# Warmup Iteration   3: 8.400 ops/ms
Iteration   1: 8.652 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.179 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.409 ±(99.9%) 4.324 ops/ms [Average]
  (min, avg, max) = (8.179, 8.409, 8.652), stdev = 0.237
  CI (99.9%): [4.085, 12.733] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 8.635 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.685 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.003 ms/op
Iteration   1: 3.355 ±(99.9%) 0.004 ms/op
Iteration   2: 3.184 ±(99.9%) 0.006 ms/op
Iteration   3: 3.158 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.233 ±(99.9%) 1.953 ms/op [Average]
  (min, avg, max) = (3.158, 3.233, 3.355), stdev = 0.107
  CI (99.9%): [1.280, 5.185] (assumes normal distribution)


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
# Warmup Iteration   1: 7.319 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.364 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.005 ms/op
Iteration   1: 3.104 ±(99.9%) 0.005 ms/op
Iteration   2: 3.084 ±(99.9%) 0.006 ms/op
Iteration   3: 3.167 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.118 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.084, 3.118, 3.167), stdev = 0.043
  CI (99.9%): [2.330, 3.907] (assumes normal distribution)


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
# Warmup Iteration   1: 7.876 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.557 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.002 ms/op
Iteration   1: 3.356 ±(99.9%) 0.003 ms/op
Iteration   2: 3.143 ±(99.9%) 0.003 ms/op
Iteration   3: 3.142 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.213 ±(99.9%) 2.249 ms/op [Average]
  (min, avg, max) = (3.142, 3.213, 3.356), stdev = 0.123
  CI (99.9%): [0.964, 5.462] (assumes normal distribution)


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
# Warmup Iteration   1: 9.019 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.756 ±(99.9%) 0.008 ms/op
Iteration   1: 3.686 ±(99.9%) 0.010 ms/op
Iteration   2: 3.695 ±(99.9%) 0.009 ms/op
Iteration   3: 3.608 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.663 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (3.608, 3.663, 3.695), stdev = 0.048
  CI (99.9%): [2.793, 4.533] (assumes normal distribution)


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
# Warmup Iteration   1: 8.122 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.628 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.268 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  15.604 ms/op
                 createUser·p0.9999: 21.266 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   2: 3.121 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.049 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   5.194 ms/op
                 createUser·p0.999:  12.845 ms/op
                 createUser·p0.9999: 28.344 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 3.154 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  15.650 ms/op
                 createUser·p0.9999: 19.581 ms/op
                 createUser·p1.00:   25.756 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 303660
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13240 
    [ 2.500,  5.000) = 285573 
    [ 5.000,  7.500) = 3776 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 220 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.518 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      5.382 ms/op
     p(99.9000) =     15.385 ms/op
     p(99.9900) =     27.108 ms/op
     p(99.9990) =     28.801 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 6.992 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.434 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
Iteration   1: 3.120 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.313 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  9.379 ms/op
                 existUser·p0.9999: 20.332 ms/op
                 existUser·p1.00:   20.972 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.215 ms/op
                 existUser·p0.90:   3.789 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.898 ms/op
                 existUser·p0.999:  16.071 ms/op
                 existUser·p0.9999: 22.889 ms/op
                 existUser·p1.00:   24.543 ms/op

Iteration   3: 3.236 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.481 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   5.407 ms/op
                 existUser·p0.999:  13.149 ms/op
                 existUser·p0.9999: 23.233 ms/op
                 existUser·p1.00:   24.707 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297834
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23410 
    [ 2.500,  5.000) = 268039 
    [ 5.000,  7.500) = 5751 
    [ 7.500, 10.000) = 287 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.122 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.936 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     12.673 ms/op
     p(99.9900) =     22.683 ms/op
     p(99.9990) =     23.549 ms/op
     p(99.9999) =     24.707 ms/op
    p(100.0000) =     24.707 ms/op


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
# Warmup Iteration   1: 7.561 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.583 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.012 ms/op
Iteration   1: 3.218 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.530 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  10.306 ms/op
                 getUser·p0.9999: 23.429 ms/op
                 getUser·p1.00:   24.773 ms/op

Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.180 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  13.124 ms/op
                 getUser·p0.9999: 22.683 ms/op
                 getUser·p1.00:   23.134 ms/op

Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.294 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  15.144 ms/op
                 getUser·p0.9999: 22.841 ms/op
                 getUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 297016
  mean =      3.230 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13066 
    [ 2.500,  5.000) = 276775 
    [ 5.000,  7.500) = 6043 
    [ 7.500, 10.000) = 743 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.294 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.088 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     13.173 ms/op
     p(99.9900) =     22.970 ms/op
     p(99.9990) =     24.513 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 9.991 ±(99.9%) 0.126 ms/op
# Warmup Iteration   2: 4.198 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.846 ±(99.9%) 0.013 ms/op
Iteration   1: 3.738 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.176 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.226 ms/op
                 listUser·p0.9999: 32.717 ms/op
                 listUser·p1.00:   33.882 ms/op

Iteration   2: 3.855 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.151 ms/op
                 listUser·p0.9999: 14.336 ms/op
                 listUser·p1.00:   15.270 ms/op

Iteration   3: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.585 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   5.107 ms/op
                 listUser·p0.99:   7.528 ms/op
                 listUser·p0.999:  12.735 ms/op
                 listUser·p0.9999: 18.032 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 251407
  mean =      3.818 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 240930 
    [ 5.000,  7.500) = 8414 
    [ 7.500, 10.000) = 1344 
    [10.000, 12.500) = 259 
    [12.500, 15.000) = 225 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 15 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.174 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     31.144 ms/op
     p(99.9990) =     33.504 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.933 ± 0.845  ops/ms
ClientPb.existUser                       thrpt       3  10.375 ± 2.559  ops/ms
ClientPb.getUser                         thrpt       3   9.816 ± 6.159  ops/ms
ClientPb.listUser                        thrpt       3   8.409 ± 4.324  ops/ms
ClientPb.createUser                       avgt       3   3.233 ± 1.953   ms/op
ClientPb.existUser                        avgt       3   3.118 ± 0.789   ms/op
ClientPb.getUser                          avgt       3   3.213 ± 2.249   ms/op
ClientPb.listUser                         avgt       3   3.663 ± 0.870   ms/op
ClientPb.createUser                     sample  303660   3.160 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.049           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.068           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.518           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.785           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.382           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.385           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.108           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.901           ms/op
ClientPb.existUser                      sample  297834   3.221 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.122           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.183           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.936           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.673           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.683           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.707           ms/op
ClientPb.getUser                        sample  297016   3.230 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.600           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.088           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.087           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.173           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.970           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.773           ms/op
ClientPb.listUser                       sample  251407   3.818 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.176           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.703           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.174           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.266           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.144           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.882           ms/op
