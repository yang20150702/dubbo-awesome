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
# Warmup Iteration   1: 2.083 ops/ms
# Warmup Iteration   2: 4.922 ops/ms
# Warmup Iteration   3: 6.187 ops/ms
Iteration   1: 6.470 ops/ms
Iteration   2: 6.462 ops/ms
Iteration   3: 6.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.478 ±(99.9%) 0.385 ops/ms [Average]
  (min, avg, max) = (6.462, 6.478, 6.502), stdev = 0.021
  CI (99.9%): [6.093, 6.863] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 4.241 ops/ms
# Warmup Iteration   2: 6.397 ops/ms
# Warmup Iteration   3: 6.865 ops/ms
Iteration   1: 7.158 ops/ms
Iteration   2: 7.004 ops/ms
Iteration   3: 7.247 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.136 ±(99.9%) 2.247 ops/ms [Average]
  (min, avg, max) = (7.004, 7.136, 7.247), stdev = 0.123
  CI (99.9%): [4.889, 9.383] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 3.908 ops/ms
# Warmup Iteration   2: 5.738 ops/ms
# Warmup Iteration   3: 6.477 ops/ms
Iteration   1: 6.403 ops/ms
Iteration   2: 6.676 ops/ms
Iteration   3: 6.689 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.589 ±(99.9%) 2.947 ops/ms [Average]
  (min, avg, max) = (6.403, 6.589, 6.689), stdev = 0.162
  CI (99.9%): [3.642, 9.536] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.094 ops/ms
# Warmup Iteration   2: 4.674 ops/ms
# Warmup Iteration   3: 4.984 ops/ms
Iteration   1: 4.955 ops/ms
Iteration   2: 5.096 ops/ms
Iteration   3: 5.211 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.087 ±(99.9%) 2.347 ops/ms [Average]
  (min, avg, max) = (4.955, 5.087, 5.211), stdev = 0.129
  CI (99.9%): [2.741, 7.434] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.613 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.483 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.271 ±(99.9%) 0.006 ms/op
Iteration   1: 4.905 ±(99.9%) 0.004 ms/op
Iteration   2: 4.962 ±(99.9%) 0.003 ms/op
Iteration   3: 4.994 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.954 ±(99.9%) 0.825 ms/op [Average]
  (min, avg, max) = (4.905, 4.954, 4.994), stdev = 0.045
  CI (99.9%): [4.129, 5.779] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 7.045 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.816 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.672 ±(99.9%) 0.012 ms/op
Iteration   1: 4.596 ±(99.9%) 0.003 ms/op
Iteration   2: 4.627 ±(99.9%) 0.003 ms/op
Iteration   3: 4.591 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.604 ±(99.9%) 0.353 ms/op [Average]
  (min, avg, max) = (4.591, 4.604, 4.627), stdev = 0.019
  CI (99.9%): [4.252, 4.957] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 7.937 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 5.242 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.079 ±(99.9%) 0.015 ms/op
Iteration   1: 4.802 ±(99.9%) 0.003 ms/op
Iteration   2: 4.905 ±(99.9%) 0.003 ms/op
Iteration   3: 4.889 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.865 ±(99.9%) 1.016 ms/op [Average]
  (min, avg, max) = (4.802, 4.865, 4.905), stdev = 0.056
  CI (99.9%): [3.849, 5.881] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.260 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 6.646 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 6.287 ±(99.9%) 0.017 ms/op
Iteration   1: 6.267 ±(99.9%) 0.016 ms/op
Iteration   2: 6.487 ±(99.9%) 0.024 ms/op
Iteration   3: 6.249 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.334 ±(99.9%) 2.422 ms/op [Average]
  (min, avg, max) = (6.249, 6.334, 6.487), stdev = 0.133
  CI (99.9%): [3.912, 8.757] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.152 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.576 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.287 ±(99.9%) 0.016 ms/op
Iteration   1: 4.964 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.243 ms/op
                 createUser·p0.50:   4.776 ms/op
                 createUser·p0.90:   6.169 ms/op
                 createUser·p0.95:   6.775 ms/op
                 createUser·p0.99:   9.485 ms/op
                 createUser·p0.999:  15.322 ms/op
                 createUser·p0.9999: 28.891 ms/op
                 createUser·p1.00:   29.131 ms/op

Iteration   2: 5.001 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.296 ms/op
                 createUser·p0.50:   4.833 ms/op
                 createUser·p0.90:   6.201 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  17.696 ms/op
                 createUser·p0.9999: 21.922 ms/op
                 createUser·p1.00:   22.381 ms/op

Iteration   3: 4.934 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.200 ms/op
                 createUser·p0.50:   4.760 ms/op
                 createUser·p0.90:   6.308 ms/op
                 createUser·p0.95:   6.996 ms/op
                 createUser·p0.99:   9.396 ms/op
                 createUser·p0.999:  16.716 ms/op
                 createUser·p0.9999: 20.993 ms/op
                 createUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 193331
  mean =      4.966 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1812 
    [ 2.500,  5.000) = 113143 
    [ 5.000,  7.500) = 72614 
    [ 7.500, 10.000) = 4502 
    [10.000, 12.500) = 790 
    [12.500, 15.000) = 231 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 67 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      4.784 ms/op
     p(90.0000) =      6.226 ms/op
     p(95.0000) =      6.865 ms/op
     p(99.0000) =      9.306 ms/op
     p(99.9000) =     15.510 ms/op
     p(99.9900) =     28.224 ms/op
     p(99.9990) =     29.131 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.950 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.968 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.758 ±(99.9%) 0.014 ms/op
Iteration   1: 4.566 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   1.118 ms/op
                 existUser·p0.50:   4.448 ms/op
                 existUser·p0.90:   5.734 ms/op
                 existUser·p0.95:   6.234 ms/op
                 existUser·p0.99:   7.995 ms/op
                 existUser·p0.999:  13.121 ms/op
                 existUser·p0.9999: 38.335 ms/op
                 existUser·p1.00:   38.797 ms/op

Iteration   2: 4.500 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.863 ms/op
                 existUser·p0.50:   4.424 ms/op
                 existUser·p0.90:   5.718 ms/op
                 existUser·p0.95:   6.226 ms/op
                 existUser·p0.99:   7.807 ms/op
                 existUser·p0.999:  11.040 ms/op
                 existUser·p0.9999: 25.771 ms/op
                 existUser·p1.00:   26.214 ms/op

Iteration   3: 4.467 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.114 ms/op
                 existUser·p0.50:   4.366 ms/op
                 existUser·p0.90:   5.595 ms/op
                 existUser·p0.95:   6.078 ms/op
                 existUser·p0.99:   7.561 ms/op
                 existUser·p0.999:  13.415 ms/op
                 existUser·p0.9999: 29.131 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 212788
  mean =      4.510 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7230 
    [ 2.500,  5.000) = 151319 
    [ 5.000,  7.500) = 51588 
    [ 7.500, 10.000) = 2072 
    [10.000, 12.500) = 350 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 11 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 19 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      4.407 ms/op
     p(90.0000) =      5.685 ms/op
     p(95.0000) =      6.185 ms/op
     p(99.0000) =      7.816 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     37.159 ms/op
     p(99.9990) =     38.789 ms/op
     p(99.9999) =     38.797 ms/op
    p(100.0000) =     38.797 ms/op


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
# Warmup Iteration   1: 7.579 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 5.391 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.091 ±(99.9%) 0.017 ms/op
Iteration   1: 4.993 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.019 ms/op
                 getUser·p0.50:   4.817 ms/op
                 getUser·p0.90:   6.324 ms/op
                 getUser·p0.95:   7.037 ms/op
                 getUser·p0.99:   9.234 ms/op
                 getUser·p0.999:  14.204 ms/op
                 getUser·p0.9999: 15.765 ms/op
                 getUser·p1.00:   15.925 ms/op

Iteration   2: 5.063 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.290 ms/op
                 getUser·p0.50:   4.923 ms/op
                 getUser·p0.90:   6.316 ms/op
                 getUser·p0.95:   6.914 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  12.679 ms/op
                 getUser·p0.9999: 24.871 ms/op
                 getUser·p1.00:   24.904 ms/op

Iteration   3: 4.820 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.163 ms/op
                 getUser·p0.50:   4.727 ms/op
                 getUser·p0.90:   5.964 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   7.782 ms/op
                 getUser·p0.999:  12.824 ms/op
                 getUser·p0.9999: 21.094 ms/op
                 getUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 193498
  mean =      4.957 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1870 
    [ 2.500,  5.000) = 109740 
    [ 5.000,  7.500) = 77123 
    [ 7.500, 10.000) = 3884 
    [10.000, 12.500) = 636 
    [12.500, 15.000) = 146 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.019 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.193 ms/op
     p(95.0000) =      6.758 ms/op
     p(99.0000) =      8.733 ms/op
     p(99.9000) =     13.369 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.904 ms/op
     p(99.9999) =     24.904 ms/op
    p(100.0000) =     24.904 ms/op


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
# Warmup Iteration   1: 9.600 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 6.867 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 6.355 ±(99.9%) 0.025 ms/op
Iteration   1: 6.372 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.696 ms/op
                 listUser·p0.50:   6.029 ms/op
                 listUser·p0.90:   8.454 ms/op
                 listUser·p0.95:   9.552 ms/op
                 listUser·p0.99:   12.042 ms/op
                 listUser·p0.999:  17.859 ms/op
                 listUser·p0.9999: 25.417 ms/op
                 listUser·p1.00:   25.985 ms/op

Iteration   2: 6.154 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.087 ms/op
                 listUser·p0.50:   5.865 ms/op
                 listUser·p0.90:   7.930 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.682 ms/op
                 listUser·p0.999:  21.299 ms/op
                 listUser·p0.9999: 26.791 ms/op
                 listUser·p1.00:   27.099 ms/op

Iteration   3: 6.072 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.765 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   7.963 ms/op
                 listUser·p0.95:   9.142 ms/op
                 listUser·p0.99:   12.291 ms/op
                 listUser·p0.999:  20.677 ms/op
                 listUser·p0.9999: 25.509 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 154854
  mean =      6.197 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 28272 
    [ 5.000,  7.500) = 103569 
    [ 7.500, 10.000) = 18108 
    [10.000, 12.500) = 3648 
    [12.500, 15.000) = 749 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 84 
    [20.000, 22.500) = 94 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 56 

  Percentiles, ms/op:
      p(0.0000) =      1.696 ms/op
     p(50.0000) =      5.874 ms/op
     p(90.0000) =      8.135 ms/op
     p(95.0000) =      9.257 ms/op
     p(99.0000) =     12.026 ms/op
     p(99.9000) =     20.518 ms/op
     p(99.9900) =     25.985 ms/op
     p(99.9990) =     26.991 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.478 ± 0.385  ops/ms
ClientGrpc.existUser                       thrpt       3   7.136 ± 2.247  ops/ms
ClientGrpc.getUser                         thrpt       3   6.589 ± 2.947  ops/ms
ClientGrpc.listUser                        thrpt       3   5.087 ± 2.347  ops/ms
ClientGrpc.createUser                       avgt       3   4.954 ± 0.825   ms/op
ClientGrpc.existUser                        avgt       3   4.604 ± 0.353   ms/op
ClientGrpc.getUser                          avgt       3   4.865 ± 1.016   ms/op
ClientGrpc.listUser                         avgt       3   6.334 ± 2.422   ms/op
ClientGrpc.createUser                     sample  193331   4.966 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.200           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.784           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.226           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.865           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           9.306           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          15.510           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          28.224           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          29.131           ms/op
ClientGrpc.existUser                      sample  212788   4.510 ± 0.009   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.863           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.685           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.185           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.816           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.747           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          37.159           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          38.797           ms/op
ClientGrpc.getUser                        sample  193498   4.957 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.019           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.825           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.193           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.758           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.733           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.369           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.150           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.904           ms/op
ClientGrpc.listUser                       sample  154854   6.197 ± 0.014   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.696           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.135           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.257           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.026           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.518           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.985           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.099           ms/op
