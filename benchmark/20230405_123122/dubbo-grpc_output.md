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
# Warmup Iteration   1: 4.770 ops/ms
# Warmup Iteration   2: 9.422 ops/ms
# Warmup Iteration   3: 10.284 ops/ms
Iteration   1: 10.833 ops/ms
Iteration   2: 11.035 ops/ms
Iteration   3: 10.736 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.868 ±(99.9%) 2.789 ops/ms [Average]
  (min, avg, max) = (10.736, 10.868, 11.035), stdev = 0.153
  CI (99.9%): [8.079, 13.657] (assumes normal distribution)


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
# Warmup Iteration   1: 8.308 ops/ms
# Warmup Iteration   2: 10.973 ops/ms
# Warmup Iteration   3: 11.257 ops/ms
Iteration   1: 11.305 ops/ms
Iteration   2: 11.484 ops/ms
Iteration   3: 11.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.349 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (11.259, 11.349, 11.484), stdev = 0.119
  CI (99.9%): [9.183, 13.515] (assumes normal distribution)


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
# Warmup Iteration   1: 8.302 ops/ms
# Warmup Iteration   2: 10.522 ops/ms
# Warmup Iteration   3: 10.835 ops/ms
Iteration   1: 10.877 ops/ms
Iteration   2: 11.004 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.872 ±(99.9%) 2.469 ops/ms [Average]
  (min, avg, max) = (10.734, 10.872, 11.004), stdev = 0.135
  CI (99.9%): [8.403, 13.340] (assumes normal distribution)


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
# Warmup Iteration   1: 5.743 ops/ms
# Warmup Iteration   2: 8.131 ops/ms
# Warmup Iteration   3: 8.268 ops/ms
Iteration   1: 8.314 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.284 ±(99.9%) 1.379 ops/ms [Average]
  (min, avg, max) = (8.199, 8.284, 8.341), stdev = 0.076
  CI (99.9%): [6.905, 9.664] (assumes normal distribution)


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
# Warmup Iteration   1: 3.844 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.046 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.987 ±(99.9%) 0.003 ms/op
Iteration   1: 2.930 ±(99.9%) 0.003 ms/op
Iteration   2: 2.950 ±(99.9%) 0.002 ms/op
Iteration   3: 2.952 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.944 ±(99.9%) 0.223 ms/op [Average]
  (min, avg, max) = (2.930, 2.944, 2.952), stdev = 0.012
  CI (99.9%): [2.721, 3.167] (assumes normal distribution)


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
# Warmup Iteration   1: 3.770 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.917 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.863 ±(99.9%) 0.002 ms/op
Iteration   1: 2.831 ±(99.9%) 0.007 ms/op
Iteration   2: 2.783 ±(99.9%) 0.003 ms/op
Iteration   3: 2.850 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.821 ±(99.9%) 0.624 ms/op [Average]
  (min, avg, max) = (2.783, 2.821, 2.850), stdev = 0.034
  CI (99.9%): [2.198, 3.445] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.043 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 2.969 ±(99.9%) 0.003 ms/op
Iteration   1: 2.947 ±(99.9%) 0.002 ms/op
Iteration   2: 2.927 ±(99.9%) 0.003 ms/op
Iteration   3: 2.942 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.939 ±(99.9%) 0.195 ms/op [Average]
  (min, avg, max) = (2.927, 2.939, 2.947), stdev = 0.011
  CI (99.9%): [2.744, 3.134] (assumes normal distribution)


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
# Warmup Iteration   1: 5.063 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.978 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.010 ms/op
Iteration   1: 3.840 ±(99.9%) 0.018 ms/op
Iteration   2: 3.882 ±(99.9%) 0.021 ms/op
Iteration   3: 3.795 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.839 ±(99.9%) 0.788 ms/op [Average]
  (min, avg, max) = (3.795, 3.839, 3.882), stdev = 0.043
  CI (99.9%): [3.051, 4.627] (assumes normal distribution)


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
# Warmup Iteration   1: 3.896 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.950 ±(99.9%) 0.007 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.624 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.281 ms/op
                 createUser·p0.95:   3.437 ms/op
                 createUser·p0.99:   4.116 ms/op
                 createUser·p0.999:  6.838 ms/op
                 createUser·p0.9999: 19.086 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   2: 2.980 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.539 ms/op
                 createUser·p0.50:   2.945 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.856 ms/op
                 createUser·p0.9999: 16.323 ms/op
                 createUser·p1.00:   16.613 ms/op

Iteration   3: 2.944 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.509 ms/op
                 createUser·p0.50:   2.912 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.383 ms/op
                 createUser·p0.999:  10.027 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   19.169 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325181
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1756 
    [ 1.250,  2.500) = 27500 
    [ 2.500,  3.750) = 282940 
    [ 3.750,  5.000) = 11713 
    [ 5.000,  6.250) = 725 
    [ 6.250,  7.500) = 233 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 28 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.509 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.428 ms/op
     p(95.0000) =      3.682 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.406 ms/op
     p(99.9900) =     18.726 ms/op
     p(99.9990) =     19.579 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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
# Warmup Iteration   1: 3.848 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.900 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.005 ms/op
Iteration   1: 2.823 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.039 ms/op
                 existUser·p0.9999: 16.917 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 2.845 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.550 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.124 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.812 ms/op

Iteration   3: 2.790 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.601 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.301 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  7.714 ms/op
                 existUser·p0.9999: 25.347 ms/op
                 existUser·p1.00:   25.919 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340608
  mean =      2.819 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 62687 
    [ 2.500,  5.000) = 277012 
    [ 5.000,  7.500) = 625 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 62 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.588 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.824 ms/op
     p(99.9900) =     17.955 ms/op
     p(99.9990) =     25.860 ms/op
     p(99.9999) =     25.919 ms/op
    p(100.0000) =     25.919 ms/op


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
# Warmup Iteration   1: 3.984 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.977 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.006 ms/op
Iteration   1: 2.979 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.817 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.485 ms/op
                 getUser·p0.9999: 11.583 ms/op
                 getUser·p1.00:   11.698 ms/op

Iteration   2: 2.955 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.665 ms/op
                 getUser·p0.50:   2.957 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.493 ms/op
                 getUser·p0.9999: 13.408 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   3: 2.939 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.744 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.617 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  8.022 ms/op
                 getUser·p0.9999: 15.730 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324611
  mean =      2.958 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2213 
    [ 1.250,  2.500) = 27102 
    [ 2.500,  3.750) = 282419 
    [ 3.750,  5.000) = 11801 
    [ 5.000,  6.250) = 614 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 15 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      6.652 ms/op
     p(99.9900) =     15.262 ms/op
     p(99.9990) =     15.966 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 4.941 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.037 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.881 ±(99.9%) 0.010 ms/op
Iteration   1: 3.864 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   4.825 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   6.530 ms/op
                 listUser·p0.999:  13.049 ms/op
                 listUser·p0.9999: 15.448 ms/op
                 listUser·p1.00:   15.843 ms/op

Iteration   2: 3.933 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.863 ms/op
                 listUser·p0.50:   3.760 ms/op
                 listUser·p0.90:   4.956 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  21.124 ms/op
                 listUser·p0.9999: 23.224 ms/op
                 listUser·p1.00:   24.412 ms/op

Iteration   3: 3.851 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.871 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.464 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  14.647 ms/op
                 listUser·p0.9999: 21.191 ms/op
                 listUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247165
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4112 
    [ 2.500,  5.000) = 222916 
    [ 5.000,  7.500) = 19107 
    [ 7.500, 10.000) = 549 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     14.579 ms/op
     p(99.9900) =     22.586 ms/op
     p(99.9990) =     24.289 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.868 ± 2.789  ops/ms
ClientGrpc.existUser                       thrpt       3  11.349 ± 2.166  ops/ms
ClientGrpc.getUser                         thrpt       3  10.872 ± 2.469  ops/ms
ClientGrpc.listUser                        thrpt       3   8.284 ± 1.379  ops/ms
ClientGrpc.createUser                       avgt       3   2.944 ± 0.223   ms/op
ClientGrpc.existUser                        avgt       3   2.821 ± 0.624   ms/op
ClientGrpc.getUser                          avgt       3   2.939 ± 0.195   ms/op
ClientGrpc.listUser                         avgt       3   3.839 ± 0.788   ms/op
ClientGrpc.createUser                     sample  325181   2.950 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.509           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.933           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.428           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.406           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.726           ms/op
ClientGrpc.existUser                      sample  340608   2.819 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.550           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.284           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.824           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.955           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.919           ms/op
ClientGrpc.getUser                        sample  324611   2.958 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.665           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.953           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.453           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.674           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.652           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.262           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.056           ms/op
ClientGrpc.listUser                       sample  247165   3.882 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.863           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.456           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.636           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.579           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.586           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.412           ms/op
