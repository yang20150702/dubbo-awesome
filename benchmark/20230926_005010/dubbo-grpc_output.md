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
# Warmup Iteration   1: 3.683 ops/ms
# Warmup Iteration   2: 8.081 ops/ms
# Warmup Iteration   3: 9.522 ops/ms
Iteration   1: 9.782 ops/ms
Iteration   2: 10.168 ops/ms
Iteration   3: 10.230 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.060 ±(99.9%) 4.426 ops/ms [Average]
  (min, avg, max) = (9.782, 10.060, 10.230), stdev = 0.243
  CI (99.9%): [5.634, 14.485] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.748 ops/ms
# Warmup Iteration   2: 9.770 ops/ms
# Warmup Iteration   3: 10.614 ops/ms
Iteration   1: 10.329 ops/ms
Iteration   2: 10.796 ops/ms
Iteration   3: 10.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.526 ±(99.9%) 4.413 ops/ms [Average]
  (min, avg, max) = (10.329, 10.526, 10.796), stdev = 0.242
  CI (99.9%): [6.113, 14.938] (assumes normal distribution)


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
# Warmup Iteration   1: 6.568 ops/ms
# Warmup Iteration   2: 9.526 ops/ms
# Warmup Iteration   3: 9.811 ops/ms
Iteration   1: 9.924 ops/ms
Iteration   2: 10.020 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.004 ±(99.9%) 1.352 ops/ms [Average]
  (min, avg, max) = (9.924, 10.004, 10.070), stdev = 0.074
  CI (99.9%): [8.653, 11.356] (assumes normal distribution)


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
# Warmup Iteration   1: 5.144 ops/ms
# Warmup Iteration   2: 7.593 ops/ms
# Warmup Iteration   3: 7.907 ops/ms
Iteration   1: 7.877 ops/ms
Iteration   2: 7.875 ops/ms
Iteration   3: 8.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.926 ±(99.9%) 1.586 ops/ms [Average]
  (min, avg, max) = (7.875, 7.926, 8.026), stdev = 0.087
  CI (99.9%): [6.340, 9.512] (assumes normal distribution)


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
# Warmup Iteration   1: 4.697 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.308 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.002 ms/op
Iteration   1: 3.177 ±(99.9%) 0.002 ms/op
Iteration   2: 3.184 ±(99.9%) 0.002 ms/op
Iteration   3: 3.219 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.193 ±(99.9%) 0.414 ms/op [Average]
  (min, avg, max) = (3.177, 3.193, 3.219), stdev = 0.023
  CI (99.9%): [2.780, 3.607] (assumes normal distribution)


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
# Warmup Iteration   1: 4.456 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.002 ms/op
Iteration   1: 3.101 ±(99.9%) 0.002 ms/op
Iteration   2: 3.105 ±(99.9%) 0.001 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.103 ±(99.9%) 0.035 ms/op [Average]
  (min, avg, max) = (3.101, 3.103, 3.105), stdev = 0.002
  CI (99.9%): [3.068, 3.138] (assumes normal distribution)


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
# Warmup Iteration   1: 4.603 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.003 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.128 ±(99.9%) 0.002 ms/op
Iteration   3: 3.218 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.172 ±(99.9%) 0.824 ms/op [Average]
  (min, avg, max) = (3.128, 3.172, 3.218), stdev = 0.045
  CI (99.9%): [2.348, 3.996] (assumes normal distribution)


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
# Warmup Iteration   1: 5.777 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.230 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.072 ±(99.9%) 0.019 ms/op
Iteration   1: 4.033 ±(99.9%) 0.034 ms/op
Iteration   2: 3.897 ±(99.9%) 0.005 ms/op
Iteration   3: 4.004 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.978 ±(99.9%) 1.304 ms/op [Average]
  (min, avg, max) = (3.897, 3.978, 4.033), stdev = 0.071
  CI (99.9%): [2.674, 5.282] (assumes normal distribution)


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
# Warmup Iteration   1: 4.432 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.312 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.007 ms/op
Iteration   1: 3.244 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.929 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.051 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  7.545 ms/op
                 createUser·p0.9999: 13.603 ms/op
                 createUser·p1.00:   14.041 ms/op

Iteration   2: 3.175 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.020 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.342 ms/op
                 createUser·p0.999:  8.057 ms/op
                 createUser·p0.9999: 15.218 ms/op
                 createUser·p1.00:   16.073 ms/op

Iteration   3: 3.133 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.816 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.628 ms/op
                 createUser·p0.9999: 16.757 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301503
  mean =      3.183 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 124 
    [ 1.250,  2.500) = 7636 
    [ 2.500,  3.750) = 261789 
    [ 3.750,  5.000) = 30492 
    [ 5.000,  6.250) = 760 
    [ 6.250,  7.500) = 296 
    [ 7.500,  8.750) = 146 
    [ 8.750, 10.000) = 14 
    [10.000, 11.250) = 54 
    [11.250, 12.500) = 15 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 55 
    [15.000, 16.250) = 34 
    [16.250, 17.500) = 37 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      3.969 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      8.155 ms/op
     p(99.9900) =     16.379 ms/op
     p(99.9990) =     16.908 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 4.335 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.196 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.006 ms/op
Iteration   1: 3.060 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.836 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.633 ms/op
                 existUser·p0.95:   3.838 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  7.950 ms/op
                 existUser·p0.9999: 12.395 ms/op
                 existUser·p1.00:   12.698 ms/op

Iteration   2: 3.086 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.862 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.682 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   4.325 ms/op
                 existUser·p0.999:  9.247 ms/op
                 existUser·p0.9999: 22.193 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 3.076 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.760 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  5.874 ms/op
                 existUser·p0.9999: 15.929 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 312078
  mean =      3.074 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14125 
    [ 2.500,  5.000) = 296601 
    [ 5.000,  7.500) = 976 
    [ 7.500, 10.000) = 221 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.760 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.858 ms/op
     p(99.0000) =      4.325 ms/op
     p(99.9000) =      7.863 ms/op
     p(99.9900) =     21.548 ms/op
     p(99.9990) =     22.540 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.662 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.363 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.276 ±(99.9%) 0.006 ms/op
Iteration   1: 3.193 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.890 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.469 ms/op
                 getUser·p0.999:  13.007 ms/op
                 getUser·p0.9999: 16.580 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   2: 3.196 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.621 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   3.936 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.691 ms/op
                 getUser·p0.9999: 15.188 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   3: 3.234 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  7.782 ms/op
                 getUser·p0.9999: 19.137 ms/op
                 getUser·p1.00:   19.628 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 299280
  mean =      3.208 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 5500 
    [ 2.500,  3.750) = 258463 
    [ 3.750,  5.000) = 33311 
    [ 5.000,  6.250) = 797 
    [ 6.250,  7.500) = 633 
    [ 7.500,  8.750) = 143 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.621 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.155 ms/op
     p(99.9900) =     18.619 ms/op
     p(99.9990) =     19.400 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 5.766 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.184 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.037 ±(99.9%) 0.010 ms/op
Iteration   1: 4.011 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.993 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.186 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  14.259 ms/op
                 listUser·p0.9999: 16.663 ms/op
                 listUser·p1.00:   17.072 ms/op

Iteration   2: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.784 ms/op
                 listUser·p0.99:   6.853 ms/op
                 listUser·p0.999:  14.139 ms/op
                 listUser·p0.9999: 16.284 ms/op
                 listUser·p1.00:   16.597 ms/op

Iteration   3: 4.006 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.046 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.481 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  15.116 ms/op
                 listUser·p0.9999: 16.696 ms/op
                 listUser·p1.00:   18.088 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240298
  mean =      3.993 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 973 
    [ 2.500,  3.750) = 83201 
    [ 3.750,  5.000) = 143934 
    [ 5.000,  6.250) = 6625 
    [ 6.250,  7.500) = 4165 
    [ 7.500,  8.750) = 688 
    [ 8.750, 10.000) = 187 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 67 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 110 
    [15.000, 16.250) = 128 
    [16.250, 17.500) = 57 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.046 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.022 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.233 ms/op
     p(99.9900) =     16.564 ms/op
     p(99.9990) =     17.295 ms/op
     p(99.9999) =     18.088 ms/op
    p(100.0000) =     18.088 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.060 ± 4.426  ops/ms
ClientGrpc.existUser                       thrpt       3  10.526 ± 4.413  ops/ms
ClientGrpc.getUser                         thrpt       3  10.004 ± 1.352  ops/ms
ClientGrpc.listUser                        thrpt       3   7.926 ± 1.586  ops/ms
ClientGrpc.createUser                       avgt       3   3.193 ± 0.414   ms/op
ClientGrpc.existUser                        avgt       3   3.103 ± 0.035   ms/op
ClientGrpc.getUser                          avgt       3   3.172 ± 0.824   ms/op
ClientGrpc.listUser                         avgt       3   3.978 ± 1.304   ms/op
ClientGrpc.createUser                     sample  301503   3.183 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.816           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.768           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.969           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.155           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.379           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.974           ms/op
ClientGrpc.existUser                      sample  312078   3.074 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.760           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.015           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.858           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.325           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.863           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.548           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.643           ms/op
ClientGrpc.getUser                        sample  299280   3.208 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.621           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.146           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.155           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.619           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  240298   3.993 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.046           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.908           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.022           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.233           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          16.564           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          18.088           ms/op
