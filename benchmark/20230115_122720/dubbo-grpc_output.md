# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.450 ops/ms
# Warmup Iteration   2: 9.233 ops/ms
# Warmup Iteration   3: 9.964 ops/ms
Iteration   1: 9.805 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 9.953 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.883 ±(99.9%) 1.350 ops/ms [Average]
  (min, avg, max) = (9.805, 9.883, 9.953), stdev = 0.074
  CI (99.9%): [8.533, 11.234] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.461 ops/ms
# Warmup Iteration   2: 10.568 ops/ms
# Warmup Iteration   3: 11.159 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 10.593 ops/ms
Iteration   3: 10.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.696 ±(99.9%) 2.473 ops/ms [Average]
  (min, avg, max) = (10.593, 10.696, 10.850), stdev = 0.136
  CI (99.9%): [8.223, 13.168] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.285 ops/ms
# Warmup Iteration   2: 9.915 ops/ms
# Warmup Iteration   3: 10.223 ops/ms
Iteration   1: 10.057 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 10.027 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.066 ±(99.9%) 0.812 ops/ms [Average]
  (min, avg, max) = (10.027, 10.066, 10.114), stdev = 0.045
  CI (99.9%): [9.254, 10.878] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.231 ops/ms
# Warmup Iteration   2: 7.216 ops/ms
# Warmup Iteration   3: 8.054 ops/ms
Iteration   1: 8.107 ops/ms
Iteration   2: 7.891 ops/ms
Iteration   3: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.061 ±(99.9%) 2.785 ops/ms [Average]
  (min, avg, max) = (7.891, 8.061, 8.186), stdev = 0.153
  CI (99.9%): [5.276, 10.846] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.465 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.002 ms/op
Iteration   1: 3.135 ±(99.9%) 0.003 ms/op
Iteration   2: 3.219 ±(99.9%) 0.002 ms/op
Iteration   3: 3.157 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.793 ms/op [Average]
  (min, avg, max) = (3.135, 3.170, 3.219), stdev = 0.043
  CI (99.9%): [2.377, 3.964] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.739 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.002 ms/op
Iteration   1: 2.943 ±(99.9%) 0.003 ms/op
Iteration   2: 3.014 ±(99.9%) 0.002 ms/op
Iteration   3: 3.006 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.987 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (2.943, 2.987, 3.014), stdev = 0.039
  CI (99.9%): [2.276, 3.699] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.106 ±(99.9%) 0.002 ms/op
Iteration   2: 3.121 ±(99.9%) 0.002 ms/op
Iteration   3: 3.199 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.142 ±(99.9%) 0.908 ms/op [Average]
  (min, avg, max) = (3.106, 3.142, 3.199), stdev = 0.050
  CI (99.9%): [2.234, 4.050] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.417 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.020 ms/op
Iteration   1: 3.925 ±(99.9%) 0.010 ms/op
Iteration   2: 3.931 ±(99.9%) 0.022 ms/op
Iteration   3: 3.975 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.944 ±(99.9%) 0.493 ms/op [Average]
  (min, avg, max) = (3.925, 3.944, 3.975), stdev = 0.027
  CI (99.9%): [3.450, 4.437] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.211 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.098 ±(99.9%) 0.007 ms/op
Iteration   1: 3.129 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.112 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  6.554 ms/op
                 createUser·p0.9999: 13.100 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.031 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.277 ms/op
                 createUser·p0.50:   3.031 ms/op
                 createUser·p0.90:   3.682 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  6.691 ms/op
                 createUser·p0.9999: 15.614 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   3: 3.141 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   3.990 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  10.349 ms/op
                 createUser·p0.9999: 18.180 ms/op
                 createUser·p1.00:   18.645 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309678
  mean =      3.100 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1192 
    [ 1.250,  2.500) = 30652 
    [ 2.500,  3.750) = 241155 
    [ 3.750,  5.000) = 35750 
    [ 5.000,  6.250) = 436 
    [ 6.250,  7.500) = 148 
    [ 7.500,  8.750) = 64 
    [ 8.750, 10.000) = 45 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 37 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.277 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.809 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.350 ms/op
     p(99.9000) =      8.132 ms/op
     p(99.9900) =     15.943 ms/op
     p(99.9990) =     18.472 ms/op
     p(99.9999) =     18.645 ms/op
    p(100.0000) =     18.645 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.912 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.007 ms/op
Iteration   1: 3.033 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   4.035 ms/op
                 existUser·p0.99:   4.899 ms/op
                 existUser·p0.999:  6.847 ms/op
                 existUser·p0.9999: 25.344 ms/op
                 existUser·p1.00:   26.378 ms/op

Iteration   2: 3.057 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.792 ms/op
                 existUser·p0.50:   3.047 ms/op
                 existUser·p0.90:   3.813 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.448 ms/op
                 existUser·p0.999:  10.623 ms/op
                 existUser·p0.9999: 15.702 ms/op
                 existUser·p1.00:   16.712 ms/op

Iteration   3: 3.061 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.734 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   3.908 ms/op
                 existUser·p0.99:   4.201 ms/op
                 existUser·p0.999:  6.617 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 314814
  mean =      3.050 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44107 
    [ 2.500,  5.000) = 269118 
    [ 5.000,  7.500) = 1283 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      3.970 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      7.394 ms/op
     p(99.9900) =     24.314 ms/op
     p(99.9990) =     26.106 ms/op
     p(99.9999) =     26.378 ms/op
    p(100.0000) =     26.378 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.166 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.168 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.006 ms/op
Iteration   1: 3.134 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.149 ms/op
                 getUser·p0.9999: 18.532 ms/op
                 getUser·p1.00:   19.792 ms/op

Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.516 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.335 ms/op
                 getUser·p0.9999: 18.999 ms/op
                 getUser·p1.00:   19.431 ms/op

Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.595 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.260 ms/op
                 getUser·p0.999:  6.711 ms/op
                 getUser·p0.9999: 19.469 ms/op
                 getUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306854
  mean =      3.129 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20914 
    [ 2.500,  5.000) = 284683 
    [ 5.000,  7.500) = 964 
    [ 7.500, 10.000) = 69 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.516 ms/op
     p(50.0000) =      3.097 ms/op
     p(90.0000) =      3.731 ms/op
     p(95.0000) =      3.920 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.397 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     21.098 ms/op
     p(99.9999) =     21.299 ms/op
    p(100.0000) =     21.299 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.749 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.204 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.015 ±(99.9%) 0.012 ms/op
Iteration   1: 4.008 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   7.037 ms/op
                 listUser·p0.999:  13.455 ms/op
                 listUser·p0.9999: 15.075 ms/op
                 listUser·p1.00:   15.860 ms/op

Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.702 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.046 ms/op
                 listUser·p0.99:   7.602 ms/op
                 listUser·p0.999:  17.302 ms/op
                 listUser·p0.9999: 20.323 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 3.995 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.693 ms/op
                 listUser·p0.50:   3.830 ms/op
                 listUser·p0.90:   5.071 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  16.171 ms/op
                 listUser·p0.9999: 25.492 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237788
  mean =      4.039 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2065 
    [ 2.500,  5.000) = 208974 
    [ 5.000,  7.500) = 25006 
    [ 7.500, 10.000) = 1178 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.693 ms/op
     p(50.0000) =      3.858 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.168 ms/op
     p(99.9000) =     15.322 ms/op
     p(99.9900) =     24.976 ms/op
     p(99.9990) =     26.079 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.883 ± 1.350  ops/ms
ClientGrpc.existUser                       thrpt       3  10.696 ± 2.473  ops/ms
ClientGrpc.getUser                         thrpt       3  10.066 ± 0.812  ops/ms
ClientGrpc.listUser                        thrpt       3   8.061 ± 2.785  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.793   ms/op
ClientGrpc.existUser                        avgt       3   2.987 ± 0.712   ms/op
ClientGrpc.getUser                          avgt       3   3.142 ± 0.908   ms/op
ClientGrpc.listUser                         avgt       3   3.944 ± 0.493   ms/op
ClientGrpc.createUser                     sample  309678   3.100 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.277           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.809           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.132           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.943           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.645           ms/op
ClientGrpc.existUser                      sample  314814   3.050 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.635           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.970           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.394           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.314           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.378           ms/op
ClientGrpc.getUser                        sample  306854   3.129 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.516           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.097           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.731           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.920           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.397           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.104           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.299           ms/op
ClientGrpc.listUser                       sample  237788   4.039 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.693           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.858           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.168           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.322           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.976           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
