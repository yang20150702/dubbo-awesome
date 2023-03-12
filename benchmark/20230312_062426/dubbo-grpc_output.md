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
# Warmup Iteration   1: 4.780 ops/ms
# Warmup Iteration   2: 9.688 ops/ms
# Warmup Iteration   3: 10.497 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.755 ±(99.9%) 1.411 ops/ms [Average]
  (min, avg, max) = (10.682, 10.755, 10.836), stdev = 0.077
  CI (99.9%): [9.344, 12.166] (assumes normal distribution)


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
# Warmup Iteration   1: 7.813 ops/ms
# Warmup Iteration   2: 11.061 ops/ms
# Warmup Iteration   3: 11.412 ops/ms
Iteration   1: 11.624 ops/ms
Iteration   2: 11.355 ops/ms
Iteration   3: 11.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.413 ±(99.9%) 3.447 ops/ms [Average]
  (min, avg, max) = (11.259, 11.413, 11.624), stdev = 0.189
  CI (99.9%): [7.966, 14.860] (assumes normal distribution)


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
# Warmup Iteration   1: 7.592 ops/ms
# Warmup Iteration   2: 10.614 ops/ms
# Warmup Iteration   3: 11.029 ops/ms
Iteration   1: 10.796 ops/ms
Iteration   2: 10.892 ops/ms
Iteration   3: 11.111 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.933 ±(99.9%) 2.945 ops/ms [Average]
  (min, avg, max) = (10.796, 10.933, 11.111), stdev = 0.161
  CI (99.9%): [7.988, 13.878] (assumes normal distribution)


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
# Warmup Iteration   1: 5.815 ops/ms
# Warmup Iteration   2: 8.059 ops/ms
# Warmup Iteration   3: 8.295 ops/ms
Iteration   1: 8.406 ops/ms
Iteration   2: 8.371 ops/ms
Iteration   3: 8.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.383 ±(99.9%) 0.362 ops/ms [Average]
  (min, avg, max) = (8.371, 8.383, 8.406), stdev = 0.020
  CI (99.9%): [8.021, 8.745] (assumes normal distribution)


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
# Warmup Iteration   1: 3.662 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.853 ±(99.9%) 0.003 ms/op
Iteration   1: 2.981 ±(99.9%) 0.002 ms/op
Iteration   2: 2.921 ±(99.9%) 0.003 ms/op
Iteration   3: 2.948 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.950 ±(99.9%) 0.547 ms/op [Average]
  (min, avg, max) = (2.921, 2.950, 2.981), stdev = 0.030
  CI (99.9%): [2.403, 3.497] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.758 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 2.895 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.764 ±(99.9%) 0.003 ms/op
Iteration   1: 2.816 ±(99.9%) 0.003 ms/op
Iteration   2: 2.812 ±(99.9%) 0.003 ms/op
Iteration   3: 2.836 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (2.812, 2.821, 2.836), stdev = 0.013
  CI (99.9%): [2.589, 3.053] (assumes normal distribution)


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
# Warmup Iteration   1: 3.901 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.002 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 2.918 ±(99.9%) 0.004 ms/op
Iteration   3: 2.937 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.921 ±(99.9%) 0.263 ms/op [Average]
  (min, avg, max) = (2.909, 2.921, 2.937), stdev = 0.014
  CI (99.9%): [2.658, 3.184] (assumes normal distribution)


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
# Warmup Iteration   1: 4.825 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.946 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.007 ms/op
Iteration   1: 3.726 ±(99.9%) 0.034 ms/op
Iteration   2: 3.775 ±(99.9%) 0.017 ms/op
Iteration   3: 3.809 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.770 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.726, 3.770, 3.809), stdev = 0.042
  CI (99.9%): [3.005, 4.536] (assumes normal distribution)


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
# Warmup Iteration   1: 3.979 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.051 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
Iteration   1: 2.939 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.574 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  6.701 ms/op
                 createUser·p0.9999: 15.567 ms/op
                 createUser·p1.00:   16.581 ms/op

Iteration   2: 2.986 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  6.281 ms/op
                 createUser·p0.9999: 16.127 ms/op
                 createUser·p1.00:   16.663 ms/op

Iteration   3: 2.986 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.573 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  8.827 ms/op
                 createUser·p0.9999: 21.169 ms/op
                 createUser·p1.00:   21.398 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 323090
  mean =      2.970 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37362 
    [ 2.500,  5.000) = 284206 
    [ 5.000,  7.500) = 1152 
    [ 7.500, 10.000) = 138 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      8.110 ms/op
     p(99.9900) =     18.346 ms/op
     p(99.9990) =     21.398 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.818 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.922 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.005 ms/op
Iteration   1: 2.921 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   3.994 ms/op
                 existUser·p0.999:  5.980 ms/op
                 existUser·p0.9999: 11.470 ms/op
                 existUser·p1.00:   11.780 ms/op

Iteration   2: 2.803 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.554 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.293 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  6.083 ms/op
                 existUser·p0.9999: 12.399 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.849 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.486 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  10.067 ms/op
                 existUser·p0.9999: 16.597 ms/op
                 existUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335881
  mean =      2.857 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2582 
    [ 1.250,  2.500) = 45926 
    [ 2.500,  3.750) = 279962 
    [ 3.750,  5.000) = 6521 
    [ 5.000,  6.250) = 470 
    [ 6.250,  7.500) = 86 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.326 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =      7.480 ms/op
     p(99.9900) =     16.105 ms/op
     p(99.9990) =     16.657 ms/op
     p(99.9999) =     16.777 ms/op
    p(100.0000) =     16.777 ms/op


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
# Warmup Iteration   1: 3.796 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.007 ms/op
Iteration   1: 2.924 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  9.077 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   13.746 ms/op

Iteration   2: 2.923 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.399 ms/op
                 getUser·p0.999:  7.847 ms/op
                 getUser·p0.9999: 12.993 ms/op
                 getUser·p1.00:   13.320 ms/op

Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.775 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.350 ms/op
                 getUser·p0.999:  5.757 ms/op
                 getUser·p0.9999: 13.976 ms/op
                 getUser·p1.00:   14.156 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 326174
  mean =      2.943 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1790 
    [ 1.250,  2.500) = 33003 
    [ 2.500,  3.750) = 277844 
    [ 3.750,  5.000) = 12122 
    [ 5.000,  6.250) = 985 
    [ 6.250,  7.500) = 137 
    [ 7.500,  8.750) = 57 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 39 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =      7.175 ms/op
     p(99.9900) =     13.628 ms/op
     p(99.9990) =     14.090 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.955 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.140 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.011 ms/op
Iteration   1: 3.834 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.822 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.801 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  12.173 ms/op
                 listUser·p0.9999: 13.904 ms/op
                 listUser·p1.00:   15.958 ms/op

Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.882 ms/op
                 listUser·p0.95:   5.497 ms/op
                 listUser·p0.99:   6.796 ms/op
                 listUser·p0.999:  13.942 ms/op
                 listUser·p0.9999: 23.206 ms/op
                 listUser·p1.00:   23.495 ms/op

Iteration   3: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.924 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.710 ms/op
                 listUser·p0.999:  16.021 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248630
  mean =      3.860 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5016 
    [ 2.500,  5.000) = 222866 
    [ 5.000,  7.500) = 19653 
    [ 7.500, 10.000) = 673 
    [10.000, 12.500) = 99 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.822 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.858 ms/op
     p(95.0000) =      5.489 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     13.353 ms/op
     p(99.9900) =     22.132 ms/op
     p(99.9990) =     23.364 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.755 ± 1.411  ops/ms
ClientGrpc.existUser                       thrpt       3  11.413 ± 3.447  ops/ms
ClientGrpc.getUser                         thrpt       3  10.933 ± 2.945  ops/ms
ClientGrpc.listUser                        thrpt       3   8.383 ± 0.362  ops/ms
ClientGrpc.createUser                       avgt       3   2.950 ± 0.547   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 0.232   ms/op
ClientGrpc.getUser                          avgt       3   2.921 ± 0.263   ms/op
ClientGrpc.listUser                         avgt       3   3.770 ± 0.765   ms/op
ClientGrpc.createUser                     sample  323090   2.970 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.548           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.945           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.538           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.110           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.346           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.398           ms/op
ClientGrpc.existUser                      sample  335881   2.857 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.554           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.326           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.480           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.105           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.777           ms/op
ClientGrpc.getUser                        sample  326174   2.943 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.688           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.420           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.175           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          13.628           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          14.156           ms/op
ClientGrpc.listUser                       sample  248630   3.860 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.822           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.858           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.489           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.353           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.132           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
