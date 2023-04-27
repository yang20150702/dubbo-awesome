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
# Warmup Iteration   1: 2.614 ops/ms
# Warmup Iteration   2: 5.867 ops/ms
# Warmup Iteration   3: 7.288 ops/ms
Iteration   1: 7.674 ops/ms
Iteration   2: 7.720 ops/ms
Iteration   3: 7.487 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.627 ±(99.9%) 2.258 ops/ms [Average]
  (min, avg, max) = (7.487, 7.627, 7.720), stdev = 0.124
  CI (99.9%): [5.369, 9.885] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.893 ops/ms
# Warmup Iteration   2: 7.107 ops/ms
# Warmup Iteration   3: 7.808 ops/ms
Iteration   1: 8.490 ops/ms
Iteration   2: 8.227 ops/ms
Iteration   3: 8.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.380 ±(99.9%) 2.494 ops/ms [Average]
  (min, avg, max) = (8.227, 8.380, 8.490), stdev = 0.137
  CI (99.9%): [5.886, 10.875] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.399 ops/ms
# Warmup Iteration   2: 6.832 ops/ms
# Warmup Iteration   3: 7.241 ops/ms
Iteration   1: 7.127 ops/ms
Iteration   2: 7.591 ops/ms
Iteration   3: 7.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.368 ±(99.9%) 4.238 ops/ms [Average]
  (min, avg, max) = (7.127, 7.368, 7.591), stdev = 0.232
  CI (99.9%): [3.130, 11.606] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.572 ops/ms
# Warmup Iteration   2: 5.295 ops/ms
# Warmup Iteration   3: 5.767 ops/ms
Iteration   1: 5.727 ops/ms
Iteration   2: 5.888 ops/ms
Iteration   3: 5.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.790 ±(99.9%) 1.578 ops/ms [Average]
  (min, avg, max) = (5.727, 5.790, 5.888), stdev = 0.087
  CI (99.9%): [4.211, 7.368] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.865 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.622 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.617 ±(99.9%) 0.013 ms/op
Iteration   1: 4.545 ±(99.9%) 0.004 ms/op
Iteration   2: 4.539 ±(99.9%) 0.004 ms/op
Iteration   3: 4.620 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.568 ±(99.9%) 0.821 ms/op [Average]
  (min, avg, max) = (4.539, 4.568, 4.620), stdev = 0.045
  CI (99.9%): [3.747, 5.389] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.489 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 4.426 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.091 ±(99.9%) 0.003 ms/op
Iteration   1: 3.930 ±(99.9%) 0.005 ms/op
Iteration   2: 4.173 ±(99.9%) 0.002 ms/op
Iteration   3: 4.236 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.113 ±(99.9%) 2.952 ms/op [Average]
  (min, avg, max) = (3.930, 4.113, 4.236), stdev = 0.162
  CI (99.9%): [1.161, 7.065] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.540 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.608 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.434 ±(99.9%) 0.006 ms/op
Iteration   1: 4.310 ±(99.9%) 0.004 ms/op
Iteration   2: 4.418 ±(99.9%) 0.002 ms/op
Iteration   3: 4.454 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.394 ±(99.9%) 1.368 ms/op [Average]
  (min, avg, max) = (4.310, 4.394, 4.454), stdev = 0.075
  CI (99.9%): [3.026, 5.762] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.525 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 6.106 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.621 ±(99.9%) 0.014 ms/op
Iteration   1: 5.752 ±(99.9%) 0.017 ms/op
Iteration   2: 5.931 ±(99.9%) 0.022 ms/op
Iteration   3: 5.591 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.758 ±(99.9%) 3.105 ms/op [Average]
  (min, avg, max) = (5.591, 5.758, 5.931), stdev = 0.170
  CI (99.9%): [2.653, 8.863] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.837 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 4.646 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.431 ±(99.9%) 0.014 ms/op
Iteration   1: 4.543 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   4.399 ms/op
                 createUser·p0.90:   5.743 ms/op
                 createUser·p0.95:   6.234 ms/op
                 createUser·p0.99:   8.061 ms/op
                 createUser·p0.999:  12.731 ms/op
                 createUser·p0.9999: 29.911 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   2: 4.360 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.202 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.390 ms/op
                 createUser·p0.95:   5.915 ms/op
                 createUser·p0.99:   7.717 ms/op
                 createUser·p0.999:  11.735 ms/op
                 createUser·p0.9999: 20.021 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 4.497 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.383 ms/op
                 createUser·p0.90:   5.677 ms/op
                 createUser·p0.95:   6.119 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  14.926 ms/op
                 createUser·p0.9999: 21.620 ms/op
                 createUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 214952
  mean =      4.465 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4246 
    [ 2.500,  5.000) = 161949 
    [ 5.000,  7.500) = 46141 
    [ 7.500, 10.000) = 1988 
    [10.000, 12.500) = 354 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      4.334 ms/op
     p(90.0000) =      5.620 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.791 ms/op
     p(99.9000) =     13.255 ms/op
     p(99.9900) =     28.787 ms/op
     p(99.9990) =     30.174 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.890 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.450 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.191 ±(99.9%) 0.013 ms/op
Iteration   1: 4.086 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.024 ms/op
                 existUser·p0.50:   3.969 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.579 ms/op
                 existUser·p0.99:   7.365 ms/op
                 existUser·p0.999:  10.264 ms/op
                 existUser·p0.9999: 17.662 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.472 ms/op
                 existUser·p0.99:   7.193 ms/op
                 existUser·p0.999:  13.058 ms/op
                 existUser·p0.9999: 20.382 ms/op
                 existUser·p1.00:   20.447 ms/op

Iteration   3: 3.962 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.126 ms/op
                 existUser·p0.50:   3.854 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   6.832 ms/op
                 existUser·p0.999:  9.643 ms/op
                 existUser·p0.9999: 22.053 ms/op
                 existUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 238788
  mean =      4.018 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6707 
    [ 2.500,  5.000) = 208300 
    [ 5.000,  7.500) = 21874 
    [ 7.500, 10.000) = 1553 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 72 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.024 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.480 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     11.583 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.499 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.633 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.580 ±(99.9%) 0.015 ms/op
Iteration   1: 4.478 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.317 ms/op
                 getUser·p0.50:   4.342 ms/op
                 getUser·p0.90:   5.579 ms/op
                 getUser·p0.95:   6.144 ms/op
                 getUser·p0.99:   8.118 ms/op
                 getUser·p0.999:  11.970 ms/op
                 getUser·p0.9999: 19.577 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 4.212 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.251 ms/op
                 getUser·p0.95:   5.825 ms/op
                 getUser·p0.99:   7.422 ms/op
                 getUser·p0.999:  12.026 ms/op
                 getUser·p0.9999: 31.372 ms/op
                 getUser·p1.00:   34.144 ms/op

Iteration   3: 4.133 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.184 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   7.045 ms/op
                 getUser·p0.999:  13.412 ms/op
                 getUser·p0.9999: 30.015 ms/op
                 getUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 224898
  mean =      4.269 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4839 
    [ 2.500,  5.000) = 183822 
    [ 5.000,  7.500) = 33842 
    [ 7.500, 10.000) = 1844 
    [10.000, 12.500) = 364 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 12 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      4.153 ms/op
     p(90.0000) =      5.341 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.578 ms/op
     p(99.9000) =     12.124 ms/op
     p(99.9900) =     30.982 ms/op
     p(99.9990) =     31.736 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 7.222 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.519 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.185 ±(99.9%) 0.020 ms/op
Iteration   1: 5.251 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.602 ms/op
                 listUser·p0.50:   4.956 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  16.979 ms/op
                 listUser·p0.9999: 26.533 ms/op
                 listUser·p1.00:   27.492 ms/op

Iteration   2: 4.779 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   4.497 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.274 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  16.928 ms/op
                 listUser·p0.9999: 29.884 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   3: 5.267 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.618 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   7.012 ms/op
                 listUser·p0.95:   7.915 ms/op
                 listUser·p0.99:   10.368 ms/op
                 listUser·p0.999:  19.754 ms/op
                 listUser·p0.9999: 31.687 ms/op
                 listUser·p1.00:   32.473 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 188691
  mean =      5.089 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 681 
    [ 2.500,  5.000) = 108393 
    [ 5.000,  7.500) = 68434 
    [ 7.500, 10.000) = 9307 
    [10.000, 12.500) = 1309 
    [12.500, 15.000) = 278 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 52 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      4.792 ms/op
     p(90.0000) =      6.832 ms/op
     p(95.0000) =      7.717 ms/op
     p(99.0000) =      9.994 ms/op
     p(99.9000) =     19.048 ms/op
     p(99.9900) =     30.085 ms/op
     p(99.9990) =     32.444 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.627 ± 2.258  ops/ms
ClientGrpc.existUser                       thrpt       3   8.380 ± 2.494  ops/ms
ClientGrpc.getUser                         thrpt       3   7.368 ± 4.238  ops/ms
ClientGrpc.listUser                        thrpt       3   5.790 ± 1.578  ops/ms
ClientGrpc.createUser                       avgt       3   4.568 ± 0.821   ms/op
ClientGrpc.existUser                        avgt       3   4.113 ± 2.952   ms/op
ClientGrpc.getUser                          avgt       3   4.394 ± 1.368   ms/op
ClientGrpc.listUser                         avgt       3   5.758 ± 3.105   ms/op
ClientGrpc.createUser                     sample  214952   4.465 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.981           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.620           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.103           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.255           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.787           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.867           ms/op
ClientGrpc.existUser                      sample  238788   4.018 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.024           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.908           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.997           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.480           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.160           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.583           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.414           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.151           ms/op
ClientGrpc.getUser                        sample  224898   4.269 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.155           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.153           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.341           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.874           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.578           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.124           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.982           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          34.144           ms/op
ClientGrpc.listUser                       sample  188691   5.089 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.832           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.717           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.994           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.048           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.085           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.473           ms/op
