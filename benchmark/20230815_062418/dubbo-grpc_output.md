# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.008 ops/ms
# Warmup Iteration   2: 5.052 ops/ms
# Warmup Iteration   3: 6.536 ops/ms
Iteration   1: 6.852 ops/ms
Iteration   2: 6.880 ops/ms
Iteration   3: 6.743 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.825 ±(99.9%) 1.322 ops/ms [Average]
  (min, avg, max) = (6.743, 6.825, 6.880), stdev = 0.072
  CI (99.9%): [5.504, 8.147] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.457 ops/ms
# Warmup Iteration   2: 6.783 ops/ms
# Warmup Iteration   3: 7.207 ops/ms
Iteration   1: 7.128 ops/ms
Iteration   2: 7.146 ops/ms
Iteration   3: 7.077 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.117 ±(99.9%) 0.651 ops/ms [Average]
  (min, avg, max) = (7.077, 7.117, 7.146), stdev = 0.036
  CI (99.9%): [6.467, 7.768] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.666 ops/ms
# Warmup Iteration   2: 6.368 ops/ms
# Warmup Iteration   3: 6.763 ops/ms
Iteration   1: 6.886 ops/ms
Iteration   2: 6.687 ops/ms
Iteration   3: 6.893 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.822 ±(99.9%) 2.130 ops/ms [Average]
  (min, avg, max) = (6.687, 6.822, 6.893), stdev = 0.117
  CI (99.9%): [4.692, 8.952] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ops/ms
# Warmup Iteration   2: 4.574 ops/ms
# Warmup Iteration   3: 5.292 ops/ms
Iteration   1: 5.217 ops/ms
Iteration   2: 5.440 ops/ms
Iteration   3: 5.373 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.343 ±(99.9%) 2.089 ops/ms [Average]
  (min, avg, max) = (5.217, 5.343, 5.440), stdev = 0.114
  CI (99.9%): [3.254, 7.432] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.372 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.088 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.843 ±(99.9%) 0.005 ms/op
Iteration   1: 4.571 ±(99.9%) 0.005 ms/op
Iteration   2: 4.599 ±(99.9%) 0.004 ms/op
Iteration   3: 4.576 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.582 ±(99.9%) 0.279 ms/op [Average]
  (min, avg, max) = (4.571, 4.582, 4.599), stdev = 0.015
  CI (99.9%): [4.303, 4.861] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.668 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.714 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.459 ±(99.9%) 0.004 ms/op
Iteration   1: 4.454 ±(99.9%) 0.004 ms/op
Iteration   2: 4.286 ±(99.9%) 0.004 ms/op
Iteration   3: 4.075 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.272 ±(99.9%) 3.466 ms/op [Average]
  (min, avg, max) = (4.075, 4.272, 4.454), stdev = 0.190
  CI (99.9%): [0.806, 7.737] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.164 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 5.030 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.826 ±(99.9%) 0.007 ms/op
Iteration   1: 4.598 ±(99.9%) 0.005 ms/op
Iteration   2: 4.518 ±(99.9%) 0.004 ms/op
Iteration   3: 4.627 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.581 ±(99.9%) 1.037 ms/op [Average]
  (min, avg, max) = (4.518, 4.581, 4.627), stdev = 0.057
  CI (99.9%): [3.544, 5.618] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.662 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 6.526 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 6.244 ±(99.9%) 0.024 ms/op
Iteration   1: 6.079 ±(99.9%) 0.025 ms/op
Iteration   2: 5.923 ±(99.9%) 0.016 ms/op
Iteration   3: 5.883 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.962 ±(99.9%) 1.891 ms/op [Average]
  (min, avg, max) = (5.883, 5.962, 6.079), stdev = 0.104
  CI (99.9%): [4.070, 7.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.181 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.784 ±(99.9%) 0.013 ms/op
Iteration   1: 4.598 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   4.506 ms/op
                 createUser·p0.90:   5.628 ms/op
                 createUser·p0.95:   6.177 ms/op
                 createUser·p0.99:   7.799 ms/op
                 createUser·p0.999:  13.246 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 4.675 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.943 ms/op
                 createUser·p0.50:   4.555 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.300 ms/op
                 createUser·p0.99:   7.791 ms/op
                 createUser·p0.999:  11.977 ms/op
                 createUser·p0.9999: 22.526 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 4.745 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.002 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   5.947 ms/op
                 createUser·p0.95:   6.439 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  13.197 ms/op
                 createUser·p0.9999: 26.158 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 205344
  mean =      4.672 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3857 
    [ 2.500,  5.000) = 141088 
    [ 5.000,  7.500) = 57597 
    [ 7.500, 10.000) = 2094 
    [10.000, 12.500) = 475 
    [12.500, 15.000) = 71 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.943 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      5.825 ms/op
     p(95.0000) =      6.324 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     12.681 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     26.826 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.290 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.733 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.274 ±(99.9%) 0.013 ms/op
Iteration   1: 4.397 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.122 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.366 ms/op
                 existUser·p0.95:   5.792 ms/op
                 existUser·p0.99:   7.430 ms/op
                 existUser·p0.999:  11.048 ms/op
                 existUser·p0.9999: 26.903 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 4.402 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.002 ms/op
                 existUser·p0.50:   4.317 ms/op
                 existUser·p0.90:   5.415 ms/op
                 existUser·p0.95:   5.816 ms/op
                 existUser·p0.99:   7.660 ms/op
                 existUser·p0.999:  13.784 ms/op
                 existUser·p0.9999: 22.649 ms/op
                 existUser·p1.00:   23.527 ms/op

Iteration   3: 4.291 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.087 ms/op
                 existUser·p0.50:   4.260 ms/op
                 existUser·p0.90:   5.407 ms/op
                 existUser·p0.95:   5.833 ms/op
                 existUser·p0.99:   7.830 ms/op
                 existUser·p0.999:  17.105 ms/op
                 existUser·p0.9999: 20.926 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 219985
  mean =      4.363 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10822 
    [ 2.500,  5.000) = 166469 
    [ 5.000,  7.500) = 40296 
    [ 7.500, 10.000) = 1802 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 35 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.301 ms/op
     p(90.0000) =      5.399 ms/op
     p(95.0000) =      5.816 ms/op
     p(99.0000) =      7.644 ms/op
     p(99.9000) =     13.877 ms/op
     p(99.9900) =     24.906 ms/op
     p(99.9990) =     26.962 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.250 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 5.041 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.756 ±(99.9%) 0.014 ms/op
Iteration   1: 4.575 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   5.702 ms/op
                 getUser·p0.95:   6.260 ms/op
                 getUser·p0.99:   8.167 ms/op
                 getUser·p0.999:  13.305 ms/op
                 getUser·p0.9999: 17.401 ms/op
                 getUser·p1.00:   21.430 ms/op

Iteration   2: 4.677 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.303 ms/op
                 getUser·p0.50:   4.530 ms/op
                 getUser·p0.90:   5.710 ms/op
                 getUser·p0.95:   6.128 ms/op
                 getUser·p0.99:   7.815 ms/op
                 getUser·p0.999:  13.418 ms/op
                 getUser·p0.9999: 18.590 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   3: 4.655 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.214 ms/op
                 getUser·p0.50:   4.514 ms/op
                 getUser·p0.90:   5.693 ms/op
                 getUser·p0.95:   6.259 ms/op
                 getUser·p0.99:   8.471 ms/op
                 getUser·p0.999:  13.489 ms/op
                 getUser·p0.9999: 22.029 ms/op
                 getUser·p1.00:   23.593 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 206902
  mean =      4.635 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3945 
    [ 2.500,  5.000) = 149605 
    [ 5.000,  7.500) = 50150 
    [ 7.500, 10.000) = 2389 
    [10.000, 12.500) = 486 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 35 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      4.506 ms/op
     p(90.0000) =      5.702 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =      8.167 ms/op
     p(99.9000) =     13.338 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     23.263 ms/op
     p(99.9999) =     23.593 ms/op
    p(100.0000) =     23.593 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.313 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 6.575 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.758 ±(99.9%) 0.021 ms/op
Iteration   1: 5.931 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.722 ms/op
                 listUser·p0.50:   5.620 ms/op
                 listUser·p0.90:   7.725 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   11.469 ms/op
                 listUser·p0.999:  17.573 ms/op
                 listUser·p0.9999: 19.484 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   2: 5.971 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.145 ms/op
                 listUser·p0.50:   5.693 ms/op
                 listUser·p0.90:   7.700 ms/op
                 listUser·p0.95:   8.831 ms/op
                 listUser·p0.99:   11.354 ms/op
                 listUser·p0.999:  18.874 ms/op
                 listUser·p0.9999: 22.018 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 5.871 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.704 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.643 ms/op
                 listUser·p0.95:   8.798 ms/op
                 listUser·p0.99:   11.846 ms/op
                 listUser·p0.999:  22.512 ms/op
                 listUser·p0.9999: 25.694 ms/op
                 listUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 161930
  mean =      5.924 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 116 
    [ 2.500,  5.000) = 36470 
    [ 5.000,  7.500) = 107269 
    [ 7.500, 10.000) = 14255 
    [10.000, 12.500) = 2758 
    [12.500, 15.000) = 587 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 152 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.145 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.692 ms/op
     p(95.0000) =      8.847 ms/op
     p(99.0000) =     11.518 ms/op
     p(99.9000) =     19.305 ms/op
     p(99.9900) =     24.846 ms/op
     p(99.9990) =     26.191 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.825 ± 1.322  ops/ms
ClientGrpc.existUser                       thrpt       3   7.117 ± 0.651  ops/ms
ClientGrpc.getUser                         thrpt       3   6.822 ± 2.130  ops/ms
ClientGrpc.listUser                        thrpt       3   5.343 ± 2.089  ops/ms
ClientGrpc.createUser                       avgt       3   4.582 ± 0.279   ms/op
ClientGrpc.existUser                        avgt       3   4.272 ± 3.466   ms/op
ClientGrpc.getUser                          avgt       3   4.581 ± 1.037   ms/op
ClientGrpc.listUser                         avgt       3   5.962 ± 1.891   ms/op
ClientGrpc.createUser                     sample  205344   4.672 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.943           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.825           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.324           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.938           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.681           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.625           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.034           ms/op
ClientGrpc.existUser                      sample  219985   4.363 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.002           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.301           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.399           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.816           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.644           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.877           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          24.906           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.968           ms/op
ClientGrpc.getUser                        sample  206902   4.635 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.065           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.506           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.702           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.210           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.167           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.185           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.593           ms/op
ClientGrpc.listUser                       sample  161930   5.924 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.145           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.847           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.518           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.305           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.846           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.313           ms/op
