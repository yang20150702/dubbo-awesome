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
# Warmup Iteration   1: 4.496 ops/ms
# Warmup Iteration   2: 9.165 ops/ms
# Warmup Iteration   3: 10.065 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.247 ops/ms
Iteration   3: 10.659 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.523 ±(99.9%) 4.365 ops/ms [Average]
  (min, avg, max) = (10.247, 10.523, 10.664), stdev = 0.239
  CI (99.9%): [6.158, 14.888] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ops/ms
# Warmup Iteration   2: 10.558 ops/ms
# Warmup Iteration   3: 10.537 ops/ms
Iteration   1: 10.785 ops/ms
Iteration   2: 10.692 ops/ms
Iteration   3: 10.842 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.773 ±(99.9%) 1.383 ops/ms [Average]
  (min, avg, max) = (10.692, 10.773, 10.842), stdev = 0.076
  CI (99.9%): [9.390, 12.156] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.605 ops/ms
# Warmup Iteration   2: 10.341 ops/ms
# Warmup Iteration   3: 10.279 ops/ms
Iteration   1: 10.530 ops/ms
Iteration   2: 10.271 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.429 ±(99.9%) 2.529 ops/ms [Average]
  (min, avg, max) = (10.271, 10.429, 10.530), stdev = 0.139
  CI (99.9%): [7.900, 12.957] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.893 ops/ms
# Warmup Iteration   2: 7.527 ops/ms
# Warmup Iteration   3: 7.860 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 7.804 ops/ms
Iteration   3: 7.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.852 ±(99.9%) 1.940 ops/ms [Average]
  (min, avg, max) = (7.779, 7.852, 7.974), stdev = 0.106
  CI (99.9%): [5.913, 9.792] (assumes normal distribution)


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.002 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
Iteration   3: 3.055 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.079 ±(99.9%) 1.024 ms/op [Average]
  (min, avg, max) = (3.040, 3.079, 3.144), stdev = 0.056
  CI (99.9%): [2.056, 4.103] (assumes normal distribution)


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
# Warmup Iteration   1: 3.789 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.952 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.008 ±(99.9%) 0.002 ms/op
Iteration   1: 2.952 ±(99.9%) 0.002 ms/op
Iteration   2: 3.008 ±(99.9%) 0.002 ms/op
Iteration   3: 2.910 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.957 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (2.910, 2.957, 3.008), stdev = 0.049
  CI (99.9%): [2.060, 3.853] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.936 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.115 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.157 ±(99.9%) 0.002 ms/op
Iteration   2: 3.132 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.100 ±(99.9%) 1.446 ms/op [Average]
  (min, avg, max) = (3.009, 3.100, 3.157), stdev = 0.079
  CI (99.9%): [1.654, 4.545] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 4.905 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.147 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.121 ±(99.9%) 0.014 ms/op
Iteration   1: 3.999 ±(99.9%) 0.056 ms/op
Iteration   2: 3.887 ±(99.9%) 0.011 ms/op
Iteration   3: 3.976 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.954 ±(99.9%) 1.077 ms/op [Average]
  (min, avg, max) = (3.887, 3.954, 3.999), stdev = 0.059
  CI (99.9%): [2.876, 5.031] (assumes normal distribution)


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
# Warmup Iteration   1: 4.164 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.117 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.528 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.300 ms/op
                 createUser·p0.9999: 14.766 ms/op
                 createUser·p1.00:   15.106 ms/op

Iteration   2: 3.086 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.708 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.744 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.657 ms/op
                 createUser·p0.9999: 17.105 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   3: 3.116 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.598 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.764 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  11.519 ms/op
                 createUser·p0.9999: 28.659 ms/op
                 createUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310449
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29302 
    [ 2.500,  5.000) = 280099 
    [ 5.000,  7.500) = 660 
    [ 7.500, 10.000) = 110 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.528 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     27.749 ms/op
     p(99.9990) =     30.402 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


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
# Warmup Iteration   1: 3.892 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.867 ±(99.9%) 0.006 ms/op
Iteration   1: 2.974 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.764 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  6.545 ms/op
                 existUser·p0.9999: 21.037 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.447 ms/op
                 existUser·p0.9999: 15.224 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.559 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.568 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  8.136 ms/op
                 existUser·p0.9999: 15.303 ms/op
                 existUser·p1.00:   17.498 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323852
  mean =      2.965 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41832 
    [ 2.500,  5.000) = 281117 
    [ 5.000,  7.500) = 591 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.559 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.174 ms/op
     p(99.9000) =      7.431 ms/op
     p(99.9900) =     19.412 ms/op
     p(99.9990) =     21.160 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.780 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.630 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  11.293 ms/op
                 getUser·p0.9999: 13.222 ms/op
                 getUser·p1.00:   13.468 ms/op

Iteration   2: 3.105 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.656 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  8.004 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.339 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.822 ms/op
                 getUser·p0.9999: 25.952 ms/op
                 getUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314145
  mean =      3.055 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26993 
    [ 2.500,  5.000) = 285858 
    [ 5.000,  7.500) = 876 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.654 ms/op
     p(95.0000) =      3.861 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      9.238 ms/op
     p(99.9900) =     23.782 ms/op
     p(99.9990) =     26.116 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.816 ms/op
                 listUser·p0.99:   6.955 ms/op
                 listUser·p0.999:  15.501 ms/op
                 listUser·p0.9999: 20.714 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 3.971 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   5.702 ms/op
                 listUser·p0.99:   7.127 ms/op
                 listUser·p0.999:  15.194 ms/op
                 listUser·p0.9999: 25.197 ms/op
                 listUser·p1.00:   25.297 ms/op

Iteration   3: 3.975 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.451 ms/op
                 listUser·p0.9999: 28.734 ms/op
                 listUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239784
  mean =      4.003 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4291 
    [ 2.500,  5.000) = 207118 
    [ 5.000,  7.500) = 26950 
    [ 7.500, 10.000) = 880 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.661 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     14.634 ms/op
     p(99.9900) =     27.001 ms/op
     p(99.9990) =     29.092 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.523 ± 4.365  ops/ms
ClientGrpc.existUser                       thrpt       3  10.773 ± 1.383  ops/ms
ClientGrpc.getUser                         thrpt       3  10.429 ± 2.529  ops/ms
ClientGrpc.listUser                        thrpt       3   7.852 ± 1.940  ops/ms
ClientGrpc.createUser                       avgt       3   3.079 ± 1.024   ms/op
ClientGrpc.existUser                        avgt       3   2.957 ± 0.896   ms/op
ClientGrpc.getUser                          avgt       3   3.100 ± 1.446   ms/op
ClientGrpc.listUser                         avgt       3   3.954 ± 1.077   ms/op
ClientGrpc.createUser                     sample  310449   3.095 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.528           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.932           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.651           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.749           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.474           ms/op
ClientGrpc.existUser                      sample  323852   2.965 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.559           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.945           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.752           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.174           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.431           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.412           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  314145   3.055 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.339           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.861           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.238           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.782           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.247           ms/op
ClientGrpc.listUser                       sample  239784   4.003 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.036           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.661           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.955           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.634           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.001           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          29.295           ms/op
