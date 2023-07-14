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
# Warmup Iteration   1: 4.480 ops/ms
# Warmup Iteration   2: 9.164 ops/ms
# Warmup Iteration   3: 9.960 ops/ms
Iteration   1: 10.546 ops/ms
Iteration   2: 10.448 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.427 ±(99.9%) 2.395 ops/ms [Average]
  (min, avg, max) = (10.286, 10.427, 10.546), stdev = 0.131
  CI (99.9%): [8.031, 12.822] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.420 ops/ms
# Warmup Iteration   2: 10.534 ops/ms
# Warmup Iteration   3: 11.061 ops/ms
Iteration   1: 11.141 ops/ms
Iteration   2: 10.913 ops/ms
Iteration   3: 10.973 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.009 ±(99.9%) 2.151 ops/ms [Average]
  (min, avg, max) = (10.913, 11.009, 11.141), stdev = 0.118
  CI (99.9%): [8.858, 13.160] (assumes normal distribution)


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
# Warmup Iteration   1: 7.299 ops/ms
# Warmup Iteration   2: 10.242 ops/ms
# Warmup Iteration   3: 10.383 ops/ms
Iteration   1: 10.795 ops/ms
Iteration   2: 10.680 ops/ms
Iteration   3: 10.646 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.707 ±(99.9%) 1.417 ops/ms [Average]
  (min, avg, max) = (10.646, 10.707, 10.795), stdev = 0.078
  CI (99.9%): [9.290, 12.124] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.580 ops/ms
# Warmup Iteration   2: 7.759 ops/ms
# Warmup Iteration   3: 8.045 ops/ms
Iteration   1: 8.029 ops/ms
Iteration   2: 8.065 ops/ms
Iteration   3: 7.975 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.023 ±(99.9%) 0.828 ops/ms [Average]
  (min, avg, max) = (7.975, 8.023, 8.065), stdev = 0.045
  CI (99.9%): [7.195, 8.851] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.115 ±(99.9%) 0.002 ms/op
Iteration   2: 3.091 ±(99.9%) 0.003 ms/op
Iteration   3: 3.078 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.095 ±(99.9%) 0.337 ms/op [Average]
  (min, avg, max) = (3.078, 3.095, 3.115), stdev = 0.018
  CI (99.9%): [2.758, 3.432] (assumes normal distribution)


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
# Warmup Iteration   1: 4.002 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.004 ms/op
Iteration   1: 2.917 ±(99.9%) 0.002 ms/op
Iteration   2: 2.915 ±(99.9%) 0.002 ms/op
Iteration   3: 2.971 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.935 ±(99.9%) 0.580 ms/op [Average]
  (min, avg, max) = (2.915, 2.935, 2.971), stdev = 0.032
  CI (99.9%): [2.355, 3.514] (assumes normal distribution)


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
# Warmup Iteration   1: 4.283 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.010 ±(99.9%) 0.003 ms/op
Iteration   2: 3.047 ±(99.9%) 0.003 ms/op
Iteration   3: 3.021 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.026 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.010, 3.026, 3.047), stdev = 0.019
  CI (99.9%): [2.679, 3.373] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.499 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.130 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.007 ms/op
Iteration   1: 3.983 ±(99.9%) 0.016 ms/op
Iteration   2: 3.942 ±(99.9%) 0.039 ms/op
Iteration   3: 3.959 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.382 ms/op [Average]
  (min, avg, max) = (3.942, 3.961, 3.983), stdev = 0.021
  CI (99.9%): [3.580, 4.343] (assumes normal distribution)


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.257 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.555 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.883 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.193 ms/op
                 createUser·p0.9999: 18.612 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   2: 3.023 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.758 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  6.570 ms/op
                 createUser·p0.9999: 18.345 ms/op
                 createUser·p1.00:   19.300 ms/op

Iteration   3: 3.053 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.638 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.662 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  7.524 ms/op
                 createUser·p0.9999: 16.385 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 315460
  mean =      3.043 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1218 
    [ 1.250,  2.500) = 16882 
    [ 2.500,  3.750) = 281449 
    [ 3.750,  5.000) = 14569 
    [ 5.000,  6.250) = 808 
    [ 6.250,  7.500) = 264 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 22 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 47 

  Percentiles, ms/op:
      p(0.0000) =      0.555 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.752 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.131 ms/op
     p(99.9900) =     18.347 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 3.710 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.080 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.007 ms/op
Iteration   1: 2.944 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.752 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  5.859 ms/op
                 existUser·p0.9999: 12.536 ms/op
                 existUser·p1.00:   13.025 ms/op

Iteration   2: 2.914 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.673 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.588 ms/op
                 existUser·p0.99:   4.497 ms/op
                 existUser·p0.999:  7.259 ms/op
                 existUser·p0.9999: 15.975 ms/op
                 existUser·p1.00:   16.204 ms/op

Iteration   3: 2.928 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  7.217 ms/op
                 existUser·p0.9999: 18.363 ms/op
                 existUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 327541
  mean =      2.929 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2827 
    [ 1.250,  2.500) = 31330 
    [ 2.500,  3.750) = 280577 
    [ 3.750,  5.000) = 11780 
    [ 5.000,  6.250) = 587 
    [ 6.250,  7.500) = 201 
    [ 7.500,  8.750) = 42 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 39 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.795 ms/op
     p(99.9900) =     16.818 ms/op
     p(99.9990) =     19.276 ms/op
     p(99.9999) =     19.366 ms/op
    p(100.0000) =     19.366 ms/op


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
# Warmup Iteration   1: 4.148 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.119 ±(99.9%) 0.007 ms/op
Iteration   1: 3.017 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.754 ms/op
                 getUser·p0.50:   3.023 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  6.258 ms/op
                 getUser·p0.9999: 17.138 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.069 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.559 ms/op
                 getUser·p0.999:  10.611 ms/op
                 getUser·p0.9999: 20.302 ms/op
                 getUser·p1.00:   20.808 ms/op

Iteration   3: 3.052 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  5.958 ms/op
                 getUser·p0.9999: 18.743 ms/op
                 getUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315246
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18658 
    [ 2.500,  5.000) = 295160 
    [ 5.000,  7.500) = 1154 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.636 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      7.150 ms/op
     p(99.9900) =     18.883 ms/op
     p(99.9990) =     20.672 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


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
# Warmup Iteration   1: 5.587 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.093 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.973 ±(99.9%) 0.010 ms/op
Iteration   1: 3.940 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.116 ms/op
                 listUser·p0.9999: 18.740 ms/op
                 listUser·p1.00:   19.169 ms/op

Iteration   2: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.743 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.439 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.553 ms/op
                 listUser·p0.9999: 18.806 ms/op
                 listUser·p1.00:   20.185 ms/op

Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.507 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.914 ms/op
                 listUser·p0.999:  13.857 ms/op
                 listUser·p0.9999: 25.850 ms/op
                 listUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242518
  mean =      3.954 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3742 
    [ 2.500,  5.000) = 216670 
    [ 5.000,  7.500) = 20942 
    [ 7.500, 10.000) = 683 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 205 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.507 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      6.824 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     24.551 ms/op
     p(99.9990) =     26.102 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.427 ± 2.395  ops/ms
ClientGrpc.existUser                       thrpt       3  11.009 ± 2.151  ops/ms
ClientGrpc.getUser                         thrpt       3  10.707 ± 1.417  ops/ms
ClientGrpc.listUser                        thrpt       3   8.023 ± 0.828  ops/ms
ClientGrpc.createUser                       avgt       3   3.095 ± 0.337   ms/op
ClientGrpc.existUser                        avgt       3   2.935 ± 0.580   ms/op
ClientGrpc.getUser                          avgt       3   3.026 ± 0.347   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.382   ms/op
ClientGrpc.createUser                     sample  315460   3.043 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.555           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.523           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.131           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.347           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.300           ms/op
ClientGrpc.existUser                      sample  327541   2.929 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.665           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.929           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.416           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.358           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.795           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.818           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.366           ms/op
ClientGrpc.getUser                        sample  315246   3.046 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.636           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.150           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.883           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.808           ms/op
ClientGrpc.listUser                       sample  242518   3.954 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.507           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.813           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.530           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.824           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.551           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.214           ms/op
