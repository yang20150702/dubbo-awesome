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
# Warmup Iteration   1: 4.236 ops/ms
# Warmup Iteration   2: 9.092 ops/ms
# Warmup Iteration   3: 10.289 ops/ms
Iteration   1: 10.074 ops/ms
Iteration   2: 10.145 ops/ms
Iteration   3: 10.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.194 ±(99.9%) 2.757 ops/ms [Average]
  (min, avg, max) = (10.074, 10.194, 10.364), stdev = 0.151
  CI (99.9%): [7.438, 12.951] (assumes normal distribution)


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
# Warmup Iteration   1: 7.626 ops/ms
# Warmup Iteration   2: 10.222 ops/ms
# Warmup Iteration   3: 10.493 ops/ms
Iteration   1: 10.734 ops/ms
Iteration   2: 10.830 ops/ms
Iteration   3: 10.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.754 ±(99.9%) 1.241 ops/ms [Average]
  (min, avg, max) = (10.698, 10.754, 10.830), stdev = 0.068
  CI (99.9%): [9.513, 11.995] (assumes normal distribution)


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
# Warmup Iteration   1: 7.216 ops/ms
# Warmup Iteration   2: 9.999 ops/ms
# Warmup Iteration   3: 10.109 ops/ms
Iteration   1: 10.017 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 10.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.110 ±(99.9%) 2.282 ops/ms [Average]
  (min, avg, max) = (10.017, 10.110, 10.253), stdev = 0.125
  CI (99.9%): [7.828, 12.393] (assumes normal distribution)


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
# Warmup Iteration   1: 5.532 ops/ms
# Warmup Iteration   2: 7.629 ops/ms
# Warmup Iteration   3: 7.958 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 7.884 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.981 ±(99.9%) 1.542 ops/ms [Average]
  (min, avg, max) = (7.884, 7.981, 8.033), stdev = 0.084
  CI (99.9%): [6.439, 9.523] (assumes normal distribution)


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
# Warmup Iteration   1: 4.618 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.156 ±(99.9%) 0.002 ms/op
Iteration   1: 3.125 ±(99.9%) 0.002 ms/op
Iteration   2: 3.162 ±(99.9%) 0.003 ms/op
Iteration   3: 3.173 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.153 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.125, 3.153, 3.173), stdev = 0.025
  CI (99.9%): [2.691, 3.615] (assumes normal distribution)


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.083 ±(99.9%) 0.003 ms/op
Iteration   1: 2.953 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.002 ms/op
Iteration   3: 3.022 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.003 ±(99.9%) 0.798 ms/op [Average]
  (min, avg, max) = (2.953, 3.003, 3.034), stdev = 0.044
  CI (99.9%): [2.205, 3.801] (assumes normal distribution)


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
# Warmup Iteration   1: 4.292 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.004 ms/op
Iteration   1: 3.169 ±(99.9%) 0.002 ms/op
Iteration   2: 3.176 ±(99.9%) 0.004 ms/op
Iteration   3: 3.184 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.176 ±(99.9%) 0.138 ms/op [Average]
  (min, avg, max) = (3.169, 3.176, 3.184), stdev = 0.008
  CI (99.9%): [3.038, 3.314] (assumes normal distribution)


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
# Warmup Iteration   1: 5.321 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.183 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.059 ±(99.9%) 0.011 ms/op
Iteration   1: 4.018 ±(99.9%) 0.009 ms/op
Iteration   2: 4.045 ±(99.9%) 0.006 ms/op
Iteration   3: 3.993 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.019 ±(99.9%) 0.477 ms/op [Average]
  (min, avg, max) = (3.993, 4.019, 4.045), stdev = 0.026
  CI (99.9%): [3.542, 4.495] (assumes normal distribution)


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
# Warmup Iteration   1: 4.198 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.273 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.205 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.630 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.695 ms/op
                 createUser·p0.95:   3.916 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  11.194 ms/op
                 createUser·p0.9999: 12.412 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   2: 3.159 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  10.066 ms/op
                 createUser·p0.9999: 14.932 ms/op
                 createUser·p1.00:   15.516 ms/op

Iteration   3: 3.178 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.635 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.071 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.907 ms/op
                 createUser·p0.9999: 26.442 ms/op
                 createUser·p1.00:   26.804 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306551
  mean =      3.131 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28043 
    [ 2.500,  5.000) = 277216 
    [ 5.000,  7.500) = 755 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 219 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 37 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.630 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     10.737 ms/op
     p(99.9900) =     25.101 ms/op
     p(99.9990) =     26.704 ms/op
     p(99.9999) =     26.804 ms/op
    p(100.0000) =     26.804 ms/op


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
# Warmup Iteration   1: 3.843 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.006 ±(99.9%) 0.008 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.779 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.670 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.168 ms/op
                 existUser·p0.999:  6.825 ms/op
                 existUser·p0.9999: 19.726 ms/op
                 existUser·p1.00:   20.218 ms/op

Iteration   2: 2.919 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.748 ms/op
                 existUser·p0.95:   3.932 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.402 ms/op
                 existUser·p0.9999: 16.369 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.979 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.826 ms/op
                 existUser·p0.99:   4.227 ms/op
                 existUser·p0.999:  7.922 ms/op
                 existUser·p0.9999: 17.867 ms/op
                 existUser·p1.00:   18.153 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321889
  mean =      2.982 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51937 
    [ 2.500,  5.000) = 269055 
    [ 5.000,  7.500) = 640 
    [ 7.500, 10.000) = 65 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.690 ms/op
     p(95.0000) =      3.871 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.094 ms/op
     p(99.9900) =     18.765 ms/op
     p(99.9990) =     20.105 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 4.297 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.007 ms/op
Iteration   1: 3.133 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  7.111 ms/op
                 getUser·p0.9999: 17.845 ms/op
                 getUser·p1.00:   18.219 ms/op

Iteration   2: 3.109 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.960 ms/op
                 getUser·p0.9999: 17.658 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.636 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.059 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  6.203 ms/op
                 getUser·p0.9999: 20.067 ms/op
                 getUser·p1.00:   20.578 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 305504
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24411 
    [ 2.500,  5.000) = 280239 
    [ 5.000,  7.500) = 654 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.789 ms/op
     p(95.0000) =      3.977 ms/op
     p(99.0000) =      4.358 ms/op
     p(99.9000) =      6.799 ms/op
     p(99.9900) =     18.037 ms/op
     p(99.9990) =     20.444 ms/op
     p(99.9999) =     20.578 ms/op
    p(100.0000) =     20.578 ms/op


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
# Warmup Iteration   1: 5.512 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.111 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.960 ±(99.9%) 0.011 ms/op
Iteration   1: 3.930 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   5.022 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.012 ms/op
                 listUser·p0.9999: 18.088 ms/op
                 listUser·p1.00:   19.104 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.300 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.644 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  15.061 ms/op
                 listUser·p0.9999: 21.039 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   3: 3.928 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.122 ms/op
                 listUser·p0.9999: 26.598 ms/op
                 listUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242564
  mean =      3.955 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1932 
    [ 2.500,  5.000) = 218224 
    [ 5.000,  7.500) = 21118 
    [ 7.500, 10.000) = 797 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 142 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.043 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     15.015 ms/op
     p(99.9900) =     25.837 ms/op
     p(99.9990) =     26.959 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.194 ± 2.757  ops/ms
ClientGrpc.existUser                       thrpt       3  10.754 ± 1.241  ops/ms
ClientGrpc.getUser                         thrpt       3  10.110 ± 2.282  ops/ms
ClientGrpc.listUser                        thrpt       3   7.981 ± 1.542  ops/ms
ClientGrpc.createUser                       avgt       3   3.153 ± 0.462   ms/op
ClientGrpc.existUser                        avgt       3   3.003 ± 0.798   ms/op
ClientGrpc.getUser                          avgt       3   3.176 ± 0.138   ms/op
ClientGrpc.listUser                         avgt       3   4.019 ± 0.477   ms/op
ClientGrpc.createUser                     sample  306551   3.131 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.630           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.105           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.998           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.737           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.101           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.804           ms/op
ClientGrpc.existUser                      sample  321889   2.982 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.729           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.094           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.765           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.218           ms/op
ClientGrpc.getUser                        sample  305504   3.140 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.588           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.125           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.789           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.977           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.358           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.799           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.037           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.578           ms/op
ClientGrpc.listUser                       sample  242564   3.955 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.043           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.915           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.015           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.837           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
