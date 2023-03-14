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
# Warmup Iteration   1: 2.078 ops/ms
# Warmup Iteration   2: 4.986 ops/ms
# Warmup Iteration   3: 8.424 ops/ms
Iteration   1: 8.803 ops/ms
Iteration   2: 9.569 ops/ms
Iteration   3: 9.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.254 ±(99.9%) 7.307 ops/ms [Average]
  (min, avg, max) = (8.803, 9.254, 9.569), stdev = 0.401
  CI (99.9%): [1.946, 16.561] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.286 ops/ms
# Warmup Iteration   2: 8.283 ops/ms
# Warmup Iteration   3: 9.476 ops/ms
Iteration   1: 9.779 ops/ms
Iteration   2: 9.356 ops/ms
Iteration   3: 9.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.482 ±(99.9%) 4.711 ops/ms [Average]
  (min, avg, max) = (9.312, 9.482, 9.779), stdev = 0.258
  CI (99.9%): [4.772, 14.193] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.081 ops/ms
# Warmup Iteration   2: 8.031 ops/ms
# Warmup Iteration   3: 9.002 ops/ms
Iteration   1: 8.702 ops/ms
Iteration   2: 9.413 ops/ms
Iteration   3: 9.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.189 ±(99.9%) 7.715 ops/ms [Average]
  (min, avg, max) = (8.702, 9.189, 9.454), stdev = 0.423
  CI (99.9%): [1.475, 16.904] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.705 ops/ms
# Warmup Iteration   2: 6.935 ops/ms
# Warmup Iteration   3: 7.945 ops/ms
Iteration   1: 7.886 ops/ms
Iteration   2: 8.338 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.038 ±(99.9%) 4.738 ops/ms [Average]
  (min, avg, max) = (7.886, 8.038, 8.338), stdev = 0.260
  CI (99.9%): [3.300, 12.776] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.789 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.988 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.461 ±(99.9%) 0.008 ms/op
Iteration   1: 3.366 ±(99.9%) 0.010 ms/op
Iteration   2: 3.535 ±(99.9%) 0.007 ms/op
Iteration   3: 3.463 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.455 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.366, 3.455, 3.535), stdev = 0.085
  CI (99.9%): [1.909, 5.001] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.984 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.662 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.362 ±(99.9%) 0.007 ms/op
Iteration   1: 3.219 ±(99.9%) 0.004 ms/op
Iteration   2: 3.225 ±(99.9%) 0.008 ms/op
Iteration   3: 3.298 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.247 ±(99.9%) 0.802 ms/op [Average]
  (min, avg, max) = (3.219, 3.247, 3.298), stdev = 0.044
  CI (99.9%): [2.445, 4.049] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 10.080 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.418 ±(99.9%) 0.009 ms/op
Iteration   1: 3.342 ±(99.9%) 0.005 ms/op
Iteration   2: 3.545 ±(99.9%) 0.007 ms/op
Iteration   3: 3.359 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.415 ±(99.9%) 2.057 ms/op [Average]
  (min, avg, max) = (3.342, 3.415, 3.545), stdev = 0.113
  CI (99.9%): [1.358, 5.472] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.997 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.141 ±(99.9%) 0.009 ms/op
Iteration   1: 4.063 ±(99.9%) 0.008 ms/op
Iteration   2: 3.997 ±(99.9%) 0.007 ms/op
Iteration   3: 3.980 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.013 ±(99.9%) 0.794 ms/op [Average]
  (min, avg, max) = (3.980, 4.013, 4.063), stdev = 0.044
  CI (99.9%): [3.219, 4.808] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.991 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.444 ±(99.9%) 0.010 ms/op
Iteration   1: 3.506 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.042 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   4.166 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.187 ms/op
                 createUser·p0.999:  20.731 ms/op
                 createUser·p0.9999: 22.872 ms/op
                 createUser·p1.00:   23.527 ms/op

Iteration   2: 3.459 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.585 ms/op
                 createUser·p0.50:   3.334 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.439 ms/op
                 createUser·p0.999:  22.226 ms/op
                 createUser·p0.9999: 24.404 ms/op
                 createUser·p1.00:   25.231 ms/op

Iteration   3: 3.355 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.485 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  19.640 ms/op
                 createUser·p0.9999: 33.584 ms/op
                 createUser·p1.00:   34.669 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279042
  mean =      3.439 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14098 
    [ 2.500,  5.000) = 258019 
    [ 5.000,  7.500) = 5930 
    [ 7.500, 10.000) = 502 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.042 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.985 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     20.407 ms/op
     p(99.9900) =     31.932 ms/op
     p(99.9990) =     34.537 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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
# Warmup Iteration   1: 8.263 ±(99.9%) 0.108 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.380 ±(99.9%) 0.010 ms/op
Iteration   1: 3.190 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  8.798 ms/op
                 existUser·p0.9999: 22.936 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.370 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.569 ms/op
                 existUser·p0.50:   3.289 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.906 ms/op
                 existUser·p0.999:  10.226 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 3.304 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.364 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.891 ms/op
                 existUser·p0.99:   5.835 ms/op
                 existUser·p0.999:  14.776 ms/op
                 existUser·p0.9999: 25.657 ms/op
                 existUser·p1.00:   26.477 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291942
  mean =      3.286 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15606 
    [ 2.500,  5.000) = 270441 
    [ 5.000,  7.500) = 5043 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.290 ms/op
     p(99.9900) =     25.133 ms/op
     p(99.9990) =     26.321 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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
# Warmup Iteration   1: 10.752 ±(99.9%) 0.133 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.727 ±(99.9%) 0.015 ms/op
Iteration   1: 3.501 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.659 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.545 ms/op
                 getUser·p0.999:  21.470 ms/op
                 getUser·p0.9999: 25.588 ms/op
                 getUser·p1.00:   26.477 ms/op

Iteration   2: 3.473 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.386 ms/op
                 getUser·p0.50:   3.375 ms/op
                 getUser·p0.90:   3.994 ms/op
                 getUser·p0.95:   4.440 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  23.001 ms/op
                 getUser·p0.9999: 29.530 ms/op
                 getUser·p1.00:   31.031 ms/op

Iteration   3: 3.391 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.286 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   6.046 ms/op
                 getUser·p0.999:  13.887 ms/op
                 getUser·p0.9999: 34.378 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277612
  mean =      3.454 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11333 
    [ 2.500,  5.000) = 257938 
    [ 5.000,  7.500) = 7126 
    [ 7.500, 10.000) = 782 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 32 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.286 ms/op
     p(50.0000) =      3.359 ms/op
     p(90.0000) =      3.879 ms/op
     p(95.0000) =      4.235 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =     14.129 ms/op
     p(99.9900) =     32.776 ms/op
     p(99.9990) =     34.909 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


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
# Warmup Iteration   1: 10.963 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.299 ±(99.9%) 0.016 ms/op
Iteration   1: 3.985 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.183 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   6.808 ms/op
                 listUser·p0.999:  17.623 ms/op
                 listUser·p0.9999: 24.181 ms/op
                 listUser·p1.00:   25.330 ms/op

Iteration   2: 3.996 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.363 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   6.382 ms/op
                 listUser·p0.999:  15.788 ms/op
                 listUser·p0.9999: 20.578 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.915 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.062 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   6.913 ms/op
                 listUser·p0.999:  14.691 ms/op
                 listUser·p0.9999: 21.294 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242115
  mean =      3.965 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 235161 
    [ 5.000,  7.500) = 5254 
    [ 7.500, 10.000) = 916 
    [10.000, 12.500) = 236 
    [12.500, 15.000) = 216 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.062 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     16.073 ms/op
     p(99.9900) =     23.394 ms/op
     p(99.9990) =     25.264 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.254 ± 7.307  ops/ms
ClientPb.existUser                       thrpt       3   9.482 ± 4.711  ops/ms
ClientPb.getUser                         thrpt       3   9.189 ± 7.715  ops/ms
ClientPb.listUser                        thrpt       3   8.038 ± 4.738  ops/ms
ClientPb.createUser                       avgt       3   3.455 ± 1.546   ms/op
ClientPb.existUser                        avgt       3   3.247 ± 0.802   ms/op
ClientPb.getUser                          avgt       3   3.415 ± 2.057   ms/op
ClientPb.listUser                         avgt       3   4.013 ± 0.794   ms/op
ClientPb.createUser                     sample  279042   3.439 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.042           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.326           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.985           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.334           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.841           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.407           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.932           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.669           ms/op
ClientPb.existUser                      sample  291942   3.286 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.364           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.228           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.580           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.677           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.290           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.133           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  277612   3.454 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.286           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.359           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.879           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.235           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.152           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.129           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.776           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.652           ms/op
ClientPb.listUser                       sample  242115   3.965 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.062           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.871           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.857           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.073           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.394           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.330           ms/op
