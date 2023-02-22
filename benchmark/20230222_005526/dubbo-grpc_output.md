# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.877 ops/ms
# Warmup Iteration   2: 9.487 ops/ms
# Warmup Iteration   3: 10.287 ops/ms
Iteration   1: 10.722 ops/ms
Iteration   2: 10.244 ops/ms
Iteration   3: 10.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.412 ±(99.9%) 4.906 ops/ms [Average]
  (min, avg, max) = (10.244, 10.412, 10.722), stdev = 0.269
  CI (99.9%): [5.507, 15.318] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.916 ops/ms
# Warmup Iteration   2: 10.249 ops/ms
# Warmup Iteration   3: 10.646 ops/ms
Iteration   1: 10.718 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.723 ±(99.9%) 1.984 ops/ms [Average]
  (min, avg, max) = (10.617, 10.723, 10.834), stdev = 0.109
  CI (99.9%): [8.739, 12.707] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ops/ms
# Warmup Iteration   2: 10.270 ops/ms
# Warmup Iteration   3: 10.492 ops/ms
Iteration   1: 10.211 ops/ms
Iteration   2: 10.370 ops/ms
Iteration   3: 10.523 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.368 ±(99.9%) 2.845 ops/ms [Average]
  (min, avg, max) = (10.211, 10.368, 10.523), stdev = 0.156
  CI (99.9%): [7.523, 13.213] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.759 ops/ms
# Warmup Iteration   2: 7.768 ops/ms
# Warmup Iteration   3: 8.181 ops/ms
Iteration   1: 8.159 ops/ms
Iteration   2: 8.054 ops/ms
Iteration   3: 8.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.174 ±(99.9%) 2.329 ops/ms [Average]
  (min, avg, max) = (8.054, 8.174, 8.308), stdev = 0.128
  CI (99.9%): [5.845, 10.503] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.982 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.001 ms/op
Iteration   1: 3.156 ±(99.9%) 0.002 ms/op
Iteration   2: 3.158 ±(99.9%) 0.002 ms/op
Iteration   3: 3.167 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.161 ±(99.9%) 0.105 ms/op [Average]
  (min, avg, max) = (3.156, 3.161, 3.167), stdev = 0.006
  CI (99.9%): [3.055, 3.266] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.662 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.002 ms/op
Iteration   1: 2.984 ±(99.9%) 0.002 ms/op
Iteration   2: 2.968 ±(99.9%) 0.003 ms/op
Iteration   3: 2.887 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.946 ±(99.9%) 0.950 ms/op [Average]
  (min, avg, max) = (2.887, 2.946, 2.984), stdev = 0.052
  CI (99.9%): [1.996, 3.897] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.720 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.002 ms/op
Iteration   1: 3.115 ±(99.9%) 0.002 ms/op
Iteration   2: 3.037 ±(99.9%) 0.003 ms/op
Iteration   3: 2.905 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.019 ±(99.9%) 1.943 ms/op [Average]
  (min, avg, max) = (2.905, 3.019, 3.115), stdev = 0.106
  CI (99.9%): [1.076, 4.962] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.547 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.009 ±(99.9%) 0.008 ms/op
Iteration   1: 4.054 ±(99.9%) 0.021 ms/op
Iteration   2: 3.978 ±(99.9%) 0.022 ms/op
Iteration   3: 4.110 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 1.204 ms/op [Average]
  (min, avg, max) = (3.978, 4.047, 4.110), stdev = 0.066
  CI (99.9%): [2.844, 5.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.792 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
Iteration   1: 3.076 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.772 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  8.102 ms/op
                 createUser·p0.9999: 22.073 ms/op
                 createUser·p1.00:   22.479 ms/op

Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.552 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  13.154 ms/op
                 createUser·p0.9999: 21.227 ms/op
                 createUser·p1.00:   22.020 ms/op

Iteration   3: 2.954 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.450 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  6.958 ms/op
                 createUser·p0.9999: 20.881 ms/op
                 createUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316293
  mean =      3.033 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37743 
    [ 2.500,  5.000) = 277400 
    [ 5.000,  7.500) = 754 
    [ 7.500, 10.000) = 117 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.450 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.678 ms/op
     p(95.0000) =      3.879 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.301 ms/op
     p(99.9900) =     21.541 ms/op
     p(99.9990) =     22.370 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.513 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.962 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.924 ±(99.9%) 0.007 ms/op
Iteration   1: 2.970 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.759 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  8.102 ms/op
                 existUser·p0.9999: 12.378 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 2.941 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  5.706 ms/op
                 existUser·p0.9999: 14.602 ms/op
                 existUser·p1.00:   14.991 ms/op

Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.579 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.465 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.194 ms/op
                 existUser·p0.999:  7.789 ms/op
                 existUser·p0.9999: 14.860 ms/op
                 existUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326558
  mean =      2.939 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1803 
    [ 1.250,  2.500) = 49670 
    [ 2.500,  3.750) = 260130 
    [ 3.750,  5.000) = 14074 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 74 
    [ 7.500,  8.750) = 108 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 55 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 85 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.668 ms/op
     p(99.9900) =     14.675 ms/op
     p(99.9990) =     16.882 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.823 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 2.998 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.851 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  6.843 ms/op
                 getUser·p0.9999: 12.135 ms/op
                 getUser·p1.00:   12.419 ms/op

Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.233 ms/op
                 getUser·p0.9999: 15.279 ms/op
                 getUser·p1.00:   17.105 ms/op

Iteration   3: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.263 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.271 ms/op
                 getUser·p0.9999: 14.945 ms/op
                 getUser·p1.00:   15.254 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319545
  mean =      3.002 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2056 
    [ 1.250,  2.500) = 31946 
    [ 2.500,  3.750) = 269082 
    [ 3.750,  5.000) = 15508 
    [ 5.000,  6.250) = 505 
    [ 6.250,  7.500) = 155 
    [ 7.500,  8.750) = 36 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 71 
    [15.000, 16.250) = 25 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.263 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.182 ms/op
     p(99.9000) =      7.184 ms/op
     p(99.9900) =     14.927 ms/op
     p(99.9990) =     15.454 ms/op
     p(99.9999) =     17.105 ms/op
    p(100.0000) =     17.105 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.220 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.206 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.837 ±(99.9%) 0.010 ms/op
Iteration   1: 3.998 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.936 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  12.009 ms/op
                 listUser·p0.9999: 15.351 ms/op
                 listUser·p1.00:   16.220 ms/op

Iteration   2: 3.931 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.009 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.571 ms/op
                 listUser·p0.999:  14.493 ms/op
                 listUser·p0.9999: 23.031 ms/op
                 listUser·p1.00:   24.281 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.233 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.866 ms/op
                 listUser·p0.95:   5.521 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  14.791 ms/op
                 listUser·p0.9999: 22.961 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242846
  mean =      3.952 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3767 
    [ 2.500,  5.000) = 212422 
    [ 5.000,  7.500) = 25535 
    [ 7.500, 10.000) = 601 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.781 ms/op
     p(99.9900) =     22.675 ms/op
     p(99.9990) =     24.211 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.412 ± 4.906  ops/ms
ClientGrpc.existUser                       thrpt       3  10.723 ± 1.984  ops/ms
ClientGrpc.getUser                         thrpt       3  10.368 ± 2.845  ops/ms
ClientGrpc.listUser                        thrpt       3   8.174 ± 2.329  ops/ms
ClientGrpc.createUser                       avgt       3   3.161 ± 0.105   ms/op
ClientGrpc.existUser                        avgt       3   2.946 ± 0.950   ms/op
ClientGrpc.getUser                          avgt       3   3.019 ± 1.943   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 1.204   ms/op
ClientGrpc.createUser                     sample  316293   3.033 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.450           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.678           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.879           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.293           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.301           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.541           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.479           ms/op
ClientGrpc.existUser                      sample  326558   2.939 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.428           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.920           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.731           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.145           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.668           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.675           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  319545   3.002 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.263           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.006           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.184           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.927           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.105           ms/op
ClientGrpc.listUser                       sample  242846   3.952 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.936           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.772           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.620           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.781           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.675           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.657           ms/op
