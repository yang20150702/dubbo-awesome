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
# Warmup Iteration   1: 3.298 ops/ms
# Warmup Iteration   2: 7.175 ops/ms
# Warmup Iteration   3: 8.510 ops/ms
Iteration   1: 8.857 ops/ms
Iteration   2: 8.845 ops/ms
Iteration   3: 8.968 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.890 ±(99.9%) 1.236 ops/ms [Average]
  (min, avg, max) = (8.845, 8.890, 8.968), stdev = 0.068
  CI (99.9%): [7.654, 10.126] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 5.828 ops/ms
# Warmup Iteration   2: 8.689 ops/ms
# Warmup Iteration   3: 9.355 ops/ms
Iteration   1: 9.498 ops/ms
Iteration   2: 9.303 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.378 ±(99.9%) 1.915 ops/ms [Average]
  (min, avg, max) = (9.303, 9.378, 9.498), stdev = 0.105
  CI (99.9%): [7.463, 11.292] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.439 ops/ms
# Warmup Iteration   2: 8.510 ops/ms
# Warmup Iteration   3: 8.726 ops/ms
Iteration   1: 8.964 ops/ms
Iteration   2: 8.864 ops/ms
Iteration   3: 8.904 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.911 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (8.864, 8.911, 8.964), stdev = 0.050
  CI (99.9%): [7.998, 9.824] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.437 ops/ms
# Warmup Iteration   2: 6.541 ops/ms
# Warmup Iteration   3: 6.947 ops/ms
Iteration   1: 6.911 ops/ms
Iteration   2: 6.897 ops/ms
Iteration   3: 6.983 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.930 ±(99.9%) 0.837 ops/ms [Average]
  (min, avg, max) = (6.897, 6.930, 6.983), stdev = 0.046
  CI (99.9%): [6.094, 7.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.459 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.738 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.810 ±(99.9%) 0.003 ms/op
Iteration   1: 3.591 ±(99.9%) 0.003 ms/op
Iteration   2: 3.483 ±(99.9%) 0.003 ms/op
Iteration   3: 3.679 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.584 ±(99.9%) 1.794 ms/op [Average]
  (min, avg, max) = (3.483, 3.584, 3.679), stdev = 0.098
  CI (99.9%): [1.790, 5.379] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.767 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.612 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.480 ±(99.9%) 0.002 ms/op
Iteration   1: 3.430 ±(99.9%) 0.003 ms/op
Iteration   2: 3.529 ±(99.9%) 0.002 ms/op
Iteration   3: 3.370 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.443 ±(99.9%) 1.470 ms/op [Average]
  (min, avg, max) = (3.370, 3.443, 3.529), stdev = 0.081
  CI (99.9%): [1.973, 4.913] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.174 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.004 ms/op
Iteration   1: 3.595 ±(99.9%) 0.004 ms/op
Iteration   2: 3.520 ±(99.9%) 0.005 ms/op
Iteration   3: 3.543 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.553 ±(99.9%) 0.697 ms/op [Average]
  (min, avg, max) = (3.520, 3.553, 3.595), stdev = 0.038
  CI (99.9%): [2.856, 4.250] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.314 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.880 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.579 ±(99.9%) 0.015 ms/op
Iteration   1: 4.606 ±(99.9%) 0.011 ms/op
Iteration   2: 4.513 ±(99.9%) 0.013 ms/op
Iteration   3: 4.587 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.568 ±(99.9%) 0.891 ms/op [Average]
  (min, avg, max) = (4.513, 4.568, 4.606), stdev = 0.049
  CI (99.9%): [3.677, 5.460] (assumes normal distribution)


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
# Warmup Iteration   1: 5.357 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.793 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.669 ±(99.9%) 0.008 ms/op
Iteration   1: 3.513 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.812 ms/op
                 createUser·p0.50:   3.473 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.383 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  12.675 ms/op
                 createUser·p0.9999: 20.964 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.585 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.531 ms/op
                 createUser·p0.90:   4.194 ms/op
                 createUser·p0.95:   4.473 ms/op
                 createUser·p0.99:   5.366 ms/op
                 createUser·p0.999:  8.244 ms/op
                 createUser·p0.9999: 16.238 ms/op
                 createUser·p1.00:   17.334 ms/op

Iteration   3: 3.539 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.788 ms/op
                 createUser·p0.50:   3.514 ms/op
                 createUser·p0.90:   4.088 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  12.730 ms/op
                 createUser·p0.9999: 18.893 ms/op
                 createUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 270936
  mean =      3.545 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6876 
    [ 2.500,  5.000) = 259457 
    [ 5.000,  7.500) = 3944 
    [ 7.500, 10.000) = 366 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 107 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.143 ms/op
     p(99.9900) =     19.297 ms/op
     p(99.9990) =     21.374 ms/op
     p(99.9999) =     21.463 ms/op
    p(100.0000) =     21.463 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.000 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.580 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.419 ±(99.9%) 0.006 ms/op
Iteration   1: 3.440 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.080 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   5.425 ms/op
                 existUser·p0.999:  8.231 ms/op
                 existUser·p0.9999: 18.607 ms/op
                 existUser·p1.00:   18.874 ms/op

Iteration   2: 3.492 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.293 ms/op
                 existUser·p0.99:   5.353 ms/op
                 existUser·p0.999:  9.443 ms/op
                 existUser·p0.9999: 16.968 ms/op
                 existUser·p1.00:   17.498 ms/op

Iteration   3: 3.478 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   3.400 ms/op
                 existUser·p0.90:   4.010 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.279 ms/op
                 existUser·p0.999:  12.028 ms/op
                 existUser·p0.9999: 28.443 ms/op
                 existUser·p1.00:   28.705 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276698
  mean =      3.470 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8302 
    [ 2.500,  5.000) = 264239 
    [ 5.000,  7.500) = 3590 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.366 ms/op
     p(99.9000) =      9.388 ms/op
     p(99.9900) =     27.468 ms/op
     p(99.9990) =     28.639 ms/op
     p(99.9999) =     28.705 ms/op
    p(100.0000) =     28.705 ms/op


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
# Warmup Iteration   1: 5.109 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.831 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.715 ±(99.9%) 0.010 ms/op
Iteration   1: 3.655 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.057 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  8.577 ms/op
                 getUser·p0.9999: 24.117 ms/op
                 getUser·p1.00:   24.314 ms/op

Iteration   2: 3.606 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.971 ms/op
                 getUser·p0.50:   3.547 ms/op
                 getUser·p0.90:   4.252 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  15.031 ms/op
                 getUser·p0.9999: 22.670 ms/op
                 getUser·p1.00:   24.216 ms/op

Iteration   3: 3.476 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.792 ms/op
                 getUser·p0.50:   3.482 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.153 ms/op
                 getUser·p0.999:  7.166 ms/op
                 getUser·p0.9999: 18.894 ms/op
                 getUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 268344
  mean =      3.577 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7419 
    [ 2.500,  5.000) = 255994 
    [ 5.000,  7.500) = 4385 
    [ 7.500, 10.000) = 325 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.535 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.465 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     23.768 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 5.607 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.023 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.584 ±(99.9%) 0.013 ms/op
Iteration   1: 4.564 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.554 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.611 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  15.833 ms/op
                 listUser·p0.9999: 20.021 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   2: 4.516 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   4.366 ms/op
                 listUser·p0.90:   5.415 ms/op
                 listUser·p0.95:   6.537 ms/op
                 listUser·p0.99:   7.829 ms/op
                 listUser·p0.999:  16.026 ms/op
                 listUser·p0.9999: 18.219 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   3: 4.526 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.974 ms/op
                 listUser·p0.50:   4.350 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.234 ms/op
                 listUser·p0.99:   8.036 ms/op
                 listUser·p0.999:  20.752 ms/op
                 listUser·p0.9999: 23.263 ms/op
                 listUser·p1.00:   24.609 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 211727
  mean =      4.535 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 476 
    [ 2.500,  5.000) = 179128 
    [ 5.000,  7.500) = 28701 
    [ 7.500, 10.000) = 2922 
    [10.000, 12.500) = 156 
    [12.500, 15.000) = 22 
    [15.000, 17.500) = 153 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.974 ms/op
     p(50.0000) =      4.375 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.455 ms/op
     p(99.0000) =      7.930 ms/op
     p(99.9000) =     16.852 ms/op
     p(99.9900) =     22.894 ms/op
     p(99.9990) =     24.243 ms/op
     p(99.9999) =     24.609 ms/op
    p(100.0000) =     24.609 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.890 ± 1.236  ops/ms
ClientGrpc.existUser                       thrpt       3   9.378 ± 1.915  ops/ms
ClientGrpc.getUser                         thrpt       3   8.911 ± 0.913  ops/ms
ClientGrpc.listUser                        thrpt       3   6.930 ± 0.837  ops/ms
ClientGrpc.createUser                       avgt       3   3.584 ± 1.794   ms/op
ClientGrpc.existUser                        avgt       3   3.443 ± 1.470   ms/op
ClientGrpc.getUser                          avgt       3   3.553 ± 0.697   ms/op
ClientGrpc.listUser                         avgt       3   4.568 ± 0.891   ms/op
ClientGrpc.createUser                     sample  270936   3.545 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.788           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.506           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.143           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.297           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.463           ms/op
ClientGrpc.existUser                      sample  276698   3.470 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.718           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.055           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.366           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.388           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.468           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.705           ms/op
ClientGrpc.getUser                        sample  268344   3.577 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.792           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.464           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.768           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.314           ms/op
ClientGrpc.listUser                       sample  211727   4.535 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.974           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.455           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.930           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.852           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.894           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.609           ms/op
