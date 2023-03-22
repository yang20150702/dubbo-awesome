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
# Warmup Iteration   1: 4.663 ops/ms
# Warmup Iteration   2: 9.750 ops/ms
# Warmup Iteration   3: 10.245 ops/ms
Iteration   1: 10.728 ops/ms
Iteration   2: 10.936 ops/ms
Iteration   3: 10.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.764 ±(99.9%) 2.870 ops/ms [Average]
  (min, avg, max) = (10.628, 10.764, 10.936), stdev = 0.157
  CI (99.9%): [7.894, 13.634] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 8.300 ops/ms
# Warmup Iteration   2: 11.089 ops/ms
# Warmup Iteration   3: 11.265 ops/ms
Iteration   1: 11.168 ops/ms
Iteration   2: 11.036 ops/ms
Iteration   3: 11.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.111 ±(99.9%) 1.243 ops/ms [Average]
  (min, avg, max) = (11.036, 11.111, 11.168), stdev = 0.068
  CI (99.9%): [9.868, 12.354] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.854 ops/ms
# Warmup Iteration   2: 10.150 ops/ms
# Warmup Iteration   3: 10.694 ops/ms
Iteration   1: 10.474 ops/ms
Iteration   2: 10.679 ops/ms
Iteration   3: 10.637 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.596 ±(99.9%) 1.975 ops/ms [Average]
  (min, avg, max) = (10.474, 10.596, 10.679), stdev = 0.108
  CI (99.9%): [8.621, 12.572] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.580 ops/ms
# Warmup Iteration   2: 7.781 ops/ms
# Warmup Iteration   3: 8.240 ops/ms
Iteration   1: 8.175 ops/ms
Iteration   2: 7.987 ops/ms
Iteration   3: 8.410 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.191 ±(99.9%) 3.874 ops/ms [Average]
  (min, avg, max) = (7.987, 8.191, 8.410), stdev = 0.212
  CI (99.9%): [4.317, 12.064] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.053 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.999 ±(99.9%) 0.002 ms/op
Iteration   1: 2.956 ±(99.9%) 0.003 ms/op
Iteration   2: 2.896 ±(99.9%) 0.003 ms/op
Iteration   3: 2.900 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.917 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (2.896, 2.917, 2.956), stdev = 0.034
  CI (99.9%): [2.306, 3.528] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.947 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.904 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.827 ±(99.9%) 0.004 ms/op
Iteration   1: 2.832 ±(99.9%) 0.003 ms/op
Iteration   2: 2.801 ±(99.9%) 0.004 ms/op
Iteration   3: 2.835 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.822 ±(99.9%) 0.341 ms/op [Average]
  (min, avg, max) = (2.801, 2.822, 2.835), stdev = 0.019
  CI (99.9%): [2.481, 3.164] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.131 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.215 ±(99.9%) 0.005 ms/op
Iteration   2: 2.978 ±(99.9%) 0.004 ms/op
Iteration   3: 2.911 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.035 ±(99.9%) 2.911 ms/op [Average]
  (min, avg, max) = (2.911, 3.035, 3.215), stdev = 0.160
  CI (99.9%): [0.123, 5.946] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.056 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.088 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.027 ms/op
Iteration   1: 3.917 ±(99.9%) 0.006 ms/op
Iteration   2: 3.897 ±(99.9%) 0.019 ms/op
Iteration   3: 3.911 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.908 ±(99.9%) 0.192 ms/op [Average]
  (min, avg, max) = (3.897, 3.908, 3.917), stdev = 0.011
  CI (99.9%): [3.716, 4.101] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.949 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.036 ±(99.9%) 0.005 ms/op
Iteration   1: 2.969 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.546 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  6.644 ms/op
                 createUser·p0.9999: 16.109 ms/op
                 createUser·p1.00:   17.039 ms/op

Iteration   2: 2.985 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.674 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.502 ms/op
                 createUser·p0.95:   3.678 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.256 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   12.812 ms/op

Iteration   3: 2.965 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.715 ms/op
                 createUser·p0.50:   2.957 ms/op
                 createUser·p0.90:   3.478 ms/op
                 createUser·p0.95:   3.670 ms/op
                 createUser·p0.99:   4.325 ms/op
                 createUser·p0.999:  8.815 ms/op
                 createUser·p0.9999: 14.818 ms/op
                 createUser·p1.00:   15.155 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 322910
  mean =      2.973 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1351 
    [ 1.250,  2.500) = 33811 
    [ 2.500,  3.750) = 273413 
    [ 3.750,  5.000) = 13315 
    [ 5.000,  6.250) = 434 
    [ 6.250,  7.500) = 246 
    [ 7.500,  8.750) = 83 
    [ 8.750, 10.000) = 34 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 78 
    [12.500, 13.750) = 43 
    [13.750, 15.000) = 38 
    [15.000, 16.250) = 31 
    [16.250, 17.500) = 8 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.758 ms/op
     p(99.9900) =     15.150 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     17.039 ms/op
    p(100.0000) =     17.039 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.869 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.880 ±(99.9%) 0.006 ms/op
Iteration   1: 2.877 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  6.029 ms/op
                 existUser·p0.9999: 12.003 ms/op
                 existUser·p1.00:   12.272 ms/op

Iteration   2: 2.907 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.727 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.371 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  5.956 ms/op
                 existUser·p0.9999: 20.676 ms/op
                 existUser·p1.00:   20.906 ms/op

Iteration   3: 2.898 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.685 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.416 ms/op
                 existUser·p0.999:  7.627 ms/op
                 existUser·p0.9999: 14.580 ms/op
                 existUser·p1.00:   14.926 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 331918
  mean =      2.894 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37078 
    [ 2.500,  5.000) = 293744 
    [ 5.000,  7.500) = 845 
    [ 7.500, 10.000) = 91 
    [10.000, 12.500) = 75 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.685 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.338 ms/op
     p(95.0000) =      3.551 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =      6.317 ms/op
     p(99.9900) =     14.913 ms/op
     p(99.9990) =     20.852 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.984 ±(99.9%) 0.006 ms/op
Iteration   1: 2.977 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.355 ms/op
                 getUser·p0.95:   3.564 ms/op
                 getUser·p0.99:   4.133 ms/op
                 getUser·p0.999:  6.537 ms/op
                 getUser·p0.9999: 14.676 ms/op
                 getUser·p1.00:   15.073 ms/op

Iteration   2: 3.015 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.601 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   4.227 ms/op
                 getUser·p0.999:  7.634 ms/op
                 getUser·p0.9999: 12.812 ms/op
                 getUser·p1.00:   13.337 ms/op

Iteration   3: 2.959 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.609 ms/op
                 getUser·p0.50:   2.937 ms/op
                 getUser·p0.90:   3.482 ms/op
                 getUser·p0.95:   3.736 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.274 ms/op
                 getUser·p0.9999: 15.178 ms/op
                 getUser·p1.00:   15.614 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321582
  mean =      2.983 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1230 
    [ 1.250,  2.500) = 25504 
    [ 2.500,  3.750) = 281701 
    [ 3.750,  5.000) = 12150 
    [ 5.000,  6.250) = 425 
    [ 6.250,  7.500) = 267 
    [ 7.500,  8.750) = 79 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 88 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.473 ms/op
     p(95.0000) =      3.686 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      7.373 ms/op
     p(99.9900) =     14.778 ms/op
     p(99.9990) =     15.436 ms/op
     p(99.9999) =     15.614 ms/op
    p(100.0000) =     15.614 ms/op


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
# Warmup Iteration   1: 4.559 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.056 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.888 ±(99.9%) 0.010 ms/op
Iteration   1: 3.943 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.208 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.776 ms/op
                 listUser·p0.95:   5.775 ms/op
                 listUser·p0.99:   6.758 ms/op
                 listUser·p0.999:  14.563 ms/op
                 listUser·p0.9999: 22.265 ms/op
                 listUser·p1.00:   23.364 ms/op

Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.204 ms/op
                 listUser·p0.50:   3.822 ms/op
                 listUser·p0.90:   4.964 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   7.160 ms/op
                 listUser·p0.999:  13.266 ms/op
                 listUser·p0.9999: 15.712 ms/op
                 listUser·p1.00:   16.105 ms/op

Iteration   3: 3.905 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.823 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.850 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   6.767 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 18.383 ms/op
                 listUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243385
  mean =      3.943 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3840 
    [ 2.500,  5.000) = 218052 
    [ 5.000,  7.500) = 20276 
    [ 7.500, 10.000) = 748 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.823 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.866 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      6.889 ms/op
     p(99.9000) =     14.330 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     23.335 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.764 ± 2.870  ops/ms
ClientGrpc.existUser                       thrpt       3  11.111 ± 1.243  ops/ms
ClientGrpc.getUser                         thrpt       3  10.596 ± 1.975  ops/ms
ClientGrpc.listUser                        thrpt       3   8.191 ± 3.874  ops/ms
ClientGrpc.createUser                       avgt       3   2.917 ± 0.611   ms/op
ClientGrpc.existUser                        avgt       3   2.822 ± 0.341   ms/op
ClientGrpc.getUser                          avgt       3   3.035 ± 2.911   ms/op
ClientGrpc.listUser                         avgt       3   3.908 ± 0.192   ms/op
ClientGrpc.createUser                     sample  322910   2.973 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.546           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.966           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.502           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.703           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.758           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          15.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.039           ms/op
ClientGrpc.existUser                      sample  331918   2.894 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.685           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.338           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.551           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.317           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.913           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.906           ms/op
ClientGrpc.getUser                        sample  321582   2.983 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.601           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.974           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.473           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.373           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.778           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          15.614           ms/op
ClientGrpc.listUser                       sample  243385   3.943 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.823           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.797           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.866           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.652           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.330           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.676           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.364           ms/op
