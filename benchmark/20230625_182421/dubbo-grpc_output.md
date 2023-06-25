# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ops/ms
# Warmup Iteration   2: 8.460 ops/ms
# Warmup Iteration   3: 10.158 ops/ms
Iteration   1: 10.377 ops/ms
Iteration   2: 10.491 ops/ms
Iteration   3: 10.620 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.496 ±(99.9%) 2.217 ops/ms [Average]
  (min, avg, max) = (10.377, 10.496, 10.620), stdev = 0.122
  CI (99.9%): [8.279, 12.713] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.858 ops/ms
# Warmup Iteration   2: 10.617 ops/ms
# Warmup Iteration   3: 10.882 ops/ms
Iteration   1: 10.918 ops/ms
Iteration   2: 11.036 ops/ms
Iteration   3: 10.773 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.909 ±(99.9%) 2.407 ops/ms [Average]
  (min, avg, max) = (10.773, 10.909, 11.036), stdev = 0.132
  CI (99.9%): [8.502, 13.316] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.047 ops/ms
# Warmup Iteration   2: 9.895 ops/ms
# Warmup Iteration   3: 10.465 ops/ms
Iteration   1: 10.556 ops/ms
Iteration   2: 10.453 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.458 ±(99.9%) 1.733 ops/ms [Average]
  (min, avg, max) = (10.366, 10.458, 10.556), stdev = 0.095
  CI (99.9%): [8.725, 12.191] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.459 ops/ms
# Warmup Iteration   2: 7.336 ops/ms
# Warmup Iteration   3: 7.898 ops/ms
Iteration   1: 7.929 ops/ms
Iteration   2: 7.928 ops/ms
Iteration   3: 7.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.944 ±(99.9%) 0.503 ops/ms [Average]
  (min, avg, max) = (7.928, 7.944, 7.976), stdev = 0.028
  CI (99.9%): [7.441, 8.447] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.383 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.218 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.003 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.059 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.086 ±(99.9%) 0.419 ms/op [Average]
  (min, avg, max) = (3.059, 3.086, 3.101), stdev = 0.023
  CI (99.9%): [2.667, 3.505] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.002 ms/op
Iteration   1: 2.939 ±(99.9%) 0.003 ms/op
Iteration   2: 2.929 ±(99.9%) 0.002 ms/op
Iteration   3: 2.956 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.942 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (2.929, 2.942, 2.956), stdev = 0.013
  CI (99.9%): [2.696, 3.187] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.243 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.002 ms/op
Iteration   1: 3.052 ±(99.9%) 0.004 ms/op
Iteration   2: 3.041 ±(99.9%) 0.002 ms/op
Iteration   3: 3.089 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.061 ±(99.9%) 0.463 ms/op [Average]
  (min, avg, max) = (3.041, 3.061, 3.089), stdev = 0.025
  CI (99.9%): [2.598, 3.524] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.252 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.066 ±(99.9%) 0.009 ms/op
Iteration   1: 3.992 ±(99.9%) 0.020 ms/op
Iteration   2: 3.961 ±(99.9%) 0.006 ms/op
Iteration   3: 3.959 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.971 ±(99.9%) 0.332 ms/op [Average]
  (min, avg, max) = (3.959, 3.971, 3.992), stdev = 0.018
  CI (99.9%): [3.638, 4.303] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.692 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.080 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  7.618 ms/op
                 createUser·p0.9999: 13.346 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  7.078 ms/op
                 createUser·p0.9999: 17.026 ms/op
                 createUser·p1.00:   17.695 ms/op

Iteration   3: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.581 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.613 ms/op
                 createUser·p0.9999: 17.710 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310769
  mean =      3.090 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 782 
    [ 1.250,  2.500) = 19037 
    [ 2.500,  3.750) = 268621 
    [ 3.750,  5.000) = 20884 
    [ 5.000,  6.250) = 729 
    [ 6.250,  7.500) = 371 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 43 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.581 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      7.776 ms/op
     p(99.9900) =     16.941 ms/op
     p(99.9990) =     18.267 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.484 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.889 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.116 ms/op
                 existUser·p0.999:  6.753 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 2.908 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.891 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.164 ms/op
                 existUser·p0.999:  6.808 ms/op
                 existUser·p0.9999: 14.680 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   3: 2.862 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.742 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.182 ms/op
                 existUser·p0.999:  7.565 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   17.433 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332446
  mean =      2.886 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 38832 
    [ 2.500,  5.000) = 292428 
    [ 5.000,  7.500) = 952 
    [ 7.500, 10.000) = 67 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.482 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     17.417 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.594 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.066 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.358 ms/op
                 getUser·p0.999:  8.149 ms/op
                 getUser·p0.9999: 14.298 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.547 ms/op
                 getUser·p0.95:   3.826 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  7.893 ms/op
                 getUser·p0.9999: 15.132 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   3: 3.090 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.604 ms/op
                 getUser·p0.999:  9.109 ms/op
                 getUser·p0.9999: 19.191 ms/op
                 getUser·p1.00:   19.235 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312070
  mean =      3.075 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 472 
    [ 1.250,  2.500) = 15699 
    [ 2.500,  3.750) = 277018 
    [ 3.750,  5.000) = 17187 
    [ 5.000,  6.250) = 935 
    [ 6.250,  7.500) = 283 
    [ 7.500,  8.750) = 180 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 72 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.902 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.469 ms/op
     p(99.9900) =     18.638 ms/op
     p(99.9990) =     19.202 ms/op
     p(99.9999) =     19.235 ms/op
    p(100.0000) =     19.235 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.797 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.113 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.024 ±(99.9%) 0.011 ms/op
Iteration   1: 4.006 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.051 ms/op
                 listUser·p0.999:  13.861 ms/op
                 listUser·p0.9999: 16.876 ms/op
                 listUser·p1.00:   17.138 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.994 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  16.165 ms/op
                 listUser·p0.9999: 17.695 ms/op
                 listUser·p1.00:   17.990 ms/op

Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.759 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  16.247 ms/op
                 listUser·p0.9999: 26.141 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243972
  mean =      3.932 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2888 
    [ 2.500,  5.000) = 220079 
    [ 5.000,  7.500) = 19642 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.759 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     15.254 ms/op
     p(99.9900) =     25.192 ms/op
     p(99.9990) =     26.364 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.496 ± 2.217  ops/ms
ClientGrpc.existUser                       thrpt       3  10.909 ± 2.407  ops/ms
ClientGrpc.getUser                         thrpt       3  10.458 ± 1.733  ops/ms
ClientGrpc.listUser                        thrpt       3   7.944 ± 0.503  ops/ms
ClientGrpc.createUser                       avgt       3   3.086 ± 0.419   ms/op
ClientGrpc.existUser                        avgt       3   2.942 ± 0.246   ms/op
ClientGrpc.getUser                          avgt       3   3.061 ± 0.463   ms/op
ClientGrpc.listUser                         avgt       3   3.971 ± 0.332   ms/op
ClientGrpc.createUser                     sample  310769   3.090 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.581           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.858           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.776           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.941           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.416           ms/op
ClientGrpc.existUser                      sample  332446   2.886 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.725           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.482           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.157           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.004           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.417           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  312070   3.075 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.902           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.469           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.638           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.235           ms/op
ClientGrpc.listUser                       sample  243972   3.932 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.759           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.192           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.411           ms/op
