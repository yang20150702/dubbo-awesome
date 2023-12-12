# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.985 ops/ms
# Warmup Iteration   2: 12.394 ops/ms
# Warmup Iteration   3: 12.437 ops/ms
Iteration   1: 12.740 ops/ms
Iteration   2: 12.715 ops/ms
Iteration   3: 12.851 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.769 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (12.715, 12.769, 12.851), stdev = 0.072
  CI (99.9%): [11.447, 14.090] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.151 ops/ms
# Warmup Iteration   2: 13.170 ops/ms
# Warmup Iteration   3: 13.187 ops/ms
Iteration   1: 13.237 ops/ms
Iteration   2: 13.331 ops/ms
Iteration   3: 13.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.205 ±(99.9%) 2.647 ops/ms [Average]
  (min, avg, max) = (13.047, 13.205, 13.331), stdev = 0.145
  CI (99.9%): [10.558, 15.852] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.195 ops/ms
# Warmup Iteration   2: 12.770 ops/ms
# Warmup Iteration   3: 12.893 ops/ms
Iteration   1: 12.813 ops/ms
Iteration   2: 12.927 ops/ms
Iteration   3: 13.032 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.924 ±(99.9%) 2.000 ops/ms [Average]
  (min, avg, max) = (12.813, 12.924, 13.032), stdev = 0.110
  CI (99.9%): [10.924, 14.924] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.489 ops/ms
# Warmup Iteration   2: 10.711 ops/ms
# Warmup Iteration   3: 10.800 ops/ms
Iteration   1: 10.678 ops/ms
Iteration   2: 10.823 ops/ms
Iteration   3: 10.901 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.801 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (10.678, 10.801, 10.901), stdev = 0.113
  CI (99.9%): [8.738, 12.864] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.497 ±(99.9%) 0.004 ms/op
Iteration   2: 2.538 ±(99.9%) 0.004 ms/op
Iteration   3: 2.485 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.506 ±(99.9%) 0.512 ms/op [Average]
  (min, avg, max) = (2.485, 2.506, 2.538), stdev = 0.028
  CI (99.9%): [1.995, 3.018] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.003 ms/op
Iteration   1: 2.408 ±(99.9%) 0.003 ms/op
Iteration   2: 2.411 ±(99.9%) 0.003 ms/op
Iteration   3: 2.426 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.415 ±(99.9%) 0.177 ms/op [Average]
  (min, avg, max) = (2.408, 2.415, 2.426), stdev = 0.010
  CI (99.9%): [2.238, 2.592] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.830 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.475 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.431 ±(99.9%) 0.003 ms/op
Iteration   2: 2.436 ±(99.9%) 0.005 ms/op
Iteration   3: 2.435 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.434 ±(99.9%) 0.048 ms/op [Average]
  (min, avg, max) = (2.431, 2.434, 2.436), stdev = 0.003
  CI (99.9%): [2.386, 2.481] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.933 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.004 ms/op
Iteration   1: 2.970 ±(99.9%) 0.005 ms/op
Iteration   2: 2.972 ±(99.9%) 0.005 ms/op
Iteration   3: 2.988 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.977 ±(99.9%) 0.183 ms/op [Average]
  (min, avg, max) = (2.970, 2.977, 2.988), stdev = 0.010
  CI (99.9%): [2.794, 3.159] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.486 ±(99.9%) 0.006 ms/op
Iteration   1: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.146 ms/op
                 createUser·p0.99:   3.641 ms/op
                 createUser·p0.999:  10.223 ms/op
                 createUser·p0.9999: 15.919 ms/op
                 createUser·p1.00:   16.876 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.973 ms/op
                 createUser·p0.50:   2.572 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   3.912 ms/op
                 createUser·p0.999:  8.607 ms/op
                 createUser·p0.9999: 12.550 ms/op
                 createUser·p1.00:   12.747 ms/op

Iteration   3: 2.476 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.133 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  8.765 ms/op
                 createUser·p0.9999: 10.603 ms/op
                 createUser·p1.00:   12.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386016
  mean =      2.485 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 187923 
    [ 2.500,  3.750) = 193847 
    [ 3.750,  5.000) = 3286 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 48 
    [ 8.750, 10.000) = 72 
    [10.000, 11.250) = 95 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.805 ms/op
     p(99.9000) =      8.765 ms/op
     p(99.9900) =     14.477 ms/op
     p(99.9990) =     16.664 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.625 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.448 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.437 ±(99.9%) 0.005 ms/op
Iteration   1: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.538 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  7.549 ms/op
                 existUser·p0.9999: 13.864 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.084 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  6.321 ms/op
                 existUser·p0.9999: 13.058 ms/op
                 existUser·p1.00:   13.304 ms/op

Iteration   3: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.109 ms/op
                 existUser·p0.99:   3.662 ms/op
                 existUser·p0.999:  7.197 ms/op
                 existUser·p0.9999: 11.915 ms/op
                 existUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 390336
  mean =      2.458 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 192192 
    [ 2.500,  3.750) = 195100 
    [ 3.750,  5.000) = 2304 
    [ 5.000,  6.250) = 275 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 43 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.538 ms/op
     p(50.0000) =      2.544 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      3.588 ms/op
     p(99.9000) =      7.192 ms/op
     p(99.9900) =     13.238 ms/op
     p(99.9990) =     14.028 ms/op
     p(99.9999) =     14.123 ms/op
    p(100.0000) =     14.123 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.002 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.526 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.006 ms/op
Iteration   1: 2.451 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.986 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.908 ms/op
                 getUser·p0.999:  6.042 ms/op
                 getUser·p0.9999: 15.301 ms/op
                 getUser·p1.00:   16.318 ms/op

Iteration   2: 2.447 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.930 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.974 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.871 ms/op
                 getUser·p0.999:  7.088 ms/op
                 getUser·p0.9999: 12.747 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   3: 2.432 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.026 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   2.961 ms/op
                 getUser·p0.95:   3.068 ms/op
                 getUser·p0.99:   3.584 ms/op
                 getUser·p0.999:  6.735 ms/op
                 getUser·p0.9999: 10.249 ms/op
                 getUser·p1.00:   11.272 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 392502
  mean =      2.444 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 83 
    [ 1.250,  2.500) = 199215 
    [ 2.500,  3.750) = 188969 
    [ 3.750,  5.000) = 3460 
    [ 5.000,  6.250) = 377 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 100 
    [11.250, 12.500) = 92 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 35 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.974 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      6.644 ms/op
     p(99.9900) =     13.877 ms/op
     p(99.9990) =     16.287 ms/op
     p(99.9999) =     16.318 ms/op
    p(100.0000) =     16.318 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.758 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.003 ±(99.9%) 0.009 ms/op
Iteration   1: 2.986 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.760 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.579 ms/op
                 listUser·p0.999:  9.387 ms/op
                 listUser·p0.9999: 10.584 ms/op
                 listUser·p1.00:   11.092 ms/op

Iteration   2: 2.965 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.480 ms/op
                 listUser·p0.999:  10.342 ms/op
                 listUser·p0.9999: 16.948 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 2.951 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.915 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.350 ms/op
                 listUser·p0.99:   5.513 ms/op
                 listUser·p0.999:  9.235 ms/op
                 listUser·p0.9999: 12.608 ms/op
                 listUser·p1.00:   13.320 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 323164
  mean =      2.967 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 125 
    [ 1.250,  2.500) = 103387 
    [ 2.500,  3.750) = 182431 
    [ 3.750,  5.000) = 30428 
    [ 5.000,  6.250) = 5517 
    [ 6.250,  7.500) = 561 
    [ 7.500,  8.750) = 206 
    [ 8.750, 10.000) = 291 
    [10.000, 11.250) = 116 
    [11.250, 12.500) = 53 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     13.113 ms/op
     p(99.9990) =     17.294 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.769 ± 1.322  ops/ms
ClientPb.existUser                       thrpt       3  13.205 ± 2.647  ops/ms
ClientPb.getUser                         thrpt       3  12.924 ± 2.000  ops/ms
ClientPb.listUser                        thrpt       3  10.801 ± 2.063  ops/ms
ClientPb.createUser                       avgt       3   2.506 ± 0.512   ms/op
ClientPb.existUser                        avgt       3   2.415 ± 0.177   ms/op
ClientPb.getUser                          avgt       3   2.434 ± 0.048   ms/op
ClientPb.listUser                         avgt       3   2.977 ± 0.183   ms/op
ClientPb.createUser                     sample  386016   2.485 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.897           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.015           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.765           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.477           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.876           ms/op
ClientPb.existUser                      sample  390336   2.458 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.538           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.544           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.192           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.123           ms/op
ClientPb.getUser                        sample  392502   2.444 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.930           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.466           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.974           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           6.644           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.877           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.318           ms/op
ClientPb.listUser                       sample  323164   2.967 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.760           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.908           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.846           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.454           ms/op
ClientPb.listUser:listUser·p0.9999      sample          13.113           ms/op
ClientPb.listUser:listUser·p1.00        sample          18.874           ms/op
