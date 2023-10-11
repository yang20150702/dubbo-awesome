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
# Warmup Iteration   1: 3.261 ops/ms
# Warmup Iteration   2: 7.302 ops/ms
# Warmup Iteration   3: 8.260 ops/ms
Iteration   1: 8.657 ops/ms
Iteration   2: 8.706 ops/ms
Iteration   3: 8.546 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.636 ±(99.9%) 1.495 ops/ms [Average]
  (min, avg, max) = (8.546, 8.636, 8.706), stdev = 0.082
  CI (99.9%): [7.142, 10.131] (assumes normal distribution)


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
# Warmup Iteration   1: 5.874 ops/ms
# Warmup Iteration   2: 8.675 ops/ms
# Warmup Iteration   3: 9.042 ops/ms
Iteration   1: 9.095 ops/ms
Iteration   2: 8.927 ops/ms
Iteration   3: 9.046 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.023 ±(99.9%) 1.576 ops/ms [Average]
  (min, avg, max) = (8.927, 9.023, 9.095), stdev = 0.086
  CI (99.9%): [7.447, 10.599] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.942 ops/ms
# Warmup Iteration   2: 8.394 ops/ms
# Warmup Iteration   3: 8.405 ops/ms
Iteration   1: 8.610 ops/ms
Iteration   2: 8.494 ops/ms
Iteration   3: 8.605 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.570 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (8.494, 8.570, 8.610), stdev = 0.066
  CI (99.9%): [7.370, 9.769] (assumes normal distribution)


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
# Warmup Iteration   1: 4.335 ops/ms
# Warmup Iteration   2: 6.726 ops/ms
# Warmup Iteration   3: 6.934 ops/ms
Iteration   1: 6.926 ops/ms
Iteration   2: 6.929 ops/ms
Iteration   3: 6.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.914 ±(99.9%) 0.401 ops/ms [Average]
  (min, avg, max) = (6.889, 6.914, 6.929), stdev = 0.022
  CI (99.9%): [6.514, 7.315] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.298 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.724 ±(99.9%) 0.013 ms/op
Iteration   1: 3.660 ±(99.9%) 0.001 ms/op
Iteration   2: 3.768 ±(99.9%) 0.003 ms/op
Iteration   3: 3.639 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.689 ±(99.9%) 1.263 ms/op [Average]
  (min, avg, max) = (3.639, 3.689, 3.768), stdev = 0.069
  CI (99.9%): [2.426, 4.952] (assumes normal distribution)


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
# Warmup Iteration   1: 4.655 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.621 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.550 ±(99.9%) 0.002 ms/op
Iteration   1: 3.542 ±(99.9%) 0.002 ms/op
Iteration   2: 3.433 ±(99.9%) 0.002 ms/op
Iteration   3: 3.515 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.497 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (3.433, 3.497, 3.542), stdev = 0.056
  CI (99.9%): [2.468, 4.525] (assumes normal distribution)


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
# Warmup Iteration   1: 5.192 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.823 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.676 ±(99.9%) 0.004 ms/op
Iteration   1: 3.663 ±(99.9%) 0.003 ms/op
Iteration   2: 3.662 ±(99.9%) 0.003 ms/op
Iteration   3: 3.729 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.684 ±(99.9%) 0.701 ms/op [Average]
  (min, avg, max) = (3.662, 3.684, 3.729), stdev = 0.038
  CI (99.9%): [2.983, 4.386] (assumes normal distribution)


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
# Warmup Iteration   1: 6.360 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 5.105 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.668 ±(99.9%) 0.013 ms/op
Iteration   1: 4.607 ±(99.9%) 0.012 ms/op
Iteration   2: 4.604 ±(99.9%) 0.025 ms/op
Iteration   3: 4.642 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.617 ±(99.9%) 0.389 ms/op [Average]
  (min, avg, max) = (4.604, 4.617, 4.642), stdev = 0.021
  CI (99.9%): [4.229, 5.006] (assumes normal distribution)


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
# Warmup Iteration   1: 4.900 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.911 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.008 ms/op
Iteration   1: 3.676 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.725 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.252 ms/op
                 createUser·p0.95:   4.448 ms/op
                 createUser·p0.99:   5.595 ms/op
                 createUser·p0.999:  9.815 ms/op
                 createUser·p0.9999: 20.424 ms/op
                 createUser·p1.00:   20.873 ms/op

Iteration   2: 3.653 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.821 ms/op
                 createUser·p0.50:   3.596 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.095 ms/op
                 createUser·p0.999:  11.043 ms/op
                 createUser·p0.9999: 19.636 ms/op
                 createUser·p1.00:   20.709 ms/op

Iteration   3: 3.627 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.959 ms/op
                 createUser·p0.50:   3.564 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.440 ms/op
                 createUser·p0.99:   5.104 ms/op
                 createUser·p0.999:  8.098 ms/op
                 createUser·p0.9999: 19.834 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 262827
  mean =      3.652 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1610 
    [ 2.500,  5.000) = 257669 
    [ 5.000,  7.500) = 2889 
    [ 7.500, 10.000) = 411 
    [10.000, 12.500) = 59 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 118 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.725 ms/op
     p(50.0000) =      3.592 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.448 ms/op
     p(99.0000) =      5.243 ms/op
     p(99.9000) =      9.404 ms/op
     p(99.9900) =     20.298 ms/op
     p(99.9990) =     20.734 ms/op
     p(99.9999) =     20.873 ms/op
    p(100.0000) =     20.873 ms/op


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
# Warmup Iteration   1: 4.078 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.687 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.007 ms/op
Iteration   1: 3.586 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.726 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  8.181 ms/op
                 existUser·p0.9999: 13.963 ms/op
                 existUser·p1.00:   19.595 ms/op

Iteration   2: 3.539 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.149 ms/op
                 existUser·p0.95:   4.358 ms/op
                 existUser·p0.99:   5.046 ms/op
                 existUser·p0.999:  9.972 ms/op
                 existUser·p0.9999: 15.597 ms/op
                 existUser·p1.00:   15.860 ms/op

Iteration   3: 3.579 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.786 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  12.063 ms/op
                 existUser·p0.9999: 19.533 ms/op
                 existUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268974
  mean =      3.568 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 301 
    [ 1.250,  2.500) = 3839 
    [ 2.500,  3.750) = 180135 
    [ 3.750,  5.000) = 81666 
    [ 5.000,  6.250) = 1882 
    [ 6.250,  7.500) = 510 
    [ 7.500,  8.750) = 271 
    [ 8.750, 10.000) = 115 
    [10.000, 11.250) = 60 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 46 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.726 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =      9.765 ms/op
     p(99.9900) =     19.038 ms/op
     p(99.9990) =     19.802 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


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
# Warmup Iteration   1: 5.118 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.780 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.734 ±(99.9%) 0.009 ms/op
Iteration   1: 3.700 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.872 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.383 ms/op
                 getUser·p0.95:   4.563 ms/op
                 getUser·p0.99:   5.349 ms/op
                 getUser·p0.999:  8.889 ms/op
                 getUser·p0.9999: 19.214 ms/op
                 getUser·p1.00:   19.530 ms/op

Iteration   2: 3.627 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.904 ms/op
                 getUser·p0.50:   3.592 ms/op
                 getUser·p0.90:   4.170 ms/op
                 getUser·p0.95:   4.399 ms/op
                 getUser·p0.99:   4.899 ms/op
                 getUser·p0.999:  8.313 ms/op
                 getUser·p0.9999: 19.438 ms/op
                 getUser·p1.00:   19.726 ms/op

Iteration   3: 3.673 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.880 ms/op
                 getUser·p0.50:   3.617 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.603 ms/op
                 getUser·p0.999:  9.141 ms/op
                 getUser·p0.9999: 22.872 ms/op
                 getUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 261618
  mean =      3.666 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4057 
    [ 2.500,  5.000) = 253677 
    [ 5.000,  7.500) = 3349 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 37 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      5.300 ms/op
     p(99.9000) =      8.624 ms/op
     p(99.9900) =     20.895 ms/op
     p(99.9990) =     23.127 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 6.383 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 5.076 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.576 ±(99.9%) 0.012 ms/op
Iteration   1: 4.649 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.438 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.226 ms/op
                 listUser·p0.95:   6.111 ms/op
                 listUser·p0.99:   7.848 ms/op
                 listUser·p0.999:  14.680 ms/op
                 listUser·p0.9999: 16.255 ms/op
                 listUser·p1.00:   16.433 ms/op

Iteration   2: 4.593 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.153 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.791 ms/op
                 listUser·p0.999:  15.915 ms/op
                 listUser·p0.9999: 18.287 ms/op
                 listUser·p1.00:   18.776 ms/op

Iteration   3: 4.541 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.153 ms/op
                 listUser·p0.50:   4.473 ms/op
                 listUser·p0.90:   5.063 ms/op
                 listUser·p0.95:   5.616 ms/op
                 listUser·p0.99:   7.578 ms/op
                 listUser·p0.999:  17.615 ms/op
                 listUser·p0.9999: 19.988 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 208878
  mean =      4.594 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 179407 
    [ 5.000,  7.500) = 26247 
    [ 7.500, 10.000) = 2474 
    [10.000, 12.500) = 166 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 174 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.153 ms/op
     p(50.0000) =      4.497 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.741 ms/op
     p(99.9000) =     15.811 ms/op
     p(99.9900) =     19.694 ms/op
     p(99.9990) =     20.117 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.636 ± 1.495  ops/ms
ClientGrpc.existUser                       thrpt       3   9.023 ± 1.576  ops/ms
ClientGrpc.getUser                         thrpt       3   8.570 ± 1.200  ops/ms
ClientGrpc.listUser                        thrpt       3   6.914 ± 0.401  ops/ms
ClientGrpc.createUser                       avgt       3   3.689 ± 1.263   ms/op
ClientGrpc.existUser                        avgt       3   3.497 ± 1.029   ms/op
ClientGrpc.getUser                          avgt       3   3.684 ± 0.701   ms/op
ClientGrpc.listUser                         avgt       3   4.617 ± 0.389   ms/op
ClientGrpc.createUser                     sample  262827   3.652 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.725           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.592           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.227           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.448           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.243           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.404           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.298           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.873           ms/op
ClientGrpc.existUser                      sample  268974   3.568 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.726           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.120           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.765           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.038           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.956           ms/op
ClientGrpc.getUser                        sample  261618   3.666 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.872           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.276           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.514           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.300           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.624           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.895           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.265           ms/op
ClientGrpc.listUser                       sample  208878   4.594 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.153           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.497           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.741           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.811           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.694           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.185           ms/op
