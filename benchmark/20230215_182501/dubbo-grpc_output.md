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
# Warmup Iteration   1: 4.374 ops/ms
# Warmup Iteration   2: 8.890 ops/ms
# Warmup Iteration   3: 10.041 ops/ms
Iteration   1: 10.077 ops/ms
Iteration   2: 10.034 ops/ms
Iteration   3: 10.084 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.065 ±(99.9%) 0.490 ops/ms [Average]
  (min, avg, max) = (10.034, 10.065, 10.084), stdev = 0.027
  CI (99.9%): [9.574, 10.555] (assumes normal distribution)


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
# Warmup Iteration   1: 7.683 ops/ms
# Warmup Iteration   2: 9.872 ops/ms
# Warmup Iteration   3: 10.154 ops/ms
Iteration   1: 10.251 ops/ms
Iteration   2: 10.244 ops/ms
Iteration   3: 10.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.347 ±(99.9%) 3.151 ops/ms [Average]
  (min, avg, max) = (10.244, 10.347, 10.546), stdev = 0.173
  CI (99.9%): [7.196, 13.498] (assumes normal distribution)


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
# Warmup Iteration   1: 6.739 ops/ms
# Warmup Iteration   2: 9.792 ops/ms
# Warmup Iteration   3: 10.159 ops/ms
Iteration   1: 10.150 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 9.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.027 ±(99.9%) 2.141 ops/ms [Average]
  (min, avg, max) = (9.916, 10.027, 10.150), stdev = 0.117
  CI (99.9%): [7.886, 12.169] (assumes normal distribution)


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
# Warmup Iteration   1: 5.704 ops/ms
# Warmup Iteration   2: 7.790 ops/ms
# Warmup Iteration   3: 7.917 ops/ms
Iteration   1: 8.056 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.033 ±(99.9%) 0.570 ops/ms [Average]
  (min, avg, max) = (7.997, 8.033, 8.056), stdev = 0.031
  CI (99.9%): [7.463, 8.603] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.275 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.300 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.196 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.002 ms/op
Iteration   2: 3.066 ±(99.9%) 0.005 ms/op
Iteration   3: 3.155 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.126 ±(99.9%) 0.944 ms/op [Average]
  (min, avg, max) = (3.066, 3.126, 3.157), stdev = 0.052
  CI (99.9%): [2.182, 4.071] (assumes normal distribution)


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
# Warmup Iteration   1: 4.178 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.097 ±(99.9%) 0.003 ms/op
Iteration   1: 2.992 ±(99.9%) 0.003 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 3.070 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.033 ±(99.9%) 0.712 ms/op [Average]
  (min, avg, max) = (2.992, 3.033, 3.070), stdev = 0.039
  CI (99.9%): [2.321, 3.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.395 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.234 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.164 ±(99.9%) 0.002 ms/op
Iteration   1: 3.204 ±(99.9%) 0.003 ms/op
Iteration   2: 3.214 ±(99.9%) 0.002 ms/op
Iteration   3: 3.215 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.211 ±(99.9%) 0.113 ms/op [Average]
  (min, avg, max) = (3.204, 3.211, 3.215), stdev = 0.006
  CI (99.9%): [3.098, 3.324] (assumes normal distribution)


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
# Warmup Iteration   1: 5.014 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.017 ms/op
Iteration   1: 3.961 ±(99.9%) 0.013 ms/op
Iteration   2: 4.030 ±(99.9%) 0.011 ms/op
Iteration   3: 4.038 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.010 ±(99.9%) 0.773 ms/op [Average]
  (min, avg, max) = (3.961, 4.010, 4.038), stdev = 0.042
  CI (99.9%): [3.237, 4.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.334 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.008 ms/op
Iteration   1: 3.040 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.589 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  7.763 ms/op
                 createUser·p0.9999: 19.988 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.613 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.743 ms/op
                 createUser·p0.999:  7.695 ms/op
                 createUser·p0.9999: 21.234 ms/op
                 createUser·p1.00:   21.594 ms/op

Iteration   3: 3.149 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.055 ms/op
                 createUser·p0.99:   4.448 ms/op
                 createUser·p0.999:  10.273 ms/op
                 createUser·p0.9999: 22.970 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309047
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26299 
    [ 2.500,  5.000) = 281111 
    [ 5.000,  7.500) = 1285 
    [ 7.500, 10.000) = 103 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 104 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.589 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.233 ms/op
     p(99.9900) =     21.830 ms/op
     p(99.9990) =     23.319 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


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
# Warmup Iteration   1: 3.885 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.751 ms/op
                 existUser·p0.999:  8.213 ms/op
                 existUser·p0.9999: 13.032 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 3.034 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.849 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.290 ms/op
                 existUser·p0.9999: 18.838 ms/op
                 existUser·p1.00:   19.333 ms/op

Iteration   3: 3.039 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.647 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.731 ms/op
                 existUser·p0.95:   3.940 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.772 ms/op
                 existUser·p0.9999: 15.582 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316620
  mean =      3.032 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1172 
    [ 1.250,  2.500) = 40381 
    [ 2.500,  3.750) = 246629 
    [ 3.750,  5.000) = 26726 
    [ 5.000,  6.250) = 931 
    [ 6.250,  7.500) = 418 
    [ 7.500,  8.750) = 139 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      3.002 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     16.930 ms/op
     p(99.9990) =     19.224 ms/op
     p(99.9999) =     19.333 ms/op
    p(100.0000) =     19.333 ms/op


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.007 ms/op
Iteration   1: 3.292 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.219 ms/op
                 getUser·p0.90:   4.047 ms/op
                 getUser·p0.95:   4.325 ms/op
                 getUser·p0.99:   5.554 ms/op
                 getUser·p0.999:  10.915 ms/op
                 getUser·p0.9999: 16.454 ms/op
                 getUser·p1.00:   16.744 ms/op

Iteration   2: 3.227 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.586 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.867 ms/op
                 getUser·p0.95:   4.076 ms/op
                 getUser·p0.99:   4.737 ms/op
                 getUser·p0.999:  7.421 ms/op
                 getUser·p0.9999: 18.320 ms/op
                 getUser·p1.00:   18.579 ms/op

Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.275 ms/op
                 getUser·p0.50:   3.162 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.182 ms/op
                 getUser·p0.99:   4.981 ms/op
                 getUser·p0.999:  8.373 ms/op
                 getUser·p0.9999: 19.958 ms/op
                 getUser·p1.00:   20.021 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 295581
  mean =      3.248 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16406 
    [ 2.500,  5.000) = 275805 
    [ 5.000,  7.500) = 2824 
    [ 7.500, 10.000) = 313 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 8 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.275 ms/op
     p(50.0000) =      3.191 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.194 ms/op
     p(99.0000) =      5.136 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     19.988 ms/op
     p(99.9999) =     20.021 ms/op
    p(100.0000) =     20.021 ms/op


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
# Warmup Iteration   1: 5.396 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.273 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.011 ms/op
Iteration   1: 4.084 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 17.322 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   2: 4.035 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  16.995 ms/op
                 listUser·p0.9999: 21.008 ms/op
                 listUser·p1.00:   21.332 ms/op

Iteration   3: 3.976 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.713 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.053 ms/op
                 listUser·p0.999:  15.980 ms/op
                 listUser·p0.9999: 23.881 ms/op
                 listUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238490
  mean =      4.031 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3188 
    [ 2.500,  5.000) = 204570 
    [ 5.000,  7.500) = 28884 
    [ 7.500, 10.000) = 1243 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 205 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.713 ms/op
     p(50.0000) =      3.826 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.956 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     22.811 ms/op
     p(99.9990) =     24.100 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.065 ± 0.490  ops/ms
ClientGrpc.existUser                       thrpt       3  10.347 ± 3.151  ops/ms
ClientGrpc.getUser                         thrpt       3  10.027 ± 2.141  ops/ms
ClientGrpc.listUser                        thrpt       3   8.033 ± 0.570  ops/ms
ClientGrpc.createUser                       avgt       3   3.126 ± 0.944   ms/op
ClientGrpc.existUser                        avgt       3   3.033 ± 0.712   ms/op
ClientGrpc.getUser                          avgt       3   3.211 ± 0.113   ms/op
ClientGrpc.listUser                         avgt       3   4.010 ± 0.773   ms/op
ClientGrpc.createUser                     sample  309047   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.589           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.088           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.977           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.233           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.830           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  316620   3.032 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.647           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.002           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.715           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.538           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.889           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.930           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.333           ms/op
ClientGrpc.getUser                        sample  295581   3.248 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.275           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.191           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.569           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.431           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.021           ms/op
ClientGrpc.listUser                       sample  238490   4.031 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.713           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.826           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.267           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.234           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.811           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.183           ms/op
