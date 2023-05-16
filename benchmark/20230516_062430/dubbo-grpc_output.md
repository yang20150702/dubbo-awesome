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
# Warmup Iteration   1: 2.239 ops/ms
# Warmup Iteration   2: 5.158 ops/ms
# Warmup Iteration   3: 7.030 ops/ms
Iteration   1: 6.981 ops/ms
Iteration   2: 7.194 ops/ms
Iteration   3: 7.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.239 ±(99.9%) 5.169 ops/ms [Average]
  (min, avg, max) = (6.981, 7.239, 7.542), stdev = 0.283
  CI (99.9%): [2.070, 12.408] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.386 ops/ms
# Warmup Iteration   2: 7.641 ops/ms
# Warmup Iteration   3: 8.212 ops/ms
Iteration   1: 8.151 ops/ms
Iteration   2: 8.539 ops/ms
Iteration   3: 8.241 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.310 ±(99.9%) 3.704 ops/ms [Average]
  (min, avg, max) = (8.151, 8.310, 8.539), stdev = 0.203
  CI (99.9%): [4.606, 12.014] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.037 ops/ms
# Warmup Iteration   2: 7.000 ops/ms
# Warmup Iteration   3: 7.334 ops/ms
Iteration   1: 7.411 ops/ms
Iteration   2: 7.429 ops/ms
Iteration   3: 7.579 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.473 ±(99.9%) 1.686 ops/ms [Average]
  (min, avg, max) = (7.411, 7.473, 7.579), stdev = 0.092
  CI (99.9%): [5.787, 9.159] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.677 ops/ms
# Warmup Iteration   2: 5.350 ops/ms
# Warmup Iteration   3: 5.799 ops/ms
Iteration   1: 5.699 ops/ms
Iteration   2: 5.857 ops/ms
Iteration   3: 5.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.810 ±(99.9%) 1.775 ops/ms [Average]
  (min, avg, max) = (5.699, 5.810, 5.876), stdev = 0.097
  CI (99.9%): [4.036, 7.585] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.634 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.552 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.253 ±(99.9%) 0.011 ms/op
Iteration   1: 4.158 ±(99.9%) 0.003 ms/op
Iteration   2: 4.275 ±(99.9%) 0.003 ms/op
Iteration   3: 4.073 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.169 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (4.073, 4.169, 4.275), stdev = 0.101
  CI (99.9%): [2.321, 6.016] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.261 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.003 ms/op
Iteration   1: 3.887 ±(99.9%) 0.004 ms/op
Iteration   2: 3.923 ±(99.9%) 0.003 ms/op
Iteration   3: 3.977 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.929 ±(99.9%) 0.822 ms/op [Average]
  (min, avg, max) = (3.887, 3.929, 3.977), stdev = 0.045
  CI (99.9%): [3.107, 4.751] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.435 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.478 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.324 ±(99.9%) 0.005 ms/op
Iteration   1: 4.181 ±(99.9%) 0.002 ms/op
Iteration   2: 4.108 ±(99.9%) 0.004 ms/op
Iteration   3: 4.112 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.134 ±(99.9%) 0.746 ms/op [Average]
  (min, avg, max) = (4.108, 4.134, 4.181), stdev = 0.041
  CI (99.9%): [3.388, 4.879] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.616 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 6.167 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.639 ±(99.9%) 0.010 ms/op
Iteration   1: 5.522 ±(99.9%) 0.015 ms/op
Iteration   2: 5.564 ±(99.9%) 0.013 ms/op
Iteration   3: 5.580 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.556 ±(99.9%) 0.548 ms/op [Average]
  (min, avg, max) = (5.522, 5.556, 5.580), stdev = 0.030
  CI (99.9%): [5.007, 6.104] (assumes normal distribution)


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
# Warmup Iteration   1: 6.290 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 4.503 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.310 ±(99.9%) 0.012 ms/op
Iteration   1: 4.207 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.075 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 16.207 ms/op
                 createUser·p1.00:   16.777 ms/op

Iteration   2: 4.305 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.202 ms/op
                 createUser·p0.90:   5.308 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.176 ms/op
                 createUser·p0.999:  9.915 ms/op
                 createUser·p0.9999: 17.648 ms/op
                 createUser·p1.00:   19.071 ms/op

Iteration   3: 4.350 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.055 ms/op
                 createUser·p0.50:   4.243 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.135 ms/op
                 createUser·p0.999:  12.124 ms/op
                 createUser·p0.9999: 19.671 ms/op
                 createUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 223789
  mean =      4.287 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1977 
    [ 2.500,  5.000) = 186143 
    [ 5.000,  7.500) = 33968 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 204 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.055 ms/op
     p(50.0000) =      4.178 ms/op
     p(90.0000) =      5.276 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     19.202 ms/op
     p(99.9990) =     19.900 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.684 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.398 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.011 ms/op
Iteration   1: 4.213 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   4.100 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.307 ms/op
                 existUser·p0.999:  11.862 ms/op
                 existUser·p0.9999: 31.100 ms/op
                 existUser·p1.00:   31.425 ms/op

Iteration   2: 4.150 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   4.051 ms/op
                 existUser·p0.90:   5.038 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.987 ms/op
                 existUser·p0.999:  12.665 ms/op
                 existUser·p0.9999: 22.333 ms/op
                 existUser·p1.00:   22.643 ms/op

Iteration   3: 4.083 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.881 ms/op
                 existUser·p0.50:   4.030 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.777 ms/op
                 existUser·p0.999:  9.716 ms/op
                 existUser·p0.9999: 25.499 ms/op
                 existUser·p1.00:   25.887 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 231414
  mean =      4.148 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7558 
    [ 2.500,  5.000) = 197266 
    [ 5.000,  7.500) = 24504 
    [ 7.500, 10.000) = 1637 
    [10.000, 12.500) = 286 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 26 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      4.059 ms/op
     p(90.0000) =      5.087 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.332 ms/op
     p(99.9000) =     11.469 ms/op
     p(99.9900) =     28.733 ms/op
     p(99.9990) =     31.359 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.617 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.559 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.014 ms/op
Iteration   1: 4.293 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   4.186 ms/op
                 getUser·p0.90:   5.415 ms/op
                 getUser·p0.95:   5.898 ms/op
                 getUser·p0.99:   8.126 ms/op
                 getUser·p0.999:  14.409 ms/op
                 getUser·p0.9999: 17.760 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 4.264 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   4.166 ms/op
                 getUser·p0.90:   5.267 ms/op
                 getUser·p0.95:   5.743 ms/op
                 getUser·p0.99:   7.176 ms/op
                 getUser·p0.999:  10.486 ms/op
                 getUser·p0.9999: 22.101 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 4.210 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.104 ms/op
                 getUser·p0.50:   4.125 ms/op
                 getUser·p0.90:   5.071 ms/op
                 getUser·p0.95:   5.562 ms/op
                 getUser·p0.99:   6.939 ms/op
                 getUser·p0.999:  11.994 ms/op
                 getUser·p0.9999: 21.050 ms/op
                 getUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225546
  mean =      4.255 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6247 
    [ 2.500,  5.000) = 186459 
    [ 5.000,  7.500) = 30745 
    [ 7.500, 10.000) = 1529 
    [10.000, 12.500) = 362 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.259 ms/op
     p(95.0000) =      5.751 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     12.172 ms/op
     p(99.9900) =     21.310 ms/op
     p(99.9990) =     24.051 ms/op
     p(99.9999) =     24.183 ms/op
    p(100.0000) =     24.183 ms/op


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
# Warmup Iteration   1: 8.877 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 6.032 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.022 ms/op
Iteration   1: 5.536 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.898 ms/op
                 listUser·p0.50:   5.259 ms/op
                 listUser·p0.90:   7.422 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.207 ms/op
                 listUser·p0.999:  16.880 ms/op
                 listUser·p0.9999: 27.532 ms/op
                 listUser·p1.00:   27.722 ms/op

Iteration   2: 5.706 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.669 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   7.430 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   10.764 ms/op
                 listUser·p0.999:  17.531 ms/op
                 listUser·p0.9999: 21.067 ms/op
                 listUser·p1.00:   21.594 ms/op

Iteration   3: 5.492 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.804 ms/op
                 listUser·p0.50:   5.292 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   9.863 ms/op
                 listUser·p0.999:  20.840 ms/op
                 listUser·p0.9999: 23.021 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172220
  mean =      5.577 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 163 
    [ 2.500,  5.000) = 60649 
    [ 5.000,  7.500) = 96637 
    [ 7.500, 10.000) = 12690 
    [10.000, 12.500) = 1560 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 128 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.669 ms/op
     p(50.0000) =      5.325 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.249 ms/op
     p(99.0000) =     10.240 ms/op
     p(99.9000) =     19.235 ms/op
     p(99.9900) =     26.029 ms/op
     p(99.9990) =     27.651 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.239 ± 5.169  ops/ms
ClientGrpc.existUser                       thrpt       3   8.310 ± 3.704  ops/ms
ClientGrpc.getUser                         thrpt       3   7.473 ± 1.686  ops/ms
ClientGrpc.listUser                        thrpt       3   5.810 ± 1.775  ops/ms
ClientGrpc.createUser                       avgt       3   4.169 ± 1.847   ms/op
ClientGrpc.existUser                        avgt       3   3.929 ± 0.822   ms/op
ClientGrpc.getUser                          avgt       3   4.134 ± 0.746   ms/op
ClientGrpc.listUser                         avgt       3   5.556 ± 0.548   ms/op
ClientGrpc.createUser                     sample  223789   4.287 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.055           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.178           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.276           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.127           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.043           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.202           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.054           ms/op
ClientGrpc.existUser                      sample  231414   4.148 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.825           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.059           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.087           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.554           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.332           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.469           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          28.733           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.425           ms/op
ClientGrpc.getUser                        sample  225546   4.255 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.906           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.157           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.259           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.751           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.381           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.172           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.310           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.183           ms/op
ClientGrpc.listUser                       sample  172220   5.577 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.669           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.325           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.274           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.249           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.240           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.235           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.029           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.722           ms/op
