# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.426 ops/ms
# Warmup Iteration   2: 11.991 ops/ms
# Warmup Iteration   3: 12.456 ops/ms
Iteration   1: 12.677 ops/ms
Iteration   2: 12.711 ops/ms
Iteration   3: 12.830 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.739 ±(99.9%) 1.467 ops/ms [Average]
  (min, avg, max) = (12.677, 12.739, 12.830), stdev = 0.080
  CI (99.9%): [11.272, 14.206] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 8.221 ops/ms
# Warmup Iteration   2: 13.194 ops/ms
# Warmup Iteration   3: 13.246 ops/ms
Iteration   1: 13.253 ops/ms
Iteration   2: 13.154 ops/ms
Iteration   3: 13.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.170 ±(99.9%) 1.399 ops/ms [Average]
  (min, avg, max) = (13.102, 13.170, 13.253), stdev = 0.077
  CI (99.9%): [11.771, 14.569] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.757 ops/ms
# Warmup Iteration   2: 12.304 ops/ms
# Warmup Iteration   3: 12.779 ops/ms
Iteration   1: 12.789 ops/ms
Iteration   2: 12.697 ops/ms
Iteration   3: 12.804 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.763 ±(99.9%) 1.051 ops/ms [Average]
  (min, avg, max) = (12.697, 12.763, 12.804), stdev = 0.058
  CI (99.9%): [11.712, 13.815] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.766 ops/ms
# Warmup Iteration   2: 10.580 ops/ms
# Warmup Iteration   3: 10.742 ops/ms
Iteration   1: 10.776 ops/ms
Iteration   2: 10.779 ops/ms
Iteration   3: 10.789 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.781 ±(99.9%) 0.127 ops/ms [Average]
  (min, avg, max) = (10.776, 10.781, 10.789), stdev = 0.007
  CI (99.9%): [10.654, 10.909] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.030 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.562 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.512 ±(99.9%) 0.004 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.488 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.490 ±(99.9%) 0.065 ms/op [Average]
  (min, avg, max) = (2.488, 2.490, 2.494), stdev = 0.004
  CI (99.9%): [2.425, 2.556] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.462 ±(99.9%) 0.004 ms/op
Iteration   1: 2.407 ±(99.9%) 0.005 ms/op
Iteration   2: 2.423 ±(99.9%) 0.004 ms/op
Iteration   3: 2.404 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.411 ±(99.9%) 0.185 ms/op [Average]
  (min, avg, max) = (2.404, 2.411, 2.423), stdev = 0.010
  CI (99.9%): [2.226, 2.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.084 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.005 ms/op
Iteration   1: 2.473 ±(99.9%) 0.004 ms/op
Iteration   2: 2.471 ±(99.9%) 0.004 ms/op
Iteration   3: 2.470 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.027 ms/op [Average]
  (min, avg, max) = (2.470, 2.471, 2.473), stdev = 0.002
  CI (99.9%): [2.444, 2.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.766 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.004 ms/op
Iteration   1: 2.995 ±(99.9%) 0.006 ms/op
Iteration   2: 2.979 ±(99.9%) 0.004 ms/op
Iteration   3: 3.005 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.993 ±(99.9%) 0.239 ms/op [Average]
  (min, avg, max) = (2.979, 2.993, 3.005), stdev = 0.013
  CI (99.9%): [2.754, 3.231] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.169 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.614 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.505 ±(99.9%) 0.005 ms/op
Iteration   1: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.004 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.019 ms/op
                 createUser·p0.95:   3.138 ms/op
                 createUser·p0.99:   3.678 ms/op
                 createUser·p0.999:  8.043 ms/op
                 createUser·p0.9999: 13.901 ms/op
                 createUser·p1.00:   14.336 ms/op

Iteration   2: 2.511 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.371 ms/op
                 createUser·p0.50:   2.556 ms/op
                 createUser·p0.90:   3.043 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   3.940 ms/op
                 createUser·p0.999:  10.633 ms/op
                 createUser·p0.9999: 14.918 ms/op
                 createUser·p1.00:   15.876 ms/op

Iteration   3: 2.500 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   2.576 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.756 ms/op
                 createUser·p0.999:  8.119 ms/op
                 createUser·p0.9999: 9.664 ms/op
                 createUser·p1.00:   10.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383713
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 186333 
    [ 2.500,  3.750) = 193305 
    [ 3.750,  5.000) = 3030 
    [ 5.000,  6.250) = 377 
    [ 6.250,  7.500) = 115 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 70 
    [13.750, 15.000) = 42 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.035 ms/op
     p(95.0000) =      3.154 ms/op
     p(99.0000) =      3.777 ms/op
     p(99.9000) =      9.180 ms/op
     p(99.9900) =     13.894 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.876 ms/op
    p(100.0000) =     15.876 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.935 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.463 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.465 ±(99.9%) 0.005 ms/op
Iteration   1: 2.443 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.408 ms/op
                 existUser·p0.50:   2.507 ms/op
                 existUser·p0.90:   2.970 ms/op
                 existUser·p0.95:   3.068 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.743 ms/op
                 existUser·p0.9999: 13.843 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.480 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.970 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.146 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  6.481 ms/op
                 existUser·p0.9999: 12.059 ms/op
                 existUser·p1.00:   12.812 ms/op

Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.994 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.678 ms/op
                 existUser·p0.999:  8.357 ms/op
                 existUser·p0.9999: 11.174 ms/op
                 existUser·p1.00:   11.764 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 389665
  mean =      2.461 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 35 
    [ 1.250,  2.500) = 193362 
    [ 2.500,  3.750) = 191943 
    [ 3.750,  5.000) = 3140 
    [ 5.000,  6.250) = 740 
    [ 6.250,  7.500) = 57 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 89 
    [10.000, 11.250) = 83 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 59 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      2.990 ms/op
     p(95.0000) =      3.101 ms/op
     p(99.0000) =      3.842 ms/op
     p(99.9000) =      7.452 ms/op
     p(99.9900) =     13.207 ms/op
     p(99.9990) =     14.030 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.865 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.532 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.458 ±(99.9%) 0.005 ms/op
Iteration   1: 2.445 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.928 ms/op
                 getUser·p0.50:   2.425 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.121 ms/op
                 getUser·p0.99:   3.793 ms/op
                 getUser·p0.999:  8.075 ms/op
                 getUser·p0.9999: 15.085 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 2.482 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.399 ms/op
                 getUser·p0.50:   2.462 ms/op
                 getUser·p0.90:   3.027 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.309 ms/op
                 getUser·p0.9999: 12.964 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   2.417 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.133 ms/op
                 getUser·p0.99:   3.682 ms/op
                 getUser·p0.999:  6.779 ms/op
                 getUser·p0.9999: 11.104 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 390039
  mean =      2.459 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 123 
    [ 1.250,  2.500) = 202262 
    [ 2.500,  3.750) = 182525 
    [ 3.750,  5.000) = 4012 
    [ 5.000,  6.250) = 631 
    [ 6.250,  7.500) = 109 
    [ 7.500,  8.750) = 18 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 79 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.399 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.146 ms/op
     p(99.0000) =      3.936 ms/op
     p(99.9000) =      7.289 ms/op
     p(99.9900) =     13.779 ms/op
     p(99.9990) =     16.780 ms/op
     p(99.9999) =     16.908 ms/op
    p(100.0000) =     16.908 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.697 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.997 ±(99.9%) 0.008 ms/op
Iteration   1: 2.994 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.843 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.817 ms/op
                 listUser·p0.95:   4.342 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.343 ms/op
                 listUser·p0.9999: 10.846 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   2: 2.999 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.949 ms/op
                 listUser·p0.90:   3.834 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.149 ms/op
                 listUser·p0.9999: 10.764 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.903 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.558 ms/op
                 listUser·p0.999:  8.863 ms/op
                 listUser·p0.9999: 10.836 ms/op
                 listUser·p1.00:   12.517 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319419
  mean =      3.003 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 92743 
    [ 2.500,  3.750) = 189179 
    [ 3.750,  5.000) = 30405 
    [ 5.000,  6.250) = 5662 
    [ 6.250,  7.500) = 629 
    [ 7.500,  8.750) = 239 
    [ 8.750, 10.000) = 299 
    [10.000, 11.250) = 135 
    [11.250, 12.500) = 3 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.843 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.358 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =      9.110 ms/op
     p(99.9900) =     10.798 ms/op
     p(99.9990) =     11.662 ms/op
     p(99.9999) =     12.517 ms/op
    p(100.0000) =     12.517 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.739 ± 1.467  ops/ms
ClientPb.existUser                       thrpt       3  13.170 ± 1.399  ops/ms
ClientPb.getUser                         thrpt       3  12.763 ± 1.051  ops/ms
ClientPb.listUser                        thrpt       3  10.781 ± 0.127  ops/ms
ClientPb.createUser                       avgt       3   2.490 ± 0.065   ms/op
ClientPb.existUser                        avgt       3   2.411 ± 0.185   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.027   ms/op
ClientPb.listUser                         avgt       3   2.993 ± 0.239   ms/op
ClientPb.createUser                     sample  383713   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.371           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.035           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.154           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.777           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.180           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.894           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.876           ms/op
ClientPb.existUser                      sample  389665   2.461 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.408           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.990           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.101           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.842           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.452           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.207           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.074           ms/op
ClientPb.getUser                        sample  390039   2.459 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.399           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.433           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.146           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.936           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.289           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.779           ms/op
ClientPb.getUser:getUser·p1.00          sample          16.908           ms/op
ClientPb.listUser                       sample  319419   3.003 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.843           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.945           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.521           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.110           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.798           ms/op
ClientPb.listUser:listUser·p1.00        sample          12.517           ms/op
