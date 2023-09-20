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
# Warmup Iteration   1: 3.465 ops/ms
# Warmup Iteration   2: 8.010 ops/ms
# Warmup Iteration   3: 9.330 ops/ms
Iteration   1: 9.645 ops/ms
Iteration   2: 9.681 ops/ms
Iteration   3: 9.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.693 ±(99.9%) 1.020 ops/ms [Average]
  (min, avg, max) = (9.645, 9.693, 9.755), stdev = 0.056
  CI (99.9%): [8.674, 10.713] (assumes normal distribution)


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
# Warmup Iteration   1: 6.841 ops/ms
# Warmup Iteration   2: 9.937 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.344 ops/ms
Iteration   2: 10.405 ops/ms
Iteration   3: 10.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.424 ±(99.9%) 1.648 ops/ms [Average]
  (min, avg, max) = (10.344, 10.424, 10.522), stdev = 0.090
  CI (99.9%): [8.776, 12.071] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.202 ops/ms
# Warmup Iteration   2: 9.731 ops/ms
# Warmup Iteration   3: 10.090 ops/ms
Iteration   1: 10.228 ops/ms
Iteration   2: 10.189 ops/ms
Iteration   3: 10.383 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.266 ±(99.9%) 1.874 ops/ms [Average]
  (min, avg, max) = (10.189, 10.266, 10.383), stdev = 0.103
  CI (99.9%): [8.393, 12.140] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.314 ops/ms
# Warmup Iteration   2: 7.856 ops/ms
# Warmup Iteration   3: 8.107 ops/ms
Iteration   1: 8.000 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.098 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.150 ±(99.9%) 3.306 ops/ms [Average]
  (min, avg, max) = (8.000, 8.150, 8.351), stdev = 0.181
  CI (99.9%): [4.843, 11.456] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.799 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.261 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.178 ±(99.9%) 0.004 ms/op
Iteration   1: 3.249 ±(99.9%) 0.003 ms/op
Iteration   2: 3.153 ±(99.9%) 0.005 ms/op
Iteration   3: 3.175 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.192 ±(99.9%) 0.914 ms/op [Average]
  (min, avg, max) = (3.153, 3.192, 3.249), stdev = 0.050
  CI (99.9%): [2.278, 4.106] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.530 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.186 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.130 ±(99.9%) 0.002 ms/op
Iteration   1: 2.951 ±(99.9%) 0.004 ms/op
Iteration   2: 3.043 ±(99.9%) 0.003 ms/op
Iteration   3: 3.012 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.002 ±(99.9%) 0.858 ms/op [Average]
  (min, avg, max) = (2.951, 3.002, 3.043), stdev = 0.047
  CI (99.9%): [2.144, 3.859] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.501 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.285 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.003 ms/op
Iteration   1: 3.156 ±(99.9%) 0.005 ms/op
Iteration   2: 3.119 ±(99.9%) 0.002 ms/op
Iteration   3: 3.103 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.126 ±(99.9%) 0.495 ms/op [Average]
  (min, avg, max) = (3.103, 3.126, 3.156), stdev = 0.027
  CI (99.9%): [2.631, 3.621] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.695 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.211 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.019 ms/op
Iteration   1: 4.024 ±(99.9%) 0.023 ms/op
Iteration   2: 3.986 ±(99.9%) 0.031 ms/op
Iteration   3: 3.958 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.989 ±(99.9%) 0.607 ms/op [Average]
  (min, avg, max) = (3.958, 3.989, 4.024), stdev = 0.033
  CI (99.9%): [3.382, 4.596] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.049 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.899 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.731 ms/op
                 createUser·p0.95:   3.944 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  11.654 ms/op
                 createUser·p0.9999: 15.535 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.698 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  8.392 ms/op
                 createUser·p0.9999: 25.592 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.173 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.522 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.678 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.596 ms/op
                 createUser·p0.999:  17.662 ms/op
                 createUser·p0.9999: 24.281 ms/op
                 createUser·p1.00:   25.428 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 302453
  mean =      3.174 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8401 
    [ 2.500,  5.000) = 292176 
    [ 5.000,  7.500) = 1285 
    [ 7.500, 10.000) = 198 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 158 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.522 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      3.891 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     13.894 ms/op
     p(99.9900) =     24.281 ms/op
     p(99.9990) =     25.788 ms/op
     p(99.9999) =     25.788 ms/op
    p(100.0000) =     25.788 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.016 ±(99.9%) 0.007 ms/op
Iteration   1: 3.002 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.546 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.051 ms/op
                 existUser·p0.999:  8.126 ms/op
                 existUser·p0.9999: 13.304 ms/op
                 existUser·p1.00:   13.468 ms/op

Iteration   2: 2.975 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.712 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.555 ms/op
                 existUser·p0.99:   4.219 ms/op
                 existUser·p0.999:  8.041 ms/op
                 existUser·p0.9999: 26.542 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   3: 3.023 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.681 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  7.560 ms/op
                 existUser·p0.9999: 20.513 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319702
  mean =      3.000 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19354 
    [ 2.500,  5.000) = 299056 
    [ 5.000,  7.500) = 942 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 40 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.437 ms/op
     p(95.0000) =      3.629 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      8.076 ms/op
     p(99.9900) =     22.088 ms/op
     p(99.9990) =     26.798 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 4.799 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.365 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.061 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.461 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.082 ms/op
                 getUser·p0.9999: 17.713 ms/op
                 getUser·p1.00:   18.252 ms/op

Iteration   2: 3.161 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.653 ms/op
                 getUser·p0.999:  11.698 ms/op
                 getUser·p0.9999: 20.034 ms/op
                 getUser·p1.00:   20.677 ms/op

Iteration   3: 3.182 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.839 ms/op
                 getUser·p0.50:   3.117 ms/op
                 getUser·p0.90:   3.752 ms/op
                 getUser·p0.95:   3.940 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  10.224 ms/op
                 getUser·p0.9999: 21.919 ms/op
                 getUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 306288
  mean =      3.134 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10028 
    [ 2.500,  5.000) = 294312 
    [ 5.000,  7.500) = 1378 
    [ 7.500, 10.000) = 275 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.461 ms/op
     p(50.0000) =      3.088 ms/op
     p(90.0000) =      3.658 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.538 ms/op
     p(99.9000) =      9.809 ms/op
     p(99.9900) =     20.832 ms/op
     p(99.9990) =     22.213 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 5.757 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.131 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 4.007 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.678 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.909 ms/op
                 listUser·p0.9999: 26.837 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.229 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.506 ms/op
                 listUser·p0.95:   5.235 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  15.176 ms/op
                 listUser·p0.9999: 17.492 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.984 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.908 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.941 ms/op
                 listUser·p0.999:  17.775 ms/op
                 listUser·p0.9999: 26.934 ms/op
                 listUser·p1.00:   27.296 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241970
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2657 
    [ 2.500,  5.000) = 220255 
    [ 5.000,  7.500) = 17507 
    [ 7.500, 10.000) = 919 
    [10.000, 12.500) = 185 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 194 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      3.838 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.914 ms/op
     p(99.9000) =     15.418 ms/op
     p(99.9900) =     26.804 ms/op
     p(99.9990) =     27.203 ms/op
     p(99.9999) =     27.296 ms/op
    p(100.0000) =     27.296 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.693 ± 1.020  ops/ms
ClientGrpc.existUser                       thrpt       3  10.424 ± 1.648  ops/ms
ClientGrpc.getUser                         thrpt       3  10.266 ± 1.874  ops/ms
ClientGrpc.listUser                        thrpt       3   8.150 ± 3.306  ops/ms
ClientGrpc.createUser                       avgt       3   3.192 ± 0.914   ms/op
ClientGrpc.existUser                        avgt       3   3.002 ± 0.858   ms/op
ClientGrpc.getUser                          avgt       3   3.126 ± 0.495   ms/op
ClientGrpc.listUser                         avgt       3   3.989 ± 0.607   ms/op
ClientGrpc.createUser                     sample  302453   3.174 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.522           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.129           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.699           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.481           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.894           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.281           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          25.788           ms/op
ClientGrpc.existUser                      sample  319702   3.000 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.546           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.437           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.629           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          22.088           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.870           ms/op
ClientGrpc.getUser                        sample  306288   3.134 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.461           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.088           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.903           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.538           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.809           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.832           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.282           ms/op
ClientGrpc.listUser                       sample  241970   3.967 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.908           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.838           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.661           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.914           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.418           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.804           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.296           ms/op
