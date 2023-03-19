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
# Warmup Iteration   1: 4.907 ops/ms
# Warmup Iteration   2: 9.332 ops/ms
# Warmup Iteration   3: 10.533 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.784 ops/ms
Iteration   3: 11.170 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.860 ±(99.9%) 5.119 ops/ms [Average]
  (min, avg, max) = (10.624, 10.860, 11.170), stdev = 0.281
  CI (99.9%): [5.740, 15.979] (assumes normal distribution)


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
# Warmup Iteration   1: 8.222 ops/ms
# Warmup Iteration   2: 11.167 ops/ms
# Warmup Iteration   3: 11.492 ops/ms
Iteration   1: 11.459 ops/ms
Iteration   2: 11.156 ops/ms
Iteration   3: 11.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.349 ±(99.9%) 3.060 ops/ms [Average]
  (min, avg, max) = (11.156, 11.349, 11.459), stdev = 0.168
  CI (99.9%): [8.289, 14.409] (assumes normal distribution)


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
# Warmup Iteration   1: 7.902 ops/ms
# Warmup Iteration   2: 10.413 ops/ms
# Warmup Iteration   3: 10.797 ops/ms
Iteration   1: 10.900 ops/ms
Iteration   2: 10.920 ops/ms
Iteration   3: 10.905 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.908 ±(99.9%) 0.186 ops/ms [Average]
  (min, avg, max) = (10.900, 10.908, 10.920), stdev = 0.010
  CI (99.9%): [10.722, 11.095] (assumes normal distribution)


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
# Warmup Iteration   1: 6.623 ops/ms
# Warmup Iteration   2: 8.341 ops/ms
# Warmup Iteration   3: 8.441 ops/ms
Iteration   1: 8.698 ops/ms
Iteration   2: 8.463 ops/ms
Iteration   3: 8.604 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.588 ±(99.9%) 2.160 ops/ms [Average]
  (min, avg, max) = (8.463, 8.588, 8.698), stdev = 0.118
  CI (99.9%): [6.428, 10.748] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.044 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.900 ±(99.9%) 0.003 ms/op
Iteration   1: 2.904 ±(99.9%) 0.003 ms/op
Iteration   2: 2.912 ±(99.9%) 0.003 ms/op
Iteration   3: 2.878 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.898 ±(99.9%) 0.329 ms/op [Average]
  (min, avg, max) = (2.878, 2.898, 2.912), stdev = 0.018
  CI (99.9%): [2.569, 3.227] (assumes normal distribution)


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.852 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.893 ±(99.9%) 0.002 ms/op
Iteration   1: 2.746 ±(99.9%) 0.004 ms/op
Iteration   2: 2.786 ±(99.9%) 0.003 ms/op
Iteration   3: 2.802 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.778 ±(99.9%) 0.522 ms/op [Average]
  (min, avg, max) = (2.746, 2.778, 2.802), stdev = 0.029
  CI (99.9%): [2.256, 3.300] (assumes normal distribution)


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
# Warmup Iteration   1: 3.790 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.953 ±(99.9%) 0.003 ms/op
Iteration   1: 2.931 ±(99.9%) 0.002 ms/op
Iteration   2: 2.909 ±(99.9%) 0.004 ms/op
Iteration   3: 2.921 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.920 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.909, 2.920, 2.931), stdev = 0.011
  CI (99.9%): [2.719, 3.121] (assumes normal distribution)


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
# Warmup Iteration   1: 4.660 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.853 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.816 ±(99.9%) 0.014 ms/op
Iteration   1: 3.810 ±(99.9%) 0.030 ms/op
Iteration   2: 3.709 ±(99.9%) 0.024 ms/op
Iteration   3: 3.785 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.768 ±(99.9%) 0.964 ms/op [Average]
  (min, avg, max) = (3.709, 3.768, 3.810), stdev = 0.053
  CI (99.9%): [2.804, 4.732] (assumes normal distribution)


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
# Warmup Iteration   1: 3.716 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.007 ms/op
Iteration   1: 2.920 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.666 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.371 ms/op
                 createUser·p0.95:   3.596 ms/op
                 createUser·p0.99:   4.059 ms/op
                 createUser·p0.999:  6.115 ms/op
                 createUser·p0.9999: 13.355 ms/op
                 createUser·p1.00:   13.599 ms/op

Iteration   2: 2.926 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.780 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.416 ms/op
                 createUser·p0.95:   3.609 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  7.688 ms/op
                 createUser·p0.9999: 12.389 ms/op
                 createUser·p1.00:   13.074 ms/op

Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.614 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.351 ms/op
                 createUser·p0.95:   3.539 ms/op
                 createUser·p0.99:   4.108 ms/op
                 createUser·p0.999:  10.469 ms/op
                 createUser·p0.9999: 22.225 ms/op
                 createUser·p1.00:   22.708 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 327538
  mean =      2.931 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34062 
    [ 2.500,  5.000) = 292382 
    [ 5.000,  7.500) = 779 
    [ 7.500, 10.000) = 73 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.614 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.438 ms/op
     p(99.9900) =     18.171 ms/op
     p(99.9990) =     22.592 ms/op
     p(99.9999) =     22.708 ms/op
    p(100.0000) =     22.708 ms/op


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
# Warmup Iteration   1: 3.664 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.921 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.897 ±(99.9%) 0.006 ms/op
Iteration   1: 2.850 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.693 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.134 ms/op
                 existUser·p0.9999: 11.698 ms/op
                 existUser·p1.00:   12.059 ms/op

Iteration   2: 2.890 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.710 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   3.879 ms/op
                 existUser·p0.999:  5.772 ms/op
                 existUser·p0.9999: 13.941 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.808 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.613 ms/op
                 existUser·p0.50:   2.806 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.396 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  6.381 ms/op
                 existUser·p0.9999: 16.010 ms/op
                 existUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336894
  mean =      2.849 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2677 
    [ 1.250,  2.500) = 49800 
    [ 2.500,  3.750) = 277646 
    [ 3.750,  5.000) = 5847 
    [ 5.000,  6.250) = 586 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 45 
    [ 8.750, 10.000) = 31 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.613 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.330 ms/op
     p(95.0000) =      3.490 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      6.267 ms/op
     p(99.9900) =     15.144 ms/op
     p(99.9990) =     17.552 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.960 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.005 ms/op
Iteration   1: 2.911 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.550 ms/op
                 getUser·p0.9999: 11.961 ms/op
                 getUser·p1.00:   12.403 ms/op

Iteration   2: 2.965 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  6.377 ms/op
                 getUser·p0.9999: 18.954 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 2.894 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.644 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.338 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.828 ms/op
                 getUser·p0.9999: 14.467 ms/op
                 getUser·p1.00:   15.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 328274
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2506 
    [ 1.250,  2.500) = 34396 
    [ 2.500,  3.750) = 279595 
    [ 3.750,  5.000) = 10635 
    [ 5.000,  6.250) = 756 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 65 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.644 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.445 ms/op
     p(99.9900) =     15.992 ms/op
     p(99.9990) =     19.315 ms/op
     p(99.9999) =     19.431 ms/op
    p(100.0000) =     19.431 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.849 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.009 ms/op
Iteration   1: 3.788 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.485 ms/op
                 listUser·p0.50:   3.645 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.567 ms/op
                 listUser·p0.999:  11.829 ms/op
                 listUser·p0.9999: 13.304 ms/op
                 listUser·p1.00:   14.369 ms/op

Iteration   2: 3.722 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.300 ms/op
                 listUser·p0.999:  15.809 ms/op
                 listUser·p0.9999: 18.736 ms/op
                 listUser·p1.00:   19.137 ms/op

Iteration   3: 3.749 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.317 ms/op
                 listUser·p0.50:   3.617 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.341 ms/op
                 listUser·p0.999:  13.493 ms/op
                 listUser·p0.9999: 23.653 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 256094
  mean =      3.753 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5870 
    [ 2.500,  5.000) = 231906 
    [ 5.000,  7.500) = 17399 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 174 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      3.613 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      6.390 ms/op
     p(99.9000) =     13.074 ms/op
     p(99.9900) =     19.921 ms/op
     p(99.9990) =     24.113 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.860 ± 5.119  ops/ms
ClientGrpc.existUser                       thrpt       3  11.349 ± 3.060  ops/ms
ClientGrpc.getUser                         thrpt       3  10.908 ± 0.186  ops/ms
ClientGrpc.listUser                        thrpt       3   8.588 ± 2.160  ops/ms
ClientGrpc.createUser                       avgt       3   2.898 ± 0.329   ms/op
ClientGrpc.existUser                        avgt       3   2.778 ± 0.522   ms/op
ClientGrpc.getUser                          avgt       3   2.920 ± 0.201   ms/op
ClientGrpc.listUser                         avgt       3   3.768 ± 0.964   ms/op
ClientGrpc.createUser                     sample  327538   2.931 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.614           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.925           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.219           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.438           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.171           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.708           ms/op
ClientGrpc.existUser                      sample  336894   2.849 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.613           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.330           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.490           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.141           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.267           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.144           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.662           ms/op
ClientGrpc.getUser                        sample  328274   2.923 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.644           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.920           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.400           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.629           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.445           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.992           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.431           ms/op
ClientGrpc.listUser                       sample  256094   3.753 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.485           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.613           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.292           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.390           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.074           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.921           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.183           ms/op
