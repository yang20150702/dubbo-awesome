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
# Warmup Iteration   1: 4.643 ops/ms
# Warmup Iteration   2: 9.392 ops/ms
# Warmup Iteration   3: 10.416 ops/ms
Iteration   1: 10.424 ops/ms
Iteration   2: 10.733 ops/ms
Iteration   3: 10.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.638 ±(99.9%) 3.380 ops/ms [Average]
  (min, avg, max) = (10.424, 10.638, 10.755), stdev = 0.185
  CI (99.9%): [7.257, 14.018] (assumes normal distribution)


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
# Warmup Iteration   1: 8.080 ops/ms
# Warmup Iteration   2: 10.828 ops/ms
# Warmup Iteration   3: 11.050 ops/ms
Iteration   1: 11.094 ops/ms
Iteration   2: 10.876 ops/ms
Iteration   3: 11.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.013 ±(99.9%) 2.184 ops/ms [Average]
  (min, avg, max) = (10.876, 11.013, 11.094), stdev = 0.120
  CI (99.9%): [8.829, 13.197] (assumes normal distribution)


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
# Warmup Iteration   1: 7.000 ops/ms
# Warmup Iteration   2: 10.188 ops/ms
# Warmup Iteration   3: 10.626 ops/ms
Iteration   1: 10.503 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.556 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.502 ±(99.9%) 0.996 ops/ms [Average]
  (min, avg, max) = (10.447, 10.502, 10.556), stdev = 0.055
  CI (99.9%): [9.506, 11.498] (assumes normal distribution)


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
# Warmup Iteration   1: 6.379 ops/ms
# Warmup Iteration   2: 7.794 ops/ms
# Warmup Iteration   3: 8.313 ops/ms
Iteration   1: 8.382 ops/ms
Iteration   2: 8.365 ops/ms
Iteration   3: 8.312 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.353 ±(99.9%) 0.667 ops/ms [Average]
  (min, avg, max) = (8.312, 8.353, 8.382), stdev = 0.037
  CI (99.9%): [7.686, 9.020] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.107 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.040 ±(99.9%) 0.003 ms/op
Iteration   1: 3.002 ±(99.9%) 0.002 ms/op
Iteration   2: 2.995 ±(99.9%) 0.003 ms/op
Iteration   3: 2.993 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.997 ±(99.9%) 0.091 ms/op [Average]
  (min, avg, max) = (2.993, 2.997, 3.002), stdev = 0.005
  CI (99.9%): [2.905, 3.088] (assumes normal distribution)


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
# Warmup Iteration   1: 3.952 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.914 ±(99.9%) 0.003 ms/op
Iteration   1: 2.928 ±(99.9%) 0.005 ms/op
Iteration   2: 2.834 ±(99.9%) 0.003 ms/op
Iteration   3: 2.893 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.885 ±(99.9%) 0.870 ms/op [Average]
  (min, avg, max) = (2.834, 2.885, 2.928), stdev = 0.048
  CI (99.9%): [2.014, 3.755] (assumes normal distribution)


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.048 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.955 ±(99.9%) 0.004 ms/op
Iteration   1: 2.955 ±(99.9%) 0.002 ms/op
Iteration   2: 2.964 ±(99.9%) 0.003 ms/op
Iteration   3: 2.973 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.964 ±(99.9%) 0.162 ms/op [Average]
  (min, avg, max) = (2.955, 2.964, 2.973), stdev = 0.009
  CI (99.9%): [2.802, 3.126] (assumes normal distribution)


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
# Warmup Iteration   1: 5.080 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.987 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.006 ms/op
Iteration   1: 3.815 ±(99.9%) 0.019 ms/op
Iteration   2: 3.861 ±(99.9%) 0.024 ms/op
Iteration   3: 3.759 ±(99.9%) 0.041 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.812 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (3.759, 3.812, 3.861), stdev = 0.051
  CI (99.9%): [2.876, 4.748] (assumes normal distribution)


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.074 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.005 ±(99.9%) 0.007 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.445 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  5.612 ms/op
                 createUser·p0.9999: 12.321 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   2: 2.926 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.700 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.404 ms/op
                 createUser·p0.95:   3.641 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  6.447 ms/op
                 createUser·p0.9999: 20.613 ms/op
                 createUser·p1.00:   21.004 ms/op

Iteration   3: 3.011 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.585 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  9.003 ms/op
                 createUser·p0.9999: 22.819 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322963
  mean =      2.972 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 32159 
    [ 2.500,  5.000) = 289426 
    [ 5.000,  7.500) = 1043 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.585 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      7.701 ms/op
     p(99.9900) =     21.673 ms/op
     p(99.9990) =     23.127 ms/op
     p(99.9999) =     23.200 ms/op
    p(100.0000) =     23.200 ms/op


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
# Warmup Iteration   1: 3.830 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.969 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.005 ms/op
Iteration   1: 2.886 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.699 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.346 ms/op
                 existUser·p0.95:   3.490 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  6.226 ms/op
                 existUser·p0.9999: 16.266 ms/op
                 existUser·p1.00:   16.482 ms/op

Iteration   2: 2.868 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.635 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.645 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  7.010 ms/op
                 existUser·p0.9999: 12.842 ms/op
                 existUser·p1.00:   13.074 ms/op

Iteration   3: 2.867 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.406 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.580 ms/op
                 existUser·p0.99:   4.612 ms/op
                 existUser·p0.999:  7.656 ms/op
                 existUser·p0.9999: 23.718 ms/op
                 existUser·p1.00:   24.379 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 334387
  mean =      2.874 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49022 
    [ 2.500,  5.000) = 284086 
    [ 5.000,  7.500) = 1015 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.406 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.568 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      7.129 ms/op
     p(99.9900) =     16.945 ms/op
     p(99.9990) =     23.996 ms/op
     p(99.9999) =     24.379 ms/op
    p(100.0000) =     24.379 ms/op


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
# Warmup Iteration   1: 3.904 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.041 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.006 ms/op
Iteration   1: 2.947 ±(99.9%) 0.004 ms/op
                 getUser·p0.00:   0.834 ms/op
                 getUser·p0.50:   2.949 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.482 ms/op
                 getUser·p0.99:   4.096 ms/op
                 getUser·p0.999:  5.935 ms/op
                 getUser·p0.9999: 11.780 ms/op
                 getUser·p1.00:   12.026 ms/op

Iteration   2: 2.966 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.797 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.023 ms/op
                 getUser·p0.9999: 19.464 ms/op
                 getUser·p1.00:   19.628 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.794 ms/op
                 getUser·p0.50:   2.920 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.752 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  6.529 ms/op
                 getUser·p0.9999: 16.420 ms/op
                 getUser·p1.00:   17.203 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 325347
  mean =      2.950 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1317 
    [ 1.250,  2.500) = 32554 
    [ 2.500,  3.750) = 277481 
    [ 3.750,  5.000) = 12671 
    [ 5.000,  6.250) = 839 
    [ 6.250,  7.500) = 243 
    [ 7.500,  8.750) = 58 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 17 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.941 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      6.911 ms/op
     p(99.9900) =     18.103 ms/op
     p(99.9990) =     19.587 ms/op
     p(99.9999) =     19.628 ms/op
    p(100.0000) =     19.628 ms/op


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
# Warmup Iteration   1: 5.085 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.407 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.766 ms/op
                 listUser·p0.9999: 19.366 ms/op
                 listUser·p1.00:   21.823 ms/op

Iteration   2: 3.799 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.662 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.374 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  12.777 ms/op
                 listUser·p0.9999: 18.317 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   3: 3.865 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.771 ms/op
                 listUser·p0.50:   3.719 ms/op
                 listUser·p0.90:   4.841 ms/op
                 listUser·p0.95:   5.415 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  17.900 ms/op
                 listUser·p0.9999: 23.069 ms/op
                 listUser·p1.00:   24.019 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249641
  mean =      3.845 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4755 
    [ 2.500,  5.000) = 225578 
    [ 5.000,  7.500) = 18147 
    [ 7.500, 10.000) = 672 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 73 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.399 ms/op
     p(99.0000) =      6.676 ms/op
     p(99.9000) =     14.806 ms/op
     p(99.9900) =     22.513 ms/op
     p(99.9990) =     23.790 ms/op
     p(99.9999) =     24.019 ms/op
    p(100.0000) =     24.019 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.638 ± 3.380  ops/ms
ClientGrpc.existUser                       thrpt       3  11.013 ± 2.184  ops/ms
ClientGrpc.getUser                         thrpt       3  10.502 ± 0.996  ops/ms
ClientGrpc.listUser                        thrpt       3   8.353 ± 0.667  ops/ms
ClientGrpc.createUser                       avgt       3   2.997 ± 0.091   ms/op
ClientGrpc.existUser                        avgt       3   2.885 ± 0.870   ms/op
ClientGrpc.getUser                          avgt       3   2.964 ± 0.162   ms/op
ClientGrpc.listUser                         avgt       3   3.812 ± 0.936   ms/op
ClientGrpc.createUser                     sample  322963   2.972 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.585           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.482           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.690           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.465           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.701           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.200           ms/op
ClientGrpc.existUser                      sample  334387   2.874 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.406           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.855           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.568           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.129           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.945           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.379           ms/op
ClientGrpc.getUser                        sample  325347   2.950 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.748           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.941           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.437           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.911           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.103           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.628           ms/op
ClientGrpc.listUser                       sample  249641   3.845 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.771           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.784           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.399           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.676           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.806           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.513           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.019           ms/op
