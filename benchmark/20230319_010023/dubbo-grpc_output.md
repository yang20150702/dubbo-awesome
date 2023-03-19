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
# Warmup Iteration   1: 4.078 ops/ms
# Warmup Iteration   2: 9.118 ops/ms
# Warmup Iteration   3: 10.334 ops/ms
Iteration   1: 10.624 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.668 ±(99.9%) 1.219 ops/ms [Average]
  (min, avg, max) = (10.624, 10.668, 10.745), stdev = 0.067
  CI (99.9%): [9.450, 11.887] (assumes normal distribution)


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
# Warmup Iteration   1: 7.875 ops/ms
# Warmup Iteration   2: 10.666 ops/ms
# Warmup Iteration   3: 10.966 ops/ms
Iteration   1: 11.213 ops/ms
Iteration   2: 11.180 ops/ms
Iteration   3: 11.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.166 ±(99.9%) 1.024 ops/ms [Average]
  (min, avg, max) = (11.104, 11.166, 11.213), stdev = 0.056
  CI (99.9%): [10.142, 12.190] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.149 ops/ms
# Warmup Iteration   2: 10.231 ops/ms
# Warmup Iteration   3: 10.615 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.664 ops/ms
Iteration   3: 10.756 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.661 ±(99.9%) 1.761 ops/ms [Average]
  (min, avg, max) = (10.563, 10.661, 10.756), stdev = 0.097
  CI (99.9%): [8.900, 12.422] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.277 ops/ms
# Warmup Iteration   2: 7.891 ops/ms
# Warmup Iteration   3: 8.033 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.425 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.247 ±(99.9%) 3.126 ops/ms [Average]
  (min, avg, max) = (8.083, 8.247, 8.425), stdev = 0.171
  CI (99.9%): [5.121, 11.374] (assumes normal distribution)


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
# Warmup Iteration   1: 4.508 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.002 ms/op
Iteration   1: 3.066 ±(99.9%) 0.003 ms/op
Iteration   2: 2.985 ±(99.9%) 0.002 ms/op
Iteration   3: 3.038 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.030 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (2.985, 3.030, 3.066), stdev = 0.041
  CI (99.9%): [2.280, 3.779] (assumes normal distribution)


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
# Warmup Iteration   1: 3.812 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.973 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.859 ±(99.9%) 0.003 ms/op
Iteration   1: 2.820 ±(99.9%) 0.003 ms/op
Iteration   2: 2.908 ±(99.9%) 0.002 ms/op
Iteration   3: 2.892 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.873 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (2.820, 2.873, 2.908), stdev = 0.047
  CI (99.9%): [2.017, 3.729] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.156 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.004 ms/op
Iteration   1: 3.024 ±(99.9%) 0.003 ms/op
Iteration   2: 2.954 ±(99.9%) 0.002 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.641 ms/op [Average]
  (min, avg, max) = (2.954, 2.991, 3.024), stdev = 0.035
  CI (99.9%): [2.350, 3.632] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.014 ms/op
Iteration   1: 3.982 ±(99.9%) 0.011 ms/op
Iteration   2: 3.903 ±(99.9%) 0.011 ms/op
Iteration   3: 3.951 ±(99.9%) 0.037 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.945 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.903, 3.945, 3.982), stdev = 0.040
  CI (99.9%): [3.219, 4.672] (assumes normal distribution)


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
# Warmup Iteration   1: 4.355 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.061 ±(99.9%) 0.006 ms/op
Iteration   1: 2.993 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.641 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.428 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.055 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   2: 3.063 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  12.584 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   22.053 ms/op

Iteration   3: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  7.683 ms/op
                 createUser·p0.9999: 21.945 ms/op
                 createUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317600
  mean =      3.021 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22823 
    [ 2.500,  5.000) = 293186 
    [ 5.000,  7.500) = 1094 
    [ 7.500, 10.000) = 186 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.994 ms/op
     p(99.9900) =     21.496 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.987 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.898 ±(99.9%) 0.006 ms/op
Iteration   1: 2.899 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.901 ms/op
                 existUser·p0.50:   2.875 ms/op
                 existUser·p0.90:   3.260 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   4.170 ms/op
                 existUser·p0.999:  6.447 ms/op
                 existUser·p0.9999: 14.269 ms/op
                 existUser·p1.00:   14.582 ms/op

Iteration   2: 2.881 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.428 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  5.555 ms/op
                 existUser·p0.9999: 13.140 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.876 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.715 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.445 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.024 ms/op
                 existUser·p0.9999: 15.382 ms/op
                 existUser·p1.00:   16.138 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332764
  mean =      2.885 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 737 
    [ 1.250,  2.500) = 34487 
    [ 2.500,  3.750) = 290591 
    [ 3.750,  5.000) = 6011 
    [ 5.000,  6.250) = 620 
    [ 6.250,  7.500) = 158 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.867 ms/op
     p(90.0000) =      3.256 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.210 ms/op
     p(99.9900) =     14.409 ms/op
     p(99.9990) =     15.559 ms/op
     p(99.9999) =     16.138 ms/op
    p(100.0000) =     16.138 ms/op


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.007 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.952 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.104 ms/op
                 getUser·p0.9999: 12.633 ms/op
                 getUser·p1.00:   12.861 ms/op

Iteration   2: 3.025 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.628 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.555 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.788 ms/op
                 getUser·p0.9999: 14.219 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.327 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  8.252 ms/op
                 getUser·p0.9999: 18.359 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317002
  mean =      3.028 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 544 
    [ 1.250,  2.500) = 18921 
    [ 2.500,  3.750) = 281256 
    [ 3.750,  5.000) = 14707 
    [ 5.000,  6.250) = 873 
    [ 6.250,  7.500) = 354 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      7.864 ms/op
     p(99.9900) =     15.827 ms/op
     p(99.9990) =     19.054 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 5.130 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.010 ms/op
Iteration   1: 3.915 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.748 ms/op
                 listUser·p0.95:   5.628 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.637 ms/op
                 listUser·p0.9999: 22.086 ms/op
                 listUser·p1.00:   25.756 ms/op

Iteration   2: 3.963 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  13.735 ms/op
                 listUser·p0.9999: 19.200 ms/op
                 listUser·p1.00:   19.628 ms/op

Iteration   3: 3.897 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.057 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.743 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  16.908 ms/op
                 listUser·p0.9999: 21.823 ms/op
                 listUser·p1.00:   24.445 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244509
  mean =      3.925 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2687 
    [ 2.500,  5.000) = 220390 
    [ 5.000,  7.500) = 20332 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.755 ms/op
     p(99.0000) =      6.881 ms/op
     p(99.9000) =     13.893 ms/op
     p(99.9900) =     21.823 ms/op
     p(99.9990) =     24.299 ms/op
     p(99.9999) =     25.756 ms/op
    p(100.0000) =     25.756 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.668 ± 1.219  ops/ms
ClientGrpc.existUser                       thrpt       3  11.166 ± 1.024  ops/ms
ClientGrpc.getUser                         thrpt       3  10.661 ± 1.761  ops/ms
ClientGrpc.listUser                        thrpt       3   8.247 ± 3.126  ops/ms
ClientGrpc.createUser                       avgt       3   3.030 ± 0.749   ms/op
ClientGrpc.existUser                        avgt       3   2.873 ± 0.856   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.641   ms/op
ClientGrpc.listUser                         avgt       3   3.945 ± 0.726   ms/op
ClientGrpc.createUser                     sample  317600   3.021 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.641           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.457           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.994           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.496           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.217           ms/op
ClientGrpc.existUser                      sample  332764   2.885 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.712           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.867           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.256           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.449           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.210           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.409           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.138           ms/op
ClientGrpc.getUser                        sample  317002   3.028 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.327           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.523           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.864           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.827           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  244509   3.925 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.057           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.781           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.755           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.881           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.893           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.823           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.756           ms/op
