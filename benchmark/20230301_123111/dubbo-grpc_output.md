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
# Warmup Iteration   1: 4.529 ops/ms
# Warmup Iteration   2: 9.412 ops/ms
# Warmup Iteration   3: 10.410 ops/ms
Iteration   1: 10.497 ops/ms
Iteration   2: 10.299 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.447 ±(99.9%) 2.372 ops/ms [Average]
  (min, avg, max) = (10.299, 10.447, 10.545), stdev = 0.130
  CI (99.9%): [8.075, 12.819] (assumes normal distribution)


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
# Warmup Iteration   1: 7.967 ops/ms
# Warmup Iteration   2: 10.786 ops/ms
# Warmup Iteration   3: 11.005 ops/ms
Iteration   1: 10.596 ops/ms
Iteration   2: 10.690 ops/ms
Iteration   3: 10.903 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.729 ±(99.9%) 2.869 ops/ms [Average]
  (min, avg, max) = (10.596, 10.729, 10.903), stdev = 0.157
  CI (99.9%): [7.860, 13.599] (assumes normal distribution)


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
# Warmup Iteration   1: 7.408 ops/ms
# Warmup Iteration   2: 10.168 ops/ms
# Warmup Iteration   3: 10.561 ops/ms
Iteration   1: 10.444 ops/ms
Iteration   2: 10.345 ops/ms
Iteration   3: 10.390 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.393 ±(99.9%) 0.912 ops/ms [Average]
  (min, avg, max) = (10.345, 10.393, 10.444), stdev = 0.050
  CI (99.9%): [9.481, 11.306] (assumes normal distribution)


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
# Warmup Iteration   1: 5.879 ops/ms
# Warmup Iteration   2: 8.040 ops/ms
# Warmup Iteration   3: 8.059 ops/ms
Iteration   1: 8.280 ops/ms
Iteration   2: 8.469 ops/ms
Iteration   3: 8.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.298 ±(99.9%) 2.956 ops/ms [Average]
  (min, avg, max) = (8.146, 8.298, 8.469), stdev = 0.162
  CI (99.9%): [5.343, 11.254] (assumes normal distribution)


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
# Warmup Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.003 ms/op
Iteration   1: 3.015 ±(99.9%) 0.003 ms/op
Iteration   2: 3.094 ±(99.9%) 0.002 ms/op
Iteration   3: 3.154 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.088 ±(99.9%) 1.265 ms/op [Average]
  (min, avg, max) = (3.015, 3.088, 3.154), stdev = 0.069
  CI (99.9%): [1.823, 4.352] (assumes normal distribution)


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
# Warmup Iteration   1: 3.717 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.929 ±(99.9%) 0.003 ms/op
Iteration   1: 2.949 ±(99.9%) 0.003 ms/op
Iteration   2: 2.880 ±(99.9%) 0.004 ms/op
Iteration   3: 2.880 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.903 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (2.880, 2.903, 2.949), stdev = 0.040
  CI (99.9%): [2.174, 3.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.034 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.099 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.058 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.003 ms/op
Iteration   2: 2.987 ±(99.9%) 0.002 ms/op
Iteration   3: 2.992 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.024 ±(99.9%) 1.083 ms/op [Average]
  (min, avg, max) = (2.987, 3.024, 3.093), stdev = 0.059
  CI (99.9%): [1.941, 4.107] (assumes normal distribution)


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
# Warmup Iteration   1: 5.184 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.049 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.027 ms/op
Iteration   1: 3.854 ±(99.9%) 0.011 ms/op
Iteration   2: 3.835 ±(99.9%) 0.010 ms/op
Iteration   3: 3.988 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.892 ±(99.9%) 1.522 ms/op [Average]
  (min, avg, max) = (3.835, 3.892, 3.988), stdev = 0.083
  CI (99.9%): [2.370, 5.414] (assumes normal distribution)


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.007 ms/op
Iteration   1: 3.068 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.716 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  7.373 ms/op
                 createUser·p0.9999: 11.380 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   2: 3.070 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.707 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  8.634 ms/op
                 createUser·p0.9999: 14.807 ms/op
                 createUser·p1.00:   15.761 ms/op

Iteration   3: 3.067 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.470 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.758 ms/op
                 createUser·p0.9999: 14.582 ms/op
                 createUser·p1.00:   15.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 312871
  mean =      3.068 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1205 
    [ 1.250,  2.500) = 27569 
    [ 2.500,  3.750) = 259614 
    [ 3.750,  5.000) = 23411 
    [ 5.000,  6.250) = 490 
    [ 6.250,  7.500) = 200 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 80 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 79 
    [15.000, 16.250) = 11 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     14.528 ms/op
     p(99.9990) =     15.645 ms/op
     p(99.9999) =     15.761 ms/op
    p(100.0000) =     15.761 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.066 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.935 ±(99.9%) 0.006 ms/op
Iteration   1: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.670 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.576 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  5.726 ms/op
                 existUser·p0.9999: 11.485 ms/op
                 existUser·p1.00:   11.747 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.679 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.695 ms/op
                 existUser·p0.95:   3.912 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  7.266 ms/op
                 existUser·p0.9999: 14.783 ms/op
                 existUser·p1.00:   15.286 ms/op

Iteration   3: 2.922 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.438 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.727 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  12.314 ms/op
                 existUser·p0.9999: 26.118 ms/op
                 existUser·p1.00:   26.509 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326630
  mean =      2.938 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51833 
    [ 2.500,  5.000) = 273540 
    [ 5.000,  7.500) = 914 
    [ 7.500, 10.000) = 89 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      7.766 ms/op
     p(99.9900) =     23.102 ms/op
     p(99.9990) =     26.459 ms/op
     p(99.9999) =     26.509 ms/op
    p(100.0000) =     26.509 ms/op


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
# Warmup Iteration   1: 3.799 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.192 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.007 ms/op
Iteration   1: 3.081 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.589 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  10.387 ms/op
                 getUser·p0.9999: 20.861 ms/op
                 getUser·p1.00:   21.168 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.493 ms/op
                 getUser·p0.9999: 17.874 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   3: 2.996 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.674 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.141 ms/op
                 getUser·p0.999:  7.708 ms/op
                 getUser·p0.9999: 18.535 ms/op
                 getUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315801
  mean =      3.038 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29043 
    [ 2.500,  5.000) = 285786 
    [ 5.000,  7.500) = 638 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.035 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.972 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     21.065 ms/op
     p(99.9999) =     21.168 ms/op
    p(100.0000) =     21.168 ms/op


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
# Warmup Iteration   1: 4.650 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.011 ms/op
Iteration   1: 3.906 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.047 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.996 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 20.404 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.504 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.022 ms/op
                 listUser·p0.9999: 23.953 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 3.858 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.637 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  17.170 ms/op
                 listUser·p0.9999: 26.766 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244895
  mean =      3.918 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4240 
    [ 2.500,  5.000) = 215234 
    [ 5.000,  7.500) = 24243 
    [ 7.500, 10.000) = 694 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.504 ms/op
     p(50.0000) =      3.740 ms/op
     p(90.0000) =      5.030 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     15.650 ms/op
     p(99.9900) =     23.937 ms/op
     p(99.9990) =     27.347 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.447 ± 2.372  ops/ms
ClientGrpc.existUser                       thrpt       3  10.729 ± 2.869  ops/ms
ClientGrpc.getUser                         thrpt       3  10.393 ± 0.912  ops/ms
ClientGrpc.listUser                        thrpt       3   8.298 ± 2.956  ops/ms
ClientGrpc.createUser                       avgt       3   3.088 ± 1.265   ms/op
ClientGrpc.existUser                        avgt       3   2.903 ± 0.729   ms/op
ClientGrpc.getUser                          avgt       3   3.024 ± 1.083   ms/op
ClientGrpc.listUser                         avgt       3   3.892 ± 1.522   ms/op
ClientGrpc.createUser                     sample  312871   3.068 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.470           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.260           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.200           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.528           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.761           ms/op
ClientGrpc.existUser                      sample  326630   2.938 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.438           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.600           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.334           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.766           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.102           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.509           ms/op
ClientGrpc.getUser                        sample  315801   3.038 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.589           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.613           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.972           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.054           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.168           ms/op
ClientGrpc.listUser                       sample  244895   3.918 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.504           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.740           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.650           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.937           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.312           ms/op
