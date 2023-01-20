# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.478 ops/ms
# Warmup Iteration   2: 5.815 ops/ms
# Warmup Iteration   3: 9.481 ops/ms
Iteration   1: 9.385 ops/ms
Iteration   2: 9.937 ops/ms
Iteration   3: 9.855 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.726 ±(99.9%) 5.430 ops/ms [Average]
  (min, avg, max) = (9.385, 9.726, 9.937), stdev = 0.298
  CI (99.9%): [4.296, 15.156] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 9.502 ops/ms
# Warmup Iteration   3: 10.189 ops/ms
Iteration   1: 10.148 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.296 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.263 ±(99.9%) 1.872 ops/ms [Average]
  (min, avg, max) = (10.148, 10.263, 10.345), stdev = 0.103
  CI (99.9%): [8.390, 12.135] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ops/ms
# Warmup Iteration   2: 9.452 ops/ms
# Warmup Iteration   3: 10.107 ops/ms
Iteration   1: 10.199 ops/ms
Iteration   2: 9.988 ops/ms
Iteration   3: 10.191 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.126 ±(99.9%) 2.183 ops/ms [Average]
  (min, avg, max) = (9.988, 10.126, 10.199), stdev = 0.120
  CI (99.9%): [7.943, 12.309] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.230 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 8.408 ops/ms
Iteration   1: 8.416 ops/ms
Iteration   2: 8.711 ops/ms
Iteration   3: 8.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.561 ±(99.9%) 2.687 ops/ms [Average]
  (min, avg, max) = (8.416, 8.561, 8.711), stdev = 0.147
  CI (99.9%): [5.874, 11.248] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 8.774 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.409 ±(99.9%) 0.004 ms/op
Iteration   1: 3.252 ±(99.9%) 0.007 ms/op
Iteration   2: 3.210 ±(99.9%) 0.008 ms/op
Iteration   3: 3.224 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.228 ±(99.9%) 0.388 ms/op [Average]
  (min, avg, max) = (3.210, 3.228, 3.252), stdev = 0.021
  CI (99.9%): [2.840, 3.617] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.956 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.181 ±(99.9%) 0.004 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.010 ±(99.9%) 0.008 ms/op
Iteration   3: 3.131 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.061 ±(99.9%) 1.144 ms/op [Average]
  (min, avg, max) = (3.010, 3.061, 3.131), stdev = 0.063
  CI (99.9%): [1.917, 4.205] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.042 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.384 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.005 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
Iteration   2: 3.301 ±(99.9%) 0.005 ms/op
Iteration   3: 3.117 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.192 ±(99.9%) 1.759 ms/op [Average]
  (min, avg, max) = (3.117, 3.192, 3.301), stdev = 0.096
  CI (99.9%): [1.432, 4.951] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.961 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.003 ms/op
Iteration   1: 3.642 ±(99.9%) 0.007 ms/op
Iteration   2: 3.695 ±(99.9%) 0.010 ms/op
Iteration   3: 3.750 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.696 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (3.642, 3.696, 3.750), stdev = 0.054
  CI (99.9%): [2.711, 4.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 7.470 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 3.594 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.008 ms/op
Iteration   1: 3.298 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.850 ms/op
                 createUser·p0.95:   4.751 ms/op
                 createUser·p0.99:   6.273 ms/op
                 createUser·p0.999:  10.285 ms/op
                 createUser·p0.9999: 19.637 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.186 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.694 ms/op
                 createUser·p0.99:   6.111 ms/op
                 createUser·p0.999:  18.123 ms/op
                 createUser·p0.9999: 22.509 ms/op
                 createUser·p1.00:   23.134 ms/op

Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.430 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   6.152 ms/op
                 createUser·p0.999:  14.806 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294961
  mean =      3.255 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14249 
    [ 2.500,  5.000) = 270719 
    [ 5.000,  7.500) = 9013 
    [ 7.500, 10.000) = 493 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.432 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     14.749 ms/op
     p(99.9900) =     22.086 ms/op
     p(99.9990) =     22.908 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.980 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.407 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.008 ms/op
Iteration   1: 3.117 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.432 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   5.161 ms/op
                 existUser·p0.999:  10.551 ms/op
                 existUser·p0.9999: 20.414 ms/op
                 existUser·p1.00:   22.151 ms/op

Iteration   2: 3.080 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.620 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.473 ms/op
                 existUser·p0.99:   5.726 ms/op
                 existUser·p0.999:  12.943 ms/op
                 existUser·p0.9999: 19.700 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   3: 3.201 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.077 ms/op
                 existUser·p0.50:   3.150 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  17.859 ms/op
                 existUser·p0.9999: 21.267 ms/op
                 existUser·p1.00:   23.134 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306393
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23327 
    [ 2.500,  5.000) = 278033 
    [ 5.000,  7.500) = 4207 
    [ 7.500, 10.000) = 380 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 42 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 169 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.480 ms/op
     p(99.9000) =     16.630 ms/op
     p(99.9900) =     20.677 ms/op
     p(99.9990) =     22.795 ms/op
     p(99.9999) =     23.134 ms/op
    p(100.0000) =     23.134 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.674 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.380 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.010 ms/op
Iteration   1: 3.236 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   6.390 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   2: 3.191 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.499 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   5.292 ms/op
                 getUser·p0.999:  11.613 ms/op
                 getUser·p0.9999: 24.245 ms/op
                 getUser·p1.00:   25.002 ms/op

Iteration   3: 3.104 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.247 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.666 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  16.712 ms/op
                 getUser·p0.9999: 22.577 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 302099
  mean =      3.176 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20807 
    [ 2.500,  5.000) = 274496 
    [ 5.000,  7.500) = 5878 
    [ 7.500, 10.000) = 480 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 78 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.899 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     16.728 ms/op
     p(99.9900) =     24.300 ms/op
     p(99.9990) =     26.016 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.839 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.803 ±(99.9%) 0.012 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.625 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.811 ms/op
                 listUser·p0.9999: 19.609 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 3.796 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.025 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 16.377 ms/op
                 listUser·p1.00:   16.466 ms/op

Iteration   3: 3.823 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.175 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.211 ms/op
                 listUser·p0.95:   4.648 ms/op
                 listUser·p0.99:   7.168 ms/op
                 listUser·p0.999:  13.959 ms/op
                 listUser·p0.9999: 19.399 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253774
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 243943 
    [ 5.000,  7.500) = 7897 
    [ 7.500, 10.000) = 1135 
    [10.000, 12.500) = 253 
    [12.500, 15.000) = 281 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.307 ms/op
     p(50.0000) =      3.699 ms/op
     p(90.0000) =      4.129 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.959 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     20.561 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.726 ± 5.430  ops/ms
ClientPb.existUser                       thrpt       3  10.263 ± 1.872  ops/ms
ClientPb.getUser                         thrpt       3  10.126 ± 2.183  ops/ms
ClientPb.listUser                        thrpt       3   8.561 ± 2.687  ops/ms
ClientPb.createUser                       avgt       3   3.228 ± 0.388   ms/op
ClientPb.existUser                        avgt       3   3.061 ± 1.144   ms/op
ClientPb.getUser                          avgt       3   3.192 ± 1.759   ms/op
ClientPb.listUser                         avgt       3   3.696 ± 0.985   ms/op
ClientPb.createUser                     sample  294961   3.255 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.677           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.105           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.801           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.432           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.749           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.086           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.134           ms/op
ClientPb.existUser                      sample  306393   3.132 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.077           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.416           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.480           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.630           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.677           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.134           ms/op
ClientPb.getUser                        sample  302099   3.176 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.723           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.097           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.572           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.728           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.300           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.051           ms/op
ClientPb.listUser                       sample  253774   3.783 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.307           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.699           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.129           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.959           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.268           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.611           ms/op
