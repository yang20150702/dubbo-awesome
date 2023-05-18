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
# Warmup Iteration   1: 2.134 ops/ms
# Warmup Iteration   2: 5.978 ops/ms
# Warmup Iteration   3: 7.452 ops/ms
Iteration   1: 7.820 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 7.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.944 ±(99.9%) 4.011 ops/ms [Average]
  (min, avg, max) = (7.814, 7.944, 8.198), stdev = 0.220
  CI (99.9%): [3.933, 11.955] (assumes normal distribution)


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
# Warmup Iteration   1: 4.802 ops/ms
# Warmup Iteration   2: 7.771 ops/ms
# Warmup Iteration   3: 8.374 ops/ms
Iteration   1: 8.570 ops/ms
Iteration   2: 8.539 ops/ms
Iteration   3: 8.469 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.526 ±(99.9%) 0.950 ops/ms [Average]
  (min, avg, max) = (8.469, 8.526, 8.570), stdev = 0.052
  CI (99.9%): [7.576, 9.476] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 7.076 ops/ms
# Warmup Iteration   3: 7.643 ops/ms
Iteration   1: 7.923 ops/ms
Iteration   2: 7.925 ops/ms
Iteration   3: 8.008 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.952 ±(99.9%) 0.880 ops/ms [Average]
  (min, avg, max) = (7.923, 7.952, 8.008), stdev = 0.048
  CI (99.9%): [7.073, 8.832] (assumes normal distribution)


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
# Warmup Iteration   1: 4.025 ops/ms
# Warmup Iteration   2: 5.573 ops/ms
# Warmup Iteration   3: 6.102 ops/ms
Iteration   1: 6.431 ops/ms
Iteration   2: 6.311 ops/ms
Iteration   3: 6.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.314 ±(99.9%) 2.116 ops/ms [Average]
  (min, avg, max) = (6.199, 6.314, 6.431), stdev = 0.116
  CI (99.9%): [4.198, 8.430] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.804 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.397 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.271 ±(99.9%) 0.008 ms/op
Iteration   1: 4.139 ±(99.9%) 0.003 ms/op
Iteration   2: 3.929 ±(99.9%) 0.003 ms/op
Iteration   3: 3.999 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.022 ±(99.9%) 1.950 ms/op [Average]
  (min, avg, max) = (3.929, 4.022, 4.139), stdev = 0.107
  CI (99.9%): [2.072, 5.973] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.465 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.003 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.789 ±(99.9%) 0.004 ms/op
Iteration   1: 3.861 ±(99.9%) 0.004 ms/op
Iteration   2: 3.759 ±(99.9%) 0.003 ms/op
Iteration   3: 3.673 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.765 ±(99.9%) 1.719 ms/op [Average]
  (min, avg, max) = (3.673, 3.765, 3.861), stdev = 0.094
  CI (99.9%): [2.046, 5.484] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.474 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.023 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.873 ±(99.9%) 0.006 ms/op
Iteration   1: 4.014 ±(99.9%) 0.007 ms/op
Iteration   2: 4.002 ±(99.9%) 0.003 ms/op
Iteration   3: 3.991 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.002 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (3.991, 4.002, 4.014), stdev = 0.012
  CI (99.9%): [3.790, 4.214] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.445 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 5.044 ±(99.9%) 0.022 ms/op
Iteration   1: 5.039 ±(99.9%) 0.024 ms/op
Iteration   2: 5.043 ±(99.9%) 0.025 ms/op
Iteration   3: 4.998 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.027 ±(99.9%) 0.460 ms/op [Average]
  (min, avg, max) = (4.998, 5.027, 5.043), stdev = 0.025
  CI (99.9%): [4.566, 5.487] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 6.097 ±(99.9%) 0.068 ms/op
# Warmup Iteration   2: 4.523 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.013 ms/op
Iteration   1: 4.178 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.143 ms/op
                 createUser·p0.50:   4.043 ms/op
                 createUser·p0.90:   5.267 ms/op
                 createUser·p0.95:   5.751 ms/op
                 createUser·p0.99:   7.938 ms/op
                 createUser·p0.999:  12.532 ms/op
                 createUser·p0.9999: 15.145 ms/op
                 createUser·p1.00:   15.598 ms/op

Iteration   2: 4.046 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.896 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.112 ms/op
                 createUser·p0.95:   5.521 ms/op
                 createUser·p0.99:   7.778 ms/op
                 createUser·p0.999:  13.144 ms/op
                 createUser·p0.9999: 20.426 ms/op
                 createUser·p1.00:   22.282 ms/op

Iteration   3: 3.994 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.954 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.333 ms/op
                 createUser·p0.99:   7.511 ms/op
                 createUser·p0.999:  13.267 ms/op
                 createUser·p0.9999: 28.901 ms/op
                 createUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 235784
  mean =      4.071 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6230 
    [ 2.500,  5.000) = 202331 
    [ 5.000,  7.500) = 24443 
    [ 7.500, 10.000) = 2028 
    [10.000, 12.500) = 442 
    [12.500, 15.000) = 193 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.896 ms/op
     p(50.0000) =      3.936 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      7.784 ms/op
     p(99.9000) =     12.930 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     29.259 ms/op
     p(99.9999) =     29.295 ms/op
    p(100.0000) =     29.295 ms/op


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
# Warmup Iteration   1: 5.716 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 4.039 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.914 ±(99.9%) 0.010 ms/op
Iteration   1: 3.828 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.990 ms/op
                 existUser·p0.50:   3.719 ms/op
                 existUser·p0.90:   4.809 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   6.849 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 14.959 ms/op
                 existUser·p1.00:   16.040 ms/op

Iteration   2: 3.827 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.935 ms/op
                 existUser·p0.50:   3.711 ms/op
                 existUser·p0.90:   4.760 ms/op
                 existUser·p0.95:   5.145 ms/op
                 existUser·p0.99:   6.734 ms/op
                 existUser·p0.999:  11.255 ms/op
                 existUser·p0.9999: 18.131 ms/op
                 existUser·p1.00:   20.611 ms/op

Iteration   3: 3.767 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.620 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   7.479 ms/op
                 existUser·p0.999:  11.616 ms/op
                 existUser·p0.9999: 21.038 ms/op
                 existUser·p1.00:   21.660 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 251947
  mean =      3.807 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10227 
    [ 2.500,  5.000) = 225272 
    [ 5.000,  7.500) = 14413 
    [ 7.500, 10.000) = 1436 
    [10.000, 12.500) = 398 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.169 ms/op
     p(99.0000) =      7.074 ms/op
     p(99.9000) =     11.616 ms/op
     p(99.9900) =     19.052 ms/op
     p(99.9990) =     21.411 ms/op
     p(99.9999) =     21.660 ms/op
    p(100.0000) =     21.660 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.000 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.255 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.001 ±(99.9%) 0.013 ms/op
Iteration   1: 3.968 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.772 ms/op
                 getUser·p0.50:   3.875 ms/op
                 getUser·p0.90:   4.956 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.594 ms/op
                 getUser·p0.999:  12.803 ms/op
                 getUser·p0.9999: 16.537 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 3.993 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.106 ms/op
                 getUser·p0.50:   3.891 ms/op
                 getUser·p0.90:   4.981 ms/op
                 getUser·p0.95:   5.448 ms/op
                 getUser·p0.99:   7.451 ms/op
                 getUser·p0.999:  12.288 ms/op
                 getUser·p0.9999: 21.690 ms/op
                 getUser·p1.00:   24.052 ms/op

Iteration   3: 4.000 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.963 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   5.390 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  12.191 ms/op
                 getUser·p0.9999: 19.235 ms/op
                 getUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 240681
  mean =      3.987 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8811 
    [ 2.500,  5.000) = 209067 
    [ 5.000,  7.500) = 20328 
    [ 7.500, 10.000) = 1811 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 58 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.772 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.964 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     12.288 ms/op
     p(99.9900) =     19.396 ms/op
     p(99.9990) =     22.929 ms/op
     p(99.9999) =     24.052 ms/op
    p(100.0000) =     24.052 ms/op


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
# Warmup Iteration   1: 7.830 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 5.556 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.995 ±(99.9%) 0.017 ms/op
Iteration   1: 5.073 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.642 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   6.865 ms/op
                 listUser·p0.95:   7.774 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  14.877 ms/op
                 listUser·p0.9999: 19.389 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   2: 5.083 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.612 ms/op
                 listUser·p0.50:   4.817 ms/op
                 listUser·p0.90:   6.603 ms/op
                 listUser·p0.95:   7.545 ms/op
                 listUser·p0.99:   10.011 ms/op
                 listUser·p0.999:  16.745 ms/op
                 listUser·p0.9999: 22.207 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 5.069 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.395 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.636 ms/op
                 listUser·p0.95:   7.528 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  20.152 ms/op
                 listUser·p0.9999: 27.452 ms/op
                 listUser·p1.00:   27.853 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189137
  mean =      5.075 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 347 
    [ 2.500,  5.000) = 112448 
    [ 5.000,  7.500) = 65863 
    [ 7.500, 10.000) = 8734 
    [10.000, 12.500) = 1166 
    [12.500, 15.000) = 316 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 73 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.395 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      6.701 ms/op
     p(95.0000) =      7.627 ms/op
     p(99.0000) =      9.847 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     25.469 ms/op
     p(99.9990) =     27.765 ms/op
     p(99.9999) =     27.853 ms/op
    p(100.0000) =     27.853 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.944 ± 4.011  ops/ms
ClientGrpc.existUser                       thrpt       3   8.526 ± 0.950  ops/ms
ClientGrpc.getUser                         thrpt       3   7.952 ± 0.880  ops/ms
ClientGrpc.listUser                        thrpt       3   6.314 ± 2.116  ops/ms
ClientGrpc.createUser                       avgt       3   4.022 ± 1.950   ms/op
ClientGrpc.existUser                        avgt       3   3.765 ± 1.719   ms/op
ClientGrpc.getUser                          avgt       3   4.002 ± 0.212   ms/op
ClientGrpc.listUser                         avgt       3   5.027 ± 0.460   ms/op
ClientGrpc.createUser                     sample  235784   4.071 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.896           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.936           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.095           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.554           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.784           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.930           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.296           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.295           ms/op
ClientGrpc.existUser                      sample  251947   3.807 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.935           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.735           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.169           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.074           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.616           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.052           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.660           ms/op
ClientGrpc.getUser                        sample  240681   3.987 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.772           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.883           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.415           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.545           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.288           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.396           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.052           ms/op
ClientGrpc.listUser                       sample  189137   5.075 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.395           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.801           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.701           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.847           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.777           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.469           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.853           ms/op
