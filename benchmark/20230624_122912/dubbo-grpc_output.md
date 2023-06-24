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
# Warmup Iteration   1: 4.737 ops/ms
# Warmup Iteration   2: 9.179 ops/ms
# Warmup Iteration   3: 10.271 ops/ms
Iteration   1: 10.772 ops/ms
Iteration   2: 10.834 ops/ms
Iteration   3: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.809 ±(99.9%) 0.589 ops/ms [Average]
  (min, avg, max) = (10.772, 10.809, 10.834), stdev = 0.032
  CI (99.9%): [10.220, 11.397] (assumes normal distribution)


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
# Warmup Iteration   1: 8.058 ops/ms
# Warmup Iteration   2: 10.815 ops/ms
# Warmup Iteration   3: 11.142 ops/ms
Iteration   1: 11.136 ops/ms
Iteration   2: 11.379 ops/ms
Iteration   3: 11.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.370 ±(99.9%) 4.192 ops/ms [Average]
  (min, avg, max) = (11.136, 11.370, 11.596), stdev = 0.230
  CI (99.9%): [7.179, 15.562] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.682 ops/ms
# Warmup Iteration   2: 10.521 ops/ms
# Warmup Iteration   3: 10.760 ops/ms
Iteration   1: 10.747 ops/ms
Iteration   2: 10.824 ops/ms
Iteration   3: 10.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.839 ±(99.9%) 1.825 ops/ms [Average]
  (min, avg, max) = (10.747, 10.839, 10.945), stdev = 0.100
  CI (99.9%): [9.014, 12.664] (assumes normal distribution)


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
# Warmup Iteration   1: 5.718 ops/ms
# Warmup Iteration   2: 8.093 ops/ms
# Warmup Iteration   3: 8.008 ops/ms
Iteration   1: 8.460 ops/ms
Iteration   2: 8.416 ops/ms
Iteration   3: 8.439 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.438 ±(99.9%) 0.400 ops/ms [Average]
  (min, avg, max) = (8.416, 8.438, 8.460), stdev = 0.022
  CI (99.9%): [8.039, 8.838] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.047 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 2.973 ±(99.9%) 0.004 ms/op
Iteration   1: 2.944 ±(99.9%) 0.003 ms/op
Iteration   2: 2.944 ±(99.9%) 0.003 ms/op
Iteration   3: 2.947 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.945 ±(99.9%) 0.029 ms/op [Average]
  (min, avg, max) = (2.944, 2.945, 2.947), stdev = 0.002
  CI (99.9%): [2.915, 2.974] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.691 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.937 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.799 ±(99.9%) 0.003 ms/op
Iteration   1: 2.697 ±(99.9%) 0.004 ms/op
Iteration   2: 2.799 ±(99.9%) 0.004 ms/op
Iteration   3: 2.848 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.781 ±(99.9%) 1.410 ms/op [Average]
  (min, avg, max) = (2.697, 2.781, 2.848), stdev = 0.077
  CI (99.9%): [1.371, 4.192] (assumes normal distribution)


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
# Warmup Iteration   1: 4.033 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.045 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.958 ±(99.9%) 0.002 ms/op
Iteration   1: 2.987 ±(99.9%) 0.002 ms/op
Iteration   2: 2.894 ±(99.9%) 0.002 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.931 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (2.894, 2.931, 2.987), stdev = 0.049
  CI (99.9%): [2.036, 3.826] (assumes normal distribution)


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
# Warmup Iteration   1: 5.104 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.881 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.884 ±(99.9%) 0.031 ms/op
Iteration   1: 3.872 ±(99.9%) 0.013 ms/op
Iteration   2: 3.781 ±(99.9%) 0.019 ms/op
Iteration   3: 3.686 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.780 ±(99.9%) 1.699 ms/op [Average]
  (min, avg, max) = (3.686, 3.780, 3.872), stdev = 0.093
  CI (99.9%): [2.080, 5.479] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.840 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.946 ±(99.9%) 0.007 ms/op
Iteration   1: 2.952 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.569 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  7.484 ms/op
                 createUser·p0.9999: 13.718 ms/op
                 createUser·p1.00:   13.976 ms/op

Iteration   2: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.485 ms/op
                 createUser·p0.50:   2.937 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  8.963 ms/op
                 createUser·p0.9999: 15.309 ms/op
                 createUser·p1.00:   15.696 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.634 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  10.043 ms/op
                 createUser·p0.9999: 17.269 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321375
  mean =      2.987 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33051 
    [ 2.500,  5.000) = 286826 
    [ 5.000,  7.500) = 1069 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 42 
    [12.500, 15.000) = 141 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.485 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      8.940 ms/op
     p(99.9900) =     15.331 ms/op
     p(99.9990) =     17.498 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.387 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 2.926 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.820 ±(99.9%) 0.006 ms/op
Iteration   1: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.387 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.399 ms/op
                 existUser·p0.9999: 19.002 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   2: 2.952 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.737 ms/op
                 existUser·p0.9999: 22.244 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   3: 2.848 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.204 ms/op
                 existUser·p0.999:  6.241 ms/op
                 existUser·p0.9999: 17.523 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331561
  mean =      2.895 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44551 
    [ 2.500,  5.000) = 286057 
    [ 5.000,  7.500) = 675 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.879 ms/op
     p(90.0000) =      3.420 ms/op
     p(95.0000) =      3.625 ms/op
     p(99.0000) =      4.235 ms/op
     p(99.9000) =      6.480 ms/op
     p(99.9900) =     19.323 ms/op
     p(99.9990) =     22.960 ms/op
     p(99.9999) =     22.970 ms/op
    p(100.0000) =     22.970 ms/op


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
# Warmup Iteration   1: 3.784 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
Iteration   1: 2.930 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.580 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.408 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  7.406 ms/op
                 getUser·p0.9999: 18.192 ms/op
                 getUser·p1.00:   18.743 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.508 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  6.339 ms/op
                 getUser·p0.9999: 18.220 ms/op
                 getUser·p1.00:   18.907 ms/op

Iteration   3: 2.949 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.596 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.201 ms/op
                 getUser·p0.9999: 15.450 ms/op
                 getUser·p1.00:   15.811 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327122
  mean =      2.933 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2622 
    [ 1.250,  2.500) = 28894 
    [ 2.500,  3.750) = 283494 
    [ 3.750,  5.000) = 11095 
    [ 5.000,  6.250) = 609 
    [ 6.250,  7.500) = 165 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 37 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 37 

  Percentiles, ms/op:
      p(0.0000) =      0.508 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.637 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.586 ms/op
     p(99.9900) =     17.793 ms/op
     p(99.9990) =     18.734 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.105 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.855 ±(99.9%) 0.011 ms/op
Iteration   1: 3.903 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.630 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  16.202 ms/op
                 listUser·p0.9999: 19.582 ms/op
                 listUser·p1.00:   19.956 ms/op

Iteration   2: 3.887 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.665 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  17.078 ms/op
                 listUser·p0.9999: 23.348 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   3: 3.836 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.829 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  15.752 ms/op
                 listUser·p0.9999: 24.958 ms/op
                 listUser·p1.00:   25.395 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248034
  mean =      3.875 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6702 
    [ 2.500,  5.000) = 220733 
    [ 5.000,  7.500) = 19377 
    [ 7.500, 10.000) = 656 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.736 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.709 ms/op
     p(99.9000) =     16.007 ms/op
     p(99.9900) =     24.510 ms/op
     p(99.9990) =     25.299 ms/op
     p(99.9999) =     25.395 ms/op
    p(100.0000) =     25.395 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.809 ± 0.589  ops/ms
ClientGrpc.existUser                       thrpt       3  11.370 ± 4.192  ops/ms
ClientGrpc.getUser                         thrpt       3  10.839 ± 1.825  ops/ms
ClientGrpc.listUser                        thrpt       3   8.438 ± 0.400  ops/ms
ClientGrpc.createUser                       avgt       3   2.945 ± 0.029   ms/op
ClientGrpc.existUser                        avgt       3   2.781 ± 1.410   ms/op
ClientGrpc.getUser                          avgt       3   2.931 ± 0.895   ms/op
ClientGrpc.listUser                         avgt       3   3.780 ± 1.699   ms/op
ClientGrpc.createUser                     sample  321375   2.987 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.485           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.736           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.940           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.331           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.218           ms/op
ClientGrpc.existUser                      sample  331561   2.895 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.879           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.625           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.235           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.480           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.323           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.970           ms/op
ClientGrpc.getUser                        sample  327122   2.933 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.508           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.379           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.793           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  248034   3.875 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.630           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.736           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.709           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.007           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.510           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.395           ms/op
