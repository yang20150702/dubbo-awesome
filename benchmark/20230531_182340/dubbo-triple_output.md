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
# Warmup Iteration   1: 2.295 ops/ms
# Warmup Iteration   2: 6.317 ops/ms
# Warmup Iteration   3: 8.932 ops/ms
Iteration   1: 9.010 ops/ms
Iteration   2: 9.331 ops/ms
Iteration   3: 9.233 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.192 ±(99.9%) 3.000 ops/ms [Average]
  (min, avg, max) = (9.010, 9.192, 9.331), stdev = 0.164
  CI (99.9%): [6.192, 12.192] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.012 ops/ms
# Warmup Iteration   2: 8.685 ops/ms
# Warmup Iteration   3: 9.632 ops/ms
Iteration   1: 9.926 ops/ms
Iteration   2: 9.867 ops/ms
Iteration   3: 10.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.963 ±(99.9%) 2.171 ops/ms [Average]
  (min, avg, max) = (9.867, 9.963, 10.096), stdev = 0.119
  CI (99.9%): [7.792, 12.133] (assumes normal distribution)


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
# Warmup Iteration   1: 3.075 ops/ms
# Warmup Iteration   2: 8.509 ops/ms
# Warmup Iteration   3: 9.351 ops/ms
Iteration   1: 8.984 ops/ms
Iteration   2: 9.405 ops/ms
Iteration   3: 9.690 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.360 ±(99.9%) 6.478 ops/ms [Average]
  (min, avg, max) = (8.984, 9.360, 9.690), stdev = 0.355
  CI (99.9%): [2.882, 15.837] (assumes normal distribution)


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
# Warmup Iteration   1: 2.624 ops/ms
# Warmup Iteration   2: 7.216 ops/ms
# Warmup Iteration   3: 7.865 ops/ms
Iteration   1: 7.935 ops/ms
Iteration   2: 8.066 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.038 ±(99.9%) 1.673 ops/ms [Average]
  (min, avg, max) = (7.935, 8.038, 8.112), stdev = 0.092
  CI (99.9%): [6.364, 9.711] (assumes normal distribution)


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
# Warmup Iteration   1: 9.449 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.405 ±(99.9%) 0.010 ms/op
Iteration   1: 3.314 ±(99.9%) 0.005 ms/op
Iteration   2: 3.242 ±(99.9%) 0.011 ms/op
Iteration   3: 3.357 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.304 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.242, 3.304, 3.357), stdev = 0.058
  CI (99.9%): [2.242, 4.367] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.834 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.538 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.004 ms/op
Iteration   1: 3.135 ±(99.9%) 0.006 ms/op
Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
Iteration   3: 3.201 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.171 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (3.135, 3.171, 3.201), stdev = 0.034
  CI (99.9%): [2.555, 3.786] (assumes normal distribution)


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
# Warmup Iteration   1: 9.048 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.730 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.546 ±(99.9%) 0.006 ms/op
Iteration   1: 3.338 ±(99.9%) 0.009 ms/op
Iteration   2: 3.307 ±(99.9%) 0.011 ms/op
Iteration   3: 3.348 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.331 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (3.307, 3.331, 3.348), stdev = 0.021
  CI (99.9%): [2.942, 3.720] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.704 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.655 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.008 ms/op
Iteration   1: 3.981 ±(99.9%) 0.016 ms/op
Iteration   2: 3.852 ±(99.9%) 0.013 ms/op
Iteration   3: 3.880 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.904 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (3.852, 3.904, 3.981), stdev = 0.068
  CI (99.9%): [2.665, 5.143] (assumes normal distribution)


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
# Warmup Iteration   1: 10.375 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.927 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.013 ms/op
Iteration   1: 3.318 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   5.546 ms/op
                 createUser·p0.999:  16.485 ms/op
                 createUser·p0.9999: 23.036 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   2: 3.449 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.363 ms/op
                 createUser·p0.90:   3.924 ms/op
                 createUser·p0.95:   4.588 ms/op
                 createUser·p0.99:   6.193 ms/op
                 createUser·p0.999:  19.165 ms/op
                 createUser·p0.9999: 23.215 ms/op
                 createUser·p1.00:   24.805 ms/op

Iteration   3: 3.425 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.174 ms/op
                 createUser·p0.50:   3.289 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  16.196 ms/op
                 createUser·p0.9999: 24.838 ms/op
                 createUser·p1.00:   26.280 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282567
  mean =      3.396 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13853 
    [ 2.500,  5.000) = 261911 
    [ 5.000,  7.500) = 5749 
    [ 7.500, 10.000) = 532 
    [10.000, 12.500) = 182 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 105 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 58 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.034 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.284 ms/op
     p(99.0000) =      5.835 ms/op
     p(99.9000) =     16.267 ms/op
     p(99.9900) =     24.437 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 8.265 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 3.445 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.386 ±(99.9%) 0.009 ms/op
Iteration   1: 3.206 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   3.092 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   5.571 ms/op
                 existUser·p0.999:  9.218 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   22.708 ms/op

Iteration   2: 3.394 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.384 ms/op
                 existUser·p0.50:   3.273 ms/op
                 existUser·p0.90:   3.994 ms/op
                 existUser·p0.95:   4.407 ms/op
                 existUser·p0.99:   5.636 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 22.400 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.622 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.140 ms/op
                 existUser·p0.999:  11.684 ms/op
                 existUser·p0.9999: 28.253 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 290893
  mean =      3.300 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13410 
    [ 2.500,  5.000) = 271616 
    [ 5.000,  7.500) = 5087 
    [ 7.500, 10.000) = 425 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 135 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.759 ms/op
     p(99.9000) =     11.563 ms/op
     p(99.9900) =     26.369 ms/op
     p(99.9990) =     28.779 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 9.854 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.619 ±(99.9%) 0.011 ms/op
Iteration   1: 3.450 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.239 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   4.121 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   6.381 ms/op
                 getUser·p0.999:  14.860 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.352 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.252 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   4.132 ms/op
                 getUser·p0.99:   5.538 ms/op
                 getUser·p0.999:  21.427 ms/op
                 getUser·p0.9999: 31.014 ms/op
                 getUser·p1.00:   31.556 ms/op

Iteration   3: 3.404 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.858 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   4.133 ms/op
                 getUser·p0.99:   6.855 ms/op
                 getUser·p0.999:  22.657 ms/op
                 getUser·p0.9999: 27.381 ms/op
                 getUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 282087
  mean =      3.402 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9987 
    [ 2.500,  5.000) = 264505 
    [ 5.000,  7.500) = 6294 
    [ 7.500, 10.000) = 854 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.858 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.851 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.186 ms/op
     p(99.9000) =     14.890 ms/op
     p(99.9900) =     29.052 ms/op
     p(99.9990) =     31.365 ms/op
     p(99.9999) =     31.556 ms/op
    p(100.0000) =     31.556 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.165 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.463 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.014 ms/op
Iteration   1: 4.015 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.745 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   4.737 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 26.741 ms/op
                 listUser·p1.00:   27.230 ms/op

Iteration   2: 4.019 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.474 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.854 ms/op
                 listUser·p0.999:  14.369 ms/op
                 listUser·p0.9999: 18.810 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 3.953 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.059 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  14.631 ms/op
                 listUser·p0.9999: 16.938 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240011
  mean =      3.995 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 231017 
    [ 5.000,  7.500) = 6539 
    [ 7.500, 10.000) = 1580 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 220 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.745 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     23.462 ms/op
     p(99.9990) =     27.217 ms/op
     p(99.9999) =     27.230 ms/op
    p(100.0000) =     27.230 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.192 ± 3.000  ops/ms
ClientPb.existUser                       thrpt       3   9.963 ± 2.171  ops/ms
ClientPb.getUser                         thrpt       3   9.360 ± 6.478  ops/ms
ClientPb.listUser                        thrpt       3   8.038 ± 1.673  ops/ms
ClientPb.createUser                       avgt       3   3.304 ± 1.062   ms/op
ClientPb.existUser                        avgt       3   3.171 ± 0.616   ms/op
ClientPb.getUser                          avgt       3   3.331 ± 0.389   ms/op
ClientPb.listUser                         avgt       3   3.904 ± 1.239   ms/op
ClientPb.createUser                     sample  282567   3.396 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.034           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.835           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.267           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.437           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.280           ms/op
ClientPb.existUser                      sample  290893   3.300 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.309           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.759           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.563           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  282087   3.402 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.858           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.851           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.375           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.186           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.890           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.052           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.556           ms/op
ClientPb.listUser                       sample  240011   3.995 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.745           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.694           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.504           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.417           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.462           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.230           ms/op
