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
# Warmup Iteration   1: 4.111 ops/ms
# Warmup Iteration   2: 8.977 ops/ms
# Warmup Iteration   3: 9.942 ops/ms
Iteration   1: 10.617 ops/ms
Iteration   2: 10.549 ops/ms
Iteration   3: 10.642 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.603 ±(99.9%) 0.875 ops/ms [Average]
  (min, avg, max) = (10.549, 10.603, 10.642), stdev = 0.048
  CI (99.9%): [9.727, 11.478] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.553 ops/ms
# Warmup Iteration   2: 10.584 ops/ms
# Warmup Iteration   3: 11.194 ops/ms
Iteration   1: 11.161 ops/ms
Iteration   2: 11.150 ops/ms
Iteration   3: 11.264 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.192 ±(99.9%) 1.152 ops/ms [Average]
  (min, avg, max) = (11.150, 11.192, 11.264), stdev = 0.063
  CI (99.9%): [10.040, 12.344] (assumes normal distribution)


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
# Warmup Iteration   1: 7.192 ops/ms
# Warmup Iteration   2: 10.133 ops/ms
# Warmup Iteration   3: 10.757 ops/ms
Iteration   1: 10.610 ops/ms
Iteration   2: 10.617 ops/ms
Iteration   3: 10.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.608 ±(99.9%) 0.185 ops/ms [Average]
  (min, avg, max) = (10.597, 10.608, 10.617), stdev = 0.010
  CI (99.9%): [10.423, 10.793] (assumes normal distribution)


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
# Warmup Iteration   1: 5.842 ops/ms
# Warmup Iteration   2: 7.757 ops/ms
# Warmup Iteration   3: 8.084 ops/ms
Iteration   1: 8.092 ops/ms
Iteration   2: 8.113 ops/ms
Iteration   3: 8.226 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.144 ±(99.9%) 1.314 ops/ms [Average]
  (min, avg, max) = (8.092, 8.144, 8.226), stdev = 0.072
  CI (99.9%): [6.830, 9.457] (assumes normal distribution)


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
# Warmup Iteration   1: 4.329 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.066 ±(99.9%) 0.003 ms/op
Iteration   1: 3.050 ±(99.9%) 0.003 ms/op
Iteration   2: 3.030 ±(99.9%) 0.004 ms/op
Iteration   3: 2.984 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.021 ±(99.9%) 0.620 ms/op [Average]
  (min, avg, max) = (2.984, 3.021, 3.050), stdev = 0.034
  CI (99.9%): [2.401, 3.641] (assumes normal distribution)


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
# Warmup Iteration   1: 4.109 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.002 ms/op
Iteration   1: 2.896 ±(99.9%) 0.001 ms/op
Iteration   2: 2.826 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.871 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (2.826, 2.871, 2.896), stdev = 0.039
  CI (99.9%): [2.157, 3.585] (assumes normal distribution)


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
# Warmup Iteration   1: 4.206 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.025 ±(99.9%) 0.003 ms/op
Iteration   1: 2.960 ±(99.9%) 0.003 ms/op
Iteration   2: 2.978 ±(99.9%) 0.003 ms/op
Iteration   3: 2.996 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.978 ±(99.9%) 0.320 ms/op [Average]
  (min, avg, max) = (2.960, 2.978, 2.996), stdev = 0.018
  CI (99.9%): [2.658, 3.298] (assumes normal distribution)


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
# Warmup Iteration   1: 4.790 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.011 ms/op
Iteration   1: 3.869 ±(99.9%) 0.010 ms/op
Iteration   2: 3.846 ±(99.9%) 0.008 ms/op
Iteration   3: 3.906 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.874 ±(99.9%) 0.552 ms/op [Average]
  (min, avg, max) = (3.846, 3.874, 3.906), stdev = 0.030
  CI (99.9%): [3.321, 4.426] (assumes normal distribution)


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
# Warmup Iteration   1: 4.345 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.147 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
Iteration   1: 3.054 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.478 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  6.956 ms/op
                 createUser·p0.9999: 18.973 ms/op
                 createUser·p1.00:   19.169 ms/op

Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.318 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.633 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.604 ms/op
                 createUser·p0.999:  7.410 ms/op
                 createUser·p0.9999: 15.517 ms/op
                 createUser·p1.00:   15.991 ms/op

Iteration   3: 3.062 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.629 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  11.831 ms/op
                 createUser·p0.9999: 16.548 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313792
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 341 
    [ 1.250,  2.500) = 23116 
    [ 2.500,  3.750) = 271470 
    [ 3.750,  5.000) = 17236 
    [ 5.000,  6.250) = 974 
    [ 6.250,  7.500) = 298 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 83 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.318 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.793 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.305 ms/op
     p(99.9900) =     18.620 ms/op
     p(99.9990) =     19.127 ms/op
     p(99.9999) =     19.169 ms/op
    p(100.0000) =     19.169 ms/op


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
# Warmup Iteration   1: 4.050 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 2.961 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.006 ms/op
Iteration   1: 2.915 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.334 ms/op
                 existUser·p0.50:   2.884 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.104 ms/op
                 existUser·p0.999:  5.794 ms/op
                 existUser·p0.9999: 22.184 ms/op
                 existUser·p1.00:   24.740 ms/op

Iteration   2: 2.887 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.791 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.551 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  5.615 ms/op
                 existUser·p0.9999: 21.821 ms/op
                 existUser·p1.00:   22.053 ms/op

Iteration   3: 2.878 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   2.851 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  6.928 ms/op
                 existUser·p0.9999: 24.183 ms/op
                 existUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331733
  mean =      2.893 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45329 
    [ 2.500,  5.000) = 285717 
    [ 5.000,  7.500) = 522 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.334 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.043 ms/op
     p(99.9000) =      6.529 ms/op
     p(99.9900) =     22.593 ms/op
     p(99.9990) =     24.271 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.042 ±(99.9%) 0.008 ms/op
Iteration   1: 2.974 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.617 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.695 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  6.717 ms/op
                 getUser·p0.9999: 24.953 ms/op
                 getUser·p1.00:   25.526 ms/op

Iteration   2: 3.072 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.991 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.576 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.610 ms/op
                 getUser·p0.9999: 24.470 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   3: 3.001 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.627 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  6.602 ms/op
                 getUser·p0.9999: 22.796 ms/op
                 getUser·p1.00:   23.331 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318183
  mean =      3.015 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27934 
    [ 2.500,  5.000) = 289046 
    [ 5.000,  7.500) = 965 
    [ 7.500, 10.000) = 78 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.617 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      6.980 ms/op
     p(99.9900) =     23.992 ms/op
     p(99.9990) =     25.410 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 4.814 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.074 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.032 ±(99.9%) 0.012 ms/op
Iteration   1: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.715 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   6.865 ms/op
                 listUser·p0.999:  12.370 ms/op
                 listUser·p0.9999: 15.311 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   2: 3.935 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.027 ms/op
                 listUser·p0.9999: 26.450 ms/op
                 listUser·p1.00:   27.689 ms/op

Iteration   3: 3.884 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.165 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.636 ms/op
                 listUser·p0.999:  15.003 ms/op
                 listUser·p0.9999: 25.977 ms/op
                 listUser·p1.00:   26.345 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246201
  mean =      3.899 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3073 
    [ 2.500,  5.000) = 223848 
    [ 5.000,  7.500) = 18115 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.756 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.521 ms/op
     p(99.0000) =      6.816 ms/op
     p(99.9000) =     14.451 ms/op
     p(99.9900) =     25.919 ms/op
     p(99.9990) =     27.545 ms/op
     p(99.9999) =     27.689 ms/op
    p(100.0000) =     27.689 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.603 ± 0.875  ops/ms
ClientGrpc.existUser                       thrpt       3  11.192 ± 1.152  ops/ms
ClientGrpc.getUser                         thrpt       3  10.608 ± 0.185  ops/ms
ClientGrpc.listUser                        thrpt       3   8.144 ± 1.314  ops/ms
ClientGrpc.createUser                       avgt       3   3.021 ± 0.620   ms/op
ClientGrpc.existUser                        avgt       3   2.871 ± 0.714   ms/op
ClientGrpc.getUser                          avgt       3   2.978 ± 0.320   ms/op
ClientGrpc.listUser                         avgt       3   3.874 ± 0.552   ms/op
ClientGrpc.createUser                     sample  313792   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.318           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.019           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.793           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.305           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.620           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.169           ms/op
ClientGrpc.existUser                      sample  331733   2.893 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.334           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.043           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.593           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.740           ms/op
ClientGrpc.getUser                        sample  318183   3.015 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.617           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.982           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.711           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.415           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.980           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.992           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.526           ms/op
ClientGrpc.listUser                       sample  246201   3.899 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.756           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.816           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.919           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.689           ms/op
