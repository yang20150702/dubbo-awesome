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
# Warmup Iteration   1: 4.171 ops/ms
# Warmup Iteration   2: 9.304 ops/ms
# Warmup Iteration   3: 9.994 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.665 ops/ms
Iteration   3: 10.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.564 ±(99.9%) 3.617 ops/ms [Average]
  (min, avg, max) = (10.336, 10.564, 10.692), stdev = 0.198
  CI (99.9%): [6.947, 14.181] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.429 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 11.168 ops/ms
Iteration   1: 11.219 ops/ms
Iteration   2: 11.198 ops/ms
Iteration   3: 11.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.181 ±(99.9%) 0.881 ops/ms [Average]
  (min, avg, max) = (11.127, 11.181, 11.219), stdev = 0.048
  CI (99.9%): [10.301, 12.062] (assumes normal distribution)


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
# Warmup Iteration   1: 7.126 ops/ms
# Warmup Iteration   2: 10.212 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.641 ops/ms
Iteration   2: 10.720 ops/ms
Iteration   3: 10.701 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.687 ±(99.9%) 0.758 ops/ms [Average]
  (min, avg, max) = (10.641, 10.687, 10.720), stdev = 0.042
  CI (99.9%): [9.930, 11.445] (assumes normal distribution)


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
# Warmup Iteration   1: 5.999 ops/ms
# Warmup Iteration   2: 7.739 ops/ms
# Warmup Iteration   3: 7.887 ops/ms
Iteration   1: 8.038 ops/ms
Iteration   2: 8.061 ops/ms
Iteration   3: 8.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.044 ±(99.9%) 0.268 ops/ms [Average]
  (min, avg, max) = (8.034, 8.044, 8.061), stdev = 0.015
  CI (99.9%): [7.776, 8.312] (assumes normal distribution)


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
# Warmup Iteration   1: 4.271 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.006 ms/op
Iteration   2: 3.005 ±(99.9%) 0.003 ms/op
Iteration   3: 2.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.006 ±(99.9%) 0.141 ms/op [Average]
  (min, avg, max) = (2.999, 3.006, 3.015), stdev = 0.008
  CI (99.9%): [2.865, 3.147] (assumes normal distribution)


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
# Warmup Iteration   1: 4.105 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.002 ms/op
Iteration   1: 2.836 ±(99.9%) 0.003 ms/op
Iteration   2: 2.893 ±(99.9%) 0.002 ms/op
Iteration   3: 2.851 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.860 ±(99.9%) 0.542 ms/op [Average]
  (min, avg, max) = (2.836, 2.860, 2.893), stdev = 0.030
  CI (99.9%): [2.318, 3.402] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.173 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.003 ms/op
Iteration   1: 3.004 ±(99.9%) 0.003 ms/op
Iteration   2: 3.052 ±(99.9%) 0.003 ms/op
Iteration   3: 3.015 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 0.459 ms/op [Average]
  (min, avg, max) = (3.004, 3.024, 3.052), stdev = 0.025
  CI (99.9%): [2.564, 3.483] (assumes normal distribution)


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
# Warmup Iteration   1: 5.262 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.937 ±(99.9%) 0.013 ms/op
Iteration   1: 3.917 ±(99.9%) 0.060 ms/op
Iteration   2: 3.912 ±(99.9%) 0.011 ms/op
Iteration   3: 3.926 ±(99.9%) 0.045 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.918 ±(99.9%) 0.127 ms/op [Average]
  (min, avg, max) = (3.912, 3.918, 3.926), stdev = 0.007
  CI (99.9%): [3.791, 4.045] (assumes normal distribution)


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
Iteration   1: 2.994 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.413 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  7.715 ms/op
                 createUser·p0.9999: 12.571 ms/op
                 createUser·p1.00:   12.927 ms/op

Iteration   2: 3.011 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.666 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.953 ms/op
                 createUser·p0.9999: 22.753 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 3.049 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.539 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.801 ms/op
                 createUser·p0.999:  11.966 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317955
  mean =      3.018 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27172 
    [ 2.500,  5.000) = 288934 
    [ 5.000,  7.500) = 1359 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.413 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.588 ms/op
     p(99.9000) =     10.028 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.991 ms/op
     p(99.9999) =     23.101 ms/op
    p(100.0000) =     23.101 ms/op


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.005 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.281 ms/op
                 existUser·p0.95:   3.400 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  8.142 ms/op
                 existUser·p0.9999: 17.660 ms/op
                 existUser·p1.00:   18.186 ms/op

Iteration   2: 2.920 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.671 ms/op
                 existUser·p0.9999: 17.564 ms/op
                 existUser·p1.00:   17.760 ms/op

Iteration   3: 2.926 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.573 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.408 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  7.182 ms/op
                 existUser·p0.9999: 24.843 ms/op
                 existUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329421
  mean =      2.913 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38484 
    [ 2.500,  5.000) = 289883 
    [ 5.000,  7.500) = 800 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.573 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.576 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.012 ms/op
     p(99.9900) =     18.474 ms/op
     p(99.9990) =     25.324 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.032 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.809 ms/op
                 getUser·p0.9999: 13.902 ms/op
                 getUser·p1.00:   14.123 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.760 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  8.231 ms/op
                 getUser·p0.9999: 17.302 ms/op
                 getUser·p1.00:   17.334 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.655 ms/op
                 getUser·p0.50:   2.974 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.691 ms/op
                 getUser·p0.9999: 16.754 ms/op
                 getUser·p1.00:   17.039 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316024
  mean =      3.036 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 544 
    [ 1.250,  2.500) = 20338 
    [ 2.500,  3.750) = 279292 
    [ 3.750,  5.000) = 14250 
    [ 5.000,  6.250) = 766 
    [ 6.250,  7.500) = 465 
    [ 7.500,  8.750) = 152 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 57 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 61 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      7.684 ms/op
     p(99.9900) =     16.777 ms/op
     p(99.9990) =     17.329 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.474 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.446 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.701 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.245 ms/op
                 listUser·p0.999:  15.142 ms/op
                 listUser·p0.9999: 19.497 ms/op
                 listUser·p1.00:   19.890 ms/op

Iteration   2: 3.974 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.916 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.669 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  18.907 ms/op
                 listUser·p0.9999: 25.985 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.895 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.591 ms/op
                 listUser·p0.9999: 23.723 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240752
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2309 
    [ 2.500,  5.000) = 214938 
    [ 5.000,  7.500) = 21983 
    [ 7.500, 10.000) = 1081 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.702 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     16.949 ms/op
     p(99.9900) =     24.705 ms/op
     p(99.9990) =     27.564 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.564 ± 3.617  ops/ms
ClientGrpc.existUser                       thrpt       3  11.181 ± 0.881  ops/ms
ClientGrpc.getUser                         thrpt       3  10.687 ± 0.758  ops/ms
ClientGrpc.listUser                        thrpt       3   8.044 ± 0.268  ops/ms
ClientGrpc.createUser                       avgt       3   3.006 ± 0.141   ms/op
ClientGrpc.existUser                        avgt       3   2.860 ± 0.542   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 0.459   ms/op
ClientGrpc.listUser                         avgt       3   3.918 ± 0.127   ms/op
ClientGrpc.createUser                     sample  317955   3.018 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.413           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.986           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.588           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.028           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.101           ms/op
ClientGrpc.existUser                      sample  329421   2.913 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.573           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.383           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.474           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.706           ms/op
ClientGrpc.getUser                        sample  316024   3.036 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.655           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.543           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.684           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.777           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.334           ms/op
ClientGrpc.listUser                       sample  240752   3.988 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.701           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.702           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.949           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.705           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
