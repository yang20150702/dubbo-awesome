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
# Warmup Iteration   1: 3.101 ops/ms
# Warmup Iteration   2: 6.644 ops/ms
# Warmup Iteration   3: 8.394 ops/ms
Iteration   1: 8.970 ops/ms
Iteration   2: 9.173 ops/ms
Iteration   3: 9.380 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.174 ±(99.9%) 3.739 ops/ms [Average]
  (min, avg, max) = (8.970, 9.174, 9.380), stdev = 0.205
  CI (99.9%): [5.435, 12.914] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 6.878 ops/ms
# Warmup Iteration   2: 8.768 ops/ms
# Warmup Iteration   3: 9.350 ops/ms
Iteration   1: 9.295 ops/ms
Iteration   2: 9.166 ops/ms
Iteration   3: 9.283 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.248 ±(99.9%) 1.294 ops/ms [Average]
  (min, avg, max) = (9.166, 9.248, 9.295), stdev = 0.071
  CI (99.9%): [7.953, 10.542] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.800 ops/ms
# Warmup Iteration   2: 8.281 ops/ms
# Warmup Iteration   3: 8.930 ops/ms
Iteration   1: 8.952 ops/ms
Iteration   2: 8.822 ops/ms
Iteration   3: 9.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.952 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (8.822, 8.952, 9.082), stdev = 0.130
  CI (99.9%): [6.585, 11.319] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ops/ms
# Warmup Iteration   2: 6.758 ops/ms
# Warmup Iteration   3: 7.036 ops/ms
Iteration   1: 6.967 ops/ms
Iteration   2: 7.040 ops/ms
Iteration   3: 6.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.952 ±(99.9%) 1.772 ops/ms [Average]
  (min, avg, max) = (6.848, 6.952, 7.040), stdev = 0.097
  CI (99.9%): [5.180, 8.724] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 5.288 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.020 ms/op
Iteration   1: 3.685 ±(99.9%) 0.003 ms/op
Iteration   2: 3.686 ±(99.9%) 0.003 ms/op
Iteration   3: 3.661 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.678 ±(99.9%) 0.266 ms/op [Average]
  (min, avg, max) = (3.661, 3.678, 3.686), stdev = 0.015
  CI (99.9%): [3.412, 3.944] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.731 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.698 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.002 ms/op
Iteration   1: 3.314 ±(99.9%) 0.003 ms/op
Iteration   2: 3.401 ±(99.9%) 0.003 ms/op
Iteration   3: 3.463 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.393 ±(99.9%) 1.359 ms/op [Average]
  (min, avg, max) = (3.314, 3.393, 3.463), stdev = 0.075
  CI (99.9%): [2.033, 4.752] (assumes normal distribution)


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
# Warmup Iteration   1: 4.982 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.746 ±(99.9%) 0.004 ms/op
Iteration   1: 3.680 ±(99.9%) 0.003 ms/op
Iteration   2: 3.647 ±(99.9%) 0.005 ms/op
Iteration   3: 3.660 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.662 ±(99.9%) 0.300 ms/op [Average]
  (min, avg, max) = (3.647, 3.662, 3.680), stdev = 0.016
  CI (99.9%): [3.363, 3.962] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.503 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.972 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.718 ±(99.9%) 0.013 ms/op
Iteration   1: 4.614 ±(99.9%) 0.008 ms/op
Iteration   2: 4.660 ±(99.9%) 0.010 ms/op
Iteration   3: 4.657 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.644 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (4.614, 4.644, 4.660), stdev = 0.026
  CI (99.9%): [4.174, 5.114] (assumes normal distribution)


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
# Warmup Iteration   1: 5.621 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.835 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.593 ±(99.9%) 0.008 ms/op
Iteration   1: 3.559 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.151 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.137 ms/op
                 createUser·p0.95:   4.481 ms/op
                 createUser·p0.99:   5.562 ms/op
                 createUser·p0.999:  9.685 ms/op
                 createUser·p0.9999: 14.828 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.581 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.903 ms/op
                 createUser·p0.50:   3.547 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   5.276 ms/op
                 createUser·p0.999:  9.404 ms/op
                 createUser·p0.9999: 16.531 ms/op
                 createUser·p1.00:   17.007 ms/op

Iteration   3: 3.623 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.678 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  13.245 ms/op
                 createUser·p0.9999: 19.666 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 267479
  mean =      3.587 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5878 
    [ 2.500,  5.000) = 255935 
    [ 5.000,  7.500) = 5037 
    [ 7.500, 10.000) = 326 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =     10.658 ms/op
     p(99.9900) =     18.981 ms/op
     p(99.9990) =     20.075 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.029 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.009 ms/op
Iteration   1: 3.491 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   3.449 ms/op
                 existUser·p0.90:   4.108 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.349 ms/op
                 existUser·p0.999:  8.362 ms/op
                 existUser·p0.9999: 14.869 ms/op
                 existUser·p1.00:   15.417 ms/op

Iteration   2: 3.341 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.750 ms/op
                 existUser·p0.50:   3.346 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.235 ms/op
                 existUser·p0.99:   4.866 ms/op
                 existUser·p0.999:  6.939 ms/op
                 existUser·p0.9999: 16.380 ms/op
                 existUser·p1.00:   18.317 ms/op

Iteration   3: 3.327 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.888 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.854 ms/op
                 existUser·p0.95:   4.149 ms/op
                 existUser·p0.99:   5.300 ms/op
                 existUser·p0.999:  11.086 ms/op
                 existUser·p0.9999: 18.219 ms/op
                 existUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 283386
  mean =      3.385 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 496 
    [ 1.250,  2.500) = 13126 
    [ 2.500,  3.750) = 216458 
    [ 3.750,  5.000) = 49745 
    [ 5.000,  6.250) = 2518 
    [ 6.250,  7.500) = 494 
    [ 7.500,  8.750) = 191 
    [ 8.750, 10.000) = 65 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 63 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.990 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     10.234 ms/op
     p(99.9900) =     16.663 ms/op
     p(99.9990) =     18.394 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 5.161 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.748 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.640 ±(99.9%) 0.009 ms/op
Iteration   1: 3.560 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.249 ms/op
                 getUser·p0.50:   3.543 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.472 ms/op
                 getUser·p0.999:  10.920 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.565 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.518 ms/op
                 getUser·p0.90:   4.145 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  9.541 ms/op
                 getUser·p0.9999: 17.466 ms/op
                 getUser·p1.00:   17.826 ms/op

Iteration   3: 3.630 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.993 ms/op
                 getUser·p0.50:   3.604 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.880 ms/op
                 getUser·p0.9999: 21.070 ms/op
                 getUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 267831
  mean =      3.584 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11830 
    [ 2.500,  5.000) = 250415 
    [ 5.000,  7.500) = 4972 
    [ 7.500, 10.000) = 385 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.925 ms/op
     p(50.0000) =      3.551 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.292 ms/op
     p(99.9900) =     20.979 ms/op
     p(99.9990) =     21.648 ms/op
     p(99.9999) =     21.725 ms/op
    p(100.0000) =     21.725 ms/op


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
# Warmup Iteration   1: 6.552 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.004 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.958 ±(99.9%) 0.019 ms/op
Iteration   1: 4.783 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.235 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.480 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   8.897 ms/op
                 listUser·p0.999:  15.452 ms/op
                 listUser·p0.9999: 20.696 ms/op
                 listUser·p1.00:   21.430 ms/op

Iteration   2: 4.681 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.978 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.176 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  17.489 ms/op
                 listUser·p0.9999: 25.112 ms/op
                 listUser·p1.00:   25.657 ms/op

Iteration   3: 4.732 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   4.481 ms/op
                 listUser·p0.90:   6.218 ms/op
                 listUser·p0.95:   6.988 ms/op
                 listUser·p0.99:   8.688 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 24.076 ms/op
                 listUser·p1.00:   24.904 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 202821
  mean =      4.732 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 929 
    [ 2.500,  5.000) = 148582 
    [ 5.000,  7.500) = 46410 
    [ 7.500, 10.000) = 6045 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 104 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 82 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.978 ms/op
     p(50.0000) =      4.465 ms/op
     p(90.0000) =      6.373 ms/op
     p(95.0000) =      7.152 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     17.897 ms/op
     p(99.9900) =     24.342 ms/op
     p(99.9990) =     25.493 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.174 ± 3.739  ops/ms
ClientGrpc.existUser                       thrpt       3   9.248 ± 1.294  ops/ms
ClientGrpc.getUser                         thrpt       3   8.952 ± 2.367  ops/ms
ClientGrpc.listUser                        thrpt       3   6.952 ± 1.772  ops/ms
ClientGrpc.createUser                       avgt       3   3.678 ± 0.266   ms/op
ClientGrpc.existUser                        avgt       3   3.393 ± 1.359   ms/op
ClientGrpc.getUser                          avgt       3   3.662 ± 0.300   ms/op
ClientGrpc.listUser                         avgt       3   4.644 ± 0.470   ms/op
ClientGrpc.createUser                     sample  267479   3.587 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.903           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.531           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.658           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.981           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.218           ms/op
ClientGrpc.existUser                      sample  283386   3.385 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.683           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.363           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.268           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.234           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.547           ms/op
ClientGrpc.getUser                        sample  267831   3.584 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.925           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.551           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.497           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.292           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.979           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.725           ms/op
ClientGrpc.listUser                       sample  202821   4.732 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.978           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.373           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.152           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.765           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.897           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.342           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.657           ms/op
