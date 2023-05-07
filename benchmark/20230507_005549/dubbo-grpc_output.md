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
# Warmup Iteration   1: 4.485 ops/ms
# Warmup Iteration   2: 9.551 ops/ms
# Warmup Iteration   3: 10.373 ops/ms
Iteration   1: 10.701 ops/ms
Iteration   2: 10.991 ops/ms
Iteration   3: 10.674 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.789 ±(99.9%) 3.208 ops/ms [Average]
  (min, avg, max) = (10.674, 10.789, 10.991), stdev = 0.176
  CI (99.9%): [7.581, 13.996] (assumes normal distribution)


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
# Warmup Iteration   1: 8.210 ops/ms
# Warmup Iteration   2: 10.698 ops/ms
# Warmup Iteration   3: 11.376 ops/ms
Iteration   1: 11.265 ops/ms
Iteration   2: 11.404 ops/ms
Iteration   3: 11.684 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.451 ±(99.9%) 3.899 ops/ms [Average]
  (min, avg, max) = (11.265, 11.451, 11.684), stdev = 0.214
  CI (99.9%): [7.552, 15.350] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.915 ops/ms
# Warmup Iteration   2: 10.653 ops/ms
# Warmup Iteration   3: 10.952 ops/ms
Iteration   1: 10.920 ops/ms
Iteration   2: 10.966 ops/ms
Iteration   3: 10.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.952 ±(99.9%) 0.516 ops/ms [Average]
  (min, avg, max) = (10.920, 10.952, 10.971), stdev = 0.028
  CI (99.9%): [10.436, 11.469] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.654 ops/ms
# Warmup Iteration   2: 8.522 ops/ms
# Warmup Iteration   3: 8.705 ops/ms
Iteration   1: 8.568 ops/ms
Iteration   2: 8.488 ops/ms
Iteration   3: 8.510 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.522 ±(99.9%) 0.752 ops/ms [Average]
  (min, avg, max) = (8.488, 8.522, 8.568), stdev = 0.041
  CI (99.9%): [7.770, 9.274] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.993 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.003 ms/op
Iteration   1: 2.954 ±(99.9%) 0.002 ms/op
Iteration   2: 3.059 ±(99.9%) 0.002 ms/op
Iteration   3: 2.943 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.985 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (2.943, 2.985, 3.059), stdev = 0.064
  CI (99.9%): [1.814, 4.157] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.850 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.914 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 2.807 ±(99.9%) 0.003 ms/op
Iteration   1: 2.844 ±(99.9%) 0.003 ms/op
Iteration   2: 2.840 ±(99.9%) 0.003 ms/op
Iteration   3: 2.797 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.827 ±(99.9%) 0.472 ms/op [Average]
  (min, avg, max) = (2.797, 2.827, 2.844), stdev = 0.026
  CI (99.9%): [2.355, 3.299] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 3.764 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.895 ±(99.9%) 0.003 ms/op
Iteration   1: 2.900 ±(99.9%) 0.002 ms/op
Iteration   2: 2.901 ±(99.9%) 0.002 ms/op
Iteration   3: 2.918 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.906 ±(99.9%) 0.184 ms/op [Average]
  (min, avg, max) = (2.900, 2.906, 2.918), stdev = 0.010
  CI (99.9%): [2.722, 3.090] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.932 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.871 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.035 ms/op
Iteration   1: 3.768 ±(99.9%) 0.006 ms/op
Iteration   2: 3.713 ±(99.9%) 0.017 ms/op
Iteration   3: 3.728 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.736 ±(99.9%) 0.520 ms/op [Average]
  (min, avg, max) = (3.713, 3.736, 3.768), stdev = 0.029
  CI (99.9%): [3.216, 4.256] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.418 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.136 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
Iteration   1: 2.955 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.437 ms/op
                 createUser·p0.95:   3.654 ms/op
                 createUser·p0.99:   4.186 ms/op
                 createUser·p0.999:  6.881 ms/op
                 createUser·p0.9999: 12.330 ms/op
                 createUser·p1.00:   12.583 ms/op

Iteration   2: 2.919 ±(99.9%) 0.004 ms/op
                 createUser·p0.00:   0.510 ms/op
                 createUser·p0.50:   2.916 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   3.908 ms/op
                 createUser·p0.999:  6.861 ms/op
                 createUser·p0.9999: 12.501 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   3: 2.961 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.606 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  9.723 ms/op
                 createUser·p0.9999: 26.444 ms/op
                 createUser·p1.00:   26.837 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 325949
  mean =      2.945 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26298 
    [ 2.500,  5.000) = 298696 
    [ 5.000,  7.500) = 603 
    [ 7.500, 10.000) = 119 
    [10.000, 12.500) = 116 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.367 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.141 ms/op
     p(99.9000) =      7.685 ms/op
     p(99.9900) =     24.839 ms/op
     p(99.9990) =     26.697 ms/op
     p(99.9999) =     26.837 ms/op
    p(100.0000) =     26.837 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.729 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.942 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.741 ±(99.9%) 0.007 ms/op
Iteration   1: 2.730 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.789 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.375 ms/op
                 existUser·p0.999:  6.357 ms/op
                 existUser·p0.9999: 12.691 ms/op
                 existUser·p1.00:   12.960 ms/op

Iteration   2: 2.849 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.351 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  6.289 ms/op
                 existUser·p0.9999: 23.429 ms/op
                 existUser·p1.00:   23.724 ms/op

Iteration   3: 2.825 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.507 ms/op
                 existUser·p0.50:   2.839 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.543 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  6.152 ms/op
                 existUser·p0.9999: 16.040 ms/op
                 existUser·p1.00:   16.187 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 342637
  mean =      2.801 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 63655 
    [ 2.500,  5.000) = 277935 
    [ 5.000,  7.500) = 819 
    [ 7.500, 10.000) = 68 
    [10.000, 12.500) = 47 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.559 ms/op
     p(99.0000) =      4.317 ms/op
     p(99.9000) =      6.262 ms/op
     p(99.9900) =     17.383 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.724 ms/op
    p(100.0000) =     23.724 ms/op


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
# Warmup Iteration   1: 3.819 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.005 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.937 ±(99.9%) 0.006 ms/op
Iteration   1: 2.940 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.688 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  6.334 ms/op
                 getUser·p0.9999: 12.831 ms/op
                 getUser·p1.00:   13.074 ms/op

Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.961 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.641 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.283 ms/op
                 getUser·p0.9999: 21.152 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 2.944 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.514 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.351 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.085 ms/op
                 getUser·p0.9999: 24.487 ms/op
                 getUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 324863
  mean =      2.954 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27546 
    [ 2.500,  5.000) = 296474 
    [ 5.000,  7.500) = 610 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.514 ms/op
     p(50.0000) =      2.945 ms/op
     p(90.0000) =      3.408 ms/op
     p(95.0000) =      3.621 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.243 ms/op
     p(99.9900) =     22.655 ms/op
     p(99.9990) =     24.773 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.641 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.562 ms/op
                 listUser·p0.999:  13.239 ms/op
                 listUser·p0.9999: 15.065 ms/op
                 listUser·p1.00:   16.777 ms/op

Iteration   2: 3.687 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.712 ms/op
                 listUser·p0.50:   3.568 ms/op
                 listUser·p0.90:   4.604 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.463 ms/op
                 listUser·p0.999:  15.244 ms/op
                 listUser·p0.9999: 16.689 ms/op
                 listUser·p1.00:   17.465 ms/op

Iteration   3: 3.881 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.979 ms/op
                 listUser·p0.50:   3.686 ms/op
                 listUser·p0.90:   5.074 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   7.040 ms/op
                 listUser·p0.999:  18.892 ms/op
                 listUser·p0.9999: 21.693 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 253608
  mean =      3.787 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7223 
    [ 2.500,  5.000) = 224465 
    [ 5.000,  7.500) = 20804 
    [ 7.500, 10.000) = 585 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 166 
    [17.500, 20.000) = 49 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     15.237 ms/op
     p(99.9900) =     20.894 ms/op
     p(99.9990) =     21.839 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.789 ± 3.208  ops/ms
ClientGrpc.existUser                       thrpt       3  11.451 ± 3.899  ops/ms
ClientGrpc.getUser                         thrpt       3  10.952 ± 0.516  ops/ms
ClientGrpc.listUser                        thrpt       3   8.522 ± 0.752  ops/ms
ClientGrpc.createUser                       avgt       3   2.985 ± 1.171   ms/op
ClientGrpc.existUser                        avgt       3   2.827 ± 0.472   ms/op
ClientGrpc.getUser                          avgt       3   2.906 ± 0.184   ms/op
ClientGrpc.listUser                         avgt       3   3.736 ± 0.520   ms/op
ClientGrpc.createUser                     sample  325949   2.945 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.510           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.937           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.367           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.141           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.685           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.839           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.837           ms/op
ClientGrpc.existUser                      sample  342637   2.801 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.467           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.826           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.559           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.262           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.383           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.724           ms/op
ClientGrpc.getUser                        sample  324863   2.954 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.514           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.945           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.408           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.621           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.211           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.243           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.655           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.871           ms/op
ClientGrpc.listUser                       sample  253608   3.787 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.712           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.629           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.850           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.237           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.894           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
