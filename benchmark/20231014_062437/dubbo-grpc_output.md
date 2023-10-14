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
# Warmup Iteration   1: 2.797 ops/ms
# Warmup Iteration   2: 6.961 ops/ms
# Warmup Iteration   3: 8.236 ops/ms
Iteration   1: 8.624 ops/ms
Iteration   2: 8.526 ops/ms
Iteration   3: 8.648 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.599 ±(99.9%) 1.177 ops/ms [Average]
  (min, avg, max) = (8.526, 8.599, 8.648), stdev = 0.065
  CI (99.9%): [7.422, 9.776] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.142 ops/ms
# Warmup Iteration   2: 8.757 ops/ms
# Warmup Iteration   3: 9.043 ops/ms
Iteration   1: 9.497 ops/ms
Iteration   2: 9.028 ops/ms
Iteration   3: 9.223 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.249 ±(99.9%) 4.294 ops/ms [Average]
  (min, avg, max) = (9.028, 9.249, 9.497), stdev = 0.235
  CI (99.9%): [4.955, 13.543] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.255 ops/ms
# Warmup Iteration   2: 8.388 ops/ms
# Warmup Iteration   3: 8.649 ops/ms
Iteration   1: 8.621 ops/ms
Iteration   2: 8.848 ops/ms
Iteration   3: 9.139 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.869 ±(99.9%) 4.735 ops/ms [Average]
  (min, avg, max) = (8.621, 8.869, 9.139), stdev = 0.260
  CI (99.9%): [4.135, 13.604] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.145 ops/ms
# Warmup Iteration   2: 6.599 ops/ms
# Warmup Iteration   3: 6.939 ops/ms
Iteration   1: 6.535 ops/ms
Iteration   2: 6.532 ops/ms
Iteration   3: 6.751 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.606 ±(99.9%) 2.293 ops/ms [Average]
  (min, avg, max) = (6.532, 6.606, 6.751), stdev = 0.126
  CI (99.9%): [4.313, 8.899] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.478 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.759 ±(99.9%) 0.009 ms/op
Iteration   1: 3.665 ±(99.9%) 0.005 ms/op
Iteration   2: 3.622 ±(99.9%) 0.003 ms/op
Iteration   3: 3.778 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.688 ±(99.9%) 1.465 ms/op [Average]
  (min, avg, max) = (3.622, 3.688, 3.778), stdev = 0.080
  CI (99.9%): [2.223, 5.153] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 5.222 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.540 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.402 ±(99.9%) 0.004 ms/op
Iteration   1: 3.410 ±(99.9%) 0.003 ms/op
Iteration   2: 3.338 ±(99.9%) 0.002 ms/op
Iteration   3: 3.304 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.351 ±(99.9%) 0.980 ms/op [Average]
  (min, avg, max) = (3.304, 3.351, 3.410), stdev = 0.054
  CI (99.9%): [2.371, 4.331] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.528 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.781 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.650 ±(99.9%) 0.004 ms/op
Iteration   1: 3.455 ±(99.9%) 0.005 ms/op
Iteration   2: 3.524 ±(99.9%) 0.005 ms/op
Iteration   3: 3.517 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.499 ±(99.9%) 0.691 ms/op [Average]
  (min, avg, max) = (3.455, 3.499, 3.524), stdev = 0.038
  CI (99.9%): [2.808, 4.189] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.983 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.984 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 4.542 ±(99.9%) 0.012 ms/op
Iteration   1: 4.545 ±(99.9%) 0.014 ms/op
Iteration   2: 4.639 ±(99.9%) 0.014 ms/op
Iteration   3: 4.649 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.611 ±(99.9%) 1.041 ms/op [Average]
  (min, avg, max) = (4.545, 4.611, 4.649), stdev = 0.057
  CI (99.9%): [3.570, 5.652] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.492 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.795 ±(99.9%) 0.013 ms/op
Iteration   1: 3.598 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.879 ms/op
                 createUser·p0.50:   3.518 ms/op
                 createUser·p0.90:   4.407 ms/op
                 createUser·p0.95:   4.817 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  11.878 ms/op
                 createUser·p0.9999: 19.956 ms/op
                 createUser·p1.00:   20.283 ms/op

Iteration   2: 3.605 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.889 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.087 ms/op
                 createUser·p0.999:  11.813 ms/op
                 createUser·p0.9999: 20.746 ms/op
                 createUser·p1.00:   21.299 ms/op

Iteration   3: 3.628 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.562 ms/op
                 createUser·p0.50:   3.523 ms/op
                 createUser·p0.90:   4.555 ms/op
                 createUser·p0.95:   4.932 ms/op
                 createUser·p0.99:   6.300 ms/op
                 createUser·p0.999:  13.218 ms/op
                 createUser·p0.9999: 23.435 ms/op
                 createUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 265891
  mean =      3.611 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10308 
    [ 2.500,  5.000) = 245680 
    [ 5.000,  7.500) = 8642 
    [ 7.500, 10.000) = 788 
    [10.000, 12.500) = 209 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.562 ms/op
     p(50.0000) =      3.527 ms/op
     p(90.0000) =      4.481 ms/op
     p(95.0000) =      4.841 ms/op
     p(99.0000) =      6.128 ms/op
     p(99.9000) =     12.485 ms/op
     p(99.9900) =     22.340 ms/op
     p(99.9990) =     24.009 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.083 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.642 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.412 ±(99.9%) 0.009 ms/op
Iteration   1: 3.417 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.799 ms/op
                 existUser·p0.50:   3.318 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.514 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  14.460 ms/op
                 existUser·p0.9999: 22.446 ms/op
                 existUser·p1.00:   23.986 ms/op

Iteration   2: 3.418 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.904 ms/op
                 existUser·p0.50:   3.322 ms/op
                 existUser·p0.90:   4.235 ms/op
                 existUser·p0.95:   4.579 ms/op
                 existUser·p0.99:   5.931 ms/op
                 existUser·p0.999:  11.197 ms/op
                 existUser·p0.9999: 17.760 ms/op
                 existUser·p1.00:   18.285 ms/op

Iteration   3: 3.419 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.745 ms/op
                 existUser·p0.50:   3.330 ms/op
                 existUser·p0.90:   4.260 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  12.747 ms/op
                 existUser·p0.9999: 17.946 ms/op
                 existUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 280737
  mean =      3.418 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11329 
    [ 2.500,  5.000) = 262373 
    [ 5.000,  7.500) = 5659 
    [ 7.500, 10.000) = 851 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 87 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.745 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      5.964 ms/op
     p(99.9000) =     12.473 ms/op
     p(99.9900) =     21.524 ms/op
     p(99.9990) =     23.809 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.202 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.682 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.581 ±(99.9%) 0.025 ms/op
Iteration   1: 3.456 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.884 ms/op
                 getUser·p0.50:   3.437 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   5.906 ms/op
                 getUser·p0.999:  11.140 ms/op
                 getUser·p0.9999: 30.638 ms/op
                 getUser·p1.00:   30.966 ms/op

Iteration   2: 3.535 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.358 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.165 ms/op
                 getUser·p0.999:  10.453 ms/op
                 getUser·p0.9999: 31.685 ms/op
                 getUser·p1.00:   33.358 ms/op

Iteration   3: 3.532 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   3.453 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.480 ms/op
                 getUser·p0.999:  13.975 ms/op
                 getUser·p0.9999: 20.742 ms/op
                 getUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 273647
  mean =      3.507 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16538 
    [ 2.500,  5.000) = 249675 
    [ 5.000,  7.500) = 6045 
    [ 7.500, 10.000) = 908 
    [10.000, 12.500) = 247 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 13 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.867 ms/op
     p(50.0000) =      3.445 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.645 ms/op
     p(99.0000) =      6.144 ms/op
     p(99.9000) =     11.710 ms/op
     p(99.9900) =     29.065 ms/op
     p(99.9990) =     33.178 ms/op
     p(99.9999) =     33.358 ms/op
    p(100.0000) =     33.358 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 6.976 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 5.106 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.628 ±(99.9%) 0.018 ms/op
Iteration   1: 4.689 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   4.456 ms/op
                 listUser·p0.90:   5.939 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.602 ms/op
                 listUser·p0.999:  22.413 ms/op
                 listUser·p0.9999: 27.570 ms/op
                 listUser·p1.00:   28.836 ms/op

Iteration   2: 4.563 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   4.293 ms/op
                 listUser·p0.90:   5.906 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   9.191 ms/op
                 listUser·p0.999:  22.491 ms/op
                 listUser·p0.9999: 26.213 ms/op
                 listUser·p1.00:   27.918 ms/op

Iteration   3: 4.635 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.198 ms/op
                 listUser·p0.50:   4.391 ms/op
                 listUser·p0.90:   5.988 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   9.470 ms/op
                 listUser·p0.999:  18.869 ms/op
                 listUser·p0.9999: 25.068 ms/op
                 listUser·p1.00:   25.461 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 207687
  mean =      4.628 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 845 
    [ 2.500,  5.000) = 159710 
    [ 5.000,  7.500) = 41132 
    [ 7.500, 10.000) = 4745 
    [10.000, 12.500) = 643 
    [12.500, 15.000) = 179 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 79 
    [20.000, 22.500) = 106 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 73 

  Percentiles, ms/op:
      p(0.0000) =      1.198 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.939 ms/op
     p(95.0000) =      6.840 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     21.506 ms/op
     p(99.9900) =     27.195 ms/op
     p(99.9990) =     28.175 ms/op
     p(99.9999) =     28.836 ms/op
    p(100.0000) =     28.836 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.599 ± 1.177  ops/ms
ClientGrpc.existUser                       thrpt       3   9.249 ± 4.294  ops/ms
ClientGrpc.getUser                         thrpt       3   8.869 ± 4.735  ops/ms
ClientGrpc.listUser                        thrpt       3   6.606 ± 2.293  ops/ms
ClientGrpc.createUser                       avgt       3   3.688 ± 1.465   ms/op
ClientGrpc.existUser                        avgt       3   3.351 ± 0.980   ms/op
ClientGrpc.getUser                          avgt       3   3.499 ± 0.691   ms/op
ClientGrpc.listUser                         avgt       3   4.611 ± 1.041   ms/op
ClientGrpc.createUser                     sample  265891   3.611 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.562           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.527           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.841           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.128           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.485           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.340           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.150           ms/op
ClientGrpc.existUser                      sample  280737   3.418 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.745           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.579           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.964           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.473           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.524           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.986           ms/op
ClientGrpc.getUser                        sample  273647   3.507 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.867           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.645           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.144           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.710           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.065           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.358           ms/op
ClientGrpc.listUser                       sample  207687   4.628 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.198           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.383           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.840           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          21.506           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.195           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.836           ms/op
