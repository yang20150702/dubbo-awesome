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
# Warmup Iteration   1: 2.733 ops/ms
# Warmup Iteration   2: 6.760 ops/ms
# Warmup Iteration   3: 9.293 ops/ms
Iteration   1: 9.717 ops/ms
Iteration   2: 9.434 ops/ms
Iteration   3: 9.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.639 ±(99.9%) 3.278 ops/ms [Average]
  (min, avg, max) = (9.434, 9.639, 9.767), stdev = 0.180
  CI (99.9%): [6.361, 12.917] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ops/ms
# Warmup Iteration   2: 8.849 ops/ms
# Warmup Iteration   3: 9.715 ops/ms
Iteration   1: 9.902 ops/ms
Iteration   2: 10.287 ops/ms
Iteration   3: 10.455 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.215 ±(99.9%) 5.175 ops/ms [Average]
  (min, avg, max) = (9.902, 10.215, 10.455), stdev = 0.284
  CI (99.9%): [5.040, 15.390] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.768 ops/ms
# Warmup Iteration   2: 9.127 ops/ms
# Warmup Iteration   3: 9.155 ops/ms
Iteration   1: 10.015 ops/ms
Iteration   2: 10.066 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.945 ±(99.9%) 3.042 ops/ms [Average]
  (min, avg, max) = (9.755, 9.945, 10.066), stdev = 0.167
  CI (99.9%): [6.903, 12.988] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.584 ops/ms
# Warmup Iteration   2: 7.778 ops/ms
# Warmup Iteration   3: 8.329 ops/ms
Iteration   1: 8.404 ops/ms
Iteration   2: 8.356 ops/ms
Iteration   3: 8.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.454 ±(99.9%) 2.381 ops/ms [Average]
  (min, avg, max) = (8.356, 8.454, 8.603), stdev = 0.131
  CI (99.9%): [6.073, 10.836] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.805 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.590 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.464 ±(99.9%) 0.008 ms/op
Iteration   1: 3.367 ±(99.9%) 0.003 ms/op
Iteration   2: 3.221 ±(99.9%) 0.006 ms/op
Iteration   3: 3.231 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.273 ±(99.9%) 1.491 ms/op [Average]
  (min, avg, max) = (3.221, 3.273, 3.367), stdev = 0.082
  CI (99.9%): [1.782, 4.764] (assumes normal distribution)


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
# Warmup Iteration   1: 7.152 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.189 ±(99.9%) 0.005 ms/op
Iteration   1: 3.328 ±(99.9%) 0.003 ms/op
Iteration   2: 3.158 ±(99.9%) 0.007 ms/op
Iteration   3: 3.129 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.205 ±(99.9%) 1.962 ms/op [Average]
  (min, avg, max) = (3.129, 3.205, 3.328), stdev = 0.108
  CI (99.9%): [1.243, 5.166] (assumes normal distribution)


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
# Warmup Iteration   1: 8.135 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.440 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.440 ±(99.9%) 0.003 ms/op
Iteration   1: 3.423 ±(99.9%) 0.007 ms/op
Iteration   2: 3.326 ±(99.9%) 0.009 ms/op
Iteration   3: 3.221 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.323 ±(99.9%) 1.845 ms/op [Average]
  (min, avg, max) = (3.221, 3.323, 3.423), stdev = 0.101
  CI (99.9%): [1.479, 5.168] (assumes normal distribution)


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
# Warmup Iteration   1: 9.172 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.185 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.798 ±(99.9%) 0.006 ms/op
Iteration   1: 3.764 ±(99.9%) 0.007 ms/op
Iteration   2: 3.733 ±(99.9%) 0.007 ms/op
Iteration   3: 3.872 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.790 ±(99.9%) 1.328 ms/op [Average]
  (min, avg, max) = (3.733, 3.790, 3.872), stdev = 0.073
  CI (99.9%): [2.462, 5.117] (assumes normal distribution)


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
# Warmup Iteration   1: 8.137 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.707 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.010 ms/op
Iteration   1: 3.230 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   6.742 ms/op
                 createUser·p0.999:  11.959 ms/op
                 createUser·p0.9999: 20.296 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   2: 3.272 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   6.021 ms/op
                 createUser·p0.999:  17.475 ms/op
                 createUser·p0.9999: 23.263 ms/op
                 createUser·p1.00:   23.691 ms/op

Iteration   3: 3.180 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.090 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.527 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   5.497 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 25.656 ms/op
                 createUser·p1.00:   26.640 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 297235
  mean =      3.227 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13320 
    [ 2.500,  5.000) = 277018 
    [ 5.000,  7.500) = 5482 
    [ 7.500, 10.000) = 977 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     23.809 ms/op
     p(99.9990) =     26.314 ms/op
     p(99.9999) =     26.640 ms/op
    p(100.0000) =     26.640 ms/op


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
# Warmup Iteration   1: 7.927 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 3.465 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
Iteration   1: 3.241 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.871 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.579 ms/op
                 existUser·p0.999:  19.604 ms/op
                 existUser·p0.9999: 26.191 ms/op
                 existUser·p1.00:   28.901 ms/op

Iteration   2: 3.161 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.591 ms/op
                 existUser·p0.50:   2.974 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   4.309 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  9.814 ms/op
                 existUser·p0.9999: 27.948 ms/op
                 existUser·p1.00:   28.967 ms/op

Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.895 ms/op
                 existUser·p0.99:   6.087 ms/op
                 existUser·p0.999:  9.343 ms/op
                 existUser·p0.9999: 22.899 ms/op
                 existUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301515
  mean =      3.182 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16486 
    [ 2.500,  5.000) = 275822 
    [ 5.000,  7.500) = 8072 
    [ 7.500, 10.000) = 781 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 65 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.292 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      6.250 ms/op
     p(99.9000) =     18.216 ms/op
     p(99.9900) =     26.850 ms/op
     p(99.9990) =     28.868 ms/op
     p(99.9999) =     28.967 ms/op
    p(100.0000) =     28.967 ms/op


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
# Warmup Iteration   1: 8.806 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.574 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.285 ±(99.9%) 0.009 ms/op
Iteration   1: 3.308 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.988 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   4.137 ms/op
                 getUser·p0.99:   6.660 ms/op
                 getUser·p0.999:  18.678 ms/op
                 getUser·p0.9999: 27.241 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.849 ms/op
                 getUser·p0.999:  10.152 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   3: 3.249 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.139 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   6.439 ms/op
                 getUser·p0.999:  12.016 ms/op
                 getUser·p0.9999: 22.779 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 293418
  mean =      3.270 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8307 
    [ 2.500,  5.000) = 275103 
    [ 5.000,  7.500) = 8577 
    [ 7.500, 10.000) = 1020 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 170 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.988 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     17.138 ms/op
     p(99.9900) =     25.963 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 9.140 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.353 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.915 ±(99.9%) 0.014 ms/op
Iteration   1: 3.819 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.137 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  15.929 ms/op
                 listUser·p0.9999: 21.635 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   2: 3.819 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  13.848 ms/op
                 listUser·p0.9999: 23.921 ms/op
                 listUser·p1.00:   23.986 ms/op

Iteration   3: 3.975 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.286 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  13.193 ms/op
                 listUser·p0.9999: 17.537 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 248078
  mean =      3.870 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 72 
    [ 2.500,  5.000) = 237147 
    [ 5.000,  7.500) = 8387 
    [ 7.500, 10.000) = 1701 
    [10.000, 12.500) = 293 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.397 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     21.607 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.639 ± 3.278  ops/ms
ClientPb.existUser                       thrpt       3  10.215 ± 5.175  ops/ms
ClientPb.getUser                         thrpt       3   9.945 ± 3.042  ops/ms
ClientPb.listUser                        thrpt       3   8.454 ± 2.381  ops/ms
ClientPb.createUser                       avgt       3   3.273 ± 1.491   ms/op
ClientPb.existUser                        avgt       3   3.205 ± 1.962   ms/op
ClientPb.getUser                          avgt       3   3.323 ± 1.845   ms/op
ClientPb.listUser                         avgt       3   3.790 ± 1.328   ms/op
ClientPb.createUser                     sample  297235   3.227 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.656           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.193           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.236           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.809           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.640           ms/op
ClientPb.existUser                      sample  301515   3.182 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.292           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.060           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.551           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.211           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.250           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.216           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.850           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.967           ms/op
ClientPb.getUser                        sample  293418   3.270 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.988           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.963           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  248078   3.870 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.397           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.731           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.284           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.496           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.303           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.607           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.986           ms/op
