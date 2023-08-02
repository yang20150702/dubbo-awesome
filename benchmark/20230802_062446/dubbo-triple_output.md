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
# Warmup Iteration   1: 2.521 ops/ms
# Warmup Iteration   2: 6.021 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.846 ops/ms
Iteration   2: 9.621 ops/ms
Iteration   3: 10.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.830 ±(99.9%) 3.664 ops/ms [Average]
  (min, avg, max) = (9.621, 9.830, 10.022), stdev = 0.201
  CI (99.9%): [6.166, 13.493] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.654 ops/ms
# Warmup Iteration   2: 9.440 ops/ms
# Warmup Iteration   3: 9.977 ops/ms
Iteration   1: 10.449 ops/ms
Iteration   2: 10.197 ops/ms
Iteration   3: 10.050 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.232 ±(99.9%) 3.677 ops/ms [Average]
  (min, avg, max) = (10.050, 10.232, 10.449), stdev = 0.202
  CI (99.9%): [6.555, 13.909] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.190 ops/ms
# Warmup Iteration   2: 9.272 ops/ms
# Warmup Iteration   3: 9.349 ops/ms
Iteration   1: 9.844 ops/ms
Iteration   2: 10.372 ops/ms
Iteration   3: 9.713 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.976 ±(99.9%) 6.365 ops/ms [Average]
  (min, avg, max) = (9.713, 9.976, 10.372), stdev = 0.349
  CI (99.9%): [3.611, 16.341] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.140 ops/ms
# Warmup Iteration   2: 7.272 ops/ms
# Warmup Iteration   3: 8.332 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.337 ±(99.9%) 1.729 ops/ms [Average]
  (min, avg, max) = (8.239, 8.337, 8.428), stdev = 0.095
  CI (99.9%): [6.608, 10.065] (assumes normal distribution)


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
# Warmup Iteration   1: 7.809 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.586 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.337 ±(99.9%) 0.007 ms/op
Iteration   1: 3.350 ±(99.9%) 0.005 ms/op
Iteration   2: 3.209 ±(99.9%) 0.006 ms/op
Iteration   3: 3.121 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.227 ±(99.9%) 2.108 ms/op [Average]
  (min, avg, max) = (3.121, 3.227, 3.350), stdev = 0.116
  CI (99.9%): [1.119, 5.334] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.525 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.275 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.149 ±(99.9%) 0.005 ms/op
Iteration   1: 3.234 ±(99.9%) 0.007 ms/op
Iteration   2: 3.231 ±(99.9%) 0.007 ms/op
Iteration   3: 3.173 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.213 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.173, 3.213, 3.234), stdev = 0.034
  CI (99.9%): [2.590, 3.835] (assumes normal distribution)


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
# Warmup Iteration   1: 8.312 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.545 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.004 ms/op
Iteration   1: 3.212 ±(99.9%) 0.004 ms/op
Iteration   2: 3.222 ±(99.9%) 0.003 ms/op
Iteration   3: 3.259 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.231 ±(99.9%) 0.449 ms/op [Average]
  (min, avg, max) = (3.212, 3.231, 3.259), stdev = 0.025
  CI (99.9%): [2.782, 3.680] (assumes normal distribution)


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
# Warmup Iteration   1: 8.669 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.254 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.005 ms/op
Iteration   1: 3.855 ±(99.9%) 0.004 ms/op
Iteration   2: 3.830 ±(99.9%) 0.006 ms/op
Iteration   3: 3.847 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.844 ±(99.9%) 0.238 ms/op [Average]
  (min, avg, max) = (3.830, 3.844, 3.855), stdev = 0.013
  CI (99.9%): [3.606, 4.082] (assumes normal distribution)


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
# Warmup Iteration   1: 8.190 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.697 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.010 ms/op
Iteration   1: 3.282 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.281 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   5.448 ms/op
                 createUser·p0.999:  8.968 ms/op
                 createUser·p0.9999: 24.945 ms/op
                 createUser·p1.00:   25.952 ms/op

Iteration   2: 3.285 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.531 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   4.104 ms/op
                 createUser·p0.99:   6.683 ms/op
                 createUser·p0.999:  21.398 ms/op
                 createUser·p0.9999: 24.177 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.398 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.551 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.137 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  15.890 ms/op
                 createUser·p0.9999: 19.562 ms/op
                 createUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 288919
  mean =      3.321 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19566 
    [ 2.500,  5.000) = 262852 
    [ 5.000,  7.500) = 5175 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 79 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      5.915 ms/op
     p(99.9000) =     16.351 ms/op
     p(99.9900) =     24.383 ms/op
     p(99.9990) =     25.952 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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
# Warmup Iteration   1: 6.767 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 3.374 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.008 ms/op
Iteration   1: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.333 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.689 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  18.572 ms/op
                 existUser·p0.9999: 21.342 ms/op
                 existUser·p1.00:   22.413 ms/op

Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  12.749 ms/op
                 existUser·p0.9999: 21.299 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.213 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   3.121 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   4.059 ms/op
                 existUser·p0.99:   5.595 ms/op
                 existUser·p0.999:  11.108 ms/op
                 existUser·p0.9999: 32.606 ms/op
                 existUser·p1.00:   33.948 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304073
  mean =      3.155 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12684 
    [ 2.500,  5.000) = 284377 
    [ 5.000,  7.500) = 5794 
    [ 7.500, 10.000) = 680 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     13.499 ms/op
     p(99.9900) =     30.611 ms/op
     p(99.9990) =     33.062 ms/op
     p(99.9999) =     33.948 ms/op
    p(100.0000) =     33.948 ms/op


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
# Warmup Iteration   1: 8.413 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 3.402 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.219 ±(99.9%) 0.009 ms/op
Iteration   1: 3.282 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   4.432 ms/op
                 getUser·p0.99:   7.283 ms/op
                 getUser·p0.999:  15.671 ms/op
                 getUser·p0.9999: 22.290 ms/op
                 getUser·p1.00:   23.495 ms/op

Iteration   2: 3.342 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.395 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.481 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  20.290 ms/op
                 getUser·p0.9999: 22.493 ms/op
                 getUser·p1.00:   23.953 ms/op

Iteration   3: 3.273 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.444 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   6.316 ms/op
                 getUser·p0.999:  12.720 ms/op
                 getUser·p0.9999: 26.935 ms/op
                 getUser·p1.00:   28.410 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 290960
  mean =      3.298 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18089 
    [ 2.500,  5.000) = 262269 
    [ 5.000,  7.500) = 8759 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 122 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.736 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     14.304 ms/op
     p(99.9900) =     25.940 ms/op
     p(99.9990) =     28.121 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 8.542 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.967 ±(99.9%) 0.013 ms/op
Iteration   1: 3.809 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.245 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.051 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.438 ms/op
                 listUser·p0.999:  15.501 ms/op
                 listUser·p0.9999: 19.681 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 3.884 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   7.659 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.135 ms/op

Iteration   3: 3.828 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.471 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 14.942 ms/op
                 listUser·p1.00:   14.975 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 249621
  mean =      3.840 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 239630 
    [ 5.000,  7.500) = 7365 
    [ 7.500, 10.000) = 1785 
    [10.000, 12.500) = 263 
    [12.500, 15.000) = 312 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.030 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.596 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     14.402 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     21.103 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.830 ± 3.664  ops/ms
ClientPb.existUser                       thrpt       3  10.232 ± 3.677  ops/ms
ClientPb.getUser                         thrpt       3   9.976 ± 6.365  ops/ms
ClientPb.listUser                        thrpt       3   8.337 ± 1.729  ops/ms
ClientPb.createUser                       avgt       3   3.227 ± 2.108   ms/op
ClientPb.existUser                        avgt       3   3.213 ± 0.622   ms/op
ClientPb.getUser                          avgt       3   3.231 ± 0.449   ms/op
ClientPb.listUser                         avgt       3   3.844 ± 0.238   ms/op
ClientPb.createUser                     sample  288919   3.321 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.531           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.727           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.067           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.915           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.351           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.383           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.149           ms/op
ClientPb.existUser                      sample  304073   3.155 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.428           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.498           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.051           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.499           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.611           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.948           ms/op
ClientPb.getUser                        sample  290960   3.298 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.395           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.736           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.366           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.660           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.304           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.940           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.410           ms/op
ClientPb.listUser                       sample  249621   3.840 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.030           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.740           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.219           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.402           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.021           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.135           ms/op
