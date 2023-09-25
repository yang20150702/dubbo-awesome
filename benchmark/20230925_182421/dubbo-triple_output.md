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
# Warmup Iteration   1: 2.610 ops/ms
# Warmup Iteration   2: 5.843 ops/ms
# Warmup Iteration   3: 9.113 ops/ms
Iteration   1: 9.594 ops/ms
Iteration   2: 9.384 ops/ms
Iteration   3: 9.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.539 ±(99.9%) 2.488 ops/ms [Average]
  (min, avg, max) = (9.384, 9.539, 9.640), stdev = 0.136
  CI (99.9%): [7.051, 12.027] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.581 ops/ms
# Warmup Iteration   2: 9.105 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 10.142 ops/ms
Iteration   2: 10.408 ops/ms
Iteration   3: 9.944 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.165 ±(99.9%) 4.252 ops/ms [Average]
  (min, avg, max) = (9.944, 10.165, 10.408), stdev = 0.233
  CI (99.9%): [5.913, 14.416] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.554 ops/ms
# Warmup Iteration   2: 9.149 ops/ms
# Warmup Iteration   3: 9.753 ops/ms
Iteration   1: 9.800 ops/ms
Iteration   2: 9.905 ops/ms
Iteration   3: 9.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.862 ±(99.9%) 1.002 ops/ms [Average]
  (min, avg, max) = (9.800, 9.862, 9.905), stdev = 0.055
  CI (99.9%): [8.859, 10.864] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.306 ops/ms
# Warmup Iteration   2: 7.679 ops/ms
# Warmup Iteration   3: 7.891 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.262 ops/ms
Iteration   3: 8.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.213 ±(99.9%) 1.599 ops/ms [Average]
  (min, avg, max) = (8.112, 8.213, 8.265), stdev = 0.088
  CI (99.9%): [6.614, 9.812] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.971 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.004 ms/op
Iteration   1: 3.293 ±(99.9%) 0.004 ms/op
Iteration   2: 3.295 ±(99.9%) 0.008 ms/op
Iteration   3: 3.292 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.293 ±(99.9%) 0.021 ms/op [Average]
  (min, avg, max) = (3.292, 3.293, 3.295), stdev = 0.001
  CI (99.9%): [3.272, 3.315] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.883 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.455 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.005 ms/op
Iteration   1: 3.134 ±(99.9%) 0.006 ms/op
Iteration   2: 3.159 ±(99.9%) 0.006 ms/op
Iteration   3: 3.225 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.173 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (3.134, 3.173, 3.225), stdev = 0.047
  CI (99.9%): [2.313, 4.033] (assumes normal distribution)


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
# Warmup Iteration   1: 9.157 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.599 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.384 ±(99.9%) 0.003 ms/op
Iteration   1: 3.293 ±(99.9%) 0.002 ms/op
Iteration   2: 3.304 ±(99.9%) 0.002 ms/op
Iteration   3: 3.295 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.297 ±(99.9%) 0.111 ms/op [Average]
  (min, avg, max) = (3.293, 3.297, 3.304), stdev = 0.006
  CI (99.9%): [3.186, 3.408] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.343 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.229 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.006 ms/op
Iteration   1: 3.920 ±(99.9%) 0.004 ms/op
Iteration   2: 3.930 ±(99.9%) 0.005 ms/op
Iteration   3: 3.871 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.907 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (3.871, 3.907, 3.930), stdev = 0.032
  CI (99.9%): [3.324, 4.490] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.013 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.750 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.341 ms/op
                 createUser·p0.999:  17.203 ms/op
                 createUser·p0.9999: 18.584 ms/op
                 createUser·p1.00:   20.480 ms/op

Iteration   2: 3.296 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   5.596 ms/op
                 createUser·p0.999:  11.238 ms/op
                 createUser·p0.9999: 21.384 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.278 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  15.450 ms/op
                 createUser·p0.9999: 23.757 ms/op
                 createUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293316
  mean =      3.274 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14975 
    [ 2.500,  5.000) = 274007 
    [ 5.000,  7.500) = 3525 
    [ 7.500, 10.000) = 257 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.904 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.489 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     23.901 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 7.742 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 3.446 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.007 ms/op
Iteration   1: 3.200 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  11.600 ms/op
                 existUser·p0.9999: 20.152 ms/op
                 existUser·p1.00:   21.299 ms/op

Iteration   2: 3.173 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.104 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   5.022 ms/op
                 existUser·p0.999:  17.727 ms/op
                 existUser·p0.9999: 22.735 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   3: 3.191 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.268 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 24.639 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301192
  mean =      3.188 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13596 
    [ 2.500,  5.000) = 283268 
    [ 5.000,  7.500) = 3740 
    [ 7.500, 10.000) = 158 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     13.025 ms/op
     p(99.9900) =     23.053 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 8.263 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.541 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.439 ±(99.9%) 0.010 ms/op
Iteration   1: 3.327 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.651 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.849 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 26.161 ms/op
                 getUser·p1.00:   26.411 ms/op

Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.252 ms/op
                 getUser·p0.999:  14.516 ms/op
                 getUser·p0.9999: 23.200 ms/op
                 getUser·p1.00:   24.379 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.235 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.501 ms/op
                 getUser·p0.999:  15.188 ms/op
                 getUser·p0.9999: 23.418 ms/op
                 getUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 291256
  mean =      3.296 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8736 
    [ 2.500,  5.000) = 275767 
    [ 5.000,  7.500) = 5528 
    [ 7.500, 10.000) = 577 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.651 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      6.533 ms/op
     p(99.9000) =     17.359 ms/op
     p(99.9900) =     24.084 ms/op
     p(99.9990) =     26.321 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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
# Warmup Iteration   1: 8.946 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.289 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.968 ±(99.9%) 0.012 ms/op
Iteration   1: 3.934 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.780 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.497 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  15.369 ms/op
                 listUser·p0.9999: 19.722 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 3.883 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.921 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.407 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  13.435 ms/op
                 listUser·p0.9999: 15.037 ms/op
                 listUser·p1.00:   15.647 ms/op

Iteration   3: 4.031 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.109 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   7.362 ms/op
                 listUser·p0.999:  14.494 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   21.496 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242914
  mean =      3.948 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 60 
    [ 2.500,  5.000) = 235956 
    [ 5.000,  7.500) = 5177 
    [ 7.500, 10.000) = 939 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 371 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     14.565 ms/op
     p(99.9900) =     19.029 ms/op
     p(99.9990) =     22.399 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.539 ± 2.488  ops/ms
ClientPb.existUser                       thrpt       3  10.165 ± 4.252  ops/ms
ClientPb.getUser                         thrpt       3   9.862 ± 1.002  ops/ms
ClientPb.listUser                        thrpt       3   8.213 ± 1.599  ops/ms
ClientPb.createUser                       avgt       3   3.293 ± 0.021   ms/op
ClientPb.existUser                        avgt       3   3.173 ± 0.860   ms/op
ClientPb.getUser                          avgt       3   3.297 ± 0.111   ms/op
ClientPb.listUser                         avgt       3   3.907 ± 0.583   ms/op
ClientPb.createUser                     sample  293316   3.274 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.904           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.629           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.489           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.170           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.495           ms/op
ClientPb.createUser:createUser·p1.00    sample          24.576           ms/op
ClientPb.existUser                      sample  301192   3.188 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.104           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.142           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.752           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.025           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.053           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.199           ms/op
ClientPb.getUser                        sample  291256   3.296 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.651           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.609           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.533           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.359           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.084           ms/op
ClientPb.getUser:getUser·p1.00          sample          26.411           ms/op
ClientPb.listUser                       sample  242914   3.948 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.921           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.822           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.565           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.029           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.577           ms/op
