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
# Warmup Iteration   1: 4.416 ops/ms
# Warmup Iteration   2: 9.114 ops/ms
# Warmup Iteration   3: 9.897 ops/ms
Iteration   1: 9.608 ops/ms
Iteration   2: 9.786 ops/ms
Iteration   3: 10.135 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.843 ±(99.9%) 4.888 ops/ms [Average]
  (min, avg, max) = (9.608, 9.843, 10.135), stdev = 0.268
  CI (99.9%): [4.955, 14.731] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.719 ops/ms
# Warmup Iteration   2: 10.172 ops/ms
# Warmup Iteration   3: 10.335 ops/ms
Iteration   1: 10.474 ops/ms
Iteration   2: 10.607 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.546 ±(99.9%) 1.223 ops/ms [Average]
  (min, avg, max) = (10.474, 10.546, 10.607), stdev = 0.067
  CI (99.9%): [9.323, 11.770] (assumes normal distribution)


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
# Warmup Iteration   1: 6.661 ops/ms
# Warmup Iteration   2: 9.616 ops/ms
# Warmup Iteration   3: 9.937 ops/ms
Iteration   1: 10.064 ops/ms
Iteration   2: 10.124 ops/ms
Iteration   3: 10.120 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.103 ±(99.9%) 0.610 ops/ms [Average]
  (min, avg, max) = (10.064, 10.103, 10.124), stdev = 0.033
  CI (99.9%): [9.493, 10.713] (assumes normal distribution)


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
# Warmup Iteration   1: 5.428 ops/ms
# Warmup Iteration   2: 6.964 ops/ms
# Warmup Iteration   3: 7.666 ops/ms
Iteration   1: 7.782 ops/ms
Iteration   2: 7.828 ops/ms
Iteration   3: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.868 ±(99.9%) 2.043 ops/ms [Average]
  (min, avg, max) = (7.782, 7.868, 7.995), stdev = 0.112
  CI (99.9%): [5.825, 9.911] (assumes normal distribution)


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
# Warmup Iteration   1: 4.426 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.001 ms/op
Iteration   1: 3.215 ±(99.9%) 0.009 ms/op
Iteration   2: 3.167 ±(99.9%) 0.002 ms/op
Iteration   3: 3.288 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.223 ±(99.9%) 1.116 ms/op [Average]
  (min, avg, max) = (3.167, 3.223, 3.288), stdev = 0.061
  CI (99.9%): [2.108, 4.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.198 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.005 ms/op
Iteration   1: 3.138 ±(99.9%) 0.001 ms/op
Iteration   2: 3.090 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.101 ±(99.9%) 0.602 ms/op [Average]
  (min, avg, max) = (3.075, 3.101, 3.138), stdev = 0.033
  CI (99.9%): [2.499, 3.703] (assumes normal distribution)


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
# Warmup Iteration   1: 4.199 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.002 ms/op
Iteration   1: 3.183 ±(99.9%) 0.002 ms/op
Iteration   2: 3.204 ±(99.9%) 0.002 ms/op
Iteration   3: 3.210 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.199 ±(99.9%) 0.258 ms/op [Average]
  (min, avg, max) = (3.183, 3.199, 3.210), stdev = 0.014
  CI (99.9%): [2.941, 3.457] (assumes normal distribution)


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
# Warmup Iteration   1: 5.354 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.201 ±(99.9%) 0.017 ms/op
Iteration   1: 4.048 ±(99.9%) 0.011 ms/op
Iteration   2: 3.982 ±(99.9%) 0.023 ms/op
Iteration   3: 4.031 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.020 ±(99.9%) 0.618 ms/op [Average]
  (min, avg, max) = (3.982, 4.020, 4.048), stdev = 0.034
  CI (99.9%): [3.403, 4.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.384 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
Iteration   1: 3.247 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.219 ms/op
                 createUser·p0.90:   3.957 ms/op
                 createUser·p0.95:   4.149 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  8.371 ms/op
                 createUser·p0.9999: 19.207 ms/op
                 createUser·p1.00:   19.792 ms/op

Iteration   2: 3.229 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.191 ms/op
                 createUser·p0.90:   3.895 ms/op
                 createUser·p0.95:   4.063 ms/op
                 createUser·p0.99:   4.465 ms/op
                 createUser·p0.999:  11.026 ms/op
                 createUser·p0.9999: 14.601 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 3.203 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.680 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.875 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  7.417 ms/op
                 createUser·p0.9999: 16.879 ms/op
                 createUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297368
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 603 
    [ 1.250,  2.500) = 15445 
    [ 2.500,  3.750) = 234175 
    [ 3.750,  5.000) = 45930 
    [ 5.000,  6.250) = 614 
    [ 6.250,  7.500) = 213 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.680 ms/op
     p(50.0000) =      3.195 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      9.894 ms/op
     p(99.9900) =     17.777 ms/op
     p(99.9990) =     19.631 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.922 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.130 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
Iteration   1: 3.018 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.847 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.756 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  7.127 ms/op
                 existUser·p0.9999: 11.784 ms/op
                 existUser·p1.00:   12.419 ms/op

Iteration   2: 3.049 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.885 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.965 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  6.589 ms/op
                 existUser·p0.9999: 22.283 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   3: 3.048 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.809 ms/op
                 existUser·p0.99:   4.190 ms/op
                 existUser·p0.999:  5.448 ms/op
                 existUser·p0.9999: 18.416 ms/op
                 existUser·p1.00:   18.678 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315899
  mean =      3.038 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33149 
    [ 2.500,  5.000) = 281785 
    [ 5.000,  7.500) = 776 
    [ 7.500, 10.000) = 36 
    [10.000, 12.500) = 57 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      3.019 ms/op
     p(90.0000) =      3.645 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      6.504 ms/op
     p(99.9900) =     21.365 ms/op
     p(99.9990) =     22.632 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.391 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.791 ms/op
                 getUser·p0.50:   3.142 ms/op
                 getUser·p0.90:   3.871 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.587 ms/op
                 getUser·p0.9999: 16.269 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  6.171 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   24.871 ms/op

Iteration   3: 3.223 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.809 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.928 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  9.675 ms/op
                 getUser·p0.9999: 22.549 ms/op
                 getUser·p1.00:   23.003 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300976
  mean =      3.189 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18805 
    [ 2.500,  5.000) = 281386 
    [ 5.000,  7.500) = 561 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.158 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.047 ms/op
     p(99.0000) =      4.393 ms/op
     p(99.9000) =      6.767 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     24.838 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 5.747 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.175 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.012 ms/op
Iteration   1: 4.196 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.274 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.374 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  13.140 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   15.909 ms/op

Iteration   2: 4.094 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.239 ms/op
                 listUser·p0.50:   3.908 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   7.414 ms/op
                 listUser·p0.999:  15.298 ms/op
                 listUser·p0.9999: 22.413 ms/op
                 listUser·p1.00:   22.708 ms/op

Iteration   3: 4.076 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.155 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.210 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.016 ms/op
                 listUser·p0.999:  16.034 ms/op
                 listUser·p0.9999: 24.725 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233110
  mean =      4.121 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2949 
    [ 2.500,  5.000) = 197846 
    [ 5.000,  7.500) = 30483 
    [ 7.500, 10.000) = 1333 
    [10.000, 12.500) = 161 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.250 ms/op
     p(99.9000) =     14.385 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     26.041 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.843 ± 4.888  ops/ms
ClientGrpc.existUser                       thrpt       3  10.546 ± 1.223  ops/ms
ClientGrpc.getUser                         thrpt       3  10.103 ± 0.610  ops/ms
ClientGrpc.listUser                        thrpt       3   7.868 ± 2.043  ops/ms
ClientGrpc.createUser                       avgt       3   3.223 ± 1.116   ms/op
ClientGrpc.existUser                        avgt       3   3.101 ± 0.602   ms/op
ClientGrpc.getUser                          avgt       3   3.199 ± 0.258   ms/op
ClientGrpc.listUser                         avgt       3   4.020 ± 0.618   ms/op
ClientGrpc.createUser                     sample  297368   3.227 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.680           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.195           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.100           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.489           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.777           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.792           ms/op
ClientGrpc.existUser                      sample  315899   3.038 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.691           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.019           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.645           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.867           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.309           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.504           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.365           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.807           ms/op
ClientGrpc.getUser                        sample  300976   3.189 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.158           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.393           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.767           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.003           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.871           ms/op
ClientGrpc.listUser                       sample  233110   4.121 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.155           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.936           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.385           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.626           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
