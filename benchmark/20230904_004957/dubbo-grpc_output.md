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
# Warmup Iteration   1: 4.069 ops/ms
# Warmup Iteration   2: 8.706 ops/ms
# Warmup Iteration   3: 10.017 ops/ms
Iteration   1: 10.295 ops/ms
Iteration   2: 10.363 ops/ms
Iteration   3: 10.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.375 ±(99.9%) 1.587 ops/ms [Average]
  (min, avg, max) = (10.295, 10.375, 10.468), stdev = 0.087
  CI (99.9%): [8.788, 11.962] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.288 ops/ms
# Warmup Iteration   2: 10.279 ops/ms
# Warmup Iteration   3: 10.904 ops/ms
Iteration   1: 10.852 ops/ms
Iteration   2: 10.651 ops/ms
Iteration   3: 10.957 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.820 ±(99.9%) 2.837 ops/ms [Average]
  (min, avg, max) = (10.651, 10.820, 10.957), stdev = 0.156
  CI (99.9%): [7.983, 13.657] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.730 ops/ms
# Warmup Iteration   2: 9.941 ops/ms
# Warmup Iteration   3: 10.197 ops/ms
Iteration   1: 10.384 ops/ms
Iteration   2: 10.537 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.453 ±(99.9%) 1.423 ops/ms [Average]
  (min, avg, max) = (10.384, 10.453, 10.537), stdev = 0.078
  CI (99.9%): [9.029, 11.876] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.599 ops/ms
# Warmup Iteration   2: 7.724 ops/ms
# Warmup Iteration   3: 7.904 ops/ms
Iteration   1: 8.044 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 7.995 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.025 ±(99.9%) 0.472 ops/ms [Average]
  (min, avg, max) = (7.995, 8.025, 8.044), stdev = 0.026
  CI (99.9%): [7.553, 8.496] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.004 ms/op
Iteration   1: 3.093 ±(99.9%) 0.002 ms/op
Iteration   2: 2.961 ±(99.9%) 0.004 ms/op
Iteration   3: 3.134 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 1.650 ms/op [Average]
  (min, avg, max) = (2.961, 3.062, 3.134), stdev = 0.090
  CI (99.9%): [1.412, 4.712] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.848 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.002 ms/op
Iteration   1: 2.868 ±(99.9%) 0.003 ms/op
Iteration   2: 2.933 ±(99.9%) 0.002 ms/op
Iteration   3: 2.891 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.897 ±(99.9%) 0.594 ms/op [Average]
  (min, avg, max) = (2.868, 2.897, 2.933), stdev = 0.033
  CI (99.9%): [2.304, 3.491] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.423 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.189 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.003 ms/op
Iteration   1: 3.051 ±(99.9%) 0.003 ms/op
Iteration   2: 3.033 ±(99.9%) 0.003 ms/op
Iteration   3: 3.044 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.170 ms/op [Average]
  (min, avg, max) = (3.033, 3.043, 3.051), stdev = 0.009
  CI (99.9%): [2.872, 3.213] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.685 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.267 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.022 ms/op
Iteration   1: 4.080 ±(99.9%) 0.022 ms/op
Iteration   2: 4.034 ±(99.9%) 0.012 ms/op
Iteration   3: 3.994 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.036 ±(99.9%) 0.786 ms/op [Average]
  (min, avg, max) = (3.994, 4.036, 4.080), stdev = 0.043
  CI (99.9%): [3.251, 4.822] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.378 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.258 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.065 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.858 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.863 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  7.876 ms/op
                 createUser·p0.9999: 15.775 ms/op
                 createUser·p1.00:   16.351 ms/op

Iteration   2: 3.010 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  7.937 ms/op
                 createUser·p0.9999: 13.965 ms/op
                 createUser·p1.00:   14.189 ms/op

Iteration   3: 3.095 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.035 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.948 ms/op
                 createUser·p0.999:  8.716 ms/op
                 createUser·p0.9999: 23.986 ms/op
                 createUser·p1.00:   26.116 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 314345
  mean =      3.056 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21556 
    [ 2.500,  5.000) = 290545 
    [ 5.000,  7.500) = 1731 
    [ 7.500, 10.000) = 272 
    [10.000, 12.500) = 41 
    [12.500, 15.000) = 113 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.703 ms/op
     p(50.0000) =      3.015 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.776 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     23.026 ms/op
     p(99.9990) =     25.957 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.829 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.058 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.006 ms/op
Iteration   1: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.711 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  6.791 ms/op
                 existUser·p0.9999: 12.866 ms/op
                 existUser·p1.00:   13.435 ms/op

Iteration   2: 2.978 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.834 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  12.380 ms/op
                 existUser·p0.9999: 15.856 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   3: 2.983 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.628 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.547 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.128 ms/op
                 existUser·p0.9999: 18.547 ms/op
                 existUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323441
  mean =      2.966 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1555 
    [ 1.250,  2.500) = 40380 
    [ 2.500,  3.750) = 263466 
    [ 3.750,  5.000) = 16358 
    [ 5.000,  6.250) = 836 
    [ 6.250,  7.500) = 386 
    [ 7.500,  8.750) = 178 
    [ 8.750, 10.000) = 25 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 37 
    [15.000, 16.250) = 41 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.628 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.172 ms/op
     p(99.9900) =     16.971 ms/op
     p(99.9990) =     19.489 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.502 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.255 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.089 ±(99.9%) 0.006 ms/op
Iteration   1: 3.078 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.698 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.639 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  7.545 ms/op
                 getUser·p0.9999: 20.388 ms/op
                 getUser·p1.00:   20.480 ms/op

Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.874 ms/op
                 getUser·p0.999:  8.563 ms/op
                 getUser·p0.9999: 20.414 ms/op
                 getUser·p1.00:   21.922 ms/op

Iteration   3: 3.071 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.768 ms/op
                 getUser·p0.999:  8.379 ms/op
                 getUser·p0.9999: 23.462 ms/op
                 getUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313236
  mean =      3.064 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21893 
    [ 2.500,  5.000) = 289032 
    [ 5.000,  7.500) = 1907 
    [ 7.500, 10.000) = 190 
    [10.000, 12.500) = 22 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.698 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      3.842 ms/op
     p(99.0000) =      4.792 ms/op
     p(99.9000) =      8.192 ms/op
     p(99.9900) =     22.611 ms/op
     p(99.9990) =     24.227 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 5.464 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.041 ±(99.9%) 0.011 ms/op
Iteration   1: 3.978 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.870 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.947 ms/op
                 listUser·p0.99:   7.135 ms/op
                 listUser·p0.999:  15.818 ms/op
                 listUser·p0.9999: 20.213 ms/op
                 listUser·p1.00:   20.677 ms/op

Iteration   2: 4.037 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   4.833 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  14.314 ms/op
                 listUser·p0.9999: 21.961 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.990 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.793 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   6.070 ms/op
                 listUser·p0.99:   7.397 ms/op
                 listUser·p0.999:  18.973 ms/op
                 listUser·p0.9999: 23.790 ms/op
                 listUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240072
  mean =      4.002 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2995 
    [ 2.500,  5.000) = 213029 
    [ 5.000,  7.500) = 22159 
    [ 7.500, 10.000) = 1434 
    [10.000, 12.500) = 96 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.939 ms/op
     p(99.0000) =      7.258 ms/op
     p(99.9000) =     15.729 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     24.006 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.375 ± 1.587  ops/ms
ClientGrpc.existUser                       thrpt       3  10.820 ± 2.837  ops/ms
ClientGrpc.getUser                         thrpt       3  10.453 ± 1.423  ops/ms
ClientGrpc.listUser                        thrpt       3   8.025 ± 0.472  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 1.650   ms/op
ClientGrpc.existUser                        avgt       3   2.897 ± 0.594   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.170   ms/op
ClientGrpc.listUser                         avgt       3   4.036 ± 0.786   ms/op
ClientGrpc.createUser                     sample  314345   3.056 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.703           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.015           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.826           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.569           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.026           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.116           ms/op
ClientGrpc.existUser                      sample  323441   2.966 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.628           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.933           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.785           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.172           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.971           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.726           ms/op
ClientGrpc.getUser                        sample  313236   3.064 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.698           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.023           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.600           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.842           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.192           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.611           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  240072   4.002 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.793           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.834           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.005           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.939           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.258           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.729           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.315           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.379           ms/op
