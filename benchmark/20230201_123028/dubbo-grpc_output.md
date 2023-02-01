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
# Warmup Iteration   1: 4.601 ops/ms
# Warmup Iteration   2: 8.970 ops/ms
# Warmup Iteration   3: 10.254 ops/ms
Iteration   1: 10.082 ops/ms
Iteration   2: 10.329 ops/ms
Iteration   3: 10.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.188 ±(99.9%) 2.322 ops/ms [Average]
  (min, avg, max) = (10.082, 10.188, 10.329), stdev = 0.127
  CI (99.9%): [7.866, 12.510] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.786 ops/ms
# Warmup Iteration   2: 10.594 ops/ms
# Warmup Iteration   3: 11.243 ops/ms
Iteration   1: 10.640 ops/ms
Iteration   2: 11.021 ops/ms
Iteration   3: 11.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.900 ±(99.9%) 4.102 ops/ms [Average]
  (min, avg, max) = (10.640, 10.900, 11.038), stdev = 0.225
  CI (99.9%): [6.798, 15.002] (assumes normal distribution)


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
# Warmup Iteration   1: 7.214 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.230 ops/ms
Iteration   1: 10.105 ops/ms
Iteration   2: 10.164 ops/ms
Iteration   3: 9.882 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.050 ±(99.9%) 2.706 ops/ms [Average]
  (min, avg, max) = (9.882, 10.050, 10.164), stdev = 0.148
  CI (99.9%): [7.344, 12.757] (assumes normal distribution)


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
# Warmup Iteration   1: 6.226 ops/ms
# Warmup Iteration   2: 7.756 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 7.803 ops/ms
Iteration   2: 7.831 ops/ms
Iteration   3: 7.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.849 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (7.803, 7.849, 7.915), stdev = 0.058
  CI (99.9%): [6.784, 8.915] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.126 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.141 ±(99.9%) 0.001 ms/op
Iteration   3: 3.168 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.122 ±(99.9%) 1.062 ms/op [Average]
  (min, avg, max) = (3.056, 3.122, 3.168), stdev = 0.058
  CI (99.9%): [2.059, 4.184] (assumes normal distribution)


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
# Warmup Iteration   1: 3.930 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.002 ms/op
Iteration   1: 3.015 ±(99.9%) 0.002 ms/op
Iteration   2: 3.002 ±(99.9%) 0.002 ms/op
Iteration   3: 2.906 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.974 ±(99.9%) 1.085 ms/op [Average]
  (min, avg, max) = (2.906, 2.974, 3.015), stdev = 0.059
  CI (99.9%): [1.890, 4.059] (assumes normal distribution)


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
# Warmup Iteration   1: 4.186 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.097 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.049 ±(99.9%) 0.003 ms/op
Iteration   1: 3.080 ±(99.9%) 0.002 ms/op
Iteration   2: 3.088 ±(99.9%) 0.008 ms/op
Iteration   3: 3.092 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.110 ms/op [Average]
  (min, avg, max) = (3.080, 3.087, 3.092), stdev = 0.006
  CI (99.9%): [2.977, 3.197] (assumes normal distribution)


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
# Warmup Iteration   1: 5.137 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.031 ±(99.9%) 0.023 ms/op
Iteration   1: 4.070 ±(99.9%) 0.011 ms/op
Iteration   2: 4.033 ±(99.9%) 0.014 ms/op
Iteration   3: 3.992 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.032 ±(99.9%) 0.707 ms/op [Average]
  (min, avg, max) = (3.992, 4.032, 4.070), stdev = 0.039
  CI (99.9%): [3.325, 4.739] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.090 ±(99.9%) 0.006 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.744 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.221 ms/op
                 createUser·p0.9999: 11.795 ms/op
                 createUser·p1.00:   12.485 ms/op

Iteration   2: 3.115 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  9.378 ms/op
                 createUser·p0.9999: 17.227 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.164 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  7.602 ms/op
                 createUser·p0.9999: 15.064 ms/op
                 createUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309912
  mean =      3.096 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 887 
    [ 1.250,  2.500) = 29576 
    [ 2.500,  3.750) = 248252 
    [ 3.750,  5.000) = 30202 
    [ 5.000,  6.250) = 451 
    [ 6.250,  7.500) = 210 
    [ 7.500,  8.750) = 69 
    [ 8.750, 10.000) = 70 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 45 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.924 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.735 ms/op
     p(99.9900) =     16.466 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     18.055 ms/op
    p(100.0000) =     18.055 ms/op


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
# Warmup Iteration   1: 3.822 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 2.963 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.028 ±(99.9%) 0.006 ms/op
Iteration   1: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.596 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.151 ms/op
                 existUser·p0.999:  5.565 ms/op
                 existUser·p0.9999: 13.937 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   2: 3.030 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.654 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  9.333 ms/op
                 existUser·p0.9999: 14.727 ms/op
                 existUser·p1.00:   15.303 ms/op

Iteration   3: 2.943 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.586 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.777 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.689 ms/op
                 existUser·p0.9999: 14.520 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323169
  mean =      2.971 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2704 
    [ 1.250,  2.500) = 39887 
    [ 2.500,  3.750) = 261655 
    [ 3.750,  5.000) = 17947 
    [ 5.000,  6.250) = 475 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 49 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 95 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.586 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      7.389 ms/op
     p(99.9900) =     14.462 ms/op
     p(99.9990) =     15.004 ms/op
     p(99.9999) =     15.303 ms/op
    p(100.0000) =     15.303 ms/op


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
# Warmup Iteration   1: 3.933 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.008 ms/op
Iteration   1: 3.121 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.406 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  9.067 ms/op
                 getUser·p0.9999: 12.743 ms/op
                 getUser·p1.00:   12.960 ms/op

Iteration   2: 3.079 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.284 ms/op
                 getUser·p0.999:  7.076 ms/op
                 getUser·p0.9999: 22.736 ms/op
                 getUser·p1.00:   23.331 ms/op

Iteration   3: 3.101 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.813 ms/op
                 getUser·p0.50:   3.101 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.834 ms/op
                 getUser·p0.99:   4.170 ms/op
                 getUser·p0.999:  5.954 ms/op
                 getUser·p0.9999: 15.210 ms/op
                 getUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 309571
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21627 
    [ 2.500,  5.000) = 287047 
    [ 5.000,  7.500) = 539 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      7.860 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     23.226 ms/op
     p(99.9999) =     23.331 ms/op
    p(100.0000) =     23.331 ms/op


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
# Warmup Iteration   1: 5.148 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.029 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.050 ±(99.9%) 0.012 ms/op
Iteration   1: 3.884 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.695 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  13.501 ms/op
                 listUser·p0.9999: 19.678 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 4.142 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.495 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.809 ms/op
                 listUser·p0.999:  13.573 ms/op
                 listUser·p0.9999: 22.385 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.988 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.319 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.571 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.204 ms/op
                 listUser·p0.9999: 21.527 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239954
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4655 
    [ 2.500,  5.000) = 199922 
    [ 5.000,  7.500) = 34021 
    [ 7.500, 10.000) = 893 
    [10.000, 12.500) = 128 
    [12.500, 15.000) = 125 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     14.107 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     22.728 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.188 ± 2.322  ops/ms
ClientGrpc.existUser                       thrpt       3  10.900 ± 4.102  ops/ms
ClientGrpc.getUser                         thrpt       3  10.050 ± 2.706  ops/ms
ClientGrpc.listUser                        thrpt       3   7.849 ± 1.066  ops/ms
ClientGrpc.createUser                       avgt       3   3.122 ± 1.062   ms/op
ClientGrpc.existUser                        avgt       3   2.974 ± 1.085   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.110   ms/op
ClientGrpc.listUser                         avgt       3   4.032 ± 0.707   ms/op
ClientGrpc.createUser                     sample  309912   3.096 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.744           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.076           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.924           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.735           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.466           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.055           ms/op
ClientGrpc.existUser                      sample  323169   2.971 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.586           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.592           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.389           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.462           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.303           ms/op
ClientGrpc.getUser                        sample  309571   3.100 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.406           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.908           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.252           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.860           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.725           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.331           ms/op
ClientGrpc.listUser                       sample  239954   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.495           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.107           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.266           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.807           ms/op
