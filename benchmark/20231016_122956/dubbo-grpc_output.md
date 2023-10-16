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
# Warmup Iteration   1: 4.536 ops/ms
# Warmup Iteration   2: 9.212 ops/ms
# Warmup Iteration   3: 9.844 ops/ms
Iteration   1: 9.986 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.149 ±(99.9%) 2.769 ops/ms [Average]
  (min, avg, max) = (9.986, 10.149, 10.286), stdev = 0.152
  CI (99.9%): [7.381, 12.918] (assumes normal distribution)


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
# Warmup Iteration   1: 7.525 ops/ms
# Warmup Iteration   2: 10.416 ops/ms
# Warmup Iteration   3: 10.716 ops/ms
Iteration   1: 10.748 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.813 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.727 ±(99.9%) 1.787 ops/ms [Average]
  (min, avg, max) = (10.621, 10.727, 10.813), stdev = 0.098
  CI (99.9%): [8.940, 12.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.760 ops/ms
# Warmup Iteration   2: 9.701 ops/ms
# Warmup Iteration   3: 10.126 ops/ms
Iteration   1: 10.394 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 10.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.346 ±(99.9%) 1.103 ops/ms [Average]
  (min, avg, max) = (10.278, 10.346, 10.394), stdev = 0.060
  CI (99.9%): [9.243, 11.449] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.613 ops/ms
# Warmup Iteration   2: 7.868 ops/ms
# Warmup Iteration   3: 8.042 ops/ms
Iteration   1: 8.188 ops/ms
Iteration   2: 8.244 ops/ms
Iteration   3: 8.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.194 ±(99.9%) 0.863 ops/ms [Average]
  (min, avg, max) = (8.150, 8.194, 8.244), stdev = 0.047
  CI (99.9%): [7.331, 9.057] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.156 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.198 ±(99.9%) 0.010 ms/op
Iteration   1: 3.150 ±(99.9%) 0.003 ms/op
Iteration   2: 3.162 ±(99.9%) 0.003 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.147 ±(99.9%) 0.301 ms/op [Average]
  (min, avg, max) = (3.129, 3.147, 3.162), stdev = 0.016
  CI (99.9%): [2.846, 3.448] (assumes normal distribution)


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
# Warmup Iteration   1: 3.998 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.113 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.072 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.005 ms/op
Iteration   2: 2.869 ±(99.9%) 0.004 ms/op
Iteration   3: 3.000 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.966 ±(99.9%) 1.547 ms/op [Average]
  (min, avg, max) = (2.869, 2.966, 3.028), stdev = 0.085
  CI (99.9%): [1.418, 4.513] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.005 ms/op
Iteration   1: 3.184 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.003 ms/op
Iteration   3: 3.130 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.168 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.130, 3.168, 3.189), stdev = 0.033
  CI (99.9%): [2.573, 3.763] (assumes normal distribution)


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.976 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.024 ms/op
Iteration   1: 3.874 ±(99.9%) 0.036 ms/op
Iteration   2: 3.918 ±(99.9%) 0.031 ms/op
Iteration   3: 3.952 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 0.710 ms/op [Average]
  (min, avg, max) = (3.874, 3.915, 3.952), stdev = 0.039
  CI (99.9%): [3.204, 4.625] (assumes normal distribution)


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
# Warmup Iteration   1: 4.377 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.296 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.810 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.736 ms/op
                 createUser·p0.95:   3.920 ms/op
                 createUser·p0.99:   4.481 ms/op
                 createUser·p0.999:  9.447 ms/op
                 createUser·p0.9999: 19.235 ms/op
                 createUser·p1.00:   22.610 ms/op

Iteration   2: 3.147 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.768 ms/op
                 createUser·p0.999:  16.987 ms/op
                 createUser·p0.9999: 25.514 ms/op
                 createUser·p1.00:   28.377 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.554 ms/op
                 createUser·p0.50:   3.150 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.780 ms/op
                 createUser·p0.9999: 21.191 ms/op
                 createUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304208
  mean =      3.157 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12245 
    [ 2.500,  5.000) = 289977 
    [ 5.000,  7.500) = 1327 
    [ 7.500, 10.000) = 298 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.711 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     24.740 ms/op
     p(99.9990) =     28.176 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 3.788 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.025 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.617 ms/op
                 existUser·p0.95:   3.822 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.135 ms/op
                 existUser·p0.9999: 14.734 ms/op
                 existUser·p1.00:   15.172 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.539 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.581 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  12.861 ms/op
                 existUser·p0.9999: 18.686 ms/op
                 existUser·p1.00:   19.956 ms/op

Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.662 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.686 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.912 ms/op
                 existUser·p0.9999: 18.021 ms/op
                 existUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318463
  mean =      3.014 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1345 
    [ 1.250,  2.500) = 18389 
    [ 2.500,  3.750) = 283401 
    [ 3.750,  5.000) = 13744 
    [ 5.000,  6.250) = 810 
    [ 6.250,  7.500) = 333 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 58 
    [11.250, 12.500) = 61 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 51 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.523 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     18.934 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.121 ±(99.9%) 0.007 ms/op
Iteration   1: 3.152 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.641 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.928 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.960 ms/op
                 getUser·p0.9999: 23.686 ms/op
                 getUser·p1.00:   25.035 ms/op

Iteration   2: 3.165 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.880 ms/op
                 getUser·p0.9999: 16.694 ms/op
                 getUser·p1.00:   17.203 ms/op

Iteration   3: 3.065 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.724 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.686 ms/op
                 getUser·p0.999:  9.273 ms/op
                 getUser·p0.9999: 16.876 ms/op
                 getUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306906
  mean =      3.127 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15736 
    [ 2.500,  5.000) = 289417 
    [ 5.000,  7.500) = 1241 
    [ 7.500, 10.000) = 180 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 142 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.641 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.579 ms/op
     p(99.9000) =     10.831 ms/op
     p(99.9900) =     17.105 ms/op
     p(99.9990) =     24.408 ms/op
     p(99.9999) =     25.035 ms/op
    p(100.0000) =     25.035 ms/op


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.009 ms/op
Iteration   1: 3.940 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.053 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.423 ms/op
                 listUser·p0.99:   6.652 ms/op
                 listUser·p0.999:  12.182 ms/op
                 listUser·p0.9999: 16.691 ms/op
                 listUser·p1.00:   16.876 ms/op

Iteration   2: 3.902 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.083 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  13.335 ms/op
                 listUser·p0.9999: 24.569 ms/op
                 listUser·p1.00:   24.871 ms/op

Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.110 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  14.819 ms/op
                 listUser·p0.9999: 19.149 ms/op
                 listUser·p1.00:   19.759 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 244869
  mean =      3.921 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3502 
    [ 2.500,  5.000) = 226449 
    [ 5.000,  7.500) = 13842 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.053 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      6.652 ms/op
     p(99.9000) =     13.175 ms/op
     p(99.9900) =     19.237 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.149 ± 2.769  ops/ms
ClientGrpc.existUser                       thrpt       3  10.727 ± 1.787  ops/ms
ClientGrpc.getUser                         thrpt       3  10.346 ± 1.103  ops/ms
ClientGrpc.listUser                        thrpt       3   8.194 ± 0.863  ops/ms
ClientGrpc.createUser                       avgt       3   3.147 ± 0.301   ms/op
ClientGrpc.existUser                        avgt       3   2.966 ± 1.547   ms/op
ClientGrpc.getUser                          avgt       3   3.168 ± 0.595   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 0.710   ms/op
ClientGrpc.createUser                     sample  304208   3.157 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.554           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.740           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.377           ms/op
ClientGrpc.existUser                      sample  318463   3.014 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.539           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.489           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.092           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.990           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  306906   3.127 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.641           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.101           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.662           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.858           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.579           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.831           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.105           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.035           ms/op
ClientGrpc.listUser                       sample  244869   3.921 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.053           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.407           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.308           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.652           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.175           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.237           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.871           ms/op
