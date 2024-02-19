# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.854 ops/ms
# Warmup Iteration   2: 12.349 ops/ms
# Warmup Iteration   3: 12.512 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 12.748 ops/ms
Iteration   3: 12.861 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.741 ±(99.9%) 2.252 ops/ms [Average]
  (min, avg, max) = (12.615, 12.741, 12.861), stdev = 0.123
  CI (99.9%): [10.490, 14.993] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 8.620 ops/ms
# Warmup Iteration   2: 13.299 ops/ms
# Warmup Iteration   3: 13.029 ops/ms
Iteration   1: 13.294 ops/ms
Iteration   2: 13.218 ops/ms
Iteration   3: 13.249 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.254 ±(99.9%) 0.697 ops/ms [Average]
  (min, avg, max) = (13.218, 13.254, 13.294), stdev = 0.038
  CI (99.9%): [12.557, 13.950] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ops/ms
# Warmup Iteration   2: 12.735 ops/ms
# Warmup Iteration   3: 12.933 ops/ms
Iteration   1: 12.948 ops/ms
Iteration   2: 13.063 ops/ms
Iteration   3: 13.017 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.009 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (12.948, 13.009, 13.063), stdev = 0.058
  CI (99.9%): [11.959, 14.059] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.816 ops/ms
# Warmup Iteration   2: 10.725 ops/ms
# Warmup Iteration   3: 10.841 ops/ms
Iteration   1: 10.807 ops/ms
Iteration   2: 10.965 ops/ms
Iteration   3: 10.924 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.899 ±(99.9%) 1.490 ops/ms [Average]
  (min, avg, max) = (10.807, 10.899, 10.965), stdev = 0.082
  CI (99.9%): [9.409, 12.389] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.967 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.573 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.503 ±(99.9%) 0.004 ms/op
Iteration   1: 2.523 ±(99.9%) 0.004 ms/op
Iteration   2: 2.515 ±(99.9%) 0.004 ms/op
Iteration   3: 2.497 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.512 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (2.497, 2.512, 2.523), stdev = 0.014
  CI (99.9%): [2.263, 2.760] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.605 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.407 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.434 ±(99.9%) 0.004 ms/op
Iteration   1: 2.422 ±(99.9%) 0.004 ms/op
Iteration   2: 2.418 ±(99.9%) 0.004 ms/op
Iteration   3: 2.423 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.421 ±(99.9%) 0.055 ms/op [Average]
  (min, avg, max) = (2.418, 2.421, 2.423), stdev = 0.003
  CI (99.9%): [2.366, 2.476] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.571 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.509 ±(99.9%) 0.005 ms/op
Iteration   2: 2.495 ±(99.9%) 0.003 ms/op
Iteration   3: 2.500 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.501 ±(99.9%) 0.134 ms/op [Average]
  (min, avg, max) = (2.495, 2.501, 2.509), stdev = 0.007
  CI (99.9%): [2.368, 2.635] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.682 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.975 ±(99.9%) 0.005 ms/op
Iteration   1: 2.958 ±(99.9%) 0.005 ms/op
Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
Iteration   3: 2.950 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.957 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (2.950, 2.957, 2.962), stdev = 0.006
  CI (99.9%): [2.847, 3.066] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.239 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.641 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.488 ±(99.9%) 0.006 ms/op
Iteration   1: 2.465 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.990 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   2.986 ms/op
                 createUser·p0.95:   3.092 ms/op
                 createUser·p0.99:   3.547 ms/op
                 createUser·p0.999:  6.401 ms/op
                 createUser·p0.9999: 13.387 ms/op
                 createUser·p1.00:   14.008 ms/op

Iteration   2: 2.474 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.449 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 12.879 ms/op
                 createUser·p1.00:   13.124 ms/op

Iteration   3: 2.488 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  8.179 ms/op
                 createUser·p0.9999: 10.858 ms/op
                 createUser·p1.00:   11.387 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 387478
  mean =      2.475 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 187613 
    [ 2.500,  3.750) = 196267 
    [ 3.750,  5.000) = 2633 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 150 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 95 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     12.931 ms/op
     p(99.9990) =     13.806 ms/op
     p(99.9999) =     14.008 ms/op
    p(100.0000) =     14.008 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.671 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.416 ±(99.9%) 0.005 ms/op
Iteration   1: 2.395 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.865 ms/op
                 existUser·p0.50:   2.449 ms/op
                 existUser·p0.90:   2.904 ms/op
                 existUser·p0.95:   3.002 ms/op
                 existUser·p0.99:   3.555 ms/op
                 existUser·p0.999:  6.668 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 2.409 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.031 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  7.846 ms/op
                 existUser·p0.9999: 13.164 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.412 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.919 ms/op
                 existUser·p0.50:   2.466 ms/op
                 existUser·p0.90:   2.933 ms/op
                 existUser·p0.95:   3.052 ms/op
                 existUser·p0.99:   3.690 ms/op
                 existUser·p0.999:  6.865 ms/op
                 existUser·p0.9999: 11.960 ms/op
                 existUser·p1.00:   12.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 398824
  mean =      2.405 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203266 
    [ 2.500,  5.000) = 194928 
    [ 5.000,  7.500) = 236 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.865 ms/op
     p(50.0000) =      2.466 ms/op
     p(90.0000) =      2.920 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      3.584 ms/op
     p(99.9000) =      7.083 ms/op
     p(99.9900) =     13.730 ms/op
     p(99.9990) =     20.480 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.853 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.515 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.478 ±(99.9%) 0.006 ms/op
Iteration   1: 2.482 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.744 ms/op
                 getUser·p0.999:  7.122 ms/op
                 getUser·p0.9999: 13.783 ms/op
                 getUser·p1.00:   14.090 ms/op

Iteration   2: 2.507 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.815 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.207 ms/op
                 getUser·p0.99:   4.121 ms/op
                 getUser·p0.999:  9.509 ms/op
                 getUser·p0.9999: 12.685 ms/op
                 getUser·p1.00:   13.730 ms/op

Iteration   3: 2.483 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.166 ms/op
                 getUser·p0.99:   3.949 ms/op
                 getUser·p0.999:  7.226 ms/op
                 getUser·p0.9999: 11.676 ms/op
                 getUser·p1.00:   14.729 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 385114
  mean =      2.491 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 191760 
    [ 2.500,  3.750) = 188183 
    [ 3.750,  5.000) = 3956 
    [ 5.000,  6.250) = 662 
    [ 6.250,  7.500) = 54 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 42 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 92 
    [13.750, 15.000) = 21 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.815 ms/op
     p(50.0000) =      2.507 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      7.755 ms/op
     p(99.9900) =     13.230 ms/op
     p(99.9990) =     14.406 ms/op
     p(99.9999) =     14.729 ms/op
    p(100.0000) =     14.729 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.712 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.026 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.008 ms/op
Iteration   1: 2.962 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.830 ms/op
                 listUser·p0.50:   2.904 ms/op
                 listUser·p0.90:   3.809 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  8.930 ms/op
                 listUser·p0.9999: 10.469 ms/op
                 listUser·p1.00:   11.010 ms/op

Iteration   2: 2.950 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.997 ms/op
                 listUser·p0.50:   2.892 ms/op
                 listUser·p0.90:   3.789 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   5.431 ms/op
                 listUser·p0.999:  9.316 ms/op
                 listUser·p0.9999: 11.004 ms/op
                 listUser·p1.00:   11.747 ms/op

Iteration   3: 2.932 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   0.773 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   3.773 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  8.651 ms/op
                 listUser·p0.9999: 9.798 ms/op
                 listUser·p1.00:   12.042 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 325367
  mean =      2.948 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 159 
    [ 1.250,  2.500) = 101696 
    [ 2.500,  3.750) = 188964 
    [ 3.750,  5.000) = 28417 
    [ 5.000,  6.250) = 4992 
    [ 6.250,  7.500) = 500 
    [ 7.500,  8.750) = 263 
    [ 8.750, 10.000) = 303 
    [10.000, 11.250) = 62 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      8.978 ms/op
     p(99.9900) =     10.715 ms/op
     p(99.9990) =     11.747 ms/op
     p(99.9999) =     12.042 ms/op
    p(100.0000) =     12.042 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.741 ± 2.252  ops/ms
ClientPb.existUser                       thrpt       3  13.254 ± 0.697  ops/ms
ClientPb.getUser                         thrpt       3  13.009 ± 1.050  ops/ms
ClientPb.listUser                        thrpt       3  10.899 ± 1.490  ops/ms
ClientPb.createUser                       avgt       3   2.512 ± 0.249   ms/op
ClientPb.existUser                        avgt       3   2.421 ± 0.055   ms/op
ClientPb.getUser                          avgt       3   2.501 ± 0.134   ms/op
ClientPb.listUser                         avgt       3   2.957 ± 0.110   ms/op
ClientPb.createUser                     sample  387478   2.475 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.897           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.002           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.117           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.978           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.008           ms/op
ClientPb.existUser                      sample  398824   2.405 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.865           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.466           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.920           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.584           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.083           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.730           ms/op
ClientPb.existUser:existUser·p1.00      sample          20.546           ms/op
ClientPb.getUser                        sample  385114   2.491 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.815           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.507           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.755           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.230           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.729           ms/op
ClientPb.listUser                       sample  325367   2.948 ± 0.004   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.892           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.789           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.423           ms/op
ClientPb.listUser:listUser·p0.999       sample           8.978           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.715           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.042           ms/op
