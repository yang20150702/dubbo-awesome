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
# Warmup Iteration   1: 4.610 ops/ms
# Warmup Iteration   2: 9.647 ops/ms
# Warmup Iteration   3: 10.447 ops/ms
Iteration   1: 10.751 ops/ms
Iteration   2: 10.804 ops/ms
Iteration   3: 10.954 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.836 ±(99.9%) 1.928 ops/ms [Average]
  (min, avg, max) = (10.751, 10.836, 10.954), stdev = 0.106
  CI (99.9%): [8.908, 12.764] (assumes normal distribution)


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
# Warmup Iteration   1: 8.751 ops/ms
# Warmup Iteration   2: 11.056 ops/ms
# Warmup Iteration   3: 11.331 ops/ms
Iteration   1: 11.678 ops/ms
Iteration   2: 11.440 ops/ms
Iteration   3: 11.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.399 ±(99.9%) 5.500 ops/ms [Average]
  (min, avg, max) = (11.079, 11.399, 11.678), stdev = 0.301
  CI (99.9%): [5.899, 16.898] (assumes normal distribution)


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
# Warmup Iteration   1: 8.295 ops/ms
# Warmup Iteration   2: 10.678 ops/ms
# Warmup Iteration   3: 10.886 ops/ms
Iteration   1: 10.938 ops/ms
Iteration   2: 11.042 ops/ms
Iteration   3: 11.060 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  11.013 ±(99.9%) 1.197 ops/ms [Average]
  (min, avg, max) = (10.938, 11.013, 11.060), stdev = 0.066
  CI (99.9%): [9.817, 12.210] (assumes normal distribution)


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
# Warmup Iteration   1: 7.150 ops/ms
# Warmup Iteration   2: 8.093 ops/ms
# Warmup Iteration   3: 8.419 ops/ms
Iteration   1: 8.423 ops/ms
Iteration   2: 8.376 ops/ms
Iteration   3: 8.369 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.389 ±(99.9%) 0.541 ops/ms [Average]
  (min, avg, max) = (8.369, 8.389, 8.423), stdev = 0.030
  CI (99.9%): [7.848, 8.930] (assumes normal distribution)


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 3.067 ±(99.9%) 0.002 ms/op
Iteration   3: 2.982 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.001 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (2.953, 3.001, 3.067), stdev = 0.059
  CI (99.9%): [1.918, 4.084] (assumes normal distribution)


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
# Warmup Iteration   1: 3.670 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.881 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.817 ±(99.9%) 0.003 ms/op
Iteration   1: 2.843 ±(99.9%) 0.002 ms/op
Iteration   2: 2.753 ±(99.9%) 0.003 ms/op
Iteration   3: 2.840 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.812 ±(99.9%) 0.930 ms/op [Average]
  (min, avg, max) = (2.753, 2.812, 2.843), stdev = 0.051
  CI (99.9%): [1.881, 3.742] (assumes normal distribution)


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
# Warmup Iteration   1: 3.975 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.065 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.967 ±(99.9%) 0.003 ms/op
Iteration   1: 2.966 ±(99.9%) 0.003 ms/op
Iteration   2: 2.881 ±(99.9%) 0.002 ms/op
Iteration   3: 2.919 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.922 ±(99.9%) 0.776 ms/op [Average]
  (min, avg, max) = (2.881, 2.922, 2.966), stdev = 0.043
  CI (99.9%): [2.146, 3.698] (assumes normal distribution)


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.899 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.018 ms/op
Iteration   1: 3.805 ±(99.9%) 0.010 ms/op
Iteration   2: 3.765 ±(99.9%) 0.008 ms/op
Iteration   3: 3.818 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.796 ±(99.9%) 0.508 ms/op [Average]
  (min, avg, max) = (3.765, 3.796, 3.818), stdev = 0.028
  CI (99.9%): [3.288, 4.304] (assumes normal distribution)


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.071 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.976 ±(99.9%) 0.006 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   2.961 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.018 ms/op
                 createUser·p0.999:  6.157 ms/op
                 createUser·p0.9999: 12.640 ms/op
                 createUser·p1.00:   12.960 ms/op

Iteration   2: 2.964 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.627 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.543 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  10.830 ms/op
                 createUser·p0.9999: 17.079 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 2.910 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.662 ms/op
                 createUser·p0.50:   2.908 ms/op
                 createUser·p0.90:   3.367 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  7.759 ms/op
                 createUser·p0.9999: 18.383 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325032
  mean =      2.952 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1979 
    [ 1.250,  2.500) = 32983 
    [ 2.500,  3.750) = 277775 
    [ 3.750,  5.000) = 10911 
    [ 5.000,  6.250) = 759 
    [ 6.250,  7.500) = 197 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 74 
    [10.000, 11.250) = 107 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 25 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      9.535 ms/op
     p(99.9900) =     17.203 ms/op
     p(99.9990) =     18.506 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


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
# Warmup Iteration   1: 3.525 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 2.931 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.822 ±(99.9%) 0.006 ms/op
Iteration   1: 2.849 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.519 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 17.793 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   2: 2.808 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.492 ms/op
                 existUser·p0.50:   2.818 ms/op
                 existUser·p0.90:   3.187 ms/op
                 existUser·p0.95:   3.351 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  7.521 ms/op
                 existUser·p0.9999: 15.536 ms/op
                 existUser·p1.00:   15.974 ms/op

Iteration   3: 2.798 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.540 ms/op
                 existUser·p0.50:   2.798 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  7.593 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.500 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340720
  mean =      2.818 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3111 
    [ 1.250,  2.500) = 58315 
    [ 2.500,  3.750) = 271904 
    [ 3.750,  5.000) = 6484 
    [ 5.000,  6.250) = 382 
    [ 6.250,  7.500) = 217 
    [ 7.500,  8.750) = 109 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 24 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.492 ms/op
     p(50.0000) =      2.818 ms/op
     p(90.0000) =      3.301 ms/op
     p(95.0000) =      3.494 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      7.285 ms/op
     p(99.9900) =     15.921 ms/op
     p(99.9990) =     18.140 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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
# Warmup Iteration   1: 3.559 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.052 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.980 ±(99.9%) 0.005 ms/op
Iteration   1: 2.934 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  6.496 ms/op
                 getUser·p0.9999: 11.749 ms/op
                 getUser·p1.00:   11.895 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  7.619 ms/op
                 getUser·p0.9999: 15.114 ms/op
                 getUser·p1.00:   16.466 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.243 ms/op
                 getUser·p0.999:  6.201 ms/op
                 getUser·p0.9999: 16.342 ms/op
                 getUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325909
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2552 
    [ 1.250,  2.500) = 27908 
    [ 2.500,  3.750) = 283344 
    [ 3.750,  5.000) = 10824 
    [ 5.000,  6.250) = 855 
    [ 6.250,  7.500) = 198 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 27 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 48 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.654 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      6.702 ms/op
     p(99.9900) =     15.925 ms/op
     p(99.9990) =     16.515 ms/op
     p(99.9999) =     16.695 ms/op
    p(100.0000) =     16.695 ms/op


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
# Warmup Iteration   1: 4.712 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.066 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.012 ms/op
Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.545 ms/op
                 listUser·p0.999:  13.682 ms/op
                 listUser·p0.9999: 19.019 ms/op
                 listUser·p1.00:   19.530 ms/op

Iteration   2: 3.895 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.710 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.353 ms/op
                 listUser·p0.9999: 28.224 ms/op
                 listUser·p1.00:   28.541 ms/op

Iteration   3: 3.899 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.455 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.742 ms/op
                 listUser·p0.999:  14.336 ms/op
                 listUser·p0.9999: 18.153 ms/op
                 listUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247357
  mean =      3.883 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4107 
    [ 2.500,  5.000) = 223694 
    [ 5.000,  7.500) = 18465 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     25.970 ms/op
     p(99.9990) =     28.444 ms/op
     p(99.9999) =     28.541 ms/op
    p(100.0000) =     28.541 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.836 ± 1.928  ops/ms
ClientGrpc.existUser                       thrpt       3  11.399 ± 5.500  ops/ms
ClientGrpc.getUser                         thrpt       3  11.013 ± 1.197  ops/ms
ClientGrpc.listUser                        thrpt       3   8.389 ± 0.541  ops/ms
ClientGrpc.createUser                       avgt       3   3.001 ± 1.083   ms/op
ClientGrpc.existUser                        avgt       3   2.812 ± 0.930   ms/op
ClientGrpc.getUser                          avgt       3   2.922 ± 0.776   ms/op
ClientGrpc.listUser                         avgt       3   3.796 ± 0.508   ms/op
ClientGrpc.createUser                     sample  325032   2.952 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.627           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.461           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.535           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.203           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  340720   2.818 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.492           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.818           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.301           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.494           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.285           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.921           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.219           ms/op
ClientGrpc.getUser                        sample  325909   2.945 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.654           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.702           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.925           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.695           ms/op
ClientGrpc.listUser                       sample  247357   3.883 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.455           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.336           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.970           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.541           ms/op
