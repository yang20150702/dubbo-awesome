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
# Warmup Iteration   1: 2.293 ops/ms
# Warmup Iteration   2: 5.446 ops/ms
# Warmup Iteration   3: 6.932 ops/ms
Iteration   1: 6.917 ops/ms
Iteration   2: 7.157 ops/ms
Iteration   3: 7.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.212 ±(99.9%) 5.940 ops/ms [Average]
  (min, avg, max) = (6.917, 7.212, 7.561), stdev = 0.326
  CI (99.9%): [1.271, 13.152] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.213 ops/ms
# Warmup Iteration   2: 7.734 ops/ms
# Warmup Iteration   3: 7.852 ops/ms
Iteration   1: 7.906 ops/ms
Iteration   2: 8.228 ops/ms
Iteration   3: 8.071 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.068 ±(99.9%) 2.941 ops/ms [Average]
  (min, avg, max) = (7.906, 8.068, 8.228), stdev = 0.161
  CI (99.9%): [5.127, 11.009] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.549 ops/ms
# Warmup Iteration   2: 6.827 ops/ms
# Warmup Iteration   3: 7.291 ops/ms
Iteration   1: 7.633 ops/ms
Iteration   2: 7.339 ops/ms
Iteration   3: 7.362 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.445 ±(99.9%) 2.980 ops/ms [Average]
  (min, avg, max) = (7.339, 7.445, 7.633), stdev = 0.163
  CI (99.9%): [4.464, 10.425] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ops/ms
# Warmup Iteration   2: 5.127 ops/ms
# Warmup Iteration   3: 5.639 ops/ms
Iteration   1: 5.713 ops/ms
Iteration   2: 5.749 ops/ms
Iteration   3: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.696 ±(99.9%) 1.165 ops/ms [Average]
  (min, avg, max) = (5.625, 5.696, 5.749), stdev = 0.064
  CI (99.9%): [4.531, 6.861] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.780 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.609 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.527 ±(99.9%) 0.007 ms/op
Iteration   1: 4.308 ±(99.9%) 0.003 ms/op
Iteration   2: 4.130 ±(99.9%) 0.003 ms/op
Iteration   3: 4.135 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.191 ±(99.9%) 1.854 ms/op [Average]
  (min, avg, max) = (4.130, 4.191, 4.308), stdev = 0.102
  CI (99.9%): [2.338, 6.045] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 6.100 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.953 ±(99.9%) 0.004 ms/op
Iteration   1: 3.768 ±(99.9%) 0.003 ms/op
Iteration   2: 3.839 ±(99.9%) 0.004 ms/op
Iteration   3: 3.779 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.795 ±(99.9%) 0.698 ms/op [Average]
  (min, avg, max) = (3.768, 3.795, 3.839), stdev = 0.038
  CI (99.9%): [3.098, 4.493] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.324 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.444 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.366 ±(99.9%) 0.005 ms/op
Iteration   1: 4.136 ±(99.9%) 0.003 ms/op
Iteration   2: 3.993 ±(99.9%) 0.003 ms/op
Iteration   3: 4.154 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.095 ±(99.9%) 1.610 ms/op [Average]
  (min, avg, max) = (3.993, 4.095, 4.154), stdev = 0.088
  CI (99.9%): [2.485, 5.704] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.617 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.860 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.756 ±(99.9%) 0.021 ms/op
Iteration   1: 5.557 ±(99.9%) 0.016 ms/op
Iteration   2: 5.463 ±(99.9%) 0.018 ms/op
Iteration   3: 5.514 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.511 ±(99.9%) 0.864 ms/op [Average]
  (min, avg, max) = (5.463, 5.511, 5.557), stdev = 0.047
  CI (99.9%): [4.647, 6.375] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.528 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.226 ±(99.9%) 0.013 ms/op
Iteration   1: 4.258 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.779 ms/op
                 createUser·p0.50:   4.141 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.808 ms/op
                 createUser·p0.99:   7.217 ms/op
                 createUser·p0.999:  9.929 ms/op
                 createUser·p0.9999: 16.252 ms/op
                 createUser·p1.00:   16.548 ms/op

Iteration   2: 4.237 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   4.121 ms/op
                 createUser·p0.90:   5.407 ms/op
                 createUser·p0.95:   5.906 ms/op
                 createUser·p0.99:   7.610 ms/op
                 createUser·p0.999:  14.961 ms/op
                 createUser·p0.9999: 17.644 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 4.112 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.014 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.523 ms/op
                 createUser·p0.99:   7.258 ms/op
                 createUser·p0.999:  12.370 ms/op
                 createUser·p0.9999: 34.290 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 228543
  mean =      4.202 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4734 
    [ 2.500,  5.000) = 188834 
    [ 5.000,  7.500) = 32932 
    [ 7.500, 10.000) = 1594 
    [10.000, 12.500) = 240 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 32 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.779 ms/op
     p(50.0000) =      4.092 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.767 ms/op
     p(99.0000) =      7.365 ms/op
     p(99.9000) =     12.337 ms/op
     p(99.9900) =     33.948 ms/op
     p(99.9990) =     34.697 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.008 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.525 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.297 ±(99.9%) 0.012 ms/op
Iteration   1: 4.147 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   4.002 ms/op
                 existUser·p0.90:   5.186 ms/op
                 existUser·p0.95:   5.693 ms/op
                 existUser·p0.99:   7.985 ms/op
                 existUser·p0.999:  12.579 ms/op
                 existUser·p0.9999: 16.098 ms/op
                 existUser·p1.00:   16.433 ms/op

Iteration   2: 3.923 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.809 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.390 ms/op
                 existUser·p0.99:   7.463 ms/op
                 existUser·p0.999:  15.636 ms/op
                 existUser·p0.9999: 19.890 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   3: 3.919 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.882 ms/op
                 existUser·p0.95:   5.308 ms/op
                 existUser·p0.99:   7.316 ms/op
                 existUser·p0.999:  11.980 ms/op
                 existUser·p0.9999: 22.310 ms/op
                 existUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 240348
  mean =      3.993 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7606 
    [ 2.500,  5.000) = 209571 
    [ 5.000,  7.500) = 20617 
    [ 7.500, 10.000) = 1702 
    [10.000, 12.500) = 505 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.973 ms/op
     p(95.0000) =      5.472 ms/op
     p(99.0000) =      7.619 ms/op
     p(99.9000) =     13.619 ms/op
     p(99.9900) =     20.513 ms/op
     p(99.9990) =     29.642 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.451 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.286 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.088 ±(99.9%) 0.012 ms/op
Iteration   1: 4.081 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.133 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.726 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  12.564 ms/op
                 getUser·p0.9999: 14.917 ms/op
                 getUser·p1.00:   15.434 ms/op

Iteration   2: 4.105 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   4.010 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.021 ms/op
                 getUser·p0.999:  12.866 ms/op
                 getUser·p0.9999: 18.914 ms/op
                 getUser·p1.00:   19.268 ms/op

Iteration   3: 4.280 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.253 ms/op
                 getUser·p0.50:   4.145 ms/op
                 getUser·p0.90:   5.292 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.265 ms/op
                 getUser·p0.999:  12.452 ms/op
                 getUser·p0.9999: 23.874 ms/op
                 getUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231035
  mean =      4.154 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5372 
    [ 2.500,  5.000) = 194475 
    [ 5.000,  7.500) = 29070 
    [ 7.500, 10.000) = 1433 
    [10.000, 12.500) = 443 
    [12.500, 15.000) = 168 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.035 ms/op
     p(90.0000) =      5.202 ms/op
     p(95.0000) =      5.669 ms/op
     p(99.0000) =      7.337 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     20.627 ms/op
     p(99.9990) =     24.316 ms/op
     p(99.9999) =     24.478 ms/op
    p(100.0000) =     24.478 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 6.768 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.833 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.018 ms/op
Iteration   1: 5.426 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.269 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   6.914 ms/op
                 listUser·p0.95:   7.873 ms/op
                 listUser·p0.99:   9.765 ms/op
                 listUser·p0.999:  16.450 ms/op
                 listUser·p0.9999: 20.599 ms/op
                 listUser·p1.00:   22.249 ms/op

Iteration   2: 5.185 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   0.967 ms/op
                 listUser·p0.50:   4.932 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.791 ms/op
                 listUser·p0.99:   9.978 ms/op
                 listUser·p0.999:  19.049 ms/op
                 listUser·p0.9999: 23.145 ms/op
                 listUser·p1.00:   23.855 ms/op

Iteration   3: 5.315 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.196 ms/op
                 listUser·p0.50:   5.038 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   7.823 ms/op
                 listUser·p0.99:   10.240 ms/op
                 listUser·p0.999:  22.361 ms/op
                 listUser·p0.9999: 31.064 ms/op
                 listUser·p1.00:   31.359 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 180748
  mean =      5.307 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 119 
    [ 2.500,  5.000) = 85586 
    [ 5.000,  7.500) = 83455 
    [ 7.500, 10.000) = 9802 
    [10.000, 12.500) = 1159 
    [12.500, 15.000) = 300 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.967 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.832 ms/op
     p(99.0000) =      9.978 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     29.804 ms/op
     p(99.9990) =     31.306 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.212 ± 5.940  ops/ms
ClientGrpc.existUser                       thrpt       3   8.068 ± 2.941  ops/ms
ClientGrpc.getUser                         thrpt       3   7.445 ± 2.980  ops/ms
ClientGrpc.listUser                        thrpt       3   5.696 ± 1.165  ops/ms
ClientGrpc.createUser                       avgt       3   4.191 ± 1.854   ms/op
ClientGrpc.existUser                        avgt       3   3.795 ± 0.698   ms/op
ClientGrpc.getUser                          avgt       3   4.095 ± 1.610   ms/op
ClientGrpc.listUser                         avgt       3   5.511 ± 0.864   ms/op
ClientGrpc.createUser                     sample  228543   4.202 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.779           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.092           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.284           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.767           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.365           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.337           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          33.948           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          34.865           ms/op
ClientGrpc.existUser                      sample  240348   3.993 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.788           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.973           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.472           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.619           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.619           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.513           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          29.819           ms/op
ClientGrpc.getUser                        sample  231035   4.154 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.124           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.035           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.202           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.669           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.337           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.599           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.627           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.478           ms/op
ClientGrpc.listUser                       sample  180748   5.307 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.967           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.054           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.873           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.832           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.978           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.662           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          31.359           ms/op
