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
# Warmup Iteration   1: 4.054 ops/ms
# Warmup Iteration   2: 8.709 ops/ms
# Warmup Iteration   3: 10.119 ops/ms
Iteration   1: 10.645 ops/ms
Iteration   2: 10.782 ops/ms
Iteration   3: 10.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.696 ±(99.9%) 1.373 ops/ms [Average]
  (min, avg, max) = (10.645, 10.696, 10.782), stdev = 0.075
  CI (99.9%): [9.323, 12.068] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.367 ops/ms
# Warmup Iteration   2: 10.596 ops/ms
# Warmup Iteration   3: 11.157 ops/ms
Iteration   1: 10.972 ops/ms
Iteration   2: 11.185 ops/ms
Iteration   3: 11.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.149 ±(99.9%) 2.949 ops/ms [Average]
  (min, avg, max) = (10.972, 11.149, 11.289), stdev = 0.162
  CI (99.9%): [8.199, 14.098] (assumes normal distribution)


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
# Warmup Iteration   1: 6.744 ops/ms
# Warmup Iteration   2: 10.168 ops/ms
# Warmup Iteration   3: 10.604 ops/ms
Iteration   1: 10.509 ops/ms
Iteration   2: 10.636 ops/ms
Iteration   3: 10.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.653 ±(99.9%) 2.797 ops/ms [Average]
  (min, avg, max) = (10.509, 10.653, 10.814), stdev = 0.153
  CI (99.9%): [7.856, 13.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.844 ops/ms
# Warmup Iteration   2: 8.006 ops/ms
# Warmup Iteration   3: 8.231 ops/ms
Iteration   1: 8.100 ops/ms
Iteration   2: 8.358 ops/ms
Iteration   3: 8.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.218 ±(99.9%) 2.378 ops/ms [Average]
  (min, avg, max) = (8.100, 8.218, 8.358), stdev = 0.130
  CI (99.9%): [5.840, 10.596] (assumes normal distribution)


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
# Warmup Iteration   1: 4.159 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.120 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.003 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.003 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.001 ±(99.9%) 0.546 ms/op [Average]
  (min, avg, max) = (2.970, 3.001, 3.030), stdev = 0.030
  CI (99.9%): [2.455, 3.547] (assumes normal distribution)


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
# Warmup Iteration   1: 3.810 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.981 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.003 ms/op
Iteration   1: 2.894 ±(99.9%) 0.001 ms/op
Iteration   2: 2.853 ±(99.9%) 0.004 ms/op
Iteration   3: 2.845 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.864 ±(99.9%) 0.475 ms/op [Average]
  (min, avg, max) = (2.845, 2.864, 2.894), stdev = 0.026
  CI (99.9%): [2.389, 3.339] (assumes normal distribution)


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
# Warmup Iteration   1: 4.027 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.087 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.004 ms/op
Iteration   1: 2.979 ±(99.9%) 0.003 ms/op
Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
Iteration   3: 2.963 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.997 ±(99.9%) 0.826 ms/op [Average]
  (min, avg, max) = (2.963, 2.997, 3.048), stdev = 0.045
  CI (99.9%): [2.171, 3.822] (assumes normal distribution)


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
# Warmup Iteration   1: 5.338 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 3.933 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.025 ms/op
Iteration   1: 3.878 ±(99.9%) 0.011 ms/op
Iteration   2: 3.816 ±(99.9%) 0.020 ms/op
Iteration   3: 3.863 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.853 ±(99.9%) 0.593 ms/op [Average]
  (min, avg, max) = (3.816, 3.853, 3.878), stdev = 0.033
  CI (99.9%): [3.259, 4.446] (assumes normal distribution)


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
# Warmup Iteration   1: 4.213 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.096 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.031 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.024 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.840 ms/op
                 createUser·p0.9999: 12.468 ms/op
                 createUser·p1.00:   12.681 ms/op

Iteration   2: 3.029 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.572 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.190 ms/op
                 createUser·p0.999:  9.339 ms/op
                 createUser·p0.9999: 16.080 ms/op
                 createUser·p1.00:   16.646 ms/op

Iteration   3: 3.031 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.850 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  10.133 ms/op
                 createUser·p0.9999: 27.802 ms/op
                 createUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 316729
  mean =      3.030 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27363 
    [ 2.500,  5.000) = 288270 
    [ 5.000,  7.500) = 737 
    [ 7.500, 10.000) = 121 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.301 ms/op
     p(99.9000) =      8.995 ms/op
     p(99.9900) =     25.317 ms/op
     p(99.9990) =     28.175 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.012 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.902 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.166 ms/op
                 existUser·p0.999:  5.382 ms/op
                 existUser·p0.9999: 11.520 ms/op
                 existUser·p1.00:   12.239 ms/op

Iteration   2: 2.810 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.594 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.203 ms/op
                 existUser·p0.95:   3.355 ms/op
                 existUser·p0.99:   3.977 ms/op
                 existUser·p0.999:  12.879 ms/op
                 existUser·p0.9999: 14.166 ms/op
                 existUser·p1.00:   14.500 ms/op

Iteration   3: 2.887 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.725 ms/op
                 existUser·p0.50:   2.859 ms/op
                 existUser·p0.90:   3.461 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.352 ms/op
                 existUser·p0.999:  8.036 ms/op
                 existUser·p0.9999: 15.938 ms/op
                 existUser·p1.00:   16.368 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334824
  mean =      2.870 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3132 
    [ 1.250,  2.500) = 46223 
    [ 2.500,  3.750) = 277728 
    [ 3.750,  5.000) = 6654 
    [ 5.000,  6.250) = 572 
    [ 6.250,  7.500) = 156 
    [ 7.500,  8.750) = 39 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 31 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 114 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 23 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.594 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.186 ms/op
     p(99.9000) =      8.036 ms/op
     p(99.9900) =     14.565 ms/op
     p(99.9990) =     16.246 ms/op
     p(99.9999) =     16.368 ms/op
    p(100.0000) =     16.368 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.859 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  7.337 ms/op
                 getUser·p0.9999: 13.466 ms/op
                 getUser·p1.00:   13.894 ms/op

Iteration   2: 3.011 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.662 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.523 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.448 ms/op
                 getUser·p0.999:  6.493 ms/op
                 getUser·p0.9999: 14.473 ms/op
                 getUser·p1.00:   14.762 ms/op

Iteration   3: 3.031 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.769 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.510 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.123 ms/op
                 getUser·p0.9999: 18.085 ms/op
                 getUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317053
  mean =      3.026 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 717 
    [ 1.250,  2.500) = 20373 
    [ 2.500,  3.750) = 280323 
    [ 3.750,  5.000) = 14464 
    [ 5.000,  6.250) = 703 
    [ 6.250,  7.500) = 207 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 32 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.662 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.555 ms/op
     p(95.0000) =      3.744 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      6.987 ms/op
     p(99.9900) =     16.635 ms/op
     p(99.9990) =     18.934 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.841 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.011 ms/op
Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  16.348 ms/op
                 listUser·p0.9999: 21.620 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.954 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.847 ms/op
                 listUser·p0.999:  14.748 ms/op
                 listUser·p0.9999: 17.883 ms/op
                 listUser·p1.00:   18.481 ms/op

Iteration   3: 3.887 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.065 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.726 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 21.390 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245310
  mean =      3.910 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3687 
    [ 2.500,  5.000) = 221681 
    [ 5.000,  7.500) = 18807 
    [ 7.500, 10.000) = 699 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 187 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.065 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.644 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     15.789 ms/op
     p(99.9900) =     21.332 ms/op
     p(99.9990) =     22.089 ms/op
     p(99.9999) =     22.217 ms/op
    p(100.0000) =     22.217 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.696 ± 1.373  ops/ms
ClientGrpc.existUser                       thrpt       3  11.149 ± 2.949  ops/ms
ClientGrpc.getUser                         thrpt       3  10.653 ± 2.797  ops/ms
ClientGrpc.listUser                        thrpt       3   8.218 ± 2.378  ops/ms
ClientGrpc.createUser                       avgt       3   3.001 ± 0.546   ms/op
ClientGrpc.existUser                        avgt       3   2.864 ± 0.475   ms/op
ClientGrpc.getUser                          avgt       3   2.997 ± 0.826   ms/op
ClientGrpc.listUser                         avgt       3   3.853 ± 0.593   ms/op
ClientGrpc.createUser                     sample  316729   3.030 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.633           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.994           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.568           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.301           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.995           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.317           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.312           ms/op
ClientGrpc.existUser                      sample  334824   2.870 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.594           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.859           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.186           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.036           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.565           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.368           ms/op
ClientGrpc.getUser                        sample  317053   3.026 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.662           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.555           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.744           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.334           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.987           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.635           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.940           ms/op
ClientGrpc.listUser                       sample  245310   3.910 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.065           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.768           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.644           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.789           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.332           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.217           ms/op
