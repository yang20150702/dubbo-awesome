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
# Warmup Iteration   1: 2.276 ops/ms
# Warmup Iteration   2: 5.770 ops/ms
# Warmup Iteration   3: 7.433 ops/ms
Iteration   1: 7.620 ops/ms
Iteration   2: 7.919 ops/ms
Iteration   3: 7.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.765 ±(99.9%) 2.733 ops/ms [Average]
  (min, avg, max) = (7.620, 7.765, 7.919), stdev = 0.150
  CI (99.9%): [5.032, 10.497] (assumes normal distribution)


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
# Warmup Iteration   1: 4.760 ops/ms
# Warmup Iteration   2: 7.609 ops/ms
# Warmup Iteration   3: 8.188 ops/ms
Iteration   1: 8.138 ops/ms
Iteration   2: 8.104 ops/ms
Iteration   3: 8.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.144 ±(99.9%) 0.780 ops/ms [Average]
  (min, avg, max) = (8.104, 8.144, 8.189), stdev = 0.043
  CI (99.9%): [7.364, 8.924] (assumes normal distribution)


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
# Warmup Iteration   1: 4.527 ops/ms
# Warmup Iteration   2: 7.145 ops/ms
# Warmup Iteration   3: 7.552 ops/ms
Iteration   1: 7.784 ops/ms
Iteration   2: 7.652 ops/ms
Iteration   3: 7.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.666 ±(99.9%) 2.045 ops/ms [Average]
  (min, avg, max) = (7.561, 7.666, 7.784), stdev = 0.112
  CI (99.9%): [5.621, 9.711] (assumes normal distribution)


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
# Warmup Iteration   1: 3.990 ops/ms
# Warmup Iteration   2: 5.640 ops/ms
# Warmup Iteration   3: 6.160 ops/ms
Iteration   1: 6.219 ops/ms
Iteration   2: 6.030 ops/ms
Iteration   3: 6.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.127 ±(99.9%) 1.728 ops/ms [Average]
  (min, avg, max) = (6.030, 6.127, 6.219), stdev = 0.095
  CI (99.9%): [4.399, 7.856] (assumes normal distribution)


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
# Warmup Iteration   1: 7.062 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.005 ms/op
Iteration   1: 3.910 ±(99.9%) 0.004 ms/op
Iteration   2: 3.977 ±(99.9%) 0.003 ms/op
Iteration   3: 3.980 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.956 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (3.910, 3.956, 3.980), stdev = 0.039
  CI (99.9%): [3.240, 4.671] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 5.981 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.102 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.011 ms/op
Iteration   1: 3.785 ±(99.9%) 0.005 ms/op
Iteration   2: 3.772 ±(99.9%) 0.003 ms/op
Iteration   3: 3.873 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.810 ±(99.9%) 1.007 ms/op [Average]
  (min, avg, max) = (3.772, 3.810, 3.873), stdev = 0.055
  CI (99.9%): [2.803, 4.817] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.146 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.563 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.995 ±(99.9%) 0.004 ms/op
Iteration   2: 4.020 ±(99.9%) 0.003 ms/op
Iteration   3: 3.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.997 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (3.977, 3.997, 4.020), stdev = 0.021
  CI (99.9%): [3.606, 4.388] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.720 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 5.711 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.297 ±(99.9%) 0.017 ms/op
Iteration   1: 5.187 ±(99.9%) 0.013 ms/op
Iteration   2: 5.220 ±(99.9%) 0.008 ms/op
Iteration   3: 5.055 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.154 ±(99.9%) 1.596 ms/op [Average]
  (min, avg, max) = (5.055, 5.154, 5.220), stdev = 0.087
  CI (99.9%): [3.558, 6.750] (assumes normal distribution)


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
# Warmup Iteration   1: 6.116 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.528 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.087 ±(99.9%) 0.013 ms/op
Iteration   1: 4.156 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.022 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   5.276 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.946 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 20.366 ms/op
                 createUser·p1.00:   23.462 ms/op

Iteration   2: 4.217 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.073 ms/op
                 createUser·p0.50:   4.100 ms/op
                 createUser·p0.90:   5.226 ms/op
                 createUser·p0.95:   5.702 ms/op
                 createUser·p0.99:   7.796 ms/op
                 createUser·p0.999:  11.993 ms/op
                 createUser·p0.9999: 26.549 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 4.106 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.000 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   5.136 ms/op
                 createUser·p0.95:   5.652 ms/op
                 createUser·p0.99:   8.176 ms/op
                 createUser·p0.999:  18.121 ms/op
                 createUser·p0.9999: 22.486 ms/op
                 createUser·p1.00:   23.200 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 230793
  mean =      4.159 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6607 
    [ 2.500,  5.000) = 192079 
    [ 5.000,  7.500) = 29309 
    [ 7.500, 10.000) = 1930 
    [10.000, 12.500) = 541 
    [12.500, 15.000) = 129 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      4.026 ms/op
     p(90.0000) =      5.218 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     14.041 ms/op
     p(99.9900) =     22.673 ms/op
     p(99.9990) =     26.719 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 6.072 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 4.099 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.844 ±(99.9%) 0.012 ms/op
Iteration   1: 3.833 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.744 ms/op
                 existUser·p0.90:   4.727 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  12.386 ms/op
                 existUser·p0.9999: 15.772 ms/op
                 existUser·p1.00:   15.991 ms/op

Iteration   2: 3.712 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   4.964 ms/op
                 existUser·p0.99:   6.259 ms/op
                 existUser·p0.999:  12.222 ms/op
                 existUser·p0.9999: 18.186 ms/op
                 existUser·p1.00:   18.678 ms/op

Iteration   3: 3.726 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.997 ms/op
                 existUser·p0.50:   3.666 ms/op
                 existUser·p0.90:   4.678 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.685 ms/op
                 existUser·p0.999:  10.945 ms/op
                 existUser·p0.9999: 23.710 ms/op
                 existUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 255478
  mean =      3.756 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14497 
    [ 2.500,  5.000) = 226101 
    [ 5.000,  7.500) = 13183 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 347 
    [12.500, 15.000) = 100 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.756 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.636 ms/op
     p(99.9000) =     11.862 ms/op
     p(99.9900) =     20.021 ms/op
     p(99.9990) =     24.197 ms/op
     p(99.9999) =     24.216 ms/op
    p(100.0000) =     24.216 ms/op


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
# Warmup Iteration   1: 6.529 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.471 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.013 ms/op
Iteration   1: 4.082 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.079 ms/op
                 getUser·p0.50:   3.957 ms/op
                 getUser·p0.90:   5.095 ms/op
                 getUser·p0.95:   5.612 ms/op
                 getUser·p0.99:   7.828 ms/op
                 getUser·p0.999:  14.308 ms/op
                 getUser·p0.9999: 17.285 ms/op
                 getUser·p1.00:   17.859 ms/op

Iteration   2: 4.151 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.906 ms/op
                 getUser·p0.50:   4.030 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.513 ms/op
                 getUser·p0.99:   7.078 ms/op
                 getUser·p0.999:  12.075 ms/op
                 getUser·p0.9999: 23.560 ms/op
                 getUser·p1.00:   24.150 ms/op

Iteration   3: 4.207 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.128 ms/op
                 getUser·p0.50:   4.076 ms/op
                 getUser·p0.90:   5.194 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   7.971 ms/op
                 getUser·p0.999:  13.093 ms/op
                 getUser·p0.9999: 29.976 ms/op
                 getUser·p1.00:   30.376 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 231342
  mean =      4.146 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5212 
    [ 2.500,  5.000) = 197475 
    [ 5.000,  7.500) = 26208 
    [ 7.500, 10.000) = 1819 
    [10.000, 12.500) = 374 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.906 ms/op
     p(50.0000) =      4.014 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.587 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     12.763 ms/op
     p(99.9900) =     29.478 ms/op
     p(99.9990) =     30.257 ms/op
     p(99.9999) =     30.376 ms/op
    p(100.0000) =     30.376 ms/op


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
# Warmup Iteration   1: 7.695 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 5.521 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.173 ±(99.9%) 0.019 ms/op
Iteration   1: 5.055 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.877 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.423 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.486 ms/op
                 listUser·p0.999:  15.913 ms/op
                 listUser·p0.9999: 20.186 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   2: 5.220 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.386 ms/op
                 listUser·p0.50:   4.940 ms/op
                 listUser·p0.90:   6.816 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   9.929 ms/op
                 listUser·p0.999:  20.339 ms/op
                 listUser·p0.9999: 29.822 ms/op
                 listUser·p1.00:   30.245 ms/op

Iteration   3: 5.226 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.362 ms/op
                 listUser·p0.50:   4.948 ms/op
                 listUser·p0.90:   6.791 ms/op
                 listUser·p0.95:   7.758 ms/op
                 listUser·p0.99:   10.142 ms/op
                 listUser·p0.999:  20.081 ms/op
                 listUser·p0.9999: 32.661 ms/op
                 listUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 185854
  mean =      5.166 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 326 
    [ 2.500,  5.000) = 101607 
    [ 5.000,  7.500) = 73806 
    [ 7.500, 10.000) = 8398 
    [10.000, 12.500) = 1219 
    [12.500, 15.000) = 187 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 27 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.877 ms/op
     p(50.0000) =      4.907 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.619 ms/op
     p(99.0000) =      9.896 ms/op
     p(99.9000) =     18.322 ms/op
     p(99.9900) =     32.126 ms/op
     p(99.9990) =     34.041 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.765 ± 2.733  ops/ms
ClientGrpc.existUser                       thrpt       3   8.144 ± 0.780  ops/ms
ClientGrpc.getUser                         thrpt       3   7.666 ± 2.045  ops/ms
ClientGrpc.listUser                        thrpt       3   6.127 ± 1.728  ops/ms
ClientGrpc.createUser                       avgt       3   3.956 ± 0.716   ms/op
ClientGrpc.existUser                        avgt       3   3.810 ± 1.007   ms/op
ClientGrpc.getUser                          avgt       3   3.997 ± 0.391   ms/op
ClientGrpc.listUser                         avgt       3   5.154 ± 1.596   ms/op
ClientGrpc.createUser                     sample  230793   4.159 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           1.000           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.026           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.218           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.685           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.946           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          14.041           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  255478   3.756 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.756           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.653           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.104           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.636           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.862           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.021           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.216           ms/op
ClientGrpc.getUser                        sample  231342   4.146 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.906           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.136           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.610           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.763           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          29.478           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.376           ms/op
ClientGrpc.listUser                       sample  185854   5.166 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.877           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.907           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.619           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.896           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.322           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          32.126           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          34.210           ms/op
