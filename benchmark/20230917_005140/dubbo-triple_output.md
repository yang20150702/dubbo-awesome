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
# Warmup Iteration   1: 1.780 ops/ms
# Warmup Iteration   2: 4.506 ops/ms
# Warmup Iteration   3: 8.171 ops/ms
Iteration   1: 8.600 ops/ms
Iteration   2: 8.293 ops/ms
Iteration   3: 8.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  8.599 ±(99.9%) 5.566 ops/ms [Average]
  (min, avg, max) = (8.293, 8.599, 8.903), stdev = 0.305
  CI (99.9%): [3.033, 14.165] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.258 ops/ms
# Warmup Iteration   2: 7.753 ops/ms
# Warmup Iteration   3: 9.129 ops/ms
Iteration   1: 9.160 ops/ms
Iteration   2: 9.212 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.172 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (9.144, 9.172, 9.212), stdev = 0.036
  CI (99.9%): [8.521, 9.823] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.068 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 8.482 ops/ms
Iteration   1: 8.514 ops/ms
Iteration   2: 8.342 ops/ms
Iteration   3: 8.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.497 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (8.342, 8.497, 8.635), stdev = 0.147
  CI (99.9%): [5.809, 11.185] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 6.046 ops/ms
# Warmup Iteration   3: 6.852 ops/ms
Iteration   1: 7.302 ops/ms
Iteration   2: 7.355 ops/ms
Iteration   3: 7.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.343 ±(99.9%) 0.666 ops/ms [Average]
  (min, avg, max) = (7.302, 7.343, 7.372), stdev = 0.036
  CI (99.9%): [6.677, 8.009] (assumes normal distribution)


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
# Warmup Iteration   1: 12.305 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.691 ±(99.9%) 0.005 ms/op
Iteration   1: 3.527 ±(99.9%) 0.004 ms/op
Iteration   2: 3.531 ±(99.9%) 0.004 ms/op
Iteration   3: 3.448 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.502 ±(99.9%) 0.862 ms/op [Average]
  (min, avg, max) = (3.448, 3.502, 3.531), stdev = 0.047
  CI (99.9%): [2.640, 4.364] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 9.814 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.701 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.004 ms/op
Iteration   1: 3.351 ±(99.9%) 0.007 ms/op
Iteration   2: 3.431 ±(99.9%) 0.003 ms/op
Iteration   3: 3.404 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.395 ±(99.9%) 0.741 ms/op [Average]
  (min, avg, max) = (3.351, 3.395, 3.431), stdev = 0.041
  CI (99.9%): [2.654, 4.137] (assumes normal distribution)


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
# Warmup Iteration   1: 11.062 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.727 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.514 ±(99.9%) 0.003 ms/op
Iteration   1: 3.619 ±(99.9%) 0.005 ms/op
Iteration   2: 3.600 ±(99.9%) 0.003 ms/op
Iteration   3: 3.578 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.599 ±(99.9%) 0.374 ms/op [Average]
  (min, avg, max) = (3.578, 3.599, 3.619), stdev = 0.021
  CI (99.9%): [3.225, 3.973] (assumes normal distribution)


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
# Warmup Iteration   1: 11.263 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.588 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.222 ±(99.9%) 0.007 ms/op
Iteration   1: 4.293 ±(99.9%) 0.008 ms/op
Iteration   2: 4.157 ±(99.9%) 0.010 ms/op
Iteration   3: 4.173 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.208 ±(99.9%) 1.353 ms/op [Average]
  (min, avg, max) = (4.157, 4.208, 4.293), stdev = 0.074
  CI (99.9%): [2.855, 5.561] (assumes normal distribution)


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
# Warmup Iteration   1: 10.523 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.010 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.013 ms/op
Iteration   1: 3.450 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.419 ms/op
                 createUser·p0.50:   3.432 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.100 ms/op
                 createUser·p0.99:   5.677 ms/op
                 createUser·p0.999:  19.704 ms/op
                 createUser·p0.9999: 22.634 ms/op
                 createUser·p1.00:   23.003 ms/op

Iteration   2: 3.529 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.700 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   4.047 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  21.594 ms/op
                 createUser·p0.9999: 23.524 ms/op
                 createUser·p1.00:   24.674 ms/op

Iteration   3: 3.536 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.608 ms/op
                 createUser·p0.50:   3.424 ms/op
                 createUser·p0.90:   4.022 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  24.265 ms/op
                 createUser·p0.9999: 37.224 ms/op
                 createUser·p1.00:   37.356 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 273730
  mean =      3.505 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6926 
    [ 2.500,  5.000) = 261817 
    [ 5.000,  7.500) = 3815 
    [ 7.500, 10.000) = 506 
    [10.000, 12.500) = 289 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 144 
    [22.500, 25.000) = 105 
    [25.000, 27.500) = 28 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.416 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     21.144 ms/op
     p(99.9900) =     35.799 ms/op
     p(99.9990) =     37.307 ms/op
     p(99.9999) =     37.356 ms/op
    p(100.0000) =     37.356 ms/op


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
# Warmup Iteration   1: 9.769 ±(99.9%) 0.110 ms/op
# Warmup Iteration   2: 3.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.441 ±(99.9%) 0.009 ms/op
Iteration   1: 3.462 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.343 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.858 ms/op
                 existUser·p0.95:   4.202 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  21.955 ms/op
                 existUser·p0.9999: 24.076 ms/op
                 existUser·p1.00:   24.642 ms/op

Iteration   2: 3.353 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.296 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.677 ms/op
                 existUser·p0.999:  11.227 ms/op
                 existUser·p0.9999: 25.330 ms/op
                 existUser·p1.00:   25.788 ms/op

Iteration   3: 3.463 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.425 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   3.920 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   6.136 ms/op
                 existUser·p0.999:  23.790 ms/op
                 existUser·p0.9999: 27.793 ms/op
                 existUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 280256
  mean =      3.425 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8487 
    [ 2.500,  5.000) = 265892 
    [ 5.000,  7.500) = 4655 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 71 

  Percentiles, ms/op:
      p(0.0000) =      0.425 ms/op
     p(50.0000) =      3.326 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      6.087 ms/op
     p(99.9000) =     14.250 ms/op
     p(99.9900) =     26.608 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 10.144 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.822 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.685 ±(99.9%) 0.012 ms/op
Iteration   1: 3.527 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.237 ms/op
                 getUser·p0.50:   3.432 ms/op
                 getUser·p0.90:   3.977 ms/op
                 getUser·p0.95:   4.301 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  21.738 ms/op
                 getUser·p0.9999: 23.953 ms/op
                 getUser·p1.00:   24.707 ms/op

Iteration   2: 3.571 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.520 ms/op
                 getUser·p0.50:   3.457 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.194 ms/op
                 getUser·p0.99:   6.132 ms/op
                 getUser·p0.999:  24.216 ms/op
                 getUser·p0.9999: 27.672 ms/op
                 getUser·p1.00:   29.458 ms/op

Iteration   3: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   3.924 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   6.431 ms/op
                 getUser·p0.999:  21.266 ms/op
                 getUser·p0.9999: 28.749 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270744
  mean =      3.544 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2689 
    [ 2.500,  5.000) = 261739 
    [ 5.000,  7.500) = 5084 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.237 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      3.957 ms/op
     p(95.0000) =      4.252 ms/op
     p(99.0000) =      6.103 ms/op
     p(99.9000) =     21.602 ms/op
     p(99.9900) =     27.881 ms/op
     p(99.9990) =     29.530 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 12.075 ±(99.9%) 0.177 ms/op
# Warmup Iteration   2: 4.491 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.376 ±(99.9%) 0.012 ms/op
Iteration   1: 4.216 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   4.063 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  20.323 ms/op
                 listUser·p0.9999: 23.816 ms/op
                 listUser·p1.00:   24.543 ms/op

Iteration   2: 4.179 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.870 ms/op
                 listUser·p0.50:   4.014 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 19.225 ms/op
                 listUser·p1.00:   19.497 ms/op

Iteration   3: 4.221 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.417 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   4.620 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  16.151 ms/op
                 listUser·p0.9999: 17.741 ms/op
                 listUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 228166
  mean =      4.205 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 46 
    [ 2.500,  5.000) = 216604 
    [ 5.000,  7.500) = 9433 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 196 
    [12.500, 15.000) = 221 
    [15.000, 17.500) = 271 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.417 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.005 ms/op
     p(99.0000) =      7.277 ms/op
     p(99.9000) =     16.772 ms/op
     p(99.9900) =     23.140 ms/op
     p(99.9990) =     24.253 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   8.599 ± 5.566  ops/ms
ClientPb.existUser                       thrpt       3   9.172 ± 0.651  ops/ms
ClientPb.getUser                         thrpt       3   8.497 ± 2.688  ops/ms
ClientPb.listUser                        thrpt       3   7.343 ± 0.666  ops/ms
ClientPb.createUser                       avgt       3   3.502 ± 0.862   ms/op
ClientPb.existUser                        avgt       3   3.395 ± 0.741   ms/op
ClientPb.getUser                          avgt       3   3.599 ± 0.374   ms/op
ClientPb.listUser                         avgt       3   4.208 ± 1.353   ms/op
ClientPb.createUser                     sample  273730   3.505 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.419           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.416           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.973           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.252           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.972           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.144           ms/op
ClientPb.createUser:createUser·p0.9999  sample          35.799           ms/op
ClientPb.createUser:createUser·p1.00    sample          37.356           ms/op
ClientPb.existUser                      sample  280256   3.425 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.425           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.326           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.250           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.608           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.196           ms/op
ClientPb.getUser                        sample  270744   3.544 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.237           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.437           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.252           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.103           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.602           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.881           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.409           ms/op
ClientPb.listUser                       sample  228166   4.205 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.417           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.067           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.005           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.277           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.772           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.140           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.543           ms/op
