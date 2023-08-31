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
# Warmup Iteration   1: 1.887 ops/ms
# Warmup Iteration   2: 4.718 ops/ms
# Warmup Iteration   3: 8.361 ops/ms
Iteration   1: 8.913 ops/ms
Iteration   2: 9.204 ops/ms
Iteration   3: 9.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.073 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (8.913, 9.073, 9.204), stdev = 0.147
  CI (99.9%): [6.385, 11.761] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.569 ops/ms
# Warmup Iteration   2: 8.493 ops/ms
# Warmup Iteration   3: 8.996 ops/ms
Iteration   1: 9.363 ops/ms
Iteration   2: 9.658 ops/ms
Iteration   3: 9.547 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.523 ±(99.9%) 2.717 ops/ms [Average]
  (min, avg, max) = (9.363, 9.523, 9.658), stdev = 0.149
  CI (99.9%): [6.805, 12.240] (assumes normal distribution)


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
# Warmup Iteration   1: 2.479 ops/ms
# Warmup Iteration   2: 7.930 ops/ms
# Warmup Iteration   3: 8.606 ops/ms
Iteration   1: 8.878 ops/ms
Iteration   2: 8.918 ops/ms
Iteration   3: 9.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.955 ±(99.9%) 1.838 ops/ms [Average]
  (min, avg, max) = (8.878, 8.955, 9.069), stdev = 0.101
  CI (99.9%): [7.117, 10.793] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 2.620 ops/ms
# Warmup Iteration   2: 7.124 ops/ms
# Warmup Iteration   3: 7.234 ops/ms
Iteration   1: 7.582 ops/ms
Iteration   2: 7.674 ops/ms
Iteration   3: 7.414 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.557 ±(99.9%) 2.406 ops/ms [Average]
  (min, avg, max) = (7.414, 7.557, 7.674), stdev = 0.132
  CI (99.9%): [5.151, 9.963] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.922 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.852 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.006 ms/op
Iteration   1: 3.493 ±(99.9%) 0.008 ms/op
Iteration   2: 3.432 ±(99.9%) 0.011 ms/op
Iteration   3: 3.510 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.478 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (3.432, 3.478, 3.510), stdev = 0.041
  CI (99.9%): [2.731, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 11.324 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.455 ±(99.9%) 0.004 ms/op
Iteration   1: 3.285 ±(99.9%) 0.008 ms/op
Iteration   2: 3.418 ±(99.9%) 0.007 ms/op
Iteration   3: 3.306 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.337 ±(99.9%) 1.307 ms/op [Average]
  (min, avg, max) = (3.285, 3.337, 3.418), stdev = 0.072
  CI (99.9%): [2.030, 4.643] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.532 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.733 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.007 ms/op
Iteration   1: 3.609 ±(99.9%) 0.006 ms/op
Iteration   2: 3.415 ±(99.9%) 0.004 ms/op
Iteration   3: 3.481 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 1.805 ms/op [Average]
  (min, avg, max) = (3.415, 3.502, 3.609), stdev = 0.099
  CI (99.9%): [1.697, 5.307] (assumes normal distribution)


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
# Warmup Iteration   1: 12.055 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.644 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.009 ms/op
Iteration   1: 4.273 ±(99.9%) 0.008 ms/op
Iteration   2: 4.194 ±(99.9%) 0.005 ms/op
Iteration   3: 4.121 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.196 ±(99.9%) 1.390 ms/op [Average]
  (min, avg, max) = (4.121, 4.196, 4.273), stdev = 0.076
  CI (99.9%): [2.805, 5.586] (assumes normal distribution)


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
# Warmup Iteration   1: 9.662 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.006 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.705 ±(99.9%) 0.013 ms/op
Iteration   1: 3.458 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.663 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   6.103 ms/op
                 createUser·p0.999:  23.215 ms/op
                 createUser·p0.9999: 27.729 ms/op
                 createUser·p1.00:   28.672 ms/op

Iteration   2: 3.576 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.449 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.571 ms/op
                 createUser·p0.99:   7.533 ms/op
                 createUser·p0.999:  24.761 ms/op
                 createUser·p0.9999: 27.171 ms/op
                 createUser·p1.00:   30.605 ms/op

Iteration   3: 3.553 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.264 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.063 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   6.439 ms/op
                 createUser·p0.999:  18.672 ms/op
                 createUser·p0.9999: 29.852 ms/op
                 createUser·p1.00:   32.735 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 272042
  mean =      3.528 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3919 
    [ 2.500,  5.000) = 260006 
    [ 5.000,  7.500) = 6112 
    [ 7.500, 10.000) = 1219 
    [10.000, 12.500) = 310 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 91 
    [25.000, 27.500) = 121 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.264 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      3.953 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     23.429 ms/op
     p(99.9900) =     29.327 ms/op
     p(99.9990) =     31.082 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 9.235 ±(99.9%) 0.138 ms/op
# Warmup Iteration   2: 3.657 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.434 ±(99.9%) 0.009 ms/op
Iteration   1: 3.325 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  18.075 ms/op
                 existUser·p0.9999: 30.335 ms/op
                 existUser·p1.00:   32.178 ms/op

Iteration   2: 3.413 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.270 ms/op
                 existUser·p0.50:   3.305 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   4.211 ms/op
                 existUser·p0.99:   6.947 ms/op
                 existUser·p0.999:  23.200 ms/op
                 existUser·p0.9999: 29.446 ms/op
                 existUser·p1.00:   30.343 ms/op

Iteration   3: 3.394 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.529 ms/op
                 existUser·p0.999:  20.311 ms/op
                 existUser·p0.9999: 30.260 ms/op
                 existUser·p1.00:   30.736 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 284247
  mean =      3.377 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12916 
    [ 2.500,  5.000) = 263979 
    [ 5.000,  7.500) = 5535 
    [ 7.500, 10.000) = 1193 
    [10.000, 12.500) = 272 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 100 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.270 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     20.423 ms/op
     p(99.9900) =     29.843 ms/op
     p(99.9990) =     31.431 ms/op
     p(99.9999) =     32.178 ms/op
    p(100.0000) =     32.178 ms/op


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
# Warmup Iteration   1: 11.648 ±(99.9%) 0.168 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.632 ±(99.9%) 0.011 ms/op
Iteration   1: 3.565 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.899 ms/op
                 getUser·p0.99:   7.430 ms/op
                 getUser·p0.999:  21.433 ms/op
                 getUser·p0.9999: 25.461 ms/op
                 getUser·p1.00:   27.263 ms/op

Iteration   2: 3.377 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   3.240 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.734 ms/op
                 getUser·p0.999:  23.997 ms/op
                 getUser·p0.9999: 31.654 ms/op
                 getUser·p1.00:   32.145 ms/op

Iteration   3: 3.440 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.830 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   6.095 ms/op
                 getUser·p0.999:  25.066 ms/op
                 getUser·p0.9999: 27.361 ms/op
                 getUser·p1.00:   28.639 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277606
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5723 
    [ 2.500,  5.000) = 263338 
    [ 5.000,  7.500) = 6724 
    [ 7.500, 10.000) = 1074 
    [10.000, 12.500) = 399 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 136 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.699 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.227 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     21.541 ms/op
     p(99.9900) =     30.573 ms/op
     p(99.9990) =     31.800 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 13.099 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.436 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.016 ms/op
Iteration   1: 4.117 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.651 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.424 ms/op
                 listUser·p0.95:   4.956 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  22.785 ms/op
                 listUser·p0.9999: 27.271 ms/op
                 listUser·p1.00:   30.867 ms/op

Iteration   2: 4.119 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   8.053 ms/op
                 listUser·p0.999:  16.274 ms/op
                 listUser·p0.9999: 19.759 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   3: 4.156 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.071 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.071 ms/op
                 listUser·p0.99:   8.765 ms/op
                 listUser·p0.999:  18.219 ms/op
                 listUser·p0.9999: 21.037 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 232376
  mean =      4.131 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45 
    [ 2.500,  5.000) = 220419 
    [ 5.000,  7.500) = 8263 
    [ 7.500, 10.000) = 2512 
    [10.000, 12.500) = 533 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 176 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.651 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     18.076 ms/op
     p(99.9900) =     26.174 ms/op
     p(99.9990) =     30.376 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.073 ± 2.688  ops/ms
ClientPb.existUser                       thrpt       3   9.523 ± 2.717  ops/ms
ClientPb.getUser                         thrpt       3   8.955 ± 1.838  ops/ms
ClientPb.listUser                        thrpt       3   7.557 ± 2.406  ops/ms
ClientPb.createUser                       avgt       3   3.478 ± 0.748   ms/op
ClientPb.existUser                        avgt       3   3.337 ± 1.307   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 1.805   ms/op
ClientPb.listUser                         avgt       3   4.196 ± 1.390   ms/op
ClientPb.createUser                     sample  272042   3.528 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.264           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.387           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.953           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.685           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.429           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.327           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.735           ms/op
ClientPb.existUser                      sample  284247   3.377 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.270           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.269           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.727           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.529           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.423           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.843           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.178           ms/op
ClientPb.getUser                        sample  277606   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.699           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.326           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.922           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.541           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.573           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.145           ms/op
ClientPb.listUser                       sample  232376   4.131 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.651           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.932           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.538           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.030           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.076           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.174           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.867           ms/op
