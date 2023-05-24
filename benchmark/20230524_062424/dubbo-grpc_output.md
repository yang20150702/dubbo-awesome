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
# Warmup Iteration   1: 4.430 ops/ms
# Warmup Iteration   2: 9.356 ops/ms
# Warmup Iteration   3: 10.030 ops/ms
Iteration   1: 10.511 ops/ms
Iteration   2: 10.477 ops/ms
Iteration   3: 10.711 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.566 ±(99.9%) 2.309 ops/ms [Average]
  (min, avg, max) = (10.477, 10.566, 10.711), stdev = 0.127
  CI (99.9%): [8.258, 12.875] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.806 ops/ms
# Warmup Iteration   2: 10.916 ops/ms
# Warmup Iteration   3: 11.203 ops/ms
Iteration   1: 11.040 ops/ms
Iteration   2: 11.372 ops/ms
Iteration   3: 11.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.297 ±(99.9%) 4.181 ops/ms [Average]
  (min, avg, max) = (11.040, 11.297, 11.480), stdev = 0.229
  CI (99.9%): [7.116, 15.478] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.483 ops/ms
# Warmup Iteration   2: 10.381 ops/ms
# Warmup Iteration   3: 10.606 ops/ms
Iteration   1: 10.682 ops/ms
Iteration   2: 10.687 ops/ms
Iteration   3: 10.716 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.695 ±(99.9%) 0.340 ops/ms [Average]
  (min, avg, max) = (10.682, 10.695, 10.716), stdev = 0.019
  CI (99.9%): [10.355, 11.035] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.460 ops/ms
# Warmup Iteration   2: 8.168 ops/ms
# Warmup Iteration   3: 8.318 ops/ms
Iteration   1: 8.196 ops/ms
Iteration   2: 8.199 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.208 ±(99.9%) 0.333 ops/ms [Average]
  (min, avg, max) = (8.196, 8.208, 8.229), stdev = 0.018
  CI (99.9%): [7.875, 8.540] (assumes normal distribution)


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
# Warmup Iteration   1: 4.337 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.151 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.037 ±(99.9%) 0.003 ms/op
Iteration   1: 2.983 ±(99.9%) 0.002 ms/op
Iteration   2: 2.988 ±(99.9%) 0.002 ms/op
Iteration   3: 2.984 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 0.050 ms/op [Average]
  (min, avg, max) = (2.983, 2.985, 2.988), stdev = 0.003
  CI (99.9%): [2.935, 3.035] (assumes normal distribution)


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
# Warmup Iteration   1: 3.982 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.979 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.002 ms/op
Iteration   1: 2.860 ±(99.9%) 0.002 ms/op
Iteration   2: 2.777 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.845 ±(99.9%) 1.142 ms/op [Average]
  (min, avg, max) = (2.777, 2.845, 2.899), stdev = 0.063
  CI (99.9%): [1.703, 3.988] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.230 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 2.959 ±(99.9%) 0.004 ms/op
Iteration   2: 2.973 ±(99.9%) 0.003 ms/op
Iteration   3: 2.984 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.972 ±(99.9%) 0.227 ms/op [Average]
  (min, avg, max) = (2.959, 2.972, 2.984), stdev = 0.012
  CI (99.9%): [2.745, 3.199] (assumes normal distribution)


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
# Warmup Iteration   1: 5.308 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.022 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.024 ms/op
Iteration   1: 3.872 ±(99.9%) 0.020 ms/op
Iteration   2: 3.802 ±(99.9%) 0.024 ms/op
Iteration   3: 3.915 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.863 ±(99.9%) 1.039 ms/op [Average]
  (min, avg, max) = (3.802, 3.863, 3.915), stdev = 0.057
  CI (99.9%): [2.824, 4.902] (assumes normal distribution)


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
# Warmup Iteration   1: 4.361 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
Iteration   1: 2.975 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.682 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  8.254 ms/op
                 createUser·p0.9999: 15.802 ms/op
                 createUser·p1.00:   16.335 ms/op

Iteration   2: 2.981 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.761 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.396 ms/op
                 createUser·p0.9999: 17.203 ms/op
                 createUser·p1.00:   17.498 ms/op

Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.799 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.645 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  8.618 ms/op
                 createUser·p0.9999: 20.480 ms/op
                 createUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322179
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32425 
    [ 2.500,  5.000) = 288587 
    [ 5.000,  7.500) = 782 
    [ 7.500, 10.000) = 171 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      8.074 ms/op
     p(99.9900) =     19.816 ms/op
     p(99.9990) =     21.725 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.010 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.807 ±(99.9%) 0.006 ms/op
Iteration   1: 2.861 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.248 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.153 ms/op
                 existUser·p0.999:  6.190 ms/op
                 existUser·p0.9999: 19.158 ms/op
                 existUser·p1.00:   19.562 ms/op

Iteration   2: 2.802 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.166 ms/op
                 existUser·p0.95:   3.359 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.390 ms/op
                 existUser·p0.9999: 17.812 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 2.891 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.761 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.482 ms/op
                 existUser·p0.99:   4.132 ms/op
                 existUser·p0.999:  6.318 ms/op
                 existUser·p0.9999: 19.235 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 336782
  mean =      2.851 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1049 
    [ 1.250,  2.500) = 48352 
    [ 2.500,  3.750) = 280313 
    [ 3.750,  5.000) = 6190 
    [ 5.000,  6.250) = 573 
    [ 6.250,  7.500) = 112 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 36 

  Percentiles, ms/op:
      p(0.0000) =      0.733 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.265 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.142 ms/op
     p(99.9000) =      6.162 ms/op
     p(99.9900) =     19.104 ms/op
     p(99.9990) =     19.625 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 4.182 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.108 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.005 ms/op
Iteration   1: 2.968 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.703 ms/op
                 getUser·p0.50:   2.941 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.513 ms/op
                 getUser·p0.9999: 14.261 ms/op
                 getUser·p1.00:   14.877 ms/op

Iteration   2: 2.973 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   2.945 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.670 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.590 ms/op
                 getUser·p0.9999: 25.272 ms/op
                 getUser·p1.00:   26.051 ms/op

Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.551 ms/op
                 getUser·p0.99:   4.366 ms/op
                 getUser·p0.999:  9.385 ms/op
                 getUser·p0.9999: 17.535 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 323938
  mean =      2.962 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26786 
    [ 2.500,  5.000) = 295910 
    [ 5.000,  7.500) = 936 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.633 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     21.618 ms/op
     p(99.9990) =     25.520 ms/op
     p(99.9999) =     26.051 ms/op
    p(100.0000) =     26.051 ms/op


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
# Warmup Iteration   1: 5.529 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.012 ms/op
Iteration   1: 3.898 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   3.723 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.931 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  17.133 ms/op
                 listUser·p0.9999: 20.218 ms/op
                 listUser·p1.00:   22.348 ms/op

Iteration   2: 3.905 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.130 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.760 ms/op
                 listUser·p0.95:   5.603 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  15.027 ms/op
                 listUser·p0.9999: 22.866 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 3.823 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.014 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   6.529 ms/op
                 listUser·p0.999:  16.138 ms/op
                 listUser·p0.9999: 25.587 ms/op
                 listUser·p1.00:   26.149 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 247782
  mean =      3.875 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4339 
    [ 2.500,  5.000) = 223342 
    [ 5.000,  7.500) = 19042 
    [ 7.500, 10.000) = 599 
    [10.000, 12.500) = 76 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     23.902 ms/op
     p(99.9990) =     26.021 ms/op
     p(99.9999) =     26.149 ms/op
    p(100.0000) =     26.149 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.566 ± 2.309  ops/ms
ClientGrpc.existUser                       thrpt       3  11.297 ± 4.181  ops/ms
ClientGrpc.getUser                         thrpt       3  10.695 ± 0.340  ops/ms
ClientGrpc.listUser                        thrpt       3   8.208 ± 0.333  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 0.050   ms/op
ClientGrpc.existUser                        avgt       3   2.845 ± 1.142   ms/op
ClientGrpc.getUser                          avgt       3   2.972 ± 0.227   ms/op
ClientGrpc.listUser                         avgt       3   3.863 ± 1.039   ms/op
ClientGrpc.createUser                     sample  322179   2.979 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.761           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.953           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.473           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.074           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.816           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  336782   2.851 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.733           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.834           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.265           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.142           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.162           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.104           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.792           ms/op
ClientGrpc.getUser                        sample  323938   2.962 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.635           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.937           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.301           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.618           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.051           ms/op
ClientGrpc.listUser                       sample  247782   3.875 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.877           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.731           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.768           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.902           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.149           ms/op
