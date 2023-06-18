# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.071 ops/ms
# Warmup Iteration   2: 5.256 ops/ms
# Warmup Iteration   3: 8.461 ops/ms
Iteration   1: 8.936 ops/ms
Iteration   2: 9.360 ops/ms
Iteration   3: 9.169 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.155 ±(99.9%) 3.873 ops/ms [Average]
  (min, avg, max) = (8.936, 9.155, 9.360), stdev = 0.212
  CI (99.9%): [5.282, 13.028] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.156 ops/ms
# Warmup Iteration   2: 9.102 ops/ms
# Warmup Iteration   3: 9.339 ops/ms
Iteration   1: 9.358 ops/ms
Iteration   2: 9.406 ops/ms
Iteration   3: 9.472 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.412 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (9.358, 9.412, 9.472), stdev = 0.058
  CI (99.9%): [8.362, 10.462] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ops/ms
# Warmup Iteration   2: 7.666 ops/ms
# Warmup Iteration   3: 9.054 ops/ms
Iteration   1: 9.594 ops/ms
Iteration   2: 9.253 ops/ms
Iteration   3: 9.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.359 ±(99.9%) 3.719 ops/ms [Average]
  (min, avg, max) = (9.230, 9.359, 9.594), stdev = 0.204
  CI (99.9%): [5.640, 13.077] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.862 ops/ms
# Warmup Iteration   2: 6.687 ops/ms
# Warmup Iteration   3: 7.770 ops/ms
Iteration   1: 8.001 ops/ms
Iteration   2: 8.164 ops/ms
Iteration   3: 8.123 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.096 ±(99.9%) 1.546 ops/ms [Average]
  (min, avg, max) = (8.001, 8.096, 8.164), stdev = 0.085
  CI (99.9%): [6.550, 9.641] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.395 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.882 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.007 ms/op
Iteration   1: 3.363 ±(99.9%) 0.007 ms/op
Iteration   2: 3.651 ±(99.9%) 0.007 ms/op
Iteration   3: 3.450 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.488 ±(99.9%) 2.690 ms/op [Average]
  (min, avg, max) = (3.363, 3.488, 3.651), stdev = 0.147
  CI (99.9%): [0.798, 6.178] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.190 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.595 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.007 ms/op
Iteration   1: 3.280 ±(99.9%) 0.010 ms/op
Iteration   2: 3.279 ±(99.9%) 0.005 ms/op
Iteration   3: 3.326 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.295 ±(99.9%) 0.487 ms/op [Average]
  (min, avg, max) = (3.279, 3.295, 3.326), stdev = 0.027
  CI (99.9%): [2.809, 3.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 8.260 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.681 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.544 ±(99.9%) 0.007 ms/op
Iteration   1: 3.354 ±(99.9%) 0.006 ms/op
Iteration   2: 3.347 ±(99.9%) 0.010 ms/op
Iteration   3: 3.437 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.380 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.347, 3.380, 3.437), stdev = 0.050
  CI (99.9%): [2.467, 4.293] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.094 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.367 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.010 ms/op
Iteration   1: 4.028 ±(99.9%) 0.013 ms/op
Iteration   2: 4.026 ±(99.9%) 0.009 ms/op
Iteration   3: 4.052 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.035 ±(99.9%) 0.265 ms/op [Average]
  (min, avg, max) = (4.026, 4.035, 4.052), stdev = 0.015
  CI (99.9%): [3.770, 4.300] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.258 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.785 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.327 ±(99.9%) 0.009 ms/op
Iteration   1: 3.367 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.781 ms/op
                 createUser·p0.95:   4.116 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  20.840 ms/op
                 createUser·p0.9999: 25.707 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 3.407 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.405 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  20.813 ms/op
                 createUser·p0.9999: 24.125 ms/op
                 createUser·p1.00:   24.936 ms/op

Iteration   3: 3.361 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   3.293 ms/op
                 createUser·p0.90:   3.719 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  17.760 ms/op
                 createUser·p0.9999: 28.279 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283842
  mean =      3.378 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8440 
    [ 2.500,  5.000) = 269704 
    [ 5.000,  7.500) = 4749 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 114 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 47 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      4.104 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     27.525 ms/op
     p(99.9990) =     28.508 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.144 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.008 ms/op
Iteration   1: 3.368 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.182 ms/op
                 existUser·p0.99:   5.661 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 22.922 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.281 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  21.750 ms/op
                 existUser·p0.9999: 28.009 ms/op
                 existUser·p1.00:   29.131 ms/op

Iteration   3: 3.342 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.994 ms/op
                 existUser·p0.99:   5.754 ms/op
                 existUser·p0.999:  13.249 ms/op
                 existUser·p0.9999: 27.685 ms/op
                 existUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285846
  mean =      3.356 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21027 
    [ 2.500,  5.000) = 259249 
    [ 5.000,  7.500) = 4356 
    [ 7.500, 10.000) = 636 
    [10.000, 12.500) = 194 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 78 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.080 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     14.846 ms/op
     p(99.9900) =     27.473 ms/op
     p(99.9990) =     28.751 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 10.074 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.010 ms/op
Iteration   1: 3.426 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   4.022 ms/op
                 getUser·p0.99:   6.914 ms/op
                 getUser·p0.999:  18.763 ms/op
                 getUser·p0.9999: 27.525 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   2: 3.586 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   6.217 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 23.664 ms/op
                 getUser·p1.00:   24.347 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.145 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   3.994 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  21.421 ms/op
                 getUser·p0.9999: 26.640 ms/op
                 getUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 276256
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5051 
    [ 2.500,  5.000) = 261589 
    [ 5.000,  7.500) = 8406 
    [ 7.500, 10.000) = 808 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.920 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.545 ms/op
     p(99.9000) =     19.292 ms/op
     p(99.9900) =     26.915 ms/op
     p(99.9990) =     27.820 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.896 ±(99.9%) 0.134 ms/op
# Warmup Iteration   2: 4.864 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.247 ±(99.9%) 0.014 ms/op
Iteration   1: 4.123 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.225 ms/op
                 listUser·p0.999:  19.016 ms/op
                 listUser·p0.9999: 23.994 ms/op
                 listUser·p1.00:   24.773 ms/op

Iteration   2: 3.973 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.519 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.571 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  16.582 ms/op
                 listUser·p0.9999: 21.722 ms/op
                 listUser·p1.00:   22.479 ms/op

Iteration   3: 4.077 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.482 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.858 ms/op
                 listUser·p0.99:   7.083 ms/op
                 listUser·p0.999:  13.894 ms/op
                 listUser·p0.9999: 14.830 ms/op
                 listUser·p1.00:   14.893 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236671
  mean =      4.056 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 23 
    [ 2.500,  5.000) = 226994 
    [ 5.000,  7.500) = 7337 
    [ 7.500, 10.000) = 1544 
    [10.000, 12.500) = 250 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.473 ms/op
     p(95.0000) =      4.825 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     15.876 ms/op
     p(99.9900) =     23.200 ms/op
     p(99.9990) =     24.737 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.155 ± 3.873  ops/ms
ClientPb.existUser                       thrpt       3   9.412 ± 1.050  ops/ms
ClientPb.getUser                         thrpt       3   9.359 ± 3.719  ops/ms
ClientPb.listUser                        thrpt       3   8.096 ± 1.546  ops/ms
ClientPb.createUser                       avgt       3   3.488 ± 2.690   ms/op
ClientPb.existUser                        avgt       3   3.295 ± 0.487   ms/op
ClientPb.getUser                          avgt       3   3.380 ± 0.913   ms/op
ClientPb.listUser                         avgt       3   4.035 ± 0.265   ms/op
ClientPb.createUser                     sample  283842   3.378 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.200           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.104           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.628           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.859           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.525           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.508           ms/op
ClientPb.existUser                      sample  285846   3.356 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.879           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.080           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.846           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.473           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.131           ms/op
ClientPb.getUser                        sample  276256   3.475 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.986           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.545           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.292           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.915           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.853           ms/op
ClientPb.listUser                       sample  236671   4.056 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.455           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.876           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.773           ms/op
