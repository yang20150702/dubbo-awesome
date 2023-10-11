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
# Warmup Iteration   1: 1.730 ops/ms
# Warmup Iteration   2: 4.563 ops/ms
# Warmup Iteration   3: 8.336 ops/ms
Iteration   1: 8.380 ops/ms
Iteration   2: 8.732 ops/ms
Iteration   3: 8.807 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.640 ±(99.9%) 4.165 ops/ms [Average]
  (min, avg, max) = (8.380, 8.640, 8.807), stdev = 0.228
  CI (99.9%): [4.475, 12.805] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.638 ops/ms
# Warmup Iteration   2: 7.103 ops/ms
# Warmup Iteration   3: 8.947 ops/ms
Iteration   1: 8.928 ops/ms
Iteration   2: 8.761 ops/ms
Iteration   3: 8.908 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.865 ±(99.9%) 1.664 ops/ms [Average]
  (min, avg, max) = (8.761, 8.865, 8.928), stdev = 0.091
  CI (99.9%): [7.201, 10.530] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.285 ops/ms
# Warmup Iteration   2: 6.952 ops/ms
# Warmup Iteration   3: 8.453 ops/ms
Iteration   1: 8.230 ops/ms
Iteration   2: 8.423 ops/ms
Iteration   3: 8.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.409 ±(99.9%) 3.157 ops/ms [Average]
  (min, avg, max) = (8.230, 8.409, 8.575), stdev = 0.173
  CI (99.9%): [5.253, 11.566] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.311 ops/ms
# Warmup Iteration   2: 6.413 ops/ms
# Warmup Iteration   3: 7.274 ops/ms
Iteration   1: 7.079 ops/ms
Iteration   2: 7.437 ops/ms
Iteration   3: 7.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.353 ±(99.9%) 4.445 ops/ms [Average]
  (min, avg, max) = (7.079, 7.353, 7.544), stdev = 0.244
  CI (99.9%): [2.908, 11.798] (assumes normal distribution)


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
# Warmup Iteration   1: 11.222 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.005 ms/op
Iteration   1: 3.784 ±(99.9%) 0.005 ms/op
Iteration   2: 3.691 ±(99.9%) 0.006 ms/op
Iteration   3: 3.814 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.763 ±(99.9%) 1.173 ms/op [Average]
  (min, avg, max) = (3.691, 3.763, 3.814), stdev = 0.064
  CI (99.9%): [2.590, 4.936] (assumes normal distribution)


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
# Warmup Iteration   1: 12.180 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 3.889 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.641 ±(99.9%) 0.005 ms/op
Iteration   1: 3.616 ±(99.9%) 0.004 ms/op
Iteration   2: 3.577 ±(99.9%) 0.008 ms/op
Iteration   3: 3.608 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.600 ±(99.9%) 0.372 ms/op [Average]
  (min, avg, max) = (3.577, 3.600, 3.616), stdev = 0.020
  CI (99.9%): [3.229, 3.972] (assumes normal distribution)


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
# Warmup Iteration   1: 13.385 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.427 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.005 ms/op
Iteration   1: 3.681 ±(99.9%) 0.006 ms/op
Iteration   2: 3.698 ±(99.9%) 0.005 ms/op
Iteration   3: 3.615 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.665 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (3.615, 3.665, 3.698), stdev = 0.044
  CI (99.9%): [2.867, 4.463] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.070 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.929 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.323 ±(99.9%) 0.006 ms/op
Iteration   1: 4.369 ±(99.9%) 0.013 ms/op
Iteration   2: 4.292 ±(99.9%) 0.008 ms/op
Iteration   3: 4.276 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.312 ±(99.9%) 0.911 ms/op [Average]
  (min, avg, max) = (4.276, 4.312, 4.369), stdev = 0.050
  CI (99.9%): [3.401, 5.223] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 11.363 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.086 ±(99.9%) 0.017 ms/op
Iteration   1: 3.748 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.350 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.514 ms/op
                 createUser·p0.95:   5.358 ms/op
                 createUser·p0.99:   8.270 ms/op
                 createUser·p0.999:  20.962 ms/op
                 createUser·p0.9999: 25.059 ms/op
                 createUser·p1.00:   25.723 ms/op

Iteration   2: 3.669 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.403 ms/op
                 createUser·p0.50:   3.482 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   5.005 ms/op
                 createUser·p0.99:   7.550 ms/op
                 createUser·p0.999:  22.020 ms/op
                 createUser·p0.9999: 24.674 ms/op
                 createUser·p1.00:   25.526 ms/op

Iteration   3: 3.765 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.772 ms/op
                 createUser·p0.50:   3.490 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   5.292 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  25.592 ms/op
                 createUser·p0.9999: 33.784 ms/op
                 createUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 257557
  mean =      3.727 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2018 
    [ 2.500,  5.000) = 241363 
    [ 5.000,  7.500) = 10520 
    [ 7.500, 10.000) = 2855 
    [10.000, 12.500) = 292 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.350 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      5.153 ms/op
     p(99.0000) =      8.110 ms/op
     p(99.9000) =     21.856 ms/op
     p(99.9900) =     33.112 ms/op
     p(99.9990) =     34.013 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


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
# Warmup Iteration   1: 11.597 ±(99.9%) 0.136 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.617 ±(99.9%) 0.013 ms/op
Iteration   1: 3.532 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.511 ms/op
                 existUser·p0.50:   3.420 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.391 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  10.453 ms/op
                 existUser·p0.9999: 23.658 ms/op
                 existUser·p1.00:   24.707 ms/op

Iteration   2: 3.537 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.434 ms/op
                 existUser·p0.50:   3.379 ms/op
                 existUser·p0.90:   3.822 ms/op
                 existUser·p0.95:   4.489 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  23.691 ms/op
                 existUser·p0.9999: 27.130 ms/op
                 existUser·p1.00:   27.918 ms/op

Iteration   3: 3.581 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.409 ms/op
                 existUser·p0.50:   3.441 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   8.151 ms/op
                 existUser·p0.999:  23.598 ms/op
                 existUser·p0.9999: 31.673 ms/op
                 existUser·p1.00:   35.979 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 270340
  mean =      3.550 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5412 
    [ 2.500,  5.000) = 254762 
    [ 5.000,  7.500) = 7140 
    [ 7.500, 10.000) = 2494 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 16 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.409 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      3.842 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      7.676 ms/op
     p(99.9000) =     18.062 ms/op
     p(99.9900) =     29.572 ms/op
     p(99.9990) =     35.841 ms/op
     p(99.9999) =     35.979 ms/op
    p(100.0000) =     35.979 ms/op


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
# Warmup Iteration   1: 12.457 ±(99.9%) 0.150 ms/op
# Warmup Iteration   2: 4.268 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.016 ms/op
Iteration   1: 3.803 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.551 ms/op
                 getUser·p0.90:   4.399 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   8.191 ms/op
                 getUser·p0.999:  15.668 ms/op
                 getUser·p0.9999: 26.211 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 4.089 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.670 ms/op
                 getUser·p0.90:   5.407 ms/op
                 getUser·p0.95:   6.734 ms/op
                 getUser·p0.99:   9.535 ms/op
                 getUser·p0.999:  24.856 ms/op
                 getUser·p0.9999: 29.524 ms/op
                 getUser·p1.00:   30.409 ms/op

Iteration   3: 3.790 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   3.572 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   5.112 ms/op
                 getUser·p0.99:   8.292 ms/op
                 getUser·p0.999:  26.018 ms/op
                 getUser·p0.9999: 29.673 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246743
  mean =      3.889 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 817 
    [ 2.500,  5.000) = 225803 
    [ 5.000,  7.500) = 14828 
    [ 7.500, 10.000) = 4035 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 109 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.980 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     23.774 ms/op
     p(99.9900) =     29.458 ms/op
     p(99.9990) =     30.444 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 13.897 ±(99.9%) 0.203 ms/op
# Warmup Iteration   2: 5.274 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.640 ±(99.9%) 0.019 ms/op
Iteration   1: 4.621 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   5.393 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   10.373 ms/op
                 listUser·p0.999:  23.947 ms/op
                 listUser·p0.9999: 31.099 ms/op
                 listUser·p1.00:   33.554 ms/op

Iteration   2: 4.501 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.531 ms/op
                 listUser·p0.50:   4.334 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  19.854 ms/op
                 listUser·p0.9999: 24.893 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   3: 4.479 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.425 ms/op
                 listUser·p0.50:   4.301 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.259 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  19.124 ms/op
                 listUser·p0.9999: 25.279 ms/op
                 listUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 211653
  mean =      4.533 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19 
    [ 2.500,  5.000) = 192392 
    [ 5.000,  7.500) = 13514 
    [ 7.500, 10.000) = 3707 
    [10.000, 12.500) = 1349 
    [12.500, 15.000) = 215 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.425 ms/op
     p(50.0000) =      4.309 ms/op
     p(90.0000) =      4.940 ms/op
     p(95.0000) =      5.988 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     20.885 ms/op
     p(99.9900) =     30.114 ms/op
     p(99.9990) =     32.206 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.640 ± 4.165  ops/ms
ClientPb.existUser                       thrpt       3   8.865 ± 1.664  ops/ms
ClientPb.getUser                         thrpt       3   8.409 ± 3.157  ops/ms
ClientPb.listUser                        thrpt       3   7.353 ± 4.445  ops/ms
ClientPb.createUser                       avgt       3   3.763 ± 1.173   ms/op
ClientPb.existUser                        avgt       3   3.600 ± 0.372   ms/op
ClientPb.getUser                          avgt       3   3.665 ± 0.798   ms/op
ClientPb.listUser                         avgt       3   4.312 ± 0.911   ms/op
ClientPb.createUser                     sample  257557   3.727 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.498           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.350           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.153           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.110           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.856           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.112           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.079           ms/op
ClientPb.existUser                      sample  270340   3.550 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.409           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.412           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.676           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.062           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.572           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.979           ms/op
ClientPb.getUser                        sample  246743   3.889 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.588           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.702           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.980           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.733           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.774           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.458           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  211653   4.533 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.425           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.940           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.988           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.896           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.885           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.114           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
