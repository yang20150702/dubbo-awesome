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
# Warmup Iteration   1: 4.236 ops/ms
# Warmup Iteration   2: 9.560 ops/ms
# Warmup Iteration   3: 10.084 ops/ms
Iteration   1: 10.488 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.476 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.509 ±(99.9%) 0.871 ops/ms [Average]
  (min, avg, max) = (10.476, 10.509, 10.564), stdev = 0.048
  CI (99.9%): [9.639, 11.380] (assumes normal distribution)


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
# Warmup Iteration   1: 7.139 ops/ms
# Warmup Iteration   2: 10.620 ops/ms
# Warmup Iteration   3: 11.325 ops/ms
Iteration   1: 11.074 ops/ms
Iteration   2: 11.049 ops/ms
Iteration   3: 11.009 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.044 ±(99.9%) 0.603 ops/ms [Average]
  (min, avg, max) = (11.009, 11.044, 11.074), stdev = 0.033
  CI (99.9%): [10.441, 11.647] (assumes normal distribution)


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
# Warmup Iteration   1: 6.912 ops/ms
# Warmup Iteration   2: 10.351 ops/ms
# Warmup Iteration   3: 10.650 ops/ms
Iteration   1: 10.515 ops/ms
Iteration   2: 10.349 ops/ms
Iteration   3: 10.719 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.528 ±(99.9%) 3.378 ops/ms [Average]
  (min, avg, max) = (10.349, 10.528, 10.719), stdev = 0.185
  CI (99.9%): [7.149, 13.906] (assumes normal distribution)


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
# Warmup Iteration   1: 5.735 ops/ms
# Warmup Iteration   2: 7.799 ops/ms
# Warmup Iteration   3: 8.039 ops/ms
Iteration   1: 7.738 ops/ms
Iteration   2: 8.195 ops/ms
Iteration   3: 8.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.017 ±(99.9%) 4.477 ops/ms [Average]
  (min, avg, max) = (7.738, 8.017, 8.195), stdev = 0.245
  CI (99.9%): [3.541, 12.494] (assumes normal distribution)


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
# Warmup Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.162 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.073 ±(99.9%) 0.003 ms/op
Iteration   1: 3.071 ±(99.9%) 0.002 ms/op
Iteration   2: 3.012 ±(99.9%) 0.003 ms/op
Iteration   3: 3.002 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.028 ±(99.9%) 0.678 ms/op [Average]
  (min, avg, max) = (3.002, 3.028, 3.071), stdev = 0.037
  CI (99.9%): [2.350, 3.706] (assumes normal distribution)


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
# Warmup Iteration   1: 3.993 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.974 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.954 ±(99.9%) 0.002 ms/op
Iteration   1: 2.887 ±(99.9%) 0.003 ms/op
Iteration   2: 2.878 ±(99.9%) 0.003 ms/op
Iteration   3: 2.870 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.878 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.870, 2.878, 2.887), stdev = 0.008
  CI (99.9%): [2.726, 3.030] (assumes normal distribution)


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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.142 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.023 ±(99.9%) 0.005 ms/op
Iteration   1: 3.039 ±(99.9%) 0.002 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 2.981 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.010 ±(99.9%) 0.533 ms/op [Average]
  (min, avg, max) = (2.981, 3.010, 3.039), stdev = 0.029
  CI (99.9%): [2.477, 3.543] (assumes normal distribution)


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
# Warmup Iteration   1: 5.383 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.051 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.039 ±(99.9%) 0.011 ms/op
Iteration   1: 4.009 ±(99.9%) 0.008 ms/op
Iteration   2: 4.657 ±(99.9%) 0.013 ms/op
Iteration   3: 4.375 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.347 ±(99.9%) 5.934 ms/op [Average]
  (min, avg, max) = (4.009, 4.347, 4.657), stdev = 0.325
  CI (99.9%): [≈ 0, 10.281] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.543 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.068 ±(99.9%) 0.007 ms/op
Iteration   1: 3.082 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.588 ms/op
                 createUser·p0.999:  6.828 ms/op
                 createUser·p0.9999: 14.782 ms/op
                 createUser·p1.00:   15.041 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.854 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  8.980 ms/op
                 createUser·p0.9999: 16.181 ms/op
                 createUser·p1.00:   18.285 ms/op

Iteration   3: 3.074 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.752 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.555 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.260 ms/op
                 createUser·p0.999:  7.099 ms/op
                 createUser·p0.9999: 29.346 ms/op
                 createUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 311919
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20860 
    [ 2.500,  5.000) = 289758 
    [ 5.000,  7.500) = 993 
    [ 7.500, 10.000) = 52 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 99 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.752 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      7.375 ms/op
     p(99.9900) =     28.535 ms/op
     p(99.9990) =     29.586 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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
# Warmup Iteration   1: 3.932 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.023 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.949 ±(99.9%) 0.005 ms/op
Iteration   1: 2.913 ±(99.9%) 0.004 ms/op
                 existUser·p0.00:   0.526 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.510 ms/op
                 existUser·p0.99:   4.010 ms/op
                 existUser·p0.999:  6.236 ms/op
                 existUser·p0.9999: 12.010 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   2: 2.919 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.709 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.564 ms/op
                 existUser·p0.99:   4.686 ms/op
                 existUser·p0.999:  8.583 ms/op
                 existUser·p0.9999: 13.501 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.813 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.285 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.067 ms/op
                 existUser·p0.999:  6.764 ms/op
                 existUser·p0.9999: 16.056 ms/op
                 existUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329752
  mean =      2.912 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 971 
    [ 1.250,  2.500) = 32432 
    [ 2.500,  3.750) = 289353 
    [ 3.750,  5.000) = 5640 
    [ 5.000,  6.250) = 565 
    [ 6.250,  7.500) = 380 
    [ 7.500,  8.750) = 214 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 8 
    [15.000, 16.250) = 49 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.523 ms/op
     p(99.0000) =      4.215 ms/op
     p(99.9000) =      7.815 ms/op
     p(99.9900) =     15.615 ms/op
     p(99.9990) =     16.318 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 4.142 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.131 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.735 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.441 ms/op
                 getUser·p0.95:   3.629 ms/op
                 getUser·p0.99:   4.342 ms/op
                 getUser·p0.999:  6.373 ms/op
                 getUser·p0.9999: 18.953 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   2: 3.032 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.584 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.866 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 14.046 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   3: 3.020 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.790 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.412 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  6.917 ms/op
                 getUser·p0.9999: 28.456 ms/op
                 getUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 317503
  mean =      3.023 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20107 
    [ 2.500,  5.000) = 295613 
    [ 5.000,  7.500) = 1552 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.710 ms/op
     p(99.9000) =      6.873 ms/op
     p(99.9900) =     27.533 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


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
# Warmup Iteration   1: 5.559 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.869 ±(99.9%) 0.010 ms/op
Iteration   1: 3.875 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.915 ms/op
                 listUser·p0.95:   5.431 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  16.876 ms/op
                 listUser·p0.9999: 20.299 ms/op
                 listUser·p1.00:   20.873 ms/op

Iteration   2: 3.913 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  14.456 ms/op
                 listUser·p0.9999: 16.963 ms/op
                 listUser·p1.00:   17.302 ms/op

Iteration   3: 3.898 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.817 ms/op
                 listUser·p0.95:   5.841 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.236 ms/op
                 listUser·p0.9999: 19.457 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246378
  mean =      3.895 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3847 
    [ 2.500,  5.000) = 221230 
    [ 5.000,  7.500) = 20198 
    [ 7.500, 10.000) = 650 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 98 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.860 ms/op
     p(99.9900) =     19.509 ms/op
     p(99.9990) =     20.926 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.509 ± 0.871  ops/ms
ClientGrpc.existUser                       thrpt       3  11.044 ± 0.603  ops/ms
ClientGrpc.getUser                         thrpt       3  10.528 ± 3.378  ops/ms
ClientGrpc.listUser                        thrpt       3   8.017 ± 4.477  ops/ms
ClientGrpc.createUser                       avgt       3   3.028 ± 0.678   ms/op
ClientGrpc.existUser                        avgt       3   2.878 ± 0.152   ms/op
ClientGrpc.getUser                          avgt       3   3.010 ± 0.533   ms/op
ClientGrpc.listUser                         avgt       3   4.347 ± 5.934   ms/op
ClientGrpc.createUser                     sample  311919   3.078 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.752           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.047           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.805           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.375           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.535           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.721           ms/op
ClientGrpc.existUser                      sample  329752   2.912 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.526           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.523           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.215           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.815           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.615           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          16.417           ms/op
ClientGrpc.getUser                        sample  317503   3.023 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.756           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.873           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.533           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          28.901           ms/op
ClientGrpc.listUser                       sample  246378   3.895 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.932           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.744           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.571           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.860           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.509           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.070           ms/op
