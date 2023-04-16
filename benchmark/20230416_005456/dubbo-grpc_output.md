# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.378 ops/ms
# Warmup Iteration   2: 5.204 ops/ms
# Warmup Iteration   3: 7.237 ops/ms
Iteration   1: 7.421 ops/ms
Iteration   2: 7.819 ops/ms
Iteration   3: 7.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.631 ±(99.9%) 3.645 ops/ms [Average]
  (min, avg, max) = (7.421, 7.631, 7.819), stdev = 0.200
  CI (99.9%): [3.986, 11.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.871 ops/ms
# Warmup Iteration   2: 7.617 ops/ms
# Warmup Iteration   3: 8.006 ops/ms
Iteration   1: 8.125 ops/ms
Iteration   2: 8.042 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.121 ±(99.9%) 1.415 ops/ms [Average]
  (min, avg, max) = (8.042, 8.121, 8.197), stdev = 0.078
  CI (99.9%): [6.706, 9.536] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.785 ops/ms
# Warmup Iteration   2: 7.193 ops/ms
# Warmup Iteration   3: 7.766 ops/ms
Iteration   1: 7.827 ops/ms
Iteration   2: 7.888 ops/ms
Iteration   3: 7.610 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.775 ±(99.9%) 2.666 ops/ms [Average]
  (min, avg, max) = (7.610, 7.775, 7.888), stdev = 0.146
  CI (99.9%): [5.109, 10.441] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.933 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 5.882 ops/ms
Iteration   1: 5.978 ops/ms
Iteration   2: 5.869 ops/ms
Iteration   3: 5.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.936 ±(99.9%) 1.069 ops/ms [Average]
  (min, avg, max) = (5.869, 5.936, 5.978), stdev = 0.059
  CI (99.9%): [4.867, 7.004] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.189 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.008 ms/op
Iteration   1: 4.319 ±(99.9%) 0.003 ms/op
Iteration   2: 4.172 ±(99.9%) 0.002 ms/op
Iteration   3: 4.183 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.225 ±(99.9%) 1.492 ms/op [Average]
  (min, avg, max) = (4.172, 4.225, 4.319), stdev = 0.082
  CI (99.9%): [2.733, 5.717] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.921 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.941 ±(99.9%) 0.003 ms/op
Iteration   1: 3.876 ±(99.9%) 0.002 ms/op
Iteration   2: 3.892 ±(99.9%) 0.003 ms/op
Iteration   3: 3.917 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.895 ±(99.9%) 0.378 ms/op [Average]
  (min, avg, max) = (3.876, 3.895, 3.917), stdev = 0.021
  CI (99.9%): [3.517, 4.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.249 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.011 ms/op
Iteration   1: 4.066 ±(99.9%) 0.003 ms/op
Iteration   2: 4.099 ±(99.9%) 0.003 ms/op
Iteration   3: 4.032 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.066 ±(99.9%) 0.616 ms/op [Average]
  (min, avg, max) = (4.032, 4.066, 4.099), stdev = 0.034
  CI (99.9%): [3.450, 4.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 7.861 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.706 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.024 ms/op
Iteration   1: 5.382 ±(99.9%) 0.018 ms/op
Iteration   2: 5.444 ±(99.9%) 0.018 ms/op
Iteration   3: 5.322 ±(99.9%) 0.031 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.383 ±(99.9%) 1.113 ms/op [Average]
  (min, avg, max) = (5.322, 5.383, 5.444), stdev = 0.061
  CI (99.9%): [4.270, 6.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.603 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.570 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.249 ±(99.9%) 0.011 ms/op
Iteration   1: 4.247 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.059 ms/op
                 createUser·p0.50:   4.178 ms/op
                 createUser·p0.90:   5.235 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   6.365 ms/op
                 createUser·p0.999:  13.118 ms/op
                 createUser·p0.9999: 18.101 ms/op
                 createUser·p1.00:   18.842 ms/op

Iteration   2: 4.167 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.076 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.530 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  9.950 ms/op
                 createUser·p0.9999: 30.540 ms/op
                 createUser·p1.00:   30.900 ms/op

Iteration   3: 4.214 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.038 ms/op
                 createUser·p0.50:   4.129 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.496 ms/op
                 createUser·p0.999:  17.281 ms/op
                 createUser·p0.9999: 35.258 ms/op
                 createUser·p1.00:   35.521 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 227885
  mean =      4.209 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3044 
    [ 2.500,  5.000) = 193210 
    [ 5.000,  7.500) = 30629 
    [ 7.500, 10.000) = 642 
    [10.000, 12.500) = 88 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.038 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      6.455 ms/op
     p(99.9000) =     13.470 ms/op
     p(99.9900) =     34.996 ms/op
     p(99.9990) =     35.437 ms/op
     p(99.9999) =     35.521 ms/op
    p(100.0000) =     35.521 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.646 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.121 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.858 ±(99.9%) 0.009 ms/op
Iteration   1: 3.882 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.030 ms/op
                 existUser·p0.50:   3.805 ms/op
                 existUser·p0.90:   4.669 ms/op
                 existUser·p0.95:   5.014 ms/op
                 existUser·p0.99:   6.095 ms/op
                 existUser·p0.999:  9.611 ms/op
                 existUser·p0.9999: 22.643 ms/op
                 existUser·p1.00:   23.200 ms/op

Iteration   2: 3.914 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.096 ms/op
                 existUser·p0.50:   3.822 ms/op
                 existUser·p0.90:   4.792 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.021 ms/op
                 existUser·p0.999:  8.934 ms/op
                 existUser·p0.9999: 31.124 ms/op
                 existUser·p1.00:   31.457 ms/op

Iteration   3: 3.802 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.899 ms/op
                 existUser·p0.99:   5.829 ms/op
                 existUser·p0.999:  13.135 ms/op
                 existUser·p0.9999: 28.396 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 248223
  mean =      3.865 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4473 
    [ 2.500,  5.000) = 230548 
    [ 5.000,  7.500) = 12344 
    [ 7.500, 10.000) = 587 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 70 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 47 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 19 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.669 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     10.875 ms/op
     p(99.9900) =     29.923 ms/op
     p(99.9990) =     31.441 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.161 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.234 ±(99.9%) 0.012 ms/op
Iteration   1: 4.080 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   4.018 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.431 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  14.451 ms/op
                 getUser·p0.9999: 15.458 ms/op
                 getUser·p1.00:   16.269 ms/op

Iteration   2: 4.141 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.143 ms/op
                 getUser·p0.50:   4.071 ms/op
                 getUser·p0.90:   5.063 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   6.488 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 17.572 ms/op
                 getUser·p1.00:   18.153 ms/op

Iteration   3: 4.127 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.331 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   5.005 ms/op
                 getUser·p0.95:   5.308 ms/op
                 getUser·p0.99:   6.021 ms/op
                 getUser·p0.999:  9.971 ms/op
                 getUser·p0.9999: 33.244 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 233152
  mean =      4.116 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4447 
    [ 2.500,  5.000) = 203812 
    [ 5.000,  7.500) = 23827 
    [ 7.500, 10.000) = 757 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.038 ms/op
     p(95.0000) =      5.374 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     11.024 ms/op
     p(99.9900) =     32.375 ms/op
     p(99.9990) =     33.664 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.878 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 5.860 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.570 ±(99.9%) 0.019 ms/op
Iteration   1: 5.335 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   5.128 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.471 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  16.238 ms/op
                 listUser·p0.9999: 20.022 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 5.548 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.767 ms/op
                 listUser·p0.50:   5.300 ms/op
                 listUser·p0.90:   7.037 ms/op
                 listUser·p0.95:   8.045 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  15.855 ms/op
                 listUser·p0.9999: 21.739 ms/op
                 listUser·p1.00:   23.036 ms/op

Iteration   3: 5.471 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   5.276 ms/op
                 listUser·p0.90:   6.767 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   9.732 ms/op
                 listUser·p0.999:  23.347 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   26.968 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176073
  mean =      5.450 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 96 
    [ 2.500,  5.000) = 67049 
    [ 5.000,  7.500) = 98361 
    [ 7.500, 10.000) = 8922 
    [10.000, 12.500) = 1234 
    [12.500, 15.000) = 138 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 74 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      6.808 ms/op
     p(95.0000) =      7.774 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     16.999 ms/op
     p(99.9900) =     24.654 ms/op
     p(99.9990) =     26.295 ms/op
     p(99.9999) =     26.968 ms/op
    p(100.0000) =     26.968 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.631 ± 3.645  ops/ms
ClientGrpc.existUser                       thrpt       3   8.121 ± 1.415  ops/ms
ClientGrpc.getUser                         thrpt       3   7.775 ± 2.666  ops/ms
ClientGrpc.listUser                        thrpt       3   5.936 ± 1.069  ops/ms
ClientGrpc.createUser                       avgt       3   4.225 ± 1.492   ms/op
ClientGrpc.existUser                        avgt       3   3.895 ± 0.378   ms/op
ClientGrpc.getUser                          avgt       3   4.066 ± 0.616   ms/op
ClientGrpc.listUser                         avgt       3   5.383 ± 1.113   ms/op
ClientGrpc.createUser                     sample  227885   4.209 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.038           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.186           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.538           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.455           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.470           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          34.996           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          35.521           ms/op
ClientGrpc.existUser                      sample  248223   3.865 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.784           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.789           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.669           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.030           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.980           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.875           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          29.923           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          31.457           ms/op
ClientGrpc.getUser                        sample  233152   4.116 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.712           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.038           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.374           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.308           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.024           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          32.375           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          33.751           ms/op
ClientGrpc.listUser                       sample  176073   5.450 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.296           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.774           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.896           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.999           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.654           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.968           ms/op
