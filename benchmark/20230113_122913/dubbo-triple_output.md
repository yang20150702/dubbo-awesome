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
# Warmup Iteration   1: 2.413 ops/ms
# Warmup Iteration   2: 6.467 ops/ms
# Warmup Iteration   3: 9.222 ops/ms
Iteration   1: 9.772 ops/ms
Iteration   2: 9.654 ops/ms
Iteration   3: 9.990 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.805 ±(99.9%) 3.110 ops/ms [Average]
  (min, avg, max) = (9.654, 9.805, 9.990), stdev = 0.170
  CI (99.9%): [6.695, 12.915] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.301 ops/ms
# Warmup Iteration   2: 9.368 ops/ms
# Warmup Iteration   3: 10.035 ops/ms
Iteration   1: 10.521 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.421 ±(99.9%) 3.073 ops/ms [Average]
  (min, avg, max) = (10.226, 10.421, 10.521), stdev = 0.168
  CI (99.9%): [7.348, 13.493] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.291 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 10.096 ops/ms
Iteration   1: 9.963 ops/ms
Iteration   2: 9.660 ops/ms
Iteration   3: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.785 ±(99.9%) 2.891 ops/ms [Average]
  (min, avg, max) = (9.660, 9.785, 9.963), stdev = 0.158
  CI (99.9%): [6.894, 12.676] (assumes normal distribution)


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
# Warmup Iteration   1: 3.430 ops/ms
# Warmup Iteration   2: 7.812 ops/ms
# Warmup Iteration   3: 8.391 ops/ms
Iteration   1: 8.812 ops/ms
Iteration   2: 8.396 ops/ms
Iteration   3: 8.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.612 ±(99.9%) 3.809 ops/ms [Average]
  (min, avg, max) = (8.396, 8.612, 8.812), stdev = 0.209
  CI (99.9%): [4.803, 12.421] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.549 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.349 ±(99.9%) 0.007 ms/op
Iteration   1: 3.291 ±(99.9%) 0.007 ms/op
Iteration   2: 3.033 ±(99.9%) 0.007 ms/op
Iteration   3: 3.163 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.163 ±(99.9%) 2.355 ms/op [Average]
  (min, avg, max) = (3.033, 3.163, 3.291), stdev = 0.129
  CI (99.9%): [0.808, 5.518] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 6.720 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.347 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.006 ms/op
Iteration   1: 3.086 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.042 ±(99.9%) 0.696 ms/op [Average]
  (min, avg, max) = (3.015, 3.042, 3.086), stdev = 0.038
  CI (99.9%): [2.346, 3.739] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.710 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.239 ±(99.9%) 0.003 ms/op
Iteration   1: 3.232 ±(99.9%) 0.006 ms/op
Iteration   2: 3.270 ±(99.9%) 0.007 ms/op
Iteration   3: 3.295 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.266 ±(99.9%) 0.572 ms/op [Average]
  (min, avg, max) = (3.232, 3.266, 3.295), stdev = 0.031
  CI (99.9%): [2.693, 3.838] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.052 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.005 ms/op
Iteration   1: 3.731 ±(99.9%) 0.009 ms/op
Iteration   2: 3.736 ±(99.9%) 0.005 ms/op
Iteration   3: 3.618 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.695 ±(99.9%) 1.218 ms/op [Average]
  (min, avg, max) = (3.618, 3.695, 3.736), stdev = 0.067
  CI (99.9%): [2.477, 4.912] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 7.753 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 3.619 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.008 ms/op
Iteration   1: 3.101 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.217 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.318 ms/op
                 createUser·p0.95:   3.723 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 19.825 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   2: 3.184 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   5.505 ms/op
                 createUser·p0.999:  12.970 ms/op
                 createUser·p0.9999: 27.229 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 3.090 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.237 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.277 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   5.333 ms/op
                 createUser·p0.999:  15.934 ms/op
                 createUser·p0.9999: 25.220 ms/op
                 createUser·p1.00:   27.886 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 307010
  mean =      3.124 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11816 
    [ 2.500,  5.000) = 288087 
    [ 5.000,  7.500) = 6344 
    [ 7.500, 10.000) = 323 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 158 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 46 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =     15.548 ms/op
     p(99.9900) =     26.519 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     28.180 ms/op
    p(100.0000) =     28.180 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 6.611 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.397 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.129 ±(99.9%) 0.008 ms/op
Iteration   1: 3.020 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.236 ms/op
                 existUser·p0.95:   3.457 ms/op
                 existUser·p0.99:   5.325 ms/op
                 existUser·p0.999:  9.535 ms/op
                 existUser·p0.9999: 20.526 ms/op
                 existUser·p1.00:   22.544 ms/op

Iteration   2: 3.119 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   4.016 ms/op
                 existUser·p0.99:   6.210 ms/op
                 existUser·p0.999:  13.484 ms/op
                 existUser·p0.9999: 22.912 ms/op
                 existUser·p1.00:   24.805 ms/op

Iteration   3: 3.018 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.315 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.330 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.832 ms/op
                 existUser·p0.9999: 27.492 ms/op
                 existUser·p1.00:   27.820 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 314426
  mean =      3.052 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15697 
    [ 2.500,  5.000) = 293576 
    [ 5.000,  7.500) = 4455 
    [ 7.500, 10.000) = 345 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.574 ms/op
     p(99.9900) =     26.724 ms/op
     p(99.9990) =     27.492 ms/op
     p(99.9999) =     27.820 ms/op
    p(100.0000) =     27.820 ms/op


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
# Warmup Iteration   1: 7.555 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.555 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
Iteration   1: 3.125 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.270 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.379 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   5.710 ms/op
                 getUser·p0.999:  15.155 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 3.293 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.630 ms/op
                 getUser·p0.50:   3.224 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  10.812 ms/op
                 getUser·p0.9999: 24.457 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.157 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.233 ms/op
                 getUser·p0.50:   3.064 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   5.809 ms/op
                 getUser·p0.999:  15.254 ms/op
                 getUser·p0.9999: 21.594 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300569
  mean =      3.190 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7794 
    [ 2.500,  5.000) = 287650 
    [ 5.000,  7.500) = 4192 
    [ 7.500, 10.000) = 416 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.233 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     15.162 ms/op
     p(99.9900) =     23.394 ms/op
     p(99.9990) =     24.936 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 8.697 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.050 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.013 ms/op
Iteration   1: 3.693 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   3.969 ms/op
                 listUser·p0.95:   4.190 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.950 ms/op
                 listUser·p0.9999: 19.639 ms/op
                 listUser·p1.00:   20.414 ms/op

Iteration   2: 3.708 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.014 ms/op
                 listUser·p0.95:   4.202 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  13.517 ms/op
                 listUser·p0.9999: 15.221 ms/op
                 listUser·p1.00:   15.352 ms/op

Iteration   3: 3.762 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.167 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   3.994 ms/op
                 listUser·p0.95:   4.219 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  16.105 ms/op
                 listUser·p0.9999: 20.089 ms/op
                 listUser·p1.00:   20.873 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 257725
  mean =      3.721 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 250641 
    [ 5.000,  7.500) = 4962 
    [ 7.500, 10.000) = 1397 
    [10.000, 12.500) = 275 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      3.998 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.988 ms/op
     p(99.9000) =     13.997 ms/op
     p(99.9900) =     19.209 ms/op
     p(99.9990) =     20.822 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.805 ± 3.110  ops/ms
ClientPb.existUser                       thrpt       3  10.421 ± 3.073  ops/ms
ClientPb.getUser                         thrpt       3   9.785 ± 2.891  ops/ms
ClientPb.listUser                        thrpt       3   8.612 ± 3.809  ops/ms
ClientPb.createUser                       avgt       3   3.163 ± 2.355   ms/op
ClientPb.existUser                        avgt       3   3.042 ± 0.696   ms/op
ClientPb.getUser                          avgt       3   3.266 ± 0.572   ms/op
ClientPb.listUser                         avgt       3   3.695 ± 1.218   ms/op
ClientPb.createUser                     sample  307010   3.124 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.778           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.998           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.420           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.464           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.548           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.519           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.180           ms/op
ClientPb.existUser                      sample  314426   3.052 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.760           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.506           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.472           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.574           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.724           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.820           ms/op
ClientPb.getUser                        sample  300569   3.190 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.233           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.092           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.531           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.162           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.394           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  257725   3.721 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.049           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.998           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.202           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.988           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.997           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.209           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.873           ms/op
