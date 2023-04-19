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
# Warmup Iteration   1: 2.356 ops/ms
# Warmup Iteration   2: 5.542 ops/ms
# Warmup Iteration   3: 7.122 ops/ms
Iteration   1: 7.596 ops/ms
Iteration   2: 7.489 ops/ms
Iteration   3: 7.647 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.578 ±(99.9%) 1.470 ops/ms [Average]
  (min, avg, max) = (7.489, 7.578, 7.647), stdev = 0.081
  CI (99.9%): [6.108, 9.048] (assumes normal distribution)


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
# Warmup Iteration   1: 4.541 ops/ms
# Warmup Iteration   2: 7.309 ops/ms
# Warmup Iteration   3: 7.680 ops/ms
Iteration   1: 7.461 ops/ms
Iteration   2: 7.597 ops/ms
Iteration   3: 7.800 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.619 ±(99.9%) 3.120 ops/ms [Average]
  (min, avg, max) = (7.461, 7.619, 7.800), stdev = 0.171
  CI (99.9%): [4.499, 10.739] (assumes normal distribution)


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
# Warmup Iteration   1: 4.216 ops/ms
# Warmup Iteration   2: 6.803 ops/ms
# Warmup Iteration   3: 7.285 ops/ms
Iteration   1: 7.209 ops/ms
Iteration   2: 7.585 ops/ms
Iteration   3: 7.549 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.447 ±(99.9%) 3.777 ops/ms [Average]
  (min, avg, max) = (7.209, 7.447, 7.585), stdev = 0.207
  CI (99.9%): [3.670, 11.225] (assumes normal distribution)


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
# Warmup Iteration   1: 4.371 ops/ms
# Warmup Iteration   2: 5.317 ops/ms
# Warmup Iteration   3: 5.779 ops/ms
Iteration   1: 5.649 ops/ms
Iteration   2: 5.787 ops/ms
Iteration   3: 5.809 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.748 ±(99.9%) 1.581 ops/ms [Average]
  (min, avg, max) = (5.649, 5.748, 5.809), stdev = 0.087
  CI (99.9%): [4.167, 7.329] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.596 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.572 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.401 ±(99.9%) 0.029 ms/op
Iteration   1: 4.193 ±(99.9%) 0.004 ms/op
Iteration   2: 4.297 ±(99.9%) 0.004 ms/op
Iteration   3: 4.256 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.249 ±(99.9%) 0.956 ms/op [Average]
  (min, avg, max) = (4.193, 4.249, 4.297), stdev = 0.052
  CI (99.9%): [3.293, 5.205] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.052 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.182 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.003 ms/op
Iteration   1: 3.836 ±(99.9%) 0.003 ms/op
Iteration   2: 3.871 ±(99.9%) 0.003 ms/op
Iteration   3: 3.786 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.831 ±(99.9%) 0.779 ms/op [Average]
  (min, avg, max) = (3.786, 3.831, 3.871), stdev = 0.043
  CI (99.9%): [3.052, 4.610] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.349 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.379 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.015 ms/op
Iteration   1: 4.073 ±(99.9%) 0.004 ms/op
Iteration   2: 4.094 ±(99.9%) 0.004 ms/op
Iteration   3: 4.312 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.160 ±(99.9%) 2.420 ms/op [Average]
  (min, avg, max) = (4.073, 4.160, 4.312), stdev = 0.133
  CI (99.9%): [1.740, 6.580] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.083 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 5.747 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.406 ±(99.9%) 0.014 ms/op
Iteration   1: 5.390 ±(99.9%) 0.010 ms/op
Iteration   2: 5.299 ±(99.9%) 0.015 ms/op
Iteration   3: 5.541 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.410 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (5.299, 5.410, 5.541), stdev = 0.122
  CI (99.9%): [3.182, 7.638] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.706 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.843 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.559 ±(99.9%) 0.015 ms/op
Iteration   1: 4.408 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.354 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.144 ms/op
                 createUser·p0.99:   7.619 ms/op
                 createUser·p0.999:  12.921 ms/op
                 createUser·p0.9999: 20.118 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   2: 4.543 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.035 ms/op
                 createUser·p0.50:   4.456 ms/op
                 createUser·p0.90:   5.669 ms/op
                 createUser·p0.95:   6.046 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  10.086 ms/op
                 createUser·p0.9999: 18.544 ms/op
                 createUser·p1.00:   18.809 ms/op

Iteration   3: 4.441 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.178 ms/op
                 createUser·p0.50:   4.293 ms/op
                 createUser·p0.90:   5.464 ms/op
                 createUser·p0.95:   5.939 ms/op
                 createUser·p0.99:   7.662 ms/op
                 createUser·p0.999:  13.534 ms/op
                 createUser·p0.9999: 24.164 ms/op
                 createUser·p1.00:   33.063 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214958
  mean =      4.463 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3928 
    [ 2.500,  5.000) = 162753 
    [ 5.000,  7.500) = 46096 
    [ 7.500, 10.000) = 1732 
    [10.000, 12.500) = 222 
    [12.500, 15.000) = 91 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.035 ms/op
     p(50.0000) =      4.350 ms/op
     p(90.0000) =      5.603 ms/op
     p(95.0000) =      6.054 ms/op
     p(99.0000) =      7.520 ms/op
     p(99.9000) =     12.633 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     32.547 ms/op
     p(99.9999) =     33.063 ms/op
    p(100.0000) =     33.063 ms/op


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
# Warmup Iteration   1: 6.074 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.272 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.153 ±(99.9%) 0.010 ms/op
Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.137 ms/op
                 existUser·p0.50:   4.096 ms/op
                 existUser·p0.90:   5.276 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   6.908 ms/op
                 existUser·p0.999:  10.514 ms/op
                 existUser·p0.9999: 15.571 ms/op
                 existUser·p1.00:   15.958 ms/op

Iteration   2: 4.098 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.998 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.513 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  10.501 ms/op
                 existUser·p0.9999: 29.936 ms/op
                 existUser·p1.00:   30.278 ms/op

Iteration   3: 4.221 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   4.121 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.538 ms/op
                 existUser·p0.99:   7.152 ms/op
                 existUser·p0.999:  12.718 ms/op
                 existUser·p0.9999: 18.724 ms/op
                 existUser·p1.00:   20.742 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231248
  mean =      4.151 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9145 
    [ 2.500,  5.000) = 192451 
    [ 5.000,  7.500) = 27883 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 151 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.067 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.053 ms/op
     p(99.9000) =     11.121 ms/op
     p(99.9900) =     21.590 ms/op
     p(99.9990) =     30.235 ms/op
     p(99.9999) =     30.278 ms/op
    p(100.0000) =     30.278 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.547 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.574 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.456 ±(99.9%) 0.014 ms/op
Iteration   1: 4.348 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.092 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.775 ms/op
                 getUser·p0.99:   7.403 ms/op
                 getUser·p0.999:  12.393 ms/op
                 getUser·p0.9999: 16.338 ms/op
                 getUser·p1.00:   16.908 ms/op

Iteration   2: 4.337 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.126 ms/op
                 getUser·p0.50:   4.252 ms/op
                 getUser·p0.90:   5.358 ms/op
                 getUser·p0.95:   5.833 ms/op
                 getUser·p0.99:   7.102 ms/op
                 getUser·p0.999:  13.377 ms/op
                 getUser·p0.9999: 19.976 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 4.290 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.260 ms/op
                 getUser·p0.50:   4.227 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.489 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  13.871 ms/op
                 getUser·p0.9999: 20.846 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 221965
  mean =      4.325 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3191 
    [ 2.500,  5.000) = 184188 
    [ 5.000,  7.500) = 32952 
    [ 7.500, 10.000) = 1250 
    [10.000, 12.500) = 140 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      4.235 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      7.111 ms/op
     p(99.9000) =     13.223 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     20.997 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 7.006 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.296 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.559 ±(99.9%) 0.019 ms/op
Iteration   1: 5.504 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.954 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  16.210 ms/op
                 listUser·p0.9999: 18.815 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 5.569 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.298 ms/op
                 listUser·p0.50:   5.325 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.094 ms/op
                 listUser·p0.99:   10.301 ms/op
                 listUser·p0.999:  17.743 ms/op
                 listUser·p0.9999: 20.095 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   3: 5.533 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.955 ms/op
                 listUser·p0.95:   7.881 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  21.332 ms/op
                 listUser·p0.9999: 24.507 ms/op
                 listUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173480
  mean =      5.535 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 61097 
    [ 5.000,  7.500) = 100008 
    [ 7.500, 10.000) = 10517 
    [10.000, 12.500) = 1238 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.298 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.045 ms/op
     p(95.0000) =      7.987 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     23.713 ms/op
     p(99.9990) =     25.225 ms/op
     p(99.9999) =     25.297 ms/op
    p(100.0000) =     25.297 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.578 ± 1.470  ops/ms
ClientGrpc.existUser                       thrpt       3   7.619 ± 3.120  ops/ms
ClientGrpc.getUser                         thrpt       3   7.447 ± 3.777  ops/ms
ClientGrpc.listUser                        thrpt       3   5.748 ± 1.581  ops/ms
ClientGrpc.createUser                       avgt       3   4.249 ± 0.956   ms/op
ClientGrpc.existUser                        avgt       3   3.831 ± 0.779   ms/op
ClientGrpc.getUser                          avgt       3   4.160 ± 2.420   ms/op
ClientGrpc.listUser                         avgt       3   5.410 ± 2.228   ms/op
ClientGrpc.createUser                     sample  214958   4.463 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.035           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.350           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.603           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.054           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.520           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.633           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.184           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.063           ms/op
ClientGrpc.existUser                      sample  231248   4.151 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.931           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.067           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.161           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.053           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.121           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.590           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.278           ms/op
ClientGrpc.getUser                        sample  221965   4.325 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.092           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.235           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.718           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.223           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.087           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.004           ms/op
ClientGrpc.listUser                       sample  173480   5.535 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.298           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.045           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.987           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.043           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.924           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.713           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.297           ms/op
