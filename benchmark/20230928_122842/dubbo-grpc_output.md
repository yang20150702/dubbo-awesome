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
# Warmup Iteration   1: 3.819 ops/ms
# Warmup Iteration   2: 8.733 ops/ms
# Warmup Iteration   3: 9.778 ops/ms
Iteration   1: 9.961 ops/ms
Iteration   2: 10.127 ops/ms
Iteration   3: 10.054 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.047 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (9.961, 10.047, 10.127), stdev = 0.083
  CI (99.9%): [8.531, 11.563] (assumes normal distribution)


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
# Warmup Iteration   1: 6.885 ops/ms
# Warmup Iteration   2: 10.082 ops/ms
# Warmup Iteration   3: 10.530 ops/ms
Iteration   1: 10.588 ops/ms
Iteration   2: 10.329 ops/ms
Iteration   3: 10.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.505 ±(99.9%) 2.788 ops/ms [Average]
  (min, avg, max) = (10.329, 10.505, 10.599), stdev = 0.153
  CI (99.9%): [7.718, 13.293] (assumes normal distribution)


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
# Warmup Iteration   1: 6.862 ops/ms
# Warmup Iteration   2: 9.758 ops/ms
# Warmup Iteration   3: 10.071 ops/ms
Iteration   1: 10.287 ops/ms
Iteration   2: 10.230 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.259 ±(99.9%) 0.518 ops/ms [Average]
  (min, avg, max) = (10.230, 10.259, 10.287), stdev = 0.028
  CI (99.9%): [9.740, 10.777] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 6.093 ops/ms
# Warmup Iteration   2: 7.336 ops/ms
# Warmup Iteration   3: 8.100 ops/ms
Iteration   1: 8.138 ops/ms
Iteration   2: 8.228 ops/ms
Iteration   3: 8.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.271 ±(99.9%) 2.900 ops/ms [Average]
  (min, avg, max) = (8.138, 8.271, 8.447), stdev = 0.159
  CI (99.9%): [5.370, 11.171] (assumes normal distribution)


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
# Warmup Iteration   1: 4.354 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.123 ±(99.9%) 0.004 ms/op
Iteration   1: 3.214 ±(99.9%) 0.002 ms/op
Iteration   2: 3.187 ±(99.9%) 0.002 ms/op
Iteration   3: 3.171 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.191 ±(99.9%) 0.398 ms/op [Average]
  (min, avg, max) = (3.171, 3.191, 3.214), stdev = 0.022
  CI (99.9%): [2.793, 3.588] (assumes normal distribution)


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
# Warmup Iteration   1: 4.123 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.042 ±(99.9%) 0.002 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 3.052 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.058 ±(99.9%) 0.354 ms/op [Average]
  (min, avg, max) = (3.042, 3.058, 3.080), stdev = 0.019
  CI (99.9%): [2.704, 3.412] (assumes normal distribution)


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
# Warmup Iteration   1: 4.220 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.077 ±(99.9%) 0.002 ms/op
Iteration   1: 3.217 ±(99.9%) 0.002 ms/op
Iteration   2: 3.147 ±(99.9%) 0.001 ms/op
Iteration   3: 3.185 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.183 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.147, 3.183, 3.217), stdev = 0.035
  CI (99.9%): [2.540, 3.826] (assumes normal distribution)


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
# Warmup Iteration   1: 5.668 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.054 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.926 ±(99.9%) 0.032 ms/op
Iteration   1: 3.864 ±(99.9%) 0.022 ms/op
Iteration   2: 3.968 ±(99.9%) 0.012 ms/op
Iteration   3: 3.891 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 0.988 ms/op [Average]
  (min, avg, max) = (3.864, 3.908, 3.968), stdev = 0.054
  CI (99.9%): [2.920, 4.896] (assumes normal distribution)


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
# Warmup Iteration   1: 4.544 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.007 ms/op
Iteration   1: 3.148 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  7.184 ms/op
                 createUser·p0.9999: 13.790 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 3.086 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.034 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.564 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.301 ms/op
                 createUser·p0.999:  8.007 ms/op
                 createUser·p0.9999: 14.336 ms/op
                 createUser·p1.00:   14.565 ms/op

Iteration   3: 3.147 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.894 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.489 ms/op
                 createUser·p0.999:  8.767 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.743 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306922
  mean =      3.127 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 171 
    [ 1.250,  2.500) = 10079 
    [ 2.500,  3.750) = 273895 
    [ 3.750,  5.000) = 21175 
    [ 5.000,  6.250) = 742 
    [ 6.250,  7.500) = 473 
    [ 7.500,  8.750) = 181 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 9 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 23 
    [17.500, 18.750) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.846 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     16.820 ms/op
     p(99.9990) =     18.640 ms/op
     p(99.9999) =     18.743 ms/op
    p(100.0000) =     18.743 ms/op


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
# Warmup Iteration   1: 4.267 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.175 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.153 ±(99.9%) 0.006 ms/op
Iteration   1: 3.043 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.986 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   4.149 ms/op
                 existUser·p0.999:  7.160 ms/op
                 existUser·p0.9999: 13.238 ms/op
                 existUser·p1.00:   13.582 ms/op

Iteration   2: 3.018 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.604 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   4.129 ms/op
                 existUser·p0.999:  6.745 ms/op
                 existUser·p0.9999: 13.163 ms/op
                 existUser·p1.00:   13.566 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.689 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.478 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  11.223 ms/op
                 existUser·p0.9999: 17.835 ms/op
                 existUser·p1.00:   18.383 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318324
  mean =      3.014 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 466 
    [ 1.250,  2.500) = 25487 
    [ 2.500,  3.750) = 274777 
    [ 3.750,  5.000) = 16290 
    [ 5.000,  6.250) = 692 
    [ 6.250,  7.500) = 261 
    [ 7.500,  8.750) = 94 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 40 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 109 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 22 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.689 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.772 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.897 ms/op
     p(99.9900) =     17.444 ms/op
     p(99.9990) =     18.240 ms/op
     p(99.9999) =     18.383 ms/op
    p(100.0000) =     18.383 ms/op


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
# Warmup Iteration   1: 4.405 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.173 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.217 ms/op
                 getUser·p0.9999: 18.425 ms/op
                 getUser·p1.00:   19.825 ms/op

Iteration   2: 3.108 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.655 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   24.838 ms/op

Iteration   3: 3.190 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.957 ms/op
                 getUser·p0.99:   4.680 ms/op
                 getUser·p0.999:  9.385 ms/op
                 getUser·p0.9999: 22.805 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306607
  mean =      3.130 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6304 
    [ 2.500,  5.000) = 298398 
    [ 5.000,  7.500) = 1446 
    [ 7.500, 10.000) = 239 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.654 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.854 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =      8.390 ms/op
     p(99.9900) =     23.025 ms/op
     p(99.9990) =     24.736 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 5.663 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.070 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.939 ±(99.9%) 0.010 ms/op
Iteration   1: 3.945 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.681 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.760 ms/op
                 listUser·p0.99:   6.578 ms/op
                 listUser·p0.999:  12.975 ms/op
                 listUser·p0.9999: 16.187 ms/op
                 listUser·p1.00:   18.088 ms/op

Iteration   2: 3.857 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.221 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.087 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.402 ms/op
                 listUser·p0.9999: 16.037 ms/op
                 listUser·p1.00:   17.367 ms/op

Iteration   3: 3.903 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.599 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   5.063 ms/op
                 listUser·p0.99:   6.619 ms/op
                 listUser·p0.999:  14.844 ms/op
                 listUser·p0.9999: 18.272 ms/op
                 listUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245951
  mean =      3.901 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 8 
    [ 1.250,  2.500) = 1461 
    [ 2.500,  3.750) = 103075 
    [ 3.750,  5.000) = 129409 
    [ 5.000,  6.250) = 7448 
    [ 6.250,  7.500) = 3166 
    [ 7.500,  8.750) = 561 
    [ 8.750, 10.000) = 171 
    [10.000, 11.250) = 134 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 126 
    [13.750, 15.000) = 162 
    [15.000, 16.250) = 98 
    [16.250, 17.500) = 20 
    [17.500, 18.750) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.350 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     14.124 ms/op
     p(99.9900) =     17.511 ms/op
     p(99.9990) =     19.452 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.047 ± 1.516  ops/ms
ClientGrpc.existUser                       thrpt       3  10.505 ± 2.788  ops/ms
ClientGrpc.getUser                         thrpt       3  10.259 ± 0.518  ops/ms
ClientGrpc.listUser                        thrpt       3   8.271 ± 2.900  ops/ms
ClientGrpc.createUser                       avgt       3   3.191 ± 0.398   ms/op
ClientGrpc.existUser                        avgt       3   3.058 ± 0.354   ms/op
ClientGrpc.getUser                          avgt       3   3.183 ± 0.643   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 0.988   ms/op
ClientGrpc.createUser                     sample  306922   3.127 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.894           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.080           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.670           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.846           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.820           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.743           ms/op
ClientGrpc.existUser                      sample  318324   3.014 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.689           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.961           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.580           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.772           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.897           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.444           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.383           ms/op
ClientGrpc.getUser                        sample  306607   3.130 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.654           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.854           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.448           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.390           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.025           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  245951   3.901 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.599           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.350           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.964           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.124           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          17.511           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          19.562           ms/op
