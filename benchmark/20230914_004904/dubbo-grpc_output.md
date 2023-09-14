# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.099 ops/ms
# Warmup Iteration   2: 8.434 ops/ms
# Warmup Iteration   3: 9.685 ops/ms
Iteration   1: 10.085 ops/ms
Iteration   2: 10.085 ops/ms
Iteration   3: 10.306 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.158 ±(99.9%) 2.332 ops/ms [Average]
  (min, avg, max) = (10.085, 10.158, 10.306), stdev = 0.128
  CI (99.9%): [7.827, 12.490] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.289 ops/ms
# Warmup Iteration   2: 10.445 ops/ms
# Warmup Iteration   3: 10.484 ops/ms
Iteration   1: 10.606 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 10.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.729 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (10.606, 10.729, 10.837), stdev = 0.117
  CI (99.9%): [8.602, 12.855] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.760 ops/ms
# Warmup Iteration   2: 9.880 ops/ms
# Warmup Iteration   3: 10.032 ops/ms
Iteration   1: 10.106 ops/ms
Iteration   2: 10.006 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.150 ±(99.9%) 3.107 ops/ms [Average]
  (min, avg, max) = (10.006, 10.150, 10.338), stdev = 0.170
  CI (99.9%): [7.044, 13.257] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 5.335 ops/ms
# Warmup Iteration   2: 7.764 ops/ms
# Warmup Iteration   3: 8.125 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 8.087 ops/ms
Iteration   3: 8.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.110 ±(99.9%) 1.237 ops/ms [Average]
  (min, avg, max) = (8.056, 8.110, 8.186), stdev = 0.068
  CI (99.9%): [6.873, 9.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.326 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.001 ms/op
Iteration   1: 3.190 ±(99.9%) 0.001 ms/op
Iteration   2: 3.138 ±(99.9%) 0.002 ms/op
Iteration   3: 3.130 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.153 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (3.130, 3.153, 3.190), stdev = 0.033
  CI (99.9%): [2.559, 3.747] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.092 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.972 ±(99.9%) 0.002 ms/op
Iteration   1: 2.978 ±(99.9%) 0.002 ms/op
Iteration   2: 2.998 ±(99.9%) 0.002 ms/op
Iteration   3: 3.057 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.011 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (2.978, 3.011, 3.057), stdev = 0.041
  CI (99.9%): [2.263, 3.759] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.522 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.002 ms/op
Iteration   2: 3.146 ±(99.9%) 0.001 ms/op
Iteration   3: 3.096 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.122 ±(99.9%) 0.455 ms/op [Average]
  (min, avg, max) = (3.096, 3.122, 3.146), stdev = 0.025
  CI (99.9%): [2.668, 3.577] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.539 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.016 ms/op
Iteration   1: 3.995 ±(99.9%) 0.023 ms/op
Iteration   2: 3.939 ±(99.9%) 0.020 ms/op
Iteration   3: 3.953 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.962 ±(99.9%) 0.525 ms/op [Average]
  (min, avg, max) = (3.939, 3.962, 3.995), stdev = 0.029
  CI (99.9%): [3.438, 4.487] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.318 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.144 ±(99.9%) 0.006 ms/op
Iteration   1: 3.174 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.955 ms/op
                 createUser·p0.9999: 16.266 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.740 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  9.226 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.578 ms/op

Iteration   3: 3.143 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.571 ms/op
                 createUser·p0.999:  14.200 ms/op
                 createUser·p0.9999: 21.791 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303219
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9525 
    [ 2.500,  5.000) = 291848 
    [ 5.000,  7.500) = 1388 
    [ 7.500, 10.000) = 142 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =     10.830 ms/op
     p(99.9900) =     21.616 ms/op
     p(99.9990) =     23.067 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.234 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.009 ±(99.9%) 0.006 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.824 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.772 ms/op
                 existUser·p0.99:   4.137 ms/op
                 existUser·p0.999:  7.286 ms/op
                 existUser·p0.9999: 13.099 ms/op
                 existUser·p1.00:   13.418 ms/op

Iteration   2: 2.995 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.827 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   3.953 ms/op
                 existUser·p0.999:  6.353 ms/op
                 existUser·p0.9999: 13.533 ms/op
                 existUser·p1.00:   13.795 ms/op

Iteration   3: 3.015 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.121 ms/op
                 existUser·p0.999:  9.404 ms/op
                 existUser·p0.9999: 14.496 ms/op
                 existUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318254
  mean =      3.017 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 578 
    [ 1.250,  2.500) = 20862 
    [ 2.500,  3.750) = 284641 
    [ 3.750,  5.000) = 10900 
    [ 5.000,  6.250) = 575 
    [ 6.250,  7.500) = 384 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 3 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 118 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.547 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.059 ms/op
     p(99.9000) =      7.469 ms/op
     p(99.9900) =     14.041 ms/op
     p(99.9990) =     14.850 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.390 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.286 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.850 ms/op
                 getUser·p0.999:  8.868 ms/op
                 getUser·p0.9999: 14.205 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   2: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.902 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.805 ms/op
                 getUser·p0.99:   4.956 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 14.537 ms/op
                 getUser·p1.00:   16.663 ms/op

Iteration   3: 3.155 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.650 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  7.168 ms/op
                 getUser·p0.9999: 18.317 ms/op
                 getUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307042
  mean =      3.125 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 263 
    [ 1.250,  2.500) = 9370 
    [ 2.500,  3.750) = 277406 
    [ 3.750,  5.000) = 17675 
    [ 5.000,  6.250) = 1447 
    [ 6.250,  7.500) = 475 
    [ 7.500,  8.750) = 92 
    [ 8.750, 10.000) = 80 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 46 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 35 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      8.896 ms/op
     p(99.9900) =     17.770 ms/op
     p(99.9990) =     18.694 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.625 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.065 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.010 ms/op
Iteration   1: 3.971 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   4.973 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  13.053 ms/op
                 listUser·p0.9999: 14.745 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   2: 3.956 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.456 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 15.524 ms/op
                 listUser·p1.00:   16.515 ms/op

Iteration   3: 3.996 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  13.976 ms/op
                 listUser·p0.9999: 18.186 ms/op
                 listUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241526
  mean =      3.974 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 2086 
    [ 2.500,  3.750) = 84460 
    [ 3.750,  5.000) = 140884 
    [ 5.000,  6.250) = 7981 
    [ 6.250,  7.500) = 5065 
    [ 7.500,  8.750) = 456 
    [ 8.750, 10.000) = 130 
    [10.000, 11.250) = 47 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 132 
    [13.750, 15.000) = 141 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      5.235 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     13.713 ms/op
     p(99.9900) =     17.198 ms/op
     p(99.9990) =     18.440 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.158 ± 2.332  ops/ms
ClientGrpc.existUser                       thrpt       3  10.729 ± 2.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.150 ± 3.107  ops/ms
ClientGrpc.listUser                        thrpt       3   8.110 ± 1.237  ops/ms
ClientGrpc.createUser                       avgt       3   3.153 ± 0.594   ms/op
ClientGrpc.existUser                        avgt       3   3.011 ± 0.748   ms/op
ClientGrpc.getUser                          avgt       3   3.122 ± 0.455   ms/op
ClientGrpc.listUser                         avgt       3   3.962 ± 0.525   ms/op
ClientGrpc.createUser                     sample  303219   3.165 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.121           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.830           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.616           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  318254   3.017 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.703           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.469           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.041           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.352           ms/op
ClientGrpc.getUser                        sample  307042   3.125 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.650           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.719           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.896           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.770           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.907           ms/op
ClientGrpc.listUser                       sample  241526   3.974 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.883           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.440           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.713           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.198           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.481           ms/op
