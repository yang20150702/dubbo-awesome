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
# Warmup Iteration   1: 2.432 ops/ms
# Warmup Iteration   2: 5.414 ops/ms
# Warmup Iteration   3: 8.948 ops/ms
Iteration   1: 9.226 ops/ms
Iteration   2: 9.853 ops/ms
Iteration   3: 9.960 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.680 ±(99.9%) 7.240 ops/ms [Average]
  (min, avg, max) = (9.226, 9.680, 9.960), stdev = 0.397
  CI (99.9%): [2.440, 16.920] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ops/ms
# Warmup Iteration   2: 9.253 ops/ms
# Warmup Iteration   3: 10.003 ops/ms
Iteration   1: 10.043 ops/ms
Iteration   2: 10.174 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.182 ±(99.9%) 2.627 ops/ms [Average]
  (min, avg, max) = (10.043, 10.182, 10.330), stdev = 0.144
  CI (99.9%): [7.555, 12.809] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.603 ops/ms
# Warmup Iteration   2: 8.718 ops/ms
# Warmup Iteration   3: 9.631 ops/ms
Iteration   1: 9.866 ops/ms
Iteration   2: 9.780 ops/ms
Iteration   3: 9.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.774 ±(99.9%) 1.723 ops/ms [Average]
  (min, avg, max) = (9.677, 9.774, 9.866), stdev = 0.094
  CI (99.9%): [8.051, 11.497] (assumes normal distribution)


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
# Warmup Iteration   1: 3.057 ops/ms
# Warmup Iteration   2: 7.546 ops/ms
# Warmup Iteration   3: 8.146 ops/ms
Iteration   1: 8.240 ops/ms
Iteration   2: 8.362 ops/ms
Iteration   3: 8.291 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.298 ±(99.9%) 1.121 ops/ms [Average]
  (min, avg, max) = (8.240, 8.298, 8.362), stdev = 0.061
  CI (99.9%): [7.177, 9.419] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.842 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.004 ms/op
Iteration   1: 3.239 ±(99.9%) 0.002 ms/op
Iteration   2: 3.257 ±(99.9%) 0.005 ms/op
Iteration   3: 3.297 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.264 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (3.239, 3.264, 3.297), stdev = 0.030
  CI (99.9%): [2.722, 3.806] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.188 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.385 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.004 ms/op
Iteration   2: 3.215 ±(99.9%) 0.003 ms/op
Iteration   3: 3.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.166 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.122, 3.166, 3.215), stdev = 0.047
  CI (99.9%): [2.310, 4.022] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 8.443 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.360 ±(99.9%) 0.003 ms/op
Iteration   1: 3.310 ±(99.9%) 0.002 ms/op
Iteration   2: 3.246 ±(99.9%) 0.005 ms/op
Iteration   3: 3.239 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.265 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (3.239, 3.265, 3.310), stdev = 0.039
  CI (99.9%): [2.546, 3.984] (assumes normal distribution)


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
# Warmup Iteration   1: 8.949 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.002 ms/op
Iteration   1: 3.813 ±(99.9%) 0.006 ms/op
Iteration   2: 3.830 ±(99.9%) 0.005 ms/op
Iteration   3: 3.802 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.815 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (3.802, 3.815, 3.830), stdev = 0.014
  CI (99.9%): [3.556, 4.074] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 8.580 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.009 ms/op
Iteration   1: 3.322 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.019 ms/op
                 createUser·p0.99:   5.980 ms/op
                 createUser·p0.999:  17.413 ms/op
                 createUser·p0.9999: 20.636 ms/op
                 createUser·p1.00:   21.529 ms/op

Iteration   2: 3.305 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.407 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.554 ms/op
                 createUser·p0.999:  21.324 ms/op
                 createUser·p0.9999: 23.361 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   3: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.255 ms/op
                 createUser·p0.50:   3.285 ms/op
                 createUser·p0.90:   3.760 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  16.974 ms/op
                 createUser·p0.9999: 22.747 ms/op
                 createUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288706
  mean =      3.320 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18679 
    [ 2.500,  5.000) = 265028 
    [ 5.000,  7.500) = 3790 
    [ 7.500, 10.000) = 594 
    [10.000, 12.500) = 163 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 132 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.281 ms/op
     p(90.0000) =      3.719 ms/op
     p(95.0000) =      3.985 ms/op
     p(99.0000) =      5.652 ms/op
     p(99.9000) =     17.573 ms/op
     p(99.9900) =     22.881 ms/op
     p(99.9990) =     23.953 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 7.377 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.204 ±(99.9%) 0.008 ms/op
Iteration   1: 3.140 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.317 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  13.208 ms/op
                 existUser·p0.9999: 20.324 ms/op
                 existUser·p1.00:   20.578 ms/op

Iteration   2: 3.169 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.983 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   3.654 ms/op
                 existUser·p0.99:   4.757 ms/op
                 existUser·p0.999:  13.021 ms/op
                 existUser·p0.9999: 23.688 ms/op
                 existUser·p1.00:   24.150 ms/op

Iteration   3: 3.363 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.608 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.850 ms/op
                 existUser·p0.95:   4.243 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  13.746 ms/op
                 existUser·p0.9999: 21.610 ms/op
                 existUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297969
  mean =      3.221 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15259 
    [ 2.500,  5.000) = 277284 
    [ 5.000,  7.500) = 4505 
    [ 7.500, 10.000) = 310 
    [10.000, 12.500) = 245 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 95 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.983 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     13.239 ms/op
     p(99.9900) =     22.387 ms/op
     p(99.9990) =     23.955 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 8.340 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.475 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
Iteration   1: 3.248 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.518 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  16.630 ms/op
                 getUser·p0.9999: 21.108 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.218 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.176 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   5.175 ms/op
                 getUser·p0.999:  8.847 ms/op
                 getUser·p0.9999: 21.629 ms/op
                 getUser·p1.00:   22.610 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.266 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   6.087 ms/op
                 getUser·p0.999:  14.549 ms/op
                 getUser·p0.9999: 21.108 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295721
  mean =      3.244 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6506 
    [ 2.500,  5.000) = 283826 
    [ 5.000,  7.500) = 4451 
    [ 7.500, 10.000) = 393 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.128 ms/op
     p(50.0000) =      3.142 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     14.980 ms/op
     p(99.9900) =     21.393 ms/op
     p(99.9990) =     22.513 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.118 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.866 ±(99.9%) 0.010 ms/op
Iteration   1: 3.816 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.162 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   6.660 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 20.893 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 3.881 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.391 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.569 ms/op
                 listUser·p0.999:  14.100 ms/op
                 listUser·p0.9999: 16.499 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.783 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.494 ms/op
                 listUser·p0.50:   3.711 ms/op
                 listUser·p0.90:   4.100 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   6.447 ms/op
                 listUser·p0.999:  12.239 ms/op
                 listUser·p0.9999: 13.837 ms/op
                 listUser·p1.00:   16.105 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 250922
  mean =      3.826 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 73 
    [ 2.500,  5.000) = 243840 
    [ 5.000,  7.500) = 5381 
    [ 7.500, 10.000) = 846 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 254 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.391 ms/op
     p(50.0000) =      3.719 ms/op
     p(90.0000) =      4.153 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     13.911 ms/op
     p(99.9900) =     19.947 ms/op
     p(99.9990) =     21.757 ms/op
     p(99.9999) =     22.249 ms/op
    p(100.0000) =     22.249 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.680 ± 7.240  ops/ms
ClientPb.existUser                       thrpt       3  10.182 ± 2.627  ops/ms
ClientPb.getUser                         thrpt       3   9.774 ± 1.723  ops/ms
ClientPb.listUser                        thrpt       3   8.298 ± 1.121  ops/ms
ClientPb.createUser                       avgt       3   3.264 ± 0.542   ms/op
ClientPb.existUser                        avgt       3   3.166 ± 0.856   ms/op
ClientPb.getUser                          avgt       3   3.265 ± 0.719   ms/op
ClientPb.listUser                         avgt       3   3.815 ± 0.259   ms/op
ClientPb.createUser                     sample  288706   3.320 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.653           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.281           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.719           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.573           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.881           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.953           ms/op
ClientPb.existUser                      sample  297969   3.221 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.983           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.146           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.920           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.702           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.239           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.387           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.150           ms/op
ClientPb.getUser                        sample  295721   3.244 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.128           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.142           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.551           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.825           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.980           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.393           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.610           ms/op
ClientPb.listUser                       sample  250922   3.826 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.391           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.719           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.153           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.911           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.947           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.249           ms/op
