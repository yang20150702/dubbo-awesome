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
# Warmup Iteration   1: 3.798 ops/ms
# Warmup Iteration   2: 8.660 ops/ms
# Warmup Iteration   3: 9.520 ops/ms
Iteration   1: 9.991 ops/ms
Iteration   2: 10.198 ops/ms
Iteration   3: 10.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.166 ±(99.9%) 2.927 ops/ms [Average]
  (min, avg, max) = (9.991, 10.166, 10.307), stdev = 0.160
  CI (99.9%): [7.239, 13.092] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.174 ops/ms
# Warmup Iteration   2: 9.967 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.463 ops/ms
Iteration   2: 10.441 ops/ms
Iteration   3: 10.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.449 ±(99.9%) 0.231 ops/ms [Average]
  (min, avg, max) = (10.441, 10.449, 10.463), stdev = 0.013
  CI (99.9%): [10.217, 10.680] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.740 ops/ms
# Warmup Iteration   2: 9.643 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 9.683 ops/ms
Iteration   2: 9.968 ops/ms
Iteration   3: 9.948 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.866 ±(99.9%) 2.905 ops/ms [Average]
  (min, avg, max) = (9.683, 9.866, 9.968), stdev = 0.159
  CI (99.9%): [6.961, 12.771] (assumes normal distribution)


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
# Warmup Iteration   1: 5.406 ops/ms
# Warmup Iteration   2: 7.184 ops/ms
# Warmup Iteration   3: 7.681 ops/ms
Iteration   1: 7.610 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 7.526 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.733 ±(99.9%) 5.263 ops/ms [Average]
  (min, avg, max) = (7.526, 7.733, 8.063), stdev = 0.288
  CI (99.9%): [2.470, 12.996] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.510 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.255 ±(99.9%) 0.002 ms/op
Iteration   1: 3.284 ±(99.9%) 0.002 ms/op
Iteration   2: 3.243 ±(99.9%) 0.002 ms/op
Iteration   3: 3.331 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.286 ±(99.9%) 0.801 ms/op [Average]
  (min, avg, max) = (3.243, 3.286, 3.331), stdev = 0.044
  CI (99.9%): [2.485, 4.087] (assumes normal distribution)


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
# Warmup Iteration   1: 4.327 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.251 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.148 ±(99.9%) 0.002 ms/op
Iteration   1: 3.074 ±(99.9%) 0.002 ms/op
Iteration   2: 3.076 ±(99.9%) 0.002 ms/op
Iteration   3: 3.120 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.090 ±(99.9%) 0.479 ms/op [Average]
  (min, avg, max) = (3.074, 3.090, 3.120), stdev = 0.026
  CI (99.9%): [2.611, 3.568] (assumes normal distribution)


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
# Warmup Iteration   1: 4.464 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.286 ±(99.9%) 0.002 ms/op
Iteration   1: 3.143 ±(99.9%) 0.003 ms/op
Iteration   2: 3.189 ±(99.9%) 0.002 ms/op
Iteration   3: 3.252 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.195 ±(99.9%) 0.995 ms/op [Average]
  (min, avg, max) = (3.143, 3.195, 3.252), stdev = 0.055
  CI (99.9%): [2.200, 4.190] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 6.278 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.438 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.008 ms/op
Iteration   1: 4.279 ±(99.9%) 0.021 ms/op
Iteration   2: 4.298 ±(99.9%) 0.016 ms/op
Iteration   3: 4.194 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.257 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (4.194, 4.257, 4.298), stdev = 0.055
  CI (99.9%): [3.249, 5.265] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.400 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.270 ±(99.9%) 0.008 ms/op
Iteration   1: 3.300 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.031 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   4.026 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   4.678 ms/op
                 createUser·p0.999:  7.948 ms/op
                 createUser·p0.9999: 14.552 ms/op
                 createUser·p1.00:   15.385 ms/op

Iteration   2: 3.217 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.725 ms/op
                 createUser·p0.9999: 14.829 ms/op
                 createUser·p1.00:   15.139 ms/op

Iteration   3: 3.179 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.803 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.043 ms/op
                 createUser·p0.99:   4.547 ms/op
                 createUser·p0.999:  8.801 ms/op
                 createUser·p0.9999: 17.922 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 296886
  mean =      3.231 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 442 
    [ 1.250,  2.500) = 16885 
    [ 2.500,  3.750) = 232935 
    [ 3.750,  5.000) = 44894 
    [ 5.000,  6.250) = 873 
    [ 6.250,  7.500) = 419 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 4 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 91 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.803 ms/op
     p(50.0000) =      3.199 ms/op
     p(90.0000) =      3.916 ms/op
     p(95.0000) =      4.133 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.177 ms/op
     p(99.9900) =     17.125 ms/op
     p(99.9990) =     18.384 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 3.977 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.078 ±(99.9%) 0.007 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.707 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.908 ms/op
                 existUser·p0.95:   4.129 ms/op
                 existUser·p0.99:   4.701 ms/op
                 existUser·p0.999:  7.353 ms/op
                 existUser·p0.9999: 15.684 ms/op
                 existUser·p1.00:   16.302 ms/op

Iteration   2: 3.147 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.891 ms/op
                 existUser·p0.95:   4.071 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  7.866 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.743 ms/op

Iteration   3: 3.140 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   3.109 ms/op
                 existUser·p0.90:   3.801 ms/op
                 existUser·p0.95:   4.002 ms/op
                 existUser·p0.99:   4.440 ms/op
                 existUser·p0.999:  8.204 ms/op
                 existUser·p0.9999: 18.432 ms/op
                 existUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 304889
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 718 
    [ 1.250,  2.500) = 26494 
    [ 2.500,  3.750) = 235627 
    [ 3.750,  5.000) = 40349 
    [ 5.000,  6.250) = 902 
    [ 6.250,  7.500) = 440 
    [ 7.500,  8.750) = 122 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.707 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.067 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.931 ms/op
     p(99.9900) =     17.908 ms/op
     p(99.9990) =     19.197 ms/op
     p(99.9999) =     19.661 ms/op
    p(100.0000) =     19.661 ms/op


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
# Warmup Iteration   1: 4.761 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.311 ±(99.9%) 0.007 ms/op
Iteration   1: 3.229 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.866 ms/op
                 getUser·p0.50:   3.203 ms/op
                 getUser·p0.90:   3.895 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.579 ms/op
                 getUser·p0.999:  7.545 ms/op
                 getUser·p0.9999: 13.926 ms/op
                 getUser·p1.00:   14.172 ms/op

Iteration   2: 3.226 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  10.732 ms/op
                 getUser·p0.9999: 19.499 ms/op
                 getUser·p1.00:   21.529 ms/op

Iteration   3: 3.195 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.799 ms/op
                 getUser·p0.50:   3.170 ms/op
                 getUser·p0.90:   3.854 ms/op
                 getUser·p0.95:   4.047 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  7.021 ms/op
                 getUser·p0.9999: 17.694 ms/op
                 getUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298568
  mean =      3.216 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17578 
    [ 2.500,  5.000) = 279231 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 258 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      4.606 ms/op
     p(99.9000) =      8.403 ms/op
     p(99.9900) =     18.617 ms/op
     p(99.9990) =     21.074 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


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
# Warmup Iteration   1: 5.549 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.358 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.269 ±(99.9%) 0.012 ms/op
Iteration   1: 4.261 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.305 ms/op
                 listUser·p0.50:   4.067 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  14.867 ms/op
                 listUser·p0.9999: 22.248 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   2: 4.130 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.993 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  17.014 ms/op
                 listUser·p0.9999: 25.535 ms/op
                 listUser·p1.00:   26.018 ms/op

Iteration   3: 4.184 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.190 ms/op
                 listUser·p0.50:   3.998 ms/op
                 listUser·p0.90:   5.251 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.189 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 19.576 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 229076
  mean =      4.191 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1345 
    [ 2.500,  5.000) = 197148 
    [ 5.000,  7.500) = 28798 
    [ 7.500, 10.000) = 1304 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.993 ms/op
     p(50.0000) =      4.010 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      7.266 ms/op
     p(99.9000) =     16.810 ms/op
     p(99.9900) =     24.588 ms/op
     p(99.9990) =     25.900 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.166 ± 2.927  ops/ms
ClientGrpc.existUser                       thrpt       3  10.449 ± 0.231  ops/ms
ClientGrpc.getUser                         thrpt       3   9.866 ± 2.905  ops/ms
ClientGrpc.listUser                        thrpt       3   7.733 ± 5.263  ops/ms
ClientGrpc.createUser                       avgt       3   3.286 ± 0.801   ms/op
ClientGrpc.existUser                        avgt       3   3.090 ± 0.479   ms/op
ClientGrpc.getUser                          avgt       3   3.195 ± 0.995   ms/op
ClientGrpc.listUser                         avgt       3   4.257 ± 1.008   ms/op
ClientGrpc.createUser                     sample  296886   3.231 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.803           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.199           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.916           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.133           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.628           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.177           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.125           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.481           ms/op
ClientGrpc.existUser                      sample  304889   3.147 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.707           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.105           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.931           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.661           ms/op
ClientGrpc.getUser                        sample  298568   3.216 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.191           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.084           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.606           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.403           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.617           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.529           ms/op
ClientGrpc.listUser                       sample  229076   4.191 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.993           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.010           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.317           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.997           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.266           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.810           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.588           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.018           ms/op
