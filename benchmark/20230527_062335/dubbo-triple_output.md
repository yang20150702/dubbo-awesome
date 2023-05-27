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
# Warmup Iteration   1: 2.275 ops/ms
# Warmup Iteration   2: 5.521 ops/ms
# Warmup Iteration   3: 8.846 ops/ms
Iteration   1: 9.270 ops/ms
Iteration   2: 9.277 ops/ms
Iteration   3: 9.302 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.283 ±(99.9%) 0.309 ops/ms [Average]
  (min, avg, max) = (9.270, 9.283, 9.302), stdev = 0.017
  CI (99.9%): [8.974, 9.592] (assumes normal distribution)


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
# Warmup Iteration   1: 3.031 ops/ms
# Warmup Iteration   2: 8.727 ops/ms
# Warmup Iteration   3: 9.571 ops/ms
Iteration   1: 9.543 ops/ms
Iteration   2: 9.870 ops/ms
Iteration   3: 9.486 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.633 ±(99.9%) 3.778 ops/ms [Average]
  (min, avg, max) = (9.486, 9.633, 9.870), stdev = 0.207
  CI (99.9%): [5.855, 13.410] (assumes normal distribution)


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
# Warmup Iteration   1: 2.633 ops/ms
# Warmup Iteration   2: 8.276 ops/ms
# Warmup Iteration   3: 8.675 ops/ms
Iteration   1: 9.238 ops/ms
Iteration   2: 9.259 ops/ms
Iteration   3: 8.667 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.055 ±(99.9%) 6.125 ops/ms [Average]
  (min, avg, max) = (8.667, 9.055, 9.259), stdev = 0.336
  CI (99.9%): [2.930, 15.180] (assumes normal distribution)


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
# Warmup Iteration   1: 2.306 ops/ms
# Warmup Iteration   2: 7.096 ops/ms
# Warmup Iteration   3: 7.686 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.084 ops/ms
Iteration   3: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.043 ±(99.9%) 0.696 ops/ms [Average]
  (min, avg, max) = (8.008, 8.043, 8.084), stdev = 0.038
  CI (99.9%): [7.347, 8.740] (assumes normal distribution)


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
# Warmup Iteration   1: 9.770 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.532 ±(99.9%) 0.006 ms/op
Iteration   1: 3.374 ±(99.9%) 0.008 ms/op
Iteration   2: 3.342 ±(99.9%) 0.007 ms/op
Iteration   3: 3.222 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.312 ±(99.9%) 1.460 ms/op [Average]
  (min, avg, max) = (3.222, 3.312, 3.374), stdev = 0.080
  CI (99.9%): [1.853, 4.772] (assumes normal distribution)


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
# Warmup Iteration   1: 7.929 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.474 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.005 ms/op
Iteration   1: 3.328 ±(99.9%) 0.004 ms/op
Iteration   2: 3.287 ±(99.9%) 0.006 ms/op
Iteration   3: 3.279 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.298 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (3.279, 3.298, 3.328), stdev = 0.026
  CI (99.9%): [2.823, 3.773] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.472 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.703 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.450 ±(99.9%) 0.008 ms/op
Iteration   1: 3.500 ±(99.9%) 0.008 ms/op
Iteration   2: 3.420 ±(99.9%) 0.006 ms/op
Iteration   3: 3.411 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.444 ±(99.9%) 0.889 ms/op [Average]
  (min, avg, max) = (3.411, 3.444, 3.500), stdev = 0.049
  CI (99.9%): [2.555, 4.332] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.288 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.401 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.011 ms/op
Iteration   1: 4.015 ±(99.9%) 0.006 ms/op
Iteration   2: 3.927 ±(99.9%) 0.011 ms/op
Iteration   3: 3.843 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.928 ±(99.9%) 1.572 ms/op [Average]
  (min, avg, max) = (3.843, 3.928, 4.015), stdev = 0.086
  CI (99.9%): [2.357, 5.500] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 8.745 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.877 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.423 ±(99.9%) 0.010 ms/op
Iteration   1: 3.411 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.227 ms/op
                 createUser·p0.99:   5.726 ms/op
                 createUser·p0.999:  20.307 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   2: 3.442 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.520 ms/op
                 createUser·p0.50:   3.273 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  21.959 ms/op
                 createUser·p0.9999: 25.231 ms/op
                 createUser·p1.00:   26.149 ms/op

Iteration   3: 3.333 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.015 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   5.123 ms/op
                 createUser·p0.999:  19.829 ms/op
                 createUser·p0.9999: 25.048 ms/op
                 createUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 282560
  mean =      3.395 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6286 
    [ 2.500,  5.000) = 271437 
    [ 5.000,  7.500) = 3738 
    [ 7.500, 10.000) = 558 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 114 
    [22.500, 25.000) = 138 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.963 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.846 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =     19.952 ms/op
     p(99.9900) =     25.026 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.531 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.466 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.308 ±(99.9%) 0.008 ms/op
Iteration   1: 3.316 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.393 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   5.964 ms/op
                 existUser·p0.999:  15.174 ms/op
                 existUser·p0.9999: 23.801 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   2: 3.372 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.798 ms/op
                 existUser·p0.50:   3.297 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  10.373 ms/op
                 existUser·p0.9999: 25.035 ms/op
                 existUser·p1.00:   26.706 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.704 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.572 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  14.517 ms/op
                 existUser·p0.9999: 23.888 ms/op
                 existUser·p1.00:   24.642 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289525
  mean =      3.315 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10701 
    [ 2.500,  5.000) = 271561 
    [ 5.000,  7.500) = 6211 
    [ 7.500, 10.000) = 563 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 105 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 156 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     13.541 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.530 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 10.111 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 3.774 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.547 ±(99.9%) 0.011 ms/op
Iteration   1: 3.474 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.840 ms/op
                 getUser·p0.999:  19.588 ms/op
                 getUser·p0.9999: 23.259 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   2: 3.375 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.495 ms/op
                 getUser·p0.50:   3.244 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.965 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  21.172 ms/op
                 getUser·p0.9999: 27.476 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   3: 3.431 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.288 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.809 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  17.853 ms/op
                 getUser·p0.9999: 26.149 ms/op
                 getUser·p1.00:   27.230 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280092
  mean =      3.426 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2199 
    [ 2.500,  5.000) = 269467 
    [ 5.000,  7.500) = 7407 
    [ 7.500, 10.000) = 495 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 71 
    [27.500, 30.000) = 7 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.288 ms/op
     p(50.0000) =      3.256 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     18.481 ms/op
     p(99.9900) =     26.149 ms/op
     p(99.9990) =     27.813 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


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
# Warmup Iteration   1: 11.600 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.015 ms/op
Iteration   1: 4.081 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   7.741 ms/op
                 listUser·p0.999:  23.898 ms/op
                 listUser·p0.9999: 31.954 ms/op
                 listUser·p1.00:   32.145 ms/op

Iteration   2: 4.012 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.433 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.702 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  16.345 ms/op
                 listUser·p0.9999: 21.530 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.059 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.093 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   7.676 ms/op
                 listUser·p0.999:  15.368 ms/op
                 listUser·p0.9999: 23.171 ms/op
                 listUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 236790
  mean =      4.050 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 227066 
    [ 5.000,  7.500) = 7392 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 318 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 5 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 46 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.274 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.406 ms/op
     p(99.9000) =     16.302 ms/op
     p(99.9900) =     31.478 ms/op
     p(99.9990) =     32.047 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.283 ± 0.309  ops/ms
ClientPb.existUser                       thrpt       3   9.633 ± 3.778  ops/ms
ClientPb.getUser                         thrpt       3   9.055 ± 6.125  ops/ms
ClientPb.listUser                        thrpt       3   8.043 ± 0.696  ops/ms
ClientPb.createUser                       avgt       3   3.312 ± 1.460   ms/op
ClientPb.existUser                        avgt       3   3.298 ± 0.475   ms/op
ClientPb.getUser                          avgt       3   3.444 ± 0.889   ms/op
ClientPb.listUser                         avgt       3   3.928 ± 1.572   ms/op
ClientPb.createUser                     sample  282560   3.395 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.963           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.265           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.846           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.202           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.603           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.952           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.026           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.149           ms/op
ClientPb.existUser                      sample  289525   3.315 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.393           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.613           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.014           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.103           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.541           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.314           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.706           ms/op
ClientPb.getUser                        sample  280092   3.426 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.288           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.256           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.793           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.423           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.481           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.149           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.310           ms/op
ClientPb.listUser                       sample  236790   4.050 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.274           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.854           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.406           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.302           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.478           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.145           ms/op
