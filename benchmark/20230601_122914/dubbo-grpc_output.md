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
# Warmup Iteration   1: 2.461 ops/ms
# Warmup Iteration   2: 6.343 ops/ms
# Warmup Iteration   3: 7.807 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 7.979 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.994 ±(99.9%) 0.556 ops/ms [Average]
  (min, avg, max) = (7.974, 7.994, 8.029), stdev = 0.030
  CI (99.9%): [7.439, 8.550] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.086 ops/ms
# Warmup Iteration   2: 8.200 ops/ms
# Warmup Iteration   3: 8.680 ops/ms
Iteration   1: 8.851 ops/ms
Iteration   2: 8.978 ops/ms
Iteration   3: 8.783 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.871 ±(99.9%) 1.804 ops/ms [Average]
  (min, avg, max) = (8.783, 8.871, 8.978), stdev = 0.099
  CI (99.9%): [7.067, 10.675] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.294 ops/ms
# Warmup Iteration   2: 7.699 ops/ms
# Warmup Iteration   3: 7.644 ops/ms
Iteration   1: 8.349 ops/ms
Iteration   2: 7.782 ops/ms
Iteration   3: 7.442 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.857 ±(99.9%) 8.362 ops/ms [Average]
  (min, avg, max) = (7.442, 7.857, 8.349), stdev = 0.458
  CI (99.9%): [≈ 0, 16.220] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.451 ops/ms
# Warmup Iteration   2: 5.801 ops/ms
# Warmup Iteration   3: 6.143 ops/ms
Iteration   1: 6.050 ops/ms
Iteration   2: 5.955 ops/ms
Iteration   3: 6.124 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.043 ±(99.9%) 1.544 ops/ms [Average]
  (min, avg, max) = (5.955, 6.043, 6.124), stdev = 0.085
  CI (99.9%): [4.499, 7.587] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.490 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.168 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.102 ±(99.9%) 0.003 ms/op
Iteration   1: 3.978 ±(99.9%) 0.002 ms/op
Iteration   2: 3.925 ±(99.9%) 0.003 ms/op
Iteration   3: 3.837 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.913 ±(99.9%) 1.296 ms/op [Average]
  (min, avg, max) = (3.837, 3.913, 3.978), stdev = 0.071
  CI (99.9%): [2.617, 5.210] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 5.281 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.944 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.002 ms/op
Iteration   1: 3.796 ±(99.9%) 0.002 ms/op
Iteration   2: 3.679 ±(99.9%) 0.002 ms/op
Iteration   3: 3.600 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.692 ±(99.9%) 1.807 ms/op [Average]
  (min, avg, max) = (3.600, 3.692, 3.796), stdev = 0.099
  CI (99.9%): [1.885, 5.498] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.846 ±(99.9%) 0.116 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.003 ms/op
Iteration   1: 4.037 ±(99.9%) 0.003 ms/op
Iteration   2: 3.875 ±(99.9%) 0.003 ms/op
Iteration   3: 3.830 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.914 ±(99.9%) 1.977 ms/op [Average]
  (min, avg, max) = (3.830, 3.914, 4.037), stdev = 0.108
  CI (99.9%): [1.937, 5.891] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 7.516 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 5.037 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.924 ±(99.9%) 0.013 ms/op
Iteration   1: 5.106 ±(99.9%) 0.017 ms/op
Iteration   2: 5.106 ±(99.9%) 0.017 ms/op
Iteration   3: 4.987 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.066 ±(99.9%) 1.248 ms/op [Average]
  (min, avg, max) = (4.987, 5.066, 5.106), stdev = 0.068
  CI (99.9%): [3.819, 6.314] (assumes normal distribution)


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
# Warmup Iteration   1: 6.022 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.026 ±(99.9%) 0.012 ms/op
Iteration   1: 3.821 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.808 ms/op
                 createUser·p0.50:   3.719 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.259 ms/op
                 createUser·p0.99:   6.660 ms/op
                 createUser·p0.999:  9.231 ms/op
                 createUser·p0.9999: 17.159 ms/op
                 createUser·p1.00:   19.694 ms/op

Iteration   2: 3.845 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.972 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.866 ms/op
                 createUser·p0.95:   5.317 ms/op
                 createUser·p0.99:   6.595 ms/op
                 createUser·p0.999:  10.398 ms/op
                 createUser·p0.9999: 18.743 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.087 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.981 ms/op
                 createUser·p0.95:   5.415 ms/op
                 createUser·p0.99:   6.670 ms/op
                 createUser·p0.999:  14.348 ms/op
                 createUser·p0.9999: 25.557 ms/op
                 createUser·p1.00:   29.229 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 247149
  mean =      3.882 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5043 
    [ 2.500,  5.000) = 221215 
    [ 5.000,  7.500) = 19722 
    [ 7.500, 10.000) = 842 
    [10.000, 12.500) = 109 
    [12.500, 15.000) = 80 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.808 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.808 ms/op
     p(99.9900) =     24.847 ms/op
     p(99.9990) =     27.804 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.578 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.145 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.011 ms/op
Iteration   1: 3.596 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.738 ms/op
                 existUser·p0.50:   3.490 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.234 ms/op
                 existUser·p0.999:  10.059 ms/op
                 existUser·p0.9999: 15.828 ms/op
                 existUser·p1.00:   21.004 ms/op

Iteration   2: 3.745 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.966 ms/op
                 existUser·p0.50:   3.641 ms/op
                 existUser·p0.90:   4.751 ms/op
                 existUser·p0.95:   5.153 ms/op
                 existUser·p0.99:   6.414 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 18.285 ms/op
                 existUser·p1.00:   18.350 ms/op

Iteration   3: 3.675 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.950 ms/op
                 existUser·p0.50:   3.572 ms/op
                 existUser·p0.90:   4.784 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 17.255 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261605
  mean =      3.671 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15440 
    [ 2.500,  5.000) = 228599 
    [ 5.000,  7.500) = 16496 
    [ 7.500, 10.000) = 744 
    [10.000, 12.500) = 153 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.738 ms/op
     p(50.0000) =      3.568 ms/op
     p(90.0000) =      4.743 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     17.329 ms/op
     p(99.9990) =     20.681 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 5.687 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.238 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.950 ±(99.9%) 0.010 ms/op
Iteration   1: 4.106 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.986 ms/op
                 getUser·p0.50:   3.994 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   5.677 ms/op
                 getUser·p0.99:   7.053 ms/op
                 getUser·p0.999:  13.173 ms/op
                 getUser·p0.9999: 16.591 ms/op
                 getUser·p1.00:   16.941 ms/op

Iteration   2: 4.078 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.955 ms/op
                 getUser·p0.50:   3.985 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.603 ms/op
                 getUser·p0.99:   6.963 ms/op
                 getUser·p0.999:  11.973 ms/op
                 getUser·p0.9999: 17.934 ms/op
                 getUser·p1.00:   18.088 ms/op

Iteration   3: 4.327 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.055 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.562 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   7.479 ms/op
                 getUser·p0.999:  11.372 ms/op
                 getUser·p0.9999: 21.483 ms/op
                 getUser·p1.00:   21.922 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 230301
  mean =      4.168 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5734 
    [ 2.500,  5.000) = 188209 
    [ 5.000,  7.500) = 34559 
    [ 7.500, 10.000) = 1405 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.955 ms/op
     p(50.0000) =      4.055 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.201 ms/op
     p(99.9000) =     12.463 ms/op
     p(99.9900) =     20.937 ms/op
     p(99.9990) =     21.804 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 7.795 ±(99.9%) 0.092 ms/op
# Warmup Iteration   2: 5.150 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.368 ±(99.9%) 0.019 ms/op
Iteration   1: 5.394 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.886 ms/op
                 listUser·p0.50:   5.161 ms/op
                 listUser·p0.90:   7.021 ms/op
                 listUser·p0.95:   7.971 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  15.494 ms/op
                 listUser·p0.9999: 18.973 ms/op
                 listUser·p1.00:   19.071 ms/op

Iteration   2: 5.355 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.667 ms/op
                 listUser·p0.50:   5.104 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.889 ms/op
                 listUser·p0.99:   9.880 ms/op
                 listUser·p0.999:  22.596 ms/op
                 listUser·p0.9999: 28.251 ms/op
                 listUser·p1.00:   29.131 ms/op

Iteration   3: 5.227 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.505 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.849 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.533 ms/op
                 listUser·p0.999:  20.535 ms/op
                 listUser·p0.9999: 31.145 ms/op
                 listUser·p1.00:   31.785 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180330
  mean =      5.324 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 196 
    [ 2.500,  5.000) = 84822 
    [ 5.000,  7.500) = 83478 
    [ 7.500, 10.000) = 9930 
    [10.000, 12.500) = 1335 
    [12.500, 15.000) = 208 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      6.922 ms/op
     p(95.0000) =      7.856 ms/op
     p(99.0000) =     10.076 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     30.012 ms/op
     p(99.9990) =     31.706 ms/op
     p(99.9999) =     31.785 ms/op
    p(100.0000) =     31.785 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.994 ± 0.556  ops/ms
ClientGrpc.existUser                       thrpt       3   8.871 ± 1.804  ops/ms
ClientGrpc.getUser                         thrpt       3   7.857 ± 8.362  ops/ms
ClientGrpc.listUser                        thrpt       3   6.043 ± 1.544  ops/ms
ClientGrpc.createUser                       avgt       3   3.913 ± 1.296   ms/op
ClientGrpc.existUser                        avgt       3   3.692 ± 1.807   ms/op
ClientGrpc.getUser                          avgt       3   3.914 ± 1.977   ms/op
ClientGrpc.listUser                         avgt       3   5.066 ± 1.248   ms/op
ClientGrpc.createUser                     sample  247149   3.882 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.808           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.772           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.899           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.636           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.808           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.847           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.229           ms/op
ClientGrpc.existUser                      sample  261605   3.671 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.738           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.743           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.373           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.329           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.004           ms/op
ClientGrpc.getUser                        sample  230301   4.168 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.955           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.055           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.201           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.463           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.937           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.922           ms/op
ClientGrpc.listUser                       sample  180330   5.324 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.505           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.922           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.856           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.076           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.678           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.012           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.785           ms/op
