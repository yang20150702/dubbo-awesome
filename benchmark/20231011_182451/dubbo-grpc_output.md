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
# Warmup Iteration   1: 3.370 ops/ms
# Warmup Iteration   2: 6.451 ops/ms
# Warmup Iteration   3: 7.878 ops/ms
Iteration   1: 8.293 ops/ms
Iteration   2: 8.333 ops/ms
Iteration   3: 8.379 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.335 ±(99.9%) 0.782 ops/ms [Average]
  (min, avg, max) = (8.293, 8.335, 8.379), stdev = 0.043
  CI (99.9%): [7.552, 9.117] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.872 ops/ms
# Warmup Iteration   2: 8.551 ops/ms
# Warmup Iteration   3: 8.717 ops/ms
Iteration   1: 9.004 ops/ms
Iteration   2: 8.882 ops/ms
Iteration   3: 9.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.001 ±(99.9%) 2.166 ops/ms [Average]
  (min, avg, max) = (8.882, 9.001, 9.119), stdev = 0.119
  CI (99.9%): [6.836, 11.167] (assumes normal distribution)


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
# Warmup Iteration   1: 5.140 ops/ms
# Warmup Iteration   2: 7.947 ops/ms
# Warmup Iteration   3: 8.492 ops/ms
Iteration   1: 8.452 ops/ms
Iteration   2: 8.528 ops/ms
Iteration   3: 8.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.548 ±(99.9%) 1.948 ops/ms [Average]
  (min, avg, max) = (8.452, 8.548, 8.663), stdev = 0.107
  CI (99.9%): [6.599, 10.496] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.442 ops/ms
# Warmup Iteration   2: 5.900 ops/ms
# Warmup Iteration   3: 6.385 ops/ms
Iteration   1: 6.608 ops/ms
Iteration   2: 6.387 ops/ms
Iteration   3: 6.539 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.511 ±(99.9%) 2.059 ops/ms [Average]
  (min, avg, max) = (6.387, 6.511, 6.608), stdev = 0.113
  CI (99.9%): [4.452, 8.571] (assumes normal distribution)


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
# Warmup Iteration   1: 5.604 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.994 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.006 ms/op
Iteration   1: 3.776 ±(99.9%) 0.004 ms/op
Iteration   2: 3.706 ±(99.9%) 0.004 ms/op
Iteration   3: 3.714 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.732 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.706, 3.732, 3.776), stdev = 0.039
  CI (99.9%): [3.029, 4.435] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.135 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.771 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.004 ms/op
Iteration   1: 3.573 ±(99.9%) 0.005 ms/op
Iteration   2: 3.483 ±(99.9%) 0.005 ms/op
Iteration   3: 3.581 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.546 ±(99.9%) 0.996 ms/op [Average]
  (min, avg, max) = (3.483, 3.546, 3.581), stdev = 0.055
  CI (99.9%): [2.550, 4.542] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.588 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.973 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.008 ms/op
Iteration   1: 3.788 ±(99.9%) 0.005 ms/op
Iteration   2: 3.742 ±(99.9%) 0.005 ms/op
Iteration   3: 3.745 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.758 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.742, 3.758, 3.788), stdev = 0.026
  CI (99.9%): [3.285, 4.232] (assumes normal distribution)


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
# Warmup Iteration   1: 7.210 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 5.235 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.965 ±(99.9%) 0.018 ms/op
Iteration   1: 4.780 ±(99.9%) 0.009 ms/op
Iteration   2: 4.827 ±(99.9%) 0.014 ms/op
Iteration   3: 4.644 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.750 ±(99.9%) 1.725 ms/op [Average]
  (min, avg, max) = (4.644, 4.750, 4.827), stdev = 0.095
  CI (99.9%): [3.025, 6.476] (assumes normal distribution)


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
# Warmup Iteration   1: 5.545 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 3.969 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.848 ±(99.9%) 0.010 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.703 ms/op
                 createUser·p0.90:   4.497 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.504 ms/op
                 createUser·p0.999:  13.393 ms/op
                 createUser·p0.9999: 19.844 ms/op
                 createUser·p1.00:   20.382 ms/op

Iteration   2: 3.766 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.603 ms/op
                 createUser·p0.999:  10.549 ms/op
                 createUser·p0.9999: 22.167 ms/op
                 createUser·p1.00:   22.675 ms/op

Iteration   3: 3.835 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.853 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.948 ms/op
                 createUser·p0.99:   6.849 ms/op
                 createUser·p0.999:  19.484 ms/op
                 createUser·p0.9999: 32.178 ms/op
                 createUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252560
  mean =      3.801 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5816 
    [ 2.500,  5.000) = 236100 
    [ 5.000,  7.500) = 9086 
    [ 7.500, 10.000) = 1011 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.707 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.139 ms/op
     p(99.9900) =     31.711 ms/op
     p(99.9990) =     32.539 ms/op
     p(99.9999) =     32.571 ms/op
    p(100.0000) =     32.571 ms/op


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
# Warmup Iteration   1: 5.253 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 3.857 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.737 ±(99.9%) 0.009 ms/op
Iteration   1: 3.652 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.671 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   5.792 ms/op
                 existUser·p0.999:  14.047 ms/op
                 existUser·p0.9999: 15.961 ms/op
                 existUser·p1.00:   18.448 ms/op

Iteration   2: 3.534 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.837 ms/op
                 existUser·p0.50:   3.502 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.555 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 23.593 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.022 ms/op
                 existUser·p0.95:   4.456 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  14.021 ms/op
                 existUser·p0.9999: 22.081 ms/op
                 existUser·p1.00:   22.217 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269056
  mean =      3.569 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9937 
    [ 2.500,  5.000) = 252444 
    [ 5.000,  7.500) = 5866 
    [ 7.500, 10.000) = 463 
    [10.000, 12.500) = 90 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.671 ms/op
     p(50.0000) =      3.518 ms/op
     p(90.0000) =      4.190 ms/op
     p(95.0000) =      4.547 ms/op
     p(99.0000) =      5.841 ms/op
     p(99.9000) =     12.057 ms/op
     p(99.9900) =     22.154 ms/op
     p(99.9990) =     24.481 ms/op
     p(99.9999) =     24.773 ms/op
    p(100.0000) =     24.773 ms/op


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
# Warmup Iteration   1: 5.380 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.005 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.871 ±(99.9%) 0.010 ms/op
Iteration   1: 3.785 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   3.707 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.308 ms/op
                 getUser·p0.999:  9.462 ms/op
                 getUser·p0.9999: 18.579 ms/op
                 getUser·p1.00:   19.071 ms/op

Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.933 ms/op
                 getUser·p0.50:   3.789 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   5.017 ms/op
                 getUser·p0.99:   7.209 ms/op
                 getUser·p0.999:  13.058 ms/op
                 getUser·p0.9999: 17.189 ms/op
                 getUser·p1.00:   18.809 ms/op

Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.826 ms/op
                 getUser·p0.50:   3.695 ms/op
                 getUser·p0.90:   4.555 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  14.818 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   22.774 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251284
  mean =      3.822 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6352 
    [ 2.500,  5.000) = 234181 
    [ 5.000,  7.500) = 9183 
    [ 7.500, 10.000) = 1033 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      3.727 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.586 ms/op
     p(99.9000) =     12.988 ms/op
     p(99.9900) =     18.579 ms/op
     p(99.9990) =     22.457 ms/op
     p(99.9999) =     22.774 ms/op
    p(100.0000) =     22.774 ms/op


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
# Warmup Iteration   1: 6.650 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 5.115 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.810 ±(99.9%) 0.014 ms/op
Iteration   1: 4.793 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.116 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.865 ms/op
                 listUser·p0.95:   6.824 ms/op
                 listUser·p0.99:   8.733 ms/op
                 listUser·p0.999:  16.810 ms/op
                 listUser·p0.9999: 26.804 ms/op
                 listUser·p1.00:   28.574 ms/op

Iteration   2: 4.770 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.663 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.906 ms/op
                 listUser·p0.99:   8.552 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 19.486 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.865 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.202 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.915 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  19.464 ms/op
                 listUser·p0.9999: 24.852 ms/op
                 listUser·p1.00:   25.362 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199625
  mean =      4.809 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 519 
    [ 2.500,  5.000) = 146859 
    [ 5.000,  7.500) = 46085 
    [ 7.500, 10.000) = 5231 
    [10.000, 12.500) = 415 
    [12.500, 15.000) = 137 
    [15.000, 17.500) = 167 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      1.116 ms/op
     p(50.0000) =      4.628 ms/op
     p(90.0000) =      5.890 ms/op
     p(95.0000) =      6.857 ms/op
     p(99.0000) =      8.700 ms/op
     p(99.9000) =     17.883 ms/op
     p(99.9900) =     25.040 ms/op
     p(99.9990) =     28.410 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.335 ± 0.782  ops/ms
ClientGrpc.existUser                       thrpt       3   9.001 ± 2.166  ops/ms
ClientGrpc.getUser                         thrpt       3   8.548 ± 1.948  ops/ms
ClientGrpc.listUser                        thrpt       3   6.511 ± 2.059  ops/ms
ClientGrpc.createUser                       avgt       3   3.732 ± 0.703   ms/op
ClientGrpc.existUser                        avgt       3   3.546 ± 0.996   ms/op
ClientGrpc.getUser                          avgt       3   3.758 ± 0.473   ms/op
ClientGrpc.listUser                         avgt       3   4.750 ± 1.725   ms/op
ClientGrpc.createUser                     sample  252560   3.801 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.850           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.506           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.139           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          31.711           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          32.571           ms/op
ClientGrpc.existUser                      sample  269056   3.569 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.671           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.518           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.841           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.057           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.154           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.773           ms/op
ClientGrpc.getUser                        sample  251284   3.822 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.826           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.727           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.915           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.586           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.579           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.774           ms/op
ClientGrpc.listUser                       sample  199625   4.809 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.116           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.628           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.890           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.857           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.700           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.883           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.040           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.574           ms/op
