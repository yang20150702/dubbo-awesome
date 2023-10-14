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
# Warmup Iteration   1: 2.397 ops/ms
# Warmup Iteration   2: 5.494 ops/ms
# Warmup Iteration   3: 9.167 ops/ms
Iteration   1: 9.865 ops/ms
Iteration   2: 9.820 ops/ms
Iteration   3: 9.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.789 ±(99.9%) 1.739 ops/ms [Average]
  (min, avg, max) = (9.682, 9.789, 9.865), stdev = 0.095
  CI (99.9%): [8.050, 11.528] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.778 ops/ms
# Warmup Iteration   2: 9.629 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.291 ops/ms
Iteration   2: 10.252 ops/ms
Iteration   3: 10.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.229 ±(99.9%) 1.392 ops/ms [Average]
  (min, avg, max) = (10.144, 10.229, 10.291), stdev = 0.076
  CI (99.9%): [8.837, 11.621] (assumes normal distribution)


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
# Warmup Iteration   1: 3.644 ops/ms
# Warmup Iteration   2: 9.317 ops/ms
# Warmup Iteration   3: 10.151 ops/ms
Iteration   1: 9.780 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 9.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.997 ±(99.9%) 4.550 ops/ms [Average]
  (min, avg, max) = (9.780, 9.997, 10.269), stdev = 0.249
  CI (99.9%): [5.447, 14.547] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.737 ops/ms
# Warmup Iteration   2: 7.621 ops/ms
# Warmup Iteration   3: 8.308 ops/ms
Iteration   1: 8.264 ops/ms
Iteration   2: 8.394 ops/ms
Iteration   3: 8.354 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.337 ±(99.9%) 1.213 ops/ms [Average]
  (min, avg, max) = (8.264, 8.337, 8.394), stdev = 0.066
  CI (99.9%): [7.124, 9.550] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 8.617 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.537 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.005 ms/op
Iteration   1: 3.295 ±(99.9%) 0.005 ms/op
Iteration   2: 3.468 ±(99.9%) 0.003 ms/op
Iteration   3: 3.308 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.357 ±(99.9%) 1.753 ms/op [Average]
  (min, avg, max) = (3.295, 3.357, 3.468), stdev = 0.096
  CI (99.9%): [1.604, 5.110] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.966 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.294 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.003 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.004 ms/op
Iteration   3: 3.160 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.130 ±(99.9%) 0.509 ms/op [Average]
  (min, avg, max) = (3.105, 3.130, 3.160), stdev = 0.028
  CI (99.9%): [2.620, 3.639] (assumes normal distribution)


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
# Warmup Iteration   1: 8.561 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.602 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.271 ±(99.9%) 0.002 ms/op
Iteration   2: 3.208 ±(99.9%) 0.003 ms/op
Iteration   3: 3.211 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.230 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.208, 3.230, 3.271), stdev = 0.035
  CI (99.9%): [2.584, 3.875] (assumes normal distribution)


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
# Warmup Iteration   1: 8.920 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.128 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.826 ±(99.9%) 0.004 ms/op
Iteration   1: 3.799 ±(99.9%) 0.006 ms/op
Iteration   2: 3.785 ±(99.9%) 0.005 ms/op
Iteration   3: 3.871 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.819 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.785, 3.819, 3.871), stdev = 0.046
  CI (99.9%): [2.976, 4.661] (assumes normal distribution)


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
# Warmup Iteration   1: 7.946 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.016 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.010 ms/op
Iteration   1: 3.238 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.579 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.489 ms/op
                 createUser·p0.999:  18.809 ms/op
                 createUser·p0.9999: 20.906 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   2: 3.292 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  15.068 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   3: 3.241 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.805 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  15.283 ms/op
                 createUser·p0.9999: 18.912 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294311
  mean =      3.257 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17091 
    [ 2.500,  5.000) = 273051 
    [ 5.000,  7.500) = 3421 
    [ 7.500, 10.000) = 189 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =     16.723 ms/op
     p(99.9900) =     21.304 ms/op
     p(99.9990) =     22.905 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.847 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.382 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.218 ±(99.9%) 0.008 ms/op
Iteration   1: 3.200 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.886 ms/op
                 existUser·p0.99:   5.235 ms/op
                 existUser·p0.999:  16.105 ms/op
                 existUser·p0.9999: 19.171 ms/op
                 existUser·p1.00:   20.480 ms/op

Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.088 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  11.993 ms/op
                 existUser·p0.9999: 22.118 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.227 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.368 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   5.480 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 20.233 ms/op
                 existUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 300370
  mean =      3.195 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15071 
    [ 2.500,  5.000) = 279750 
    [ 5.000,  7.500) = 4753 
    [ 7.500, 10.000) = 330 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 175 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     12.780 ms/op
     p(99.9900) =     20.970 ms/op
     p(99.9990) =     22.217 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 7.328 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 3.400 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.009 ms/op
Iteration   1: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  16.458 ms/op
                 getUser·p0.9999: 20.152 ms/op
                 getUser·p1.00:   20.644 ms/op

Iteration   2: 3.204 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  19.899 ms/op
                 getUser·p0.9999: 22.675 ms/op
                 getUser·p1.00:   23.462 ms/op

Iteration   3: 3.254 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.227 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   5.626 ms/op
                 getUser·p0.999:  8.618 ms/op
                 getUser·p0.9999: 20.207 ms/op
                 getUser·p1.00:   21.529 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294883
  mean =      3.253 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6015 
    [ 2.500,  5.000) = 283449 
    [ 5.000,  7.500) = 4599 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 70 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.961 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      6.021 ms/op
     p(99.9000) =     15.330 ms/op
     p(99.9900) =     22.020 ms/op
     p(99.9990) =     23.269 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 8.689 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.874 ±(99.9%) 0.011 ms/op
Iteration   1: 3.862 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.917 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.383 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 21.074 ms/op
                 listUser·p1.00:   22.512 ms/op

Iteration   2: 3.838 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.699 ms/op
                 listUser·p0.90:   4.145 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  13.084 ms/op
                 listUser·p0.9999: 16.438 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.807 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.404 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   6.537 ms/op
                 listUser·p0.999:  13.402 ms/op
                 listUser·p0.9999: 14.778 ms/op
                 listUser·p1.00:   14.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250295
  mean =      3.835 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 77 
    [ 2.500,  5.000) = 243344 
    [ 5.000,  7.500) = 5289 
    [ 7.500, 10.000) = 835 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 352 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.917 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     13.156 ms/op
     p(99.9900) =     19.817 ms/op
     p(99.9990) =     22.167 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.789 ± 1.739  ops/ms
ClientPb.existUser                       thrpt       3  10.229 ± 1.392  ops/ms
ClientPb.getUser                         thrpt       3   9.997 ± 4.550  ops/ms
ClientPb.listUser                        thrpt       3   8.337 ± 1.213  ops/ms
ClientPb.createUser                       avgt       3   3.357 ± 1.753   ms/op
ClientPb.existUser                        avgt       3   3.130 ± 0.509   ms/op
ClientPb.getUser                          avgt       3   3.230 ± 0.646   ms/op
ClientPb.listUser                         avgt       3   3.819 ± 0.842   ms/op
ClientPb.createUser                     sample  294311   3.257 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.711           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.633           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.497           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.723           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.527           ms/op
ClientPb.existUser                      sample  300370   3.195 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.793           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.559           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.867           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.780           ms/op
ClientPb.existUser:existUser·p0.9999    sample          20.970           ms/op
ClientPb.existUser:existUser·p1.00      sample          22.807           ms/op
ClientPb.getUser                        sample  294883   3.253 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.961           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.613           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.817           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.021           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.330           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.020           ms/op
ClientPb.getUser:getUser·p1.00          sample          23.462           ms/op
ClientPb.listUser                       sample  250295   3.835 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.917           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.709           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.156           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.817           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.512           ms/op
