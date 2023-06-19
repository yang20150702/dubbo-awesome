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
# Warmup Iteration   1: 2.086 ops/ms
# Warmup Iteration   2: 5.227 ops/ms
# Warmup Iteration   3: 6.728 ops/ms
Iteration   1: 7.133 ops/ms
Iteration   2: 7.187 ops/ms
Iteration   3: 7.172 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.164 ±(99.9%) 0.506 ops/ms [Average]
  (min, avg, max) = (7.133, 7.164, 7.187), stdev = 0.028
  CI (99.9%): [6.658, 7.671] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 4.744 ops/ms
# Warmup Iteration   2: 7.003 ops/ms
# Warmup Iteration   3: 7.432 ops/ms
Iteration   1: 7.476 ops/ms
Iteration   2: 7.536 ops/ms
Iteration   3: 7.612 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.541 ±(99.9%) 1.249 ops/ms [Average]
  (min, avg, max) = (7.476, 7.541, 7.612), stdev = 0.068
  CI (99.9%): [6.292, 8.791] (assumes normal distribution)


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
# Warmup Iteration   1: 4.122 ops/ms
# Warmup Iteration   2: 6.521 ops/ms
# Warmup Iteration   3: 7.059 ops/ms
Iteration   1: 7.410 ops/ms
Iteration   2: 7.323 ops/ms
Iteration   3: 7.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.345 ±(99.9%) 1.047 ops/ms [Average]
  (min, avg, max) = (7.301, 7.345, 7.410), stdev = 0.057
  CI (99.9%): [6.298, 8.392] (assumes normal distribution)


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
# Warmup Iteration   1: 3.662 ops/ms
# Warmup Iteration   2: 5.033 ops/ms
# Warmup Iteration   3: 5.606 ops/ms
Iteration   1: 5.544 ops/ms
Iteration   2: 5.755 ops/ms
Iteration   3: 5.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.645 ±(99.9%) 1.931 ops/ms [Average]
  (min, avg, max) = (5.544, 5.645, 5.755), stdev = 0.106
  CI (99.9%): [3.714, 7.576] (assumes normal distribution)


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
# Warmup Iteration   1: 6.802 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.626 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.470 ±(99.9%) 0.011 ms/op
Iteration   1: 4.350 ±(99.9%) 0.003 ms/op
Iteration   2: 4.398 ±(99.9%) 0.004 ms/op
Iteration   3: 4.416 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.388 ±(99.9%) 0.627 ms/op [Average]
  (min, avg, max) = (4.350, 4.388, 4.416), stdev = 0.034
  CI (99.9%): [3.761, 5.016] (assumes normal distribution)


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
# Warmup Iteration   1: 6.334 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.389 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 4.161 ±(99.9%) 0.003 ms/op
Iteration   1: 4.158 ±(99.9%) 0.002 ms/op
Iteration   2: 4.047 ±(99.9%) 0.004 ms/op
Iteration   3: 4.249 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.151 ±(99.9%) 1.840 ms/op [Average]
  (min, avg, max) = (4.047, 4.151, 4.249), stdev = 0.101
  CI (99.9%): [2.311, 5.992] (assumes normal distribution)


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
# Warmup Iteration   1: 6.991 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.582 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.397 ±(99.9%) 0.004 ms/op
Iteration   1: 4.315 ±(99.9%) 0.003 ms/op
Iteration   2: 4.275 ±(99.9%) 0.003 ms/op
Iteration   3: 4.300 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.297 ±(99.9%) 0.367 ms/op [Average]
  (min, avg, max) = (4.275, 4.297, 4.315), stdev = 0.020
  CI (99.9%): [3.930, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 8.285 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.960 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.658 ±(99.9%) 0.013 ms/op
Iteration   1: 5.497 ±(99.9%) 0.016 ms/op
Iteration   2: 5.562 ±(99.9%) 0.014 ms/op
Iteration   3: 5.270 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.443 ±(99.9%) 2.796 ms/op [Average]
  (min, avg, max) = (5.270, 5.443, 5.562), stdev = 0.153
  CI (99.9%): [2.647, 8.239] (assumes normal distribution)


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
# Warmup Iteration   1: 6.910 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 4.678 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.451 ±(99.9%) 0.013 ms/op
Iteration   1: 4.364 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   4.284 ms/op
                 createUser·p0.90:   5.366 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   7.086 ms/op
                 createUser·p0.999:  10.506 ms/op
                 createUser·p0.9999: 20.775 ms/op
                 createUser·p1.00:   21.168 ms/op

Iteration   2: 4.370 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.826 ms/op
                 createUser·p0.50:   4.268 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   6.988 ms/op
                 createUser·p0.999:  13.451 ms/op
                 createUser·p0.9999: 27.820 ms/op
                 createUser·p1.00:   28.443 ms/op

Iteration   3: 4.411 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   4.309 ms/op
                 createUser·p0.90:   5.456 ms/op
                 createUser·p0.95:   5.759 ms/op
                 createUser·p0.99:   6.636 ms/op
                 createUser·p0.999:  12.439 ms/op
                 createUser·p0.9999: 22.881 ms/op
                 createUser·p1.00:   24.183 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219080
  mean =      4.382 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3198 
    [ 2.500,  5.000) = 174227 
    [ 5.000,  7.500) = 40240 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      4.284 ms/op
     p(90.0000) =      5.390 ms/op
     p(95.0000) =      5.718 ms/op
     p(99.0000) =      6.857 ms/op
     p(99.9000) =     12.616 ms/op
     p(99.9900) =     27.105 ms/op
     p(99.9990) =     28.293 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


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
# Warmup Iteration   1: 5.974 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.580 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.329 ±(99.9%) 0.011 ms/op
Iteration   1: 4.236 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.106 ms/op
                 existUser·p0.50:   4.145 ms/op
                 existUser·p0.90:   5.226 ms/op
                 existUser·p0.95:   5.603 ms/op
                 existUser·p0.99:   6.652 ms/op
                 existUser·p0.999:  10.543 ms/op
                 existUser·p0.9999: 20.618 ms/op
                 existUser·p1.00:   21.135 ms/op

Iteration   2: 4.153 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.067 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   4.923 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  9.503 ms/op
                 existUser·p0.9999: 18.239 ms/op
                 existUser·p1.00:   18.907 ms/op

Iteration   3: 4.158 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   4.116 ms/op
                 existUser·p0.90:   5.022 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   6.193 ms/op
                 existUser·p0.999:  9.175 ms/op
                 existUser·p0.9999: 18.544 ms/op
                 existUser·p1.00:   20.283 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 229412
  mean =      4.182 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4187 
    [ 2.500,  5.000) = 199873 
    [ 5.000,  7.500) = 24376 
    [ 7.500, 10.000) = 769 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 44 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.112 ms/op
     p(90.0000) =      5.054 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.447 ms/op
     p(99.9000) =      9.683 ms/op
     p(99.9900) =     18.350 ms/op
     p(99.9990) =     21.135 ms/op
     p(99.9999) =     21.135 ms/op
    p(100.0000) =     21.135 ms/op


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
# Warmup Iteration   1: 6.263 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.738 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.521 ±(99.9%) 0.012 ms/op
Iteration   1: 4.408 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   4.284 ms/op
                 getUser·p0.90:   5.456 ms/op
                 getUser·p0.95:   6.029 ms/op
                 getUser·p0.99:   7.553 ms/op
                 getUser·p0.999:  12.844 ms/op
                 getUser·p0.9999: 16.375 ms/op
                 getUser·p1.00:   18.121 ms/op

Iteration   2: 4.425 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.274 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.620 ms/op
                 getUser·p0.99:   6.496 ms/op
                 getUser·p0.999:  8.964 ms/op
                 getUser·p0.9999: 18.229 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   3: 4.430 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.221 ms/op
                 getUser·p0.50:   4.334 ms/op
                 getUser·p0.90:   5.366 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.006 ms/op
                 getUser·p0.999:  11.292 ms/op
                 getUser·p0.9999: 20.072 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 217096
  mean =      4.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2184 
    [ 2.500,  5.000) = 174288 
    [ 5.000,  7.500) = 39057 
    [ 7.500, 10.000) = 1239 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.221 ms/op
     p(50.0000) =      4.317 ms/op
     p(90.0000) =      5.374 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.070 ms/op
     p(99.9000) =     11.418 ms/op
     p(99.9900) =     18.706 ms/op
     p(99.9990) =     20.299 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 7.977 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 6.164 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.769 ±(99.9%) 0.018 ms/op
Iteration   1: 5.489 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.982 ms/op
                 listUser·p0.50:   5.317 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  15.210 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.202 ms/op

Iteration   2: 5.608 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   5.382 ms/op
                 listUser·p0.90:   7.184 ms/op
                 listUser·p0.95:   8.200 ms/op
                 listUser·p0.99:   10.060 ms/op
                 listUser·p0.999:  21.557 ms/op
                 listUser·p0.9999: 26.739 ms/op
                 listUser·p1.00:   27.034 ms/op

Iteration   3: 5.618 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   5.415 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.800 ms/op
                 listUser·p0.99:   10.486 ms/op
                 listUser·p0.999:  20.644 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 172373
  mean =      5.571 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 53486 
    [ 5.000,  7.500) = 106810 
    [ 7.500, 10.000) = 10290 
    [10.000, 12.500) = 1199 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 44 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      5.374 ms/op
     p(90.0000) =      6.914 ms/op
     p(95.0000) =      7.963 ms/op
     p(99.0000) =     10.011 ms/op
     p(99.9000) =     19.780 ms/op
     p(99.9900) =     26.158 ms/op
     p(99.9990) =     26.939 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.164 ± 0.506  ops/ms
ClientGrpc.existUser                       thrpt       3   7.541 ± 1.249  ops/ms
ClientGrpc.getUser                         thrpt       3   7.345 ± 1.047  ops/ms
ClientGrpc.listUser                        thrpt       3   5.645 ± 1.931  ops/ms
ClientGrpc.createUser                       avgt       3   4.388 ± 0.627   ms/op
ClientGrpc.existUser                        avgt       3   4.151 ± 1.840   ms/op
ClientGrpc.getUser                          avgt       3   4.297 ± 0.367   ms/op
ClientGrpc.listUser                         avgt       3   5.443 ± 2.796   ms/op
ClientGrpc.createUser                     sample  219080   4.382 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.826           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.284           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.390           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.718           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.857           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.616           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.105           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.443           ms/op
ClientGrpc.existUser                      sample  229412   4.182 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.931           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.112           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.054           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.415           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.447           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.683           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.135           ms/op
ClientGrpc.getUser                        sample  217096   4.421 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.221           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.767           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.070           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.418           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.706           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.447           ms/op
ClientGrpc.listUser                       sample  172373   5.571 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.321           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.374           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.963           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.011           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.780           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.158           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.034           ms/op
