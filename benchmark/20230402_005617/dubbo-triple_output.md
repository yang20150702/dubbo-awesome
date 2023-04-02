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
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 5.133 ops/ms
# Warmup Iteration   3: 9.152 ops/ms
Iteration   1: 9.040 ops/ms
Iteration   2: 9.511 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.336 ±(99.9%) 4.708 ops/ms [Average]
  (min, avg, max) = (9.040, 9.336, 9.511), stdev = 0.258
  CI (99.9%): [4.629, 14.044] (assumes normal distribution)


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
# Warmup Iteration   1: 3.162 ops/ms
# Warmup Iteration   2: 8.480 ops/ms
# Warmup Iteration   3: 9.231 ops/ms
Iteration   1: 9.995 ops/ms
Iteration   2: 10.096 ops/ms
Iteration   3: 9.747 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.946 ±(99.9%) 3.276 ops/ms [Average]
  (min, avg, max) = (9.747, 9.946, 10.096), stdev = 0.180
  CI (99.9%): [6.670, 13.222] (assumes normal distribution)


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
# Warmup Iteration   1: 3.101 ops/ms
# Warmup Iteration   2: 8.665 ops/ms
# Warmup Iteration   3: 9.313 ops/ms
Iteration   1: 9.641 ops/ms
Iteration   2: 9.029 ops/ms
Iteration   3: 9.093 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.254 ±(99.9%) 6.134 ops/ms [Average]
  (min, avg, max) = (9.029, 9.254, 9.641), stdev = 0.336
  CI (99.9%): [3.121, 15.388] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.859 ops/ms
# Warmup Iteration   2: 7.287 ops/ms
# Warmup Iteration   3: 8.320 ops/ms
Iteration   1: 8.211 ops/ms
Iteration   2: 7.960 ops/ms
Iteration   3: 8.340 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.170 ±(99.9%) 3.526 ops/ms [Average]
  (min, avg, max) = (7.960, 8.170, 8.340), stdev = 0.193
  CI (99.9%): [4.645, 11.696] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 9.218 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.591 ±(99.9%) 0.008 ms/op
Iteration   1: 3.376 ±(99.9%) 0.004 ms/op
Iteration   2: 3.215 ±(99.9%) 0.013 ms/op
Iteration   3: 3.527 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.373 ±(99.9%) 2.843 ms/op [Average]
  (min, avg, max) = (3.215, 3.373, 3.527), stdev = 0.156
  CI (99.9%): [0.530, 6.215] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.860 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.004 ms/op
Iteration   1: 3.255 ±(99.9%) 0.002 ms/op
Iteration   2: 3.234 ±(99.9%) 0.006 ms/op
Iteration   3: 3.162 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.217 ±(99.9%) 0.894 ms/op [Average]
  (min, avg, max) = (3.162, 3.217, 3.255), stdev = 0.049
  CI (99.9%): [2.323, 4.111] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 8.177 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.721 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.459 ±(99.9%) 0.008 ms/op
Iteration   1: 3.351 ±(99.9%) 0.005 ms/op
Iteration   2: 3.550 ±(99.9%) 0.008 ms/op
Iteration   3: 3.378 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.427 ±(99.9%) 1.970 ms/op [Average]
  (min, avg, max) = (3.351, 3.427, 3.550), stdev = 0.108
  CI (99.9%): [1.457, 5.397] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.243 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.008 ms/op
Iteration   1: 3.939 ±(99.9%) 0.009 ms/op
Iteration   2: 3.881 ±(99.9%) 0.012 ms/op
Iteration   3: 3.888 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.902 ±(99.9%) 0.577 ms/op [Average]
  (min, avg, max) = (3.881, 3.902, 3.939), stdev = 0.032
  CI (99.9%): [3.326, 4.479] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.776 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.434 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   4.133 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   5.218 ms/op
                 createUser·p0.999:  19.298 ms/op
                 createUser·p0.9999: 21.748 ms/op
                 createUser·p1.00:   22.741 ms/op

Iteration   2: 3.515 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.096 ms/op
                 createUser·p0.95:   4.317 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  21.758 ms/op
                 createUser·p0.9999: 26.477 ms/op
                 createUser·p1.00:   28.082 ms/op

Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.591 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.920 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  15.610 ms/op
                 createUser·p0.9999: 28.959 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 276999
  mean =      3.461 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13258 
    [ 2.500,  5.000) = 258746 
    [ 5.000,  7.500) = 4234 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.693 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     27.915 ms/op
     p(99.9990) =     29.237 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 9.444 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.650 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.314 ±(99.9%) 0.008 ms/op
Iteration   1: 3.205 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.753 ms/op
                 existUser·p0.50:   3.224 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  10.666 ms/op
                 existUser·p0.9999: 24.316 ms/op
                 existUser·p1.00:   25.526 ms/op

Iteration   2: 3.263 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.034 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   5.489 ms/op
                 existUser·p0.999:  12.616 ms/op
                 existUser·p0.9999: 26.509 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   3: 3.303 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   5.358 ms/op
                 existUser·p0.999:  9.806 ms/op
                 existUser·p0.9999: 26.212 ms/op
                 existUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 294750
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25106 
    [ 2.500,  5.000) = 265869 
    [ 5.000,  7.500) = 3003 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 4 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 67 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.617 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =     11.215 ms/op
     p(99.9900) =     26.232 ms/op
     p(99.9990) =     27.896 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


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
# Warmup Iteration   1: 8.921 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.617 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.010 ms/op
Iteration   1: 3.414 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.688 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.740 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.955 ms/op
                 getUser·p0.999:  12.653 ms/op
                 getUser·p0.9999: 22.303 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.451 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.874 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   5.964 ms/op
                 getUser·p0.999:  20.718 ms/op
                 getUser·p0.9999: 29.253 ms/op
                 getUser·p1.00:   29.753 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.622 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  17.221 ms/op
                 getUser·p0.9999: 25.354 ms/op
                 getUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278905
  mean =      3.441 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7128 
    [ 2.500,  5.000) = 263918 
    [ 5.000,  7.500) = 6616 
    [ 7.500, 10.000) = 825 
    [10.000, 12.500) = 130 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 54 

  Percentiles, ms/op:
      p(0.0000) =      0.874 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     12.812 ms/op
     p(99.9900) =     26.891 ms/op
     p(99.9990) =     29.688 ms/op
     p(99.9999) =     29.753 ms/op
    p(100.0000) =     29.753 ms/op


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
# Warmup Iteration   1: 10.944 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.430 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.012 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.432 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  19.824 ms/op
                 listUser·p0.9999: 24.097 ms/op
                 listUser·p1.00:   25.428 ms/op

Iteration   2: 3.832 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.287 ms/op
                 listUser·p0.9999: 29.229 ms/op
                 listUser·p1.00:   29.262 ms/op

Iteration   3: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  15.700 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242822
  mean =      3.951 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 234903 
    [ 5.000,  7.500) = 5600 
    [ 7.500, 10.000) = 1358 
    [10.000, 12.500) = 368 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      7.356 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     27.352 ms/op
     p(99.9990) =     29.262 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.336 ± 4.708  ops/ms
ClientPb.existUser                       thrpt       3   9.946 ± 3.276  ops/ms
ClientPb.getUser                         thrpt       3   9.254 ± 6.134  ops/ms
ClientPb.listUser                        thrpt       3   8.170 ± 3.526  ops/ms
ClientPb.createUser                       avgt       3   3.373 ± 2.843   ms/op
ClientPb.existUser                        avgt       3   3.217 ± 0.894   ms/op
ClientPb.getUser                          avgt       3   3.427 ± 1.970   ms/op
ClientPb.listUser                         avgt       3   3.902 ± 0.577   ms/op
ClientPb.createUser                     sample  276999   3.461 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.720           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.055           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.745           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.915           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  294750   3.256 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.034           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.617           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.358           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.215           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.232           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.344           ms/op
ClientPb.getUser                        sample  278905   3.441 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.874           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.162           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.668           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.812           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.891           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.753           ms/op
ClientPb.listUser                       sample  242822   3.951 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.845           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.301           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.588           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.356           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.745           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.352           ms/op
ClientPb.listUser:listUser·p1.00        sample          29.262           ms/op
