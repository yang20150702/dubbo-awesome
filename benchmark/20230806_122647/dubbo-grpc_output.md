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
# Warmup Iteration   1: 2.292 ops/ms
# Warmup Iteration   2: 5.527 ops/ms
# Warmup Iteration   3: 6.973 ops/ms
Iteration   1: 7.280 ops/ms
Iteration   2: 7.543 ops/ms
Iteration   3: 7.511 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.445 ±(99.9%) 2.614 ops/ms [Average]
  (min, avg, max) = (7.280, 7.445, 7.543), stdev = 0.143
  CI (99.9%): [4.831, 10.058] (assumes normal distribution)


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
# Warmup Iteration   1: 5.252 ops/ms
# Warmup Iteration   2: 7.371 ops/ms
# Warmup Iteration   3: 7.906 ops/ms
Iteration   1: 8.042 ops/ms
Iteration   2: 8.291 ops/ms
Iteration   3: 8.229 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.187 ±(99.9%) 2.370 ops/ms [Average]
  (min, avg, max) = (8.042, 8.187, 8.291), stdev = 0.130
  CI (99.9%): [5.817, 10.557] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.618 ops/ms
# Warmup Iteration   2: 6.942 ops/ms
# Warmup Iteration   3: 7.631 ops/ms
Iteration   1: 7.701 ops/ms
Iteration   2: 7.970 ops/ms
Iteration   3: 7.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.774 ±(99.9%) 3.135 ops/ms [Average]
  (min, avg, max) = (7.651, 7.774, 7.970), stdev = 0.172
  CI (99.9%): [4.640, 10.909] (assumes normal distribution)


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
# Warmup Iteration   1: 3.812 ops/ms
# Warmup Iteration   2: 5.243 ops/ms
# Warmup Iteration   3: 5.860 ops/ms
Iteration   1: 5.814 ops/ms
Iteration   2: 5.923 ops/ms
Iteration   3: 5.977 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.905 ±(99.9%) 1.516 ops/ms [Average]
  (min, avg, max) = (5.814, 5.905, 5.977), stdev = 0.083
  CI (99.9%): [4.389, 7.420] (assumes normal distribution)


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
# Warmup Iteration   1: 6.513 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.599 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.441 ±(99.9%) 0.013 ms/op
Iteration   1: 4.180 ±(99.9%) 0.005 ms/op
Iteration   2: 4.213 ±(99.9%) 0.004 ms/op
Iteration   3: 4.300 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.231 ±(99.9%) 1.126 ms/op [Average]
  (min, avg, max) = (4.180, 4.231, 4.300), stdev = 0.062
  CI (99.9%): [3.105, 5.357] (assumes normal distribution)


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
# Warmup Iteration   1: 5.959 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.017 ±(99.9%) 0.004 ms/op
Iteration   1: 4.022 ±(99.9%) 0.002 ms/op
Iteration   2: 3.793 ±(99.9%) 0.003 ms/op
Iteration   3: 3.949 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.921 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (3.793, 3.921, 4.022), stdev = 0.117
  CI (99.9%): [1.789, 6.053] (assumes normal distribution)


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
# Warmup Iteration   1: 6.589 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.635 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.267 ±(99.9%) 0.003 ms/op
Iteration   1: 4.151 ±(99.9%) 0.007 ms/op
Iteration   2: 4.284 ±(99.9%) 0.004 ms/op
Iteration   3: 4.275 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.237 ±(99.9%) 1.360 ms/op [Average]
  (min, avg, max) = (4.151, 4.237, 4.284), stdev = 0.075
  CI (99.9%): [2.877, 5.597] (assumes normal distribution)


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
# Warmup Iteration   1: 8.655 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 5.825 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.016 ms/op
Iteration   1: 5.424 ±(99.9%) 0.014 ms/op
Iteration   2: 5.352 ±(99.9%) 0.017 ms/op
Iteration   3: 5.532 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.436 ±(99.9%) 1.646 ms/op [Average]
  (min, avg, max) = (5.352, 5.436, 5.532), stdev = 0.090
  CI (99.9%): [3.790, 7.083] (assumes normal distribution)


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
# Warmup Iteration   1: 6.348 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.549 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.281 ±(99.9%) 0.013 ms/op
Iteration   1: 4.207 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.069 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.341 ms/op
                 createUser·p0.95:   5.865 ms/op
                 createUser·p0.99:   8.389 ms/op
                 createUser·p0.999:  12.712 ms/op
                 createUser·p0.9999: 15.866 ms/op
                 createUser·p1.00:   16.122 ms/op

Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   4.063 ms/op
                 createUser·p0.90:   5.210 ms/op
                 createUser·p0.95:   5.693 ms/op
                 createUser·p0.99:   7.952 ms/op
                 createUser·p0.999:  14.263 ms/op
                 createUser·p0.9999: 17.978 ms/op
                 createUser·p1.00:   18.547 ms/op

Iteration   3: 4.338 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   0.837 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.505 ms/op
                 createUser·p0.95:   6.005 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  15.070 ms/op
                 createUser·p0.9999: 22.073 ms/op
                 createUser·p1.00:   26.444 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 226578
  mean =      4.239 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5914 
    [ 2.500,  5.000) = 183302 
    [ 5.000,  7.500) = 34189 
    [ 7.500, 10.000) = 2215 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 159 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.837 ms/op
     p(50.0000) =      4.104 ms/op
     p(90.0000) =      5.358 ms/op
     p(95.0000) =      5.865 ms/op
     p(99.0000) =      8.192 ms/op
     p(99.9000) =     13.720 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     22.608 ms/op
     p(99.9999) =     26.444 ms/op
    p(100.0000) =     26.444 ms/op


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
# Warmup Iteration   1: 5.486 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.283 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.013 ms/op
Iteration   1: 4.027 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.968 ms/op
                 existUser·p0.50:   3.891 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.258 ms/op
                 existUser·p0.999:  10.314 ms/op
                 existUser·p0.9999: 14.764 ms/op
                 existUser·p1.00:   15.073 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.916 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.325 ms/op
                 existUser·p0.99:   6.939 ms/op
                 existUser·p0.999:  10.311 ms/op
                 existUser·p0.9999: 19.784 ms/op
                 existUser·p1.00:   19.890 ms/op

Iteration   3: 3.947 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.913 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.907 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   8.208 ms/op
                 existUser·p0.999:  11.369 ms/op
                 existUser·p0.9999: 21.823 ms/op
                 existUser·p1.00:   22.053 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 242865
  mean =      3.954 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7650 
    [ 2.500,  5.000) = 210929 
    [ 5.000,  7.500) = 21902 
    [ 7.500, 10.000) = 1932 
    [10.000, 12.500) = 351 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      5.000 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      7.471 ms/op
     p(99.9000) =     10.879 ms/op
     p(99.9900) =     21.421 ms/op
     p(99.9990) =     22.006 ms/op
     p(99.9999) =     22.053 ms/op
    p(100.0000) =     22.053 ms/op


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
# Warmup Iteration   1: 5.954 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.544 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.272 ±(99.9%) 0.014 ms/op
Iteration   1: 4.128 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.998 ms/op
                 getUser·p0.90:   5.161 ms/op
                 getUser·p0.95:   5.661 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  12.961 ms/op
                 getUser·p0.9999: 18.481 ms/op
                 getUser·p1.00:   20.120 ms/op

Iteration   2: 4.177 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   4.035 ms/op
                 getUser·p0.90:   5.333 ms/op
                 getUser·p0.95:   5.849 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  12.065 ms/op
                 getUser·p0.9999: 23.594 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   3: 4.067 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.969 ms/op
                 getUser·p0.90:   4.997 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.197 ms/op
                 getUser·p0.999:  10.383 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 232698
  mean =      4.123 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4695 
    [ 2.500,  5.000) = 198362 
    [ 5.000,  7.500) = 27372 
    [ 7.500, 10.000) = 1803 
    [10.000, 12.500) = 251 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      4.000 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.636 ms/op
     p(99.0000) =      7.455 ms/op
     p(99.9000) =     12.304 ms/op
     p(99.9900) =     23.543 ms/op
     p(99.9990) =     24.948 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 8.391 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 5.713 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 5.496 ±(99.9%) 0.021 ms/op
Iteration   1: 5.301 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.493 ms/op
                 listUser·p0.50:   5.014 ms/op
                 listUser·p0.90:   6.939 ms/op
                 listUser·p0.95:   7.995 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  16.874 ms/op
                 listUser·p0.9999: 19.822 ms/op
                 listUser·p1.00:   20.546 ms/op

Iteration   2: 5.802 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.921 ms/op
                 listUser·p0.50:   5.456 ms/op
                 listUser·p0.90:   7.651 ms/op
                 listUser·p0.95:   8.749 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  19.724 ms/op
                 listUser·p0.9999: 24.264 ms/op
                 listUser·p1.00:   26.116 ms/op

Iteration   3: 5.494 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   5.153 ms/op
                 listUser·p0.90:   7.389 ms/op
                 listUser·p0.95:   8.343 ms/op
                 listUser·p0.99:   11.370 ms/op
                 listUser·p0.999:  20.634 ms/op
                 listUser·p0.9999: 24.188 ms/op
                 listUser·p1.00:   24.478 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 173741
  mean =      5.524 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 123 
    [ 2.500,  5.000) = 72133 
    [ 5.000,  7.500) = 85729 
    [ 7.500, 10.000) = 12682 
    [10.000, 12.500) = 2152 
    [12.500, 15.000) = 498 
    [15.000, 17.500) = 151 
    [17.500, 20.000) = 146 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 43 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      5.202 ms/op
     p(90.0000) =      7.356 ms/op
     p(95.0000) =      8.356 ms/op
     p(99.0000) =     11.026 ms/op
     p(99.9000) =     19.333 ms/op
     p(99.9900) =     24.183 ms/op
     p(99.9990) =     25.995 ms/op
     p(99.9999) =     26.116 ms/op
    p(100.0000) =     26.116 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.445 ± 2.614  ops/ms
ClientGrpc.existUser                       thrpt       3   8.187 ± 2.370  ops/ms
ClientGrpc.getUser                         thrpt       3   7.774 ± 3.135  ops/ms
ClientGrpc.listUser                        thrpt       3   5.905 ± 1.516  ops/ms
ClientGrpc.createUser                       avgt       3   4.231 ± 1.126   ms/op
ClientGrpc.existUser                        avgt       3   3.921 ± 2.132   ms/op
ClientGrpc.getUser                          avgt       3   4.237 ± 1.360   ms/op
ClientGrpc.listUser                         avgt       3   5.436 ± 1.646   ms/op
ClientGrpc.createUser                     sample  226578   4.239 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.837           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.104           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.192           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.720           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.725           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.444           ms/op
ClientGrpc.existUser                      sample  242865   3.954 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.913           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.000           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.471           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.879           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.421           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.053           ms/op
ClientGrpc.getUser                        sample  232698   4.123 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.999           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.000           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.161           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.636           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.455           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.304           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          23.543           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.002           ms/op
ClientGrpc.listUser                       sample  173741   5.524 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.761           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.202           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.356           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.356           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          11.026           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.333           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.183           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.116           ms/op
