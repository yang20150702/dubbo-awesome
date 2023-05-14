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
# Warmup Iteration   1: 3.859 ops/ms
# Warmup Iteration   2: 8.224 ops/ms
# Warmup Iteration   3: 9.098 ops/ms
Iteration   1: 9.563 ops/ms
Iteration   2: 9.889 ops/ms
Iteration   3: 9.677 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.710 ±(99.9%) 3.018 ops/ms [Average]
  (min, avg, max) = (9.563, 9.710, 9.889), stdev = 0.165
  CI (99.9%): [6.692, 12.727] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 6.492 ops/ms
# Warmup Iteration   2: 9.798 ops/ms
# Warmup Iteration   3: 10.306 ops/ms
Iteration   1: 10.213 ops/ms
Iteration   2: 10.211 ops/ms
Iteration   3: 10.448 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.291 ±(99.9%) 2.487 ops/ms [Average]
  (min, avg, max) = (10.211, 10.291, 10.448), stdev = 0.136
  CI (99.9%): [7.804, 12.778] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.436 ops/ms
# Warmup Iteration   2: 9.139 ops/ms
# Warmup Iteration   3: 9.906 ops/ms
Iteration   1: 9.801 ops/ms
Iteration   2: 9.361 ops/ms
Iteration   3: 9.309 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.490 ±(99.9%) 4.927 ops/ms [Average]
  (min, avg, max) = (9.309, 9.490, 9.801), stdev = 0.270
  CI (99.9%): [4.563, 14.417] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 4.790 ops/ms
# Warmup Iteration   2: 6.486 ops/ms
# Warmup Iteration   3: 7.200 ops/ms
Iteration   1: 7.288 ops/ms
Iteration   2: 7.472 ops/ms
Iteration   3: 7.372 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.377 ±(99.9%) 1.680 ops/ms [Average]
  (min, avg, max) = (7.288, 7.377, 7.472), stdev = 0.092
  CI (99.9%): [5.697, 9.057] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.629 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.252 ±(99.9%) 0.012 ms/op
Iteration   1: 3.170 ±(99.9%) 0.003 ms/op
Iteration   2: 3.160 ±(99.9%) 0.003 ms/op
Iteration   3: 3.120 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.150 ±(99.9%) 0.481 ms/op [Average]
  (min, avg, max) = (3.120, 3.150, 3.170), stdev = 0.026
  CI (99.9%): [2.669, 3.631] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.000 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.289 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.003 ms/op
Iteration   1: 3.059 ±(99.9%) 0.003 ms/op
Iteration   2: 2.980 ±(99.9%) 0.003 ms/op
Iteration   3: 3.057 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.032 ±(99.9%) 0.828 ms/op [Average]
  (min, avg, max) = (2.980, 3.032, 3.059), stdev = 0.045
  CI (99.9%): [2.204, 3.861] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.807 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.572 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.378 ±(99.9%) 0.003 ms/op
Iteration   1: 3.370 ±(99.9%) 0.004 ms/op
Iteration   2: 3.266 ±(99.9%) 0.004 ms/op
Iteration   3: 3.181 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.272 ±(99.9%) 1.728 ms/op [Average]
  (min, avg, max) = (3.181, 3.272, 3.370), stdev = 0.095
  CI (99.9%): [1.545, 5.000] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.823 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.612 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.424 ±(99.9%) 0.023 ms/op
Iteration   1: 4.456 ±(99.9%) 0.025 ms/op
Iteration   2: 4.287 ±(99.9%) 0.012 ms/op
Iteration   3: 4.334 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.359 ±(99.9%) 1.590 ms/op [Average]
  (min, avg, max) = (4.287, 4.359, 4.456), stdev = 0.087
  CI (99.9%): [2.769, 5.950] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.632 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.008 ms/op
Iteration   1: 3.286 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.904 ms/op
                 createUser·p0.50:   3.260 ms/op
                 createUser·p0.90:   3.912 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.153 ms/op
                 createUser·p0.999:  8.018 ms/op
                 createUser·p0.9999: 22.866 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.200 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.947 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.092 ms/op
                 createUser·p0.99:   4.710 ms/op
                 createUser·p0.999:  16.912 ms/op
                 createUser·p0.9999: 24.445 ms/op
                 createUser·p1.00:   26.477 ms/op

Iteration   3: 3.249 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.059 ms/op
                 createUser·p0.99:   4.653 ms/op
                 createUser·p0.999:  7.197 ms/op
                 createUser·p0.9999: 18.028 ms/op
                 createUser·p1.00:   18.186 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 295622
  mean =      3.245 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19568 
    [ 2.500,  5.000) = 273698 
    [ 5.000,  7.500) = 1967 
    [ 7.500, 10.000) = 92 
    [10.000, 12.500) = 14 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 82 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.812 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      3.863 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =     10.194 ms/op
     p(99.9900) =     22.966 ms/op
     p(99.9990) =     26.383 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.142 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.194 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.225 ±(99.9%) 0.007 ms/op
Iteration   1: 3.228 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.785 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   4.022 ms/op
                 existUser·p0.99:   4.858 ms/op
                 existUser·p0.999:  7.413 ms/op
                 existUser·p0.9999: 14.536 ms/op
                 existUser·p1.00:   14.828 ms/op

Iteration   2: 3.251 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.743 ms/op
                 existUser·p0.50:   3.236 ms/op
                 existUser·p0.90:   3.772 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.555 ms/op
                 existUser·p0.999:  7.348 ms/op
                 existUser·p0.9999: 16.370 ms/op
                 existUser·p1.00:   16.515 ms/op

Iteration   3: 3.179 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.760 ms/op
                 existUser·p0.95:   3.977 ms/op
                 existUser·p0.99:   4.735 ms/op
                 existUser·p0.999:  6.512 ms/op
                 existUser·p0.9999: 18.252 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 298375
  mean =      3.219 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 672 
    [ 1.250,  2.500) = 15609 
    [ 2.500,  3.750) = 249450 
    [ 3.750,  5.000) = 30514 
    [ 5.000,  6.250) = 1516 
    [ 6.250,  7.500) = 378 
    [ 7.500,  8.750) = 88 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 37 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.743 ms/op
     p(50.0000) =      3.203 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      4.719 ms/op
     p(99.9000) =      7.283 ms/op
     p(99.9900) =     16.698 ms/op
     p(99.9990) =     18.616 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


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
# Warmup Iteration   1: 4.547 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.429 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.373 ±(99.9%) 0.008 ms/op
Iteration   1: 3.350 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.950 ms/op
                 getUser·p0.50:   3.305 ms/op
                 getUser·p0.90:   3.838 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   4.727 ms/op
                 getUser·p0.999:  9.445 ms/op
                 getUser·p0.9999: 14.629 ms/op
                 getUser·p1.00:   15.024 ms/op

Iteration   2: 3.396 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.447 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.153 ms/op
                 getUser·p0.99:   4.735 ms/op
                 getUser·p0.999:  7.447 ms/op
                 getUser·p0.9999: 18.285 ms/op
                 getUser·p1.00:   18.711 ms/op

Iteration   3: 3.356 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.944 ms/op
                 getUser·p0.95:   4.252 ms/op
                 getUser·p0.99:   5.128 ms/op
                 getUser·p0.999:  7.336 ms/op
                 getUser·p0.9999: 15.998 ms/op
                 getUser·p1.00:   18.055 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 285234
  mean =      3.367 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 191 
    [ 1.250,  2.500) = 8364 
    [ 2.500,  3.750) = 229054 
    [ 3.750,  5.000) = 45259 
    [ 5.000,  6.250) = 1807 
    [ 6.250,  7.500) = 263 
    [ 7.500,  8.750) = 95 
    [ 8.750, 10.000) = 26 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 73 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.447 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.912 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =      7.576 ms/op
     p(99.9900) =     17.743 ms/op
     p(99.9990) =     18.589 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


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
# Warmup Iteration   1: 5.575 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.306 ±(99.9%) 0.014 ms/op
Iteration   1: 4.365 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.991 ms/op
                 listUser·p0.50:   4.186 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.332 ms/op
                 listUser·p0.99:   7.660 ms/op
                 listUser·p0.999:  14.448 ms/op
                 listUser·p0.9999: 19.977 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 4.341 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.592 ms/op
                 listUser·p0.50:   4.133 ms/op
                 listUser·p0.90:   5.603 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   7.750 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 25.023 ms/op
                 listUser·p1.00:   25.494 ms/op

Iteration   3: 4.424 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.964 ms/op
                 listUser·p0.50:   4.162 ms/op
                 listUser·p0.90:   5.759 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.241 ms/op
                 listUser·p0.999:  19.976 ms/op
                 listUser·p0.9999: 29.140 ms/op
                 listUser·p1.00:   31.425 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 219439
  mean =      4.376 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1956 
    [ 2.500,  5.000) = 176742 
    [ 5.000,  7.500) = 37375 
    [ 7.500, 10.000) = 2639 
    [10.000, 12.500) = 269 
    [12.500, 15.000) = 121 
    [15.000, 17.500) = 124 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 44 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.592 ms/op
     p(50.0000) =      4.157 ms/op
     p(90.0000) =      5.693 ms/op
     p(95.0000) =      6.390 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     17.451 ms/op
     p(99.9900) =     27.492 ms/op
     p(99.9990) =     30.468 ms/op
     p(99.9999) =     31.425 ms/op
    p(100.0000) =     31.425 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.710 ± 3.018  ops/ms
ClientGrpc.existUser                       thrpt       3  10.291 ± 2.487  ops/ms
ClientGrpc.getUser                         thrpt       3   9.490 ± 4.927  ops/ms
ClientGrpc.listUser                        thrpt       3   7.377 ± 1.680  ops/ms
ClientGrpc.createUser                       avgt       3   3.150 ± 0.481   ms/op
ClientGrpc.existUser                        avgt       3   3.032 ± 0.828   ms/op
ClientGrpc.getUser                          avgt       3   3.272 ± 1.728   ms/op
ClientGrpc.listUser                         avgt       3   4.359 ± 1.590   ms/op
ClientGrpc.createUser                     sample  295622   3.245 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.812           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.211           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.121           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.825           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.194           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.966           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.477           ms/op
ClientGrpc.existUser                      sample  298375   3.219 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.743           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.203           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.994           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.719           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.283           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.698           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.940           ms/op
ClientGrpc.getUser                        sample  285234   3.367 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.447           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.342           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.912           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.162           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.874           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.576           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.743           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  219439   4.376 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.592           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.157           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.390           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.451           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.492           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.425           ms/op
