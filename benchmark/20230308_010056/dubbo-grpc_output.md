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
# Warmup Iteration   1: 4.856 ops/ms
# Warmup Iteration   2: 8.971 ops/ms
# Warmup Iteration   3: 10.344 ops/ms
Iteration   1: 10.659 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.636 ±(99.9%) 1.843 ops/ms [Average]
  (min, avg, max) = (10.525, 10.636, 10.723), stdev = 0.101
  CI (99.9%): [8.793, 12.479] (assumes normal distribution)


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
# Warmup Iteration   1: 8.056 ops/ms
# Warmup Iteration   2: 10.666 ops/ms
# Warmup Iteration   3: 10.827 ops/ms
Iteration   1: 11.133 ops/ms
Iteration   2: 11.213 ops/ms
Iteration   3: 11.039 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.128 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (11.039, 11.128, 11.213), stdev = 0.087
  CI (99.9%): [9.542, 12.714] (assumes normal distribution)


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
# Warmup Iteration   1: 7.930 ops/ms
# Warmup Iteration   2: 10.365 ops/ms
# Warmup Iteration   3: 10.793 ops/ms
Iteration   1: 10.360 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.447 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (10.360, 10.447, 10.533), stdev = 0.087
  CI (99.9%): [8.865, 12.028] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.835 ops/ms
# Warmup Iteration   2: 7.832 ops/ms
# Warmup Iteration   3: 8.057 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.918 ops/ms
Iteration   3: 8.148 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.010 ±(99.9%) 2.225 ops/ms [Average]
  (min, avg, max) = (7.918, 8.010, 8.148), stdev = 0.122
  CI (99.9%): [5.785, 10.235] (assumes normal distribution)


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
# Warmup Iteration   1: 3.807 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.002 ms/op
Iteration   2: 3.127 ±(99.9%) 0.002 ms/op
Iteration   3: 3.138 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.105 ±(99.9%) 0.887 ms/op [Average]
  (min, avg, max) = (3.049, 3.105, 3.138), stdev = 0.049
  CI (99.9%): [2.217, 3.992] (assumes normal distribution)


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
# Warmup Iteration   1: 3.599 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.003 ms/op
Iteration   1: 2.832 ±(99.9%) 0.003 ms/op
Iteration   2: 2.915 ±(99.9%) 0.003 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.918 ±(99.9%) 1.595 ms/op [Average]
  (min, avg, max) = (2.832, 2.918, 3.006), stdev = 0.087
  CI (99.9%): [1.322, 4.513] (assumes normal distribution)


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.002 ms/op
Iteration   1: 3.038 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.002 ms/op
Iteration   3: 3.072 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.519 ms/op [Average]
  (min, avg, max) = (3.015, 3.042, 3.072), stdev = 0.028
  CI (99.9%): [2.522, 3.561] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.057 ±(99.9%) 0.017 ms/op
Iteration   1: 4.062 ±(99.9%) 0.017 ms/op
Iteration   2: 4.026 ±(99.9%) 0.013 ms/op
Iteration   3: 3.933 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.007 ±(99.9%) 1.213 ms/op [Average]
  (min, avg, max) = (3.933, 4.007, 4.062), stdev = 0.067
  CI (99.9%): [2.793, 5.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.129 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 3.024 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  6.529 ms/op
                 createUser·p0.9999: 15.260 ms/op
                 createUser·p1.00:   15.745 ms/op

Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.125 ms/op
                 createUser·p0.90:   3.871 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  7.728 ms/op
                 createUser·p0.9999: 13.282 ms/op
                 createUser·p1.00:   13.713 ms/op

Iteration   3: 3.050 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.559 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.670 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.162 ms/op
                 createUser·p0.999:  10.816 ms/op
                 createUser·p0.9999: 29.508 ms/op
                 createUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312197
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32830 
    [ 2.500,  5.000) = 278654 
    [ 5.000,  7.500) = 412 
    [ 7.500, 10.000) = 45 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.559 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.276 ms/op
     p(99.9000) =      7.209 ms/op
     p(99.9900) =     28.854 ms/op
     p(99.9990) =     29.815 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 3.668 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 2.953 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.891 ±(99.9%) 0.006 ms/op
Iteration   1: 2.846 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.603 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.184 ms/op
                 existUser·p0.999:  6.843 ms/op
                 existUser·p0.9999: 19.153 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 2.961 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.760 ms/op
                 existUser·p0.99:   4.043 ms/op
                 existUser·p0.999:  6.669 ms/op
                 existUser·p0.9999: 17.406 ms/op
                 existUser·p1.00:   17.859 ms/op

Iteration   3: 2.815 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.612 ms/op
                 existUser·p0.50:   2.822 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.887 ms/op
                 existUser·p0.9999: 22.500 ms/op
                 existUser·p1.00:   25.199 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334087
  mean =      2.873 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 58751 
    [ 2.500,  5.000) = 274588 
    [ 5.000,  7.500) = 415 
    [ 7.500, 10.000) = 94 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.444 ms/op
     p(99.9900) =     19.549 ms/op
     p(99.9990) =     25.033 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


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
# Warmup Iteration   1: 3.791 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.006 ms/op
Iteration   1: 3.011 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  8.356 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   19.464 ms/op

Iteration   2: 3.039 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.852 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.178 ms/op
                 getUser·p0.999:  5.474 ms/op
                 getUser·p0.9999: 17.334 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.920 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.097 ms/op
                 getUser·p0.9999: 19.314 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315424
  mean =      3.044 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1199 
    [ 1.250,  2.500) = 30584 
    [ 2.500,  3.750) = 260680 
    [ 3.750,  5.000) = 22189 
    [ 5.000,  6.250) = 456 
    [ 6.250,  7.500) = 61 
    [ 7.500,  8.750) = 62 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 25 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 21 
    [16.250, 17.500) = 42 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      6.250 ms/op
     p(99.9900) =     18.872 ms/op
     p(99.9990) =     19.903 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
Iteration   1: 4.026 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  11.705 ms/op
                 listUser·p0.9999: 13.552 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   2: 4.067 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.085 ms/op
                 listUser·p0.50:   3.871 ms/op
                 listUser·p0.90:   5.202 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.528 ms/op
                 listUser·p0.9999: 16.630 ms/op
                 listUser·p1.00:   18.612 ms/op

Iteration   3: 4.034 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.968 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.792 ms/op
                 listUser·p0.99:   7.086 ms/op
                 listUser·p0.999:  18.756 ms/op
                 listUser·p0.9999: 24.152 ms/op
                 listUser·p1.00:   24.674 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237530
  mean =      4.042 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2459 
    [ 2.500,  5.000) = 204987 
    [ 5.000,  7.500) = 28842 
    [ 7.500, 10.000) = 776 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 211 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.968 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     14.025 ms/op
     p(99.9900) =     23.036 ms/op
     p(99.9990) =     24.531 ms/op
     p(99.9999) =     24.674 ms/op
    p(100.0000) =     24.674 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.636 ± 1.843  ops/ms
ClientGrpc.existUser                       thrpt       3  11.128 ± 1.586  ops/ms
ClientGrpc.getUser                         thrpt       3  10.447 ± 1.582  ops/ms
ClientGrpc.listUser                        thrpt       3   8.010 ± 2.225  ops/ms
ClientGrpc.createUser                       avgt       3   3.105 ± 0.887   ms/op
ClientGrpc.existUser                        avgt       3   2.918 ± 1.595   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.519   ms/op
ClientGrpc.listUser                         avgt       3   4.007 ± 1.213   ms/op
ClientGrpc.createUser                     sample  312197   3.073 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.559           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.744           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.276           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.209           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.854           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.884           ms/op
ClientGrpc.existUser                      sample  334087   2.873 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.603           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.875           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.444           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.549           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.199           ms/op
ClientGrpc.getUser                        sample  315424   3.044 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.846           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.219           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.250           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.872           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  237530   4.042 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.968           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.161           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.025           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.036           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.674           ms/op
