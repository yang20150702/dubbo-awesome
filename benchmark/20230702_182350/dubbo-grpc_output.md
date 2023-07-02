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
# Warmup Iteration   1: 4.149 ops/ms
# Warmup Iteration   2: 8.098 ops/ms
# Warmup Iteration   3: 10.038 ops/ms
Iteration   1: 10.563 ops/ms
Iteration   2: 10.356 ops/ms
Iteration   3: 10.619 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.513 ±(99.9%) 2.531 ops/ms [Average]
  (min, avg, max) = (10.356, 10.513, 10.619), stdev = 0.139
  CI (99.9%): [7.982, 13.043] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.556 ops/ms
# Warmup Iteration   2: 10.357 ops/ms
# Warmup Iteration   3: 11.055 ops/ms
Iteration   1: 10.850 ops/ms
Iteration   2: 11.079 ops/ms
Iteration   3: 11.000 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.976 ±(99.9%) 2.126 ops/ms [Average]
  (min, avg, max) = (10.850, 10.976, 11.079), stdev = 0.117
  CI (99.9%): [8.851, 13.102] (assumes normal distribution)


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
# Warmup Iteration   1: 6.925 ops/ms
# Warmup Iteration   2: 10.050 ops/ms
# Warmup Iteration   3: 10.269 ops/ms
Iteration   1: 10.210 ops/ms
Iteration   2: 10.443 ops/ms
Iteration   3: 10.292 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.315 ±(99.9%) 2.158 ops/ms [Average]
  (min, avg, max) = (10.210, 10.315, 10.443), stdev = 0.118
  CI (99.9%): [8.157, 12.473] (assumes normal distribution)


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
# Warmup Iteration   1: 5.403 ops/ms
# Warmup Iteration   2: 7.600 ops/ms
# Warmup Iteration   3: 8.033 ops/ms
Iteration   1: 7.978 ops/ms
Iteration   2: 8.154 ops/ms
Iteration   3: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.054 ±(99.9%) 1.644 ops/ms [Average]
  (min, avg, max) = (7.978, 8.054, 8.154), stdev = 0.090
  CI (99.9%): [6.410, 9.698] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.626 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.214 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.002 ms/op
Iteration   1: 3.196 ±(99.9%) 0.003 ms/op
Iteration   2: 3.133 ±(99.9%) 0.003 ms/op
Iteration   3: 3.063 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 1.219 ms/op [Average]
  (min, avg, max) = (3.063, 3.131, 3.196), stdev = 0.067
  CI (99.9%): [1.911, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.002 ms/op
Iteration   1: 2.938 ±(99.9%) 0.002 ms/op
Iteration   2: 2.974 ±(99.9%) 0.002 ms/op
Iteration   3: 2.888 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.933 ±(99.9%) 0.785 ms/op [Average]
  (min, avg, max) = (2.888, 2.933, 2.974), stdev = 0.043
  CI (99.9%): [2.148, 3.718] (assumes normal distribution)


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
# Warmup Iteration   1: 4.604 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.133 ±(99.9%) 0.002 ms/op
Iteration   1: 3.035 ±(99.9%) 0.003 ms/op
Iteration   2: 3.086 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.042 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.007, 3.042, 3.086), stdev = 0.040
  CI (99.9%): [2.314, 3.770] (assumes normal distribution)


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
# Warmup Iteration   1: 5.145 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.095 ±(99.9%) 0.040 ms/op
Iteration   1: 4.106 ±(99.9%) 0.010 ms/op
Iteration   2: 3.942 ±(99.9%) 0.006 ms/op
Iteration   3: 3.990 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.013 ±(99.9%) 1.532 ms/op [Average]
  (min, avg, max) = (3.942, 4.013, 4.106), stdev = 0.084
  CI (99.9%): [2.481, 5.545] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.576 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.208 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.083 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.609 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  8.966 ms/op
                 createUser·p0.9999: 28.148 ms/op
                 createUser·p1.00:   28.410 ms/op

Iteration   2: 3.022 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.403 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  6.922 ms/op
                 createUser·p0.9999: 16.679 ms/op
                 createUser·p1.00:   18.252 ms/op

Iteration   3: 3.081 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.778 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.813 ms/op
                 createUser·p0.99:   4.407 ms/op
                 createUser·p0.999:  14.758 ms/op
                 createUser·p0.9999: 22.348 ms/op
                 createUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313704
  mean =      3.061 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20927 
    [ 2.500,  5.000) = 291132 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 84 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.572 ms/op
     p(95.0000) =      3.785 ms/op
     p(99.0000) =      4.514 ms/op
     p(99.9000) =      9.430 ms/op
     p(99.9900) =     27.513 ms/op
     p(99.9990) =     28.340 ms/op
     p(99.9999) =     28.410 ms/op
    p(100.0000) =     28.410 ms/op


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
# Warmup Iteration   1: 4.147 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.009 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.941 ±(99.9%) 0.005 ms/op
Iteration   1: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.559 ms/op
                 existUser·p0.99:   4.157 ms/op
                 existUser·p0.999:  6.750 ms/op
                 existUser·p0.9999: 18.776 ms/op
                 existUser·p1.00:   19.071 ms/op

Iteration   2: 2.918 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  8.476 ms/op
                 existUser·p0.9999: 14.270 ms/op
                 existUser·p1.00:   14.516 ms/op

Iteration   3: 2.929 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.580 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.355 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  7.649 ms/op
                 existUser·p0.9999: 16.845 ms/op
                 existUser·p1.00:   17.269 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330682
  mean =      2.903 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2483 
    [ 1.250,  2.500) = 35395 
    [ 2.500,  3.750) = 283018 
    [ 3.750,  5.000) = 8202 
    [ 5.000,  6.250) = 932 
    [ 6.250,  7.500) = 323 
    [ 7.500,  8.750) = 113 
    [ 8.750, 10.000) = 23 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 52 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 43 
    [15.000, 16.250) = 30 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.580 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.564 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.490 ms/op
     p(99.9900) =     17.266 ms/op
     p(99.9990) =     19.028 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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
# Warmup Iteration   1: 4.328 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.176 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.006 ms/op
Iteration   1: 3.037 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.766 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.854 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.969 ms/op
                 getUser·p0.9999: 15.900 ms/op
                 getUser·p1.00:   16.368 ms/op

Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.848 ms/op
                 getUser·p0.50:   3.006 ms/op
                 getUser·p0.90:   3.478 ms/op
                 getUser·p0.95:   3.690 ms/op
                 getUser·p0.99:   4.710 ms/op
                 getUser·p0.999:  7.152 ms/op
                 getUser·p0.9999: 16.180 ms/op
                 getUser·p1.00:   17.465 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.734 ms/op
                 getUser·p0.50:   3.015 ms/op
                 getUser·p0.90:   3.367 ms/op
                 getUser·p0.95:   3.535 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  6.910 ms/op
                 getUser·p0.9999: 17.411 ms/op
                 getUser·p1.00:   19.268 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 316894
  mean =      3.027 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 727 
    [ 1.250,  2.500) = 16657 
    [ 2.500,  3.750) = 285519 
    [ 3.750,  5.000) = 12379 
    [ 5.000,  6.250) = 1072 
    [ 6.250,  7.500) = 312 
    [ 7.500,  8.750) = 31 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 9 
    [15.000, 16.250) = 72 
    [16.250, 17.500) = 47 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.734 ms/op
     p(50.0000) =      3.011 ms/op
     p(90.0000) =      3.445 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      6.988 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     18.916 ms/op
     p(99.9999) =     19.268 ms/op
    p(100.0000) =     19.268 ms/op


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
# Warmup Iteration   1: 5.522 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.164 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.992 ±(99.9%) 0.011 ms/op
Iteration   1: 3.979 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.751 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.045 ms/op
                 listUser·p0.999:  13.116 ms/op
                 listUser·p0.9999: 16.135 ms/op
                 listUser·p1.00:   17.170 ms/op

Iteration   2: 4.036 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.061 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   6.988 ms/op
                 listUser·p0.999:  14.500 ms/op
                 listUser·p0.9999: 22.028 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   3: 3.979 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.397 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.889 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 19.333 ms/op
                 listUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240021
  mean =      3.998 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2548 
    [ 2.500,  5.000) = 214653 
    [ 5.000,  7.500) = 21525 
    [ 7.500, 10.000) = 892 
    [10.000, 12.500) = 56 
    [12.500, 15.000) = 178 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 59 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.061 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      6.971 ms/op
     p(99.9000) =     13.942 ms/op
     p(99.9900) =     20.840 ms/op
     p(99.9990) =     22.675 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.513 ± 2.531  ops/ms
ClientGrpc.existUser                       thrpt       3  10.976 ± 2.126  ops/ms
ClientGrpc.getUser                         thrpt       3  10.315 ± 2.158  ops/ms
ClientGrpc.listUser                        thrpt       3   8.054 ± 1.644  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 1.219   ms/op
ClientGrpc.existUser                        avgt       3   2.933 ± 0.785   ms/op
ClientGrpc.getUser                          avgt       3   3.042 ± 0.728   ms/op
ClientGrpc.listUser                         avgt       3   4.013 ± 1.532   ms/op
ClientGrpc.createUser                     sample  313704   3.061 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.403           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.031           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.572           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.785           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.514           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.430           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.513           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.410           ms/op
ClientGrpc.existUser                      sample  330682   2.903 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.580           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.564           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.490           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.266           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          19.071           ms/op
ClientGrpc.getUser                        sample  316894   3.027 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.734           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.011           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.445           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.571           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.988           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.974           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.268           ms/op
ClientGrpc.listUser                       sample  240021   3.998 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.061           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.948           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.767           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.971           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.942           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.840           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.872           ms/op
