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
# Warmup Iteration   1: 4.337 ops/ms
# Warmup Iteration   2: 9.400 ops/ms
# Warmup Iteration   3: 10.288 ops/ms
Iteration   1: 10.390 ops/ms
Iteration   2: 10.535 ops/ms
Iteration   3: 10.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.502 ±(99.9%) 1.803 ops/ms [Average]
  (min, avg, max) = (10.390, 10.502, 10.579), stdev = 0.099
  CI (99.9%): [8.699, 12.304] (assumes normal distribution)


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
# Warmup Iteration   1: 7.354 ops/ms
# Warmup Iteration   2: 10.775 ops/ms
# Warmup Iteration   3: 10.811 ops/ms
Iteration   1: 11.051 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.924 ±(99.9%) 3.219 ops/ms [Average]
  (min, avg, max) = (10.723, 10.924, 11.051), stdev = 0.176
  CI (99.9%): [7.705, 14.143] (assumes normal distribution)


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
# Warmup Iteration   1: 7.353 ops/ms
# Warmup Iteration   2: 9.763 ops/ms
# Warmup Iteration   3: 9.553 ops/ms
Iteration   1: 10.169 ops/ms
Iteration   2: 10.314 ops/ms
Iteration   3: 10.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.323 ±(99.9%) 2.906 ops/ms [Average]
  (min, avg, max) = (10.169, 10.323, 10.487), stdev = 0.159
  CI (99.9%): [7.417, 13.230] (assumes normal distribution)


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
# Warmup Iteration   1: 5.429 ops/ms
# Warmup Iteration   2: 7.646 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.870 ops/ms
Iteration   2: 7.837 ops/ms
Iteration   3: 8.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.908 ±(99.9%) 1.730 ops/ms [Average]
  (min, avg, max) = (7.837, 7.908, 8.016), stdev = 0.095
  CI (99.9%): [6.178, 9.638] (assumes normal distribution)


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
# Warmup Iteration   1: 4.536 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.262 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.003 ms/op
Iteration   1: 3.113 ±(99.9%) 0.004 ms/op
Iteration   2: 3.020 ±(99.9%) 0.002 ms/op
Iteration   3: 3.039 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.896 ms/op [Average]
  (min, avg, max) = (3.020, 3.057, 3.113), stdev = 0.049
  CI (99.9%): [2.162, 3.953] (assumes normal distribution)


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
# Warmup Iteration   1: 3.989 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.003 ms/op
Iteration   1: 2.967 ±(99.9%) 0.002 ms/op
Iteration   2: 2.976 ±(99.9%) 0.003 ms/op
Iteration   3: 2.945 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.962 ±(99.9%) 0.291 ms/op [Average]
  (min, avg, max) = (2.945, 2.962, 2.976), stdev = 0.016
  CI (99.9%): [2.671, 3.253] (assumes normal distribution)


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
# Warmup Iteration   1: 4.185 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.197 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.081 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.002 ms/op
Iteration   2: 3.034 ±(99.9%) 0.004 ms/op
Iteration   3: 3.075 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.062 ±(99.9%) 0.448 ms/op [Average]
  (min, avg, max) = (3.034, 3.062, 3.078), stdev = 0.025
  CI (99.9%): [2.615, 3.510] (assumes normal distribution)


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
# Warmup Iteration   1: 5.006 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.294 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.944 ±(99.9%) 0.025 ms/op
Iteration   1: 3.949 ±(99.9%) 0.014 ms/op
Iteration   2: 3.982 ±(99.9%) 0.067 ms/op
Iteration   3: 3.945 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (3.945, 3.958, 3.982), stdev = 0.020
  CI (99.9%): [3.591, 4.326] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
Iteration   1: 3.070 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.933 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.518 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.358 ms/op
                 createUser·p0.999:  10.499 ms/op
                 createUser·p0.9999: 31.233 ms/op
                 createUser·p1.00:   31.490 ms/op

Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.684 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.547 ms/op
                 createUser·p0.95:   3.764 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  5.966 ms/op
                 createUser·p0.9999: 19.238 ms/op
                 createUser·p1.00:   19.726 ms/op

Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.669 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  7.009 ms/op
                 createUser·p0.9999: 31.392 ms/op
                 createUser·p1.00:   31.850 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313234
  mean =      3.065 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17492 
    [ 2.500,  5.000) = 294331 
    [ 5.000,  7.500) = 1120 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 64 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.230 ms/op
     p(99.9900) =     31.119 ms/op
     p(99.9990) =     31.706 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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
# Warmup Iteration   1: 4.044 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.017 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.945 ±(99.9%) 0.006 ms/op
Iteration   1: 2.948 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.437 ms/op
                 existUser·p0.95:   3.633 ms/op
                 existUser·p0.99:   4.358 ms/op
                 existUser·p0.999:  6.644 ms/op
                 existUser·p0.9999: 12.485 ms/op
                 existUser·p1.00:   12.665 ms/op

Iteration   2: 2.923 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.598 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.092 ms/op
                 existUser·p0.999:  5.863 ms/op
                 existUser·p0.9999: 19.923 ms/op
                 existUser·p1.00:   20.283 ms/op

Iteration   3: 2.859 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.604 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.366 ms/op
                 existUser·p0.999:  9.918 ms/op
                 existUser·p0.9999: 16.447 ms/op
                 existUser·p1.00:   16.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329877
  mean =      2.910 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 36871 
    [ 2.500,  5.000) = 291833 
    [ 5.000,  7.500) = 922 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      2.908 ms/op
     p(90.0000) =      3.363 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      6.676 ms/op
     p(99.9900) =     16.719 ms/op
     p(99.9990) =     20.175 ms/op
     p(99.9999) =     20.283 ms/op
    p(100.0000) =     20.283 ms/op


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
# Warmup Iteration   1: 4.118 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.174 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.069 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.212 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.975 ms/op
                 getUser·p0.9999: 12.780 ms/op
                 getUser·p1.00:   12.993 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  9.704 ms/op
                 getUser·p0.9999: 16.728 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   3: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.879 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.785 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.110 ms/op
                 getUser·p0.9999: 15.917 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 315525
  mean =      3.042 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 381 
    [ 1.250,  2.500) = 18682 
    [ 2.500,  3.750) = 280308 
    [ 3.750,  5.000) = 14345 
    [ 5.000,  6.250) = 1162 
    [ 6.250,  7.500) = 239 
    [ 7.500,  8.750) = 77 
    [ 8.750, 10.000) = 100 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 47 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.514 ms/op
     p(95.0000) =      3.760 ms/op
     p(99.0000) =      4.669 ms/op
     p(99.9000) =      8.962 ms/op
     p(99.9900) =     16.226 ms/op
     p(99.9990) =     16.903 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 5.265 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.997 ±(99.9%) 0.010 ms/op
Iteration   1: 4.007 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.341 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.062 ms/op
                 listUser·p0.999:  13.507 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 3.948 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.036 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.874 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 20.601 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   3: 3.936 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.020 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.857 ms/op
                 listUser·p0.999:  16.447 ms/op
                 listUser·p0.9999: 22.401 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242074
  mean =      3.963 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3828 
    [ 2.500,  5.000) = 215218 
    [ 5.000,  7.500) = 21639 
    [ 7.500, 10.000) = 945 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 92 
    [15.000, 17.500) = 108 
    [17.500, 20.000) = 122 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.020 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      6.947 ms/op
     p(99.9000) =     15.744 ms/op
     p(99.9900) =     20.846 ms/op
     p(99.9990) =     25.214 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.502 ± 1.803  ops/ms
ClientGrpc.existUser                       thrpt       3  10.924 ± 3.219  ops/ms
ClientGrpc.getUser                         thrpt       3  10.323 ± 2.906  ops/ms
ClientGrpc.listUser                        thrpt       3   7.908 ± 1.730  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.896   ms/op
ClientGrpc.existUser                        avgt       3   2.962 ± 0.291   ms/op
ClientGrpc.getUser                          avgt       3   3.062 ± 0.448   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.367   ms/op
ClientGrpc.createUser                     sample  313234   3.065 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.669           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.230           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.119           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          31.850           ms/op
ClientGrpc.existUser                      sample  329877   2.910 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.598           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.676           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.719           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.283           ms/op
ClientGrpc.getUser                        sample  315525   3.042 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.514           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.669           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.962           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.226           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.924           ms/op
ClientGrpc.listUser                       sample  242074   3.963 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.020           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.947           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.744           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.846           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.330           ms/op
