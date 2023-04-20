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
# Warmup Iteration   1: 2.386 ops/ms
# Warmup Iteration   2: 5.691 ops/ms
# Warmup Iteration   3: 7.246 ops/ms
Iteration   1: 7.639 ops/ms
Iteration   2: 7.650 ops/ms
Iteration   3: 7.338 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.542 ±(99.9%) 3.233 ops/ms [Average]
  (min, avg, max) = (7.338, 7.542, 7.650), stdev = 0.177
  CI (99.9%): [4.310, 10.775] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.124 ops/ms
# Warmup Iteration   2: 7.880 ops/ms
# Warmup Iteration   3: 7.997 ops/ms
Iteration   1: 7.824 ops/ms
Iteration   2: 7.679 ops/ms
Iteration   3: 7.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.716 ±(99.9%) 1.721 ops/ms [Average]
  (min, avg, max) = (7.647, 7.716, 7.824), stdev = 0.094
  CI (99.9%): [5.996, 9.437] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.228 ops/ms
# Warmup Iteration   2: 6.979 ops/ms
# Warmup Iteration   3: 7.670 ops/ms
Iteration   1: 7.790 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.069 ±(99.9%) 4.594 ops/ms [Average]
  (min, avg, max) = (7.790, 8.069, 8.279), stdev = 0.252
  CI (99.9%): [3.475, 12.664] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.575 ops/ms
# Warmup Iteration   2: 5.189 ops/ms
# Warmup Iteration   3: 5.538 ops/ms
Iteration   1: 5.534 ops/ms
Iteration   2: 5.950 ops/ms
Iteration   3: 5.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.792 ±(99.9%) 4.105 ops/ms [Average]
  (min, avg, max) = (5.534, 5.792, 5.950), stdev = 0.225
  CI (99.9%): [1.687, 9.896] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.257 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.461 ±(99.9%) 0.004 ms/op
Iteration   1: 4.182 ±(99.9%) 0.003 ms/op
Iteration   2: 4.002 ±(99.9%) 0.005 ms/op
Iteration   3: 4.143 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.109 ±(99.9%) 1.733 ms/op [Average]
  (min, avg, max) = (4.002, 4.109, 4.182), stdev = 0.095
  CI (99.9%): [2.376, 5.842] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.042 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.722 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.387 ±(99.9%) 0.008 ms/op
Iteration   1: 4.229 ±(99.9%) 0.003 ms/op
Iteration   2: 4.064 ±(99.9%) 0.003 ms/op
Iteration   3: 4.019 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.104 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (4.019, 4.104, 4.229), stdev = 0.111
  CI (99.9%): [2.084, 6.125] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.572 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.395 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.318 ±(99.9%) 0.014 ms/op
Iteration   1: 4.308 ±(99.9%) 0.005 ms/op
Iteration   2: 4.293 ±(99.9%) 0.004 ms/op
Iteration   3: 4.212 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.271 ±(99.9%) 0.946 ms/op [Average]
  (min, avg, max) = (4.212, 4.271, 4.308), stdev = 0.052
  CI (99.9%): [3.325, 5.217] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.525 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.875 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.167 ±(99.9%) 0.030 ms/op
Iteration   1: 5.277 ±(99.9%) 0.017 ms/op
Iteration   2: 5.322 ±(99.9%) 0.012 ms/op
Iteration   3: 5.650 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.416 ±(99.9%) 3.712 ms/op [Average]
  (min, avg, max) = (5.277, 5.416, 5.650), stdev = 0.203
  CI (99.9%): [1.704, 9.128] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.875 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.421 ±(99.9%) 0.014 ms/op
Iteration   1: 4.217 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   4.088 ms/op
                 createUser·p0.90:   5.382 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.604 ms/op
                 createUser·p0.999:  13.213 ms/op
                 createUser·p0.9999: 21.752 ms/op
                 createUser·p1.00:   22.086 ms/op

Iteration   2: 4.256 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   8.282 ms/op
                 createUser·p0.999:  11.580 ms/op
                 createUser·p0.9999: 22.544 ms/op
                 createUser·p1.00:   22.872 ms/op

Iteration   3: 4.369 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.051 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.439 ms/op
                 createUser·p0.95:   5.898 ms/op
                 createUser·p0.99:   7.528 ms/op
                 createUser·p0.999:  12.993 ms/op
                 createUser·p0.9999: 26.236 ms/op
                 createUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 224290
  mean =      4.280 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5941 
    [ 2.500,  5.000) = 181739 
    [ 5.000,  7.500) = 33988 
    [ 7.500, 10.000) = 2068 
    [10.000, 12.500) = 316 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.366 ms/op
     p(95.0000) =      5.857 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     12.796 ms/op
     p(99.9900) =     25.503 ms/op
     p(99.9990) =     26.698 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.737 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.699 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.218 ±(99.9%) 0.011 ms/op
Iteration   1: 3.946 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.886 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   7.176 ms/op
                 existUser·p0.999:  11.740 ms/op
                 existUser·p0.9999: 16.452 ms/op
                 existUser·p1.00:   19.431 ms/op

Iteration   2: 4.085 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.872 ms/op
                 existUser·p0.50:   3.961 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 18.858 ms/op
                 existUser·p1.00:   19.628 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.938 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.713 ms/op
                 existUser·p0.999:  11.933 ms/op
                 existUser·p0.9999: 22.033 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238075
  mean =      4.032 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6658 
    [ 2.500,  5.000) = 210313 
    [ 5.000,  7.500) = 18800 
    [ 7.500, 10.000) = 1842 
    [10.000, 12.500) = 249 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      3.928 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.390 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     12.008 ms/op
     p(99.9900) =     18.854 ms/op
     p(99.9990) =     22.565 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.691 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.613 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.012 ms/op
Iteration   1: 4.289 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   4.129 ms/op
                 getUser·p0.90:   5.464 ms/op
                 getUser·p0.95:   5.988 ms/op
                 getUser·p0.99:   8.102 ms/op
                 getUser·p0.999:  10.769 ms/op
                 getUser·p0.9999: 15.090 ms/op
                 getUser·p1.00:   15.368 ms/op

Iteration   2: 4.261 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.067 ms/op
                 getUser·p0.50:   4.157 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.332 ms/op
                 getUser·p0.999:  14.252 ms/op
                 getUser·p0.9999: 17.825 ms/op
                 getUser·p1.00:   19.169 ms/op

Iteration   3: 4.401 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.957 ms/op
                 getUser·p0.50:   4.268 ms/op
                 getUser·p0.90:   5.423 ms/op
                 getUser·p0.95:   5.874 ms/op
                 getUser·p0.99:   8.066 ms/op
                 getUser·p0.999:  12.763 ms/op
                 getUser·p0.9999: 27.835 ms/op
                 getUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 222507
  mean =      4.316 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4203 
    [ 2.500,  5.000) = 181166 
    [ 5.000,  7.500) = 34364 
    [ 7.500, 10.000) = 2228 
    [10.000, 12.500) = 321 
    [12.500, 15.000) = 116 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      4.182 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      7.873 ms/op
     p(99.9000) =     12.550 ms/op
     p(99.9900) =     27.419 ms/op
     p(99.9990) =     27.886 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.902 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.800 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.485 ±(99.9%) 0.020 ms/op
Iteration   1: 5.246 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.737 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   7.078 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.355 ms/op
                 listUser·p0.999:  16.123 ms/op
                 listUser·p0.9999: 19.268 ms/op
                 listUser·p1.00:   19.726 ms/op

Iteration   2: 5.375 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   8.184 ms/op
                 listUser·p0.99:   10.568 ms/op
                 listUser·p0.999:  16.659 ms/op
                 listUser·p0.9999: 19.235 ms/op
                 listUser·p1.00:   20.972 ms/op

Iteration   3: 5.377 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.544 ms/op
                 listUser·p0.50:   5.071 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.118 ms/op
                 listUser·p0.99:   10.584 ms/op
                 listUser·p0.999:  22.545 ms/op
                 listUser·p0.9999: 31.067 ms/op
                 listUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 179977
  mean =      5.332 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 266 
    [ 2.500,  5.000) = 87263 
    [ 5.000,  7.500) = 78390 
    [ 7.500, 10.000) = 11634 
    [10.000, 12.500) = 1737 
    [12.500, 15.000) = 340 
    [15.000, 17.500) = 177 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.544 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      7.119 ms/op
     p(95.0000) =      8.143 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     17.106 ms/op
     p(99.9900) =     28.836 ms/op
     p(99.9990) =     32.762 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.542 ± 3.233  ops/ms
ClientGrpc.existUser                       thrpt       3   7.716 ± 1.721  ops/ms
ClientGrpc.getUser                         thrpt       3   8.069 ± 4.594  ops/ms
ClientGrpc.listUser                        thrpt       3   5.792 ± 4.105  ops/ms
ClientGrpc.createUser                       avgt       3   4.109 ± 1.733   ms/op
ClientGrpc.existUser                        avgt       3   4.104 ± 2.021   ms/op
ClientGrpc.getUser                          avgt       3   4.271 ± 0.946   ms/op
ClientGrpc.listUser                         avgt       3   5.416 ± 3.712   ms/op
ClientGrpc.createUser                     sample  224290   4.280 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.977           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.157           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.366           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.857           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.750           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.796           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.503           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.739           ms/op
ClientGrpc.existUser                      sample  238075   4.032 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.837           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.928           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.390           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.008           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.854           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.069           ms/op
ClientGrpc.getUser                        sample  222507   4.316 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.896           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.182           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.358           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.865           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.873           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.550           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.419           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          27.951           ms/op
ClientGrpc.listUser                       sample  179977   5.332 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.544           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.030           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.119           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.143           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.519           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.106           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          28.836           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.997           ms/op
