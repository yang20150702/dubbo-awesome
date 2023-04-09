# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.651 ops/ms
# Warmup Iteration   3: 8.895 ops/ms
Iteration   1: 9.287 ops/ms
Iteration   2: 9.377 ops/ms
Iteration   3: 9.631 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.432 ±(99.9%) 3.257 ops/ms [Average]
  (min, avg, max) = (9.287, 9.432, 9.631), stdev = 0.179
  CI (99.9%): [6.175, 12.689] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.177 ops/ms
# Warmup Iteration   2: 8.874 ops/ms
# Warmup Iteration   3: 9.371 ops/ms
Iteration   1: 9.739 ops/ms
Iteration   2: 9.920 ops/ms
Iteration   3: 9.666 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.775 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (9.666, 9.775, 9.920), stdev = 0.131
  CI (99.9%): [7.388, 12.162] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.147 ops/ms
# Warmup Iteration   2: 8.598 ops/ms
# Warmup Iteration   3: 9.281 ops/ms
Iteration   1: 9.369 ops/ms
Iteration   2: 9.254 ops/ms
Iteration   3: 9.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.417 ±(99.9%) 3.478 ops/ms [Average]
  (min, avg, max) = (9.254, 9.417, 9.627), stdev = 0.191
  CI (99.9%): [5.938, 12.895] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.819 ops/ms
# Warmup Iteration   2: 7.385 ops/ms
# Warmup Iteration   3: 7.879 ops/ms
Iteration   1: 8.041 ops/ms
Iteration   2: 8.023 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.093 ±(99.9%) 1.944 ops/ms [Average]
  (min, avg, max) = (8.023, 8.093, 8.216), stdev = 0.107
  CI (99.9%): [6.149, 10.038] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.184 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.622 ±(99.9%) 0.011 ms/op
Iteration   1: 3.494 ±(99.9%) 0.006 ms/op
Iteration   2: 3.421 ±(99.9%) 0.004 ms/op
Iteration   3: 3.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.440 ±(99.9%) 0.867 ms/op [Average]
  (min, avg, max) = (3.404, 3.440, 3.494), stdev = 0.048
  CI (99.9%): [2.573, 4.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.575 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.007 ms/op
Iteration   1: 3.342 ±(99.9%) 0.011 ms/op
Iteration   2: 3.232 ±(99.9%) 0.006 ms/op
Iteration   3: 3.312 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.295 ±(99.9%) 1.035 ms/op [Average]
  (min, avg, max) = (3.232, 3.295, 3.342), stdev = 0.057
  CI (99.9%): [2.260, 4.330] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.104 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.891 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.401 ±(99.9%) 0.003 ms/op
Iteration   1: 3.411 ±(99.9%) 0.001 ms/op
Iteration   2: 3.476 ±(99.9%) 0.006 ms/op
Iteration   3: 3.375 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.421 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.375, 3.421, 3.476), stdev = 0.052
  CI (99.9%): [2.479, 4.362] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.189 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.360 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.868 ±(99.9%) 0.012 ms/op
Iteration   2: 4.052 ±(99.9%) 0.005 ms/op
Iteration   3: 4.275 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.065 ±(99.9%) 3.715 ms/op [Average]
  (min, avg, max) = (3.868, 4.065, 4.275), stdev = 0.204
  CI (99.9%): [0.350, 7.780] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.134 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.565 ±(99.9%) 0.011 ms/op
Iteration   1: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   6.356 ms/op
                 createUser·p0.999:  18.353 ms/op
                 createUser·p0.9999: 20.742 ms/op
                 createUser·p1.00:   21.627 ms/op

Iteration   2: 3.450 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.153 ms/op
                 createUser·p0.50:   3.346 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.242 ms/op
                 createUser·p0.999:  22.446 ms/op
                 createUser·p0.9999: 37.928 ms/op
                 createUser·p1.00:   38.470 ms/op

Iteration   3: 3.477 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.741 ms/op
                 createUser·p0.50:   3.301 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.374 ms/op
                 createUser·p0.99:   6.911 ms/op
                 createUser·p0.999:  20.176 ms/op
                 createUser·p0.9999: 27.329 ms/op
                 createUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278638
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5677 
    [ 2.500,  5.000) = 265050 
    [ 5.000,  7.500) = 6671 
    [ 7.500, 10.000) = 692 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 108 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.908 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     19.509 ms/op
     p(99.9900) =     34.546 ms/op
     p(99.9990) =     38.287 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.180 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 3.716 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.322 ±(99.9%) 0.008 ms/op
Iteration   1: 3.397 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.405 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.100 ms/op
                 existUser·p0.99:   5.972 ms/op
                 existUser·p0.999:  19.366 ms/op
                 existUser·p0.9999: 25.143 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 3.292 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.571 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  17.039 ms/op
                 existUser·p0.9999: 29.903 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   3: 3.369 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   6.283 ms/op
                 existUser·p0.999:  17.891 ms/op
                 existUser·p0.9999: 24.708 ms/op
                 existUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 286160
  mean =      3.352 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6752 
    [ 2.500,  5.000) = 273933 
    [ 5.000,  7.500) = 4641 
    [ 7.500, 10.000) = 468 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.325 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.965 ms/op
     p(99.0000) =      5.988 ms/op
     p(99.9000) =     17.891 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.370 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.357 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.607 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.011 ms/op
Iteration   1: 3.345 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.466 ms/op
                 getUser·p0.50:   3.215 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  16.433 ms/op
                 getUser·p0.9999: 22.741 ms/op
                 getUser·p1.00:   23.888 ms/op

Iteration   2: 3.297 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.391 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.658 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   4.731 ms/op
                 getUser·p0.999:  17.769 ms/op
                 getUser·p0.9999: 25.919 ms/op
                 getUser·p1.00:   26.935 ms/op

Iteration   3: 3.484 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.964 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   4.059 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.959 ms/op
                 getUser·p0.999:  19.539 ms/op
                 getUser·p0.9999: 35.377 ms/op
                 getUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284449
  mean =      3.374 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11496 
    [ 2.500,  5.000) = 267203 
    [ 5.000,  7.500) = 4531 
    [ 7.500, 10.000) = 682 
    [10.000, 12.500) = 190 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 85 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 23 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.964 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.112 ms/op
     p(99.0000) =      6.099 ms/op
     p(99.9000) =     16.575 ms/op
     p(99.9900) =     33.216 ms/op
     p(99.9990) =     35.672 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.836 ±(99.9%) 0.132 ms/op
# Warmup Iteration   2: 4.281 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.013 ms/op
Iteration   1: 4.022 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.874 ms/op
                 listUser·p0.99:   8.217 ms/op
                 listUser·p0.999:  18.645 ms/op
                 listUser·p0.9999: 21.563 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.384 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.725 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 17.465 ms/op
                 listUser·p1.00:   19.792 ms/op

Iteration   3: 3.854 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.124 ms/op
                 listUser·p0.99:   6.073 ms/op
                 listUser·p0.999:  14.271 ms/op
                 listUser·p0.9999: 15.483 ms/op
                 listUser·p1.00:   16.040 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 244016
  mean =      3.933 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 236150 
    [ 5.000,  7.500) = 5530 
    [ 7.500, 10.000) = 1429 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 307 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     15.319 ms/op
     p(99.9900) =     20.978 ms/op
     p(99.9990) =     21.809 ms/op
     p(99.9999) =     21.823 ms/op
    p(100.0000) =     21.823 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.432 ± 3.257  ops/ms
ClientPb.existUser                       thrpt       3   9.775 ± 2.387  ops/ms
ClientPb.getUser                         thrpt       3   9.417 ± 3.478  ops/ms
ClientPb.listUser                        thrpt       3   8.093 ± 1.944  ops/ms
ClientPb.createUser                       avgt       3   3.440 ± 0.867   ms/op
ClientPb.existUser                        avgt       3   3.295 ± 1.035   ms/op
ClientPb.getUser                          avgt       3   3.421 ± 0.941   ms/op
ClientPb.listUser                         avgt       3   4.065 ± 3.715   ms/op
ClientPb.createUser                     sample  278638   3.445 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.153           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.455           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.509           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.546           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.470           ms/op
ClientPb.existUser                      sample  286160   3.352 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.325           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.666           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.965           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.988           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.891           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.000           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.540           ms/op
ClientPb.getUser                        sample  284449   3.374 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.964           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.273           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.809           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.099           ms/op
ClientPb.getUser:getUser·p0.999         sample          16.575           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.216           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.783           ms/op
ClientPb.listUser                       sample  244016   3.933 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.826           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.319           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.978           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.823           ms/op
