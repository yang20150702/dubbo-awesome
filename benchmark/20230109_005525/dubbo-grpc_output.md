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
# Warmup Iteration   1: 4.560 ops/ms
# Warmup Iteration   2: 9.301 ops/ms
# Warmup Iteration   3: 10.372 ops/ms
Iteration   1: 10.307 ops/ms
Iteration   2: 10.571 ops/ms
Iteration   3: 10.415 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.431 ±(99.9%) 2.429 ops/ms [Average]
  (min, avg, max) = (10.307, 10.431, 10.571), stdev = 0.133
  CI (99.9%): [8.003, 12.860] (assumes normal distribution)


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
# Warmup Iteration   1: 7.964 ops/ms
# Warmup Iteration   2: 10.605 ops/ms
# Warmup Iteration   3: 10.771 ops/ms
Iteration   1: 10.950 ops/ms
Iteration   2: 10.866 ops/ms
Iteration   3: 10.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.850 ±(99.9%) 1.990 ops/ms [Average]
  (min, avg, max) = (10.733, 10.850, 10.950), stdev = 0.109
  CI (99.9%): [8.860, 12.839] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.795 ops/ms
# Warmup Iteration   2: 10.322 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.771 ops/ms
Iteration   2: 10.526 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.623 ±(99.9%) 2.371 ops/ms [Average]
  (min, avg, max) = (10.526, 10.623, 10.771), stdev = 0.130
  CI (99.9%): [8.252, 12.994] (assumes normal distribution)


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
# Warmup Iteration   1: 6.244 ops/ms
# Warmup Iteration   2: 7.800 ops/ms
# Warmup Iteration   3: 7.979 ops/ms
Iteration   1: 7.899 ops/ms
Iteration   2: 8.153 ops/ms
Iteration   3: 7.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.957 ±(99.9%) 3.188 ops/ms [Average]
  (min, avg, max) = (7.818, 7.957, 8.153), stdev = 0.175
  CI (99.9%): [4.769, 11.144] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.055 ±(99.9%) 0.003 ms/op
Iteration   2: 3.056 ±(99.9%) 0.002 ms/op
Iteration   3: 3.008 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.040 ±(99.9%) 0.494 ms/op [Average]
  (min, avg, max) = (3.008, 3.040, 3.056), stdev = 0.027
  CI (99.9%): [2.545, 3.534] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.198 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.003 ms/op
Iteration   1: 2.918 ±(99.9%) 0.002 ms/op
Iteration   2: 2.942 ±(99.9%) 0.003 ms/op
Iteration   3: 2.934 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.931 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.918, 2.931, 2.942), stdev = 0.012
  CI (99.9%): [2.713, 3.149] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.196 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.005 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 3.087 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.066 ±(99.9%) 0.331 ms/op [Average]
  (min, avg, max) = (3.055, 3.066, 3.087), stdev = 0.018
  CI (99.9%): [2.735, 3.398] (assumes normal distribution)


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
# Warmup Iteration   1: 4.419 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.032 ms/op
Iteration   1: 4.028 ±(99.9%) 0.019 ms/op
Iteration   2: 3.999 ±(99.9%) 0.020 ms/op
Iteration   3: 4.100 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.042 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.999, 4.042, 4.100), stdev = 0.052
  CI (99.9%): [3.098, 4.987] (assumes normal distribution)


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
# Warmup Iteration   1: 3.909 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.711 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.467 ms/op
                 createUser·p0.9999: 12.507 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.178 ms/op
                 createUser·p0.999:  6.018 ms/op
                 createUser·p0.9999: 13.495 ms/op
                 createUser·p1.00:   13.795 ms/op

Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.312 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.584 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  10.177 ms/op
                 createUser·p0.9999: 20.190 ms/op
                 createUser·p1.00:   21.103 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319929
  mean =      3.000 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32244 
    [ 2.500,  5.000) = 286748 
    [ 5.000,  7.500) = 655 
    [ 7.500, 10.000) = 47 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.312 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.726 ms/op
     p(99.9900) =     15.369 ms/op
     p(99.9990) =     21.031 ms/op
     p(99.9999) =     21.103 ms/op
    p(100.0000) =     21.103 ms/op


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
# Warmup Iteration   1: 3.825 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.021 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.007 ms/op
Iteration   1: 2.908 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  5.890 ms/op
                 existUser·p0.9999: 11.092 ms/op
                 existUser·p1.00:   11.436 ms/op

Iteration   2: 2.949 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.676 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.609 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  5.652 ms/op
                 existUser·p0.9999: 12.527 ms/op
                 existUser·p1.00:   13.189 ms/op

Iteration   3: 3.035 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  9.933 ms/op
                 existUser·p0.9999: 14.956 ms/op
                 existUser·p1.00:   15.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323966
  mean =      2.963 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2452 
    [ 1.250,  2.500) = 40919 
    [ 2.500,  3.750) = 261320 
    [ 3.750,  5.000) = 18395 
    [ 5.000,  6.250) = 395 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 33 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.659 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.178 ms/op
     p(99.9000) =      7.152 ms/op
     p(99.9900) =     13.976 ms/op
     p(99.9990) =     15.560 ms/op
     p(99.9999) =     15.974 ms/op
    p(100.0000) =     15.974 ms/op


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
# Warmup Iteration   1: 3.931 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.138 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.986 ±(99.9%) 0.006 ms/op
Iteration   1: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.745 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.426 ms/op
                 getUser·p0.9999: 16.727 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.106 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.777 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.398 ms/op
                 getUser·p0.9999: 12.608 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.326 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.682 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.030 ms/op
                 getUser·p0.9999: 19.833 ms/op
                 getUser·p1.00:   20.251 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315654
  mean =      3.041 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30346 
    [ 2.500,  5.000) = 284403 
    [ 5.000,  7.500) = 694 
    [ 7.500, 10.000) = 51 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.603 ms/op
     p(99.9900) =     17.840 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 5.403 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.829 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.400 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.988 ms/op

Iteration   2: 3.863 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.719 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  13.945 ms/op
                 listUser·p0.9999: 19.946 ms/op
                 listUser·p1.00:   20.513 ms/op

Iteration   3: 4.024 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.669 ms/op
                 listUser·p0.999:  16.646 ms/op
                 listUser·p0.9999: 21.237 ms/op
                 listUser·p1.00:   21.725 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245895
  mean =      3.903 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3794 
    [ 2.500,  5.000) = 217372 
    [ 5.000,  7.500) = 23662 
    [ 7.500, 10.000) = 624 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.719 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     20.756 ms/op
     p(99.9990) =     21.630 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.431 ± 2.429  ops/ms
ClientGrpc.existUser                       thrpt       3  10.850 ± 1.990  ops/ms
ClientGrpc.getUser                         thrpt       3  10.623 ± 2.371  ops/ms
ClientGrpc.listUser                        thrpt       3   7.957 ± 3.188  ops/ms
ClientGrpc.createUser                       avgt       3   3.040 ± 0.494   ms/op
ClientGrpc.existUser                        avgt       3   2.931 ± 0.218   ms/op
ClientGrpc.getUser                          avgt       3   3.066 ± 0.331   ms/op
ClientGrpc.listUser                         avgt       3   4.042 ± 0.944   ms/op
ClientGrpc.createUser                     sample  319929   3.000 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.312           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.325           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.726           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.369           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.103           ms/op
ClientGrpc.existUser                      sample  323966   2.963 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.659           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.797           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.178           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.152           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.976           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.974           ms/op
ClientGrpc.getUser                        sample  315654   3.041 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.326           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.682           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.603           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.840           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.251           ms/op
ClientGrpc.listUser                       sample  245895   3.903 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.719           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.726           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.756           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.725           ms/op
