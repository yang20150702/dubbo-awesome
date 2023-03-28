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
# Warmup Iteration   1: 4.614 ops/ms
# Warmup Iteration   2: 9.870 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.736 ops/ms
Iteration   2: 10.988 ops/ms
Iteration   3: 11.157 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.961 ±(99.9%) 3.864 ops/ms [Average]
  (min, avg, max) = (10.736, 10.961, 11.157), stdev = 0.212
  CI (99.9%): [7.096, 14.825] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 8.199 ops/ms
# Warmup Iteration   2: 11.247 ops/ms
# Warmup Iteration   3: 11.145 ops/ms
Iteration   1: 11.150 ops/ms
Iteration   2: 11.245 ops/ms
Iteration   3: 11.270 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.222 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (11.150, 11.222, 11.270), stdev = 0.063
  CI (99.9%): [10.071, 12.373] (assumes normal distribution)


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
# Warmup Iteration   1: 7.589 ops/ms
# Warmup Iteration   2: 10.645 ops/ms
# Warmup Iteration   3: 11.005 ops/ms
Iteration   1: 11.034 ops/ms
Iteration   2: 10.881 ops/ms
Iteration   3: 11.088 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  11.001 ±(99.9%) 1.963 ops/ms [Average]
  (min, avg, max) = (10.881, 11.001, 11.088), stdev = 0.108
  CI (99.9%): [9.038, 12.964] (assumes normal distribution)


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
# Warmup Iteration   1: 6.144 ops/ms
# Warmup Iteration   2: 8.299 ops/ms
# Warmup Iteration   3: 8.388 ops/ms
Iteration   1: 8.561 ops/ms
Iteration   2: 8.804 ops/ms
Iteration   3: 8.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.687 ±(99.9%) 2.223 ops/ms [Average]
  (min, avg, max) = (8.561, 8.687, 8.804), stdev = 0.122
  CI (99.9%): [6.464, 10.909] (assumes normal distribution)


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
# Warmup Iteration   1: 3.967 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.002 ms/op
Iteration   1: 2.884 ±(99.9%) 0.003 ms/op
Iteration   2: 2.939 ±(99.9%) 0.003 ms/op
Iteration   3: 2.892 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.905 ±(99.9%) 0.549 ms/op [Average]
  (min, avg, max) = (2.884, 2.905, 2.939), stdev = 0.030
  CI (99.9%): [2.356, 3.454] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.003 ms/op
Iteration   1: 2.791 ±(99.9%) 0.003 ms/op
Iteration   2: 2.882 ±(99.9%) 0.003 ms/op
Iteration   3: 2.791 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.822 ±(99.9%) 0.962 ms/op [Average]
  (min, avg, max) = (2.791, 2.822, 2.882), stdev = 0.053
  CI (99.9%): [1.860, 3.783] (assumes normal distribution)


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.016 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.933 ±(99.9%) 0.003 ms/op
Iteration   1: 2.896 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.002 ms/op
Iteration   3: 2.901 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.914 ±(99.9%) 0.482 ms/op [Average]
  (min, avg, max) = (2.896, 2.914, 2.944), stdev = 0.026
  CI (99.9%): [2.432, 3.396] (assumes normal distribution)


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
# Warmup Iteration   1: 4.617 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.769 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.813 ±(99.9%) 0.012 ms/op
Iteration   1: 3.773 ±(99.9%) 0.020 ms/op
Iteration   2: 3.782 ±(99.9%) 0.023 ms/op
Iteration   3: 3.770 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.775 ±(99.9%) 0.116 ms/op [Average]
  (min, avg, max) = (3.770, 3.775, 3.782), stdev = 0.006
  CI (99.9%): [3.660, 3.891] (assumes normal distribution)


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
# Warmup Iteration   1: 3.813 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.952 ±(99.9%) 0.005 ms/op
Iteration   1: 2.937 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.678 ms/op
                 createUser·p0.50:   2.929 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.424 ms/op
                 createUser·p0.99:   4.010 ms/op
                 createUser·p0.999:  7.267 ms/op
                 createUser·p0.9999: 13.160 ms/op
                 createUser·p1.00:   15.647 ms/op

Iteration   2: 2.924 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.760 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.424 ms/op
                 createUser·p0.95:   3.617 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  5.892 ms/op
                 createUser·p0.9999: 13.504 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 2.951 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.588 ms/op
                 createUser·p0.50:   2.925 ms/op
                 createUser·p0.90:   3.457 ms/op
                 createUser·p0.95:   3.736 ms/op
                 createUser·p0.99:   4.354 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 326590
  mean =      2.938 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30211 
    [ 2.500,  5.000) = 295397 
    [ 5.000,  7.500) = 686 
    [ 7.500, 10.000) = 40 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.383 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      7.139 ms/op
     p(99.9900) =     17.323 ms/op
     p(99.9990) =     20.775 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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
# Warmup Iteration   1: 3.820 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.915 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.821 ±(99.9%) 0.005 ms/op
Iteration   1: 2.843 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.522 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.289 ms/op
                 existUser·p0.95:   3.453 ms/op
                 existUser·p0.99:   4.099 ms/op
                 existUser·p0.999:  5.718 ms/op
                 existUser·p0.9999: 11.235 ms/op
                 existUser·p1.00:   11.551 ms/op

Iteration   2: 2.783 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.566 ms/op
                 existUser·p0.50:   2.802 ms/op
                 existUser·p0.90:   3.154 ms/op
                 existUser·p0.95:   3.371 ms/op
                 existUser·p0.99:   4.391 ms/op
                 existUser·p0.999:  6.099 ms/op
                 existUser·p0.9999: 11.739 ms/op
                 existUser·p1.00:   11.928 ms/op

Iteration   3: 2.828 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 23.003 ms/op
                 existUser·p1.00:   24.576 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 340521
  mean =      2.818 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 53785 
    [ 2.500,  5.000) = 285651 
    [ 5.000,  7.500) = 837 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      2.814 ms/op
     p(90.0000) =      3.252 ms/op
     p(95.0000) =      3.469 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     16.153 ms/op
     p(99.9990) =     24.497 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


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
# Warmup Iteration   1: 4.030 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.998 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.903 ±(99.9%) 0.006 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   2.896 ms/op
                 getUser·p0.90:   3.432 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.972 ms/op
                 getUser·p0.9999: 11.780 ms/op
                 getUser·p1.00:   12.173 ms/op

Iteration   2: 2.953 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.474 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.604 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  7.783 ms/op
                 getUser·p0.9999: 14.062 ms/op
                 getUser·p1.00:   14.221 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.758 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.428 ms/op
                 getUser·p0.95:   3.588 ms/op
                 getUser·p0.99:   4.325 ms/op
                 getUser·p0.999:  8.326 ms/op
                 getUser·p0.9999: 15.993 ms/op
                 getUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327119
  mean =      2.935 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2402 
    [ 1.250,  2.500) = 27690 
    [ 2.500,  3.750) = 285899 
    [ 3.750,  5.000) = 9715 
    [ 5.000,  6.250) = 873 
    [ 6.250,  7.500) = 232 
    [ 7.500,  8.750) = 119 
    [ 8.750, 10.000) = 29 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 31 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.330 ms/op
     p(99.9900) =     14.907 ms/op
     p(99.9990) =     16.117 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 4.858 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.011 ms/op
Iteration   1: 3.661 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.551 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.145 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  11.993 ms/op
                 listUser·p0.9999: 13.636 ms/op
                 listUser·p1.00:   14.139 ms/op

Iteration   2: 3.795 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.087 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.226 ms/op
                 listUser·p0.99:   6.480 ms/op
                 listUser·p0.999:  14.467 ms/op
                 listUser·p0.9999: 23.055 ms/op
                 listUser·p1.00:   23.396 ms/op

Iteration   3: 3.698 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.588 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  15.539 ms/op
                 listUser·p0.9999: 22.272 ms/op
                 listUser·p1.00:   22.741 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 258324
  mean =      3.717 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4277 
    [ 2.500,  5.000) = 238676 
    [ 5.000,  7.500) = 14492 
    [ 7.500, 10.000) = 483 
    [10.000, 12.500) = 101 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.522 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =     13.500 ms/op
     p(99.9900) =     22.681 ms/op
     p(99.9990) =     23.273 ms/op
     p(99.9999) =     23.396 ms/op
    p(100.0000) =     23.396 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.961 ± 3.864  ops/ms
ClientGrpc.existUser                       thrpt       3  11.222 ± 1.151  ops/ms
ClientGrpc.getUser                         thrpt       3  11.001 ± 1.963  ops/ms
ClientGrpc.listUser                        thrpt       3   8.687 ± 2.223  ops/ms
ClientGrpc.createUser                       avgt       3   2.905 ± 0.549   ms/op
ClientGrpc.existUser                        avgt       3   2.822 ± 0.962   ms/op
ClientGrpc.getUser                          avgt       3   2.914 ± 0.482   ms/op
ClientGrpc.listUser                         avgt       3   3.775 ± 0.116   ms/op
ClientGrpc.createUser                     sample  326590   2.938 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.588           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.929           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.383           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.139           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.323           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  340521   2.818 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.522           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.814           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.252           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.469           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.153           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.576           ms/op
ClientGrpc.getUser                        sample  327119   2.935 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.474           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.925           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.416           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.330           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.907           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.155           ms/op
ClientGrpc.listUser                       sample  258324   3.717 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.757           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.600           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.522           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.537           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.500           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.681           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.396           ms/op
