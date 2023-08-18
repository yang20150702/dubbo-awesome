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
# Warmup Iteration   1: 2.590 ops/ms
# Warmup Iteration   2: 6.418 ops/ms
# Warmup Iteration   3: 8.774 ops/ms
Iteration   1: 9.630 ops/ms
Iteration   2: 9.726 ops/ms
Iteration   3: 9.768 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.708 ±(99.9%) 1.289 ops/ms [Average]
  (min, avg, max) = (9.630, 9.708, 9.768), stdev = 0.071
  CI (99.9%): [8.419, 10.997] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.603 ops/ms
# Warmup Iteration   2: 9.419 ops/ms
# Warmup Iteration   3: 9.883 ops/ms
Iteration   1: 10.267 ops/ms
Iteration   2: 10.328 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.297 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (10.267, 10.297, 10.328), stdev = 0.031
  CI (99.9%): [9.740, 10.854] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.518 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 10.054 ops/ms
Iteration   1: 9.871 ops/ms
Iteration   2: 10.069 ops/ms
Iteration   3: 9.802 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.914 ±(99.9%) 2.527 ops/ms [Average]
  (min, avg, max) = (9.802, 9.914, 10.069), stdev = 0.138
  CI (99.9%): [7.388, 12.441] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ops/ms
# Warmup Iteration   2: 7.769 ops/ms
# Warmup Iteration   3: 8.342 ops/ms
Iteration   1: 8.480 ops/ms
Iteration   2: 8.477 ops/ms
Iteration   3: 8.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.502 ±(99.9%) 0.740 ops/ms [Average]
  (min, avg, max) = (8.477, 8.502, 8.549), stdev = 0.041
  CI (99.9%): [7.761, 9.242] (assumes normal distribution)


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
# Warmup Iteration   1: 9.170 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.512 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.530 ±(99.9%) 0.005 ms/op
Iteration   1: 3.235 ±(99.9%) 0.005 ms/op
Iteration   2: 3.217 ±(99.9%) 0.003 ms/op
Iteration   3: 3.351 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.267 ±(99.9%) 1.323 ms/op [Average]
  (min, avg, max) = (3.217, 3.267, 3.351), stdev = 0.073
  CI (99.9%): [1.944, 4.591] (assumes normal distribution)


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
# Warmup Iteration   1: 7.132 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.426 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.005 ms/op
Iteration   1: 3.202 ±(99.9%) 0.002 ms/op
Iteration   2: 3.061 ±(99.9%) 0.006 ms/op
Iteration   3: 3.009 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.091 ±(99.9%) 1.818 ms/op [Average]
  (min, avg, max) = (3.009, 3.091, 3.202), stdev = 0.100
  CI (99.9%): [1.273, 4.909] (assumes normal distribution)


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
# Warmup Iteration   1: 7.084 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.448 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.395 ±(99.9%) 0.005 ms/op
Iteration   1: 3.279 ±(99.9%) 0.005 ms/op
Iteration   2: 3.254 ±(99.9%) 0.004 ms/op
Iteration   3: 3.232 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.255 ±(99.9%) 0.426 ms/op [Average]
  (min, avg, max) = (3.232, 3.255, 3.279), stdev = 0.023
  CI (99.9%): [2.829, 3.681] (assumes normal distribution)


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
# Warmup Iteration   1: 8.353 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.181 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.936 ±(99.9%) 0.005 ms/op
Iteration   1: 3.896 ±(99.9%) 0.006 ms/op
Iteration   2: 3.885 ±(99.9%) 0.005 ms/op
Iteration   3: 3.735 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.839 ±(99.9%) 1.641 ms/op [Average]
  (min, avg, max) = (3.735, 3.839, 3.896), stdev = 0.090
  CI (99.9%): [2.198, 5.479] (assumes normal distribution)


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
# Warmup Iteration   1: 8.065 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 3.669 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.221 ±(99.9%) 0.009 ms/op
Iteration   1: 3.264 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   3.195 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   4.186 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  15.643 ms/op
                 createUser·p0.9999: 28.602 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.915 ms/op
                 createUser·p0.50:   3.232 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   4.170 ms/op
                 createUser·p0.99:   6.431 ms/op
                 createUser·p0.999:  18.869 ms/op
                 createUser·p0.9999: 22.801 ms/op
                 createUser·p1.00:   24.871 ms/op

Iteration   3: 3.196 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   5.612 ms/op
                 createUser·p0.999:  15.204 ms/op
                 createUser·p0.9999: 19.759 ms/op
                 createUser·p1.00:   20.644 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 293999
  mean =      3.264 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19065 
    [ 2.500,  5.000) = 267458 
    [ 5.000,  7.500) = 6061 
    [ 7.500, 10.000) = 874 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 92 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.915 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     27.106 ms/op
     p(99.9990) =     29.362 ms/op
     p(99.9999) =     29.491 ms/op
    p(100.0000) =     29.491 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.201 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 3.514 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.136 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.421 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   4.141 ms/op
                 existUser·p0.99:   6.111 ms/op
                 existUser·p0.999:  11.509 ms/op
                 existUser·p0.9999: 21.201 ms/op
                 existUser·p1.00:   22.282 ms/op

Iteration   2: 3.159 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   4.284 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.677 ms/op
                 existUser·p0.9999: 21.310 ms/op
                 existUser·p1.00:   22.086 ms/op

Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   5.472 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 22.372 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 306593
  mean =      3.132 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16997 
    [ 2.500,  5.000) = 281952 
    [ 5.000,  7.500) = 6398 
    [ 7.500, 10.000) = 843 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 107 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.029 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     21.748 ms/op
     p(99.9990) =     23.296 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 7.723 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.552 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.338 ±(99.9%) 0.011 ms/op
Iteration   1: 3.293 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.489 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   4.465 ms/op
                 getUser·p0.99:   6.709 ms/op
                 getUser·p0.999:  12.677 ms/op
                 getUser·p0.9999: 23.087 ms/op
                 getUser·p1.00:   24.478 ms/op

Iteration   2: 3.224 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   5.874 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 23.699 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   3: 3.227 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.071 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   4.350 ms/op
                 getUser·p0.99:   6.447 ms/op
                 getUser·p0.999:  13.943 ms/op
                 getUser·p0.9999: 21.208 ms/op
                 getUser·p1.00:   22.512 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295409
  mean =      3.248 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8165 
    [ 2.500,  5.000) = 277532 
    [ 5.000,  7.500) = 8229 
    [ 7.500, 10.000) = 1130 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 38 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 86 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      6.570 ms/op
     p(99.9000) =     12.514 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.284 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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
# Warmup Iteration   1: 8.706 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 4.035 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.012 ms/op
Iteration   1: 3.791 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.626 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.504 ms/op
                 listUser·p0.999:  14.352 ms/op
                 listUser·p0.9999: 18.645 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   2: 3.754 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.958 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.174 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  12.796 ms/op
                 listUser·p0.9999: 13.926 ms/op
                 listUser·p1.00:   14.254 ms/op

Iteration   3: 3.795 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.031 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.121 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.758 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 19.564 ms/op
                 listUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253866
  mean =      3.780 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 109 
    [ 2.500,  5.000) = 244778 
    [ 5.000,  7.500) = 6491 
    [ 7.500, 10.000) = 1662 
    [10.000, 12.500) = 429 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.031 ms/op
     p(50.0000) =      3.658 ms/op
     p(90.0000) =      4.121 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.449 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     18.587 ms/op
     p(99.9990) =     20.036 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.708 ± 1.289  ops/ms
ClientPb.existUser                       thrpt       3  10.297 ± 0.557  ops/ms
ClientPb.getUser                         thrpt       3   9.914 ± 2.527  ops/ms
ClientPb.listUser                        thrpt       3   8.502 ± 0.740  ops/ms
ClientPb.createUser                       avgt       3   3.267 ± 1.323   ms/op
ClientPb.existUser                        avgt       3   3.091 ± 1.818   ms/op
ClientPb.getUser                          avgt       3   3.255 ± 0.426   ms/op
ClientPb.listUser                         avgt       3   3.839 ± 1.641   ms/op
ClientPb.createUser                     sample  293999   3.264 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.915           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.658           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.169           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.811           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.106           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.491           ms/op
ClientPb.existUser                      sample  306593   3.132 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.029           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.052           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.396           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.734           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.124           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.748           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.527           ms/op
ClientPb.getUser                        sample  295409   3.248 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.967           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.105           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.580           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.194           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.570           ms/op
ClientPb.getUser:getUser·p0.999         sample          12.514           ms/op
ClientPb.getUser:getUser·p0.9999        sample          23.298           ms/op
ClientPb.getUser:getUser·p1.00          sample          24.478           ms/op
ClientPb.listUser                       sample  253866   3.780 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.031           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.658           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.121           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.449           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.500           ms/op
ClientPb.listUser:listUser·p0.9999      sample          18.587           ms/op
ClientPb.listUser:listUser·p1.00        sample          20.513           ms/op
