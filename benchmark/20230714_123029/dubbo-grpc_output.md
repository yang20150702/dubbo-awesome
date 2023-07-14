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
# Warmup Iteration   1: 4.954 ops/ms
# Warmup Iteration   2: 8.958 ops/ms
# Warmup Iteration   3: 10.266 ops/ms
Iteration   1: 10.459 ops/ms
Iteration   2: 10.530 ops/ms
Iteration   3: 10.573 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.520 ±(99.9%) 1.048 ops/ms [Average]
  (min, avg, max) = (10.459, 10.520, 10.573), stdev = 0.057
  CI (99.9%): [9.473, 11.568] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.407 ops/ms
# Warmup Iteration   2: 10.768 ops/ms
# Warmup Iteration   3: 11.089 ops/ms
Iteration   1: 11.143 ops/ms
Iteration   2: 11.211 ops/ms
Iteration   3: 11.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.161 ±(99.9%) 0.793 ops/ms [Average]
  (min, avg, max) = (11.131, 11.161, 11.211), stdev = 0.043
  CI (99.9%): [10.369, 11.954] (assumes normal distribution)


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
# Warmup Iteration   1: 7.433 ops/ms
# Warmup Iteration   2: 10.453 ops/ms
# Warmup Iteration   3: 10.669 ops/ms
Iteration   1: 10.881 ops/ms
Iteration   2: 10.585 ops/ms
Iteration   3: 10.752 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.739 ±(99.9%) 2.711 ops/ms [Average]
  (min, avg, max) = (10.585, 10.739, 10.881), stdev = 0.149
  CI (99.9%): [8.028, 13.450] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.722 ops/ms
# Warmup Iteration   2: 7.966 ops/ms
# Warmup Iteration   3: 8.469 ops/ms
Iteration   1: 8.271 ops/ms
Iteration   2: 8.238 ops/ms
Iteration   3: 8.131 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.213 ±(99.9%) 1.332 ops/ms [Average]
  (min, avg, max) = (8.131, 8.213, 8.271), stdev = 0.073
  CI (99.9%): [6.881, 9.545] (assumes normal distribution)


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
# Warmup Iteration   1: 4.013 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.003 ms/op
Iteration   1: 2.973 ±(99.9%) 0.002 ms/op
Iteration   2: 3.023 ±(99.9%) 0.002 ms/op
Iteration   3: 3.026 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.007 ±(99.9%) 0.541 ms/op [Average]
  (min, avg, max) = (2.973, 3.007, 3.026), stdev = 0.030
  CI (99.9%): [2.467, 3.548] (assumes normal distribution)


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
# Warmup Iteration   1: 3.652 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.774 ±(99.9%) 0.003 ms/op
Iteration   1: 2.878 ±(99.9%) 0.003 ms/op
Iteration   2: 2.838 ±(99.9%) 0.003 ms/op
Iteration   3: 2.879 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.865 ±(99.9%) 0.428 ms/op [Average]
  (min, avg, max) = (2.838, 2.865, 2.879), stdev = 0.023
  CI (99.9%): [2.437, 3.293] (assumes normal distribution)


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
# Warmup Iteration   1: 3.591 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 3.046 ±(99.9%) 0.003 ms/op
Iteration   2: 3.055 ±(99.9%) 0.003 ms/op
Iteration   3: 3.009 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.037 ±(99.9%) 0.445 ms/op [Average]
  (min, avg, max) = (3.009, 3.037, 3.055), stdev = 0.024
  CI (99.9%): [2.592, 3.481] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 3.917 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 4.038 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.902 ±(99.9%) 0.010 ms/op
Iteration   1: 3.866 ±(99.9%) 0.025 ms/op
Iteration   2: 3.882 ±(99.9%) 0.041 ms/op
Iteration   3: 3.895 ±(99.9%) 0.040 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.881 ±(99.9%) 0.269 ms/op [Average]
  (min, avg, max) = (3.866, 3.881, 3.895), stdev = 0.015
  CI (99.9%): [3.612, 4.150] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.205 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.039 ±(99.9%) 0.006 ms/op
Iteration   1: 2.967 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.743 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.490 ms/op
                 createUser·p0.95:   3.752 ms/op
                 createUser·p0.99:   4.497 ms/op
                 createUser·p0.999:  9.847 ms/op
                 createUser·p0.9999: 13.894 ms/op
                 createUser·p1.00:   14.172 ms/op

Iteration   2: 2.994 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   3.002 ms/op
                 createUser·p0.90:   3.535 ms/op
                 createUser·p0.95:   3.719 ms/op
                 createUser·p0.99:   4.219 ms/op
                 createUser·p0.999:  6.930 ms/op
                 createUser·p0.9999: 22.883 ms/op
                 createUser·p1.00:   23.298 ms/op

Iteration   3: 3.014 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.719 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.465 ms/op
                 createUser·p0.95:   3.637 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  11.074 ms/op
                 createUser·p0.9999: 26.542 ms/op
                 createUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 320808
  mean =      2.992 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28638 
    [ 2.500,  5.000) = 290908 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 169 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.707 ms/op
     p(99.0000) =      4.333 ms/op
     p(99.9000) =      9.847 ms/op
     p(99.9900) =     25.497 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.771 ms/op
    p(100.0000) =     26.771 ms/op


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
# Warmup Iteration   1: 3.744 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.008 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.906 ±(99.9%) 0.005 ms/op
Iteration   1: 2.949 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.539 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.088 ms/op
                 existUser·p0.999:  6.013 ms/op
                 existUser·p0.9999: 14.243 ms/op
                 existUser·p1.00:   14.680 ms/op

Iteration   2: 2.903 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.765 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  5.757 ms/op
                 existUser·p0.9999: 20.742 ms/op
                 existUser·p1.00:   21.725 ms/op

Iteration   3: 2.883 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.489 ms/op
                 existUser·p0.50:   2.871 ms/op
                 existUser·p0.90:   3.244 ms/op
                 existUser·p0.95:   3.416 ms/op
                 existUser·p0.99:   4.112 ms/op
                 existUser·p0.999:  6.522 ms/op
                 existUser·p0.9999: 23.527 ms/op
                 existUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329531
  mean =      2.911 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33702 
    [ 2.500,  5.000) = 295151 
    [ 5.000,  7.500) = 516 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =      5.931 ms/op
     p(99.9900) =     21.783 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


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
# Warmup Iteration   1: 3.957 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.063 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.006 ms/op
Iteration   1: 2.971 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.654 ms/op
                 getUser·p0.50:   2.982 ms/op
                 getUser·p0.90:   3.457 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.825 ms/op
                 getUser·p0.9999: 19.956 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.708 ms/op
                 getUser·p0.50:   2.994 ms/op
                 getUser·p0.90:   3.473 ms/op
                 getUser·p0.95:   3.645 ms/op
                 getUser·p0.99:   4.149 ms/op
                 getUser·p0.999:  6.652 ms/op
                 getUser·p0.9999: 16.144 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 2.998 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.599 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.559 ms/op
                 getUser·p0.95:   3.781 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  6.123 ms/op
                 getUser·p0.9999: 15.726 ms/op
                 getUser·p1.00:   17.105 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 321020
  mean =      2.989 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26833 
    [ 2.500,  5.000) = 292997 
    [ 5.000,  7.500) = 937 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.284 ms/op
     p(99.9000) =      6.783 ms/op
     p(99.9900) =     18.870 ms/op
     p(99.9990) =     20.244 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


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
# Warmup Iteration   1: 5.438 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 3.998 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
Iteration   1: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   3.785 ms/op
                 listUser·p0.90:   4.907 ms/op
                 listUser·p0.95:   5.358 ms/op
                 listUser·p0.99:   6.783 ms/op
                 listUser·p0.999:  12.749 ms/op
                 listUser·p0.9999: 19.127 ms/op
                 listUser·p1.00:   19.399 ms/op

Iteration   2: 3.856 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.903 ms/op
                 listUser·p0.50:   3.748 ms/op
                 listUser·p0.90:   4.293 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.073 ms/op
                 listUser·p0.9999: 21.191 ms/op
                 listUser·p1.00:   22.020 ms/op

Iteration   3: 3.925 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.636 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  16.843 ms/op
                 listUser·p0.9999: 20.287 ms/op
                 listUser·p1.00:   20.939 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245930
  mean =      3.905 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4843 
    [ 2.500,  5.000) = 221103 
    [ 5.000,  7.500) = 18832 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 173 
    [12.500, 15.000) = 85 
    [15.000, 17.500) = 109 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 43 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.903 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.833 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.758 ms/op
     p(99.9000) =     15.270 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     21.912 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.520 ± 1.048  ops/ms
ClientGrpc.existUser                       thrpt       3  11.161 ± 0.793  ops/ms
ClientGrpc.getUser                         thrpt       3  10.739 ± 2.711  ops/ms
ClientGrpc.listUser                        thrpt       3   8.213 ± 1.332  ops/ms
ClientGrpc.createUser                       avgt       3   3.007 ± 0.541   ms/op
ClientGrpc.existUser                        avgt       3   2.865 ± 0.428   ms/op
ClientGrpc.getUser                          avgt       3   3.037 ± 0.445   ms/op
ClientGrpc.listUser                         avgt       3   3.881 ± 0.269   ms/op
ClientGrpc.createUser                     sample  320808   2.992 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.639           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.990           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.498           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.707           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.333           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.847           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.497           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.771           ms/op
ClientGrpc.existUser                      sample  329531   2.911 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.489           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.391           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.604           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.153           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.783           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.527           ms/op
ClientGrpc.getUser                        sample  321020   2.989 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.599           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.494           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.699           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.284           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.783           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.870           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.349           ms/op
ClientGrpc.listUser                       sample  245930   3.905 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.903           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.764           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.833           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.758           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.270           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.709           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.020           ms/op
