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
# Warmup Iteration   1: 4.186 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.932 ops/ms
Iteration   1: 10.336 ops/ms
Iteration   2: 10.627 ops/ms
Iteration   3: 10.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.502 ±(99.9%) 2.737 ops/ms [Average]
  (min, avg, max) = (10.336, 10.502, 10.627), stdev = 0.150
  CI (99.9%): [7.766, 13.239] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.387 ops/ms
# Warmup Iteration   2: 10.686 ops/ms
# Warmup Iteration   3: 11.063 ops/ms
Iteration   1: 11.174 ops/ms
Iteration   2: 11.054 ops/ms
Iteration   3: 10.993 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.074 ±(99.9%) 1.676 ops/ms [Average]
  (min, avg, max) = (10.993, 11.074, 11.174), stdev = 0.092
  CI (99.9%): [9.398, 12.750] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.420 ops/ms
# Warmup Iteration   2: 10.057 ops/ms
# Warmup Iteration   3: 10.443 ops/ms
Iteration   1: 10.531 ops/ms
Iteration   2: 10.576 ops/ms
Iteration   3: 10.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.584 ±(99.9%) 1.049 ops/ms [Average]
  (min, avg, max) = (10.531, 10.584, 10.645), stdev = 0.057
  CI (99.9%): [9.535, 11.633] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.172 ops/ms
# Warmup Iteration   2: 7.494 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 7.692 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.867 ±(99.9%) 4.220 ops/ms [Average]
  (min, avg, max) = (7.692, 7.867, 8.129), stdev = 0.231
  CI (99.9%): [3.647, 12.087] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.473 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.172 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.002 ms/op
Iteration   1: 3.023 ±(99.9%) 0.002 ms/op
Iteration   2: 3.070 ±(99.9%) 0.003 ms/op
Iteration   3: 3.046 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.047 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (3.023, 3.047, 3.070), stdev = 0.023
  CI (99.9%): [2.619, 3.475] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.048 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.910 ±(99.9%) 0.002 ms/op
Iteration   1: 2.888 ±(99.9%) 0.003 ms/op
Iteration   2: 2.892 ±(99.9%) 0.003 ms/op
Iteration   3: 2.913 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.898 ±(99.9%) 0.244 ms/op [Average]
  (min, avg, max) = (2.888, 2.898, 2.913), stdev = 0.013
  CI (99.9%): [2.654, 3.142] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.327 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.179 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.050 ±(99.9%) 0.003 ms/op
Iteration   1: 3.069 ±(99.9%) 0.005 ms/op
Iteration   2: 3.041 ±(99.9%) 0.004 ms/op
Iteration   3: 3.019 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.043 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.019, 3.043, 3.069), stdev = 0.025
  CI (99.9%): [2.585, 3.501] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.768 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 4.142 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.007 ±(99.9%) 0.009 ms/op
Iteration   1: 4.004 ±(99.9%) 0.013 ms/op
Iteration   2: 3.981 ±(99.9%) 0.006 ms/op
Iteration   3: 3.959 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.981 ±(99.9%) 0.410 ms/op [Average]
  (min, avg, max) = (3.959, 3.981, 4.004), stdev = 0.022
  CI (99.9%): [3.571, 4.392] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.260 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.064 ±(99.9%) 0.006 ms/op
Iteration   1: 3.042 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.558 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.604 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   4.735 ms/op
                 createUser·p0.999:  8.483 ms/op
                 createUser·p0.9999: 13.115 ms/op
                 createUser·p1.00:   13.320 ms/op

Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.876 ms/op
                 createUser·p0.50:   3.056 ms/op
                 createUser·p0.90:   3.662 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.628 ms/op
                 createUser·p0.999:  9.290 ms/op
                 createUser·p0.9999: 15.941 ms/op
                 createUser·p1.00:   16.515 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.820 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.722 ms/op
                 createUser·p0.999:  10.600 ms/op
                 createUser·p0.9999: 18.493 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 313909
  mean =      3.060 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 688 
    [ 1.250,  2.500) = 25392 
    [ 2.500,  3.750) = 267015 
    [ 3.750,  5.000) = 18661 
    [ 5.000,  6.250) = 1018 
    [ 6.250,  7.500) = 563 
    [ 7.500,  8.750) = 200 
    [ 8.750, 10.000) = 106 
    [10.000, 11.250) = 73 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 17 
    [15.000, 16.250) = 35 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.558 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     17.007 ms/op
     p(99.9990) =     18.804 ms/op
     p(99.9999) =     18.842 ms/op
    p(100.0000) =     18.842 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.881 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.032 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.939 ±(99.9%) 0.005 ms/op
Iteration   1: 2.925 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.607 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.530 ms/op
                 existUser·p0.999:  7.844 ms/op
                 existUser·p0.9999: 14.828 ms/op
                 existUser·p1.00:   15.090 ms/op

Iteration   2: 2.900 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.553 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.408 ms/op
                 existUser·p0.9999: 14.565 ms/op
                 existUser·p1.00:   14.860 ms/op

Iteration   3: 2.938 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.621 ms/op
                 existUser·p0.50:   2.904 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  7.490 ms/op
                 existUser·p0.9999: 18.226 ms/op
                 existUser·p1.00:   18.874 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 328753
  mean =      2.921 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2099 
    [ 1.250,  2.500) = 40660 
    [ 2.500,  3.750) = 273762 
    [ 3.750,  5.000) = 10365 
    [ 5.000,  6.250) = 851 
    [ 6.250,  7.500) = 539 
    [ 7.500,  8.750) = 189 
    [ 8.750, 10.000) = 18 
    [10.000, 11.250) = 26 
    [11.250, 12.500) = 33 
    [12.500, 13.750) = 36 
    [13.750, 15.000) = 75 
    [15.000, 16.250) = 58 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.896 ms/op
     p(90.0000) =      3.424 ms/op
     p(95.0000) =      3.650 ms/op
     p(99.0000) =      4.522 ms/op
     p(99.9000) =      8.200 ms/op
     p(99.9900) =     17.465 ms/op
     p(99.9990) =     18.593 ms/op
     p(99.9999) =     18.874 ms/op
    p(100.0000) =     18.874 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.985 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.226 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.071 ±(99.9%) 0.006 ms/op
Iteration   1: 3.056 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.699 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.707 ms/op
                 getUser·p0.95:   3.961 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  8.372 ms/op
                 getUser·p0.9999: 13.534 ms/op
                 getUser·p1.00:   14.156 ms/op

Iteration   2: 3.103 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.823 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.465 ms/op
                 getUser·p0.999:  8.811 ms/op
                 getUser·p0.9999: 18.132 ms/op
                 getUser·p1.00:   19.923 ms/op

Iteration   3: 3.067 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.566 ms/op
                 getUser·p0.50:   3.027 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.822 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.099 ms/op
                 getUser·p0.9999: 19.628 ms/op
                 getUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 312429
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20357 
    [ 2.500,  5.000) = 289708 
    [ 5.000,  7.500) = 1788 
    [ 7.500, 10.000) = 350 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.566 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.641 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      8.651 ms/op
     p(99.9900) =     19.431 ms/op
     p(99.9990) =     19.984 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.108 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.170 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.070 ±(99.9%) 0.012 ms/op
Iteration   1: 4.058 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   3.883 ms/op
                 listUser·p0.90:   5.095 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   7.176 ms/op
                 listUser·p0.999:  13.979 ms/op
                 listUser·p0.9999: 16.482 ms/op
                 listUser·p1.00:   16.646 ms/op

Iteration   2: 3.956 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.201 ms/op
                 listUser·p0.999:  18.422 ms/op
                 listUser·p0.9999: 26.963 ms/op
                 listUser·p1.00:   27.591 ms/op

Iteration   3: 4.036 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   7.022 ms/op
                 listUser·p0.999:  19.059 ms/op
                 listUser·p0.9999: 21.699 ms/op
                 listUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238991
  mean =      4.016 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2324 
    [ 2.500,  5.000) = 211085 
    [ 5.000,  7.500) = 23930 
    [ 7.500, 10.000) = 1067 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 127 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 60 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      5.071 ms/op
     p(95.0000) =      5.833 ms/op
     p(99.0000) =      7.135 ms/op
     p(99.9000) =     15.745 ms/op
     p(99.9900) =     26.345 ms/op
     p(99.9990) =     27.448 ms/op
     p(99.9999) =     27.591 ms/op
    p(100.0000) =     27.591 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.502 ± 2.737  ops/ms
ClientGrpc.existUser                       thrpt       3  11.074 ± 1.676  ops/ms
ClientGrpc.getUser                         thrpt       3  10.584 ± 1.049  ops/ms
ClientGrpc.listUser                        thrpt       3   7.867 ± 4.220  ops/ms
ClientGrpc.createUser                       avgt       3   3.047 ± 0.428   ms/op
ClientGrpc.existUser                        avgt       3   2.898 ± 0.244   ms/op
ClientGrpc.getUser                          avgt       3   3.043 ± 0.458   ms/op
ClientGrpc.listUser                         avgt       3   3.981 ± 0.410   ms/op
ClientGrpc.createUser                     sample  313909   3.060 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.558           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.027           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.702           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.007           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.842           ms/op
ClientGrpc.existUser                      sample  328753   2.921 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.553           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.896           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.424           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.522           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.200           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.465           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.874           ms/op
ClientGrpc.getUser                        sample  312429   3.075 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.566           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.641           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.867           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.743           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.651           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.431           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  238991   4.016 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.071           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.833           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.135           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.745           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.591           ms/op
