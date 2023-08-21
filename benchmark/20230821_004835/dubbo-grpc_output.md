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
# Warmup Iteration   1: 2.942 ops/ms
# Warmup Iteration   2: 6.421 ops/ms
# Warmup Iteration   3: 7.441 ops/ms
Iteration   1: 8.035 ops/ms
Iteration   2: 7.585 ops/ms
Iteration   3: 7.910 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.843 ±(99.9%) 4.241 ops/ms [Average]
  (min, avg, max) = (7.585, 7.843, 8.035), stdev = 0.232
  CI (99.9%): [3.602, 12.085] (assumes normal distribution)


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
# Warmup Iteration   1: 5.225 ops/ms
# Warmup Iteration   2: 7.631 ops/ms
# Warmup Iteration   3: 8.632 ops/ms
Iteration   1: 8.716 ops/ms
Iteration   2: 9.119 ops/ms
Iteration   3: 8.444 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.760 ±(99.9%) 6.196 ops/ms [Average]
  (min, avg, max) = (8.444, 8.760, 9.119), stdev = 0.340
  CI (99.9%): [2.564, 14.956] (assumes normal distribution)


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
# Warmup Iteration   1: 4.906 ops/ms
# Warmup Iteration   2: 7.916 ops/ms
# Warmup Iteration   3: 8.186 ops/ms
Iteration   1: 8.191 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 7.900 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.993 ±(99.9%) 3.117 ops/ms [Average]
  (min, avg, max) = (7.890, 7.993, 8.191), stdev = 0.171
  CI (99.9%): [4.877, 11.110] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ops/ms
# Warmup Iteration   2: 5.794 ops/ms
# Warmup Iteration   3: 6.070 ops/ms
Iteration   1: 6.325 ops/ms
Iteration   2: 5.865 ops/ms
Iteration   3: 6.176 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.122 ±(99.9%) 4.288 ops/ms [Average]
  (min, avg, max) = (5.865, 6.122, 6.325), stdev = 0.235
  CI (99.9%): [1.835, 10.410] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.734 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.013 ms/op
Iteration   1: 4.092 ±(99.9%) 0.003 ms/op
Iteration   2: 3.943 ±(99.9%) 0.002 ms/op
Iteration   3: 4.001 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.012 ±(99.9%) 1.376 ms/op [Average]
  (min, avg, max) = (3.943, 4.012, 4.092), stdev = 0.075
  CI (99.9%): [2.635, 5.388] (assumes normal distribution)


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
# Warmup Iteration   1: 5.666 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 4.081 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.887 ±(99.9%) 0.003 ms/op
Iteration   1: 3.951 ±(99.9%) 0.003 ms/op
Iteration   2: 3.718 ±(99.9%) 0.003 ms/op
Iteration   3: 3.740 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.803 ±(99.9%) 2.352 ms/op [Average]
  (min, avg, max) = (3.718, 3.803, 3.951), stdev = 0.129
  CI (99.9%): [1.451, 6.155] (assumes normal distribution)


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
# Warmup Iteration   1: 5.741 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.046 ±(99.9%) 0.005 ms/op
Iteration   1: 4.054 ±(99.9%) 0.003 ms/op
Iteration   2: 3.939 ±(99.9%) 0.003 ms/op
Iteration   3: 3.827 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.940 ±(99.9%) 2.070 ms/op [Average]
  (min, avg, max) = (3.827, 3.940, 4.054), stdev = 0.113
  CI (99.9%): [1.870, 6.010] (assumes normal distribution)


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
# Warmup Iteration   1: 8.070 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.334 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.895 ±(99.9%) 0.031 ms/op
Iteration   1: 4.924 ±(99.9%) 0.013 ms/op
Iteration   2: 4.737 ±(99.9%) 0.015 ms/op
Iteration   3: 5.114 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.925 ±(99.9%) 3.446 ms/op [Average]
  (min, avg, max) = (4.737, 4.925, 5.114), stdev = 0.189
  CI (99.9%): [1.479, 8.371] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 5.752 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.377 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.068 ±(99.9%) 0.011 ms/op
Iteration   1: 4.151 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.361 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.087 ms/op
                 createUser·p0.95:   5.554 ms/op
                 createUser·p0.99:   7.832 ms/op
                 createUser·p0.999:  12.528 ms/op
                 createUser·p0.9999: 16.155 ms/op
                 createUser·p1.00:   16.712 ms/op

Iteration   2: 3.738 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.964 ms/op
                 createUser·p0.50:   3.678 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.833 ms/op
                 createUser·p0.99:   6.226 ms/op
                 createUser·p0.999:  9.617 ms/op
                 createUser·p0.9999: 17.754 ms/op
                 createUser·p1.00:   18.907 ms/op

Iteration   3: 3.741 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  16.647 ms/op
                 createUser·p0.9999: 32.375 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 248084
  mean =      3.868 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5735 
    [ 2.500,  5.000) = 227651 
    [ 5.000,  7.500) = 13052 
    [ 7.500, 10.000) = 1192 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 59 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.361 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.734 ms/op
     p(99.9000) =     12.054 ms/op
     p(99.9900) =     30.644 ms/op
     p(99.9990) =     32.983 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


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
# Warmup Iteration   1: 5.451 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.854 ±(99.9%) 0.010 ms/op
Iteration   1: 3.893 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.141 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.431 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  12.056 ms/op
                 existUser·p0.9999: 15.878 ms/op
                 existUser·p1.00:   16.122 ms/op

Iteration   2: 3.652 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.593 ms/op
                 existUser·p0.50:   3.559 ms/op
                 existUser·p0.90:   4.391 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   7.680 ms/op
                 existUser·p0.999:  12.408 ms/op
                 existUser·p0.9999: 18.431 ms/op
                 existUser·p1.00:   19.268 ms/op

Iteration   3: 3.869 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.015 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.300 ms/op
                 existUser·p0.99:   6.783 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 21.692 ms/op
                 existUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 252473
  mean =      3.802 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8405 
    [ 2.500,  5.000) = 226763 
    [ 5.000,  7.500) = 15016 
    [ 7.500, 10.000) = 1756 
    [10.000, 12.500) = 320 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.593 ms/op
     p(50.0000) =      3.662 ms/op
     p(90.0000) =      4.702 ms/op
     p(95.0000) =      5.259 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     11.985 ms/op
     p(99.9900) =     20.693 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 5.750 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.320 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.080 ±(99.9%) 0.012 ms/op
Iteration   1: 4.075 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.941 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   5.259 ms/op
                 getUser·p0.95:   5.906 ms/op
                 getUser·p0.99:   7.594 ms/op
                 getUser·p0.999:  12.426 ms/op
                 getUser·p0.9999: 17.863 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.925 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.932 ms/op
                 getUser·p0.95:   5.415 ms/op
                 getUser·p0.99:   6.873 ms/op
                 getUser·p0.999:  12.281 ms/op
                 getUser·p0.9999: 19.715 ms/op
                 getUser·p1.00:   21.856 ms/op

Iteration   3: 3.997 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.723 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.866 ms/op
                 getUser·p0.95:   5.366 ms/op
                 getUser·p0.99:   7.750 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 22.053 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240232
  mean =      3.995 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6895 
    [ 2.500,  5.000) = 208979 
    [ 5.000,  7.500) = 22072 
    [ 7.500, 10.000) = 1713 
    [10.000, 12.500) = 361 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.723 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     21.363 ms/op
     p(99.9990) =     22.472 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.679 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 5.435 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.977 ±(99.9%) 0.017 ms/op
Iteration   1: 4.981 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.491 ms/op
                 listUser·p0.50:   4.719 ms/op
                 listUser·p0.90:   6.414 ms/op
                 listUser·p0.95:   7.307 ms/op
                 listUser·p0.99:   9.683 ms/op
                 listUser·p0.999:  16.032 ms/op
                 listUser·p0.9999: 22.348 ms/op
                 listUser·p1.00:   22.839 ms/op

Iteration   2: 5.106 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.683 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.873 ms/op
                 listUser·p0.95:   7.692 ms/op
                 listUser·p0.99:   10.014 ms/op
                 listUser·p0.999:  18.088 ms/op
                 listUser·p0.9999: 21.520 ms/op
                 listUser·p1.00:   21.692 ms/op

Iteration   3: 4.883 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.772 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.160 ms/op
                 listUser·p0.95:   7.086 ms/op
                 listUser·p0.99:   9.273 ms/op
                 listUser·p0.999:  23.822 ms/op
                 listUser·p0.9999: 36.258 ms/op
                 listUser·p1.00:   37.093 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 192398
  mean =      4.988 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 431 
    [ 2.500,  5.000) = 126334 
    [ 5.000,  7.500) = 56804 
    [ 7.500, 10.000) = 7235 
    [10.000, 12.500) = 1005 
    [12.500, 15.000) = 266 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 43 
    [35.000, 37.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.491 ms/op
     p(50.0000) =      4.702 ms/op
     p(90.0000) =      6.504 ms/op
     p(95.0000) =      7.397 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     18.160 ms/op
     p(99.9900) =     35.227 ms/op
     p(99.9990) =     36.912 ms/op
     p(99.9999) =     37.093 ms/op
    p(100.0000) =     37.093 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.843 ± 4.241  ops/ms
ClientGrpc.existUser                       thrpt       3   8.760 ± 6.196  ops/ms
ClientGrpc.getUser                         thrpt       3   7.993 ± 3.117  ops/ms
ClientGrpc.listUser                        thrpt       3   6.122 ± 4.288  ops/ms
ClientGrpc.createUser                       avgt       3   4.012 ± 1.376   ms/op
ClientGrpc.existUser                        avgt       3   3.803 ± 2.352   ms/op
ClientGrpc.getUser                          avgt       3   3.940 ± 2.070   ms/op
ClientGrpc.listUser                         avgt       3   4.925 ± 3.446   ms/op
ClientGrpc.createUser                     sample  248084   3.868 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.361           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.760           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.104           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.734           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.054           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          30.644           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          33.227           ms/op
ClientGrpc.existUser                      sample  252473   3.802 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.593           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.662           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.702           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.259           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.315           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.985           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.693           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.020           ms/op
ClientGrpc.getUser                        sample  240232   3.995 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.723           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.014           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.579           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.447           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.222           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          21.363           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  192398   4.988 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.491           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.702           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.504           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.397           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.650           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.160           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          35.227           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          37.093           ms/op
