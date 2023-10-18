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
# Warmup Iteration   1: 1.915 ops/ms
# Warmup Iteration   2: 4.809 ops/ms
# Warmup Iteration   3: 8.699 ops/ms
Iteration   1: 9.004 ops/ms
Iteration   2: 9.230 ops/ms
Iteration   3: 9.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.170 ±(99.9%) 2.654 ops/ms [Average]
  (min, avg, max) = (9.004, 9.170, 9.275), stdev = 0.145
  CI (99.9%): [6.515, 11.824] (assumes normal distribution)


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
# Warmup Iteration   1: 3.210 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 9.384 ops/ms
Iteration   1: 9.428 ops/ms
Iteration   2: 9.488 ops/ms
Iteration   3: 9.460 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.459 ±(99.9%) 0.545 ops/ms [Average]
  (min, avg, max) = (9.428, 9.459, 9.488), stdev = 0.030
  CI (99.9%): [8.914, 10.004] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.558 ops/ms
# Warmup Iteration   2: 7.875 ops/ms
# Warmup Iteration   3: 9.015 ops/ms
Iteration   1: 9.236 ops/ms
Iteration   2: 9.374 ops/ms
Iteration   3: 9.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.265 ±(99.9%) 1.774 ops/ms [Average]
  (min, avg, max) = (9.186, 9.265, 9.374), stdev = 0.097
  CI (99.9%): [7.492, 11.039] (assumes normal distribution)


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
# Warmup Iteration   1: 2.511 ops/ms
# Warmup Iteration   2: 7.203 ops/ms
# Warmup Iteration   3: 7.526 ops/ms
Iteration   1: 7.644 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.792 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.754 ±(99.9%) 1.776 ops/ms [Average]
  (min, avg, max) = (7.644, 7.754, 7.827), stdev = 0.097
  CI (99.9%): [5.978, 9.531] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.038 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.865 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.003 ms/op
Iteration   1: 3.568 ±(99.9%) 0.004 ms/op
Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
Iteration   3: 3.486 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.516 ±(99.9%) 0.829 ms/op [Average]
  (min, avg, max) = (3.486, 3.516, 3.568), stdev = 0.045
  CI (99.9%): [2.686, 4.345] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.562 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.500 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.426 ±(99.9%) 0.004 ms/op
Iteration   1: 3.356 ±(99.9%) 0.003 ms/op
Iteration   2: 3.311 ±(99.9%) 0.004 ms/op
Iteration   3: 3.335 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.334 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (3.311, 3.334, 3.356), stdev = 0.023
  CI (99.9%): [2.923, 3.745] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 10.556 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.539 ±(99.9%) 0.002 ms/op
Iteration   1: 3.532 ±(99.9%) 0.003 ms/op
Iteration   2: 3.528 ±(99.9%) 0.002 ms/op
Iteration   3: 3.472 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.511 ±(99.9%) 0.610 ms/op [Average]
  (min, avg, max) = (3.472, 3.511, 3.532), stdev = 0.033
  CI (99.9%): [2.901, 4.120] (assumes normal distribution)


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
# Warmup Iteration   1: 11.318 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.442 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.104 ±(99.9%) 0.006 ms/op
Iteration   1: 4.217 ±(99.9%) 0.006 ms/op
Iteration   2: 4.109 ±(99.9%) 0.004 ms/op
Iteration   3: 4.144 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.157 ±(99.9%) 1.001 ms/op [Average]
  (min, avg, max) = (4.109, 4.157, 4.217), stdev = 0.055
  CI (99.9%): [3.155, 5.158] (assumes normal distribution)


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
# Warmup Iteration   1: 10.379 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 3.974 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.717 ±(99.9%) 0.013 ms/op
Iteration   1: 3.431 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.303 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.157 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  19.293 ms/op
                 createUser·p0.9999: 23.900 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 3.471 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.274 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.006 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.047 ms/op
                 createUser·p0.999:  20.742 ms/op
                 createUser·p0.9999: 27.380 ms/op
                 createUser·p1.00:   29.393 ms/op

Iteration   3: 3.459 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.371 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.178 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  19.541 ms/op
                 createUser·p0.9999: 25.697 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277969
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7449 
    [ 2.500,  5.000) = 265964 
    [ 5.000,  7.500) = 3289 
    [ 7.500, 10.000) = 688 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 103 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.190 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =     19.531 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     29.152 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 7.538 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.479 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.507 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.083 ms/op
                 existUser·p0.50:   3.207 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  17.355 ms/op
                 existUser·p0.9999: 21.109 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   2: 3.396 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.887 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.128 ms/op
                 existUser·p0.999:  10.830 ms/op
                 existUser·p0.9999: 22.320 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   3: 3.458 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   4.018 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  17.498 ms/op
                 existUser·p0.9999: 28.442 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 282783
  mean =      3.394 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3999 
    [ 2.500,  5.000) = 272329 
    [ 5.000,  7.500) = 5610 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.083 ms/op
     p(50.0000) =      3.248 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     26.238 ms/op
     p(99.9990) =     29.488 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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
# Warmup Iteration   1: 9.951 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.587 ±(99.9%) 0.011 ms/op
Iteration   1: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.137 ms/op
                 getUser·p0.50:   3.346 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   6.865 ms/op
                 getUser·p0.999:  21.299 ms/op
                 getUser·p0.9999: 24.707 ms/op
                 getUser·p1.00:   25.428 ms/op

Iteration   2: 3.446 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.952 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.846 ms/op
                 getUser·p0.95:   4.096 ms/op
                 getUser·p0.99:   5.799 ms/op
                 getUser·p0.999:  21.866 ms/op
                 getUser·p0.9999: 24.525 ms/op
                 getUser·p1.00:   25.133 ms/op

Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.323 ms/op
                 getUser·p0.50:   3.322 ms/op
                 getUser·p0.90:   4.022 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  17.925 ms/op
                 getUser·p0.9999: 25.290 ms/op
                 getUser·p1.00:   27.066 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 275563
  mean =      3.480 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4686 
    [ 2.500,  5.000) = 264410 
    [ 5.000,  7.500) = 5296 
    [ 7.500, 10.000) = 635 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 64 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 179 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     20.363 ms/op
     p(99.9900) =     24.885 ms/op
     p(99.9990) =     25.968 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


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
# Warmup Iteration   1: 10.458 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.012 ms/op
Iteration   1: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.825 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.234 ms/op
                 listUser·p0.999:  19.615 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   23.167 ms/op

Iteration   2: 4.248 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.632 ms/op
                 listUser·p0.50:   4.141 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.120 ms/op
                 listUser·p0.99:   7.228 ms/op
                 listUser·p0.999:  15.178 ms/op
                 listUser·p0.9999: 19.574 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   3: 4.097 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.400 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.513 ms/op
                 listUser·p0.999:  14.238 ms/op
                 listUser·p0.9999: 15.843 ms/op
                 listUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 231588
  mean =      4.142 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 221859 
    [ 5.000,  7.500) = 8073 
    [ 7.500, 10.000) = 800 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 297 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.632 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.907 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     15.466 ms/op
     p(99.9900) =     22.048 ms/op
     p(99.9990) =     22.907 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.170 ± 2.654  ops/ms
ClientPb.existUser                       thrpt       3   9.459 ± 0.545  ops/ms
ClientPb.getUser                         thrpt       3   9.265 ± 1.774  ops/ms
ClientPb.listUser                        thrpt       3   7.754 ± 1.776  ops/ms
ClientPb.createUser                       avgt       3   3.516 ± 0.829   ms/op
ClientPb.existUser                        avgt       3   3.334 ± 0.411   ms/op
ClientPb.getUser                          avgt       3   3.511 ± 0.610   ms/op
ClientPb.listUser                         avgt       3   4.157 ± 1.001   ms/op
ClientPb.createUser                     sample  277969   3.454 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.274           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.924           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.190           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.882           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.531           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.393           ms/op
ClientPb.existUser                      sample  282783   3.394 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.083           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.248           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.871           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.202           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.111           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.043           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.238           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  275563   3.480 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.137           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.062           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.363           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.885           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.066           ms/op
ClientPb.listUser                       sample  231588   4.142 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.632           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.010           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.907           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.466           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.048           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.167           ms/op
