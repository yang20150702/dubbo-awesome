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
# Warmup Iteration   1: 5.001 ops/ms
# Warmup Iteration   2: 9.280 ops/ms
# Warmup Iteration   3: 10.168 ops/ms
Iteration   1: 10.540 ops/ms
Iteration   2: 10.421 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.364 ±(99.9%) 3.831 ops/ms [Average]
  (min, avg, max) = (10.132, 10.364, 10.540), stdev = 0.210
  CI (99.9%): [6.533, 14.195] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.758 ops/ms
# Warmup Iteration   2: 10.542 ops/ms
# Warmup Iteration   3: 10.867 ops/ms
Iteration   1: 11.054 ops/ms
Iteration   2: 11.037 ops/ms
Iteration   3: 11.066 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.052 ±(99.9%) 0.271 ops/ms [Average]
  (min, avg, max) = (11.037, 11.052, 11.066), stdev = 0.015
  CI (99.9%): [10.782, 11.323] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.546 ops/ms
# Warmup Iteration   2: 10.194 ops/ms
# Warmup Iteration   3: 10.150 ops/ms
Iteration   1: 10.141 ops/ms
Iteration   2: 10.017 ops/ms
Iteration   3: 10.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.248 ±(99.9%) 5.442 ops/ms [Average]
  (min, avg, max) = (10.017, 10.248, 10.585), stdev = 0.298
  CI (99.9%): [4.805, 15.690] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.925 ops/ms
# Warmup Iteration   2: 7.780 ops/ms
# Warmup Iteration   3: 7.985 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 8.214 ops/ms
Iteration   3: 7.962 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.001 ±(99.9%) 3.578 ops/ms [Average]
  (min, avg, max) = (7.827, 8.001, 8.214), stdev = 0.196
  CI (99.9%): [4.423, 11.580] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.006 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.002 ms/op
Iteration   1: 3.215 ±(99.9%) 0.002 ms/op
Iteration   2: 3.134 ±(99.9%) 0.003 ms/op
Iteration   3: 3.161 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.170 ±(99.9%) 0.749 ms/op [Average]
  (min, avg, max) = (3.134, 3.170, 3.215), stdev = 0.041
  CI (99.9%): [2.421, 3.919] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.798 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.185 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.107 ±(99.9%) 0.003 ms/op
Iteration   1: 3.157 ±(99.9%) 0.002 ms/op
Iteration   2: 3.117 ±(99.9%) 0.002 ms/op
Iteration   3: 2.958 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.078 ±(99.9%) 1.920 ms/op [Average]
  (min, avg, max) = (2.958, 3.078, 3.157), stdev = 0.105
  CI (99.9%): [1.158, 4.997] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.972 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.178 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.002 ms/op
Iteration   1: 3.096 ±(99.9%) 0.003 ms/op
Iteration   2: 3.068 ±(99.9%) 0.002 ms/op
Iteration   3: 3.102 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.089 ±(99.9%) 0.325 ms/op [Average]
  (min, avg, max) = (3.068, 3.089, 3.102), stdev = 0.018
  CI (99.9%): [2.763, 3.414] (assumes normal distribution)


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
# Warmup Iteration   1: 5.008 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.222 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.174 ±(99.9%) 0.021 ms/op
Iteration   1: 3.982 ±(99.9%) 0.012 ms/op
Iteration   2: 4.066 ±(99.9%) 0.007 ms/op
Iteration   3: 4.093 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.047 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.982, 4.047, 4.093), stdev = 0.058
  CI (99.9%): [2.997, 5.097] (assumes normal distribution)


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
# Warmup Iteration   1: 4.035 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.157 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.696 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.133 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  6.868 ms/op
                 createUser·p0.9999: 14.100 ms/op
                 createUser·p1.00:   14.844 ms/op

Iteration   2: 3.202 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   3.187 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.014 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.847 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   3: 3.108 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.459 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   5.112 ms/op
                 createUser·p0.999:  10.420 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304337
  mean =      3.155 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1218 
    [ 1.250,  2.500) = 20341 
    [ 2.500,  3.750) = 246283 
    [ 3.750,  5.000) = 34103 
    [ 5.000,  6.250) = 1401 
    [ 6.250,  7.500) = 502 
    [ 7.500,  8.750) = 184 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 45 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.459 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.817 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.793 ms/op
     p(99.9900) =     18.416 ms/op
     p(99.9990) =     18.873 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
Iteration   1: 3.110 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.871 ms/op
                 existUser·p0.50:   3.064 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.010 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  8.459 ms/op
                 existUser·p0.9999: 13.414 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   2: 3.068 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.777 ms/op
                 existUser·p0.95:   4.018 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.419 ms/op
                 existUser·p0.9999: 20.939 ms/op
                 existUser·p1.00:   21.398 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.360 ms/op
                 existUser·p0.50:   2.945 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.625 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  12.010 ms/op
                 existUser·p0.9999: 15.604 ms/op
                 existUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315219
  mean =      3.046 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33612 
    [ 2.500,  5.000) = 279680 
    [ 5.000,  7.500) = 1455 
    [ 7.500, 10.000) = 226 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.360 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     20.101 ms/op
     p(99.9990) =     21.125 ms/op
     p(99.9999) =     21.398 ms/op
    p(100.0000) =     21.398 ms/op


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
# Warmup Iteration   1: 3.878 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.006 ms/op
Iteration   1: 3.171 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   3.146 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  10.916 ms/op
                 getUser·p0.9999: 17.793 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 3.135 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.772 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.298 ms/op
                 getUser·p0.9999: 18.402 ms/op
                 getUser·p1.00:   18.842 ms/op

Iteration   3: 3.243 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.186 ms/op
                 getUser·p0.99:   4.497 ms/op
                 getUser·p0.999:  6.298 ms/op
                 getUser·p0.9999: 25.957 ms/op
                 getUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301516
  mean =      3.182 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21851 
    [ 2.500,  5.000) = 278423 
    [ 5.000,  7.500) = 853 
    [ 7.500, 10.000) = 134 
    [10.000, 12.500) = 139 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.751 ms/op
     p(50.0000) =      3.162 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      9.781 ms/op
     p(99.9900) =     24.997 ms/op
     p(99.9990) =     26.182 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


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
# Warmup Iteration   1: 4.851 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.087 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.949 ±(99.9%) 0.011 ms/op
Iteration   1: 3.927 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.343 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  12.070 ms/op
                 listUser·p0.9999: 15.380 ms/op
                 listUser·p1.00:   16.810 ms/op

Iteration   2: 3.926 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.781 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  15.030 ms/op
                 listUser·p0.9999: 22.446 ms/op
                 listUser·p1.00:   23.593 ms/op

Iteration   3: 3.878 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.948 ms/op
                 listUser·p0.50:   3.736 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  13.460 ms/op
                 listUser·p0.9999: 18.784 ms/op
                 listUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245535
  mean =      3.910 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4990 
    [ 2.500,  5.000) = 217777 
    [ 5.000,  7.500) = 21841 
    [ 7.500, 10.000) = 430 
    [10.000, 12.500) = 176 
    [12.500, 15.000) = 176 
    [15.000, 17.500) = 69 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      6.595 ms/op
     p(99.9000) =     13.475 ms/op
     p(99.9900) =     21.674 ms/op
     p(99.9990) =     23.420 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.364 ± 3.831  ops/ms
ClientGrpc.existUser                       thrpt       3  11.052 ± 0.271  ops/ms
ClientGrpc.getUser                         thrpt       3  10.248 ± 5.442  ops/ms
ClientGrpc.listUser                        thrpt       3   8.001 ± 3.578  ops/ms
ClientGrpc.createUser                       avgt       3   3.170 ± 0.749   ms/op
ClientGrpc.existUser                        avgt       3   3.078 ± 1.920   ms/op
ClientGrpc.getUser                          avgt       3   3.089 ± 0.325   ms/op
ClientGrpc.listUser                         avgt       3   4.047 ± 1.050   ms/op
ClientGrpc.createUser                     sample  304337   3.155 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.459           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.117           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.817           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.793           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.416           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.907           ms/op
ClientGrpc.existUser                      sample  315219   3.046 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.360           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.011           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.101           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.398           ms/op
ClientGrpc.getUser                        sample  301516   3.182 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.751           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.162           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.875           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.071           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.781           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.997           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.313           ms/op
ClientGrpc.listUser                       sample  245535   3.910 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.781           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.932           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.587           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.595           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.475           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.674           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.593           ms/op
