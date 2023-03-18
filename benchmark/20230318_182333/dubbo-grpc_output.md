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
# Warmup Iteration   1: 3.949 ops/ms
# Warmup Iteration   2: 7.974 ops/ms
# Warmup Iteration   3: 8.894 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.549 ops/ms
Iteration   3: 9.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.675 ±(99.9%) 2.233 ops/ms [Average]
  (min, avg, max) = (9.549, 9.675, 9.793), stdev = 0.122
  CI (99.9%): [7.442, 11.909] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.272 ops/ms
# Warmup Iteration   2: 8.811 ops/ms
# Warmup Iteration   3: 9.858 ops/ms
Iteration   1: 9.228 ops/ms
Iteration   2: 9.978 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.822 ±(99.9%) 9.730 ops/ms [Average]
  (min, avg, max) = (9.228, 9.822, 10.260), stdev = 0.533
  CI (99.9%): [0.092, 19.552] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.686 ops/ms
# Warmup Iteration   2: 8.696 ops/ms
# Warmup Iteration   3: 8.771 ops/ms
Iteration   1: 9.029 ops/ms
Iteration   2: 9.112 ops/ms
Iteration   3: 9.561 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.234 ±(99.9%) 5.220 ops/ms [Average]
  (min, avg, max) = (9.029, 9.234, 9.561), stdev = 0.286
  CI (99.9%): [4.014, 14.455] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.659 ops/ms
# Warmup Iteration   2: 6.709 ops/ms
# Warmup Iteration   3: 6.876 ops/ms
Iteration   1: 7.022 ops/ms
Iteration   2: 7.319 ops/ms
Iteration   3: 7.337 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.226 ±(99.9%) 3.229 ops/ms [Average]
  (min, avg, max) = (7.022, 7.226, 7.337), stdev = 0.177
  CI (99.9%): [3.997, 10.455] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.984 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.564 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.511 ±(99.9%) 0.003 ms/op
Iteration   1: 3.606 ±(99.9%) 0.003 ms/op
Iteration   2: 3.485 ±(99.9%) 0.002 ms/op
Iteration   3: 3.394 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.495 ±(99.9%) 1.944 ms/op [Average]
  (min, avg, max) = (3.394, 3.495, 3.606), stdev = 0.107
  CI (99.9%): [1.551, 5.439] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.203 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.181 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.193 ±(99.9%) 0.003 ms/op
Iteration   1: 3.363 ±(99.9%) 0.003 ms/op
Iteration   2: 3.340 ±(99.9%) 0.003 ms/op
Iteration   3: 3.273 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.325 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (3.273, 3.325, 3.363), stdev = 0.047
  CI (99.9%): [2.465, 4.186] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.713 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.525 ±(99.9%) 0.006 ms/op
Iteration   1: 3.484 ±(99.9%) 0.002 ms/op
Iteration   2: 3.580 ±(99.9%) 0.004 ms/op
Iteration   3: 3.482 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.515 ±(99.9%) 1.026 ms/op [Average]
  (min, avg, max) = (3.482, 3.515, 3.580), stdev = 0.056
  CI (99.9%): [2.489, 4.541] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.072 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.724 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.523 ±(99.9%) 0.013 ms/op
Iteration   1: 4.704 ±(99.9%) 0.018 ms/op
Iteration   2: 4.478 ±(99.9%) 0.012 ms/op
Iteration   3: 4.513 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.565 ±(99.9%) 2.214 ms/op [Average]
  (min, avg, max) = (4.478, 4.565, 4.704), stdev = 0.121
  CI (99.9%): [2.350, 6.779] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.085 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.755 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.007 ms/op
Iteration   1: 3.586 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.811 ms/op
                 createUser·p0.50:   3.539 ms/op
                 createUser·p0.90:   4.202 ms/op
                 createUser·p0.95:   4.522 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  10.690 ms/op
                 createUser·p0.9999: 14.354 ms/op
                 createUser·p1.00:   17.433 ms/op

Iteration   2: 3.403 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.973 ms/op
                 createUser·p0.95:   4.211 ms/op
                 createUser·p0.99:   5.087 ms/op
                 createUser·p0.999:  8.959 ms/op
                 createUser·p0.9999: 16.993 ms/op
                 createUser·p1.00:   17.859 ms/op

Iteration   3: 3.300 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.297 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  8.267 ms/op
                 createUser·p0.9999: 18.579 ms/op
                 createUser·p1.00:   19.071 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 280332
  mean =      3.426 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 210 
    [ 1.250,  2.500) = 10557 
    [ 2.500,  3.750) = 205291 
    [ 3.750,  5.000) = 59885 
    [ 5.000,  6.250) = 3225 
    [ 6.250,  7.500) = 593 
    [ 7.500,  8.750) = 256 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 13 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 28 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 62 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.297 ms/op
     p(50.0000) =      3.387 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.358 ms/op
     p(99.9000) =      8.989 ms/op
     p(99.9900) =     17.825 ms/op
     p(99.9990) =     18.953 ms/op
     p(99.9999) =     19.071 ms/op
    p(100.0000) =     19.071 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.574 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.393 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.200 ±(99.9%) 0.007 ms/op
Iteration   1: 3.288 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.169 ms/op
                 existUser·p0.50:   3.240 ms/op
                 existUser·p0.90:   3.879 ms/op
                 existUser·p0.95:   4.088 ms/op
                 existUser·p0.99:   4.948 ms/op
                 existUser·p0.999:  9.576 ms/op
                 existUser·p0.9999: 15.030 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.811 ms/op
                 existUser·p0.50:   3.133 ms/op
                 existUser·p0.90:   3.727 ms/op
                 existUser·p0.95:   3.944 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  7.640 ms/op
                 existUser·p0.9999: 18.151 ms/op
                 existUser·p1.00:   18.579 ms/op

Iteration   3: 3.224 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.957 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   3.903 ms/op
                 existUser·p0.99:   5.145 ms/op
                 existUser·p0.999:  9.159 ms/op
                 existUser·p0.9999: 34.865 ms/op
                 existUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 297450
  mean =      3.227 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12842 
    [ 2.500,  5.000) = 281867 
    [ 5.000,  7.500) = 2365 
    [ 7.500, 10.000) = 175 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.811 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      4.923 ms/op
     p(99.9000) =      8.971 ms/op
     p(99.9900) =     32.678 ms/op
     p(99.9990) =     35.258 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


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
# Warmup Iteration   1: 5.204 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.674 ±(99.9%) 0.009 ms/op
Iteration   1: 3.507 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.899 ms/op
                 getUser·p0.50:   3.445 ms/op
                 getUser·p0.90:   4.190 ms/op
                 getUser·p0.95:   4.538 ms/op
                 getUser·p0.99:   5.728 ms/op
                 getUser·p0.999:  10.690 ms/op
                 getUser·p0.9999: 18.281 ms/op
                 getUser·p1.00:   18.645 ms/op

Iteration   2: 3.412 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.387 ms/op
                 getUser·p0.90:   3.990 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.218 ms/op
                 getUser·p0.999:  8.898 ms/op
                 getUser·p0.9999: 16.273 ms/op
                 getUser·p1.00:   16.613 ms/op

Iteration   3: 3.537 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.967 ms/op
                 getUser·p0.50:   3.473 ms/op
                 getUser·p0.90:   4.194 ms/op
                 getUser·p0.95:   4.506 ms/op
                 getUser·p0.99:   5.759 ms/op
                 getUser·p0.999:  12.707 ms/op
                 getUser·p0.9999: 18.020 ms/op
                 getUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 275322
  mean =      3.484 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 104 
    [ 1.250,  2.500) = 9160 
    [ 2.500,  3.750) = 196525 
    [ 3.750,  5.000) = 64047 
    [ 5.000,  6.250) = 4053 
    [ 6.250,  7.500) = 772 
    [ 7.500,  8.750) = 220 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 120 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 53 
    [17.500, 18.750) = 49 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.432 ms/op
     p(90.0000) =      4.125 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     10.644 ms/op
     p(99.9900) =     17.957 ms/op
     p(99.9990) =     19.652 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


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
# Warmup Iteration   1: 6.345 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 4.704 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.493 ±(99.9%) 0.015 ms/op
Iteration   1: 4.341 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.481 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   5.120 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   7.594 ms/op
                 listUser·p0.999:  16.559 ms/op
                 listUser·p0.9999: 22.106 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   2: 4.384 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   4.202 ms/op
                 listUser·p0.90:   5.472 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   7.955 ms/op
                 listUser·p0.999:  15.041 ms/op
                 listUser·p0.9999: 17.478 ms/op
                 listUser·p1.00:   18.252 ms/op

Iteration   3: 4.423 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.931 ms/op
                 listUser·p0.50:   4.194 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.521 ms/op
                 listUser·p0.99:   8.094 ms/op
                 listUser·p0.999:  19.197 ms/op
                 listUser·p0.9999: 30.033 ms/op
                 listUser·p1.00:   30.540 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 219049
  mean =      4.382 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 888 
    [ 2.500,  5.000) = 184553 
    [ 5.000,  7.500) = 30387 
    [ 7.500, 10.000) = 2487 
    [10.000, 12.500) = 200 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.931 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.448 ms/op
     p(95.0000) =      6.201 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     16.612 ms/op
     p(99.9900) =     29.298 ms/op
     p(99.9990) =     30.429 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.675 ± 2.233  ops/ms
ClientGrpc.existUser                       thrpt       3   9.822 ± 9.730  ops/ms
ClientGrpc.getUser                         thrpt       3   9.234 ± 5.220  ops/ms
ClientGrpc.listUser                        thrpt       3   7.226 ± 3.229  ops/ms
ClientGrpc.createUser                       avgt       3   3.495 ± 1.944   ms/op
ClientGrpc.existUser                        avgt       3   3.325 ± 0.861   ms/op
ClientGrpc.getUser                          avgt       3   3.515 ± 1.026   ms/op
ClientGrpc.listUser                         avgt       3   4.565 ± 2.214   ms/op
ClientGrpc.createUser                     sample  280332   3.426 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.297           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.387           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.059           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.358           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.989           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.825           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          19.071           ms/op
ClientGrpc.existUser                      sample  297450   3.227 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.811           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.183           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.777           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.990           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.923           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.971           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          32.678           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.324           ms/op
ClientGrpc.getUser                        sample  275322   3.484 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.899           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.125           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.440           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.587           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.644           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.957           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.923           ms/op
ClientGrpc.listUser                       sample  219049   4.382 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.931           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.194           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.448           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.938           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.612           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          29.298           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          30.540           ms/op
