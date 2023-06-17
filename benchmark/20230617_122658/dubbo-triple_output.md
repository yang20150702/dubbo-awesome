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
# Warmup Iteration   1: 2.153 ops/ms
# Warmup Iteration   2: 5.889 ops/ms
# Warmup Iteration   3: 8.795 ops/ms
Iteration   1: 9.176 ops/ms
Iteration   2: 9.261 ops/ms
Iteration   3: 9.478 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.305 ±(99.9%) 2.843 ops/ms [Average]
  (min, avg, max) = (9.176, 9.305, 9.478), stdev = 0.156
  CI (99.9%): [6.462, 12.148] (assumes normal distribution)


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
# Warmup Iteration   1: 3.580 ops/ms
# Warmup Iteration   2: 8.892 ops/ms
# Warmup Iteration   3: 9.561 ops/ms
Iteration   1: 9.605 ops/ms
Iteration   2: 9.423 ops/ms
Iteration   3: 9.419 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.482 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (9.419, 9.482, 9.605), stdev = 0.106
  CI (99.9%): [7.546, 11.418] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.141 ops/ms
# Warmup Iteration   2: 8.345 ops/ms
# Warmup Iteration   3: 8.959 ops/ms
Iteration   1: 9.353 ops/ms
Iteration   2: 9.711 ops/ms
Iteration   3: 9.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.483 ±(99.9%) 3.609 ops/ms [Average]
  (min, avg, max) = (9.353, 9.483, 9.711), stdev = 0.198
  CI (99.9%): [5.874, 13.092] (assumes normal distribution)


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
# Warmup Iteration   1: 2.812 ops/ms
# Warmup Iteration   2: 7.212 ops/ms
# Warmup Iteration   3: 7.880 ops/ms
Iteration   1: 8.023 ops/ms
Iteration   2: 8.080 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.064 ±(99.9%) 0.659 ops/ms [Average]
  (min, avg, max) = (8.023, 8.064, 8.090), stdev = 0.036
  CI (99.9%): [7.405, 8.723] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.037 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.420 ±(99.9%) 0.006 ms/op
Iteration   1: 3.400 ±(99.9%) 0.007 ms/op
Iteration   2: 3.389 ±(99.9%) 0.010 ms/op
Iteration   3: 3.354 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.381 ±(99.9%) 0.436 ms/op [Average]
  (min, avg, max) = (3.354, 3.381, 3.400), stdev = 0.024
  CI (99.9%): [2.945, 3.817] (assumes normal distribution)


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
# Warmup Iteration   1: 7.144 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.547 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
Iteration   1: 3.348 ±(99.9%) 0.008 ms/op
Iteration   2: 3.308 ±(99.9%) 0.008 ms/op
Iteration   3: 3.425 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.360 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (3.308, 3.360, 3.425), stdev = 0.059
  CI (99.9%): [2.275, 4.445] (assumes normal distribution)


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
# Warmup Iteration   1: 9.491 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.624 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.639 ±(99.9%) 0.007 ms/op
Iteration   1: 3.296 ±(99.9%) 0.008 ms/op
Iteration   2: 3.369 ±(99.9%) 0.001 ms/op
Iteration   3: 3.459 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.374 ±(99.9%) 1.488 ms/op [Average]
  (min, avg, max) = (3.296, 3.374, 3.459), stdev = 0.082
  CI (99.9%): [1.886, 4.862] (assumes normal distribution)


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
# Warmup Iteration   1: 10.637 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.250 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.891 ±(99.9%) 0.013 ms/op
Iteration   2: 3.937 ±(99.9%) 0.011 ms/op
Iteration   3: 3.925 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.918 ±(99.9%) 0.432 ms/op [Average]
  (min, avg, max) = (3.891, 3.918, 3.937), stdev = 0.024
  CI (99.9%): [3.486, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 8.741 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.009 ms/op
Iteration   1: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.077 ms/op
                 createUser·p0.50:   3.338 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  19.269 ms/op
                 createUser·p0.9999: 25.082 ms/op
                 createUser·p1.00:   26.051 ms/op

Iteration   2: 3.400 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.780 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.010 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  19.690 ms/op
                 createUser·p0.9999: 22.151 ms/op
                 createUser·p1.00:   23.495 ms/op

Iteration   3: 3.484 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   6.117 ms/op
                 createUser·p0.999:  18.161 ms/op
                 createUser·p0.9999: 24.898 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278855
  mean =      3.442 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10546 
    [ 2.500,  5.000) = 262616 
    [ 5.000,  7.500) = 4399 
    [ 7.500, 10.000) = 780 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 143 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.947 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      3.834 ms/op
     p(95.0000) =      4.166 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     18.289 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.914 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 8.581 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 3.753 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.282 ±(99.9%) 0.008 ms/op
Iteration   1: 3.209 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.681 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.498 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  9.362 ms/op
                 existUser·p0.9999: 17.367 ms/op
                 existUser·p1.00:   18.252 ms/op

Iteration   2: 3.327 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.202 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.740 ms/op
                 existUser·p0.95:   4.497 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  17.564 ms/op
                 existUser·p0.9999: 21.509 ms/op
                 existUser·p1.00:   21.856 ms/op

Iteration   3: 3.316 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.882 ms/op
                 existUser·p0.50:   3.199 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.969 ms/op
                 existUser·p0.99:   5.054 ms/op
                 existUser·p0.999:  17.529 ms/op
                 existUser·p0.9999: 24.403 ms/op
                 existUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 291899
  mean =      3.283 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5737 
    [ 2.500,  5.000) = 280355 
    [ 5.000,  7.500) = 5042 
    [ 7.500, 10.000) = 426 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.882 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     22.897 ms/op
     p(99.9990) =     25.144 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


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
# Warmup Iteration   1: 8.555 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.524 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.012 ms/op
Iteration   1: 3.519 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.380 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   3.858 ms/op
                 getUser·p0.95:   4.247 ms/op
                 getUser·p0.99:   6.521 ms/op
                 getUser·p0.999:  20.185 ms/op
                 getUser·p0.9999: 30.168 ms/op
                 getUser·p1.00:   33.882 ms/op

Iteration   2: 3.414 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.501 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.842 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  21.140 ms/op
                 getUser·p0.9999: 24.454 ms/op
                 getUser·p1.00:   25.362 ms/op

Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   3.314 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   4.145 ms/op
                 getUser·p0.99:   6.396 ms/op
                 getUser·p0.999:  16.858 ms/op
                 getUser·p0.9999: 26.106 ms/op
                 getUser·p1.00:   26.542 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277625
  mean =      3.455 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6113 
    [ 2.500,  5.000) = 262580 
    [ 5.000,  7.500) = 7633 
    [ 7.500, 10.000) = 750 
    [10.000, 12.500) = 117 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 34 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.380 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.822 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     17.629 ms/op
     p(99.9900) =     27.934 ms/op
     p(99.9990) =     32.397 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 10.127 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.013 ms/op
Iteration   1: 4.105 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   3.949 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.731 ms/op
                 listUser·p0.999:  22.423 ms/op
                 listUser·p0.9999: 26.190 ms/op
                 listUser·p1.00:   28.738 ms/op

Iteration   2: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.604 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.117 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   3: 3.926 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.413 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.555 ms/op
                 listUser·p0.99:   5.956 ms/op
                 listUser·p0.999:  15.155 ms/op
                 listUser·p0.9999: 20.939 ms/op
                 listUser·p1.00:   21.037 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 240841
  mean =      3.984 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 233088 
    [ 5.000,  7.500) = 5866 
    [ 7.500, 10.000) = 1005 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 239 
    [15.000, 17.500) = 182 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 35 

  Percentiles, ms/op:
      p(0.0000) =      1.604 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      7.050 ms/op
     p(99.9000) =     15.794 ms/op
     p(99.9900) =     25.526 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     28.738 ms/op
    p(100.0000) =     28.738 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.305 ± 2.843  ops/ms
ClientPb.existUser                       thrpt       3   9.482 ± 1.936  ops/ms
ClientPb.getUser                         thrpt       3   9.483 ± 3.609  ops/ms
ClientPb.listUser                        thrpt       3   8.064 ± 0.659  ops/ms
ClientPb.createUser                       avgt       3   3.381 ± 0.436   ms/op
ClientPb.existUser                        avgt       3   3.360 ± 1.085   ms/op
ClientPb.getUser                          avgt       3   3.374 ± 1.488   ms/op
ClientPb.listUser                         avgt       3   3.918 ± 0.432   ms/op
ClientPb.createUser                     sample  278855   3.442 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.947           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.375           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.166           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.800           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.289           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.412           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.051           ms/op
ClientPb.existUser                      sample  291899   3.283 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.882           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.162           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.969           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.603           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.043           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.897           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.395           ms/op
ClientPb.getUser                        sample  277625   3.455 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.380           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.629           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.934           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.882           ms/op
ClientPb.listUser                       sample  240841   3.984 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.604           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.891           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.620           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.050           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.794           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.526           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.738           ms/op
