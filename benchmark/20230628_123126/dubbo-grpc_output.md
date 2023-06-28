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
# Warmup Iteration   1: 3.960 ops/ms
# Warmup Iteration   2: 8.595 ops/ms
# Warmup Iteration   3: 9.780 ops/ms
Iteration   1: 9.969 ops/ms
Iteration   2: 10.229 ops/ms
Iteration   3: 10.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.120 ±(99.9%) 2.465 ops/ms [Average]
  (min, avg, max) = (9.969, 10.120, 10.229), stdev = 0.135
  CI (99.9%): [7.655, 12.584] (assumes normal distribution)


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
# Warmup Iteration   1: 7.175 ops/ms
# Warmup Iteration   2: 10.420 ops/ms
# Warmup Iteration   3: 10.940 ops/ms
Iteration   1: 10.978 ops/ms
Iteration   2: 10.729 ops/ms
Iteration   3: 11.161 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.956 ±(99.9%) 3.955 ops/ms [Average]
  (min, avg, max) = (10.729, 10.956, 11.161), stdev = 0.217
  CI (99.9%): [7.001, 14.911] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.572 ops/ms
# Warmup Iteration   2: 9.801 ops/ms
# Warmup Iteration   3: 10.108 ops/ms
Iteration   1: 10.227 ops/ms
Iteration   2: 10.286 ops/ms
Iteration   3: 10.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.265 ±(99.9%) 0.609 ops/ms [Average]
  (min, avg, max) = (10.227, 10.265, 10.286), stdev = 0.033
  CI (99.9%): [9.656, 10.874] (assumes normal distribution)


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
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 7.341 ops/ms
# Warmup Iteration   3: 7.719 ops/ms
Iteration   1: 7.794 ops/ms
Iteration   2: 7.898 ops/ms
Iteration   3: 7.811 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.834 ±(99.9%) 1.022 ops/ms [Average]
  (min, avg, max) = (7.794, 7.834, 7.898), stdev = 0.056
  CI (99.9%): [6.812, 8.856] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.992 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.103 ±(99.9%) 0.005 ms/op
Iteration   1: 3.141 ±(99.9%) 0.002 ms/op
Iteration   2: 3.101 ±(99.9%) 0.002 ms/op
Iteration   3: 3.116 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.120 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (3.101, 3.120, 3.141), stdev = 0.020
  CI (99.9%): [2.748, 3.491] (assumes normal distribution)


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.125 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.001 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.911 ±(99.9%) 0.002 ms/op
Iteration   3: 2.970 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.950 ±(99.9%) 0.626 ms/op [Average]
  (min, avg, max) = (2.911, 2.950, 2.970), stdev = 0.034
  CI (99.9%): [2.324, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.541 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.003 ms/op
Iteration   1: 3.082 ±(99.9%) 0.005 ms/op
Iteration   2: 3.099 ±(99.9%) 0.005 ms/op
Iteration   3: 3.064 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.082 ±(99.9%) 0.322 ms/op [Average]
  (min, avg, max) = (3.064, 3.082, 3.099), stdev = 0.018
  CI (99.9%): [2.759, 3.404] (assumes normal distribution)


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
# Warmup Iteration   1: 5.420 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.081 ±(99.9%) 0.009 ms/op
Iteration   1: 4.101 ±(99.9%) 0.029 ms/op
Iteration   2: 4.095 ±(99.9%) 0.009 ms/op
Iteration   3: 4.078 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.092 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (4.078, 4.092, 4.101), stdev = 0.012
  CI (99.9%): [3.873, 4.310] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.094 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.834 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  7.236 ms/op
                 createUser·p0.9999: 13.031 ms/op
                 createUser·p1.00:   13.287 ms/op

Iteration   2: 3.126 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.829 ms/op
                 createUser·p0.50:   3.097 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   3.744 ms/op
                 createUser·p0.99:   4.211 ms/op
                 createUser·p0.999:  7.103 ms/op
                 createUser·p0.9999: 12.939 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 3.116 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  7.793 ms/op
                 createUser·p0.9999: 24.286 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308391
  mean =      3.112 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9360 
    [ 2.500,  5.000) = 297828 
    [ 5.000,  7.500) = 906 
    [ 7.500, 10.000) = 71 
    [10.000, 12.500) = 72 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.592 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.386 ms/op
     p(99.9900) =     23.019 ms/op
     p(99.9990) =     25.035 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.764 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.330 ms/op
                 existUser·p0.95:   3.502 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  5.577 ms/op
                 existUser·p0.9999: 12.666 ms/op
                 existUser·p1.00:   12.943 ms/op

Iteration   2: 2.956 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.342 ms/op
                 existUser·p0.95:   3.469 ms/op
                 existUser·p0.99:   3.998 ms/op
                 existUser·p0.999:  7.011 ms/op
                 existUser·p0.9999: 19.038 ms/op
                 existUser·p1.00:   19.300 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  10.633 ms/op
                 existUser·p0.9999: 17.971 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 325755
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1184 
    [ 1.250,  2.500) = 27289 
    [ 2.500,  3.750) = 289008 
    [ 3.750,  5.000) = 7235 
    [ 5.000,  6.250) = 582 
    [ 6.250,  7.500) = 151 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 66 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 42 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.371 ms/op
     p(95.0000) =      3.547 ms/op
     p(99.0000) =      4.137 ms/op
     p(99.9000) =      7.285 ms/op
     p(99.9900) =     18.298 ms/op
     p(99.9990) =     19.194 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.113 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.663 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.633 ms/op
                 getUser·p0.95:   3.981 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  9.840 ms/op
                 getUser·p0.9999: 20.930 ms/op
                 getUser·p1.00:   21.299 ms/op

Iteration   2: 3.145 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.625 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  7.875 ms/op
                 getUser·p0.9999: 19.125 ms/op
                 getUser·p1.00:   19.595 ms/op

Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.032 ms/op
                 getUser·p0.50:   3.084 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  7.796 ms/op
                 getUser·p0.9999: 32.498 ms/op
                 getUser·p1.00:   32.801 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306805
  mean =      3.126 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12425 
    [ 2.500,  5.000) = 292496 
    [ 5.000,  7.500) = 1450 
    [ 7.500, 10.000) = 182 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.625 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.633 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      8.203 ms/op
     p(99.9900) =     31.773 ms/op
     p(99.9990) =     32.733 ms/op
     p(99.9999) =     32.801 ms/op
    p(100.0000) =     32.801 ms/op


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
# Warmup Iteration   1: 5.510 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.140 ±(99.9%) 0.011 ms/op
Iteration   1: 4.094 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.331 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  16.410 ms/op
                 listUser·p0.9999: 23.999 ms/op
                 listUser·p1.00:   24.347 ms/op

Iteration   2: 4.138 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  15.059 ms/op
                 listUser·p0.9999: 20.444 ms/op
                 listUser·p1.00:   21.660 ms/op

Iteration   3: 4.087 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.965 ms/op
                 listUser·p0.90:   4.702 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  17.785 ms/op
                 listUser·p0.9999: 21.698 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233634
  mean =      4.107 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1478 
    [ 2.500,  5.000) = 207190 
    [ 5.000,  7.500) = 23219 
    [ 7.500, 10.000) = 1337 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 87 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.079 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     17.051 ms/op
     p(99.9900) =     23.000 ms/op
     p(99.9990) =     24.303 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.120 ± 2.465  ops/ms
ClientGrpc.existUser                       thrpt       3  10.956 ± 3.955  ops/ms
ClientGrpc.getUser                         thrpt       3  10.265 ± 0.609  ops/ms
ClientGrpc.listUser                        thrpt       3   7.834 ± 1.022  ops/ms
ClientGrpc.createUser                       avgt       3   3.120 ± 0.371   ms/op
ClientGrpc.existUser                        avgt       3   2.950 ± 0.626   ms/op
ClientGrpc.getUser                          avgt       3   3.082 ± 0.322   ms/op
ClientGrpc.listUser                         avgt       3   4.092 ± 0.219   ms/op
ClientGrpc.createUser                     sample  308391   3.112 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.668           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.386           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.019           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.297           ms/op
ClientGrpc.existUser                      sample  325755   2.945 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.627           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.937           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.371           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.137           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.285           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.298           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.300           ms/op
ClientGrpc.getUser                        sample  306805   3.126 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.625           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.084           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.863           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.203           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          31.773           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          32.801           ms/op
ClientGrpc.listUser                       sample  233634   4.107 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.897           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.079           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.808           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.051           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.347           ms/op
