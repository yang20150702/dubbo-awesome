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
# Warmup Iteration   1: 1.916 ops/ms
# Warmup Iteration   2: 5.349 ops/ms
# Warmup Iteration   3: 8.852 ops/ms
Iteration   1: 9.457 ops/ms
Iteration   2: 9.265 ops/ms
Iteration   3: 9.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.341 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (9.265, 9.341, 9.457), stdev = 0.102
  CI (99.9%): [7.489, 11.193] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.792 ops/ms
# Warmup Iteration   2: 8.381 ops/ms
# Warmup Iteration   3: 9.635 ops/ms
Iteration   1: 9.908 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 9.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.867 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (9.721, 9.867, 9.971), stdev = 0.130
  CI (99.9%): [7.494, 12.239] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.542 ops/ms
# Warmup Iteration   2: 8.674 ops/ms
# Warmup Iteration   3: 9.226 ops/ms
Iteration   1: 9.210 ops/ms
Iteration   2: 9.460 ops/ms
Iteration   3: 9.582 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.417 ±(99.9%) 3.458 ops/ms [Average]
  (min, avg, max) = (9.210, 9.417, 9.582), stdev = 0.190
  CI (99.9%): [5.959, 12.875] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.366 ops/ms
# Warmup Iteration   2: 7.007 ops/ms
# Warmup Iteration   3: 7.801 ops/ms
Iteration   1: 8.067 ops/ms
Iteration   2: 8.099 ops/ms
Iteration   3: 8.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.129 ±(99.9%) 1.473 ops/ms [Average]
  (min, avg, max) = (8.067, 8.129, 8.220), stdev = 0.081
  CI (99.9%): [6.656, 9.602] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.426 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.005 ms/op
Iteration   1: 3.391 ±(99.9%) 0.009 ms/op
Iteration   2: 3.304 ±(99.9%) 0.011 ms/op
Iteration   3: 3.368 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.354 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (3.304, 3.354, 3.391), stdev = 0.045
  CI (99.9%): [2.534, 4.175] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 10.293 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.736 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.391 ±(99.9%) 0.008 ms/op
Iteration   1: 3.265 ±(99.9%) 0.012 ms/op
Iteration   2: 3.199 ±(99.9%) 0.009 ms/op
Iteration   3: 3.307 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.257 ±(99.9%) 0.994 ms/op [Average]
  (min, avg, max) = (3.199, 3.257, 3.307), stdev = 0.054
  CI (99.9%): [2.263, 4.251] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.053 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.609 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.642 ±(99.9%) 0.003 ms/op
Iteration   1: 3.486 ±(99.9%) 0.006 ms/op
Iteration   2: 3.490 ±(99.9%) 0.009 ms/op
Iteration   3: 3.385 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.454 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (3.385, 3.454, 3.490), stdev = 0.060
  CI (99.9%): [2.364, 4.544] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.951 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.005 ms/op
Iteration   1: 3.903 ±(99.9%) 0.014 ms/op
Iteration   2: 3.876 ±(99.9%) 0.013 ms/op
Iteration   3: 3.889 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.889 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (3.876, 3.889, 3.903), stdev = 0.014
  CI (99.9%): [3.634, 4.144] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.250 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.493 ±(99.9%) 0.010 ms/op
Iteration   1: 3.403 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.655 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.142 ms/op
                 createUser·p0.99:   6.029 ms/op
                 createUser·p0.999:  21.699 ms/op
                 createUser·p0.9999: 25.533 ms/op
                 createUser·p1.00:   27.099 ms/op

Iteration   2: 3.491 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.055 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   6.489 ms/op
                 createUser·p0.999:  22.522 ms/op
                 createUser·p0.9999: 26.111 ms/op
                 createUser·p1.00:   29.360 ms/op

Iteration   3: 3.318 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.702 ms/op
                 createUser·p0.50:   3.224 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.923 ms/op
                 createUser·p0.999:  18.909 ms/op
                 createUser·p0.9999: 35.021 ms/op
                 createUser·p1.00:   36.635 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281922
  mean =      3.403 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6833 
    [ 2.500,  5.000) = 270106 
    [ 5.000,  7.500) = 3793 
    [ 7.500, 10.000) = 615 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 154 
    [25.000, 27.500) = 45 
    [27.500, 30.000) = 2 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.910 ms/op
     p(50.0000) =      3.285 ms/op
     p(90.0000) =      3.826 ms/op
     p(95.0000) =      4.178 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     19.762 ms/op
     p(99.9900) =     34.275 ms/op
     p(99.9990) =     35.783 ms/op
     p(99.9999) =     36.635 ms/op
    p(100.0000) =     36.635 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.944 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.695 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.400 ±(99.9%) 0.009 ms/op
Iteration   1: 3.345 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.550 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.723 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.833 ms/op
                 existUser·p0.999:  18.186 ms/op
                 existUser·p0.9999: 22.503 ms/op
                 existUser·p1.00:   24.019 ms/op

Iteration   2: 3.217 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.362 ms/op
                 existUser·p0.50:   3.146 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  8.571 ms/op
                 existUser·p0.9999: 22.681 ms/op
                 existUser·p1.00:   23.921 ms/op

Iteration   3: 3.300 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.575 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.449 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  15.302 ms/op
                 existUser·p0.9999: 24.335 ms/op
                 existUser·p1.00:   24.936 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291907
  mean =      3.286 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9231 
    [ 2.500,  5.000) = 278024 
    [ 5.000,  7.500) = 3927 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 136 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.215 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      5.538 ms/op
     p(99.9000) =     10.912 ms/op
     p(99.9900) =     23.888 ms/op
     p(99.9990) =     24.576 ms/op
     p(99.9999) =     24.936 ms/op
    p(100.0000) =     24.936 ms/op


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
# Warmup Iteration   1: 8.648 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.565 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.449 ±(99.9%) 0.009 ms/op
Iteration   1: 3.467 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.534 ms/op
                 getUser·p0.50:   3.330 ms/op
                 getUser·p0.90:   3.985 ms/op
                 getUser·p0.95:   4.579 ms/op
                 getUser·p0.99:   6.373 ms/op
                 getUser·p0.999:  15.614 ms/op
                 getUser·p0.9999: 21.685 ms/op
                 getUser·p1.00:   23.265 ms/op

Iteration   2: 3.293 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.679 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   5.382 ms/op
                 getUser·p0.999:  10.498 ms/op
                 getUser·p0.9999: 24.717 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.355 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  18.819 ms/op
                 getUser·p0.9999: 26.666 ms/op
                 getUser·p1.00:   27.754 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 284779
  mean =      3.370 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10428 
    [ 2.500,  5.000) = 267650 
    [ 5.000,  7.500) = 5727 
    [ 7.500, 10.000) = 552 
    [10.000, 12.500) = 115 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     15.614 ms/op
     p(99.9900) =     24.790 ms/op
     p(99.9990) =     27.361 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 9.190 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.232 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.123 ±(99.9%) 0.013 ms/op
Iteration   1: 4.012 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.657 ms/op
                 listUser·p0.99:   7.643 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 22.646 ms/op
                 listUser·p1.00:   23.233 ms/op

Iteration   2: 3.856 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.195 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.190 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  14.582 ms/op
                 listUser·p0.9999: 16.417 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 3.941 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.079 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  15.563 ms/op
                 listUser·p0.9999: 20.873 ms/op
                 listUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243756
  mean =      3.935 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 236549 
    [ 5.000,  7.500) = 5028 
    [ 7.500, 10.000) = 1300 
    [10.000, 12.500) = 285 
    [12.500, 15.000) = 290 
    [15.000, 17.500) = 141 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 78 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.706 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.242 ms/op
     p(99.9000) =     15.470 ms/op
     p(99.9900) =     21.234 ms/op
     p(99.9990) =     23.067 ms/op
     p(99.9999) =     23.233 ms/op
    p(100.0000) =     23.233 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.341 ± 1.852  ops/ms
ClientPb.existUser                       thrpt       3   9.867 ± 2.372  ops/ms
ClientPb.getUser                         thrpt       3   9.417 ± 3.458  ops/ms
ClientPb.listUser                        thrpt       3   8.129 ± 1.473  ops/ms
ClientPb.createUser                       avgt       3   3.354 ± 0.821   ms/op
ClientPb.existUser                        avgt       3   3.257 ± 0.994   ms/op
ClientPb.getUser                          avgt       3   3.454 ± 1.090   ms/op
ClientPb.listUser                         avgt       3   3.889 ± 0.255   ms/op
ClientPb.createUser                     sample  281922   3.403 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.910           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.285           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.826           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.825           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.762           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.275           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.635           ms/op
ClientPb.existUser                      sample  291907   3.286 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.362           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.215           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.538           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.912           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.888           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.936           ms/op
ClientPb.getUser                        sample  284779   3.370 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.534           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.777           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.111           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.614           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.790           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.754           ms/op
ClientPb.listUser                       sample  243756   3.935 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.706           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.793           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.268           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.530           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.234           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.233           ms/op
