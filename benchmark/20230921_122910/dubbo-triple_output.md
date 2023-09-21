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
# Warmup Iteration   1: 1.845 ops/ms
# Warmup Iteration   2: 4.636 ops/ms
# Warmup Iteration   3: 8.407 ops/ms
Iteration   1: 9.113 ops/ms
Iteration   2: 9.268 ops/ms
Iteration   3: 9.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.257 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (9.113, 9.257, 9.390), stdev = 0.139
  CI (99.9%): [6.726, 11.788] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 2.849 ops/ms
# Warmup Iteration   2: 8.484 ops/ms
# Warmup Iteration   3: 8.944 ops/ms
Iteration   1: 9.540 ops/ms
Iteration   2: 9.362 ops/ms
Iteration   3: 9.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.518 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (9.362, 9.518, 9.654), stdev = 0.147
  CI (99.9%): [6.835, 12.202] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.713 ops/ms
# Warmup Iteration   2: 8.148 ops/ms
# Warmup Iteration   3: 9.008 ops/ms
Iteration   1: 9.143 ops/ms
Iteration   2: 8.999 ops/ms
Iteration   3: 9.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.064 ±(99.9%) 1.326 ops/ms [Average]
  (min, avg, max) = (8.999, 9.064, 9.143), stdev = 0.073
  CI (99.9%): [7.738, 10.390] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 2.754 ops/ms
# Warmup Iteration   2: 7.186 ops/ms
# Warmup Iteration   3: 7.427 ops/ms
Iteration   1: 7.588 ops/ms
Iteration   2: 7.827 ops/ms
Iteration   3: 7.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.622 ±(99.9%) 3.460 ops/ms [Average]
  (min, avg, max) = (7.452, 7.622, 7.827), stdev = 0.190
  CI (99.9%): [4.162, 11.082] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 11.588 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.999 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.695 ±(99.9%) 0.004 ms/op
Iteration   1: 3.423 ±(99.9%) 0.005 ms/op
Iteration   2: 3.479 ±(99.9%) 0.006 ms/op
Iteration   3: 3.458 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.453 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.423, 3.453, 3.479), stdev = 0.028
  CI (99.9%): [2.934, 3.973] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.673 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.714 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.545 ±(99.9%) 0.003 ms/op
Iteration   1: 3.442 ±(99.9%) 0.006 ms/op
Iteration   2: 3.288 ±(99.9%) 0.005 ms/op
Iteration   3: 3.402 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.378 ±(99.9%) 1.463 ms/op [Average]
  (min, avg, max) = (3.288, 3.378, 3.442), stdev = 0.080
  CI (99.9%): [1.915, 4.840] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.923 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.744 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.003 ms/op
Iteration   1: 3.549 ±(99.9%) 0.003 ms/op
Iteration   2: 3.491 ±(99.9%) 0.003 ms/op
Iteration   3: 3.465 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.502 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.465, 3.502, 3.549), stdev = 0.043
  CI (99.9%): [2.716, 4.288] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.480 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.524 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.006 ms/op
Iteration   1: 4.201 ±(99.9%) 0.008 ms/op
Iteration   2: 4.164 ±(99.9%) 0.004 ms/op
Iteration   3: 4.074 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.146 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (4.074, 4.146, 4.201), stdev = 0.065
  CI (99.9%): [2.959, 5.334] (assumes normal distribution)


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
# Warmup Iteration   1: 10.420 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.818 ±(99.9%) 0.016 ms/op
Iteration   1: 3.550 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.450 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  20.513 ms/op
                 createUser·p0.9999: 25.754 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 3.493 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.362 ms/op
                 createUser·p0.50:   3.342 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  21.843 ms/op
                 createUser·p0.9999: 24.199 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   3: 3.466 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.473 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.243 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  20.274 ms/op
                 createUser·p0.9999: 25.330 ms/op
                 createUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274099
  mean =      3.503 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4380 
    [ 2.500,  5.000) = 263768 
    [ 5.000,  7.500) = 4859 
    [ 7.500, 10.000) = 504 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 111 
    [22.500, 25.000) = 145 
    [25.000, 27.500) = 33 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.355 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     20.316 ms/op
     p(99.9900) =     25.185 ms/op
     p(99.9990) =     26.191 ms/op
     p(99.9999) =     27.754 ms/op
    p(100.0000) =     27.754 ms/op


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
# Warmup Iteration   1: 9.503 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 3.710 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.446 ±(99.9%) 0.008 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.688 ms/op
                 existUser·p0.50:   3.351 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   6.824 ms/op
                 existUser·p0.999:  19.825 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   25.461 ms/op

Iteration   2: 3.471 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.939 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.842 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   7.078 ms/op
                 existUser·p0.999:  20.729 ms/op
                 existUser·p0.9999: 23.979 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 3.471 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.386 ms/op
                 existUser·p0.50:   3.383 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.260 ms/op
                 existUser·p0.99:   5.800 ms/op
                 existUser·p0.999:  9.093 ms/op
                 existUser·p0.9999: 25.887 ms/op
                 existUser·p1.00:   28.377 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277266
  mean =      3.462 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6144 
    [ 2.500,  5.000) = 263472 
    [ 5.000,  7.500) = 6305 
    [ 7.500, 10.000) = 668 
    [10.000, 12.500) = 344 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 96 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 38 

  Percentiles, ms/op:
      p(0.0000) =      0.939 ms/op
     p(50.0000) =      3.351 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     13.189 ms/op
     p(99.9900) =     25.428 ms/op
     p(99.9990) =     26.812 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 8.045 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.723 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.662 ±(99.9%) 0.013 ms/op
Iteration   1: 3.568 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.626 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.284 ms/op
                 getUser·p0.99:   6.734 ms/op
                 getUser·p0.999:  17.105 ms/op
                 getUser·p0.9999: 19.204 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   2: 3.473 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.640 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.043 ms/op
                 getUser·p0.99:   5.977 ms/op
                 getUser·p0.999:  13.074 ms/op
                 getUser·p0.9999: 21.096 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.511 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.364 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  20.731 ms/op
                 getUser·p0.9999: 24.343 ms/op
                 getUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 272711
  mean =      3.517 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2070 
    [ 2.500,  5.000) = 263377 
    [ 5.000,  7.500) = 6242 
    [ 7.500, 10.000) = 588 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 117 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.364 ms/op
     p(50.0000) =      3.391 ms/op
     p(90.0000) =      3.891 ms/op
     p(95.0000) =      4.170 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     14.116 ms/op
     p(99.9900) =     22.699 ms/op
     p(99.9990) =     24.844 ms/op
     p(99.9999) =     25.166 ms/op
    p(100.0000) =     25.166 ms/op


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
# Warmup Iteration   1: 11.955 ±(99.9%) 0.155 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.013 ms/op
Iteration   1: 4.172 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.048 ms/op
                 listUser·p0.50:   4.051 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   4.801 ms/op
                 listUser·p0.99:   7.479 ms/op
                 listUser·p0.999:  21.027 ms/op
                 listUser·p0.9999: 24.445 ms/op
                 listUser·p1.00:   25.788 ms/op

Iteration   2: 4.188 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.294 ms/op
                 listUser·p0.50:   4.116 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   4.848 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  15.755 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.285 ms/op

Iteration   3: 4.195 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.153 ms/op
                 listUser·p0.99:   7.393 ms/op
                 listUser·p0.999:  15.303 ms/op
                 listUser·p0.9999: 20.808 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 229258
  mean =      4.185 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38 
    [ 2.500,  5.000) = 218595 
    [ 5.000,  7.500) = 8660 
    [ 7.500, 10.000) = 1147 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.956 ms/op
     p(99.0000) =      7.245 ms/op
     p(99.9000) =     16.626 ms/op
     p(99.9900) =     23.336 ms/op
     p(99.9990) =     25.585 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.257 ± 2.531  ops/ms
ClientPb.existUser                       thrpt       3   9.518 ± 2.684  ops/ms
ClientPb.getUser                         thrpt       3   9.064 ± 1.326  ops/ms
ClientPb.listUser                        thrpt       3   7.622 ± 3.460  ops/ms
ClientPb.createUser                       avgt       3   3.453 ± 0.520   ms/op
ClientPb.existUser                        avgt       3   3.378 ± 1.463   ms/op
ClientPb.getUser                          avgt       3   3.502 ± 0.786   ms/op
ClientPb.listUser                         avgt       3   4.146 ± 1.187   ms/op
ClientPb.createUser                     sample  274099   3.503 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.362           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.355           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.317           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.964           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.316           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.185           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.754           ms/op
ClientPb.existUser                      sample  277266   3.462 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.939           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.351           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.850           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.260           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.742           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.189           ms/op
ClientPb.existUser:existUser·p0.9999    sample          25.428           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  272711   3.517 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.364           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.391           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.170           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.537           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.116           ms/op
ClientPb.getUser:getUser·p0.9999        sample          22.699           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.166           ms/op
ClientPb.listUser                       sample  229258   4.185 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.048           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.055           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.956           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.245           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.626           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.336           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.788           ms/op
