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
# Warmup Iteration   1: 4.741 ops/ms
# Warmup Iteration   2: 9.561 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 11.081 ops/ms
Iteration   2: 10.184 ops/ms
Iteration   3: 10.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.470 ±(99.9%) 9.659 ops/ms [Average]
  (min, avg, max) = (10.145, 10.470, 11.081), stdev = 0.529
  CI (99.9%): [0.811, 20.129] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.961 ops/ms
# Warmup Iteration   2: 10.942 ops/ms
# Warmup Iteration   3: 10.972 ops/ms
Iteration   1: 10.809 ops/ms
Iteration   2: 11.283 ops/ms
Iteration   3: 10.987 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.026 ±(99.9%) 4.366 ops/ms [Average]
  (min, avg, max) = (10.809, 11.026, 11.283), stdev = 0.239
  CI (99.9%): [6.660, 15.392] (assumes normal distribution)


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
# Warmup Iteration   1: 7.063 ops/ms
# Warmup Iteration   2: 10.319 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.333 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.340 ±(99.9%) 1.811 ops/ms [Average]
  (min, avg, max) = (10.245, 10.340, 10.443), stdev = 0.099
  CI (99.9%): [8.529, 12.152] (assumes normal distribution)


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
# Warmup Iteration   1: 5.612 ops/ms
# Warmup Iteration   2: 7.667 ops/ms
# Warmup Iteration   3: 7.818 ops/ms
Iteration   1: 7.973 ops/ms
Iteration   2: 8.120 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.103 ±(99.9%) 2.230 ops/ms [Average]
  (min, avg, max) = (7.973, 8.103, 8.216), stdev = 0.122
  CI (99.9%): [5.873, 10.332] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.152 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.003 ms/op
Iteration   1: 3.014 ±(99.9%) 0.002 ms/op
Iteration   2: 3.195 ±(99.9%) 0.001 ms/op
Iteration   3: 3.166 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.125 ±(99.9%) 1.774 ms/op [Average]
  (min, avg, max) = (3.014, 3.125, 3.195), stdev = 0.097
  CI (99.9%): [1.351, 4.898] (assumes normal distribution)


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
# Warmup Iteration   1: 3.801 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.029 ±(99.9%) 0.002 ms/op
Iteration   1: 3.011 ±(99.9%) 0.002 ms/op
Iteration   2: 3.011 ±(99.9%) 0.001 ms/op
Iteration   3: 3.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.019 ±(99.9%) 0.246 ms/op [Average]
  (min, avg, max) = (3.011, 3.019, 3.035), stdev = 0.013
  CI (99.9%): [2.773, 3.265] (assumes normal distribution)


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
# Warmup Iteration   1: 3.733 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.003 ms/op
Iteration   1: 2.989 ±(99.9%) 0.003 ms/op
Iteration   2: 3.082 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.878 ms/op [Average]
  (min, avg, max) = (2.989, 3.043, 3.082), stdev = 0.048
  CI (99.9%): [2.165, 3.920] (assumes normal distribution)


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
# Warmup Iteration   1: 5.210 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 3.929 ±(99.9%) 0.004 ms/op
Iteration   1: 3.925 ±(99.9%) 0.071 ms/op
Iteration   2: 3.801 ±(99.9%) 0.004 ms/op
Iteration   3: 3.949 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.801, 3.892, 3.949), stdev = 0.079
  CI (99.9%): [2.447, 5.336] (assumes normal distribution)


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
# Warmup Iteration   1: 3.926 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
Iteration   1: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.773 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.879 ms/op
                 createUser·p0.99:   4.194 ms/op
                 createUser·p0.999:  6.791 ms/op
                 createUser·p0.9999: 11.917 ms/op
                 createUser·p1.00:   12.124 ms/op

Iteration   2: 3.188 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  9.470 ms/op
                 createUser·p0.9999: 13.745 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.822 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.860 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  6.740 ms/op
                 createUser·p0.9999: 16.083 ms/op
                 createUser·p1.00:   16.581 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304794
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 560 
    [ 1.250,  2.500) = 24533 
    [ 2.500,  3.750) = 239732 
    [ 3.750,  5.000) = 38864 
    [ 5.000,  6.250) = 635 
    [ 6.250,  7.500) = 212 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 47 
    [15.000, 16.250) = 10 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.940 ms/op
     p(99.9900) =     14.271 ms/op
     p(99.9990) =     16.480 ms/op
     p(99.9999) =     16.581 ms/op
    p(100.0000) =     16.581 ms/op


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
# Warmup Iteration   1: 3.617 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 2.995 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.884 ±(99.9%) 0.006 ms/op
Iteration   1: 2.834 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.659 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.363 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  6.465 ms/op
                 existUser·p0.9999: 16.576 ms/op
                 existUser·p1.00:   17.072 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.578 ms/op
                 existUser·p0.50:   2.908 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  6.313 ms/op
                 existUser·p0.9999: 14.122 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.631 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  8.629 ms/op
                 existUser·p0.9999: 16.483 ms/op
                 existUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332908
  mean =      2.882 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4886 
    [ 1.250,  2.500) = 52773 
    [ 2.500,  3.750) = 262356 
    [ 3.750,  5.000) = 11907 
    [ 5.000,  6.250) = 519 
    [ 6.250,  7.500) = 221 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 62 
    [15.000, 16.250) = 48 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.578 ms/op
     p(50.0000) =      2.900 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.674 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      6.636 ms/op
     p(99.9900) =     16.346 ms/op
     p(99.9990) =     16.930 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 3.992 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.990 ±(99.9%) 0.006 ms/op
Iteration   1: 3.061 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.650 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  11.236 ms/op
                 getUser·p0.9999: 14.968 ms/op
                 getUser·p1.00:   15.466 ms/op

Iteration   2: 2.958 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.376 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  6.513 ms/op
                 getUser·p0.9999: 21.207 ms/op
                 getUser·p1.00:   21.627 ms/op

Iteration   3: 2.997 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.610 ms/op
                 getUser·p0.9999: 17.990 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319341
  mean =      3.005 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30507 
    [ 2.500,  5.000) = 287855 
    [ 5.000,  7.500) = 620 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 76 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.376 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.551 ms/op
     p(95.0000) =      3.797 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      8.508 ms/op
     p(99.9900) =     20.355 ms/op
     p(99.9990) =     21.522 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 5.369 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.004 ±(99.9%) 0.012 ms/op
Iteration   1: 4.007 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.200 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.750 ms/op
                 listUser·p0.999:  11.884 ms/op
                 listUser·p0.9999: 14.553 ms/op
                 listUser·p1.00:   15.188 ms/op

Iteration   2: 3.983 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.554 ms/op
                 listUser·p0.999:  16.759 ms/op
                 listUser·p0.9999: 20.216 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   3: 4.009 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.720 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.172 ms/op
                 listUser·p0.9999: 23.204 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 239890
  mean =      4.000 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4824 
    [ 2.500,  5.000) = 203569 
    [ 5.000,  7.500) = 30386 
    [ 7.500, 10.000) = 700 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 111 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.720 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.724 ms/op
     p(99.9900) =     22.544 ms/op
     p(99.9990) =     25.559 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.470 ± 9.659  ops/ms
ClientGrpc.existUser                       thrpt       3  11.026 ± 4.366  ops/ms
ClientGrpc.getUser                         thrpt       3  10.340 ± 1.811  ops/ms
ClientGrpc.listUser                        thrpt       3   8.103 ± 2.230  ops/ms
ClientGrpc.createUser                       avgt       3   3.125 ± 1.774   ms/op
ClientGrpc.existUser                        avgt       3   3.019 ± 0.246   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.878   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 1.445   ms/op
ClientGrpc.createUser                     sample  304794   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.635           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.990           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.309           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           6.940           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.271           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.581           ms/op
ClientGrpc.existUser                      sample  332908   2.882 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.578           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.900           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.674           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.346           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.072           ms/op
ClientGrpc.getUser                        sample  319341   3.005 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.376           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.015           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.797           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.508           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.355           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.627           ms/op
ClientGrpc.listUser                       sample  239890   4.000 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.720           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.724           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.544           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.625           ms/op
