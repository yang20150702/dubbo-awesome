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
# Warmup Iteration   1: 3.781 ops/ms
# Warmup Iteration   2: 8.392 ops/ms
# Warmup Iteration   3: 9.558 ops/ms
Iteration   1: 9.873 ops/ms
Iteration   2: 10.175 ops/ms
Iteration   3: 10.154 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.068 ±(99.9%) 3.079 ops/ms [Average]
  (min, avg, max) = (9.873, 10.068, 10.175), stdev = 0.169
  CI (99.9%): [6.989, 13.146] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 6.867 ops/ms
# Warmup Iteration   2: 9.985 ops/ms
# Warmup Iteration   3: 10.487 ops/ms
Iteration   1: 10.567 ops/ms
Iteration   2: 10.494 ops/ms
Iteration   3: 10.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.580 ±(99.9%) 1.706 ops/ms [Average]
  (min, avg, max) = (10.494, 10.580, 10.680), stdev = 0.093
  CI (99.9%): [8.875, 12.286] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.177 ops/ms
# Warmup Iteration   2: 9.740 ops/ms
# Warmup Iteration   3: 10.029 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.044 ops/ms
Iteration   3: 10.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.154 ±(99.9%) 2.928 ops/ms [Average]
  (min, avg, max) = (10.044, 10.154, 10.338), stdev = 0.160
  CI (99.9%): [7.226, 13.082] (assumes normal distribution)


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
# Warmup Iteration   1: 5.107 ops/ms
# Warmup Iteration   2: 8.075 ops/ms
# Warmup Iteration   3: 8.120 ops/ms
Iteration   1: 8.120 ops/ms
Iteration   2: 7.920 ops/ms
Iteration   3: 8.051 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.030 ±(99.9%) 1.854 ops/ms [Average]
  (min, avg, max) = (7.920, 8.030, 8.120), stdev = 0.102
  CI (99.9%): [6.176, 9.884] (assumes normal distribution)


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
# Warmup Iteration   1: 4.425 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.293 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.004 ms/op
Iteration   1: 3.153 ±(99.9%) 0.003 ms/op
Iteration   2: 3.154 ±(99.9%) 0.002 ms/op
Iteration   3: 3.162 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.156 ±(99.9%) 0.090 ms/op [Average]
  (min, avg, max) = (3.153, 3.156, 3.162), stdev = 0.005
  CI (99.9%): [3.066, 3.246] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.002 ms/op
Iteration   2: 3.015 ±(99.9%) 0.004 ms/op
Iteration   3: 3.069 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.041 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (3.015, 3.041, 3.069), stdev = 0.027
  CI (99.9%): [2.556, 3.527] (assumes normal distribution)


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.003 ms/op
Iteration   1: 3.118 ±(99.9%) 0.005 ms/op
Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
Iteration   3: 3.172 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.134 ±(99.9%) 0.598 ms/op [Average]
  (min, avg, max) = (3.113, 3.134, 3.172), stdev = 0.033
  CI (99.9%): [2.536, 3.732] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.015 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.046 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.012 ±(99.9%) 0.018 ms/op
Iteration   1: 4.025 ±(99.9%) 0.041 ms/op
Iteration   2: 3.956 ±(99.9%) 0.035 ms/op
Iteration   3: 3.948 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.976 ±(99.9%) 0.769 ms/op [Average]
  (min, avg, max) = (3.948, 3.976, 4.025), stdev = 0.042
  CI (99.9%): [3.207, 4.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
Iteration   1: 3.220 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   3.998 ms/op
                 createUser·p0.99:   4.833 ms/op
                 createUser·p0.999:  8.219 ms/op
                 createUser·p0.9999: 17.465 ms/op
                 createUser·p1.00:   17.891 ms/op

Iteration   2: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.658 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.819 ms/op
                 createUser·p0.9999: 20.142 ms/op
                 createUser·p1.00:   20.546 ms/op

Iteration   3: 3.162 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.446 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   3.838 ms/op
                 createUser·p0.99:   4.574 ms/op
                 createUser·p0.999:  18.273 ms/op
                 createUser·p0.9999: 29.721 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302313
  mean =      3.176 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10901 
    [ 2.500,  5.000) = 289360 
    [ 5.000,  7.500) = 1587 
    [ 7.500, 10.000) = 185 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.446 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.653 ms/op
     p(99.9000) =      8.521 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     29.983 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


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
# Warmup Iteration   1: 4.242 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.303 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  8.184 ms/op
                 existUser·p0.9999: 13.992 ms/op
                 existUser·p1.00:   15.663 ms/op

Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.719 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.736 ms/op
                 existUser·p0.99:   4.645 ms/op
                 existUser·p0.999:  8.576 ms/op
                 existUser·p0.9999: 19.344 ms/op
                 existUser·p1.00:   20.251 ms/op

Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.580 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.096 ms/op
                 existUser·p0.999:  7.313 ms/op
                 existUser·p0.9999: 19.628 ms/op
                 existUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319309
  mean =      3.006 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27580 
    [ 2.500,  5.000) = 290183 
    [ 5.000,  7.500) = 1108 
    [ 7.500, 10.000) = 193 
    [10.000, 12.500) = 13 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 93 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.303 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.727 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =     19.268 ms/op
     p(99.9990) =     19.753 ms/op
     p(99.9999) =     20.251 ms/op
    p(100.0000) =     20.251 ms/op


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
# Warmup Iteration   1: 4.662 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.007 ms/op
Iteration   1: 3.204 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.684 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.883 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  17.007 ms/op
                 getUser·p0.9999: 21.268 ms/op
                 getUser·p1.00:   25.985 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.877 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.604 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.402 ms/op
                 getUser·p0.999:  7.104 ms/op
                 getUser·p0.9999: 20.522 ms/op
                 getUser·p1.00:   21.332 ms/op

Iteration   3: 3.189 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  11.132 ms/op
                 getUser·p0.9999: 21.363 ms/op
                 getUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303070
  mean =      3.167 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8692 
    [ 2.500,  5.000) = 292318 
    [ 5.000,  7.500) = 1354 
    [ 7.500, 10.000) = 262 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 136 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =     15.855 ms/op
     p(99.9900) =     21.266 ms/op
     p(99.9990) =     21.722 ms/op
     p(99.9999) =     25.985 ms/op
    p(100.0000) =     25.985 ms/op


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
# Warmup Iteration   1: 5.048 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.011 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.448 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.645 ms/op
                 listUser·p0.95:   5.677 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  14.216 ms/op
                 listUser·p0.9999: 18.120 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.070 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  14.860 ms/op
                 listUser·p0.9999: 21.678 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.077 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.628 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  15.830 ms/op
                 listUser·p0.9999: 23.537 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 237425
  mean =      4.043 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2246 
    [ 2.500,  5.000) = 217768 
    [ 5.000,  7.500) = 15706 
    [ 7.500, 10.000) = 1124 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 118 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.612 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     14.739 ms/op
     p(99.9900) =     22.545 ms/op
     p(99.9990) =     24.465 ms/op
     p(99.9999) =     24.576 ms/op
    p(100.0000) =     24.576 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.068 ± 3.079  ops/ms
ClientGrpc.existUser                       thrpt       3  10.580 ± 1.706  ops/ms
ClientGrpc.getUser                         thrpt       3  10.154 ± 2.928  ops/ms
ClientGrpc.listUser                        thrpt       3   8.030 ± 1.854  ops/ms
ClientGrpc.createUser                       avgt       3   3.156 ± 0.090   ms/op
ClientGrpc.existUser                        avgt       3   3.041 ± 0.485   ms/op
ClientGrpc.getUser                          avgt       3   3.134 ± 0.598   ms/op
ClientGrpc.listUser                         avgt       3   3.976 ± 0.769   ms/op
ClientGrpc.createUser                     sample  302313   3.176 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.446           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.138           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.653           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.521           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.065           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.212           ms/op
ClientGrpc.existUser                      sample  319309   3.006 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.303           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.727           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.375           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.176           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.268           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.251           ms/op
ClientGrpc.getUser                        sample  303070   3.167 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.684           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.109           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.723           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          15.855           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.266           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.985           ms/op
ClientGrpc.listUser                       sample  237425   4.043 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.986           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.932           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.612           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.739           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.545           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.576           ms/op
