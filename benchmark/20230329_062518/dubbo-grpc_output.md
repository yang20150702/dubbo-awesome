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
# Warmup Iteration   1: 3.895 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.963 ops/ms
Iteration   1: 10.313 ops/ms
Iteration   2: 10.768 ops/ms
Iteration   3: 10.484 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.522 ±(99.9%) 4.190 ops/ms [Average]
  (min, avg, max) = (10.313, 10.522, 10.768), stdev = 0.230
  CI (99.9%): [6.332, 14.712] (assumes normal distribution)


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
# Warmup Iteration   1: 7.379 ops/ms
# Warmup Iteration   2: 10.536 ops/ms
# Warmup Iteration   3: 10.839 ops/ms
Iteration   1: 10.831 ops/ms
Iteration   2: 10.940 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.862 ±(99.9%) 1.250 ops/ms [Average]
  (min, avg, max) = (10.814, 10.862, 10.940), stdev = 0.069
  CI (99.9%): [9.612, 12.112] (assumes normal distribution)


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
# Warmup Iteration   1: 7.071 ops/ms
# Warmup Iteration   2: 10.204 ops/ms
# Warmup Iteration   3: 10.372 ops/ms
Iteration   1: 10.597 ops/ms
Iteration   2: 10.513 ops/ms
Iteration   3: 10.443 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.518 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (10.443, 10.518, 10.597), stdev = 0.077
  CI (99.9%): [9.108, 11.928] (assumes normal distribution)


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
# Warmup Iteration   1: 5.159 ops/ms
# Warmup Iteration   2: 7.762 ops/ms
# Warmup Iteration   3: 8.086 ops/ms
Iteration   1: 8.049 ops/ms
Iteration   2: 8.163 ops/ms
Iteration   3: 8.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.084 ±(99.9%) 1.252 ops/ms [Average]
  (min, avg, max) = (8.040, 8.084, 8.163), stdev = 0.069
  CI (99.9%): [6.833, 9.336] (assumes normal distribution)


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
# Warmup Iteration   1: 4.100 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.020 ±(99.9%) 0.004 ms/op
Iteration   1: 3.026 ±(99.9%) 0.002 ms/op
Iteration   2: 3.045 ±(99.9%) 0.001 ms/op
Iteration   3: 3.098 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.057 ±(99.9%) 0.682 ms/op [Average]
  (min, avg, max) = (3.026, 3.057, 3.098), stdev = 0.037
  CI (99.9%): [2.375, 3.738] (assumes normal distribution)


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
# Warmup Iteration   1: 3.666 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.035 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.934 ±(99.9%) 0.003 ms/op
Iteration   1: 2.903 ±(99.9%) 0.002 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.890 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.908 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (2.890, 2.908, 2.933), stdev = 0.022
  CI (99.9%): [2.508, 3.309] (assumes normal distribution)


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
# Warmup Iteration   1: 4.108 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.190 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.004 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.031 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.005 ±(99.9%) 0.576 ms/op [Average]
  (min, avg, max) = (2.970, 3.005, 3.031), stdev = 0.032
  CI (99.9%): [2.429, 3.581] (assumes normal distribution)


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
# Warmup Iteration   1: 5.586 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.072 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.020 ms/op
Iteration   1: 3.939 ±(99.9%) 0.042 ms/op
Iteration   2: 3.968 ±(99.9%) 0.016 ms/op
Iteration   3: 3.837 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.915 ±(99.9%) 1.257 ms/op [Average]
  (min, avg, max) = (3.837, 3.915, 3.968), stdev = 0.069
  CI (99.9%): [2.657, 5.172] (assumes normal distribution)


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
# Warmup Iteration   1: 4.423 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.006 ms/op
Iteration   1: 2.990 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.766 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.559 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  7.277 ms/op
                 createUser·p0.9999: 13.555 ms/op
                 createUser·p1.00:   13.812 ms/op

Iteration   2: 3.088 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  8.674 ms/op
                 createUser·p0.9999: 14.778 ms/op
                 createUser·p1.00:   15.090 ms/op

Iteration   3: 3.079 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.843 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.538 ms/op
                 createUser·p0.999:  13.238 ms/op
                 createUser·p0.9999: 18.469 ms/op
                 createUser·p1.00:   19.005 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314338
  mean =      3.052 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 766 
    [ 1.250,  2.500) = 15818 
    [ 2.500,  3.750) = 283446 
    [ 3.750,  5.000) = 12799 
    [ 5.000,  6.250) = 680 
    [ 6.250,  7.500) = 365 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 61 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 65 
    [13.750, 15.000) = 65 
    [15.000, 16.250) = 15 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 33 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.715 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.842 ms/op
     p(99.9900) =     18.008 ms/op
     p(99.9990) =     18.813 ms/op
     p(99.9999) =     19.005 ms/op
    p(100.0000) =     19.005 ms/op


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
# Warmup Iteration   1: 4.103 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.061 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.005 ms/op
Iteration   1: 2.909 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.778 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  5.873 ms/op
                 existUser·p0.9999: 18.350 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   2: 2.917 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.629 ms/op
                 existUser·p0.99:   4.100 ms/op
                 existUser·p0.999:  6.713 ms/op
                 existUser·p0.9999: 13.861 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   3: 2.943 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.794 ms/op
                 existUser·p0.50:   2.925 ms/op
                 existUser·p0.90:   3.379 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  9.978 ms/op
                 existUser·p0.9999: 16.110 ms/op
                 existUser·p1.00:   16.482 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328381
  mean =      2.923 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 919 
    [ 1.250,  2.500) = 36458 
    [ 2.500,  3.750) = 281758 
    [ 3.750,  5.000) = 8366 
    [ 5.000,  6.250) = 383 
    [ 6.250,  7.500) = 172 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 57 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 74 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.609 ms/op
     p(99.0000) =      4.104 ms/op
     p(99.9000) =      7.465 ms/op
     p(99.9900) =     16.652 ms/op
     p(99.9990) =     18.800 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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
# Warmup Iteration   1: 4.314 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.150 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.486 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  11.606 ms/op
                 getUser·p0.9999: 20.975 ms/op
                 getUser·p1.00:   21.201 ms/op

Iteration   2: 3.071 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.801 ms/op
                 getUser·p0.99:   4.583 ms/op
                 getUser·p0.999:  7.870 ms/op
                 getUser·p0.9999: 15.499 ms/op
                 getUser·p1.00:   15.991 ms/op

Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.923 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.316 ms/op
                 getUser·p0.9999: 22.041 ms/op
                 getUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312168
  mean =      3.073 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16974 
    [ 2.500,  5.000) = 293657 
    [ 5.000,  7.500) = 1164 
    [ 7.500, 10.000) = 114 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.921 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.500 ms/op
     p(99.9000) =      8.694 ms/op
     p(99.9900) =     21.795 ms/op
     p(99.9990) =     22.249 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


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
# Warmup Iteration   1: 5.351 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.027 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.002 ±(99.9%) 0.011 ms/op
Iteration   1: 3.957 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.288 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.693 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  12.684 ms/op
                 listUser·p0.9999: 21.654 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 3.965 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.460 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   5.087 ms/op
                 listUser·p0.95:   5.587 ms/op
                 listUser·p0.99:   6.827 ms/op
                 listUser·p0.999:  15.112 ms/op
                 listUser·p0.9999: 18.471 ms/op
                 listUser·p1.00:   20.021 ms/op

Iteration   3: 3.950 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.857 ms/op
                 listUser·p0.99:   6.824 ms/op
                 listUser·p0.999:  16.253 ms/op
                 listUser·p0.9999: 21.457 ms/op
                 listUser·p1.00:   22.381 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242540
  mean =      3.957 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4234 
    [ 2.500,  5.000) = 215198 
    [ 5.000,  7.500) = 21884 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 136 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.460 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.956 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.573 ms/op
     p(99.9900) =     21.389 ms/op
     p(99.9990) =     22.306 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.522 ± 4.190  ops/ms
ClientGrpc.existUser                       thrpt       3  10.862 ± 1.250  ops/ms
ClientGrpc.getUser                         thrpt       3  10.518 ± 1.410  ops/ms
ClientGrpc.listUser                        thrpt       3   8.084 ± 1.252  ops/ms
ClientGrpc.createUser                       avgt       3   3.057 ± 0.682   ms/op
ClientGrpc.existUser                        avgt       3   2.908 ± 0.401   ms/op
ClientGrpc.getUser                          avgt       3   3.005 ± 0.576   ms/op
ClientGrpc.listUser                         avgt       3   3.915 ± 1.257   ms/op
ClientGrpc.createUser                     sample  314338   3.052 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.766           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.366           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.842           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.008           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.005           ms/op
ClientGrpc.existUser                      sample  328381   2.923 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.772           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.408           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.609           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.104           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.465           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.652           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.874           ms/op
ClientGrpc.getUser                        sample  312168   3.073 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.921           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.500           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.694           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.795           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.413           ms/op
ClientGrpc.listUser                       sample  242540   3.957 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.460           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.809           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.573           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.389           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
