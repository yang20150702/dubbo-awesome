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
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 4.906 ops/ms
# Warmup Iteration   3: 6.871 ops/ms
Iteration   1: 6.887 ops/ms
Iteration   2: 7.117 ops/ms
Iteration   3: 7.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.048 ±(99.9%) 2.554 ops/ms [Average]
  (min, avg, max) = (6.887, 7.048, 7.141), stdev = 0.140
  CI (99.9%): [4.494, 9.602] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.468 ops/ms
# Warmup Iteration   2: 7.171 ops/ms
# Warmup Iteration   3: 7.534 ops/ms
Iteration   1: 7.704 ops/ms
Iteration   2: 7.713 ops/ms
Iteration   3: 7.767 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.728 ±(99.9%) 0.623 ops/ms [Average]
  (min, avg, max) = (7.704, 7.728, 7.767), stdev = 0.034
  CI (99.9%): [7.106, 8.351] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 4.204 ops/ms
# Warmup Iteration   2: 6.695 ops/ms
# Warmup Iteration   3: 7.025 ops/ms
Iteration   1: 6.948 ops/ms
Iteration   2: 7.227 ops/ms
Iteration   3: 7.217 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.131 ±(99.9%) 2.891 ops/ms [Average]
  (min, avg, max) = (6.948, 7.131, 7.227), stdev = 0.158
  CI (99.9%): [4.240, 10.021] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.617 ops/ms
# Warmup Iteration   2: 4.940 ops/ms
# Warmup Iteration   3: 5.396 ops/ms
Iteration   1: 5.459 ops/ms
Iteration   2: 5.564 ops/ms
Iteration   3: 5.594 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.539 ±(99.9%) 1.291 ops/ms [Average]
  (min, avg, max) = (5.459, 5.539, 5.594), stdev = 0.071
  CI (99.9%): [4.248, 6.830] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 7.233 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.702 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.539 ±(99.9%) 0.016 ms/op
Iteration   1: 4.435 ±(99.9%) 0.004 ms/op
Iteration   2: 4.369 ±(99.9%) 0.003 ms/op
Iteration   3: 4.340 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.381 ±(99.9%) 0.895 ms/op [Average]
  (min, avg, max) = (4.340, 4.381, 4.435), stdev = 0.049
  CI (99.9%): [3.486, 5.277] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.441 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.255 ±(99.9%) 0.004 ms/op
Iteration   1: 4.084 ±(99.9%) 0.002 ms/op
Iteration   2: 4.137 ±(99.9%) 0.002 ms/op
Iteration   3: 4.043 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.088 ±(99.9%) 0.860 ms/op [Average]
  (min, avg, max) = (4.043, 4.088, 4.137), stdev = 0.047
  CI (99.9%): [3.228, 4.947] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.945 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.858 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.511 ±(99.9%) 0.007 ms/op
Iteration   1: 4.364 ±(99.9%) 0.005 ms/op
Iteration   2: 4.386 ±(99.9%) 0.004 ms/op
Iteration   3: 4.339 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.363 ±(99.9%) 0.427 ms/op [Average]
  (min, avg, max) = (4.339, 4.363, 4.386), stdev = 0.023
  CI (99.9%): [3.936, 4.790] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.179 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 6.322 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.866 ±(99.9%) 0.022 ms/op
Iteration   1: 5.954 ±(99.9%) 0.034 ms/op
Iteration   2: 5.816 ±(99.9%) 0.025 ms/op
Iteration   3: 6.020 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.930 ±(99.9%) 1.900 ms/op [Average]
  (min, avg, max) = (5.816, 5.930, 6.020), stdev = 0.104
  CI (99.9%): [4.030, 7.830] (assumes normal distribution)


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
# Warmup Iteration   1: 6.999 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.725 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.557 ±(99.9%) 0.014 ms/op
Iteration   1: 4.370 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.157 ms/op
                 createUser·p0.50:   4.301 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   5.874 ms/op
                 createUser·p0.99:   7.422 ms/op
                 createUser·p0.999:  12.629 ms/op
                 createUser·p0.9999: 24.303 ms/op
                 createUser·p1.00:   24.642 ms/op

Iteration   2: 4.354 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.922 ms/op
                 createUser·p0.50:   4.235 ms/op
                 createUser·p0.90:   5.317 ms/op
                 createUser·p0.95:   5.792 ms/op
                 createUser·p0.99:   7.935 ms/op
                 createUser·p0.999:  12.456 ms/op
                 createUser·p0.9999: 27.208 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   3: 4.365 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.014 ms/op
                 createUser·p0.50:   4.276 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   7.209 ms/op
                 createUser·p0.999:  11.874 ms/op
                 createUser·p0.9999: 29.710 ms/op
                 createUser·p1.00:   30.704 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 219900
  mean =      4.363 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4934 
    [ 2.500,  5.000) = 176187 
    [ 5.000,  7.500) = 36559 
    [ 7.500, 10.000) = 1431 
    [10.000, 12.500) = 570 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      4.268 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.792 ms/op
     p(99.0000) =      7.512 ms/op
     p(99.9000) =     12.488 ms/op
     p(99.9900) =     29.197 ms/op
     p(99.9990) =     30.002 ms/op
     p(99.9999) =     30.704 ms/op
    p(100.0000) =     30.704 ms/op


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
# Warmup Iteration   1: 6.249 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.372 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.012 ms/op
Iteration   1: 4.336 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   4.219 ms/op
                 existUser·p0.90:   5.284 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  12.752 ms/op
                 existUser·p0.9999: 23.810 ms/op
                 existUser·p1.00:   23.953 ms/op

Iteration   2: 4.142 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.139 ms/op
                 existUser·p0.50:   4.080 ms/op
                 existUser·p0.90:   5.095 ms/op
                 existUser·p0.95:   5.456 ms/op
                 existUser·p0.99:   6.816 ms/op
                 existUser·p0.999:  10.011 ms/op
                 existUser·p0.9999: 33.900 ms/op
                 existUser·p1.00:   34.210 ms/op

Iteration   3: 4.176 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.177 ms/op
                 existUser·p0.95:   5.587 ms/op
                 existUser·p0.99:   6.971 ms/op
                 existUser·p0.999:  11.239 ms/op
                 existUser·p0.9999: 24.479 ms/op
                 existUser·p1.00:   25.035 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 227536
  mean =      4.216 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4867 
    [ 2.500,  5.000) = 191659 
    [ 5.000,  7.500) = 29217 
    [ 7.500, 10.000) = 1330 
    [10.000, 12.500) = 299 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.040 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.571 ms/op
     p(99.0000) =      7.127 ms/op
     p(99.9000) =     11.526 ms/op
     p(99.9900) =     33.071 ms/op
     p(99.9990) =     34.126 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.280 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.916 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.585 ±(99.9%) 0.013 ms/op
Iteration   1: 4.537 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   4.407 ms/op
                 getUser·p0.90:   5.603 ms/op
                 getUser·p0.95:   6.070 ms/op
                 getUser·p0.99:   8.135 ms/op
                 getUser·p0.999:  12.648 ms/op
                 getUser·p0.9999: 26.542 ms/op
                 getUser·p1.00:   26.968 ms/op

Iteration   2: 4.466 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   4.358 ms/op
                 getUser·p0.90:   5.538 ms/op
                 getUser·p0.95:   6.005 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  13.861 ms/op
                 getUser·p0.9999: 29.552 ms/op
                 getUser·p1.00:   30.507 ms/op

Iteration   3: 4.556 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   4.432 ms/op
                 getUser·p0.90:   5.636 ms/op
                 getUser·p0.95:   6.046 ms/op
                 getUser·p0.99:   7.705 ms/op
                 getUser·p0.999:  11.470 ms/op
                 getUser·p0.9999: 30.999 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 212321
  mean =      4.520 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2803 
    [ 2.500,  5.000) = 159533 
    [ 5.000,  7.500) = 47527 
    [ 7.500, 10.000) = 1951 
    [10.000, 12.500) = 267 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 56 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.002 ms/op
     p(50.0000) =      4.399 ms/op
     p(90.0000) =      5.595 ms/op
     p(95.0000) =      6.046 ms/op
     p(99.0000) =      7.731 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     30.492 ms/op
     p(99.9990) =     31.027 ms/op
     p(99.9999) =     31.031 ms/op
    p(100.0000) =     31.031 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.591 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.445 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.949 ±(99.9%) 0.024 ms/op
Iteration   1: 5.740 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.466 ms/op
                 listUser·p0.50:   5.448 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.552 ms/op
                 listUser·p0.99:   10.961 ms/op
                 listUser·p0.999:  25.598 ms/op
                 listUser·p0.9999: 28.994 ms/op
                 listUser·p1.00:   29.819 ms/op

Iteration   2: 5.882 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   5.636 ms/op
                 listUser·p0.90:   7.375 ms/op
                 listUser·p0.95:   8.471 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  23.763 ms/op
                 listUser·p0.9999: 27.077 ms/op
                 listUser·p1.00:   29.065 ms/op

Iteration   3: 5.740 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.487 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.453 ms/op
                 listUser·p0.999:  26.003 ms/op
                 listUser·p0.9999: 33.358 ms/op
                 listUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 165993
  mean =      5.787 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 43788 
    [ 5.000,  7.500) = 106386 
    [ 7.500, 10.000) = 13013 
    [10.000, 12.500) = 2071 
    [12.500, 15.000) = 288 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      5.521 ms/op
     p(90.0000) =      7.414 ms/op
     p(95.0000) =      8.454 ms/op
     p(99.0000) =     10.733 ms/op
     p(99.9000) =     24.871 ms/op
     p(99.9900) =     33.128 ms/op
     p(99.9990) =     34.115 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.048 ± 2.554  ops/ms
ClientGrpc.existUser                       thrpt       3   7.728 ± 0.623  ops/ms
ClientGrpc.getUser                         thrpt       3   7.131 ± 2.891  ops/ms
ClientGrpc.listUser                        thrpt       3   5.539 ± 1.291  ops/ms
ClientGrpc.createUser                       avgt       3   4.381 ± 0.895   ms/op
ClientGrpc.existUser                        avgt       3   4.088 ± 0.860   ms/op
ClientGrpc.getUser                          avgt       3   4.363 ± 0.427   ms/op
ClientGrpc.listUser                         avgt       3   5.930 ± 1.900   ms/op
ClientGrpc.createUser                     sample  219900   4.363 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.922           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.268           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.792           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.512           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.488           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          29.197           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.704           ms/op
ClientGrpc.existUser                      sample  227536   4.216 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           1.040           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.186           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.127           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.526           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          33.071           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          34.210           ms/op
ClientGrpc.getUser                        sample  212321   4.520 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.002           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.595           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.046           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.731           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.730           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.492           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          31.031           ms/op
ClientGrpc.listUser                       sample  165993   5.787 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.350           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.521           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.414           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.454           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.733           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          24.871           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          33.128           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.521           ms/op
