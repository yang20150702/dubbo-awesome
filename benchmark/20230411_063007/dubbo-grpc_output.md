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
# Warmup Iteration   1: 2.493 ops/ms
# Warmup Iteration   2: 5.599 ops/ms
# Warmup Iteration   3: 7.408 ops/ms
Iteration   1: 7.983 ops/ms
Iteration   2: 7.655 ops/ms
Iteration   3: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.882 ±(99.9%) 3.598 ops/ms [Average]
  (min, avg, max) = (7.655, 7.882, 8.008), stdev = 0.197
  CI (99.9%): [4.284, 11.480] (assumes normal distribution)


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
# Warmup Iteration   1: 5.126 ops/ms
# Warmup Iteration   2: 7.506 ops/ms
# Warmup Iteration   3: 7.821 ops/ms
Iteration   1: 7.893 ops/ms
Iteration   2: 8.063 ops/ms
Iteration   3: 7.942 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.966 ±(99.9%) 1.596 ops/ms [Average]
  (min, avg, max) = (7.893, 7.966, 8.063), stdev = 0.087
  CI (99.9%): [6.370, 9.562] (assumes normal distribution)


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
# Warmup Iteration   1: 4.525 ops/ms
# Warmup Iteration   2: 6.980 ops/ms
# Warmup Iteration   3: 7.738 ops/ms
Iteration   1: 7.723 ops/ms
Iteration   2: 7.512 ops/ms
Iteration   3: 7.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.677 ±(99.9%) 2.690 ops/ms [Average]
  (min, avg, max) = (7.512, 7.677, 7.796), stdev = 0.147
  CI (99.9%): [4.987, 10.366] (assumes normal distribution)


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
# Warmup Iteration   1: 3.968 ops/ms
# Warmup Iteration   2: 5.147 ops/ms
# Warmup Iteration   3: 5.604 ops/ms
Iteration   1: 5.494 ops/ms
Iteration   2: 5.544 ops/ms
Iteration   3: 5.724 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.587 ±(99.9%) 2.200 ops/ms [Average]
  (min, avg, max) = (5.494, 5.587, 5.724), stdev = 0.121
  CI (99.9%): [3.387, 7.787] (assumes normal distribution)


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
# Warmup Iteration   1: 6.318 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.435 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.308 ±(99.9%) 0.007 ms/op
Iteration   1: 4.313 ±(99.9%) 0.003 ms/op
Iteration   2: 4.003 ±(99.9%) 0.002 ms/op
Iteration   3: 3.938 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.084 ±(99.9%) 3.654 ms/op [Average]
  (min, avg, max) = (3.938, 4.084, 4.313), stdev = 0.200
  CI (99.9%): [0.430, 7.739] (assumes normal distribution)


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
# Warmup Iteration   1: 5.595 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.108 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.918 ±(99.9%) 0.003 ms/op
Iteration   1: 3.836 ±(99.9%) 0.003 ms/op
Iteration   2: 3.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.955 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.930 ±(99.9%) 1.526 ms/op [Average]
  (min, avg, max) = (3.836, 3.930, 3.998), stdev = 0.084
  CI (99.9%): [2.404, 5.456] (assumes normal distribution)


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
# Warmup Iteration   1: 5.941 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.252 ±(99.9%) 0.006 ms/op
Iteration   1: 4.103 ±(99.9%) 0.005 ms/op
Iteration   2: 4.270 ±(99.9%) 0.003 ms/op
Iteration   3: 4.259 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.211 ±(99.9%) 1.708 ms/op [Average]
  (min, avg, max) = (4.103, 4.211, 4.270), stdev = 0.094
  CI (99.9%): [2.502, 5.919] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.808 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.833 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.580 ±(99.9%) 0.019 ms/op
Iteration   1: 5.533 ±(99.9%) 0.009 ms/op
Iteration   2: 5.556 ±(99.9%) 0.017 ms/op
Iteration   3: 5.542 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.544 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (5.533, 5.544, 5.556), stdev = 0.012
  CI (99.9%): [5.327, 5.760] (assumes normal distribution)


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
# Warmup Iteration   1: 6.172 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 4.711 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.312 ±(99.9%) 0.013 ms/op
Iteration   1: 4.096 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   5.038 ms/op
                 createUser·p0.95:   5.505 ms/op
                 createUser·p0.99:   6.758 ms/op
                 createUser·p0.999:  10.403 ms/op
                 createUser·p0.9999: 25.906 ms/op
                 createUser·p1.00:   26.345 ms/op

Iteration   2: 4.143 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.192 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   5.169 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  17.629 ms/op
                 createUser·p0.9999: 26.232 ms/op
                 createUser·p1.00:   27.034 ms/op

Iteration   3: 4.194 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.110 ms/op
                 createUser·p0.999:  11.896 ms/op
                 createUser·p0.9999: 28.172 ms/op
                 createUser·p1.00:   28.508 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 231680
  mean =      4.144 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3630 
    [ 2.500,  5.000) = 199234 
    [ 5.000,  7.500) = 27460 
    [ 7.500, 10.000) = 915 
    [10.000, 12.500) = 225 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 57 

  Percentiles, ms/op:
      p(0.0000) =      1.137 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     12.036 ms/op
     p(99.9900) =     27.558 ms/op
     p(99.9990) =     28.399 ms/op
     p(99.9999) =     28.508 ms/op
    p(100.0000) =     28.508 ms/op


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
# Warmup Iteration   1: 5.633 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.010 ms/op
Iteration   1: 4.004 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.940 ms/op
                 existUser·p0.90:   4.866 ms/op
                 existUser·p0.95:   5.259 ms/op
                 existUser·p0.99:   6.365 ms/op
                 existUser·p0.999:  11.698 ms/op
                 existUser·p0.9999: 17.990 ms/op
                 existUser·p1.00:   21.234 ms/op

Iteration   2: 3.842 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.821 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.054 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  11.285 ms/op
                 existUser·p0.9999: 16.619 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 3.971 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.110 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  10.600 ms/op
                 existUser·p0.9999: 19.954 ms/op
                 existUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 243637
  mean =      3.937 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6937 
    [ 2.500,  5.000) = 220199 
    [ 5.000,  7.500) = 15278 
    [ 7.500, 10.000) = 869 
    [10.000, 12.500) = 201 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.821 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.792 ms/op
     p(95.0000) =      5.177 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     10.994 ms/op
     p(99.9900) =     18.109 ms/op
     p(99.9990) =     20.677 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 6.342 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 4.500 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.280 ±(99.9%) 0.011 ms/op
Iteration   1: 4.386 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   4.219 ms/op
                 getUser·p0.90:   5.521 ms/op
                 getUser·p0.95:   6.095 ms/op
                 getUser·p0.99:   8.358 ms/op
                 getUser·p0.999:  14.567 ms/op
                 getUser·p0.9999: 23.541 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   2: 4.285 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.842 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.390 ms/op
                 getUser·p0.95:   5.939 ms/op
                 getUser·p0.99:   8.117 ms/op
                 getUser·p0.999:  14.869 ms/op
                 getUser·p0.9999: 18.859 ms/op
                 getUser·p1.00:   19.202 ms/op

Iteration   3: 4.113 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   5.079 ms/op
                 getUser·p0.95:   5.497 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  12.014 ms/op
                 getUser·p0.9999: 20.331 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 225298
  mean =      4.258 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4220 
    [ 2.500,  5.000) = 185333 
    [ 5.000,  7.500) = 32908 
    [ 7.500, 10.000) = 2131 
    [10.000, 12.500) = 367 
    [12.500, 15.000) = 172 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      4.116 ms/op
     p(90.0000) =      5.325 ms/op
     p(95.0000) =      5.849 ms/op
     p(99.0000) =      7.913 ms/op
     p(99.9000) =     13.910 ms/op
     p(99.9900) =     22.837 ms/op
     p(99.9990) =     23.879 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 8.374 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.009 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.493 ±(99.9%) 0.019 ms/op
Iteration   1: 5.643 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.315 ms/op
                 listUser·p0.50:   5.358 ms/op
                 listUser·p0.90:   7.340 ms/op
                 listUser·p0.95:   8.487 ms/op
                 listUser·p0.99:   10.813 ms/op
                 listUser·p0.999:  19.275 ms/op
                 listUser·p0.9999: 26.444 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   2: 5.616 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   5.374 ms/op
                 listUser·p0.90:   7.402 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   10.610 ms/op
                 listUser·p0.999:  18.383 ms/op
                 listUser·p0.9999: 20.976 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 5.871 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   5.587 ms/op
                 listUser·p0.90:   7.537 ms/op
                 listUser·p0.95:   8.634 ms/op
                 listUser·p0.99:   11.403 ms/op
                 listUser·p0.999:  22.857 ms/op
                 listUser·p0.9999: 26.921 ms/op
                 listUser·p1.00:   27.525 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 168102
  mean =      5.708 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 188 
    [ 2.500,  5.000) = 51339 
    [ 5.000,  7.500) = 100445 
    [ 7.500, 10.000) = 13201 
    [10.000, 12.500) = 2053 
    [12.500, 15.000) = 465 
    [15.000, 17.500) = 140 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 59 
    [25.000, 27.500) = 39 
    [27.500, 30.000) = 3 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.315 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     10.961 ms/op
     p(99.9000) =     19.920 ms/op
     p(99.9900) =     26.456 ms/op
     p(99.9990) =     30.124 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.882 ± 3.598  ops/ms
ClientGrpc.existUser                       thrpt       3   7.966 ± 1.596  ops/ms
ClientGrpc.getUser                         thrpt       3   7.677 ± 2.690  ops/ms
ClientGrpc.listUser                        thrpt       3   5.587 ± 2.200  ops/ms
ClientGrpc.createUser                       avgt       3   4.084 ± 3.654   ms/op
ClientGrpc.existUser                        avgt       3   3.930 ± 1.526   ms/op
ClientGrpc.getUser                          avgt       3   4.211 ± 1.708   ms/op
ClientGrpc.listUser                         avgt       3   5.544 ± 0.216   ms/op
ClientGrpc.createUser                     sample  231680   4.144 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.137           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.136           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.562           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.791           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.036           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.558           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          28.508           ms/op
ClientGrpc.existUser                      sample  243637   3.937 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.821           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.792           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.177           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.439           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.994           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.109           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.234           ms/op
ClientGrpc.getUser                        sample  225298   4.258 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.805           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.116           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.325           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.849           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.913           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.910           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.837           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  168102   5.708 ± 0.013   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.315           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.439           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.430           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.503           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.961           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.920           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.456           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.147           ms/op
