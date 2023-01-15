# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.690 ops/ms
# Warmup Iteration   2: 9.279 ops/ms
# Warmup Iteration   3: 10.235 ops/ms
Iteration   1: 10.331 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.489 ±(99.9%) 2.561 ops/ms [Average]
  (min, avg, max) = (10.331, 10.489, 10.600), stdev = 0.140
  CI (99.9%): [7.928, 13.049] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.470 ops/ms
# Warmup Iteration   2: 10.616 ops/ms
# Warmup Iteration   3: 10.592 ops/ms
Iteration   1: 10.788 ops/ms
Iteration   2: 10.544 ops/ms
Iteration   3: 10.432 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.588 ±(99.9%) 3.323 ops/ms [Average]
  (min, avg, max) = (10.432, 10.588, 10.788), stdev = 0.182
  CI (99.9%): [7.265, 13.911] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.285 ops/ms
# Warmup Iteration   2: 10.446 ops/ms
# Warmup Iteration   3: 10.380 ops/ms
Iteration   1: 10.636 ops/ms
Iteration   2: 10.292 ops/ms
Iteration   3: 10.669 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.533 ±(99.9%) 3.807 ops/ms [Average]
  (min, avg, max) = (10.292, 10.533, 10.669), stdev = 0.209
  CI (99.9%): [6.726, 14.339] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.411 ops/ms
# Warmup Iteration   2: 7.826 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.170 ops/ms
Iteration   2: 7.986 ops/ms
Iteration   3: 8.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.125 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (7.986, 8.125, 8.219), stdev = 0.123
  CI (99.9%): [5.886, 10.363] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.979 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.038 ±(99.9%) 0.003 ms/op
Iteration   1: 3.165 ±(99.9%) 0.011 ms/op
Iteration   2: 3.192 ±(99.9%) 0.002 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.151 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (3.096, 3.151, 3.192), stdev = 0.050
  CI (99.9%): [2.244, 4.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.002 ms/op
Iteration   1: 2.980 ±(99.9%) 0.002 ms/op
Iteration   2: 2.931 ±(99.9%) 0.003 ms/op
Iteration   3: 2.873 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.928 ±(99.9%) 0.978 ms/op [Average]
  (min, avg, max) = (2.873, 2.928, 2.980), stdev = 0.054
  CI (99.9%): [1.950, 3.906] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.698 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.942 ±(99.9%) 0.003 ms/op
Iteration   1: 3.144 ±(99.9%) 0.002 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.085 ±(99.9%) 0.941 ms/op [Average]
  (min, avg, max) = (3.052, 3.085, 3.144), stdev = 0.052
  CI (99.9%): [2.144, 4.026] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.224 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.044 ±(99.9%) 0.012 ms/op
Iteration   1: 4.069 ±(99.9%) 0.020 ms/op
Iteration   2: 3.905 ±(99.9%) 0.040 ms/op
Iteration   3: 4.071 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 1.734 ms/op [Average]
  (min, avg, max) = (3.905, 4.015, 4.071), stdev = 0.095
  CI (99.9%): [2.281, 5.749] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.032 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.506 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.204 ms/op
                 createUser·p0.999:  6.532 ms/op
                 createUser·p0.9999: 15.084 ms/op
                 createUser·p1.00:   15.417 ms/op

Iteration   2: 3.128 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  6.783 ms/op
                 createUser·p0.9999: 16.089 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   3: 3.114 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.601 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.242 ms/op
                 createUser·p0.999:  10.240 ms/op
                 createUser·p0.9999: 18.472 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308797
  mean =      3.110 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 985 
    [ 1.250,  2.500) = 22375 
    [ 2.500,  3.750) = 255706 
    [ 3.750,  5.000) = 28907 
    [ 5.000,  6.250) = 359 
    [ 6.250,  7.500) = 111 
    [ 7.500,  8.750) = 35 
    [ 8.750, 10.000) = 69 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 30 
    [15.000, 16.250) = 63 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      9.182 ms/op
     p(99.9900) =     16.699 ms/op
     p(99.9990) =     18.767 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.820 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.917 ±(99.9%) 0.006 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  5.308 ms/op
                 existUser·p0.9999: 11.790 ms/op
                 existUser·p1.00:   12.370 ms/op

Iteration   2: 3.007 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.552 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.397 ms/op
                 existUser·p0.9999: 12.862 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   3: 3.009 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.464 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  8.761 ms/op
                 existUser·p0.9999: 15.036 ms/op
                 existUser·p1.00:   15.401 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319884
  mean =      3.003 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1653 
    [ 1.250,  2.500) = 40366 
    [ 2.500,  3.750) = 255615 
    [ 3.750,  5.000) = 21498 
    [ 5.000,  6.250) = 326 
    [ 6.250,  7.500) = 134 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.464 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.169 ms/op
     p(99.9900) =     14.729 ms/op
     p(99.9990) =     15.283 ms/op
     p(99.9999) =     15.401 ms/op
    p(100.0000) =     15.401 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.007 ms/op
Iteration   1: 3.010 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.369 ms/op
                 getUser·p0.9999: 11.469 ms/op
                 getUser·p1.00:   11.862 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.531 ms/op
                 getUser·p0.9999: 13.081 ms/op
                 getUser·p1.00:   13.550 ms/op

Iteration   3: 3.044 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.731 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.423 ms/op
                 getUser·p0.9999: 27.132 ms/op
                 getUser·p1.00:   27.460 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314056
  mean =      3.054 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24195 
    [ 2.500,  5.000) = 288840 
    [ 5.000,  7.500) = 821 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.813 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.520 ms/op
     p(99.9900) =     26.712 ms/op
     p(99.9990) =     27.324 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.338 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.010 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.069 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.612 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  12.621 ms/op
                 listUser·p0.9999: 20.019 ms/op
                 listUser·p1.00:   20.611 ms/op

Iteration   2: 4.063 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.483 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.620 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 15.798 ms/op
                 listUser·p1.00:   17.007 ms/op

Iteration   3: 4.030 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.926 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  13.913 ms/op
                 listUser·p0.9999: 25.398 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238979
  mean =      4.016 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2942 
    [ 2.500,  5.000) = 205995 
    [ 5.000,  7.500) = 28951 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.483 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.145 ms/op
     p(95.0000) =      5.595 ms/op
     p(99.0000) =      6.750 ms/op
     p(99.9000) =     13.550 ms/op
     p(99.9900) =     24.256 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.489 ± 2.561  ops/ms
ClientGrpc.existUser                       thrpt       3  10.588 ± 3.323  ops/ms
ClientGrpc.getUser                         thrpt       3  10.533 ± 3.807  ops/ms
ClientGrpc.listUser                        thrpt       3   8.125 ± 2.239  ops/ms
ClientGrpc.createUser                       avgt       3   3.151 ± 0.907   ms/op
ClientGrpc.existUser                        avgt       3   2.928 ± 0.978   ms/op
ClientGrpc.getUser                          avgt       3   3.085 ± 0.941   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 1.734   ms/op
ClientGrpc.createUser                     sample  308797   3.110 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.506           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.182           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.699           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  319884   3.003 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.464           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.834           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.169           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.729           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.401           ms/op
ClientGrpc.getUser                        sample  314056   3.054 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.592           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.813           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.520           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          26.712           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.460           ms/op
ClientGrpc.listUser                       sample  238979   4.016 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.483           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.145           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.595           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.750           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.550           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.256           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
