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
# Warmup Iteration   1: 3.237 ops/ms
# Warmup Iteration   2: 6.766 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 8.075 ops/ms
Iteration   2: 8.491 ops/ms
Iteration   3: 8.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.315 ±(99.9%) 3.921 ops/ms [Average]
  (min, avg, max) = (8.075, 8.315, 8.491), stdev = 0.215
  CI (99.9%): [4.394, 12.236] (assumes normal distribution)


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
# Warmup Iteration   1: 6.046 ops/ms
# Warmup Iteration   2: 8.188 ops/ms
# Warmup Iteration   3: 8.552 ops/ms
Iteration   1: 8.685 ops/ms
Iteration   2: 9.011 ops/ms
Iteration   3: 8.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.796 ±(99.9%) 3.404 ops/ms [Average]
  (min, avg, max) = (8.685, 8.796, 9.011), stdev = 0.187
  CI (99.9%): [5.392, 12.199] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.098 ops/ms
# Warmup Iteration   2: 8.023 ops/ms
# Warmup Iteration   3: 7.970 ops/ms
Iteration   1: 8.447 ops/ms
Iteration   2: 8.241 ops/ms
Iteration   3: 8.342 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.343 ±(99.9%) 1.880 ops/ms [Average]
  (min, avg, max) = (8.241, 8.343, 8.447), stdev = 0.103
  CI (99.9%): [6.463, 10.223] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.341 ops/ms
# Warmup Iteration   2: 5.930 ops/ms
# Warmup Iteration   3: 6.520 ops/ms
Iteration   1: 6.390 ops/ms
Iteration   2: 6.536 ops/ms
Iteration   3: 6.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.489 ±(99.9%) 1.551 ops/ms [Average]
  (min, avg, max) = (6.390, 6.489, 6.539), stdev = 0.085
  CI (99.9%): [4.938, 8.039] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.496 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.952 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.836 ±(99.9%) 0.004 ms/op
Iteration   1: 3.821 ±(99.9%) 0.004 ms/op
Iteration   2: 3.875 ±(99.9%) 0.004 ms/op
Iteration   3: 3.812 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.836 ±(99.9%) 0.622 ms/op [Average]
  (min, avg, max) = (3.812, 3.836, 3.875), stdev = 0.034
  CI (99.9%): [3.214, 4.458] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.981 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.900 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.496 ±(99.9%) 0.004 ms/op
Iteration   1: 3.564 ±(99.9%) 0.005 ms/op
Iteration   2: 3.551 ±(99.9%) 0.003 ms/op
Iteration   3: 3.574 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.563 ±(99.9%) 0.204 ms/op [Average]
  (min, avg, max) = (3.551, 3.563, 3.574), stdev = 0.011
  CI (99.9%): [3.359, 3.767] (assumes normal distribution)


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
# Warmup Iteration   1: 5.349 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.711 ±(99.9%) 0.004 ms/op
Iteration   1: 3.729 ±(99.9%) 0.007 ms/op
Iteration   2: 3.806 ±(99.9%) 0.002 ms/op
Iteration   3: 3.690 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.742 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.690, 3.742, 3.806), stdev = 0.059
  CI (99.9%): [2.661, 4.822] (assumes normal distribution)


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
# Warmup Iteration   1: 6.584 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.294 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.150 ±(99.9%) 0.015 ms/op
Iteration   1: 5.047 ±(99.9%) 0.011 ms/op
Iteration   2: 5.037 ±(99.9%) 0.016 ms/op
Iteration   3: 4.975 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.020 ±(99.9%) 0.708 ms/op [Average]
  (min, avg, max) = (4.975, 5.020, 5.047), stdev = 0.039
  CI (99.9%): [4.311, 5.728] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.766 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.811 ±(99.9%) 0.013 ms/op
Iteration   1: 3.752 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.861 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.004 ms/op
                 createUser·p0.999:  13.284 ms/op
                 createUser·p0.9999: 14.549 ms/op
                 createUser·p1.00:   15.254 ms/op

Iteration   2: 3.816 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.723 ms/op
                 createUser·p0.999:  13.536 ms/op
                 createUser·p0.9999: 21.182 ms/op
                 createUser·p1.00:   21.823 ms/op

Iteration   3: 3.800 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.860 ms/op
                 createUser·p0.50:   3.752 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  11.807 ms/op
                 createUser·p0.9999: 28.049 ms/op
                 createUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253332
  mean =      3.789 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14551 
    [ 2.500,  5.000) = 225875 
    [ 5.000,  7.500) = 11318 
    [ 7.500, 10.000) = 1004 
    [10.000, 12.500) = 270 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 24 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.014 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     13.151 ms/op
     p(99.9900) =     21.223 ms/op
     p(99.9990) =     29.343 ms/op
     p(99.9999) =     29.393 ms/op
    p(100.0000) =     29.393 ms/op


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
# Warmup Iteration   1: 4.954 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.636 ±(99.9%) 0.009 ms/op
Iteration   1: 3.649 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.932 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.727 ms/op
                 existUser·p0.99:   6.406 ms/op
                 existUser·p0.999:  11.459 ms/op
                 existUser·p0.9999: 16.883 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 3.538 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.879 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.563 ms/op
                 existUser·p0.99:   5.849 ms/op
                 existUser·p0.999:  9.893 ms/op
                 existUser·p0.9999: 16.742 ms/op
                 existUser·p1.00:   17.170 ms/op

Iteration   3: 3.579 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   3.543 ms/op
                 existUser·p0.90:   4.211 ms/op
                 existUser·p0.95:   4.620 ms/op
                 existUser·p0.99:   7.086 ms/op
                 existUser·p0.999:  9.324 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 267510
  mean =      3.588 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15329 
    [ 2.500,  5.000) = 244451 
    [ 5.000,  7.500) = 6305 
    [ 7.500, 10.000) = 1120 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.879 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.637 ms/op
     p(99.0000) =      6.259 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     19.915 ms/op
     p(99.9990) =     20.862 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 5.181 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.996 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.856 ±(99.9%) 0.009 ms/op
Iteration   1: 3.865 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.921 ms/op
                 getUser·p0.50:   3.785 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   5.046 ms/op
                 getUser·p0.99:   6.808 ms/op
                 getUser·p0.999:  11.477 ms/op
                 getUser·p0.9999: 17.096 ms/op
                 getUser·p1.00:   17.367 ms/op

Iteration   2: 3.824 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.171 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  8.978 ms/op
                 getUser·p0.9999: 15.655 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   3: 3.814 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.854 ms/op
                 getUser·p0.50:   3.736 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.271 ms/op
                 getUser·p0.999:  10.781 ms/op
                 getUser·p0.9999: 23.233 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250423
  mean =      3.834 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7382 
    [ 2.500,  5.000) = 230948 
    [ 5.000,  7.500) = 10963 
    [ 7.500, 10.000) = 860 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.854 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     10.338 ms/op
     p(99.9900) =     23.101 ms/op
     p(99.9990) =     23.380 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 6.555 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 5.332 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.879 ±(99.9%) 0.014 ms/op
Iteration   1: 4.894 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.366 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   6.128 ms/op
                 listUser·p0.95:   7.071 ms/op
                 listUser·p0.99:   9.084 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 28.932 ms/op
                 listUser·p1.00:   29.164 ms/op

Iteration   2: 4.930 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.247 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   6.439 ms/op
                 listUser·p0.95:   7.251 ms/op
                 listUser·p0.99:   9.404 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 26.707 ms/op
                 listUser·p1.00:   27.263 ms/op

Iteration   3: 4.941 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.333 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.021 ms/op
                 listUser·p0.95:   6.767 ms/op
                 listUser·p0.99:   8.634 ms/op
                 listUser·p0.999:  20.686 ms/op
                 listUser·p0.9999: 32.672 ms/op
                 listUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194959
  mean =      4.921 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 214 
    [ 2.500,  5.000) = 132245 
    [ 5.000,  7.500) = 55655 
    [ 7.500, 10.000) = 5706 
    [10.000, 12.500) = 729 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.247 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.185 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     17.368 ms/op
     p(99.9900) =     32.064 ms/op
     p(99.9990) =     33.826 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.315 ± 3.921  ops/ms
ClientGrpc.existUser                       thrpt       3   8.796 ± 3.404  ops/ms
ClientGrpc.getUser                         thrpt       3   8.343 ± 1.880  ops/ms
ClientGrpc.listUser                        thrpt       3   6.489 ± 1.551  ops/ms
ClientGrpc.createUser                       avgt       3   3.836 ± 0.622   ms/op
ClientGrpc.existUser                        avgt       3   3.563 ± 0.204   ms/op
ClientGrpc.getUser                          avgt       3   3.742 ± 1.080   ms/op
ClientGrpc.listUser                         avgt       3   5.020 ± 0.708   ms/op
ClientGrpc.createUser                     sample  253332   3.789 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.835           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.579           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.014           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.151           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.223           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.393           ms/op
ClientGrpc.existUser                      sample  267510   3.588 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.879           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.555           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.637           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.259           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.256           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.915           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.070           ms/op
ClientGrpc.getUser                        sample  250423   3.834 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.854           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.981           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.382           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.338           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.101           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.002           ms/op
ClientGrpc.listUser                       sample  194959   4.921 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.247           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.185           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.044           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.368           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.064           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.013           ms/op
